---
title: "IImportDocumentOptions"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Διεπαφή για εισαγωγή του ενσωματωμένου εγγράφου."
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface IImportDocumentOptions extends IOptions
```

Διεπαφή για εισαγωγή του ενσωματωμένου εγγράφου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getObjectData()](#getObjectData--) | Τα δεδομένα του ενσωματωμένου αντικειμένου. |
| [getExtension()](#getExtension--) | Η επέκταση του ενσωματωμένου αντικειμένου. |
| [getPageNumber()](#getPageNumber--) | Ο αριθμός σελίδας για την εισαγωγή του ενσωματωμένου αντικειμένου. |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


Τα δεδομένα του ενσωματωμένου αντικειμένου.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


Η επέκταση του ενσωματωμένου αντικειμένου.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Ο αριθμός σελίδας για την εισαγωγή του ενσωματωμένου αντικειμένου.

**Returns:**
int
