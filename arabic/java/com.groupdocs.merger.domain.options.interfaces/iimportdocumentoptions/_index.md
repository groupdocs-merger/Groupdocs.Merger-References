---
title: "IImportDocumentOptions"
second_title: "توفر مساحة الأسماء com.groupdocs.merger.domain.builders منشئين."
description: "واجهة لاستيراد المستند المضمّن."
type: docs
weight: 13
url: /ar/java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface IImportDocumentOptions extends IOptions
```

واجهة لاستيراد المستند المضمّن.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getObjectData()](#getObjectData--) | بيانات الكائن المضمن. |
| [getExtension()](#getExtension--) | امتداد الكائن المضمن. |
| [getPageNumber()](#getPageNumber--) | رقم الصفحة لإدراج الكائن المضمن. |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


بيانات الكائن المضمن.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


امتداد الكائن المضمن.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


رقم الصفحة لإدراج الكائن المضمن.

**Returns:**
int
