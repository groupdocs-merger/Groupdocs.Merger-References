---
title: "ImageJoinOptions"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "خيارات دمج الصور."
type: docs
weight: 13
url: /ar/nodejs-java/com.groupdocs.merger.domain.options/imagejoinoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/iimagejoinoptions)
```
public class ImageJoinOptions implements IImageJoinOptions
```

خيارات دمج الصور.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ImageJoinOptions()](#ImageJoinOptions--) | ينشئ مثيلاً جديدًا من الفئة [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(FileType fileType)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-) | ينشئ مثيلاً جديدًا من الفئة [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(int imageJoinMode)](#ImageJoinOptions-int-) | ينشئ مثيلاً جديدًا من الفئة [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(FileType fileType, int imageJoinMode)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-) | ينشئ مثيلاً جديدًا من الفئة [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | نوع ملف الصورة. |
| [getMode()](#getMode--) | وضع دمج الصورة. |
### ImageJoinOptions() {#ImageJoinOptions--}
```
public ImageJoinOptions()
```


ينشئ مثيلاً جديدًا من الفئة [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

### ImageJoinOptions(FileType fileType) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public ImageJoinOptions(FileType fileType)
```


ينشئ مثيلاً جديدًا من الفئة [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع ملف الصورة. |

### ImageJoinOptions(int imageJoinMode) {#ImageJoinOptions-int-}
```
public ImageJoinOptions(int imageJoinMode)
```


ينشئ مثيلاً جديدًا من الفئة [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageJoinMode | int | وضع دمج الصورة. |

### ImageJoinOptions(FileType fileType, int imageJoinMode) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-}
```
public ImageJoinOptions(FileType fileType, int imageJoinMode)
```


ينشئ مثيلاً جديدًا من الفئة [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع ملف الصورة. |
| imageJoinMode | int | وضع دمج الصورة. |

### getType() {#getType--}
```
public final FileType getType()
```


نوع ملف الصورة.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getMode() {#getMode--}
```
public final int getMode()
```


وضع دمج الصورة.

**Returns:**
int
