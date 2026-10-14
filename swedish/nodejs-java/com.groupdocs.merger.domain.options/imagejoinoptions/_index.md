---
title: "ImageJoinOptions"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Alternativen för bildsammanfogning."
type: docs
weight: 13
url: /sv/nodejs-java/com.groupdocs.merger.domain.options/imagejoinoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/iimagejoinoptions)
```
public class ImageJoinOptions implements IImageJoinOptions
```

Alternativen för bildsammanfogning.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ImageJoinOptions()](#ImageJoinOptions--) | Initierar en ny instans av klassen [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(FileType fileType)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-) | Initierar en ny instans av klassen [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(int imageJoinMode)](#ImageJoinOptions-int-) | Initierar en ny instans av klassen [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(FileType fileType, int imageJoinMode)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-) | Initierar en ny instans av klassen [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getType()](#getType--) | Bildfiltypen. |
| [getMode()](#getMode--) | Läget för bildsammanfogning. |
### ImageJoinOptions() {#ImageJoinOptions--}
```
public ImageJoinOptions()
```


Initierar en ny instans av klassen [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

### ImageJoinOptions(FileType fileType) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public ImageJoinOptions(FileType fileType)
```


Initierar en ny instans av klassen [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Bildfiltypen. |

### ImageJoinOptions(int imageJoinMode) {#ImageJoinOptions-int-}
```
public ImageJoinOptions(int imageJoinMode)
```


Initierar en ny instans av klassen [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageJoinMode | int | Läget för bildsammanfogning. |

### ImageJoinOptions(FileType fileType, int imageJoinMode) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-}
```
public ImageJoinOptions(FileType fileType, int imageJoinMode)
```


Initierar en ny instans av klassen [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Bildfiltypen. |
| imageJoinMode | int | Läget för bildsammanfogning. |

### getType() {#getType--}
```
public final FileType getType()
```


Bildfiltypen.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getMode() {#getMode--}
```
public final int getMode()
```


Läget för bildsammanfogning.

**Returns:**
int
