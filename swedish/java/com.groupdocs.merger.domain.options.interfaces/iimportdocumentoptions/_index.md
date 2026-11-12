---
title: "IImportDocumentOptions"
second_title: "GroupDocs.Merger för Java API-referens"
description: "Gränssnitt för import av det inbäddade dokumentet."
type: docs
weight: 13
url: /sv/java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface IImportDocumentOptions extends IOptions
```

Gränssnitt för import av det inbäddade dokumentet.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getObjectData()](#getObjectData--) | Data för det inbäddade objektet. |
| [getExtension()](#getExtension--) | Filändelsen för det inbäddade objektet. |
| [getPageNumber()](#getPageNumber--) | Sidnumret för infogning av det inbäddade objektet. |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


Data för det inbäddade objektet.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


Filändelsen för det inbäddade objektet.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Sidnumret för infogning av det inbäddade objektet.

**Returns:**
int
