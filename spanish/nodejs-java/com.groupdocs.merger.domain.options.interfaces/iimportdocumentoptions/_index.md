---
title: "IImportDocumentOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Interfaz para la importación del documento incrustado."
type: docs
weight: 13
url: /es/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface IImportDocumentOptions extends IOptions
```

Interfaz para la importación del documento incrustado.
## Métodos

| Método | Descripción |
| --- | --- |
| [getObjectData()](#getObjectData--) | Los datos del objeto incrustado. |
| [getExtension()](#getExtension--) | La extensión del objeto incrustado. |
| [getPageNumber()](#getPageNumber--) | El número de página para insertar el objeto incrustado. |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


Los datos del objeto incrustado.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


La extensión del objeto incrustado.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


El número de página para insertar el objeto incrustado.

**Returns:**
int
