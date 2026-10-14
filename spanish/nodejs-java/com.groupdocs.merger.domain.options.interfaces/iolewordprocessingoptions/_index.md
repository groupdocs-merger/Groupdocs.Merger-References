---
title: "IOleWordProcessingOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Interfaz para opciones de importación del documento incrustado a Word processing mediante OLE."
type: docs
weight: 20
url: /es/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleWordProcessingOptions extends IImportDocumentOptions, ISizeOptions
```

Interfaz para opciones de importación del documento incrustado a Word processing mediante OLE.
## Métodos

| Método | Descripción |
| --- | --- |
| [getLeft()](#getLeft--) | La coordenada izquierda de la imagen del objeto Ole. |
| [setLeft(int value)](#setLeft-int-) | La coordenada izquierda de la imagen del objeto Ole. |
| [getTop()](#getTop--) | La coordenada superior de la imagen del objeto Ole. |
| [setTop(int value)](#setTop-int-) | La coordenada superior de la imagen del objeto Ole. |
| [getImageData()](#getImageData--) | Los datos de la imagen del objeto Ole. |
### getLeft() {#getLeft--}
```
public abstract int getLeft()
```


La coordenada izquierda de la imagen del objeto Ole.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public abstract void setLeft(int value)
```


La coordenada izquierda de la imagen del objeto Ole.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public abstract int getTop()
```


La coordenada superior de la imagen del objeto Ole.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public abstract void setTop(int value)
```


La coordenada superior de la imagen del objeto Ole.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Los datos de la imagen del objeto Ole.

**Returns:**
byte[]
