---
title: "SplitOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Fournit des options pour la division des pages du document."
type: docs
weight: 36
url: /fr/nodejs-java/com.groupdocs.merger.domain.options/splitoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions)
```
public class SplitOptions extends PageOptions implements ISplitOptions
```

Fournit des options pour la division des pages du document.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SplitOptions(int[] pageNumbers, int splitMode)](#SplitOptions-int---int-) | Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(int splitMode, int startNumber, int endNumber)](#SplitOptions-int-int-int-) | Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-int-int-int-int-) | Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int[] pageNumbers)](#SplitOptions-java.lang.String-int---) | Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)](#SplitOptions-java.lang.String-int---int-) | Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-) | Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-int-) | Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)](#SplitOptions-java.lang.String-int-int-java.lang.Integer-) | Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-java.lang.String-int-int-int-int-) | Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-) | Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-) | Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-) | Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-) | Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-) | Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-) | Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMode()](#getMode--) | Obtient le mode de division de page. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Valide les options de division. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Obtient le chemin complet du fichier du document fractionné par index avec une extension prédéfinie. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory pour créer ou libérer le flux d'aperçu de page de sortie. |
### SplitOptions(int[] pageNumbers, int splitMode) {#SplitOptions-int---int-}
```
public SplitOptions(int[] pageNumbers, int splitMode)
```


Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumbers | int[] | Numéros de page. |
| splitMode | int | Le mode de fractionnement du Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(int splitMode, int startNumber, int endNumber) {#SplitOptions-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber)
```


Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| splitMode | int | Le mode de fractionnement du Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |

### SplitOptions(int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-int-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber, int mode)
```


Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| splitMode | int | Le mode de fractionnement du Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |
| mode | int | Le mode de plage. |

### SplitOptions(String filePathFormat, int[] pageNumbers) {#SplitOptions-java.lang.String-int---}
```
public SplitOptions(String filePathFormat, int[] pageNumbers)
```


Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | Le format du chemin de fichier, par ex. 'c:/split\{0\}.doc' ou 'c:/split\{0\}.\{1\}' avec une extension déjà prédéfinie. |
| pageNumbers | int[] | Numéros de page. |

### SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode) {#SplitOptions-java.lang.String-int---int-}
```
public SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)
```


Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | Le format du chemin de fichier, par ex. 'c:/split\{0\}.doc' ou 'c:/split\{0\}.\{1\}' avec une extension déjà prédéfinie. |
| pageNumbers | int[] | Numéros de page. |
| splitMode | int | Le mode de fractionnement du Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(String filePathFormat, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber)
```


Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | Le format du chemin de fichier, par ex. 'c:/split\{0\}.doc' ou 'c:/split\{0\}.\{1\}' avec une extension déjà prédéfinie. |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)
```


Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | Le format du chemin de fichier, par ex. 'c:/split\{0\}.doc' ou 'c:/split\{0\}.\{1\}' avec une extension déjà prédéfinie. |
| splitMode | int | Le mode de fractionnement du Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |

### SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode) {#SplitOptions-java.lang.String-int-int-java.lang.Integer-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)
```


Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | Le format du chemin de fichier, par ex. 'c:/split\{0\}.doc' ou 'c:/split\{0\}.\{1\}' avec une extension déjà prédéfinie. |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |
| mode | java.lang.Integer | Le mode de plage. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-java.lang.String-int-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)
```


Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | Le format du chemin de fichier, par ex. 'c:/split\{0\}.doc' ou 'c:/split\{0\}.\{1\}' avec une extension déjà prédéfinie. |
| splitMode | int | Le mode de fractionnement du Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |
| mode | int | Le mode de plage. |

### SplitOptions(SplitStreamFactory splitStreamFactory) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory)
```


Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | La méthode qui instancie le flux utilisé pour écrire les données de division en sortie. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)
```


Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | La méthode qui instancie le flux utilisé pour écrire les données de division en sortie. |
| pageNumbers | int[] | Numéros de page. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)
```


Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | La méthode qui instancie le flux utilisé pour écrire les données de division en sortie. |
| pageNumbers | int[] | Numéros de page. |
| splitMode | int | Le mode de fractionnement du Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)
```


Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | La méthode qui instancie le flux utilisé pour écrire les données de division en sortie. |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)
```


Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | La méthode qui instancie le flux utilisé pour écrire les données de division en sortie. |
| splitMode | int | Le mode de fractionnement du Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)
```


Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | La méthode qui instancie le flux utilisé pour écrire les données de division en sortie. |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |
| mode | java.lang.Integer | Le mode de plage. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)
```


Initialise une nouvelle instance de la classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | La méthode qui instancie le flux utilisé pour écrire les données de division en sortie. |
| splitMode | int | Le mode de fractionnement du Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |
| mode | int | Le mode de plage. |

### getMode() {#getMode--}
```
public final int getMode()
```


Obtient le mode de division de page.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Valide les options de division.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type de fichier de la classe [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


Obtient le chemin complet du fichier du document fractionné par index avec une extension prédéfinie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int | Index du document découpé. |
| extension | java.lang.String | Extension du fichier. |

**Returns:**
java.lang.String - Le chemin complet du fichier.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


SplitStreamFactory pour créer ou libérer le flux d'aperçu de page de sortie.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
