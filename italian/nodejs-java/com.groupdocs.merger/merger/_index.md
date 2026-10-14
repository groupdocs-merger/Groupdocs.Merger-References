---
title: "Merger"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Rappresenta la classe principale che controlla il processo di unione dei documenti."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.merger/merger/
---
**Inheritance:**
java.lang.Object
```
public class Merger
```

Rappresenta la classe principale che controlla il processo di unione dei documenti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Merger(InputStream document)](#Merger-java.io.InputStream-) | Inizializza una nuova istanza della classe [Merger](../../com.groupdocs.merger/merger). |
| [Merger(InputStream document, ILoadOptions loadOptions)](#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-) | Inizializza una nuova istanza della classe [Merger](../../com.groupdocs.merger/merger). |
| [Merger(InputStream document, MergerSettings settings)](#Merger-java.io.InputStream-com.groupdocs.merger.MergerSettings-) | Inizializza una nuova istanza della classe [Merger](../../com.groupdocs.merger/merger). |
| [Merger(InputStream document, ILoadOptions loadOptions, MergerSettings settings)](#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-) | Inizializza una nuova istanza della classe [Merger](../../com.groupdocs.merger/merger). |
| [Merger(String filePath)](#Merger-java.lang.String-) | Inizializza una nuova istanza della classe [Merger](../../com.groupdocs.merger/merger). |
| [Merger(String filePath, ILoadOptions loadOptions)](#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-) | Inizializza una nuova istanza della classe [Merger](../../com.groupdocs.merger/merger). |
| [Merger(String filePath, MergerSettings settings)](#Merger-java.lang.String-com.groupdocs.merger.MergerSettings-) | Inizializza una nuova istanza della classe [Merger](../../com.groupdocs.merger/merger). |
| [Merger(String filePath, ILoadOptions loadOptions, MergerSettings settings)](#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-) | Inizializza una nuova istanza della classe [Merger](../../com.groupdocs.merger/merger). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [dispose()](#dispose--) | Rilascia le risorse. |
| [importDocument(IImportDocumentOptions importDocumentOptions)](#importDocument-com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions-) | Importa il documento come allegato o incorporato tramite Ole. |
| [join(InputStream document)](#join-java.io.InputStream-) | Unisce i documenti in un unico documento. |
| [join(InputStream document, IJoinOptions joinOptions)](#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-) | Unisce i documenti in un unico documento. |
| [join(InputStream document, IPageJoinOptions joinOptions)](#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-) | Unisce i documenti in un unico documento. |
| [join(InputStream document, ImageJoinOptions joinOptions)](#join-java.io.InputStream-com.groupdocs.merger.domain.options.ImageJoinOptions-) | Unisce i documenti in un unico documento. |
| [join(String filePath)](#join-java.lang.String-) | Unisce i documenti in un unico documento. |
| [join(String filePath, IJoinOptions joinOptions)](#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-) | Unisce i documenti in un unico documento. |
| [join(String filePath, IPageJoinOptions joinOptions)](#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-) | Unisce i documenti in un unico documento. |
| [join(String filePath, ImageJoinOptions joinOptions)](#join-java.lang.String-com.groupdocs.merger.domain.options.ImageJoinOptions-) | Unisce i documenti in un unico documento. |
| [createPageBuilder()](#createPageBuilder--) | Crea un nuovo Page builder con una raccolta di documenti predefinita. |
| [createPageBuilder(PageBuilderOptions pageBuilderOptions)](#createPageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | Crea un nuovo Page builder con una raccolta di documenti predefinita. |
| [applyPageBuilder(PageBuilder pageBuilder)](#applyPageBuilder-com.groupdocs.merger.domain.builders.PageBuilder-) | Applica le modifiche del page builder. |
| [split(ISplitOptions splitOptions)](#split-com.groupdocs.merger.domain.options.interfaces.ISplitOptions-) | Divide il documento unico in più documenti. |
| [split(ITextSplitOptions splitOptions)](#split-com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions-) | Divide il documento unico in più documenti. |
| [extractPages(IExtractOptions extractOptions)](#extractPages-com.groupdocs.merger.domain.options.interfaces.IExtractOptions-) | Crea un nuovo documento con alcune pagine dal documento di origine. |
| [addPassword(IAddPasswordOptions addPasswordOptions)](#addPassword-com.groupdocs.merger.domain.options.interfaces.IAddPasswordOptions-) | Protegge il documento con una password. |
| [isPasswordSet()](#isPasswordSet--) | Verifica se il documento è protetto da password. |
| [removePassword()](#removePassword--) | Rimuove la password dal documento. |
| [updatePassword(IUpdatePasswordOptions updatePasswordOptions)](#updatePassword-com.groupdocs.merger.domain.options.interfaces.IUpdatePasswordOptions-) | Aggiorna la password esistente per il documento. |
| [changeOrientation(IOrientationOptions orientationOptions)](#changeOrientation-com.groupdocs.merger.domain.options.interfaces.IOrientationOptions-) | Applica una nuova modalità di orientamento per le pagine specificate. |
| [movePage(IMoveOptions moveOptions)](#movePage-com.groupdocs.merger.domain.options.interfaces.IMoveOptions-) | Sposta la pagina in una nuova posizione all'interno del documento di formato noto. |
| [removePages(IRemoveOptions removeOptions)](#removePages-com.groupdocs.merger.domain.options.interfaces.IRemoveOptions-) | Rimuove le pagine dal documento di formato noto. |
| [swapPages(ISwapOptions swapOptions)](#swapPages-com.groupdocs.merger.domain.options.interfaces.ISwapOptions-) | Scambia due pagine all'interno del documento di formato noto. |
| [rotatePages(IRotateOptions rotateOptions)](#rotatePages-com.groupdocs.merger.domain.options.interfaces.IRotateOptions-) | Ruota le pagine del documento. |
| [getDocumentInfo()](#getDocumentInfo--) | Ottiene informazioni sulle pagine del documento: le loro dimensioni, l'altezza massima della pagina, la larghezza di una pagina con l'altezza massima. |
| [generatePreview(IPreviewOptions previewOptions)](#generatePreview-com.groupdocs.merger.domain.options.interfaces.IPreviewOptions-) | Genera l'anteprima delle pagine del documento. |
| [save(OutputStream document)](#save-java.io.OutputStream-) | Salva il documento risultante nello stream  document . |
| [save(String filePath)](#save-java.lang.String-) | Salva il file del documento risultante in  filePath . |
| [save(String filePath, boolean useDefaultDirectory)](#save-java.lang.String-boolean-) | Salva il file del documento risultante in  filePath . |
### Merger(InputStream document) {#Merger-java.io.InputStream-}
```
public Merger(InputStream document)
```


Inizializza una nuova istanza della classe [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.InputStream | Lo stream leggibile. |

### Merger(InputStream document, ILoadOptions loadOptions) {#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-}
```
public Merger(InputStream document, ILoadOptions loadOptions)
```


Inizializza una nuova istanza della classe [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.InputStream | Lo stream leggibile. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | Le opzioni di caricamento del documento. |

### Merger(InputStream document, MergerSettings settings) {#Merger-java.io.InputStream-com.groupdocs.merger.MergerSettings-}
```
public Merger(InputStream document, MergerSettings settings)
```


Inizializza una nuova istanza della classe [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.InputStream | Lo stream leggibile. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | Le impostazioni del Merger. |

### Merger(InputStream document, ILoadOptions loadOptions, MergerSettings settings) {#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-}
```
public Merger(InputStream document, ILoadOptions loadOptions, MergerSettings settings)
```


Inizializza una nuova istanza della classe [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.InputStream | Lo stream leggibile. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | Le opzioni di caricamento del documento. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | Le impostazioni del Merger. |

### Merger(String filePath) {#Merger-java.lang.String-}
```
public Merger(String filePath)
```


Inizializza una nuova istanza della classe [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file. |

### Merger(String filePath, ILoadOptions loadOptions) {#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-}
```
public Merger(String filePath, ILoadOptions loadOptions)
```


Inizializza una nuova istanza della classe [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | Le opzioni di caricamento del documento. |

### Merger(String filePath, MergerSettings settings) {#Merger-java.lang.String-com.groupdocs.merger.MergerSettings-}
```
public Merger(String filePath, MergerSettings settings)
```


Inizializza una nuova istanza della classe [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | Le impostazioni del Merger. |

### Merger(String filePath, ILoadOptions loadOptions, MergerSettings settings) {#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-}
```
public Merger(String filePath, ILoadOptions loadOptions, MergerSettings settings)
```


Inizializza una nuova istanza della classe [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | Le opzioni di caricamento del documento. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | Le impostazioni del Merger. |

### dispose() {#dispose--}
```
public final void dispose()
```


Rilascia le risorse.

### importDocument(IImportDocumentOptions importDocumentOptions) {#importDocument-com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions-}
```
public final void importDocument(IImportDocumentOptions importDocumentOptions)
```


Importa il documento come allegato o incorporato tramite Ole.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | importDocumentOptions | [IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions) | Le opzioni di importazione del documento incorporato. |

--------------------

**Learn more**

 *  More about adding attachment to PDF documents: [How to add attachment to PDF document.][]
 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]
 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]
 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]
 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[How to add attachment to PDF document.]: https://docs.groupdocs.com/merger/java/how-to-add-attachment-to-pdf-document/
[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/ |

### join(InputStream document) {#join-java.io.InputStream-}
```
public final void join(InputStream document)
```


Unisce i documenti in un unico documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.io.InputStream | Documento unito. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(InputStream document, IJoinOptions joinOptions) {#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-}
```
public final void join(InputStream document, IJoinOptions joinOptions)
```


Unisce i documenti in un unico documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.InputStream | Documento unito. |
|  | joinOptions | [IJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ijoinoptions) | Le opzioni di unione. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(InputStream document, IPageJoinOptions joinOptions) {#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-}
```
public final void join(InputStream document, IPageJoinOptions joinOptions)
```


Unisce i documenti in un unico documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.InputStream | Documento unito. |
|  | joinOptions | [IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions) | Le opzioni di unione. |

--------------------

 **Learn more** 

 *   |

### join(InputStream document, ImageJoinOptions joinOptions) {#join-java.io.InputStream-com.groupdocs.merger.domain.options.ImageJoinOptions-}
```
public final void join(InputStream document, ImageJoinOptions joinOptions)
```


Unisce i documenti in un unico documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.InputStream | Documento unito. |
|  | joinOptions | [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) | Le opzioni di unione delle immagini. |

--------------------

 **Learn more** 

 *   |

### join(String filePath) {#join-java.lang.String-}
```
public final void join(String filePath)
```


Unisce i documenti in un unico documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Percorso del file del documento unito. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(String filePath, IJoinOptions joinOptions) {#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-}
```
public final void join(String filePath, IJoinOptions joinOptions)
```


Unisce i documenti in un unico documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Percorso del file del documento unito. |
|  | joinOptions | [IJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ijoinoptions) | Le opzioni di unione. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(String filePath, IPageJoinOptions joinOptions) {#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-}
```
public final void join(String filePath, IPageJoinOptions joinOptions)
```


Unisce i documenti in un unico documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Percorso del file del documento unito. |
|  | joinOptions | [IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions) | Le opzioni di unione. |

--------------------

 **Learn more** 

 *   |

### join(String filePath, ImageJoinOptions joinOptions) {#join-java.lang.String-com.groupdocs.merger.domain.options.ImageJoinOptions-}
```
public final void join(String filePath, ImageJoinOptions joinOptions)
```


Unisce i documenti in un unico documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Percorso del file del documento unito. |
|  | joinOptions | [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) | Le opzioni di unione delle immagini. |

--------------------

 **Learn more** 

 *   |

### createPageBuilder() {#createPageBuilder--}
```
public final PageBuilder createPageBuilder()
```


Crea un nuovo Page builder con una raccolta di documenti predefinita.

**Returns:**
[PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) - The created page builder.
### createPageBuilder(PageBuilderOptions pageBuilderOptions) {#createPageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public final PageBuilder createPageBuilder(PageBuilderOptions pageBuilderOptions)
```


Crea un nuovo Page builder con una raccolta di documenti predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageBuilderOptions | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) |  |

**Returns:**
[PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) - The created page builder.
### applyPageBuilder(PageBuilder pageBuilder) {#applyPageBuilder-com.groupdocs.merger.domain.builders.PageBuilder-}
```
public final void applyPageBuilder(PageBuilder pageBuilder)
```


Applica le modifiche del page builder.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageBuilder | [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) | Il costruttore di pagine. |

### split(ISplitOptions splitOptions) {#split-com.groupdocs.merger.domain.options.interfaces.ISplitOptions-}
```
public final void split(ISplitOptions splitOptions)
```


Divide il documento unico in più documenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | splitOptions | [ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions) | Le opzioni di divisione della pagina. |

--------------------

**Learn more**

 *  More about document split scenarios and use cases: [How to split PDF, Word, Excel and PowerPoint documents in 3 lines of code][How to split PDF_ Word_ Excel and PowerPoint documents in 3 lines of code]
 *  Quick guide about how to split text files in different ways: [Split text files guide][]


[How to split PDF_ Word_ Excel and PowerPoint documents in 3 lines of code]: https://docs.groupdocs.com/merger/java/split-document/
[Split text files guide]: https://docs.groupdocs.com/merger/java/split-text-file/ |

### split(ITextSplitOptions splitOptions) {#split-com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions-}
```
public final void split(ITextSplitOptions splitOptions)
```


Divide il documento unico in più documenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | splitOptions | [ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions) | Le opzioni di divisione del testo. |

--------------------

**Learn more**

 *  More about document split scenarios and use cases: [How to split PDF, Word, Excel and PowerPoint documents in 3 lines of code][How to split PDF_ Word_ Excel and PowerPoint documents in 3 lines of code]
 *  Quick guide about how to split text files in different ways: [Split text files guide][]


[How to split PDF_ Word_ Excel and PowerPoint documents in 3 lines of code]: https://docs.groupdocs.com/merger/java/split-document/
[Split text files guide]: https://docs.groupdocs.com/merger/java/split-text-file/ |

### extractPages(IExtractOptions extractOptions) {#extractPages-com.groupdocs.merger.domain.options.interfaces.IExtractOptions-}
```
public final void extractPages(IExtractOptions extractOptions)
```


Crea un nuovo documento con alcune pagine dal documento di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | extractOptions | [IExtractOptions](../../com.groupdocs.merger.domain.options.interfaces/iextractoptions) | Le opzioni della pagina. |

--------------------

**Learn more**

 *  More about how to extract specific document pages or page range: [How to extract pages from PDF, Word, Excel and PowerPoint documents][How to extract pages from PDF_ Word_ Excel and PowerPoint documents]


[How to extract pages from PDF_ Word_ Excel and PowerPoint documents]: https://docs.groupdocs.com/merger/java/extract-pages/ |

### addPassword(IAddPasswordOptions addPasswordOptions) {#addPassword-com.groupdocs.merger.domain.options.interfaces.IAddPasswordOptions-}
```
public final void addPassword(IAddPasswordOptions addPasswordOptions)
```


Protegge il documento con una password.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | addPasswordOptions | [IAddPasswordOptions](../../com.groupdocs.merger.domain.options.interfaces/iaddpasswordoptions) | Le opzioni per specificare la password. |

--------------------

**Learn more**

 *  More about how to protect document with password: [How to protect PDF, Word, Excel and PowerPoint documents with password][How to protect PDF_ Word_ Excel and PowerPoint documents with password]
 *  More about how to update or change document password: [How to change document password][]
 *  More about how to check document password protected or not: [How to check document password protection][]
 *  More about how to remove document password: [How to remove PDF, Word, Excel and PowerPoint documents password][How to remove PDF_ Word_ Excel and PowerPoint documents password]


[How to protect PDF_ Word_ Excel and PowerPoint documents with password]: https://docs.groupdocs.com/merger/java/add-document-password/
[How to change document password]: https://docs.groupdocs.com/merger/java/update-document-password/
[How to check document password protection]: https://docs.groupdocs.com/merger/java/check-document-password-protection/
[How to remove PDF_ Word_ Excel and PowerPoint documents password]: https://docs.groupdocs.com/merger/java/remove-document-password/ |

### isPasswordSet() {#isPasswordSet--}
```
public final boolean isPasswordSet()
```


Verifica se il documento è protetto da password.

**Returns:**
boolean - Restituisce un valore che indica se il documento è protetto o meno.

--------------------

**Learn more**

 *  More about how to protect document with password: [How to protect PDF, Word, Excel and PowerPoint documents with password][How to protect PDF_ Word_ Excel and PowerPoint documents with password]
 *  More about how to update or change document password: [How to change document password][]
 *  More about how to check document password protected or not: [How to check document password protection][]
 *  More about how to remove document password: [How to remove PDF, Word, Excel and PowerPoint documents password][How to remove PDF_ Word_ Excel and PowerPoint documents password]


[How to protect PDF_ Word_ Excel and PowerPoint documents with password]: https://docs.groupdocs.com/merger/java/add-document-password/
[How to change document password]: https://docs.groupdocs.com/merger/java/update-document-password/
[How to check document password protection]: https://docs.groupdocs.com/merger/java/check-document-password-protection/
[How to remove PDF_ Word_ Excel and PowerPoint documents password]: https://docs.groupdocs.com/merger/java/remove-document-password/
### removePassword() {#removePassword--}
```
public final void removePassword()
```


Rimuove la password dal documento.

--------------------

**Learn more**

 *  More about how to protect document with password: [How to protect PDF, Word, Excel and PowerPoint documents with password][How to protect PDF_ Word_ Excel and PowerPoint documents with password]
 *  More about how to update or change document password: [How to change document password][]
 *  More about how to check document password protected or not: [How to check document password protection][]
 *  More about how to remove document password: [How to remove PDF, Word, Excel and PowerPoint documents password][How to remove PDF_ Word_ Excel and PowerPoint documents password]


[How to protect PDF_ Word_ Excel and PowerPoint documents with password]: https://docs.groupdocs.com/merger/java/add-document-password/
[How to change document password]: https://docs.groupdocs.com/merger/java/update-document-password/
[How to check document password protection]: https://docs.groupdocs.com/merger/java/check-document-password-protection/
[How to remove PDF_ Word_ Excel and PowerPoint documents password]: https://docs.groupdocs.com/merger/java/remove-document-password/

### updatePassword(IUpdatePasswordOptions updatePasswordOptions) {#updatePassword-com.groupdocs.merger.domain.options.interfaces.IUpdatePasswordOptions-}
```
public final void updatePassword(IUpdatePasswordOptions updatePasswordOptions)
```


Aggiorna la password esistente per il documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | updatePasswordOptions | [IUpdatePasswordOptions](../../com.groupdocs.merger.domain.options.interfaces/iupdatepasswordoptions) | Le opzioni per specificare le password attuali/nuove. |

--------------------

**Learn more**

 *  More about how to protect document with password: [How to protect PDF, Word, Excel and PowerPoint documents with password][How to protect PDF_ Word_ Excel and PowerPoint documents with password]
 *  More about how to update or change document password: [How to change document password][]
 *  More about how to check document password protected or not: [How to check document password protection][]
 *  More about how to remove document password: [How to remove PDF, Word, Excel and PowerPoint documents password][How to remove PDF_ Word_ Excel and PowerPoint documents password]


[How to protect PDF_ Word_ Excel and PowerPoint documents with password]: https://docs.groupdocs.com/merger/java/add-document-password/
[How to change document password]: https://docs.groupdocs.com/merger/java/update-document-password/
[How to check document password protection]: https://docs.groupdocs.com/merger/java/check-document-password-protection/
[How to remove PDF_ Word_ Excel and PowerPoint documents password]: https://docs.groupdocs.com/merger/java/remove-document-password/ |

### changeOrientation(IOrientationOptions orientationOptions) {#changeOrientation-com.groupdocs.merger.domain.options.interfaces.IOrientationOptions-}
```
public final void changeOrientation(IOrientationOptions orientationOptions)
```


Applica una nuova modalità di orientamento per le pagine specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | orientationOptions | [IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions) | Le opzioni di cambio orientamento. |

--------------------

**Learn more**

 *  More about how to change orientation for Microsoft Word document pages: [How to change Microsoft Word document pages orientation][]


[How to change Microsoft Word document pages orientation]: https://docs.groupdocs.com/merger/java/change-page-orientation/ |

### movePage(IMoveOptions moveOptions) {#movePage-com.groupdocs.merger.domain.options.interfaces.IMoveOptions-}
```
public final void movePage(IMoveOptions moveOptions)
```


Sposta la pagina in una nuova posizione all'interno del documento di formato noto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | moveOptions | [IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions) | Le opzioni di spostamento. |

--------------------

**Learn more**

 *  More about how to move page to another position within document: [How to move PDF, Word, Excel and PowerPoint document pages][How to move PDF_ Word_ Excel and PowerPoint document pages]


[How to move PDF_ Word_ Excel and PowerPoint document pages]: https://docs.groupdocs.com/merger/java/move-page/ |

### removePages(IRemoveOptions removeOptions) {#removePages-com.groupdocs.merger.domain.options.interfaces.IRemoveOptions-}
```
public final void removePages(IRemoveOptions removeOptions)
```


Rimuove le pagine dal documento di formato noto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | removeOptions | [IRemoveOptions](../../com.groupdocs.merger.domain.options.interfaces/iremoveoptions) | Le opzioni per il numero di pagine da rimuovere. |

--------------------

**Learn more**

 *  More about how to remove page from document: [How to remove page from PDF, Word, Excel or PowerPoint document][How to remove page from PDF_ Word_ Excel or PowerPoint document]


[How to remove page from PDF_ Word_ Excel or PowerPoint document]: https://docs.groupdocs.com/merger/java/remove-pages/ |

### swapPages(ISwapOptions swapOptions) {#swapPages-com.groupdocs.merger.domain.options.interfaces.ISwapOptions-}
```
public final void swapPages(ISwapOptions swapOptions)
```


Scambia due pagine all'interno del documento di formato noto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | swapOptions | [ISwapOptions](../../com.groupdocs.merger.domain.options.interfaces/iswapoptions) | Le opzioni di scambio. |

--------------------

**Learn more**

 *  More about how to swap pages positions within document: [How to swap pages inside PDF, Word, Excel or PowerPoint document][How to swap pages inside PDF_ Word_ Excel or PowerPoint document]


[How to swap pages inside PDF_ Word_ Excel or PowerPoint document]: https://docs.groupdocs.com/merger/java/swap-pages/ |

### rotatePages(IRotateOptions rotateOptions) {#rotatePages-com.groupdocs.merger.domain.options.interfaces.IRotateOptions-}
```
public final void rotatePages(IRotateOptions rotateOptions)
```


Ruota le pagine del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | rotateOptions | [IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions) | Le opzioni per la rotazione della pagina. |

--------------------

**Learn more**

 *  More about how to rotate PDF document pages: [How to rotate PDF document pages][]


[How to rotate PDF document pages]: https://docs.groupdocs.com/merger/java/rotate-pages/ |

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Ottiene informazioni sulle pagine del documento: le loro dimensioni, l'altezza massima della pagina, la larghezza di una pagina con l'altezza massima.

**Returns:**
[IDocumentInfo](../../com.groupdocs.merger.domain.result/idocumentinfo) - Information about document properties.

--------------------

**Learn more**

 *  Learn more about document file type, pages count, size and many other format specific properties: [How to get document info using GroupDocs.Merger][]


[How to get document info using GroupDocs.Merger]: https://docs.groupdocs.com/merger/java/get-document-information/
### generatePreview(IPreviewOptions previewOptions) {#generatePreview-com.groupdocs.merger.domain.options.interfaces.IPreviewOptions-}
```
public final void generatePreview(IPreviewOptions previewOptions)
```


Genera l'anteprima delle pagine del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | previewOptions | [IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions) | Le opzioni di anteprima. |

--------------------

**Learn more**

 *  Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Merger][]


[How to generate document pages preview using GroupDocs.Merger]: https://docs.groupdocs.com/merger/java/generate-document-pages-preview/ |

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


Salva il documento risultante nello stream  document .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | java.io.OutputStream | Il flusso del documento. |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Salva il file del documento risultante in  filePath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il nome del file o il percorso completo del file. |

### save(String filePath, boolean useDefaultDirectory) {#save-java.lang.String-boolean-}
```
public final void save(String filePath, boolean useDefaultDirectory)
```


Salva il file del documento risultante in  filePath .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso o il nome del file in caso di utilizzo della directory predefinita. |
| useDefaultDirectory | boolean | Utilizza la directory predefinita dalle impostazioni. |

