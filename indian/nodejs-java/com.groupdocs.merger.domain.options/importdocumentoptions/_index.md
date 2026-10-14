---
title: "ImportDocumentOptions"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "एम्बेडेड दस्तावेज़ आयात के विकल्प प्रदान करता है।"
type: docs
weight: 14
url: /hi/nodejs-java/com.groupdocs.merger.domain.options/importdocumentoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions)
```
public abstract class ImportDocumentOptions implements IImportDocumentOptions
```

एम्बेडेड दस्तावेज़ आयात के विकल्प प्रदान करता है।

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
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)](#ImportDocumentOptions-byte---java.lang.String-int-) | एक नया उदाहरण प्रारंभ करता है [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) क्लास का। |
| [ImportDocumentOptions(String filePath, int pageNumber)](#ImportDocumentOptions-java.lang.String-int-) | एक नया उदाहरण प्रारंभ करता है [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getObjectData()](#getObjectData--) | एम्बेडेड ऑब्जेक्ट का डेटा। |
| [getExtension()](#getExtension--) | एम्बेडेड ऑब्जेक्ट का विस्तार। |
| [getPageNumber()](#getPageNumber--) | एम्बेडेड ऑब्जेक्ट को सम्मिलित करने के लिए पृष्ठ संख्या। |
| [getImageData(String filePath)](#getImageData-java.lang.String-) | एम्बेडेड ऑब्जेक्ट की इमेज डेटा प्राप्त करता है। |
### ImportDocumentOptions(byte[] objectData, String extension, int pageNumber) {#ImportDocumentOptions-byte---java.lang.String-int-}
```
public ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)
```


एक नया उदाहरण प्रारंभ करता है [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| objectData | byte[] | एम्बेडेड ऑब्जेक्ट का डेटा। |
| विस्तार | java.lang.String | एम्बेडेड ऑब्जेक्ट का विस्तार। |
| pageNumber | int | एम्बेडेड ऑब्जेक्ट जोड़ने के लिए पेज नंबर। |

### ImportDocumentOptions(String filePath, int pageNumber) {#ImportDocumentOptions-java.lang.String-int-}
```
public ImportDocumentOptions(String filePath, int pageNumber)
```


एक नया उदाहरण प्रारंभ करता है [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | एम्बेडेड ऑब्जेक्ट का फ़ाइल पाथ। |
| pageNumber | int | एम्बेडेड ऑब्जेक्ट जोड़ने के लिए पेज नंबर। |

### getObjectData() {#getObjectData--}
```
public final byte[] getObjectData()
```


एम्बेडेड ऑब्जेक्ट का डेटा।

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public final String getExtension()
```


एम्बेडेड ऑब्जेक्ट का विस्तार।

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


एम्बेडेड ऑब्जेक्ट को सम्मिलित करने के लिए पृष्ठ संख्या।

**Returns:**
int
### getImageData(String filePath) {#getImageData-java.lang.String-}
```
public final byte[] getImageData(String filePath)
```


एम्बेडेड ऑब्जेक्ट की इमेज डेटा प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | एम्बेडेड ऑब्जेक्ट का फ़ाइल पाथ। |

**Returns:**
byte[]
