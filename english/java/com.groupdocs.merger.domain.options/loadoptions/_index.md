---
title: LoadOptions
second_title: GroupDocs.Merger for Java API Reference
description:  Provides options for the document loading.
type: docs
weight: 16
url: /java/com.groupdocs.merger.domain.options/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Provides options for the document loading.
## Constructors

| Constructor | Description |
| --- | --- |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-) | Initializes new instance of [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) class. |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Initializes new instance of [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) class. |
| [LoadOptions(String password, Charset encoding)](#LoadOptions-java.lang.String-java.nio.charset.Charset-) | Initializes new instance of [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) class. |
| [LoadOptions(FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-) | Initializes new instance of [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) class. |
| [LoadOptions(FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Initializes new instance of [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) class. |
| [LoadOptions(String extension, FileType fileType, String password, Charset encoding)](#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Initializes new instance of [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | The type of the file to open. |
| [getExtension()](#getExtension--) | The extension of the file to open. |
| [getPassword()](#getPassword--) | The password for opening password-protected file. |
| [getEncoding()](#getEncoding--) | The encoding used when opening text-based files such as [FileType\#CSV](../../com.groupdocs.merger.domain/filetype\#CSV) or [FileType\#TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType fileType)
```


Initializes new instance of [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The type of the file to open. |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Initializes new instance of [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | The password for opening password-protected file. |

### LoadOptions(String password, Charset encoding) {#LoadOptions-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String password, Charset encoding)
```


Initializes new instance of [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | The password for opening password-protected file. |
| encoding | java.nio.charset.Charset | The encoding used when opening text-based files such as [FileType\#CSV](../../com.groupdocs.merger.domain/filetype\#CSV) or [FileType\#TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType fileType, String password)
```


Initializes new instance of [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The type of the file to open. |
| password | java.lang.String | The password for opening password-protected file. |

### LoadOptions(FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType fileType, String password, Charset encoding)
```


Initializes new instance of [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The type of the file to open. |
| password | java.lang.String | The password for opening password-protected file. |
| encoding | java.nio.charset.Charset | The encoding used when opening text-based files such as [FileType\#CSV](../../com.groupdocs.merger.domain/filetype\#CSV) or [FileType\#TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(String extension, FileType fileType, String password, Charset encoding) {#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String extension, FileType fileType, String password, Charset encoding)
```


Initializes new instance of [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | The extension of the file to open. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The type of the file to open. |
| password | java.lang.String | The password for opening password-protected file. |
| encoding | java.nio.charset.Charset | The encoding used when opening text-based files such as [FileType\#CSV](../../com.groupdocs.merger.domain/filetype\#CSV) or [FileType\#TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### getType() {#getType--}
```
public final FileType getType()
```


The type of the file to open.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getExtension() {#getExtension--}
```
public final String getExtension()
```


The extension of the file to open.

**Returns:**
java.lang.String
### getPassword() {#getPassword--}
```
public final String getPassword()
```


The password for opening password-protected file.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


The encoding used when opening text-based files such as [FileType\#CSV](../../com.groupdocs.merger.domain/filetype\#CSV) or [FileType\#TXT](../../com.groupdocs.merger.domain/filetype\#TXT).

**Returns:**
java.nio.charset.Charset
