---
title: "SplitStreamFactory"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "출력 분할 스트림을 생성하는 메서드를 정의하는 인터페이스."
type: docs
weight: 11
url: /ko/nodejs-java/com.groupdocs.merger.domain.common/splitstreamfactory/
---```
public interface SplitStreamFactory
```

Interface that defines method to create output split stream.
## Methods

| Method | Description |
| --- | --- |
| [createSplitStream(int pageNumber)](#createSplitStream-int-) | Method to create output page preview stream. |
| [closeSplitStream(int pageNumber, OutputStream pageStream)](#closeSplitStream-int-java.io.OutputStream-) | Method to release output page preview stream |
### createSplitStream(int pageNumber) {#createSplitStream-int-}
```
public abstract OutputStream createSplitStream(int pageNumber)
```


Method to create output page preview stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int |  |

**Returns:**
java.io.OutputStream
### closeSplitStream(int pageNumber, OutputStream pageStream) {#closeSplitStream-int-java.io.OutputStream-}
```
public abstract void closeSplitStream(int pageNumber, OutputStream pageStream)
```


Method to release output page preview stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int |  |
| pageStream | java.io.OutputStream |  |

