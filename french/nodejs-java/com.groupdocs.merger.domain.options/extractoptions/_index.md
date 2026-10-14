---
title: "ExtractOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Fournit des options pour extraire les pages du document."
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.merger.domain.options/extractoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IExtractOptions](../../com.groupdocs.merger.domain.options.interfaces/iextractoptions)
```
public class ExtractOptions extends PageOptions implements IExtractOptions
```

Fournit des options pour extraire les pages du document.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ExtractOptions()](#ExtractOptions--) | Initialise une nouvelle instance de la classe [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions). |
| [ExtractOptions(int[] pageNumbers)](#ExtractOptions-int---) | Initialise une nouvelle instance de la classe [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions). |
| [ExtractOptions(int startNumber, int endNumber)](#ExtractOptions-int-int-) | Initialise une nouvelle instance de la classe [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions). |
| [ExtractOptions(int startNumber, int endNumber, int mode)](#ExtractOptions-int-int-int-) | Initialise une nouvelle instance de la classe [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions). |
### ExtractOptions() {#ExtractOptions--}
```
public ExtractOptions()
```


Initialise une nouvelle instance de la classe [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions).

### ExtractOptions(int[] pageNumbers) {#ExtractOptions-int---}
```
public ExtractOptions(int[] pageNumbers)
```


Initialise une nouvelle instance de la classe [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumbers | int[] | Numéros de page. |

### ExtractOptions(int startNumber, int endNumber) {#ExtractOptions-int-int-}
```
public ExtractOptions(int startNumber, int endNumber)
```


Initialise une nouvelle instance de la classe [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |

### ExtractOptions(int startNumber, int endNumber, int mode) {#ExtractOptions-int-int-int-}
```
public ExtractOptions(int startNumber, int endNumber, int mode)
```


Initialise une nouvelle instance de la classe [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |
| mode | int | Le mode de plage. |

