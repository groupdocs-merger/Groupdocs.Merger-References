---
title: IOleWordProcessingOptions
second_title: GroupDocs.Merger for Java API Reference
description:  Interface for import options of the embedded document to Word processing via OLE.
type: docs
weight: 20
url: /java/com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleWordProcessingOptions extends IImportDocumentOptions, ISizeOptions
```

Interface for import options of the embedded document to Word processing via OLE.
## Methods

| Method | Description |
| --- | --- |
| [getLeft()](#getLeft--) | The left coordinate of the Ole object image. |
| [setLeft(int value)](#setLeft-int-) | The left coordinate of the Ole object image. |
| [getTop()](#getTop--) | The top coordinate of the Ole object image. |
| [setTop(int value)](#setTop-int-) | The top coordinate of the Ole object image. |
| [getImageData()](#getImageData--) | The data of the Ole object image. |
### getLeft() {#getLeft--}
```
public abstract int getLeft()
```


The left coordinate of the Ole object image.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public abstract void setLeft(int value)
```


The left coordinate of the Ole object image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public abstract int getTop()
```


The top coordinate of the Ole object image.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public abstract void setTop(int value)
```


The top coordinate of the Ole object image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


The data of the Ole object image.

**Returns:**
byte[]
