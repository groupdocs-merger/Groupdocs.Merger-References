---
title: "ILoadOptions"
second_title: "توفر مساحة الأسماء com.groupdocs.merger.domain.builders منشئين."
description: "واجهة لخيارات تحميل المستند."
type: docs
weight: 15
url: /ar/java/com.groupdocs.merger.domain.options.interfaces/iloadoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ILoadOptions extends IOptions
```

واجهة لخيارات تحميل المستند.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | نوع الملف الذي سيتم فتحه. |
| [getPassword()](#getPassword--) | كلمة المرور لفتح الملف المحمي بكلمة مرور. |
| [getExtension()](#getExtension--) | امتداد الملف الذي سيتم فتحه. |
| [getEncoding()](#getEncoding--) | الترميز المستخدم عند فتح ملفات نصية مثل [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) أو [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### getType() {#getType--}
```
public abstract FileType getType()
```


نوع الملف الذي سيتم فتحه.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


كلمة المرور لفتح الملف المحمي بكلمة مرور.

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


امتداد الملف الذي سيتم فتحه.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public abstract Charset getEncoding()
```


الترميز المستخدم عند فتح ملفات نصية مثل [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) أو [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). القيمة الافتراضية هي [DefaultCharset][].


[DefaultCharset]: https://docs.oracle.com/javase/7/docs/api/java/nio/charset/Charset.html#defaultCharset%28%29

**Returns:**
java.nio.charset.Charset
