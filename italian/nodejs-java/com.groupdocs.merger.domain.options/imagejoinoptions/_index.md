---
title: "ImageJoinOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Le opzioni di unione delle immagini."
type: docs
weight: 13
url: /it/nodejs-java/com.groupdocs.merger.domain.options/imagejoinoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/iimagejoinoptions)
```
public class ImageJoinOptions implements IImageJoinOptions
```

Le opzioni di unione delle immagini.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageJoinOptions()](#ImageJoinOptions--) | Inizializza una nuova istanza della classe [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(FileType fileType)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-) | Inizializza una nuova istanza della classe [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(int imageJoinMode)](#ImageJoinOptions-int-) | Inizializza una nuova istanza della classe [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(FileType fileType, int imageJoinMode)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-) | Inizializza una nuova istanza della classe [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Il tipo di file immagine. |
| [getMode()](#getMode--) | La modalità di unione dell'immagine. |
### ImageJoinOptions() {#ImageJoinOptions--}
```
public ImageJoinOptions()
```


Inizializza una nuova istanza della classe [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

### ImageJoinOptions(FileType fileType) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public ImageJoinOptions(FileType fileType)
```


Inizializza una nuova istanza della classe [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo di file immagine. |

### ImageJoinOptions(int imageJoinMode) {#ImageJoinOptions-int-}
```
public ImageJoinOptions(int imageJoinMode)
```


Inizializza una nuova istanza della classe [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageJoinMode | int | La modalità di unione dell'immagine. |

### ImageJoinOptions(FileType fileType, int imageJoinMode) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-}
```
public ImageJoinOptions(FileType fileType, int imageJoinMode)
```


Inizializza una nuova istanza della classe [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo di file immagine. |
| imageJoinMode | int | La modalità di unione dell'immagine. |

### getType() {#getType--}
```
public final FileType getType()
```


Il tipo di file immagine.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getMode() {#getMode--}
```
public final int getMode()
```


La modalità di unione dell'immagine.

**Returns:**
int
