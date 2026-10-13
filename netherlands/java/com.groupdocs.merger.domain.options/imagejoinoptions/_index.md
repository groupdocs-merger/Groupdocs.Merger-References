---
title: "ImageJoinOptions"
second_title: "GroupDocs.Merger for Java API-referentie"
description: "De opties voor het samenvoegen van afbeeldingen."
type: docs
weight: 13
url: /nl/java/com.groupdocs.merger.domain.options/imagejoinoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/iimagejoinoptions)
```
public class ImageJoinOptions implements IImageJoinOptions
```

De opties voor het samenvoegen van afbeeldingen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ImageJoinOptions()](#ImageJoinOptions--) | Initialiseert een nieuw exemplaar van de klasse [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(FileType fileType)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-) | Initialiseert een nieuw exemplaar van de klasse [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(int imageJoinMode)](#ImageJoinOptions-int-) | Initialiseert een nieuw exemplaar van de klasse [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(FileType fileType, int imageJoinMode)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-) | Initialiseert een nieuw exemplaar van de klasse [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Het type afbeeldingsbestand. |
| [getMode()](#getMode--) | De modus voor het samenvoegen van afbeeldingen. |
### ImageJoinOptions() {#ImageJoinOptions--}
```
public ImageJoinOptions()
```


Initialiseert een nieuw exemplaar van de klasse [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

### ImageJoinOptions(FileType fileType) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public ImageJoinOptions(FileType fileType)
```


Initialiseert een nieuw exemplaar van de klasse [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het type afbeeldingsbestand. |

### ImageJoinOptions(int imageJoinMode) {#ImageJoinOptions-int-}
```
public ImageJoinOptions(int imageJoinMode)
```


Initialiseert een nieuw exemplaar van de klasse [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageJoinMode | int | De modus voor het samenvoegen van afbeeldingen. |

### ImageJoinOptions(FileType fileType, int imageJoinMode) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-}
```
public ImageJoinOptions(FileType fileType, int imageJoinMode)
```


Initialiseert een nieuw exemplaar van de klasse [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het type afbeeldingsbestand. |
| imageJoinMode | int | De modus voor het samenvoegen van afbeeldingen. |

### getType() {#getType--}
```
public final FileType getType()
```


Het type afbeeldingsbestand.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getMode() {#getMode--}
```
public final int getMode()
```


De modus voor het samenvoegen van afbeeldingen.

**Returns:**
int
