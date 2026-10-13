---
title: "PageJoinOptions"
second_title: "توفر مساحة الأسماء com.groupdocs.merger.domain.builders منشئين."
description: "يوفر خيارات لدمج المستندات."
type: docs
weight: 25
url: /ar/java/com.groupdocs.merger.domain.options/pagejoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions)
```
public class PageJoinOptions extends PageOptions implements IPageJoinOptions
```

يوفر خيارات لدمج المستندات.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [PageJoinOptions()](#PageJoinOptions--) | يُنشئ نسخة جديدة من الفئة [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int[] pageNumbers)](#PageJoinOptions-int---) | يُنشئ نسخة جديدة من الفئة [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int startNumber, int endNumber)](#PageJoinOptions-int-int-) | يُنشئ نسخة جديدة من الفئة [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int startNumber, int endNumber, int mode)](#PageJoinOptions-int-int-int-) | يُنشئ نسخة جديدة من الفئة [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-) | يُنشئ نسخة جديدة من الفئة [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int[] pageNumbers)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---) | يُنشئ نسخة جديدة من الفئة [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | يُنشئ نسخة جديدة من الفئة [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | يُنشئ نسخة جديدة من الفئة [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | نوع الملف للدمج. |
### PageJoinOptions() {#PageJoinOptions--}
```
public PageJoinOptions()
```


يُنشئ نسخة جديدة من الفئة [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

### PageJoinOptions(int[] pageNumbers) {#PageJoinOptions-int---}
```
public PageJoinOptions(int[] pageNumbers)
```


يُنشئ نسخة جديدة من الفئة [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumbers | int[] | أرقام الصفحات. |

### PageJoinOptions(int startNumber, int endNumber) {#PageJoinOptions-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber)
```


يُنشئ نسخة جديدة من الفئة [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |

### PageJoinOptions(int startNumber, int endNumber, int mode) {#PageJoinOptions-int-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber, int mode)
```


يُنشئ نسخة جديدة من الفئة [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |
| الوضع | int | وضع النطاق. |

### PageJoinOptions(FileType fileType) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public PageJoinOptions(FileType fileType)
```


يُنشئ نسخة جديدة من الفئة [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف للدمج. |

### PageJoinOptions(FileType fileType, int[] pageNumbers) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public PageJoinOptions(FileType fileType, int[] pageNumbers)
```


يُنشئ نسخة جديدة من الفئة [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف للدمج. |
| pageNumbers | int[] | أرقام الصفحات. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber)
```


يُنشئ نسخة جديدة من الفئة [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف للدمج. |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


يُنشئ نسخة جديدة من الفئة [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف للدمج. |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |
| الوضع | int | وضع النطاق. |

### getType() {#getType--}
```
public final FileType getType()
```


نوع الملف للدمج.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
