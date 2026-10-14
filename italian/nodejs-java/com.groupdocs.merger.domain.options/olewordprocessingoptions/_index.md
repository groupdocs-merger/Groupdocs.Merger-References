---
title: "OleWordProcessingOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Fornisce opzioni per l'importazione del documento incorporato in Word processing tramite OLE."
type: docs
weight: 21
url: /it/nodejs-java/com.groupdocs.merger.domain.options/olewordprocessingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleWordProcessingOptions](../../com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions)
```
public class OleWordProcessingOptions extends ImportDocumentOptions implements IOleWordProcessingOptions
```

Fornisce opzioni per l'importazione del documento incorporato in Word processing tramite OLE.

--------------------

**Learn more**

 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]


[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleWordProcessingOptions-byte---byte---java.lang.String-int-) | Inizializza una nuova istanza della classe [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)](#OleWordProcessingOptions-java.lang.String-byte---int-) | Inizializza una nuova istanza della classe [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, int pageNumber)](#OleWordProcessingOptions-java.lang.String-int-) | Inizializza una nuova istanza della classe [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLeft()](#getLeft--) | La coordinata sinistra dell'immagine dell'oggetto Ole. |
| [setLeft(int value)](#setLeft-int-) | La coordinata sinistra dell'immagine dell'oggetto Ole. |
| [getTop()](#getTop--) | La coordinata superiore dell'immagine dell'oggetto Ole. |
| [setTop(int value)](#setTop-int-) | La coordinata superiore dell'immagine dell'oggetto Ole. |
| [getWidth()](#getWidth--) | La larghezza dell'immagine dell'oggetto Ole. |
| [setWidth(int value)](#setWidth-int-) | La larghezza dell'immagine dell'oggetto Ole. |
| [getHeight()](#getHeight--) | L'altezza dell'immagine dell'oggetto Ole. |
| [setHeight(int value)](#setHeight-int-) | L'altezza dell'immagine dell'oggetto Ole. |
| [getImageData()](#getImageData--) | I dati dell'immagine dell'oggetto Ole. |
### OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleWordProcessingOptions-byte---byte---java.lang.String-int-}
```
public OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Inizializza una nuova istanza della classe [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| objectData | byte[] | I dati dell'oggetto incorporato. |
| imageData | byte[] | I dati dell'immagine dell'oggetto incorporato. |
| estensione | java.lang.String | L'estensione dell'oggetto incorporato. |
| pageNumber | int | Il numero di pagina per aggiungere l'oggetto incorporato. |

### OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber) {#OleWordProcessingOptions-java.lang.String-byte---int-}
```
public OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)
```


Inizializza una nuova istanza della classe [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso file dell'oggetto incorporato. |
| imageData | byte[] | I dati dell'immagine dell'oggetto incorporato. |
| pageNumber | int | Il numero di pagina per aggiungere l'oggetto incorporato. |

### OleWordProcessingOptions(String filePath, int pageNumber) {#OleWordProcessingOptions-java.lang.String-int-}
```
public OleWordProcessingOptions(String filePath, int pageNumber)
```


Inizializza una nuova istanza della classe [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso file dell'oggetto incorporato. |
| pageNumber | int | Il numero di pagina per aggiungere l'oggetto incorporato. |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


La coordinata sinistra dell'immagine dell'oggetto Ole.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


La coordinata sinistra dell'immagine dell'oggetto Ole.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


La coordinata superiore dell'immagine dell'oggetto Ole.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


La coordinata superiore dell'immagine dell'oggetto Ole.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


La larghezza dell'immagine dell'oggetto Ole.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


La larghezza dell'immagine dell'oggetto Ole.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


L'altezza dell'immagine dell'oggetto Ole.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


L'altezza dell'immagine dell'oggetto Ole.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


I dati dell'immagine dell'oggetto Ole.

**Returns:**
byte[]
