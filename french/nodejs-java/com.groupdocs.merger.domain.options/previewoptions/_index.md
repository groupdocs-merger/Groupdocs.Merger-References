---
title: "PreviewOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Représente les options d'aperçu du document."
type: docs
weight: 29
url: /fr/nodejs-java/com.groupdocs.merger.domain.options/previewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions)
```
public class PreviewOptions extends PageOptions implements IPreviewOptions
```

Représente les options d'aperçu du document.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-) | Initialise une nouvelle instance de la classe [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---) | Initialise une nouvelle instance de la classe [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-) | Initialise une nouvelle instance de la classe [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-) | Initialise une nouvelle instance de la classe [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Largeur de l'aperçu. |
| [setWidth(int value)](#setWidth-int-) | Largeur de l'aperçu. |
| [getHeight()](#getHeight--) | Hauteur de l'aperçu. |
| [setHeight(int value)](#setHeight-int-) | Hauteur de l'aperçu. |
| [getResolution()](#getResolution--) | Résolution de l'image. |
| [setResolution(int value)](#setResolution-int-) | Résolution de l'image. |
| [getMode()](#getMode--) | Mode d'aperçu. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Valide les options d'aperçu. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Obtient le chemin complet du fichier du document prévisualisé par numéro de page avec l'extension définie. |
| [getPageStreamFactory()](#getPageStreamFactory--) | PageStreamFactory pour créer ou libérer le flux d'aperçu de la page de sortie. |
### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)
```


Initialise une nouvelle instance de la classe [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | La méthode qui instancie le flux utilisé pour écrire les données de la page de sortie. |
| previewMode | int | Le mode d'aperçu du Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)
```


Initialise une nouvelle instance de la classe [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | La méthode qui instancie le flux utilisé pour écrire les données de la page de sortie. |
| previewMode | int | Le mode d'aperçu du Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Numéros de page. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)
```


Initialise une nouvelle instance de la classe [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | La méthode qui instancie le flux utilisé pour écrire les données de la page de sortie. |
| previewMode | int | Le mode d'aperçu du Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)
```


Initialise une nouvelle instance de la classe [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | La méthode qui instancie le flux utilisé pour écrire les données de la page de sortie. |
| previewMode | int | Le mode d'aperçu du Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |
| mode | int | Le mode de plage. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Largeur de l'aperçu.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Largeur de l'aperçu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hauteur de l'aperçu.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Hauteur de l'aperçu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Résolution de l'image.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Résolution de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public final int getMode()
```


Mode d'aperçu.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Valide les options d'aperçu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type de fichier. |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public final String getPathByPageNumber(int pageNumber, String extension)
```


Obtient le chemin complet du fichier du document prévisualisé par numéro de page avec l'extension définie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | int | Numéro de page de l'aperçu. |
| extension | java.lang.String | Extension du fichier. |

**Returns:**
java.lang.String - Le chemin complet du fichier.
### getPageStreamFactory() {#getPageStreamFactory--}
```
public PageStreamFactory getPageStreamFactory()
```


PageStreamFactory pour créer ou libérer le flux d'aperçu de la page de sortie.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
