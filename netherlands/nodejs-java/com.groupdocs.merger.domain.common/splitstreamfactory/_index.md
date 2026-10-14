---
title: "SplitStreamFactory"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Interface die de methode definieert om een uitvoer-splitstroom te maken."
type: docs
weight: 11
url: /nl/nodejs-java/com.groupdocs.merger.domain.common/splitstreamfactory/
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

