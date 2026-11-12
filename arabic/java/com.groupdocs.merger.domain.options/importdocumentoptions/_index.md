---
title: "ImportDocumentOptions"
second_title: "توفر مساحة الأسماء com.groupdocs.merger.domain.builders منشئين."
description: "يوفر خيارات لاستيراد المستند المضمّن."
type: docs
weight: 14
url: /ar/java/com.groupdocs.merger.domain.options/importdocumentoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions)
```
public abstract class ImportDocumentOptions implements IImportDocumentOptions
```

يوفر خيارات لاستيراد المستند المضمّن.

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
[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)](#ImportDocumentOptions-byte---java.lang.String-int-) | يقوم بتهيئة نسخة جديدة من الفئة [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions). |
| [ImportDocumentOptions(String filePath, int pageNumber)](#ImportDocumentOptions-java.lang.String-int-) | يقوم بتهيئة نسخة جديدة من الفئة [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions). |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getObjectData()](#getObjectData--) | بيانات الكائن المضمن. |
| [getExtension()](#getExtension--) | امتداد الكائن المضمن. |
| [getPageNumber()](#getPageNumber--) | رقم الصفحة لإدراج الكائن المضمن. |
| [getImageData(String filePath)](#getImageData-java.lang.String-) | يحصل على بيانات الصورة للكائن المضمن. |
### ImportDocumentOptions(byte[] objectData, String extension, int pageNumber) {#ImportDocumentOptions-byte---java.lang.String-int-}
```
public ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)
```


يقوم بتهيئة نسخة جديدة من الفئة [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| objectData | byte[] | بيانات الكائن المضمن. |
| امتداد | java.lang.String | امتداد الكائن المضمن. |
| pageNumber | int | رقم الصفحة لإضافة الكائن المضمن. |

### ImportDocumentOptions(String filePath, int pageNumber) {#ImportDocumentOptions-java.lang.String-int-}
```
public ImportDocumentOptions(String filePath, int pageNumber)
```


يقوم بتهيئة نسخة جديدة من الفئة [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف الكائن المضمن. |
| pageNumber | int | رقم الصفحة لإضافة الكائن المضمن. |

### getObjectData() {#getObjectData--}
```
public final byte[] getObjectData()
```


بيانات الكائن المضمن.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public final String getExtension()
```


امتداد الكائن المضمن.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


رقم الصفحة لإدراج الكائن المضمن.

**Returns:**
int
### getImageData(String filePath) {#getImageData-java.lang.String-}
```
public final byte[] getImageData(String filePath)
```


يحصل على بيانات الصورة للكائن المضمن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف الكائن المضمن. |

**Returns:**
byte[]
