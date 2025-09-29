---
title: Merger
second_title: GroupDocs.Merger for Java API Reference
description: Represents the main class that controls the document merging process.
type: docs
weight: 10
url: /java/com.groupdocs.merger/merger/
---
**Inheritance:**
java.lang.Object
```
public class Merger
```

Represents the main class that controls the document merging process.
## Constructors

| Constructor | Description |
| --- | --- |
| [Merger(InputStream document)](#Merger-java.io.InputStream-) | Initializes new instance of [Merger](../../com.groupdocs.merger/merger) class. |
| [Merger(InputStream document, ILoadOptions loadOptions)](#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-) | Initializes new instance of [Merger](../../com.groupdocs.merger/merger) class. |
| [Merger(InputStream document, MergerSettings settings)](#Merger-java.io.InputStream-com.groupdocs.merger.MergerSettings-) | Initializes new instance of [Merger](../../com.groupdocs.merger/merger) class. |
| [Merger(InputStream document, ILoadOptions loadOptions, MergerSettings settings)](#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-) | Initializes new instance of [Merger](../../com.groupdocs.merger/merger) class. |
| [Merger(String filePath)](#Merger-java.lang.String-) | Initializes new instance of [Merger](../../com.groupdocs.merger/merger) class. |
| [Merger(String filePath, ILoadOptions loadOptions)](#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-) | Initializes new instance of [Merger](../../com.groupdocs.merger/merger) class. |
| [Merger(String filePath, MergerSettings settings)](#Merger-java.lang.String-com.groupdocs.merger.MergerSettings-) | Initializes new instance of [Merger](../../com.groupdocs.merger/merger) class. |
| [Merger(String filePath, ILoadOptions loadOptions, MergerSettings settings)](#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-) | Initializes new instance of [Merger](../../com.groupdocs.merger/merger) class. |
## Methods

| Method | Description |
| --- | --- |
| [dispose()](#dispose--) | Disposes resources. |
| [importDocument(IImportDocumentOptions importDocumentOptions)](#importDocument-com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions-) | Imports the document as attachment or embedded via Ole. |
| [join(InputStream document)](#join-java.io.InputStream-) | Joins the documents into one single document. |
| [join(InputStream document, IJoinOptions joinOptions)](#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-) | Joins the documents into one single document. |
| [join(InputStream document, IPageJoinOptions joinOptions)](#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-) | Joins the documents into one single document. |
| [join(InputStream document, IImageJoinOptions joinOptions)](#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions-) | Joins the documents into one single document. |
| [join(String filePath)](#join-java.lang.String-) | Joins the documents into one single document. |
| [join(String filePath, IJoinOptions joinOptions)](#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-) | Joins the documents into one single document. |
| [join(String filePath, IPageJoinOptions joinOptions)](#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-) | Joins the documents into one single document. |
| [join(String filePath, IImageJoinOptions joinOptions)](#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions-) | Joins the documents into one single document. |
| [createPageBuilder()](#createPageBuilder--) | Creates a new Page builder with predefined document collection. |
| [createPageBuilder(PageBuilderOptions pageBuilderOptions)](#createPageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | Creates a new Page builder with predefined document collection. |
| [applyPageBuilder(PageBuilder pageBuilder)](#applyPageBuilder-com.groupdocs.merger.domain.builders.PageBuilder-) | Applies page builder changes. |
| [split(ISplitOptions splitOptions)](#split-com.groupdocs.merger.domain.options.interfaces.ISplitOptions-) | Splits the single document to the multiple documents. |
| [split(ITextSplitOptions splitOptions)](#split-com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions-) | Splits the single document to the multiple documents. |
| [extractPages(IExtractOptions extractOptions)](#extractPages-com.groupdocs.merger.domain.options.interfaces.IExtractOptions-) | Makes a new document with some pages from the source document. |
| [addPassword(IAddPasswordOptions addPasswordOptions)](#addPassword-com.groupdocs.merger.domain.options.interfaces.IAddPasswordOptions-) | Protects document with password. |
| [isPasswordSet()](#isPasswordSet--) | Checks whether document is password protected. |
| [removePassword()](#removePassword--) | Removes password from document. |
| [updatePassword(IUpdatePasswordOptions updatePasswordOptions)](#updatePassword-com.groupdocs.merger.domain.options.interfaces.IUpdatePasswordOptions-) | Updates existing password for document. |
| [changeOrientation(IOrientationOptions orientationOptions)](#changeOrientation-com.groupdocs.merger.domain.options.interfaces.IOrientationOptions-) | Applies a new orientation mode for the specified pages. |
| [movePage(IMoveOptions moveOptions)](#movePage-com.groupdocs.merger.domain.options.interfaces.IMoveOptions-) | Moves page to a new position within document of known format. |
| [removePages(IRemoveOptions removeOptions)](#removePages-com.groupdocs.merger.domain.options.interfaces.IRemoveOptions-) | Removes pages from document of known format. |
| [swapPages(ISwapOptions swapOptions)](#swapPages-com.groupdocs.merger.domain.options.interfaces.ISwapOptions-) | Swaps two pages within document of known format. |
| [rotatePages(IRotateOptions rotateOptions)](#rotatePages-com.groupdocs.merger.domain.options.interfaces.IRotateOptions-) | Rotate pages of the document. |
| [getDocumentInfo()](#getDocumentInfo--) | Gets information about document pages: their sizes, maximum page height, the width of a page with the maximum height. |
| [generatePreview(IPreviewOptions previewOptions)](#generatePreview-com.groupdocs.merger.domain.options.interfaces.IPreviewOptions-) | Generates document pages preview. |
| [save(OutputStream document)](#save-java.io.OutputStream-) | Saves the result document to the stream  document . |
| [save(OutputStream document, ISaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.merger.domain.options.interfaces.ISaveOptions-) | Saves the result document to the stream  document . |
| [save(String filePath)](#save-java.lang.String-) | Saves the result document file to  filePath . |
| [save(String filePath, boolean useDefaultDirectory)](#save-java.lang.String-boolean-) | Saves the result document file to  filePath . |
| [save(String filePath, ISaveOptions saveOptions)](#save-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ISaveOptions-) | Saves the result document file to  filePath . |
| [save(String filePath, OutputStream inputStream)](#save-java.lang.String-java.io.OutputStream-) | Saves the result document file to  filePath . |
### Merger(InputStream document) {#Merger-java.io.InputStream-}
```
public Merger(InputStream document)
```


Initializes new instance of [Merger](../../com.groupdocs.merger/merger) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | The readable stream. |

### Merger(InputStream document, ILoadOptions loadOptions) {#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-}
```
public Merger(InputStream document, ILoadOptions loadOptions)
```


Initializes new instance of [Merger](../../com.groupdocs.merger/merger) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | The readable stream. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | The document load options. |

### Merger(InputStream document, MergerSettings settings) {#Merger-java.io.InputStream-com.groupdocs.merger.MergerSettings-}
```
public Merger(InputStream document, MergerSettings settings)
```


Initializes new instance of [Merger](../../com.groupdocs.merger/merger) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | The readable stream. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | The Merger settings. |

### Merger(InputStream document, ILoadOptions loadOptions, MergerSettings settings) {#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-}
```
public Merger(InputStream document, ILoadOptions loadOptions, MergerSettings settings)
```


Initializes new instance of [Merger](../../com.groupdocs.merger/merger) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | The readable stream. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | The document load options. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | The Merger settings. |

### Merger(String filePath) {#Merger-java.lang.String-}
```
public Merger(String filePath)
```


Initializes new instance of [Merger](../../com.groupdocs.merger/merger) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path. |

### Merger(String filePath, ILoadOptions loadOptions) {#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-}
```
public Merger(String filePath, ILoadOptions loadOptions)
```


Initializes new instance of [Merger](../../com.groupdocs.merger/merger) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | The document load options. |

### Merger(String filePath, MergerSettings settings) {#Merger-java.lang.String-com.groupdocs.merger.MergerSettings-}
```
public Merger(String filePath, MergerSettings settings)
```


Initializes new instance of [Merger](../../com.groupdocs.merger/merger) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | The Merger settings. |

### Merger(String filePath, ILoadOptions loadOptions, MergerSettings settings) {#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-}
```
public Merger(String filePath, ILoadOptions loadOptions, MergerSettings settings)
```


Initializes new instance of [Merger](../../com.groupdocs.merger/merger) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | The document load options. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | The Merger settings. |

### dispose() {#dispose--}
```
public final void dispose()
```


Disposes resources.

### importDocument(IImportDocumentOptions importDocumentOptions) {#importDocument-com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions-}
```
public final void importDocument(IImportDocumentOptions importDocumentOptions)
```


Imports the document as attachment or embedded via Ole.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| importDocumentOptions | [IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions) | The embedded document import options.

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


Joins the documents into one single document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | Joined document.

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(InputStream document, IJoinOptions joinOptions) {#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-}
```
public final void join(InputStream document, IJoinOptions joinOptions)
```


Joins the documents into one single document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | Joined document. |
| joinOptions | [IJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ijoinoptions) | The join options.

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(InputStream document, IPageJoinOptions joinOptions) {#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-}
```
public final void join(InputStream document, IPageJoinOptions joinOptions)
```


Joins the documents into one single document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | Joined document. |
| joinOptions | [IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions) | The join options.

--------------------

 **Learn more** 

 *   |

### join(InputStream document, IImageJoinOptions joinOptions) {#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions-}
```
public final void join(InputStream document, IImageJoinOptions joinOptions)
```


Joins the documents into one single document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | Joined document. |
| joinOptions | [IImageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/iimagejoinoptions) | The image join options.

--------------------

 **Learn more** 

 *   |

### join(String filePath) {#join-java.lang.String-}
```
public final void join(String filePath)
```


Joins the documents into one single document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | File path of the joined document.

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(String filePath, IJoinOptions joinOptions) {#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-}
```
public final void join(String filePath, IJoinOptions joinOptions)
```


Joins the documents into one single document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | File path of the joined document. |
| joinOptions | [IJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ijoinoptions) | The join options.

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(String filePath, IPageJoinOptions joinOptions) {#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-}
```
public final void join(String filePath, IPageJoinOptions joinOptions)
```


Joins the documents into one single document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | File path of the joined document. |
| joinOptions | [IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions) | The join options.

--------------------

 **Learn more** 

 *   |

### join(String filePath, IImageJoinOptions joinOptions) {#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions-}
```
public final void join(String filePath, IImageJoinOptions joinOptions)
```


Joins the documents into one single document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | File path of the joined document. |
| joinOptions | [IImageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/iimagejoinoptions) | The image join options.

--------------------

 **Learn more** 

 *   |

### createPageBuilder() {#createPageBuilder--}
```
public final PageBuilder createPageBuilder()
```


Creates a new Page builder with predefined document collection.

**Returns:**
[PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) - The created page builder.
### createPageBuilder(PageBuilderOptions pageBuilderOptions) {#createPageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public final PageBuilder createPageBuilder(PageBuilderOptions pageBuilderOptions)
```


Creates a new Page builder with predefined document collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageBuilderOptions | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) |  |

**Returns:**
[PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) - The created page builder.
### applyPageBuilder(PageBuilder pageBuilder) {#applyPageBuilder-com.groupdocs.merger.domain.builders.PageBuilder-}
```
public final void applyPageBuilder(PageBuilder pageBuilder)
```


Applies page builder changes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageBuilder | [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) | The page builder. |

### split(ISplitOptions splitOptions) {#split-com.groupdocs.merger.domain.options.interfaces.ISplitOptions-}
```
public final void split(ISplitOptions splitOptions)
```


Splits the single document to the multiple documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| splitOptions | [ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions) | The page split options.

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


Splits the single document to the multiple documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| splitOptions | [ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions) | The text split options.

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


Makes a new document with some pages from the source document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extractOptions | [IExtractOptions](../../com.groupdocs.merger.domain.options.interfaces/iextractoptions) | The page options.

--------------------

**Learn more**

 *  More about how to extract specific document pages or page range: [How to extract pages from PDF, Word, Excel and PowerPoint documents][How to extract pages from PDF_ Word_ Excel and PowerPoint documents]


[How to extract pages from PDF_ Word_ Excel and PowerPoint documents]: https://docs.groupdocs.com/merger/java/extract-pages/ |

### addPassword(IAddPasswordOptions addPasswordOptions) {#addPassword-com.groupdocs.merger.domain.options.interfaces.IAddPasswordOptions-}
```
public final void addPassword(IAddPasswordOptions addPasswordOptions)
```


Protects document with password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| addPasswordOptions | [IAddPasswordOptions](../../com.groupdocs.merger.domain.options.interfaces/iaddpasswordoptions) | The options for specifying the password.

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


Checks whether document is password protected.

**Returns:**
boolean - Returns a value indicating whether document is protected or not.

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


Removes password from document.

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


Updates existing password for document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| updatePasswordOptions | [IUpdatePasswordOptions](../../com.groupdocs.merger.domain.options.interfaces/iupdatepasswordoptions) | The options for specifying the current/new passwords.

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


Applies a new orientation mode for the specified pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| orientationOptions | [IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions) | The change orientation options.

--------------------

**Learn more**

 *  More about how to change orientation for Microsoft Word document pages: [How to change Microsoft Word document pages orientation][]


[How to change Microsoft Word document pages orientation]: https://docs.groupdocs.com/merger/java/change-page-orientation/ |

### movePage(IMoveOptions moveOptions) {#movePage-com.groupdocs.merger.domain.options.interfaces.IMoveOptions-}
```
public final void movePage(IMoveOptions moveOptions)
```


Moves page to a new position within document of known format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| moveOptions | [IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions) | The move options.

--------------------

**Learn more**

 *  More about how to move page to another position within document: [How to move PDF, Word, Excel and PowerPoint document pages][How to move PDF_ Word_ Excel and PowerPoint document pages]


[How to move PDF_ Word_ Excel and PowerPoint document pages]: https://docs.groupdocs.com/merger/java/move-page/ |

### removePages(IRemoveOptions removeOptions) {#removePages-com.groupdocs.merger.domain.options.interfaces.IRemoveOptions-}
```
public final void removePages(IRemoveOptions removeOptions)
```


Removes pages from document of known format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| removeOptions | [IRemoveOptions](../../com.groupdocs.merger.domain.options.interfaces/iremoveoptions) | The options for the numbers of pages to be removed.

--------------------

**Learn more**

 *  More about how to remove page from document: [How to remove page from PDF, Word, Excel or PowerPoint document][How to remove page from PDF_ Word_ Excel or PowerPoint document]


[How to remove page from PDF_ Word_ Excel or PowerPoint document]: https://docs.groupdocs.com/merger/java/remove-pages/ |

### swapPages(ISwapOptions swapOptions) {#swapPages-com.groupdocs.merger.domain.options.interfaces.ISwapOptions-}
```
public final void swapPages(ISwapOptions swapOptions)
```


Swaps two pages within document of known format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| swapOptions | [ISwapOptions](../../com.groupdocs.merger.domain.options.interfaces/iswapoptions) | The swap options.

--------------------

**Learn more**

 *  More about how to swap pages positions within document: [How to swap pages inside PDF, Word, Excel or PowerPoint document][How to swap pages inside PDF_ Word_ Excel or PowerPoint document]


[How to swap pages inside PDF_ Word_ Excel or PowerPoint document]: https://docs.groupdocs.com/merger/java/swap-pages/ |

### rotatePages(IRotateOptions rotateOptions) {#rotatePages-com.groupdocs.merger.domain.options.interfaces.IRotateOptions-}
```
public final void rotatePages(IRotateOptions rotateOptions)
```


Rotate pages of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateOptions | [IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions) | The options for the page rotating.

--------------------

**Learn more**

 *  More about how to rotate PDF document pages: [How to rotate PDF document pages][]


[How to rotate PDF document pages]: https://docs.groupdocs.com/merger/java/rotate-pages/ |

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Gets information about document pages: their sizes, maximum page height, the width of a page with the maximum height.

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


Generates document pages preview.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| previewOptions | [IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions) | The preview options.

--------------------

**Learn more**

 *  Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Merger][]


[How to generate document pages preview using GroupDocs.Merger]: https://docs.groupdocs.com/merger/java/generate-document-pages-preview/ |

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


Saves the result document to the stream  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | The document stream. |

### save(OutputStream document, ISaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.merger.domain.options.interfaces.ISaveOptions-}
```
public void save(OutputStream document, ISaveOptions saveOptions)
```


Saves the result document to the stream  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | The document stream. |
| saveOptions | [ISaveOptions](../../com.groupdocs.merger.domain.options.interfaces/isaveoptions) | The options for saving. |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Saves the result document file to  filePath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file name or full file path. |

### save(String filePath, boolean useDefaultDirectory) {#save-java.lang.String-boolean-}
```
public final void save(String filePath, boolean useDefaultDirectory)
```


Saves the result document file to  filePath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path or name in case of default directory usage. |
| useDefaultDirectory | boolean | Use the default directory from settings. |

### save(String filePath, ISaveOptions saveOptions) {#save-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ISaveOptions-}
```
public void save(String filePath, ISaveOptions saveOptions)
```


Saves the result document file to  filePath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path or name in case of default directory usage. |
| saveOptions | [ISaveOptions](../../com.groupdocs.merger.domain.options.interfaces/isaveoptions) | The options for saving. |

### save(String filePath, OutputStream inputStream) {#save-java.lang.String-java.io.OutputStream-}
```
public void save(String filePath, OutputStream inputStream)
```


Saves the result document file to  filePath .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path or name in case of default directory usage. |
| inputStream | java.io.OutputStream | The document stream. |

