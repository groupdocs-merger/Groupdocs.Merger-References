---
title: IImportDocumentOptions
second_title: GroupDocs.Merger for Java API Reference
description: Interface for import of the embedded document.
type: docs
weight: 13
url: /java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface IImportDocumentOptions extends IOptions
```

Interface for import of the embedded document.
## Methods

| Method | Description |
| --- | --- |
| [getObjectData()](#getObjectData--) | The data of the embedded object. |
| [getExtension()](#getExtension--) | The extension of the embedded object. |
| [getPageNumber()](#getPageNumber--) | The page number for inserting of the embedded object. |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


The data of the embedded object.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


The extension of the embedded object.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


The page number for inserting of the embedded object.

**Returns:**
int
