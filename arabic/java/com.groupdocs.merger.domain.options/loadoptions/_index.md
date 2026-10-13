---
title: "LoadOptions"
second_title: "توفر مساحة الأسماء com.groupdocs.merger.domain.builders منشئين."
description: "يوفر خيارات لتحميل المستند."
type: docs
weight: 16
url: /ar/java/com.groupdocs.merger.domain.options/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

يوفر خيارات لتحميل المستند.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-) | يُنشئ نسخة جديدة من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | يُنشئ نسخة جديدة من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password, Charset encoding)](#LoadOptions-java.lang.String-java.nio.charset.Charset-) | يُنشئ نسخة جديدة من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-) | يُنشئ نسخة جديدة من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | يُنشئ نسخة جديدة من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String extension, FileType fileType, String password, Charset encoding)](#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | يُنشئ نسخة جديدة من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | يُنشئ نسخة جديدة من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-) | يُنشئ نسخة جديدة من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | يُنشئ نسخة جديدة من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | نوع الملف الذي سيتم تحميله. |
| [getExtension()](#getExtension--) | امتداد الملف للتهيئة. |
| [getPassword()](#getPassword--) | كلمة المرور لفتح الملف المحمي بكلمة مرور. |
| [getEncoding()](#getEncoding--) | الترميز المستخدم عند فتح ملفات نصية مثل [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) أو [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType fileType)
```


يُنشئ نسخة جديدة من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف الذي سيتم تحميله. |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


يُنشئ نسخة جديدة من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| كلمة المرور | java.lang.String | كلمة المرور لفتح الملف المحمي بكلمة مرور. |

### LoadOptions(String password, Charset encoding) {#LoadOptions-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String password, Charset encoding)
```


يُنشئ نسخة جديدة من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| كلمة المرور | java.lang.String | كلمة المرور لفتح الملف المحمي بكلمة مرور. |
| encoding | java.nio.charset.Charset | الترميز المستخدم عند فتح ملفات نصية مثل [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) أو [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType fileType, String password)
```


يُنشئ نسخة جديدة من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف الذي سيتم تحميله. |
| كلمة المرور | java.lang.String | كلمة المرور لفتح الملف المحمي بكلمة مرور. |

### LoadOptions(FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType fileType, String password, Charset encoding)
```


يُنشئ نسخة جديدة من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف الذي سيتم تحميله. |
| كلمة المرور | java.lang.String | كلمة المرور لفتح الملف المحمي بكلمة مرور. |
| encoding | java.nio.charset.Charset | الترميز المستخدم عند فتح ملفات نصية مثل [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) أو [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(String extension, FileType fileType, String password, Charset encoding) {#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String extension, FileType fileType, String password, Charset encoding)
```


يُنشئ نسخة جديدة من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| امتداد | java.lang.String | امتداد الملف للتحميل. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف الذي سيتم تحميله. |
| كلمة المرور | java.lang.String | كلمة المرور لفتح الملف المحمي بكلمة مرور. |
| encoding | java.nio.charset.Charset | الترميز المستخدم عند فتح ملفات نصية مثل [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) أو [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)
```


يُنشئ نسخة جديدة من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف للتهيئة. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف الذي سيتم تحميله. |
| كلمة المرور | java.lang.String | كلمة المرور لفتح الملف المحمي بكلمة مرور. |
| encoding | java.nio.charset.Charset | الترميز المستخدم عند فتح ملفات نصية مثل [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) أو [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password)
```


يُنشئ نسخة جديدة من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف للتهيئة. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف الذي سيتم تحميله. |
| كلمة المرور | java.lang.String | كلمة المرور لفتح الملف المحمي بكلمة مرور. |

### LoadOptions(FileType iniFileType, FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType iniFileType, FileType fileType)
```


يُنشئ نسخة جديدة من الفئة [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف للتهيئة. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف الذي سيتم تحميله. |

### getType() {#getType--}
```
public final FileType getType()
```


نوع الملف الذي سيتم تحميله.

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


كلمة المرور لفتح الملف المحمي بكلمة مرور.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


الترميز المستخدم عند فتح ملفات نصية مثل [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) أو [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). القيمة الافتراضية هي System.Text.Encoding.Default (java.nio.charset.Charset).

**Returns:**
java.nio.charset.Charset
