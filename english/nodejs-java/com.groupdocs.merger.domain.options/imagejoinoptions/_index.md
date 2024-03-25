---
title: ImageJoinOptions
second_title: GroupDocs.Merger for Node.js via Java API Reference
description: The image join options.
type: docs
weight: 13
url: /nodejs-java/com.groupdocs.merger.domain.options/imagejoinoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/iimagejoinoptions)
```
public class ImageJoinOptions implements IImageJoinOptions
```

The image join options.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageJoinOptions()](#ImageJoinOptions--) | Initializes new instance of [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) class. |
| [ImageJoinOptions(FileType fileType)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-) | Initializes new instance of [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) class. |
| [ImageJoinOptions(int imageJoinMode)](#ImageJoinOptions-int-) | Initializes new instance of [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) class. |
| [ImageJoinOptions(FileType fileType, int imageJoinMode)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-) | Initializes new instance of [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | The image file type. |
| [getMode()](#getMode--) | The image join mode. |
### ImageJoinOptions() {#ImageJoinOptions--}
```
public ImageJoinOptions()
```


Initializes new instance of [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) class.

### ImageJoinOptions(FileType fileType) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public ImageJoinOptions(FileType fileType)
```


Initializes new instance of [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The image file type. |

### ImageJoinOptions(int imageJoinMode) {#ImageJoinOptions-int-}
```
public ImageJoinOptions(int imageJoinMode)
```


Initializes new instance of [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageJoinMode | int | The image join mode. |

### ImageJoinOptions(FileType fileType, int imageJoinMode) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-}
```
public ImageJoinOptions(FileType fileType, int imageJoinMode)
```


Initializes new instance of [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The image file type. |
| imageJoinMode | int | The image join mode. |

### getType() {#getType--}
```
public final FileType getType()
```


The image file type.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getMode() {#getMode--}
```
public final int getMode()
```


The image join mode.

**Returns:**
int
