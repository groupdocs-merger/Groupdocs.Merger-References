---
title: "IImportDocumentOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Schnittstelle für den Import des eingebetteten Dokuments."
type: docs
weight: 13
url: /de/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface IImportDocumentOptions extends IOptions
```

Schnittstelle für den Import des eingebetteten Dokuments.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getObjectData()](#getObjectData--) | Die Daten des eingebetteten Objekts. |
| [getExtension()](#getExtension--) | Die Erweiterung des eingebetteten Objekts. |
| [getPageNumber()](#getPageNumber--) | Die Seitenzahl für das Einfügen des eingebetteten Objekts. |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


Die Daten des eingebetteten Objekts.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


Die Erweiterung des eingebetteten Objekts.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Die Seitenzahl für das Einfügen des eingebetteten Objekts.

**Returns:**
int
