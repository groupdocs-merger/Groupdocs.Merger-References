---
title: "GroupDocsMergerException"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "يمثل الأخطاء التي تحدث أثناء معالجة المستند."
type: docs
weight: 12
url: /ar/nodejs-java/com.groupdocs.merger.exceptions/groupdocsmergerexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception
```
public class GroupDocsMergerException extends Exception
```

يمثل الأخطاء التي تحدث أثناء معالجة المستند.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GroupDocsMergerException(String message)](#GroupDocsMergerException-java.lang.String-) | ينشئ مثلاً جديداً من الفئة [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception). |
| [GroupDocsMergerException(String message, Exception innerException)](#GroupDocsMergerException-java.lang.String-java.lang.Exception-) | ينشئ مثلاً جديداً من الفئة [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getException(Exception exception)](#getException-java.lang.Exception-) | احصل على استثناء GroupDocs Merger من الاستثناء المدخل. |
### GroupDocsMergerException(String message) {#GroupDocsMergerException-java.lang.String-}
```
public GroupDocsMergerException(String message)
```


ينشئ مثلاً جديداً من الفئة [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | الرسالة التي تصف الخطأ. |

### GroupDocsMergerException(String message, Exception innerException) {#GroupDocsMergerException-java.lang.String-java.lang.Exception-}
```
public GroupDocsMergerException(String message, Exception innerException)
```


ينشئ مثلاً جديداً من الفئة [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | الرسالة التي تصف الخطأ. |
| innerException | java.lang.Exception | الاستثناء الداخلي للخطأ. |

### getException(Exception exception) {#getException-java.lang.Exception-}
```
public static Exception getException(Exception exception)
```


احصل على استثناء GroupDocs Merger من الاستثناء المدخل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| استثناء | java.lang.Exception | استثناء الإدخال. |

**Returns:**
java.lang.Exception -
