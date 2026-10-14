---
title: "IOleDiagramOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Interfaz para opciones de importación del documento incrustado a Diagram mediante OLE."
type: docs
weight: 17
url: /es/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleDiagramOptions extends IImportDocumentOptions, ISizeOptions
```

Interfaz para opciones de importación del documento incrustado a Diagram mediante OLE.
## Métodos

| Método | Descripción |
| --- | --- |
| [getX()](#getX--) | La coordenada X del pin de la forma del objeto incrustado (centro de rotación) en relación con la página. |
| [setX(int value)](#setX-int-) | La coordenada X del pin de la forma del objeto incrustado (centro de rotación) en relación con la página. |
| [getY()](#getY--) | La coordenada Y del pin de la forma del objeto incrustado (centro de rotación) en relación con la página. |
| [setY(int value)](#setY-int-) | La coordenada Y del pin de la forma del objeto incrustado (centro de rotación) en relación con la página. |
| [getImageData()](#getImageData--) | Los datos de imagen del objeto incrustado. |
### getX() {#getX--}
```
public abstract int getX()
```


La coordenada X del pin de la forma del objeto incrustado (centro de rotación) en relación con la página.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


La coordenada X del pin de la forma del objeto incrustado (centro de rotación) en relación con la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


La coordenada Y del pin de la forma del objeto incrustado (centro de rotación) en relación con la página.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


La coordenada Y del pin de la forma del objeto incrustado (centro de rotación) en relación con la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Los datos de imagen del objeto incrustado.

**Returns:**
byte[]
