---
title: "LoadOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Fornisce opzioni per il caricamento del documento."
type: docs
weight: 16
url: /it/nodejs-java/com.groupdocs.merger.domain.options/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Fornisce opzioni per il caricamento del documento.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-) | Inizializza una nuova istanza della classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Inizializza una nuova istanza della classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password, Charset encoding)](#LoadOptions-java.lang.String-java.nio.charset.Charset-) | Inizializza una nuova istanza della classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-) | Inizializza una nuova istanza della classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Inizializza una nuova istanza della classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String extension, FileType fileType, String password, Charset encoding)](#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Inizializza una nuova istanza della classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Inizializza una nuova istanza della classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-) | Inizializza una nuova istanza della classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Inizializza una nuova istanza della classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Il tipo di file da caricare. |
| [getExtension()](#getExtension--) | L'estensione del file da inizializzare. |
| [getPassword()](#getPassword--) | La password per aprire il file protetto da password. |
| [getEncoding()](#getEncoding--) | La codifica utilizzata durante l'apertura di file basati su testo come [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) o [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType fileType)
```


Inizializza una nuova istanza della classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo di file da caricare. |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Inizializza una nuova istanza della classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | java.lang.String | La password per aprire il file protetto da password. |

### LoadOptions(String password, Charset encoding) {#LoadOptions-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String password, Charset encoding)
```


Inizializza una nuova istanza della classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | java.lang.String | La password per aprire il file protetto da password. |
| encoding | java.nio.charset.Charset | La codifica utilizzata durante l'apertura di file basati su testo come [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) o [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType fileType, String password)
```


Inizializza una nuova istanza della classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo di file da caricare. |
| password | java.lang.String | La password per aprire il file protetto da password. |

### LoadOptions(FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType fileType, String password, Charset encoding)
```


Inizializza una nuova istanza della classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo di file da caricare. |
| password | java.lang.String | La password per aprire il file protetto da password. |
| encoding | java.nio.charset.Charset | La codifica utilizzata durante l'apertura di file basati su testo come [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) o [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(String extension, FileType fileType, String password, Charset encoding) {#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String extension, FileType fileType, String password, Charset encoding)
```


Inizializza una nuova istanza della classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| estensione | java.lang.String | L'estensione del file da caricare. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo di file da caricare. |
| password | java.lang.String | La password per aprire il file protetto da password. |
| encoding | java.nio.charset.Charset | La codifica utilizzata durante l'apertura di file basati su testo come [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) o [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)
```


Inizializza una nuova istanza della classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo di file da inizializzare. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo di file da caricare. |
| password | java.lang.String | La password per aprire il file protetto da password. |
| encoding | java.nio.charset.Charset | La codifica utilizzata durante l'apertura di file basati su testo come [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) o [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password)
```


Inizializza una nuova istanza della classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo di file da inizializzare. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo di file da caricare. |
| password | java.lang.String | La password per aprire il file protetto da password. |

### LoadOptions(FileType iniFileType, FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType iniFileType, FileType fileType)
```


Inizializza una nuova istanza della classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo di file da inizializzare. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo di file da caricare. |

### getType() {#getType--}
```
public final FileType getType()
```


Il tipo di file da caricare.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getExtension() {#getExtension--}
```
public final String getExtension()
```


L'estensione del file da inizializzare.

**Returns:**
java.lang.String
### getPassword() {#getPassword--}
```
public final String getPassword()
```


La password per aprire il file protetto da password.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


La codifica utilizzata durante l'apertura di file basati su testo come [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) o [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). Il valore predefinito è System.Text.Encoding.Default (java.nio.charset.Charset).

**Returns:**
java.nio.charset.Charset
