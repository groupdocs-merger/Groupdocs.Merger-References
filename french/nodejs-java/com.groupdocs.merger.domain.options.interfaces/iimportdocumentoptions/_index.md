---
title: "IImportDocumentOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Interface pour l'importation du document intégré."
type: docs
weight: 13
url: /fr/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface IImportDocumentOptions extends IOptions
```

Interface pour l'importation du document intégré.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getObjectData()](#getObjectData--) | Les données de l'objet intégré. |
| [getExtension()](#getExtension--) | L'extension de l'objet intégré. |
| [getPageNumber()](#getPageNumber--) | Le numéro de page pour l'insertion de l'objet intégré. |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


Les données de l'objet intégré.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


L'extension de l'objet intégré.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Le numéro de page pour l'insertion de l'objet intégré.

**Returns:**
int
