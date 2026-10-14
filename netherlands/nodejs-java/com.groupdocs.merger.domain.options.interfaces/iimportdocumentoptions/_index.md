---
title: "IImportDocumentOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Interface voor import van het ingesloten document."
type: docs
weight: 13
url: /nl/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface IImportDocumentOptions extends IOptions
```

Interface voor import van het ingesloten document.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getObjectData()](#getObjectData--) | De gegevens van het ingesloten object. |
| [getExtension()](#getExtension--) | De extensie van het ingesloten object. |
| [getPageNumber()](#getPageNumber--) | Het paginanummer voor het invoegen van het ingesloten object. |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


De gegevens van het ingesloten object.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


De extensie van het ingesloten object.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Het paginanummer voor het invoegen van het ingesloten object.

**Returns:**
int
