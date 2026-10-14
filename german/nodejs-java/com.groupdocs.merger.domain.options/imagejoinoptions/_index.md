---
title: "ImageJoinOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Die Bildzusammenführungsoptionen."
type: docs
weight: 13
url: /de/nodejs-java/com.groupdocs.merger.domain.options/imagejoinoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/iimagejoinoptions)
```
public class ImageJoinOptions implements IImageJoinOptions
```

Die Bildzusammenführungsoptionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImageJoinOptions()](#ImageJoinOptions--) | Initialisiert eine neue Instanz der [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) Klasse. |
| [ImageJoinOptions(FileType fileType)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-) | Initialisiert eine neue Instanz der [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) Klasse. |
| [ImageJoinOptions(int imageJoinMode)](#ImageJoinOptions-int-) | Initialisiert eine neue Instanz der [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) Klasse. |
| [ImageJoinOptions(FileType fileType, int imageJoinMode)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-) | Initialisiert eine neue Instanz der [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Der Bilddateityp. |
| [getMode()](#getMode--) | Der Bildzusammenführungsmodus. |
### ImageJoinOptions() {#ImageJoinOptions--}
```
public ImageJoinOptions()
```


Initialisiert eine neue Instanz der [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) Klasse.

### ImageJoinOptions(FileType fileType) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public ImageJoinOptions(FileType fileType)
```


Initialisiert eine neue Instanz der [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Bilddateityp. |

### ImageJoinOptions(int imageJoinMode) {#ImageJoinOptions-int-}
```
public ImageJoinOptions(int imageJoinMode)
```


Initialisiert eine neue Instanz der [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageJoinMode | int | Der Bildzusammenführungsmodus. |

### ImageJoinOptions(FileType fileType, int imageJoinMode) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-}
```
public ImageJoinOptions(FileType fileType, int imageJoinMode)
```


Initialisiert eine neue Instanz der [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Bilddateityp. |
| imageJoinMode | int | Der Bildzusammenführungsmodus. |

### getType() {#getType--}
```
public final FileType getType()
```


Der Bilddateityp.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getMode() {#getMode--}
```
public final int getMode()
```


Der Bildzusammenführungsmodus.

**Returns:**
int
