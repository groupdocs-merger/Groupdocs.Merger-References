---
title: "PageJoinOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Fournit des options pour la fusion de documents."
type: docs
weight: 25
url: /fr/nodejs-java/com.groupdocs.merger.domain.options/pagejoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions)
```
public class PageJoinOptions extends PageOptions implements IPageJoinOptions
```

Fournit des options pour la fusion de documents.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PageJoinOptions()](#PageJoinOptions--) | Initialise une nouvelle instance de la classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int[] pageNumbers)](#PageJoinOptions-int---) | Initialise une nouvelle instance de la classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int startNumber, int endNumber)](#PageJoinOptions-int-int-) | Initialise une nouvelle instance de la classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int startNumber, int endNumber, int mode)](#PageJoinOptions-int-int-int-) | Initialise une nouvelle instance de la classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-) | Initialise une nouvelle instance de la classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int[] pageNumbers)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---) | Initialise une nouvelle instance de la classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | Initialise une nouvelle instance de la classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | Initialise une nouvelle instance de la classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Le type du fichier à joindre. |
### PageJoinOptions() {#PageJoinOptions--}
```
public PageJoinOptions()
```


Initialise une nouvelle instance de la classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

### PageJoinOptions(int[] pageNumbers) {#PageJoinOptions-int---}
```
public PageJoinOptions(int[] pageNumbers)
```


Initialise une nouvelle instance de la classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumbers | int[] | Numéros de page. |

### PageJoinOptions(int startNumber, int endNumber) {#PageJoinOptions-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber)
```


Initialise une nouvelle instance de la classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |

### PageJoinOptions(int startNumber, int endNumber, int mode) {#PageJoinOptions-int-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber, int mode)
```


Initialise une nouvelle instance de la classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |
| mode | int | Le mode de plage. |

### PageJoinOptions(FileType fileType) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public PageJoinOptions(FileType fileType)
```


Initialise une nouvelle instance de la classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier à joindre. |

### PageJoinOptions(FileType fileType, int[] pageNumbers) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public PageJoinOptions(FileType fileType, int[] pageNumbers)
```


Initialise une nouvelle instance de la classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier à joindre. |
| pageNumbers | int[] | Numéros de page. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber)
```


Initialise une nouvelle instance de la classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier à joindre. |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


Initialise une nouvelle instance de la classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier à joindre. |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |
| mode | int | Le mode de plage. |

### getType() {#getType--}
```
public final FileType getType()
```


Le type du fichier à joindre.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
