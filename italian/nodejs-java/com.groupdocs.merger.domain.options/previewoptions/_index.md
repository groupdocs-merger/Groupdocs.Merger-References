---
title: "PreviewOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Rappresenta le opzioni di anteprima del documento."
type: docs
weight: 29
url: /it/nodejs-java/com.groupdocs.merger.domain.options/previewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions)
```
public class PreviewOptions extends PageOptions implements IPreviewOptions
```

Rappresenta le opzioni di anteprima del documento.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-) | Inizializza una nuova istanza della classe [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---) | Inizializza una nuova istanza della classe [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-) | Inizializza una nuova istanza della classe [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-) | Inizializza una nuova istanza della classe [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getWidth()](#getWidth--) | Larghezza dell'anteprima. |
| [setWidth(int value)](#setWidth-int-) | Larghezza dell'anteprima. |
| [getHeight()](#getHeight--) | Altezza dell'anteprima. |
| [setHeight(int value)](#setHeight-int-) | Altezza dell'anteprima. |
| [getResolution()](#getResolution--) | Risoluzione dell'immagine. |
| [setResolution(int value)](#setResolution-int-) | Risoluzione dell'immagine. |
| [getMode()](#getMode--) | Modalità per l'anteprima. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Convalida le opzioni di anteprima. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Ottiene il percorso completo del file del documento in anteprima per numero di pagina con estensione definita. |
| [getPageStreamFactory()](#getPageStreamFactory--) | PageStreamFactory per creare o rilasciare lo stream di anteprima della pagina di output. |
### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)
```


Inizializza una nuova istanza della classe [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Il metodo che istanzia lo stream usato per scrivere i dati della pagina di output. |
| previewMode | int | La modalità di anteprima di Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)
```


Inizializza una nuova istanza della classe [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Il metodo che istanzia lo stream usato per scrivere i dati della pagina di output. |
| previewMode | int | La modalità di anteprima di Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Numeri di pagina. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)
```


Inizializza una nuova istanza della classe [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Il metodo che istanzia lo stream usato per scrivere i dati della pagina di output. |
| previewMode | int | La modalità di anteprima di Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)
```


Inizializza una nuova istanza della classe [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Il metodo che istanzia lo stream usato per scrivere i dati della pagina di output. |
| previewMode | int | La modalità di anteprima di Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |
| mode | int | La modalità di intervallo. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Larghezza dell'anteprima.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Larghezza dell'anteprima.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Altezza dell'anteprima.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Altezza dell'anteprima.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Risoluzione dell'immagine.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Risoluzione dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public final int getMode()
```


Modalità per l'anteprima.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Convalida le opzioni di anteprima.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo di file. |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public final String getPathByPageNumber(int pageNumber, String extension)
```


Ottiene il percorso completo del file del documento in anteprima per numero di pagina con estensione definita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber | int | Numero di pagina dell'anteprima. |
| estensione | java.lang.String | Estensione del file. |

**Returns:**
java.lang.String - Il percorso completo del file.
### getPageStreamFactory() {#getPageStreamFactory--}
```
public PageStreamFactory getPageStreamFactory()
```


PageStreamFactory per creare o rilasciare lo stream di anteprima della pagina di output.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
