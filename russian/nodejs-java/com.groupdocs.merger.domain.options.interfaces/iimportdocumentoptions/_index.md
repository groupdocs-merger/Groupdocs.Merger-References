---
title: "IImportDocumentOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Интерфейс для импорта встроенного документа."
type: docs
weight: 13
url: /ru/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface IImportDocumentOptions extends IOptions
```

Интерфейс для импорта встроенного документа.
## Методы

| Метод | Описание |
| --- | --- |
| [getObjectData()](#getObjectData--) | Данные встроенного объекта. |
| [getExtension()](#getExtension--) | Расширение встроенного объекта. |
| [getPageNumber()](#getPageNumber--) | Номер страницы для вставки встроенного объекта. |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


Данные встроенного объекта.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


Расширение встроенного объекта.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Номер страницы для вставки встроенного объекта.

**Returns:**
int
