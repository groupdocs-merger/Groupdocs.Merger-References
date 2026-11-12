---
title: "ITextSplitOptions"
second_title: "توفر مساحة الأسماء com.groupdocs.merger.domain.builders منشئين."
description: "واجهة لخيارات تقسيم النص."
type: docs
weight: 35
url: /ar/java/com.groupdocs.merger.domain.options.interfaces/itextsplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ITextSplitOptions extends IOptions
```

واجهة لخيارات تقسيم النص.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getLineNumbers()](#getLineNumbers--) | أرقام الأسطر لتقسيم النص. |
| [getMode()](#getMode--) | وضع لتقسيم النص. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | يتحقق من صحة خيارات التقسيم. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | يحصل على المسار الكامل للملف للمستند المقسم حسب الفهرس مع الامتداد المحدد. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | المندوب الذي يحدد الطريقة لإنشاء تدفق تقسيم الإخراج. |
### getLineNumbers() {#getLineNumbers--}
```
public abstract int[] getLineNumbers()
```


أرقام الأسطر لتقسيم النص.

**Returns:**
int[]
### getMode() {#getMode--}
```
public abstract int getMode()
```


وضع لتقسيم النص.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


يتحقق من صحة خيارات التقسيم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف لفئة [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public abstract String getPathByIndex(int index, String extension)
```


يحصل على المسار الكامل للملف للمستند المقسم حسب الفهرس مع الامتداد المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | فهرس المستند المقسم. |
| امتداد | java.lang.String | امتداد الملف. |

**Returns:**
java.lang.String - المسار الكامل للملف.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public abstract SplitStreamFactory getSplitStreamFactory()
```


المندوب الذي يحدد الطريقة لإنشاء تدفق تقسيم الإخراج.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
