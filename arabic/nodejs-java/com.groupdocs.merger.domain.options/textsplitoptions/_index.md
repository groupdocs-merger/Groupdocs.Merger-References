---
title: "TextSplitOptions"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "يوفر خيارات لتقسيم نص المستند."
type: docs
weight: 39
url: /ar/nodejs-java/com.groupdocs.merger.domain.options/textsplitoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions)
```
public class TextSplitOptions implements ITextSplitOptions
```

يوفر خيارات لتقسيم نص المستند.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TextSplitOptions(int[] lineNumbers)](#TextSplitOptions-int---) | يقوم بتهيئة نسخة جديدة من الفئة [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(int mode, int[] lineNumbers)](#TextSplitOptions-int-int---) | يقوم بتهيئة نسخة جديدة من الفئة [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(String filePathFormat, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int---) | يقوم بتهيئة نسخة جديدة من الفئة [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int-int---) | يقوم بتهيئة نسخة جديدة من الفئة [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | يقوم بتهيئة نسخة جديدة من الفئة [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---) | يقوم بتهيئة نسخة جديدة من الفئة [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getMode()](#getMode--) | وضع لتقسيم النص. |
| [getLineNumbers()](#getLineNumbers--) | أرقام الأسطر لتقسيم النص. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | يتحقق من صحة خيارات التقسيم. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | يحصل على المسار الكامل للملف للمستند المقسّم حسب الفهرس مع الامتداد المحدد. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory لإنشاء أو تحرير تدفق معاينة صفحة الإخراج. |
### TextSplitOptions(int[] lineNumbers) {#TextSplitOptions-int---}
```
public TextSplitOptions(int[] lineNumbers)
```


يقوم بتهيئة نسخة جديدة من الفئة [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lineNumbers | int[] | أرقام الأسطر لتقسيم النص. |

### TextSplitOptions(int mode, int[] lineNumbers) {#TextSplitOptions-int-int---}
```
public TextSplitOptions(int mode, int[] lineNumbers)
```


يقوم بتهيئة نسخة جديدة من الفئة [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mode | int | وضع لتقسيم النص. |
| lineNumbers | int[] | أرقام الأسطر لتقسيم النص. |

### TextSplitOptions(String filePathFormat, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int---}
```
public TextSplitOptions(String filePathFormat, int[] lineNumbers)
```


يقوم بتهيئة نسخة جديدة من الفئة [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePathFormat | java.lang.String | تنسيق مسار الملف مثل 'c:/split\{0\}.doc' أو 'c:/split\{0\}.\{1\}' مع الامتداد المحدد مسبقًا. |
| lineNumbers | int[] | أرقام الأسطر لتقسيم النص. |

### TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int-int---}
```
public TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)
```


يقوم بتهيئة نسخة جديدة من الفئة [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePathFormat | java.lang.String | تنسيق مسار الملف مثل 'c:/split\{0\}.doc' أو 'c:/split\{0\}.\{1\}' مع الامتداد المحدد مسبقًا. |
| mode | int | وضع لتقسيم النص. |
| lineNumbers | int[] | أرقام الأسطر لتقسيم النص. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)
```


يقوم بتهيئة نسخة جديدة من الفئة [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | الطريقة التي تنشئ التدفق المستخدم لكتابة بيانات التقسيم الناتجة. |
| lineNumbers | int[] | أرقام الأسطر لتقسيم النص. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)
```


يقوم بتهيئة نسخة جديدة من الفئة [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | الطريقة التي تنشئ التدفق المستخدم لكتابة بيانات التقسيم الناتجة. |
| mode | int | وضع لتقسيم النص. |
| lineNumbers | int[] | أرقام الأسطر لتقسيم النص. |

### getMode() {#getMode--}
```
public final int getMode()
```


وضع لتقسيم النص.

**Returns:**
int
### getLineNumbers() {#getLineNumbers--}
```
public final int[] getLineNumbers()
```


أرقام الأسطر لتقسيم النص.

**Returns:**
int[]
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


يتحقق من صحة خيارات التقسيم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف لفئة [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


يحصل على المسار الكامل للملف للمستند المقسّم حسب الفهرس مع الامتداد المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| فهرس | int | فهرس المستند المقسّم. |
| امتداد | java.lang.String | امتداد الملف. |

**Returns:**
java.lang.String - المسار الكامل للملف.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


SplitStreamFactory لإنشاء أو تحرير تدفق معاينة صفحة الإخراج.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
