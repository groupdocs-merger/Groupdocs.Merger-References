---
title: "OleSpreadsheetOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Fornisce opzioni per l'importazione del documento incorporato in Spreadsheet tramite OLE."
type: docs
weight: 20
url: /it/nodejs-java/com.groupdocs.merger.domain.options/olespreadsheetoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleSpreadsheetOptions](../../com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions)
```
public class OleSpreadsheetOptions extends ImportDocumentOptions implements IOleSpreadsheetOptions
```

Fornisce opzioni per l'importazione del documento incorporato in Spreadsheet tramite OLE.

--------------------

**Learn more**

 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]


[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleSpreadsheetOptions-byte---byte---java.lang.String-int-) | Inizializza una nuova istanza della classe [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
| [OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-byte---int-) | Inizializza una nuova istanza della classe [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
| [OleSpreadsheetOptions(String filePath, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-int-) | Inizializza una nuova istanza della classe [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | L'indice della riga in alto a sinistra. |
| [setRowIndex(int value)](#setRowIndex-int-) | L'indice della riga in alto a sinistra. |
| [getColumnIndex()](#getColumnIndex--) | L'indice della colonna in alto a sinistra. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | L'indice della colonna in alto a sinistra. |
| [getWidth()](#getWidth--) | La larghezza dell'immagine dell'oggetto Ole. |
| [setWidth(int value)](#setWidth-int-) | La larghezza dell'immagine dell'oggetto Ole. |
| [getHeight()](#getHeight--) | L'altezza dell'immagine dell'oggetto Ole. |
| [setHeight(int value)](#setHeight-int-) | L'altezza dell'immagine dell'oggetto Ole. |
| [getImageData()](#getImageData--) | I dati dell'immagine dell'oggetto Ole. |
### OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleSpreadsheetOptions-byte---byte---java.lang.String-int-}
```
public OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Inizializza una nuova istanza della classe [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| objectData | byte[] | I dati dell'oggetto incorporato. |
| imageData | byte[] | I dati dell'immagine dell'oggetto incorporato. |
| estensione | java.lang.String | L'estensione dell'oggetto incorporato. |
| pageNumber | int | Il numero di pagina per aggiungere l'oggetto incorporato. |

### OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-byte---int-}
```
public OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)
```


Inizializza una nuova istanza della classe [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso file dell'oggetto incorporato. |
| imageData | byte[] | I dati dell'immagine dell'oggetto incorporato. |
| pageNumber | int | Il numero di pagina per aggiungere l'oggetto incorporato. |

### OleSpreadsheetOptions(String filePath, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-int-}
```
public OleSpreadsheetOptions(String filePath, int pageNumber)
```


Inizializza una nuova istanza della classe [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso file dell'oggetto incorporato. |
| pageNumber | int | Il numero di pagina per aggiungere l'oggetto incorporato. |

### getRowIndex() {#getRowIndex--}
```
public final int getRowIndex()
```


L'indice della riga in alto a sinistra.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public final void setRowIndex(int value)
```


L'indice della riga in alto a sinistra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public final int getColumnIndex()
```


L'indice della colonna in alto a sinistra.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public final void setColumnIndex(int value)
```


L'indice della colonna in alto a sinistra.

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
