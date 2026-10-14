---
title: "OlePresentationOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Fornisce opzioni per l'importazione del documento incorporato in Presentation tramite OLE."
type: docs
weight: 19
url: /it/nodejs-java/com.groupdocs.merger.domain.options/olepresentationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOlePresentationOptions](../../com.groupdocs.merger.domain.options.interfaces/iolepresentationoptions)
```
public class OlePresentationOptions extends ImportDocumentOptions implements IOlePresentationOptions
```

Fornisce opzioni per l'importazione del documento incorporato in Presentation tramite OLE.

--------------------

**Learn more**

 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]


[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OlePresentationOptions(byte[] objectData, String extension, int pageNumber)](#OlePresentationOptions-byte---java.lang.String-int-) | Inizializza una nuova istanza della classe [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions). |
| [OlePresentationOptions(String filePath, int pageNumber)](#OlePresentationOptions-java.lang.String-int-) | Inizializza una nuova istanza della classe [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getX()](#getX--) | La coordinata X del frame dell'oggetto incorporato. |
| [setX(int value)](#setX-int-) | La coordinata X del frame dell'oggetto incorporato. |
| [getY()](#getY--) | La coordinata Y del frame dell'oggetto incorporato. |
| [setY(int value)](#setY-int-) | La coordinata Y del frame dell'oggetto incorporato. |
| [getWidth()](#getWidth--) | La larghezza del riquadro dell'oggetto incorporato. |
| [setWidth(int value)](#setWidth-int-) | La larghezza del riquadro dell'oggetto incorporato. |
| [getHeight()](#getHeight--) | L'altezza del riquadro dell'oggetto incorporato. |
| [setHeight(int value)](#setHeight-int-) | L'altezza del riquadro dell'oggetto incorporato. |
### OlePresentationOptions(byte[] objectData, String extension, int pageNumber) {#OlePresentationOptions-byte---java.lang.String-int-}
```
public OlePresentationOptions(byte[] objectData, String extension, int pageNumber)
```


Inizializza una nuova istanza della classe [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| objectData | byte[] | I dati dell'oggetto incorporato. |
| estensione | java.lang.String | L'estensione dell'oggetto incorporato. |
| pageNumber | int | Il numero di pagina per aggiungere l'oggetto incorporato. |

### OlePresentationOptions(String filePath, int pageNumber) {#OlePresentationOptions-java.lang.String-int-}
```
public OlePresentationOptions(String filePath, int pageNumber)
```


Inizializza una nuova istanza della classe [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso file dell'oggetto incorporato. |
| pageNumber | int | Il numero di pagina per aggiungere l'oggetto incorporato. |

### getX() {#getX--}
```
public final int getX()
```


La coordinata X del frame dell'oggetto incorporato.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


La coordinata X del frame dell'oggetto incorporato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


La coordinata Y del frame dell'oggetto incorporato.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


La coordinata Y del frame dell'oggetto incorporato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


La larghezza del riquadro dell'oggetto incorporato.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


La larghezza del riquadro dell'oggetto incorporato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


L'altezza del riquadro dell'oggetto incorporato.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


L'altezza del riquadro dell'oggetto incorporato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

