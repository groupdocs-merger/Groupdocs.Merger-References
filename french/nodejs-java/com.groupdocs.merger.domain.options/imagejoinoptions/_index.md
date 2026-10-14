---
title: "ImageJoinOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Les options de jonction d'images."
type: docs
weight: 13
url: /fr/nodejs-java/com.groupdocs.merger.domain.options/imagejoinoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/iimagejoinoptions)
```
public class ImageJoinOptions implements IImageJoinOptions
```

Les options de jonction d'images.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImageJoinOptions()](#ImageJoinOptions--) | Initialise une nouvelle instance de la classe [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(FileType fileType)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-) | Initialise une nouvelle instance de la classe [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(int imageJoinMode)](#ImageJoinOptions-int-) | Initialise une nouvelle instance de la classe [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(FileType fileType, int imageJoinMode)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-) | Initialise une nouvelle instance de la classe [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Le type de fichier image. |
| [getMode()](#getMode--) | Le mode de jointure d'image. |
### ImageJoinOptions() {#ImageJoinOptions--}
```
public ImageJoinOptions()
```


Initialise une nouvelle instance de la classe [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

### ImageJoinOptions(FileType fileType) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public ImageJoinOptions(FileType fileType)
```


Initialise une nouvelle instance de la classe [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type de fichier image. |

### ImageJoinOptions(int imageJoinMode) {#ImageJoinOptions-int-}
```
public ImageJoinOptions(int imageJoinMode)
```


Initialise une nouvelle instance de la classe [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageJoinMode | int | Le mode de jointure d'image. |

### ImageJoinOptions(FileType fileType, int imageJoinMode) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-}
```
public ImageJoinOptions(FileType fileType, int imageJoinMode)
```


Initialise une nouvelle instance de la classe [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type de fichier image. |
| imageJoinMode | int | Le mode de jointure d'image. |

### getType() {#getType--}
```
public final FileType getType()
```


Le type de fichier image.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getMode() {#getMode--}
```
public final int getMode()
```


Le mode de jointure d'image.

**Returns:**
int
