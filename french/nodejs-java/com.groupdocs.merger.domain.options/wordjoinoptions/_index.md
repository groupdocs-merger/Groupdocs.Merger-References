---
title: "WordJoinOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Les options de fusion Word."
type: docs
weight: 43
url: /fr/nodejs-java/com.groupdocs.merger.domain.options/wordjoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions), [com.groupdocs.merger.domain.options.PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions)
```
public class WordJoinOptions extends PageJoinOptions
```

Les options de fusion Word.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WordJoinOptions()](#WordJoinOptions--) | Initialise une nouvelle instance de la classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(int[] pageNumbers)](#WordJoinOptions-int---) | Initialise une nouvelle instance de la classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(int startNumber, int endNumber)](#WordJoinOptions-int-int-) | Initialise une nouvelle instance de la classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(int startNumber, int endNumber, int mode)](#WordJoinOptions-int-int-int-) | Initialise une nouvelle instance de la classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-) | Initialise une nouvelle instance de la classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType, int[] pageNumbers)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---) | Initialise une nouvelle instance de la classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | Initialise une nouvelle instance de la classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | Initialise une nouvelle instance de la classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMode()](#getMode--) | Le mode de jointure Word. |
| [setMode(int value)](#setMode-int-) | Le mode de jointure Word. |
| [getCompliance()](#getCompliance--) | Mode de conformité pour le format Word Ooxml |
| [setCompliance(int value)](#setCompliance-int-) | Mode de conformité pour le format Word Ooxml |
### WordJoinOptions() {#WordJoinOptions--}
```
public WordJoinOptions()
```


Initialise une nouvelle instance de la classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

### WordJoinOptions(int[] pageNumbers) {#WordJoinOptions-int---}
```
public WordJoinOptions(int[] pageNumbers)
```


Initialise une nouvelle instance de la classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumbers | int[] | Numéros de page. |

### WordJoinOptions(int startNumber, int endNumber) {#WordJoinOptions-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber)
```


Initialise une nouvelle instance de la classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |

### WordJoinOptions(int startNumber, int endNumber, int mode) {#WordJoinOptions-int-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber, int mode)
```


Initialise une nouvelle instance de la classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |
| mode | int | Le mode de plage. |

### WordJoinOptions(FileType fileType) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public WordJoinOptions(FileType fileType)
```


Initialise une nouvelle instance de la classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier à joindre. |

### WordJoinOptions(FileType fileType, int[] pageNumbers) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public WordJoinOptions(FileType fileType, int[] pageNumbers)
```


Initialise une nouvelle instance de la classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier à joindre. |
| pageNumbers | int[] | Numéros de page. |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber)
```


Initialise une nouvelle instance de la classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier à joindre. |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


Initialise une nouvelle instance de la classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier à joindre. |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |
| mode | int | Le mode de plage. |

### getMode() {#getMode--}
```
public final int getMode()
```


Le mode de jointure Word.

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Le mode de jointure Word.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Mode de conformité pour le format Word Ooxml

**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Mode de conformité pour le format Word Ooxml

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

