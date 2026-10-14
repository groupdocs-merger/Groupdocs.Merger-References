---
title: "TextSplitOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Fournit des options pour la division du texte du document."
type: docs
weight: 39
url: /fr/nodejs-java/com.groupdocs.merger.domain.options/textsplitoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions)
```
public class TextSplitOptions implements ITextSplitOptions
```

Fournit des options pour la division du texte du document.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextSplitOptions(int[] lineNumbers)](#TextSplitOptions-int---) | Initialise une nouvelle instance de la classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(int mode, int[] lineNumbers)](#TextSplitOptions-int-int---) | Initialise une nouvelle instance de la classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(String filePathFormat, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int---) | Initialise une nouvelle instance de la classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int-int---) | Initialise une nouvelle instance de la classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Initialise une nouvelle instance de la classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---) | Initialise une nouvelle instance de la classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMode()](#getMode--) | Mode de division du texte. |
| [getLineNumbers()](#getLineNumbers--) | Numéros de ligne pour la division du texte. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Valide les options de division. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Obtient le chemin complet du fichier du document fractionné par index avec l'extension définie. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory pour créer ou libérer le flux d'aperçu de page de sortie. |
### TextSplitOptions(int[] lineNumbers) {#TextSplitOptions-int---}
```
public TextSplitOptions(int[] lineNumbers)
```


Initialise une nouvelle instance de la classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lineNumbers | int[] | Numéros de ligne pour la division du texte. |

### TextSplitOptions(int mode, int[] lineNumbers) {#TextSplitOptions-int-int---}
```
public TextSplitOptions(int mode, int[] lineNumbers)
```


Initialise une nouvelle instance de la classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mode | int | Mode de division du texte. |
| lineNumbers | int[] | Numéros de ligne pour la division du texte. |

### TextSplitOptions(String filePathFormat, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int---}
```
public TextSplitOptions(String filePathFormat, int[] lineNumbers)
```


Initialise une nouvelle instance de la classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | Le format du chemin de fichier, par ex. 'c:/split\{0\}.doc' ou 'c:/split\{0\}.\{1\}' avec extension déjà définie. |
| lineNumbers | int[] | Numéros de ligne pour la division du texte. |

### TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int-int---}
```
public TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)
```


Initialise une nouvelle instance de la classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | Le format du chemin de fichier, par ex. 'c:/split\{0\}.doc' ou 'c:/split\{0\}.\{1\}' avec extension déjà définie. |
| mode | int | Mode de division du texte. |
| lineNumbers | int[] | Numéros de ligne pour la division du texte. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)
```


Initialise une nouvelle instance de la classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | La méthode qui instancie le flux utilisé pour écrire les données de division en sortie. |
| lineNumbers | int[] | Numéros de ligne pour la division du texte. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)
```


Initialise une nouvelle instance de la classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | La méthode qui instancie le flux utilisé pour écrire les données de division en sortie. |
| mode | int | Mode de division du texte. |
| lineNumbers | int[] | Numéros de ligne pour la division du texte. |

### getMode() {#getMode--}
```
public final int getMode()
```


Mode de division du texte.

**Returns:**
int
### getLineNumbers() {#getLineNumbers--}
```
public final int[] getLineNumbers()
```


Numéros de ligne pour la division du texte.

**Returns:**
int[]
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


Obtient le chemin complet du fichier du document fractionné par index avec l'extension définie.

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
