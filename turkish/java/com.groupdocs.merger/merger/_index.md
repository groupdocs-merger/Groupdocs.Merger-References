---
title: "Merger"
second_title: "GroupDocs.Merger için Java API Referansı"
description: "Belge birleştirme sürecini kontrol eden ana sınıfı temsil eder."
type: docs
weight: 10
url: /tr/java/com.groupdocs.merger/merger/
---
**Inheritance:**
java.lang.Object
```
public class Merger
```

Belge birleştirme sürecini kontrol eden ana sınıfı temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Merger(InputStream document)](#Merger-java.io.InputStream-) | Yeni bir [Merger](../../com.groupdocs.merger/merger) sınıfının örneğini başlatır. |
| [Merger(InputStream document, ILoadOptions loadOptions)](#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-) | Yeni bir [Merger](../../com.groupdocs.merger/merger) sınıfının örneğini başlatır. |
| [Merger(InputStream document, MergerSettings settings)](#Merger-java.io.InputStream-com.groupdocs.merger.MergerSettings-) | Yeni bir [Merger](../../com.groupdocs.merger/merger) sınıfının örneğini başlatır. |
| [Merger(InputStream document, ILoadOptions loadOptions, MergerSettings settings)](#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-) | Yeni bir [Merger](../../com.groupdocs.merger/merger) sınıfının örneğini başlatır. |
| [Merger(String filePath)](#Merger-java.lang.String-) | Yeni bir [Merger](../../com.groupdocs.merger/merger) sınıfının örneğini başlatır. |
| [Merger(String filePath, ILoadOptions loadOptions)](#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-) | Yeni bir [Merger](../../com.groupdocs.merger/merger) sınıfının örneğini başlatır. |
| [Merger(String filePath, MergerSettings settings)](#Merger-java.lang.String-com.groupdocs.merger.MergerSettings-) | Yeni bir [Merger](../../com.groupdocs.merger/merger) sınıfının örneğini başlatır. |
| [Merger(String filePath, ILoadOptions loadOptions, MergerSettings settings)](#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-) | Yeni bir [Merger](../../com.groupdocs.merger/merger) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [dispose()](#dispose--) | Kaynakları serbest bırakır. |
| [importDocument(IImportDocumentOptions importDocumentOptions)](#importDocument-com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions-) | Belgeyi ek olarak veya Ole aracılığıyla gömülü olarak içe aktarır. |
| [join(InputStream document)](#join-java.io.InputStream-) | Belgeleri tek bir belgeye birleştirir. |
| [join(InputStream document, IJoinOptions joinOptions)](#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-) | Belgeleri tek bir belgeye birleştirir. |
| [join(InputStream document, IPageJoinOptions joinOptions)](#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-) | Belgeleri tek bir belgeye birleştirir. |
| [join(InputStream document, IImageJoinOptions joinOptions)](#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions-) | Belgeleri tek bir belgeye birleştirir. |
| [join(String filePath)](#join-java.lang.String-) | Belgeleri tek bir belgeye birleştirir. |
| [join(String filePath, IJoinOptions joinOptions)](#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-) | Belgeleri tek bir belgeye birleştirir. |
| [join(String filePath, IPageJoinOptions joinOptions)](#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-) | Belgeleri tek bir belgeye birleştirir. |
| [join(String filePath, IImageJoinOptions joinOptions)](#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions-) | Belgeleri tek bir belgeye birleştirir. |
| [createPageBuilder()](#createPageBuilder--) | Önceden tanımlı belge koleksiyonuyla yeni bir Page builder oluşturur. |
| [createPageBuilder(PageBuilderOptions pageBuilderOptions)](#createPageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | Önceden tanımlı belge koleksiyonuyla yeni bir Page builder oluşturur. |
| [applyPageBuilder(PageBuilder pageBuilder)](#applyPageBuilder-com.groupdocs.merger.domain.builders.PageBuilder-) | Page builder değişikliklerini uygular. |
| [split(ISplitOptions splitOptions)](#split-com.groupdocs.merger.domain.options.interfaces.ISplitOptions-) | Tek belgeyi birden çok belgeye böler. |
| [split(ITextSplitOptions splitOptions)](#split-com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions-) | Tek belgeyi birden çok belgeye böler. |
| [extractPages(IExtractOptions extractOptions)](#extractPages-com.groupdocs.merger.domain.options.interfaces.IExtractOptions-) | Kaynak belgeden bazı sayfalarla yeni bir belge oluşturur. |
| [addPassword(IAddPasswordOptions addPasswordOptions)](#addPassword-com.groupdocs.merger.domain.options.interfaces.IAddPasswordOptions-) | Belgeyi şifreyle korur. |
| [isPasswordSet()](#isPasswordSet--) | Belgenin şifre korumalı olup olmadığını denetler. |
| [removePassword()](#removePassword--) | Belgeden şifreyi kaldırır. |
| [updatePassword(IUpdatePasswordOptions updatePasswordOptions)](#updatePassword-com.groupdocs.merger.domain.options.interfaces.IUpdatePasswordOptions-) | Belge için mevcut şifreyi günceller. |
| [changeOrientation(IOrientationOptions orientationOptions)](#changeOrientation-com.groupdocs.merger.domain.options.interfaces.IOrientationOptions-) | Belirtilen sayfalar için yeni bir yönlendirme modunu uygular. |
| [movePage(IMoveOptions moveOptions)](#movePage-com.groupdocs.merger.domain.options.interfaces.IMoveOptions-) | Sayfayı bilinen formatta belge içinde yeni bir konuma taşır. |
| [removePages(IRemoveOptions removeOptions)](#removePages-com.groupdocs.merger.domain.options.interfaces.IRemoveOptions-) | Bilinen formatta belgelerden sayfaları kaldırır. |
| [swapPages(ISwapOptions swapOptions)](#swapPages-com.groupdocs.merger.domain.options.interfaces.ISwapOptions-) | Bilinen formatta belge içinde iki sayfayı değiştirir. |
| [rotatePages(IRotateOptions rotateOptions)](#rotatePages-com.groupdocs.merger.domain.options.interfaces.IRotateOptions-) | Belgenin sayfalarını döndürür. |
| [getDocumentInfo()](#getDocumentInfo--) | Belge sayfaları hakkında bilgi alır: boyutları, maksimum sayfa yüksekliği, maksimum yüksekliğe sahip sayfanın genişliği. |
| [generatePreview(IPreviewOptions previewOptions)](#generatePreview-com.groupdocs.merger.domain.options.interfaces.IPreviewOptions-) | Belge sayfalarının önizlemesini oluşturur. |
| [save(OutputStream document)](#save-java.io.OutputStream-) | Sonuç belgesini akışa kaydeder  document . |
| [save(OutputStream document, ISaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.merger.domain.options.interfaces.ISaveOptions-) | Sonuç belgesini akışa kaydeder  document . |
| [save(String filePath)](#save-java.lang.String-) | Sonuç belge dosyasını  filePath  konumuna kaydeder. |
| [save(String filePath, boolean useDefaultDirectory)](#save-java.lang.String-boolean-) | Sonuç belge dosyasını  filePath  konumuna kaydeder. |
| [save(String filePath, ISaveOptions saveOptions)](#save-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ISaveOptions-) | Sonuç belge dosyasını  filePath  konumuna kaydeder. |
| [save(String filePath, OutputStream inputStream)](#save-java.lang.String-java.io.OutputStream-) | Sonuç belge dosyasını  filePath  konumuna kaydeder. |
### Merger(InputStream document) {#Merger-java.io.InputStream-}
```
public Merger(InputStream document)
```


Yeni bir [Merger](../../com.groupdocs.merger/merger) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.InputStream | Okunabilir akış. |

### Merger(InputStream document, ILoadOptions loadOptions) {#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-}
```
public Merger(InputStream document, ILoadOptions loadOptions)
```


Yeni bir [Merger](../../com.groupdocs.merger/merger) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.InputStream | Okunabilir akış. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | Belge yükleme seçenekleri. |

### Merger(InputStream document, MergerSettings settings) {#Merger-java.io.InputStream-com.groupdocs.merger.MergerSettings-}
```
public Merger(InputStream document, MergerSettings settings)
```


Yeni bir [Merger](../../com.groupdocs.merger/merger) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.InputStream | Okunabilir akış. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | Birleştirici ayarları. |

### Merger(InputStream document, ILoadOptions loadOptions, MergerSettings settings) {#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-}
```
public Merger(InputStream document, ILoadOptions loadOptions, MergerSettings settings)
```


Yeni bir [Merger](../../com.groupdocs.merger/merger) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.InputStream | Okunabilir akış. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | Belge yükleme seçenekleri. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | Birleştirici ayarları. |

### Merger(String filePath) {#Merger-java.lang.String-}
```
public Merger(String filePath)
```


Yeni bir [Merger](../../com.groupdocs.merger/merger) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Dosya yolu. |

### Merger(String filePath, ILoadOptions loadOptions) {#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-}
```
public Merger(String filePath, ILoadOptions loadOptions)
```


Yeni bir [Merger](../../com.groupdocs.merger/merger) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Dosya yolu. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | Belge yükleme seçenekleri. |

### Merger(String filePath, MergerSettings settings) {#Merger-java.lang.String-com.groupdocs.merger.MergerSettings-}
```
public Merger(String filePath, MergerSettings settings)
```


Yeni bir [Merger](../../com.groupdocs.merger/merger) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Dosya yolu. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | Birleştirici ayarları. |

### Merger(String filePath, ILoadOptions loadOptions, MergerSettings settings) {#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-}
```
public Merger(String filePath, ILoadOptions loadOptions, MergerSettings settings)
```


Yeni bir [Merger](../../com.groupdocs.merger/merger) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Dosya yolu. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | Belge yükleme seçenekleri. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | Birleştirici ayarları. |

### dispose() {#dispose--}
```
public final void dispose()
```


Kaynakları serbest bırakır.

### importDocument(IImportDocumentOptions importDocumentOptions) {#importDocument-com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions-}
```
public final void importDocument(IImportDocumentOptions importDocumentOptions)
```


Belgeyi ek olarak veya Ole aracılığıyla gömülü olarak içe aktarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | importDocumentOptions | [IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions) | Gömülü belge içe aktarma seçenekleri. |

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


Belgeleri tek bir belgeye birleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.InputStream | Birleştirilmiş belge. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(InputStream document, IJoinOptions joinOptions) {#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-}
```
public final void join(InputStream document, IJoinOptions joinOptions)
```


Belgeleri tek bir belgeye birleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.InputStream | Birleştirilmiş belge. |
|  | joinOptions | [IJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ijoinoptions) | Birleştirme seçenekleri. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(InputStream document, IPageJoinOptions joinOptions) {#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-}
```
public final void join(InputStream document, IPageJoinOptions joinOptions)
```


Belgeleri tek bir belgeye birleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.InputStream | Birleştirilmiş belge. |
|  | joinOptions | [IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions) | Birleştirme seçenekleri. |

--------------------

 **Learn more** 

 *   |

### join(InputStream document, IImageJoinOptions joinOptions) {#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions-}
```
public final void join(InputStream document, IImageJoinOptions joinOptions)
```


Belgeleri tek bir belgeye birleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.InputStream | Birleştirilmiş belge. |
|  | joinOptions | [IImageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/iimagejoinoptions) | Görüntü birleştirme seçenekleri. |

--------------------

 **Learn more** 

 *   |

### join(String filePath) {#join-java.lang.String-}
```
public final void join(String filePath)
```


Belgeleri tek bir belgeye birleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Birleştirilmiş belgenin dosya yolu. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(String filePath, IJoinOptions joinOptions) {#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-}
```
public final void join(String filePath, IJoinOptions joinOptions)
```


Belgeleri tek bir belgeye birleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Birleştirilmiş belgenin dosya yolu. |
|  | joinOptions | [IJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ijoinoptions) | Birleştirme seçenekleri. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(String filePath, IPageJoinOptions joinOptions) {#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-}
```
public final void join(String filePath, IPageJoinOptions joinOptions)
```


Belgeleri tek bir belgeye birleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Birleştirilmiş belgenin dosya yolu. |
|  | joinOptions | [IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions) | Birleştirme seçenekleri. |

--------------------

 **Learn more** 

 *   |

### join(String filePath, IImageJoinOptions joinOptions) {#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions-}
```
public final void join(String filePath, IImageJoinOptions joinOptions)
```


Belgeleri tek bir belgeye birleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Birleştirilmiş belgenin dosya yolu. |
|  | joinOptions | [IImageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/iimagejoinoptions) | Görüntü birleştirme seçenekleri. |

--------------------

 **Learn more** 

 *   |

### createPageBuilder() {#createPageBuilder--}
```
public final PageBuilder createPageBuilder()
```


Önceden tanımlı belge koleksiyonuyla yeni bir Page builder oluşturur.

**Returns:**
[PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) - The created page builder.
### createPageBuilder(PageBuilderOptions pageBuilderOptions) {#createPageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public final PageBuilder createPageBuilder(PageBuilderOptions pageBuilderOptions)
```


Önceden tanımlı belge koleksiyonuyla yeni bir Page builder oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageBuilderOptions | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) |  |

**Returns:**
[PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) - The created page builder.
### applyPageBuilder(PageBuilder pageBuilder) {#applyPageBuilder-com.groupdocs.merger.domain.builders.PageBuilder-}
```
public final void applyPageBuilder(PageBuilder pageBuilder)
```


Page builder değişikliklerini uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageBuilder | [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) | Sayfa oluşturucu. |

### split(ISplitOptions splitOptions) {#split-com.groupdocs.merger.domain.options.interfaces.ISplitOptions-}
```
public final void split(ISplitOptions splitOptions)
```


Tek belgeyi birden çok belgeye böler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | splitOptions | [ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions) | Sayfa bölme seçenekleri. |

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


Tek belgeyi birden çok belgeye böler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | splitOptions | [ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions) | Metin bölme seçenekleri. |

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


Kaynak belgeden bazı sayfalarla yeni bir belge oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | extractOptions | [IExtractOptions](../../com.groupdocs.merger.domain.options.interfaces/iextractoptions) | Sayfa seçenekleri. |

--------------------

**Learn more**

 *  More about how to extract specific document pages or page range: [How to extract pages from PDF, Word, Excel and PowerPoint documents][How to extract pages from PDF_ Word_ Excel and PowerPoint documents]


[How to extract pages from PDF_ Word_ Excel and PowerPoint documents]: https://docs.groupdocs.com/merger/java/extract-pages/ |

### addPassword(IAddPasswordOptions addPasswordOptions) {#addPassword-com.groupdocs.merger.domain.options.interfaces.IAddPasswordOptions-}
```
public final void addPassword(IAddPasswordOptions addPasswordOptions)
```


Belgeyi şifreyle korur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | addPasswordOptions | [IAddPasswordOptions](../../com.groupdocs.merger.domain.options.interfaces/iaddpasswordoptions) | Parolayı belirtmek için seçenekler. |

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


Belgenin şifre korumalı olup olmadığını denetler.

**Returns:**
boolean - Belgenin korumalı olup olmadığını gösteren bir değer döndürür.

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


Belgeden şifreyi kaldırır.

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


Belge için mevcut şifreyi günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | updatePasswordOptions | [IUpdatePasswordOptions](../../com.groupdocs.merger.domain.options.interfaces/iupdatepasswordoptions) | Mevcut/yeni parolaları belirtmek için seçenekler. |

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


Belirtilen sayfalar için yeni bir yönlendirme modunu uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | orientationOptions | [IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions) | Yön değiştirme seçenekleri. |

--------------------

**Learn more**

 *  More about how to change orientation for Microsoft Word document pages: [How to change Microsoft Word document pages orientation][]


[How to change Microsoft Word document pages orientation]: https://docs.groupdocs.com/merger/java/change-page-orientation/ |

### movePage(IMoveOptions moveOptions) {#movePage-com.groupdocs.merger.domain.options.interfaces.IMoveOptions-}
```
public final void movePage(IMoveOptions moveOptions)
```


Sayfayı bilinen formatta belge içinde yeni bir konuma taşır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | moveOptions | [IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions) | Taşıma seçenekleri. |

--------------------

**Learn more**

 *  More about how to move page to another position within document: [How to move PDF, Word, Excel and PowerPoint document pages][How to move PDF_ Word_ Excel and PowerPoint document pages]


[How to move PDF_ Word_ Excel and PowerPoint document pages]: https://docs.groupdocs.com/merger/java/move-page/ |

### removePages(IRemoveOptions removeOptions) {#removePages-com.groupdocs.merger.domain.options.interfaces.IRemoveOptions-}
```
public final void removePages(IRemoveOptions removeOptions)
```


Bilinen formatta belgelerden sayfaları kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | removeOptions | [IRemoveOptions](../../com.groupdocs.merger.domain.options.interfaces/iremoveoptions) | Kaldırılacak sayfa sayısı için seçenekler. |

--------------------

**Learn more**

 *  More about how to remove page from document: [How to remove page from PDF, Word, Excel or PowerPoint document][How to remove page from PDF_ Word_ Excel or PowerPoint document]


[How to remove page from PDF_ Word_ Excel or PowerPoint document]: https://docs.groupdocs.com/merger/java/remove-pages/ |

### swapPages(ISwapOptions swapOptions) {#swapPages-com.groupdocs.merger.domain.options.interfaces.ISwapOptions-}
```
public final void swapPages(ISwapOptions swapOptions)
```


Bilinen formatta belge içinde iki sayfayı değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | swapOptions | [ISwapOptions](../../com.groupdocs.merger.domain.options.interfaces/iswapoptions) | Değiştirme seçenekleri. |

--------------------

**Learn more**

 *  More about how to swap pages positions within document: [How to swap pages inside PDF, Word, Excel or PowerPoint document][How to swap pages inside PDF_ Word_ Excel or PowerPoint document]


[How to swap pages inside PDF_ Word_ Excel or PowerPoint document]: https://docs.groupdocs.com/merger/java/swap-pages/ |

### rotatePages(IRotateOptions rotateOptions) {#rotatePages-com.groupdocs.merger.domain.options.interfaces.IRotateOptions-}
```
public final void rotatePages(IRotateOptions rotateOptions)
```


Belgenin sayfalarını döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | rotateOptions | [IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions) | Sayfa döndürme seçenekleri. |

--------------------

**Learn more**

 *  More about how to rotate PDF document pages: [How to rotate PDF document pages][]


[How to rotate PDF document pages]: https://docs.groupdocs.com/merger/java/rotate-pages/ |

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Belge sayfaları hakkında bilgi alır: boyutları, maksimum sayfa yüksekliği, maksimum yüksekliğe sahip sayfanın genişliği.

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


Belge sayfalarının önizlemesini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | previewOptions | [IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions) | Ön izleme seçenekleri. |

--------------------

**Learn more**

 *  Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Merger][]


[How to generate document pages preview using GroupDocs.Merger]: https://docs.groupdocs.com/merger/java/generate-document-pages-preview/ |

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


Sonuç belgesini akışa kaydeder  document .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.OutputStream | Belge akışı. |

### save(OutputStream document, ISaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.merger.domain.options.interfaces.ISaveOptions-}
```
public void save(OutputStream document, ISaveOptions saveOptions)
```


Sonuç belgesini akışa kaydeder  document .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.OutputStream | Belge akışı. |
| saveOptions | [ISaveOptions](../../com.groupdocs.merger.domain.options.interfaces/isaveoptions) | Kaydetme seçenekleri. |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Sonuç belge dosyasını  filePath  konumuna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Dosya adı veya tam dosya yolu. |

### save(String filePath, boolean useDefaultDirectory) {#save-java.lang.String-boolean-}
```
public final void save(String filePath, boolean useDefaultDirectory)
```


Sonuç belge dosyasını  filePath  konumuna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Varsayılan dizin kullanımı durumunda dosya yolu veya adı. |
| useDefaultDirectory | boolean | Ayarlarından varsayılan dizini kullan. |

### save(String filePath, ISaveOptions saveOptions) {#save-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ISaveOptions-}
```
public void save(String filePath, ISaveOptions saveOptions)
```


Sonuç belge dosyasını  filePath  konumuna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Varsayılan dizin kullanımı durumunda dosya yolu veya adı. |
| saveOptions | [ISaveOptions](../../com.groupdocs.merger.domain.options.interfaces/isaveoptions) | Kaydetme seçenekleri. |

### save(String filePath, OutputStream inputStream) {#save-java.lang.String-java.io.OutputStream-}
```
public void save(String filePath, OutputStream inputStream)
```


Sonuç belge dosyasını  filePath  konumuna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Varsayılan dizin kullanımı durumunda dosya yolu veya adı. |
| inputStream | java.io.OutputStream | Belge akışı. |

