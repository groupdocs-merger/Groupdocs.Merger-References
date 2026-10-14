---
title: "ImageJoinOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "De afbeeldingssamenvoegopties."
type: docs
weight: 13
url: /nl/nodejs-java/com.groupdocs.merger.domain.options/imagejoinoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/iimagejoinoptions)
```
public class ImageJoinOptions implements IImageJoinOptions
```

De afbeeldingssamenvoegopties.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ImageJoinOptions()](#ImageJoinOptions--) | Initialiseert een nieuw exemplaar van de [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) klasse. |
| [ImageJoinOptions(FileType fileType)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-) | Initialiseert een nieuw exemplaar van de [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) klasse. |
| [ImageJoinOptions(int imageJoinMode)](#ImageJoinOptions-int-) | Initialiseert een nieuw exemplaar van de [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) klasse. |
| [ImageJoinOptions(FileType fileType, int imageJoinMode)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-) | Initialiseert een nieuw exemplaar van de [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Het afbeeldingstype. |
| [getMode()](#getMode--) | De modus voor het samenvoegen van afbeeldingen. |
### ImageJoinOptions() {#ImageJoinOptions--}
```
public ImageJoinOptions()
```


Initialiseert een nieuw exemplaar van de [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) klasse.

### ImageJoinOptions(FileType fileType) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public ImageJoinOptions(FileType fileType)
```


Initialiseert een nieuw exemplaar van de [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het afbeeldingstype. |

### ImageJoinOptions(int imageJoinMode) {#ImageJoinOptions-int-}
```
public ImageJoinOptions(int imageJoinMode)
```


Initialiseert een nieuw exemplaar van de [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageJoinMode | int | De modus voor het samenvoegen van afbeeldingen. |

### ImageJoinOptions(FileType fileType, int imageJoinMode) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-}
```
public ImageJoinOptions(FileType fileType, int imageJoinMode)
```


Initialiseert een nieuw exemplaar van de [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het afbeeldingstype. |
| imageJoinMode | int | De modus voor het samenvoegen van afbeeldingen. |

### getType() {#getType--}
```
public final FileType getType()
```


Het afbeeldingstype.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getMode() {#getMode--}
```
public final int getMode()
```


De modus voor het samenvoegen van afbeeldingen.

**Returns:**
int
