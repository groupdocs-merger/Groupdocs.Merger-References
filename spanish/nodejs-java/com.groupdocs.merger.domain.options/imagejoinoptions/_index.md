---
title: "ImageJoinOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Las opciones de unión de imágenes."
type: docs
weight: 13
url: /es/nodejs-java/com.groupdocs.merger.domain.options/imagejoinoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/iimagejoinoptions)
```
public class ImageJoinOptions implements IImageJoinOptions
```

Las opciones de unión de imágenes.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ImageJoinOptions()](#ImageJoinOptions--) | Inicializa una nueva instancia de la clase [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(FileType fileType)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-) | Inicializa una nueva instancia de la clase [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(int imageJoinMode)](#ImageJoinOptions-int-) | Inicializa una nueva instancia de la clase [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(FileType fileType, int imageJoinMode)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-) | Inicializa una nueva instancia de la clase [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getType()](#getType--) | El tipo de archivo de imagen. |
| [getMode()](#getMode--) | El modo de unión de imágenes. |
### ImageJoinOptions() {#ImageJoinOptions--}
```
public ImageJoinOptions()
```


Inicializa una nueva instancia de la clase [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

### ImageJoinOptions(FileType fileType) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public ImageJoinOptions(FileType fileType)
```


Inicializa una nueva instancia de la clase [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo de imagen. |

### ImageJoinOptions(int imageJoinMode) {#ImageJoinOptions-int-}
```
public ImageJoinOptions(int imageJoinMode)
```


Inicializa una nueva instancia de la clase [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageJoinMode | int | El modo de unión de imágenes. |

### ImageJoinOptions(FileType fileType, int imageJoinMode) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-}
```
public ImageJoinOptions(FileType fileType, int imageJoinMode)
```


Inicializa una nueva instancia de la clase [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo de imagen. |
| imageJoinMode | int | El modo de unión de imágenes. |

### getType() {#getType--}
```
public final FileType getType()
```


El tipo de archivo de imagen.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getMode() {#getMode--}
```
public final int getMode()
```


El modo de unión de imágenes.

**Returns:**
int
