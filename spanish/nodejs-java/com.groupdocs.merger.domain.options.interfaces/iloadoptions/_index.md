---
title: "ILoadOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Interfaz para las opciones de carga del documento."
type: docs
weight: 15
url: /es/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iloadoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ILoadOptions extends IOptions
```

Interfaz para las opciones de carga del documento.
## Métodos

| Método | Descripción |
| --- | --- |
| [getType()](#getType--) | El tipo de archivo a abrir. |
| [getPassword()](#getPassword--) | La contraseña para abrir el archivo protegido con contraseña. |
| [getExtension()](#getExtension--) | La extensión del archivo a abrir. |
| [getEncoding()](#getEncoding--) | La codificación utilizada al abrir archivos basados en texto, como [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) o [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### getType() {#getType--}
```
public abstract FileType getType()
```


El tipo de archivo a abrir.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


La contraseña para abrir el archivo protegido con contraseña.

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


La extensión del archivo a abrir.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public abstract Charset getEncoding()
```


La codificación utilizada al abrir archivos basados en texto, como [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) o [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). El valor predeterminado es [DefaultCharset][].


[DefaultCharset]: https://docs.oracle.com/javase/7/docs/api/java/nio/charset/Charset.html#defaultCharset%28%29

**Returns:**
java.nio.charset.Charset
