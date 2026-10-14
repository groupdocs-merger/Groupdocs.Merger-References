---
title: "ISplitOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Interfaz para las opciones de división."
type: docs
weight: 33
url: /es/nodejs-java/com.groupdocs.merger.domain.options.interfaces/isplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface ISplitOptions extends IPageOptions
```

Interfaz para las opciones de división.
## Métodos

| Método | Descripción |
| --- | --- |
| [getMode()](#getMode--) | Obtiene el modo para dividir páginas. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Valida las opciones de división. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Obtiene la ruta completa del archivo del documento dividido por índice con la extensión definida. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Delegado que define el método para crear el flujo dividido de salida. |
### getMode() {#getMode--}
```
public abstract int getMode()
```


Obtiene el modo para dividir páginas.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


Valida las opciones de división.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo de la clase [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public abstract String getPathByIndex(int index, String extension)
```


Obtiene la ruta completa del archivo del documento dividido por índice con la extensión definida.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | Índice del documento dividido. |
| extensión | java.lang.String | Extensión del archivo. |

**Returns:**
java.lang.String - La ruta completa del archivo.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public abstract SplitStreamFactory getSplitStreamFactory()
```


Delegado que define el método para crear el flujo dividido de salida.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
