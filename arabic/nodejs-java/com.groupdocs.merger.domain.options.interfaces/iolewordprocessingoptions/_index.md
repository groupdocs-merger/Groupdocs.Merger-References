---
title: "IOleWordProcessingOptions"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "واجهة لخيارات استيراد المستند المضمّن إلى معالجة النصوص عبر OLE."
type: docs
weight: 20
url: /ar/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleWordProcessingOptions extends IImportDocumentOptions, ISizeOptions
```

واجهة لخيارات استيراد المستند المضمّن إلى معالجة النصوص عبر OLE.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLeft()](#getLeft--) | الإحداثي الأيسر لصورة كائن Ole. |
| [setLeft(int value)](#setLeft-int-) | الإحداثي الأيسر لصورة كائن Ole. |
| [getTop()](#getTop--) | الإحداثي العلوي لصورة كائن Ole. |
| [setTop(int value)](#setTop-int-) | الإحداثي العلوي لصورة كائن Ole. |
| [getImageData()](#getImageData--) | بيانات صورة كائن Ole. |
### getLeft() {#getLeft--}
```
public abstract int getLeft()
```


الإحداثي الأيسر لصورة كائن Ole.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public abstract void setLeft(int value)
```


الإحداثي الأيسر لصورة كائن Ole.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public abstract int getTop()
```


الإحداثي العلوي لصورة كائن Ole.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public abstract void setTop(int value)
```


الإحداثي العلوي لصورة كائن Ole.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


بيانات صورة كائن Ole.

**Returns:**
byte[]
