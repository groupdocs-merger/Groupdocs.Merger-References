---
title: "SplitOptions"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "يوفر خيارات لتقسيم صفحات المستند."
type: docs
weight: 36
url: /ar/nodejs-java/com.groupdocs.merger.domain.options/splitoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions)
```
public class SplitOptions extends PageOptions implements ISplitOptions
```

يوفر خيارات لتقسيم صفحات المستند.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SplitOptions(int[] pageNumbers, int splitMode)](#SplitOptions-int---int-) | ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(int splitMode, int startNumber, int endNumber)](#SplitOptions-int-int-int-) | ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-int-int-int-int-) | ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int[] pageNumbers)](#SplitOptions-java.lang.String-int---) | ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)](#SplitOptions-java.lang.String-int---int-) | ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-) | ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-int-) | ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)](#SplitOptions-java.lang.String-int-int-java.lang.Integer-) | ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-java.lang.String-int-int-int-int-) | ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-) | ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-) | ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-) | ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-) | ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-) | ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-) | ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getMode()](#getMode--) | يحصل على وضع تقسيم الصفحات. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | يتحقق من صحة خيارات التقسيم. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | يحصل على المسار الكامل للملف للمستند المقسّم حسب الفهرس مع الامتداد المحدد مسبقًا. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory لإنشاء أو تحرير تدفق معاينة صفحة الإخراج. |
### SplitOptions(int[] pageNumbers, int splitMode) {#SplitOptions-int---int-}
```
public SplitOptions(int[] pageNumbers, int splitMode)
```


ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumbers | int[] | أرقام الصفحات. |
| splitMode | int | وضع التقسيم لـ Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(int splitMode, int startNumber, int endNumber) {#SplitOptions-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber)
```


ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| splitMode | int | وضع التقسيم لـ Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |

### SplitOptions(int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-int-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber, int mode)
```


ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| splitMode | int | وضع التقسيم لـ Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |
| mode | int | وضع النطاق. |

### SplitOptions(String filePathFormat, int[] pageNumbers) {#SplitOptions-java.lang.String-int---}
```
public SplitOptions(String filePathFormat, int[] pageNumbers)
```


ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePathFormat | java.lang.String | تنسيق مسار الملف مثال: 'c:/split\{0\}.doc' أو 'c:/split\{0\}.\{1\}' مع امتداد محدد مسبقًا. |
| pageNumbers | int[] | أرقام الصفحات. |

### SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode) {#SplitOptions-java.lang.String-int---int-}
```
public SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)
```


ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePathFormat | java.lang.String | تنسيق مسار الملف مثال: 'c:/split\{0\}.doc' أو 'c:/split\{0\}.\{1\}' مع امتداد محدد مسبقًا. |
| pageNumbers | int[] | أرقام الصفحات. |
| splitMode | int | وضع التقسيم لـ Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(String filePathFormat, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber)
```


ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePathFormat | java.lang.String | تنسيق مسار الملف مثال: 'c:/split\{0\}.doc' أو 'c:/split\{0\}.\{1\}' مع امتداد محدد مسبقًا. |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)
```


ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePathFormat | java.lang.String | تنسيق مسار الملف مثال: 'c:/split\{0\}.doc' أو 'c:/split\{0\}.\{1\}' مع امتداد محدد مسبقًا. |
| splitMode | int | وضع التقسيم لـ Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |

### SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode) {#SplitOptions-java.lang.String-int-int-java.lang.Integer-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)
```


ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePathFormat | java.lang.String | تنسيق مسار الملف مثال: 'c:/split\{0\}.doc' أو 'c:/split\{0\}.\{1\}' مع امتداد محدد مسبقًا. |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |
| mode | java.lang.Integer | وضع النطاق. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-java.lang.String-int-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)
```


ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePathFormat | java.lang.String | تنسيق مسار الملف مثال: 'c:/split\{0\}.doc' أو 'c:/split\{0\}.\{1\}' مع امتداد محدد مسبقًا. |
| splitMode | int | وضع التقسيم لـ Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |
| mode | int | وضع النطاق. |

### SplitOptions(SplitStreamFactory splitStreamFactory) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory)
```


ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | الطريقة التي تنشئ التدفق المستخدم لكتابة بيانات التقسيم الناتجة. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)
```


ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | الطريقة التي تنشئ التدفق المستخدم لكتابة بيانات التقسيم الناتجة. |
| pageNumbers | int[] | أرقام الصفحات. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)
```


ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | الطريقة التي تنشئ التدفق المستخدم لكتابة بيانات التقسيم الناتجة. |
| pageNumbers | int[] | أرقام الصفحات. |
| splitMode | int | وضع التقسيم لـ Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)
```


ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | الطريقة التي تنشئ التدفق المستخدم لكتابة بيانات التقسيم الناتجة. |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)
```


ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | الطريقة التي تنشئ التدفق المستخدم لكتابة بيانات التقسيم الناتجة. |
| splitMode | int | وضع التقسيم لـ Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)
```


ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | الطريقة التي تنشئ التدفق المستخدم لكتابة بيانات التقسيم الناتجة. |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |
| mode | java.lang.Integer | وضع النطاق. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)
```


ينشئ مثيلاً جديدًا من الفئة [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | الطريقة التي تنشئ التدفق المستخدم لكتابة بيانات التقسيم الناتجة. |
| splitMode | int | وضع التقسيم لـ Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |
| mode | int | وضع النطاق. |

### getMode() {#getMode--}
```
public final int getMode()
```


يحصل على وضع تقسيم الصفحات.

**Returns:**
int
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


يحصل على المسار الكامل للملف للمستند المقسّم حسب الفهرس مع الامتداد المحدد مسبقًا.

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
