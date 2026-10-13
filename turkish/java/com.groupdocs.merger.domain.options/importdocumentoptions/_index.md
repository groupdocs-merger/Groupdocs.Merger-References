---
title: "ImportDocumentOptions"
second_title: "GroupDocs.Merger için Java API Referansı"
description: "Gömülü belge içe aktarma için seçenekler sağlar."
type: docs
weight: 14
url: /tr/java/com.groupdocs.merger.domain.options/importdocumentoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions)
```
public abstract class ImportDocumentOptions implements IImportDocumentOptions
```

Gömülü belge içe aktarma için seçenekler sağlar.

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
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)](#ImportDocumentOptions-byte---java.lang.String-int-) | Yeni bir [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) sınıfının bir örneğini başlatır. |
| [ImportDocumentOptions(String filePath, int pageNumber)](#ImportDocumentOptions-java.lang.String-int-) | Yeni bir [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) sınıfının bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getObjectData()](#getObjectData--) | Gömülü nesnenin verileri. |
| [getExtension()](#getExtension--) | Gömülü nesnenin uzantısı. |
| [getPageNumber()](#getPageNumber--) | Gömülü nesnenin eklenmesi için sayfa numarası. |
| [getImageData(String filePath)](#getImageData-java.lang.String-) | Gömülü nesnenin görüntü verilerini alır. |
### ImportDocumentOptions(byte[] objectData, String extension, int pageNumber) {#ImportDocumentOptions-byte---java.lang.String-int-}
```
public ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)
```


Yeni bir [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| objectData | byte[] | Gömülü nesnenin verileri. |
| uzantı | java.lang.String | Gömülü nesnenin uzantısı. |
| pageNumber | int | Gömülü nesneyi eklemek için sayfa numarası. |

### ImportDocumentOptions(String filePath, int pageNumber) {#ImportDocumentOptions-java.lang.String-int-}
```
public ImportDocumentOptions(String filePath, int pageNumber)
```


Yeni bir [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Gömülü nesnenin dosya yolu. |
| pageNumber | int | Gömülü nesneyi eklemek için sayfa numarası. |

### getObjectData() {#getObjectData--}
```
public final byte[] getObjectData()
```


Gömülü nesnenin verileri.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Gömülü nesnenin uzantısı.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Gömülü nesnenin eklenmesi için sayfa numarası.

**Returns:**
int
### getImageData(String filePath) {#getImageData-java.lang.String-}
```
public final byte[] getImageData(String filePath)
```


Gömülü nesnenin görüntü verilerini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Gömülü nesnenin dosya yolu. |

**Returns:**
byte[]
