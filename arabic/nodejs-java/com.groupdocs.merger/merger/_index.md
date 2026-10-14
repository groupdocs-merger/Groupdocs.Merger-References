---
title: "دمج"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "يمثل الفئة الرئيسية التي تتحكم في عملية دمج المستندات."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.merger/merger/
---
**Inheritance:**
java.lang.Object
```
public class Merger
```

يمثل الفئة الرئيسية التي تتحكم في عملية دمج المستندات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Merger(InputStream document)](#Merger-java.io.InputStream-) | يُهيئ نسخة جديدة من الفئة [Merger](../../com.groupdocs.merger/merger). |
| [Merger(InputStream document, ILoadOptions loadOptions)](#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-) | يُهيئ نسخة جديدة من الفئة [Merger](../../com.groupdocs.merger/merger). |
| [Merger(InputStream document, MergerSettings settings)](#Merger-java.io.InputStream-com.groupdocs.merger.MergerSettings-) | يُهيئ نسخة جديدة من الفئة [Merger](../../com.groupdocs.merger/merger). |
| [Merger(InputStream document, ILoadOptions loadOptions, MergerSettings settings)](#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-) | يُهيئ نسخة جديدة من الفئة [Merger](../../com.groupdocs.merger/merger). |
| [Merger(String filePath)](#Merger-java.lang.String-) | يُهيئ نسخة جديدة من الفئة [Merger](../../com.groupdocs.merger/merger). |
| [Merger(String filePath, ILoadOptions loadOptions)](#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-) | يُهيئ نسخة جديدة من الفئة [Merger](../../com.groupdocs.merger/merger). |
| [Merger(String filePath, MergerSettings settings)](#Merger-java.lang.String-com.groupdocs.merger.MergerSettings-) | يُهيئ نسخة جديدة من الفئة [Merger](../../com.groupdocs.merger/merger). |
| [Merger(String filePath, ILoadOptions loadOptions, MergerSettings settings)](#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-) | يُهيئ نسخة جديدة من الفئة [Merger](../../com.groupdocs.merger/merger). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [dispose()](#dispose--) | يحرّر الموارد. |
| [importDocument(IImportDocumentOptions importDocumentOptions)](#importDocument-com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions-) | يستورد المستند كمرفق أو مدمج عبر Ole. |
| [join(InputStream document)](#join-java.io.InputStream-) | يجمع المستندات في مستند واحد. |
| [join(InputStream document, IJoinOptions joinOptions)](#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-) | يجمع المستندات في مستند واحد. |
| [join(InputStream document, IPageJoinOptions joinOptions)](#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-) | يجمع المستندات في مستند واحد. |
| [join(InputStream document, ImageJoinOptions joinOptions)](#join-java.io.InputStream-com.groupdocs.merger.domain.options.ImageJoinOptions-) | يجمع المستندات في مستند واحد. |
| [join(String filePath)](#join-java.lang.String-) | يجمع المستندات في مستند واحد. |
| [join(String filePath, IJoinOptions joinOptions)](#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-) | يجمع المستندات في مستند واحد. |
| [join(String filePath, IPageJoinOptions joinOptions)](#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-) | يجمع المستندات في مستند واحد. |
| [join(String filePath, ImageJoinOptions joinOptions)](#join-java.lang.String-com.groupdocs.merger.domain.options.ImageJoinOptions-) | يجمع المستندات في مستند واحد. |
| [createPageBuilder()](#createPageBuilder--) | ينشئ أداة بناء صفحات جديدة مع مجموعة مستندات معرفة مسبقًا. |
| [createPageBuilder(PageBuilderOptions pageBuilderOptions)](#createPageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | ينشئ أداة بناء صفحات جديدة مع مجموعة مستندات معرفة مسبقًا. |
| [applyPageBuilder(PageBuilder pageBuilder)](#applyPageBuilder-com.groupdocs.merger.domain.builders.PageBuilder-) | يطبق تغييرات أداة بناء الصفحات. |
| [split(ISplitOptions splitOptions)](#split-com.groupdocs.merger.domain.options.interfaces.ISplitOptions-) | يقسم المستند الواحد إلى مستندات متعددة. |
| [split(ITextSplitOptions splitOptions)](#split-com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions-) | يقسم المستند الواحد إلى مستندات متعددة. |
| [extractPages(IExtractOptions extractOptions)](#extractPages-com.groupdocs.merger.domain.options.interfaces.IExtractOptions-) | ينشئ مستندًا جديدًا مع بعض الصفحات من المستند المصدر. |
| [addPassword(IAddPasswordOptions addPasswordOptions)](#addPassword-com.groupdocs.merger.domain.options.interfaces.IAddPasswordOptions-) | يحمي المستند بكلمة مرور. |
| [isPasswordSet()](#isPasswordSet--) | يتحقق مما إذا كان المستند محميًا بكلمة مرور. |
| [removePassword()](#removePassword--) | يزيل كلمة المرور من المستند. |
| [updatePassword(IUpdatePasswordOptions updatePasswordOptions)](#updatePassword-com.groupdocs.merger.domain.options.interfaces.IUpdatePasswordOptions-) | يحدّث كلمة المرور الحالية للمستند. |
| [changeOrientation(IOrientationOptions orientationOptions)](#changeOrientation-com.groupdocs.merger.domain.options.interfaces.IOrientationOptions-) | يطبق وضع توجيه جديد للصفحات المحددة. |
| [movePage(IMoveOptions moveOptions)](#movePage-com.groupdocs.merger.domain.options.interfaces.IMoveOptions-) | ينقل الصفحة إلى موضع جديد داخل مستند بتنسيق معروف. |
| [removePages(IRemoveOptions removeOptions)](#removePages-com.groupdocs.merger.domain.options.interfaces.IRemoveOptions-) | يزيل الصفحات من مستند بتنسيق معروف. |
| [swapPages(ISwapOptions swapOptions)](#swapPages-com.groupdocs.merger.domain.options.interfaces.ISwapOptions-) | يبدل صفحتين داخل مستند بتنسيق معروف. |
| [rotatePages(IRotateOptions rotateOptions)](#rotatePages-com.groupdocs.merger.domain.options.interfaces.IRotateOptions-) | يدور صفحات المستند. |
| [getDocumentInfo()](#getDocumentInfo--) | يحصل على معلومات حول صفحات المستند: أحجامها، أقصى ارتفاع للصفحة، عرض الصفحة ذات أقصى ارتفاع. |
| [generatePreview(IPreviewOptions previewOptions)](#generatePreview-com.groupdocs.merger.domain.options.interfaces.IPreviewOptions-) | ينشئ معاينة لصفحات المستند. |
| [save(OutputStream document)](#save-java.io.OutputStream-) | يحفظ مستند النتيجة إلى الدفق  document . |
| [save(String filePath)](#save-java.lang.String-) | يحفظ ملف مستند النتيجة إلى  filePath . |
| [save(String filePath, boolean useDefaultDirectory)](#save-java.lang.String-boolean-) | يحفظ ملف مستند النتيجة إلى  filePath . |
### Merger(InputStream document) {#Merger-java.io.InputStream-}
```
public Merger(InputStream document)
```


يُهيئ نسخة جديدة من الفئة [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | java.io.InputStream | الدفق القابل للقراءة. |

### Merger(InputStream document, ILoadOptions loadOptions) {#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-}
```
public Merger(InputStream document, ILoadOptions loadOptions)
```


يُهيئ نسخة جديدة من الفئة [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | java.io.InputStream | الدفق القابل للقراءة. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | خيارات تحميل المستند. |

### Merger(InputStream document, MergerSettings settings) {#Merger-java.io.InputStream-com.groupdocs.merger.MergerSettings-}
```
public Merger(InputStream document, MergerSettings settings)
```


يُهيئ نسخة جديدة من الفئة [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | java.io.InputStream | الدفق القابل للقراءة. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | إعدادات الدمج. |

### Merger(InputStream document, ILoadOptions loadOptions, MergerSettings settings) {#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-}
```
public Merger(InputStream document, ILoadOptions loadOptions, MergerSettings settings)
```


يُهيئ نسخة جديدة من الفئة [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | java.io.InputStream | الدفق القابل للقراءة. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | خيارات تحميل المستند. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | إعدادات الدمج. |

### Merger(String filePath) {#Merger-java.lang.String-}
```
public Merger(String filePath)
```


يُهيئ نسخة جديدة من الفئة [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف. |

### Merger(String filePath, ILoadOptions loadOptions) {#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-}
```
public Merger(String filePath, ILoadOptions loadOptions)
```


يُهيئ نسخة جديدة من الفئة [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | خيارات تحميل المستند. |

### Merger(String filePath, MergerSettings settings) {#Merger-java.lang.String-com.groupdocs.merger.MergerSettings-}
```
public Merger(String filePath, MergerSettings settings)
```


يُهيئ نسخة جديدة من الفئة [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | إعدادات الدمج. |

### Merger(String filePath, ILoadOptions loadOptions, MergerSettings settings) {#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-}
```
public Merger(String filePath, ILoadOptions loadOptions, MergerSettings settings)
```


يُهيئ نسخة جديدة من الفئة [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | خيارات تحميل المستند. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | إعدادات الدمج. |

### dispose() {#dispose--}
```
public final void dispose()
```


يحرّر الموارد.

### importDocument(IImportDocumentOptions importDocumentOptions) {#importDocument-com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions-}
```
public final void importDocument(IImportDocumentOptions importDocumentOptions)
```


يستورد المستند كمرفق أو مدمج عبر Ole.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | importDocumentOptions | [IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions) | خيارات استيراد المستند المضمن. |

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


يجمع المستندات في مستند واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.io.InputStream | المستند المدمج. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(InputStream document, IJoinOptions joinOptions) {#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-}
```
public final void join(InputStream document, IJoinOptions joinOptions)
```


يجمع المستندات في مستند واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | java.io.InputStream | المستند المدمج. |
|  | joinOptions | [IJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ijoinoptions) | خيارات الدمج. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(InputStream document, IPageJoinOptions joinOptions) {#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-}
```
public final void join(InputStream document, IPageJoinOptions joinOptions)
```


يجمع المستندات في مستند واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | java.io.InputStream | المستند المدمج. |
|  | joinOptions | [IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions) | خيارات الدمج. |

--------------------

 **Learn more** 

 *   |

### join(InputStream document, ImageJoinOptions joinOptions) {#join-java.io.InputStream-com.groupdocs.merger.domain.options.ImageJoinOptions-}
```
public final void join(InputStream document, ImageJoinOptions joinOptions)
```


يجمع المستندات في مستند واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | java.io.InputStream | المستند المدمج. |
|  | joinOptions | [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) | خيارات دمج الصور. |

--------------------

 **Learn more** 

 *   |

### join(String filePath) {#join-java.lang.String-}
```
public final void join(String filePath)
```


يجمع المستندات في مستند واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف للمستند المدمج. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(String filePath, IJoinOptions joinOptions) {#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-}
```
public final void join(String filePath, IJoinOptions joinOptions)
```


يجمع المستندات في مستند واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف للمستند المدمج. |
|  | joinOptions | [IJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ijoinoptions) | خيارات الدمج. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(String filePath, IPageJoinOptions joinOptions) {#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-}
```
public final void join(String filePath, IPageJoinOptions joinOptions)
```


يجمع المستندات في مستند واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف للمستند المدمج. |
|  | joinOptions | [IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions) | خيارات الدمج. |

--------------------

 **Learn more** 

 *   |

### join(String filePath, ImageJoinOptions joinOptions) {#join-java.lang.String-com.groupdocs.merger.domain.options.ImageJoinOptions-}
```
public final void join(String filePath, ImageJoinOptions joinOptions)
```


يجمع المستندات في مستند واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف للمستند المدمج. |
|  | joinOptions | [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) | خيارات دمج الصور. |

--------------------

 **Learn more** 

 *   |

### createPageBuilder() {#createPageBuilder--}
```
public final PageBuilder createPageBuilder()
```


ينشئ أداة بناء صفحات جديدة مع مجموعة مستندات معرفة مسبقًا.

**Returns:**
[PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) - The created page builder.
### createPageBuilder(PageBuilderOptions pageBuilderOptions) {#createPageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public final PageBuilder createPageBuilder(PageBuilderOptions pageBuilderOptions)
```


ينشئ أداة بناء صفحات جديدة مع مجموعة مستندات معرفة مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageBuilderOptions | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) |  |

**Returns:**
[PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) - The created page builder.
### applyPageBuilder(PageBuilder pageBuilder) {#applyPageBuilder-com.groupdocs.merger.domain.builders.PageBuilder-}
```
public final void applyPageBuilder(PageBuilder pageBuilder)
```


يطبق تغييرات أداة بناء الصفحات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageBuilder | [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) | منشئ الصفحة. |

### split(ISplitOptions splitOptions) {#split-com.groupdocs.merger.domain.options.interfaces.ISplitOptions-}
```
public final void split(ISplitOptions splitOptions)
```


يقسم المستند الواحد إلى مستندات متعددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | splitOptions | [ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions) | خيارات تقسيم الصفحة. |

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


يقسم المستند الواحد إلى مستندات متعددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | splitOptions | [ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions) | خيارات تقسيم النص. |

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


ينشئ مستندًا جديدًا مع بعض الصفحات من المستند المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | extractOptions | [IExtractOptions](../../com.groupdocs.merger.domain.options.interfaces/iextractoptions) | خيارات الصفحة. |

--------------------

**Learn more**

 *  More about how to extract specific document pages or page range: [How to extract pages from PDF, Word, Excel and PowerPoint documents][How to extract pages from PDF_ Word_ Excel and PowerPoint documents]


[How to extract pages from PDF_ Word_ Excel and PowerPoint documents]: https://docs.groupdocs.com/merger/java/extract-pages/ |

### addPassword(IAddPasswordOptions addPasswordOptions) {#addPassword-com.groupdocs.merger.domain.options.interfaces.IAddPasswordOptions-}
```
public final void addPassword(IAddPasswordOptions addPasswordOptions)
```


يحمي المستند بكلمة مرور.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | addPasswordOptions | [IAddPasswordOptions](../../com.groupdocs.merger.domain.options.interfaces/iaddpasswordoptions) | الخيارات لتحديد كلمة المرور. |

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


يتحقق مما إذا كان المستند محميًا بكلمة مرور.

**Returns:**
boolean - يُعيد قيمة تشير إلى ما إذا كان المستند محميًا أم لا.

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


يزيل كلمة المرور من المستند.

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


يحدّث كلمة المرور الحالية للمستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | updatePasswordOptions | [IUpdatePasswordOptions](../../com.groupdocs.merger.domain.options.interfaces/iupdatepasswordoptions) | الخيارات لتحديد كلمات المرور الحالية/الجديدة. |

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


يطبق وضع توجيه جديد للصفحات المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | orientationOptions | [IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions) | خيارات تغيير الاتجاه. |

--------------------

**Learn more**

 *  More about how to change orientation for Microsoft Word document pages: [How to change Microsoft Word document pages orientation][]


[How to change Microsoft Word document pages orientation]: https://docs.groupdocs.com/merger/java/change-page-orientation/ |

### movePage(IMoveOptions moveOptions) {#movePage-com.groupdocs.merger.domain.options.interfaces.IMoveOptions-}
```
public final void movePage(IMoveOptions moveOptions)
```


ينقل الصفحة إلى موضع جديد داخل مستند بتنسيق معروف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | moveOptions | [IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions) | خيارات النقل. |

--------------------

**Learn more**

 *  More about how to move page to another position within document: [How to move PDF, Word, Excel and PowerPoint document pages][How to move PDF_ Word_ Excel and PowerPoint document pages]


[How to move PDF_ Word_ Excel and PowerPoint document pages]: https://docs.groupdocs.com/merger/java/move-page/ |

### removePages(IRemoveOptions removeOptions) {#removePages-com.groupdocs.merger.domain.options.interfaces.IRemoveOptions-}
```
public final void removePages(IRemoveOptions removeOptions)
```


يزيل الصفحات من مستند بتنسيق معروف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | removeOptions | [IRemoveOptions](../../com.groupdocs.merger.domain.options.interfaces/iremoveoptions) | الخيارات لعدد الصفحات التي سيتم إزالتها. |

--------------------

**Learn more**

 *  More about how to remove page from document: [How to remove page from PDF, Word, Excel or PowerPoint document][How to remove page from PDF_ Word_ Excel or PowerPoint document]


[How to remove page from PDF_ Word_ Excel or PowerPoint document]: https://docs.groupdocs.com/merger/java/remove-pages/ |

### swapPages(ISwapOptions swapOptions) {#swapPages-com.groupdocs.merger.domain.options.interfaces.ISwapOptions-}
```
public final void swapPages(ISwapOptions swapOptions)
```


يبدل صفحتين داخل مستند بتنسيق معروف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | swapOptions | [ISwapOptions](../../com.groupdocs.merger.domain.options.interfaces/iswapoptions) | خيارات التبديل. |

--------------------

**Learn more**

 *  More about how to swap pages positions within document: [How to swap pages inside PDF, Word, Excel or PowerPoint document][How to swap pages inside PDF_ Word_ Excel or PowerPoint document]


[How to swap pages inside PDF_ Word_ Excel or PowerPoint document]: https://docs.groupdocs.com/merger/java/swap-pages/ |

### rotatePages(IRotateOptions rotateOptions) {#rotatePages-com.groupdocs.merger.domain.options.interfaces.IRotateOptions-}
```
public final void rotatePages(IRotateOptions rotateOptions)
```


يدور صفحات المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | rotateOptions | [IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions) | الخيارات لتدوير الصفحة. |

--------------------

**Learn more**

 *  More about how to rotate PDF document pages: [How to rotate PDF document pages][]


[How to rotate PDF document pages]: https://docs.groupdocs.com/merger/java/rotate-pages/ |

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


يحصل على معلومات حول صفحات المستند: أحجامها، أقصى ارتفاع للصفحة، عرض الصفحة ذات أقصى ارتفاع.

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


ينشئ معاينة لصفحات المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | previewOptions | [IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions) | خيارات المعاينة. |

--------------------

**Learn more**

 *  Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Merger][]


[How to generate document pages preview using GroupDocs.Merger]: https://docs.groupdocs.com/merger/java/generate-document-pages-preview/ |

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


يحفظ مستند النتيجة إلى الدفق  document .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | java.io.OutputStream | تيار المستند. |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


يحفظ ملف مستند النتيجة إلى  filePath .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | اسم الملف أو مسار الملف الكامل. |

### save(String filePath, boolean useDefaultDirectory) {#save-java.lang.String-boolean-}
```
public final void save(String filePath, boolean useDefaultDirectory)
```


يحفظ ملف مستند النتيجة إلى  filePath .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف أو الاسم في حالة استخدام الدليل الافتراضي. |
| useDefaultDirectory | boolean | استخدم الدليل الافتراضي من الإعدادات. |

