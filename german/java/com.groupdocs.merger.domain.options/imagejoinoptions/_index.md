---
title: "ImageJoinOptions"
second_title: "GroupDocs.Merger für Java API-Referenz"
description: "Die Bildzusammenführungsoptionen."
type: docs
weight: 13
url: /de/java/com.groupdocs.merger.domain.options/imagejoinoptions/
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
| [ImageJoinOptions()](#ImageJoinOptions--) | Initialisiert eine neue Instanz der Klasse [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(FileType fileType)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-) | Initialisiert eine neue Instanz der Klasse [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(int imageJoinMode)](#ImageJoinOptions-int-) | Initialisiert eine neue Instanz der Klasse [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(FileType fileType, int imageJoinMode)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-) | Initialisiert eine neue Instanz der Klasse [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Der Bilddateityp. |
| [getMode()](#getMode--) | Der Bildzusammenführungsmodus. |
### ImageJoinOptions() {#ImageJoinOptions--}
```
public ImageJoinOptions()
```


Initialisiert eine neue Instanz der Klasse [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

### ImageJoinOptions(FileType fileType) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public ImageJoinOptions(FileType fileType)
```


Initialisiert eine neue Instanz der Klasse [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Bilddateityp. |

### ImageJoinOptions(int imageJoinMode) {#ImageJoinOptions-int-}
```
public ImageJoinOptions(int imageJoinMode)
```


Initialisiert eine neue Instanz der Klasse [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageJoinMode | int | Der Bildzusammenführungsmodus. |

### ImageJoinOptions(FileType fileType, int imageJoinMode) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-}
```
public ImageJoinOptions(FileType fileType, int imageJoinMode)
```


Initialisiert eine neue Instanz der Klasse [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

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
