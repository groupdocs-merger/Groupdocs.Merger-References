---
title: "LoadOptions"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "يوفر خيارات لتحميل المستند."
type: docs
weight: 16
url: /ar/nodejs-java/com.groupdocs.merger.domain.options/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

يوفر خيارات لتحميل المستند.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-) | ينشئ مثيلاً جديدًا من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | ينشئ مثيلاً جديدًا من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password, Charset encoding)](#LoadOptions-java.lang.String-java.nio.charset.Charset-) | ينشئ مثيلاً جديدًا من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-) | ينشئ مثيلاً جديدًا من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | ينشئ مثيلاً جديدًا من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String extension, FileType fileType, String password, Charset encoding)](#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | ينشئ مثيلاً جديدًا من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | ينشئ مثيلاً جديدًا من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-) | ينشئ مثيلاً جديدًا من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | ينشئ مثيلاً جديدًا من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | نوع الملف المراد تحميله. |
| [getExtension()](#getExtension--) | امتداد الملف للتهيئة. |
| [getPassword()](#getPassword--) | كلمة المرور لفتح ملف محمي بكلمة مرور. |
| [getEncoding()](#getEncoding--) | الترميز المستخدم عند فتح الملفات النصية مثل [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) أو [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType fileType)
```


ينشئ مثيلاً جديدًا من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف المراد تحميله. |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


ينشئ مثيلاً جديدًا من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| كلمة المرور | java.lang.String | كلمة المرور لفتح ملف محمي بكلمة مرور. |

### LoadOptions(String password, Charset encoding) {#LoadOptions-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String password, Charset encoding)
```


ينشئ مثيلاً جديدًا من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| كلمة المرور | java.lang.String | كلمة المرور لفتح ملف محمي بكلمة مرور. |
| encoding | java.nio.charset.Charset | الترميز المستخدم عند فتح الملفات النصية مثل [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) أو [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType fileType, String password)
```


ينشئ مثيلاً جديدًا من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف المراد تحميله. |
| كلمة المرور | java.lang.String | كلمة المرور لفتح ملف محمي بكلمة مرور. |

### LoadOptions(FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType fileType, String password, Charset encoding)
```


ينشئ مثيلاً جديدًا من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف المراد تحميله. |
| كلمة المرور | java.lang.String | كلمة المرور لفتح ملف محمي بكلمة مرور. |
| encoding | java.nio.charset.Charset | الترميز المستخدم عند فتح الملفات النصية مثل [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) أو [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(String extension, FileType fileType, String password, Charset encoding) {#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String extension, FileType fileType, String password, Charset encoding)
```


ينشئ مثيلاً جديدًا من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| امتداد | java.lang.String | امتداد الملف للتحميل. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف المراد تحميله. |
| كلمة المرور | java.lang.String | كلمة المرور لفتح ملف محمي بكلمة مرور. |
| encoding | java.nio.charset.Charset | الترميز المستخدم عند فتح الملفات النصية مثل [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) أو [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)
```


ينشئ مثيلاً جديدًا من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف للتهيئة. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف المراد تحميله. |
| كلمة المرور | java.lang.String | كلمة المرور لفتح ملف محمي بكلمة مرور. |
| encoding | java.nio.charset.Charset | الترميز المستخدم عند فتح الملفات النصية مثل [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) أو [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password)
```


ينشئ مثيلاً جديدًا من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف للتهيئة. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف المراد تحميله. |
| كلمة المرور | java.lang.String | كلمة المرور لفتح ملف محمي بكلمة مرور. |

### LoadOptions(FileType iniFileType, FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType iniFileType, FileType fileType)
```


ينشئ مثيلاً جديدًا من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف للتهيئة. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف المراد تحميله. |

### getType() {#getType--}
```
public final FileType getType()
```


نوع الملف المراد تحميله.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getExtension() {#getExtension--}
```
public final String getExtension()
```


امتداد الملف للتهيئة.

**Returns:**
java.lang.String
### getPassword() {#getPassword--}
```
public final String getPassword()
```


كلمة المرور لفتح ملف محمي بكلمة مرور.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


الترميز المستخدم عند فتح ملفات نصية مثل [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) أو [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). القيمة الافتراضية هي System.Text.Encoding.Default (java.nio.charset.Charset).

**Returns:**
java.nio.charset.Charset
