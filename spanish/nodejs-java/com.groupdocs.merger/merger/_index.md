---
title: "Fusionador"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Representa la clase principal que controla el proceso de combinación de documentos."
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.merger/merger/
---
**Inheritance:**
java.lang.Object
```
public class Merger
```

Representa la clase principal que controla el proceso de combinación de documentos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Merger(InputStream document)](#Merger-java.io.InputStream-) | Inicializa una nueva instancia de la clase [Merger](../../com.groupdocs.merger/merger). |
| [Merger(InputStream document, ILoadOptions loadOptions)](#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-) | Inicializa una nueva instancia de la clase [Merger](../../com.groupdocs.merger/merger). |
| [Merger(InputStream document, MergerSettings settings)](#Merger-java.io.InputStream-com.groupdocs.merger.MergerSettings-) | Inicializa una nueva instancia de la clase [Merger](../../com.groupdocs.merger/merger). |
| [Merger(InputStream document, ILoadOptions loadOptions, MergerSettings settings)](#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-) | Inicializa una nueva instancia de la clase [Merger](../../com.groupdocs.merger/merger). |
| [Merger(String filePath)](#Merger-java.lang.String-) | Inicializa una nueva instancia de la clase [Merger](../../com.groupdocs.merger/merger). |
| [Merger(String filePath, ILoadOptions loadOptions)](#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-) | Inicializa una nueva instancia de la clase [Merger](../../com.groupdocs.merger/merger). |
| [Merger(String filePath, MergerSettings settings)](#Merger-java.lang.String-com.groupdocs.merger.MergerSettings-) | Inicializa una nueva instancia de la clase [Merger](../../com.groupdocs.merger/merger). |
| [Merger(String filePath, ILoadOptions loadOptions, MergerSettings settings)](#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-) | Inicializa una nueva instancia de la clase [Merger](../../com.groupdocs.merger/merger). |
## Métodos

| Método | Descripción |
| --- | --- |
| [dispose()](#dispose--) | Libera los recursos. |
| [importDocument(IImportDocumentOptions importDocumentOptions)](#importDocument-com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions-) | Importa el documento como adjunto o incrustado mediante Ole. |
| [join(InputStream document)](#join-java.io.InputStream-) | Une los documentos en un solo documento. |
| [join(InputStream document, IJoinOptions joinOptions)](#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-) | Une los documentos en un solo documento. |
| [join(InputStream document, IPageJoinOptions joinOptions)](#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-) | Une los documentos en un solo documento. |
| [join(InputStream document, ImageJoinOptions joinOptions)](#join-java.io.InputStream-com.groupdocs.merger.domain.options.ImageJoinOptions-) | Une los documentos en un solo documento. |
| [join(String filePath)](#join-java.lang.String-) | Une los documentos en un solo documento. |
| [join(String filePath, IJoinOptions joinOptions)](#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-) | Une los documentos en un solo documento. |
| [join(String filePath, IPageJoinOptions joinOptions)](#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-) | Une los documentos en un solo documento. |
| [join(String filePath, ImageJoinOptions joinOptions)](#join-java.lang.String-com.groupdocs.merger.domain.options.ImageJoinOptions-) | Une los documentos en un solo documento. |
| [createPageBuilder()](#createPageBuilder--) | Crea un nuevo generador de páginas con una colección de documentos predefinida. |
| [createPageBuilder(PageBuilderOptions pageBuilderOptions)](#createPageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | Crea un nuevo generador de páginas con una colección de documentos predefinida. |
| [applyPageBuilder(PageBuilder pageBuilder)](#applyPageBuilder-com.groupdocs.merger.domain.builders.PageBuilder-) | Aplica los cambios del generador de páginas. |
| [split(ISplitOptions splitOptions)](#split-com.groupdocs.merger.domain.options.interfaces.ISplitOptions-) | Divide el documento único en varios documentos. |
| [split(ITextSplitOptions splitOptions)](#split-com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions-) | Divide el documento único en varios documentos. |
| [extractPages(IExtractOptions extractOptions)](#extractPages-com.groupdocs.merger.domain.options.interfaces.IExtractOptions-) | Crea un nuevo documento con algunas páginas del documento origen. |
| [addPassword(IAddPasswordOptions addPasswordOptions)](#addPassword-com.groupdocs.merger.domain.options.interfaces.IAddPasswordOptions-) | Protege el documento con una contraseña. |
| [isPasswordSet()](#isPasswordSet--) | Comprueba si el documento está protegido con contraseña. |
| [removePassword()](#removePassword--) | Elimina la contraseña del documento. |
| [updatePassword(IUpdatePasswordOptions updatePasswordOptions)](#updatePassword-com.groupdocs.merger.domain.options.interfaces.IUpdatePasswordOptions-) | Actualiza la contraseña existente del documento. |
| [changeOrientation(IOrientationOptions orientationOptions)](#changeOrientation-com.groupdocs.merger.domain.options.interfaces.IOrientationOptions-) | Aplica un nuevo modo de orientación a las páginas especificadas. |
| [movePage(IMoveOptions moveOptions)](#movePage-com.groupdocs.merger.domain.options.interfaces.IMoveOptions-) | Mueve la página a una nueva posición dentro del documento de formato conocido. |
| [removePages(IRemoveOptions removeOptions)](#removePages-com.groupdocs.merger.domain.options.interfaces.IRemoveOptions-) | Elimina páginas del documento de formato conocido. |
| [swapPages(ISwapOptions swapOptions)](#swapPages-com.groupdocs.merger.domain.options.interfaces.ISwapOptions-) | Intercambia dos páginas dentro del documento de formato conocido. |
| [rotatePages(IRotateOptions rotateOptions)](#rotatePages-com.groupdocs.merger.domain.options.interfaces.IRotateOptions-) | Rota las páginas del documento. |
| [getDocumentInfo()](#getDocumentInfo--) | Obtiene información sobre las páginas del documento: sus tamaños, la altura máxima de página, el ancho de una página con la altura máxima. |
| [generatePreview(IPreviewOptions previewOptions)](#generatePreview-com.groupdocs.merger.domain.options.interfaces.IPreviewOptions-) | Genera una vista previa de las páginas del documento. |
| [save(OutputStream document)](#save-java.io.OutputStream-) | Guarda el documento resultante en el flujo  document . |
| [save(String filePath)](#save-java.lang.String-) | Guarda el archivo del documento resultante en  filePath . |
| [save(String filePath, boolean useDefaultDirectory)](#save-java.lang.String-boolean-) | Guarda el archivo del documento resultante en  filePath . |
### Merger(InputStream document) {#Merger-java.io.InputStream-}
```
public Merger(InputStream document)
```


Inicializa una nueva instancia de la clase [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | java.io.InputStream | El flujo legible. |

### Merger(InputStream document, ILoadOptions loadOptions) {#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-}
```
public Merger(InputStream document, ILoadOptions loadOptions)
```


Inicializa una nueva instancia de la clase [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | java.io.InputStream | El flujo legible. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | Las opciones de carga del documento. |

### Merger(InputStream document, MergerSettings settings) {#Merger-java.io.InputStream-com.groupdocs.merger.MergerSettings-}
```
public Merger(InputStream document, MergerSettings settings)
```


Inicializa una nueva instancia de la clase [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | java.io.InputStream | El flujo legible. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | Los ajustes del Fusionador. |

### Merger(InputStream document, ILoadOptions loadOptions, MergerSettings settings) {#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-}
```
public Merger(InputStream document, ILoadOptions loadOptions, MergerSettings settings)
```


Inicializa una nueva instancia de la clase [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | java.io.InputStream | El flujo legible. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | Las opciones de carga del documento. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | Los ajustes del Fusionador. |

### Merger(String filePath) {#Merger-java.lang.String-}
```
public Merger(String filePath)
```


Inicializa una nueva instancia de la clase [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo. |

### Merger(String filePath, ILoadOptions loadOptions) {#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-}
```
public Merger(String filePath, ILoadOptions loadOptions)
```


Inicializa una nueva instancia de la clase [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | Las opciones de carga del documento. |

### Merger(String filePath, MergerSettings settings) {#Merger-java.lang.String-com.groupdocs.merger.MergerSettings-}
```
public Merger(String filePath, MergerSettings settings)
```


Inicializa una nueva instancia de la clase [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | Los ajustes del Fusionador. |

### Merger(String filePath, ILoadOptions loadOptions, MergerSettings settings) {#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-}
```
public Merger(String filePath, ILoadOptions loadOptions, MergerSettings settings)
```


Inicializa una nueva instancia de la clase [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | Las opciones de carga del documento. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | Los ajustes del Fusionador. |

### dispose() {#dispose--}
```
public final void dispose()
```


Libera los recursos.

### importDocument(IImportDocumentOptions importDocumentOptions) {#importDocument-com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions-}
```
public final void importDocument(IImportDocumentOptions importDocumentOptions)
```


Importa el documento como adjunto o incrustado mediante Ole.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | importDocumentOptions | [IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions) | Las opciones de importación del documento incrustado. |

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


Une los documentos en un solo documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.io.InputStream | Documento unido. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(InputStream document, IJoinOptions joinOptions) {#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-}
```
public final void join(InputStream document, IJoinOptions joinOptions)
```


Une los documentos en un solo documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | java.io.InputStream | Documento unido. |
|  | joinOptions | [IJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ijoinoptions) | Las opciones de unión. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(InputStream document, IPageJoinOptions joinOptions) {#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-}
```
public final void join(InputStream document, IPageJoinOptions joinOptions)
```


Une los documentos en un solo documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | java.io.InputStream | Documento unido. |
|  | joinOptions | [IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions) | Las opciones de unión. |

--------------------

 **Learn more** 

 *   |

### join(InputStream document, ImageJoinOptions joinOptions) {#join-java.io.InputStream-com.groupdocs.merger.domain.options.ImageJoinOptions-}
```
public final void join(InputStream document, ImageJoinOptions joinOptions)
```


Une los documentos en un solo documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | java.io.InputStream | Documento unido. |
|  | joinOptions | [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) | Las opciones de unión de imágenes. |

--------------------

 **Learn more** 

 *   |

### join(String filePath) {#join-java.lang.String-}
```
public final void join(String filePath)
```


Une los documentos en un solo documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | Ruta del archivo del documento unido. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(String filePath, IJoinOptions joinOptions) {#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-}
```
public final void join(String filePath, IJoinOptions joinOptions)
```


Une los documentos en un solo documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | Ruta del archivo del documento unido. |
|  | joinOptions | [IJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ijoinoptions) | Las opciones de unión. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(String filePath, IPageJoinOptions joinOptions) {#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-}
```
public final void join(String filePath, IPageJoinOptions joinOptions)
```


Une los documentos en un solo documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | Ruta del archivo del documento unido. |
|  | joinOptions | [IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions) | Las opciones de unión. |

--------------------

 **Learn more** 

 *   |

### join(String filePath, ImageJoinOptions joinOptions) {#join-java.lang.String-com.groupdocs.merger.domain.options.ImageJoinOptions-}
```
public final void join(String filePath, ImageJoinOptions joinOptions)
```


Une los documentos en un solo documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | Ruta del archivo del documento unido. |
|  | joinOptions | [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) | Las opciones de unión de imágenes. |

--------------------

 **Learn more** 

 *   |

### createPageBuilder() {#createPageBuilder--}
```
public final PageBuilder createPageBuilder()
```


Crea un nuevo generador de páginas con una colección de documentos predefinida.

**Returns:**
[PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) - The created page builder.
### createPageBuilder(PageBuilderOptions pageBuilderOptions) {#createPageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public final PageBuilder createPageBuilder(PageBuilderOptions pageBuilderOptions)
```


Crea un nuevo generador de páginas con una colección de documentos predefinida.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageBuilderOptions | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) |  |

**Returns:**
[PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) - The created page builder.
### applyPageBuilder(PageBuilder pageBuilder) {#applyPageBuilder-com.groupdocs.merger.domain.builders.PageBuilder-}
```
public final void applyPageBuilder(PageBuilder pageBuilder)
```


Aplica los cambios del generador de páginas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageBuilder | [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) | El generador de páginas. |

### split(ISplitOptions splitOptions) {#split-com.groupdocs.merger.domain.options.interfaces.ISplitOptions-}
```
public final void split(ISplitOptions splitOptions)
```


Divide el documento único en varios documentos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | splitOptions | [ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions) | Las opciones de división de página. |

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


Divide el documento único en varios documentos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | splitOptions | [ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions) | Las opciones de división de texto. |

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


Crea un nuevo documento con algunas páginas del documento origen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | extractOptions | [IExtractOptions](../../com.groupdocs.merger.domain.options.interfaces/iextractoptions) | Las opciones de página. |

--------------------

**Learn more**

 *  More about how to extract specific document pages or page range: [How to extract pages from PDF, Word, Excel and PowerPoint documents][How to extract pages from PDF_ Word_ Excel and PowerPoint documents]


[How to extract pages from PDF_ Word_ Excel and PowerPoint documents]: https://docs.groupdocs.com/merger/java/extract-pages/ |

### addPassword(IAddPasswordOptions addPasswordOptions) {#addPassword-com.groupdocs.merger.domain.options.interfaces.IAddPasswordOptions-}
```
public final void addPassword(IAddPasswordOptions addPasswordOptions)
```


Protege el documento con una contraseña.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | addPasswordOptions | [IAddPasswordOptions](../../com.groupdocs.merger.domain.options.interfaces/iaddpasswordoptions) | Las opciones para especificar la contraseña. |

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


Comprueba si el documento está protegido con contraseña.

**Returns:**
boolean - Devuelve un valor que indica si el documento está protegido o no.

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


Elimina la contraseña del documento.

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


Actualiza la contraseña existente del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | updatePasswordOptions | [IUpdatePasswordOptions](../../com.groupdocs.merger.domain.options.interfaces/iupdatepasswordoptions) | Las opciones para especificar las contraseñas actuales/nuevas. |

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


Aplica un nuevo modo de orientación a las páginas especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | orientationOptions | [IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions) | Las opciones de cambio de orientación. |

--------------------

**Learn more**

 *  More about how to change orientation for Microsoft Word document pages: [How to change Microsoft Word document pages orientation][]


[How to change Microsoft Word document pages orientation]: https://docs.groupdocs.com/merger/java/change-page-orientation/ |

### movePage(IMoveOptions moveOptions) {#movePage-com.groupdocs.merger.domain.options.interfaces.IMoveOptions-}
```
public final void movePage(IMoveOptions moveOptions)
```


Mueve la página a una nueva posición dentro del documento de formato conocido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | moveOptions | [IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions) | Las opciones de movimiento. |

--------------------

**Learn more**

 *  More about how to move page to another position within document: [How to move PDF, Word, Excel and PowerPoint document pages][How to move PDF_ Word_ Excel and PowerPoint document pages]


[How to move PDF_ Word_ Excel and PowerPoint document pages]: https://docs.groupdocs.com/merger/java/move-page/ |

### removePages(IRemoveOptions removeOptions) {#removePages-com.groupdocs.merger.domain.options.interfaces.IRemoveOptions-}
```
public final void removePages(IRemoveOptions removeOptions)
```


Elimina páginas del documento de formato conocido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | removeOptions | [IRemoveOptions](../../com.groupdocs.merger.domain.options.interfaces/iremoveoptions) | Las opciones para el número de páginas a eliminar. |

--------------------

**Learn more**

 *  More about how to remove page from document: [How to remove page from PDF, Word, Excel or PowerPoint document][How to remove page from PDF_ Word_ Excel or PowerPoint document]


[How to remove page from PDF_ Word_ Excel or PowerPoint document]: https://docs.groupdocs.com/merger/java/remove-pages/ |

### swapPages(ISwapOptions swapOptions) {#swapPages-com.groupdocs.merger.domain.options.interfaces.ISwapOptions-}
```
public final void swapPages(ISwapOptions swapOptions)
```


Intercambia dos páginas dentro del documento de formato conocido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | swapOptions | [ISwapOptions](../../com.groupdocs.merger.domain.options.interfaces/iswapoptions) | Las opciones de intercambio. |

--------------------

**Learn more**

 *  More about how to swap pages positions within document: [How to swap pages inside PDF, Word, Excel or PowerPoint document][How to swap pages inside PDF_ Word_ Excel or PowerPoint document]


[How to swap pages inside PDF_ Word_ Excel or PowerPoint document]: https://docs.groupdocs.com/merger/java/swap-pages/ |

### rotatePages(IRotateOptions rotateOptions) {#rotatePages-com.groupdocs.merger.domain.options.interfaces.IRotateOptions-}
```
public final void rotatePages(IRotateOptions rotateOptions)
```


Rota las páginas del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | rotateOptions | [IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions) | Las opciones para la rotación de página. |

--------------------

**Learn more**

 *  More about how to rotate PDF document pages: [How to rotate PDF document pages][]


[How to rotate PDF document pages]: https://docs.groupdocs.com/merger/java/rotate-pages/ |

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Obtiene información sobre las páginas del documento: sus tamaños, la altura máxima de página, el ancho de una página con la altura máxima.

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


Genera una vista previa de las páginas del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | previewOptions | [IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions) | Las opciones de vista previa. |

--------------------

**Learn more**

 *  Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Merger][]


[How to generate document pages preview using GroupDocs.Merger]: https://docs.groupdocs.com/merger/java/generate-document-pages-preview/ |

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


Guarda el documento resultante en el flujo  document .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | java.io.OutputStream | El flujo del documento. |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Guarda el archivo del documento resultante en  filePath .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | El nombre del archivo o la ruta completa del archivo. |

### save(String filePath, boolean useDefaultDirectory) {#save-java.lang.String-boolean-}
```
public final void save(String filePath, boolean useDefaultDirectory)
```


Guarda el archivo del documento resultante en  filePath .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo o el nombre en caso de uso del directorio predeterminado. |
| useDefaultDirectory | boolean | Utilice el directorio predeterminado de la configuración. |

