---
title: "PageStreamFactory"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "출력 페이지 미리보기 스트림을 생성하는 메서드를 정의하는 인터페이스."
type: docs
weight: 10
url: /ko/nodejs-java/com.groupdocs.merger.domain.common/pagestreamfactory/
---```
public interface PageStreamFactory
```

Interface that defines method to create output page preview stream.
## Methods

| Method | Description |
| --- | --- |
| [createPageStream(int pageNumber)](#createPageStream-int-) | Method to create output page preview stream. |
| [closePageStream(int pageNumber, OutputStream pageStream)](#closePageStream-int-java.io.OutputStream-) | Method to release output page preview stream |
### createPageStream(int pageNumber) {#createPageStream-int-}
```
public abstract OutputStream createPageStream(int pageNumber)
```


Method to create output page preview stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int |  |

**Returns:**
java.io.OutputStream
### closePageStream(int pageNumber, OutputStream pageStream) {#closePageStream-int-java.io.OutputStream-}
```
public abstract void closePageStream(int pageNumber, OutputStream pageStream)
```


Method to release output page preview stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int |  |
| pageStream | java.io.OutputStream |  |

