---
title: "ImageJoinOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Параметры объединения изображений."
type: docs
weight: 13
url: /ru/nodejs-java/com.groupdocs.merger.domain.options/imagejoinoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/iimagejoinoptions)
```
public class ImageJoinOptions implements IImageJoinOptions
```

Параметры объединения изображений.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImageJoinOptions()](#ImageJoinOptions--) | Инициализирует новый экземпляр класса [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(FileType fileType)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-) | Инициализирует новый экземпляр класса [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(int imageJoinMode)](#ImageJoinOptions-int-) | Инициализирует новый экземпляр класса [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(FileType fileType, int imageJoinMode)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-) | Инициализирует новый экземпляр класса [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Тип файла изображения. |
| [getMode()](#getMode--) | Режим объединения изображений. |
### ImageJoinOptions() {#ImageJoinOptions--}
```
public ImageJoinOptions()
```


Инициализирует новый экземпляр класса [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

### ImageJoinOptions(FileType fileType) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public ImageJoinOptions(FileType fileType)
```


Инициализирует новый экземпляр класса [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла изображения. |

### ImageJoinOptions(int imageJoinMode) {#ImageJoinOptions-int-}
```
public ImageJoinOptions(int imageJoinMode)
```


Инициализирует новый экземпляр класса [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageJoinMode | int | Режим объединения изображений. |

### ImageJoinOptions(FileType fileType, int imageJoinMode) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-}
```
public ImageJoinOptions(FileType fileType, int imageJoinMode)
```


Инициализирует новый экземпляр класса [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла изображения. |
| imageJoinMode | int | Режим объединения изображений. |

### getType() {#getType--}
```
public final FileType getType()
```


Тип файла изображения.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getMode() {#getMode--}
```
public final int getMode()
```


Режим объединения изображений.

**Returns:**
int
