---
title: "OleDiagramOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Fornisce opzioni per l'importazione del documento incorporato in Diagram tramite OLE."
type: docs
weight: 18
url: /it/nodejs-java/com.groupdocs.merger.domain.options/olediagramoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleDiagramOptions](../../com.groupdocs.merger.domain.options.interfaces/iolediagramoptions)
```
public class OleDiagramOptions extends ImportDocumentOptions implements IOleDiagramOptions
```

Fornisce opzioni per l'importazione del documento incorporato in Diagram tramite OLE.

--------------------

**Learn more**

 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleDiagramOptions-byte---byte---java.lang.String-int-) | Inizializza una nuova istanza della classe [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
| [OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)](#OleDiagramOptions-java.lang.String-byte---int-) | Inizializza una nuova istanza della classe [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
| [OleDiagramOptions(String filePath, int pageNumber)](#OleDiagramOptions-java.lang.String-int-) | Inizializza una nuova istanza della classe [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getX()](#getX--) | La coordinata X del perno della forma dell'oggetto incorporato (centro di rotazione) in relazione alla pagina. |
| [setX(int value)](#setX-int-) | La coordinata X del perno della forma dell'oggetto incorporato (centro di rotazione) in relazione alla pagina. |
| [getY()](#getY--) | La coordinata Y del perno della forma dell'oggetto incorporato (centro di rotazione) in relazione alla pagina. |
| [setY(int value)](#setY-int-) | La coordinata Y del perno della forma dell'oggetto incorporato (centro di rotazione) in relazione alla pagina. |
| [getWidth()](#getWidth--) | La larghezza della forma dell'oggetto incorporato in pollici. |
| [setWidth(int value)](#setWidth-int-) | La larghezza della forma dell'oggetto incorporato in pollici. |
| [getHeight()](#getHeight--) | L'altezza della forma dell'oggetto incorporato in pollici. |
| [setHeight(int value)](#setHeight-int-) | L'altezza della forma dell'oggetto incorporato in pollici. |
| [getImageData()](#getImageData--) | I dati dell'immagine dell'oggetto incorporato. |
### OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleDiagramOptions-byte---byte---java.lang.String-int-}
```
public OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Inizializza una nuova istanza della classe [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| objectData | byte[] | I dati dell'oggetto incorporato. |
| imageData | byte[] | I dati dell'immagine dell'oggetto incorporato. |
| estensione | java.lang.String | L'estensione dell'oggetto incorporato. |
| pageNumber | int | Il numero di pagina per aggiungere l'oggetto incorporato. |

### OleDiagramOptions(String filePath, byte[] imageData, int pageNumber) {#OleDiagramOptions-java.lang.String-byte---int-}
```
public OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)
```


Inizializza una nuova istanza della classe [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso file dell'oggetto incorporato. |
| imageData | byte[] | I dati dell'immagine dell'oggetto incorporato. |
| pageNumber | int | Il numero di pagina per aggiungere l'oggetto incorporato. |

### OleDiagramOptions(String filePath, int pageNumber) {#OleDiagramOptions-java.lang.String-int-}
```
public OleDiagramOptions(String filePath, int pageNumber)
```


Inizializza una nuova istanza della classe [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso file dell'oggetto incorporato. |
| pageNumber | int | Il numero di pagina per aggiungere l'oggetto incorporato. |

### getX() {#getX--}
```
public final int getX()
```


La coordinata X del perno della forma dell'oggetto incorporato (centro di rotazione) in relazione alla pagina.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


La coordinata X del perno della forma dell'oggetto incorporato (centro di rotazione) in relazione alla pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


La coordinata Y del perno della forma dell'oggetto incorporato (centro di rotazione) in relazione alla pagina.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


La coordinata Y del perno della forma dell'oggetto incorporato (centro di rotazione) in relazione alla pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


La larghezza della forma dell'oggetto incorporato in pollici.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


La larghezza della forma dell'oggetto incorporato in pollici.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


L'altezza della forma dell'oggetto incorporato in pollici.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


L'altezza della forma dell'oggetto incorporato in pollici.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


I dati dell'immagine dell'oggetto incorporato.

**Returns:**
byte[]
