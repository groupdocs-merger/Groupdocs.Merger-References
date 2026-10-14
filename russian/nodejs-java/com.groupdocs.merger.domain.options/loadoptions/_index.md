---
title: "LoadOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Предоставляет параметры для загрузки документа."
type: docs
weight: 16
url: /ru/nodejs-java/com.groupdocs.merger.domain.options/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Предоставляет параметры для загрузки документа.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-) | Создаёт новый экземпляр класса [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Создаёт новый экземпляр класса [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password, Charset encoding)](#LoadOptions-java.lang.String-java.nio.charset.Charset-) | Создаёт новый экземпляр класса [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-) | Создаёт новый экземпляр класса [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Создаёт новый экземпляр класса [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String extension, FileType fileType, String password, Charset encoding)](#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Создаёт новый экземпляр класса [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Создаёт новый экземпляр класса [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-) | Создаёт новый экземпляр класса [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Создаёт новый экземпляр класса [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Тип файла для загрузки. |
| [getExtension()](#getExtension--) | Расширение файла для инициализации. |
| [getPassword()](#getPassword--) | Пароль для открытия защищённого паролем файла. |
| [getEncoding()](#getEncoding--) | Кодировка, используемая при открытии текстовых файлов, таких как [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) или [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType fileType)
```


Создаёт новый экземпляр класса [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла для загрузки. |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Создаёт новый экземпляр класса [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пароль | java.lang.String | Пароль для открытия защищённого паролем файла. |

### LoadOptions(String password, Charset encoding) {#LoadOptions-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String password, Charset encoding)
```


Создаёт новый экземпляр класса [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пароль | java.lang.String | Пароль для открытия защищённого паролем файла. |
| encoding | java.nio.charset.Charset | Кодировка, используемая при открытии текстовых файлов, таких как [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) или [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType fileType, String password)
```


Создаёт новый экземпляр класса [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла для загрузки. |
| пароль | java.lang.String | Пароль для открытия защищённого паролем файла. |

### LoadOptions(FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType fileType, String password, Charset encoding)
```


Создаёт новый экземпляр класса [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла для загрузки. |
| пароль | java.lang.String | Пароль для открытия защищённого паролем файла. |
| encoding | java.nio.charset.Charset | Кодировка, используемая при открытии текстовых файлов, таких как [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) или [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(String extension, FileType fileType, String password, Charset encoding) {#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String extension, FileType fileType, String password, Charset encoding)
```


Создаёт новый экземпляр класса [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| расширение | java.lang.String | Расширение файла для загрузки. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла для загрузки. |
| пароль | java.lang.String | Пароль для открытия защищённого паролем файла. |
| encoding | java.nio.charset.Charset | Кодировка, используемая при открытии текстовых файлов, таких как [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) или [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)
```


Создаёт новый экземпляр класса [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла для инициализации. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла для загрузки. |
| пароль | java.lang.String | Пароль для открытия защищённого паролем файла. |
| encoding | java.nio.charset.Charset | Кодировка, используемая при открытии текстовых файлов, таких как [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) или [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password)
```


Создаёт новый экземпляр класса [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла для инициализации. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла для загрузки. |
| пароль | java.lang.String | Пароль для открытия защищённого паролем файла. |

### LoadOptions(FileType iniFileType, FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType iniFileType, FileType fileType)
```


Создаёт новый экземпляр класса [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла для инициализации. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла для загрузки. |

### getType() {#getType--}
```
public final FileType getType()
```


Тип файла для загрузки.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Расширение файла для инициализации.

**Returns:**
java.lang.String
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Пароль для открытия защищённого паролем файла.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Кодировка, используемая при открытии текстовых файлов, таких как [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) или [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). Значение по умолчанию — System.Text.Encoding.Default (java.nio.charset.Charset).

**Returns:**
java.nio.charset.Charset
