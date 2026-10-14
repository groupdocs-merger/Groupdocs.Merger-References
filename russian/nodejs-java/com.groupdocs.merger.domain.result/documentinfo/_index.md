---
title: "DocumentInfo"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Определяет свойства описания документа."
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.merger.domain.result/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IDocumentInfo](../../com.groupdocs.merger.domain.result/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Определяет свойства описания документа.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Инициализирует новый экземпляр класса [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-) | Инициализирует новый экземпляр класса [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
| [DocumentInfo(FileType fileType, IPageInfo[] pages, long size)](#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-) | Инициализирует новый экземпляр класса [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
## Методы

| Метод | Описание |
| --- | --- |
| [getIndex()](#getIndex--) | Индекс документа. |
| [getStream()](#getStream--) | Поток документа. |
| [getPassword()](#getPassword--) | Пароль документа. |
| [getType()](#getType--) | Получает тип файла. |
| [getPages()](#getPages--) | Определяет коллекцию страниц документа. |
| [getPageCount()](#getPageCount--) | Количество страниц документа. |
| [getSize()](#getSize--) | Размер документа в байтах |
| [toString()](#toString--) | Возвращает строку, представляющую текущий объект. |
### DocumentInfo(int index, InputStream stream, FileType fileType, String password) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password)
```


Инициализирует новый экземпляр класса [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int |  |
| поток | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла. |
| пароль | java.lang.String |  |

### DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)
```


Инициализирует новый экземпляр класса [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int |  |
| поток | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла. |
| пароль | java.lang.String |  |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Список страниц для просмотра. |
| размер | long | Размер файла. |

### DocumentInfo(FileType fileType, IPageInfo[] pages, long size) {#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```


Инициализирует новый экземпляр класса [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла. |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Список страниц для просмотра. |
| размер | long | Размер файла. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


Индекс документа.

**Returns:**
int
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Поток документа.

**Returns:**
java.io.InputStream
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Пароль документа.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final FileType getType()
```


Получает тип файла.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPages() {#getPages--}
```
public final IPageInfo[] getPages()
```


Определяет коллекцию страниц документа.

**Returns:**
com.groupdocs.merger.domain.result.IPageInfo[]
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Количество страниц документа.

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Размер документа в байтах

**Returns:**
long
### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую текущий объект.

**Returns:**
java.lang.String — строка, представляющая текущий объект.
