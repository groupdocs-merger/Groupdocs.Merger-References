---
title: "ILoadOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Интерфейс для параметров загрузки документа."
type: docs
weight: 15
url: /ru/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iloadoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ILoadOptions extends IOptions
```

Интерфейс для параметров загрузки документа.
## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Тип файла для открытия. |
| [getPassword()](#getPassword--) | Пароль для открытия защищённого паролем файла. |
| [getExtension()](#getExtension--) | Расширение файла для открытия. |
| [getEncoding()](#getEncoding--) | Кодировка, используемая при открытии текстовых файлов, таких как [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) или [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### getType() {#getType--}
```
public abstract FileType getType()
```


Тип файла для открытия.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


Пароль для открытия защищённого паролем файла.

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


Расширение файла для открытия.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public abstract Charset getEncoding()
```


Кодировка, используемая при открытии текстовых файлов, таких как [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) или [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). Значение по умолчанию — [DefaultCharset][].


[DefaultCharset]: https://docs.oracle.com/javase/7/docs/api/java/nio/charset/Charset.html#defaultCharset%28%29

**Returns:**
java.nio.charset.Charset
