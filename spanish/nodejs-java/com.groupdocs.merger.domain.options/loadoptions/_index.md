---
title: "LoadOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Proporciona opciones para la carga del documento."
type: docs
weight: 16
url: /es/nodejs-java/com.groupdocs.merger.domain.options/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Proporciona opciones para la carga del documento.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-) | Inicializa una nueva instancia de la clase [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Inicializa una nueva instancia de la clase [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password, Charset encoding)](#LoadOptions-java.lang.String-java.nio.charset.Charset-) | Inicializa una nueva instancia de la clase [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-) | Inicializa una nueva instancia de la clase [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Inicializa una nueva instancia de la clase [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String extension, FileType fileType, String password, Charset encoding)](#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Inicializa una nueva instancia de la clase [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Inicializa una nueva instancia de la clase [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-) | Inicializa una nueva instancia de la clase [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Inicializa una nueva instancia de la clase [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getType()](#getType--) | El tipo de archivo a cargar. |
| [getExtension()](#getExtension--) | La extensión del archivo a inicializar. |
| [getPassword()](#getPassword--) | La contraseña para abrir el archivo protegido con contraseña. |
| [getEncoding()](#getEncoding--) | La codificación utilizada al abrir archivos basados en texto, como [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) o [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType fileType)
```


Inicializa una nueva instancia de la clase [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo a cargar. |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Inicializa una nueva instancia de la clase [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contraseña | java.lang.String | La contraseña para abrir el archivo protegido con contraseña. |

### LoadOptions(String password, Charset encoding) {#LoadOptions-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String password, Charset encoding)
```


Inicializa una nueva instancia de la clase [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contraseña | java.lang.String | La contraseña para abrir el archivo protegido con contraseña. |
| encoding | java.nio.charset.Charset | La codificación utilizada al abrir archivos basados en texto, como [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) o [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType fileType, String password)
```


Inicializa una nueva instancia de la clase [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo a cargar. |
| contraseña | java.lang.String | La contraseña para abrir el archivo protegido con contraseña. |

### LoadOptions(FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType fileType, String password, Charset encoding)
```


Inicializa una nueva instancia de la clase [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo a cargar. |
| contraseña | java.lang.String | La contraseña para abrir el archivo protegido con contraseña. |
| encoding | java.nio.charset.Charset | La codificación utilizada al abrir archivos basados en texto, como [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) o [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(String extension, FileType fileType, String password, Charset encoding) {#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String extension, FileType fileType, String password, Charset encoding)
```


Inicializa una nueva instancia de la clase [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| extensión | java.lang.String | La extensión del archivo a cargar. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo a cargar. |
| contraseña | java.lang.String | La contraseña para abrir el archivo protegido con contraseña. |
| encoding | java.nio.charset.Charset | La codificación utilizada al abrir archivos basados en texto, como [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) o [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)
```


Inicializa una nueva instancia de la clase [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo a inicializar. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo a cargar. |
| contraseña | java.lang.String | La contraseña para abrir el archivo protegido con contraseña. |
| encoding | java.nio.charset.Charset | La codificación utilizada al abrir archivos basados en texto, como [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) o [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password)
```


Inicializa una nueva instancia de la clase [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo a inicializar. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo a cargar. |
| contraseña | java.lang.String | La contraseña para abrir el archivo protegido con contraseña. |

### LoadOptions(FileType iniFileType, FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType iniFileType, FileType fileType)
```


Inicializa una nueva instancia de la clase [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo a inicializar. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo a cargar. |

### getType() {#getType--}
```
public final FileType getType()
```


El tipo de archivo a cargar.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getExtension() {#getExtension--}
```
public final String getExtension()
```


La extensión del archivo a inicializar.

**Returns:**
java.lang.String
### getPassword() {#getPassword--}
```
public final String getPassword()
```


La contraseña para abrir el archivo protegido con contraseña.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


La codificación utilizada al abrir archivos basados en texto como [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) o [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). El valor predeterminado es System.Text.Encoding.Default (java.nio.charset.Charset).

**Returns:**
java.nio.charset.Charset
