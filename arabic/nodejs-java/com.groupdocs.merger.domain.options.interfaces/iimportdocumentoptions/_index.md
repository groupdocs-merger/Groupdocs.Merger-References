---
title: "IImportDocumentOptions"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "واجهة لاستيراد المستند المضمّن."
type: docs
weight: 13
url: /ar/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface IImportDocumentOptions extends IOptions
```

واجهة لاستيراد المستند المضمّن.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getObjectData()](#getObjectData--) | بيانات الكائن المدمج. |
| [getExtension()](#getExtension--) | امتداد الكائن المدمج. |
| [getPageNumber()](#getPageNumber--) | رقم الصفحة لإدراج الكائن المدمج. |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


بيانات الكائن المدمج.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


امتداد الكائن المدمج.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


رقم الصفحة لإدراج الكائن المدمج.

**Returns:**
int
