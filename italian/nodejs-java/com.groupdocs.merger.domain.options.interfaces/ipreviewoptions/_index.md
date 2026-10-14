---
title: "IPreviewOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Interfaccia per le opzioni di anteprima."
type: docs
weight: 28
url: /it/nodejs-java/com.groupdocs.merger.domain.options.interfaces/ipreviewoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface IPreviewOptions extends IPageOptions
```

Interfaccia per le opzioni di anteprima.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getWidth()](#getWidth--) | Larghezza dell'anteprima. |
| [setWidth(int value)](#setWidth-int-) | Larghezza dell'anteprima. |
| [getHeight()](#getHeight--) | Altezza dell'anteprima. |
| [setHeight(int value)](#setHeight-int-) | Altezza dell'anteprima. |
| [getResolution()](#getResolution--) | Risoluzione dell'immagine. |
| [setResolution(int value)](#setResolution-int-) | Risoluzione dell'immagine. |
| [getMode()](#getMode--) | Ottiene la modalità per l'anteprima. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Convalida le opzioni di divisione. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Ottiene il percorso completo del file del documento in anteprima per numero di pagina con estensione definita. |
| [getPageStreamFactory()](#getPageStreamFactory--) | Delegato che definisce il metodo per creare lo stream di anteprima della pagina di output. |
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Larghezza dell'anteprima.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public abstract void setWidth(int value)
```


Larghezza dell'anteprima.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Altezza dell'anteprima.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public abstract void setHeight(int value)
```


Altezza dell'anteprima.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public abstract int getResolution()
```


Risoluzione dell'immagine.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public abstract void setResolution(int value)
```


Risoluzione dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public abstract int getMode()
```


Ottiene la modalità per l'anteprima.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


Convalida le opzioni di divisione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo di file della classe [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public abstract String getPathByPageNumber(int pageNumber, String extension)
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
public abstract PageStreamFactory getPageStreamFactory()
```


Delegato che definisce il metodo per creare lo stream di anteprima della pagina di output.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
