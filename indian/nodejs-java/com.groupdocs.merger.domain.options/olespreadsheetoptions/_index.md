---
title: "OleSpreadsheetOptions"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "OLE के माध्यम से एम्बेडेड दस्तावेज़ को स्प्रेडशीट में आयात करने के विकल्प प्रदान करता है।"
type: docs
weight: 20
url: /hi/nodejs-java/com.groupdocs.merger.domain.options/olespreadsheetoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleSpreadsheetOptions](../../com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions)
```
public class OleSpreadsheetOptions extends ImportDocumentOptions implements IOleSpreadsheetOptions
```

OLE के माध्यम से एम्बेडेड दस्तावेज़ को स्प्रेडशीट में आयात करने के विकल्प प्रदान करता है।

--------------------

**Learn more**

 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]


[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleSpreadsheetOptions-byte---byte---java.lang.String-int-) | नए उदाहरण को इनिशियलाइज़ करता है [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) क्लास का। |
| [OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-byte---int-) | नए उदाहरण को इनिशियलाइज़ करता है [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) क्लास का। |
| [OleSpreadsheetOptions(String filePath, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-int-) | नए उदाहरण को इनिशियलाइज़ करता है [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | ऊपरी बाएँ पंक्ति सूचकांक। |
| [setRowIndex(int value)](#setRowIndex-int-) | ऊपरी बाएँ पंक्ति सूचकांक। |
| [getColumnIndex()](#getColumnIndex--) | ऊपरी बाएँ स्तंभ सूचकांक। |
| [setColumnIndex(int value)](#setColumnIndex-int-) | ऊपरी बाएँ स्तंभ सूचकांक। |
| [getWidth()](#getWidth--) | Ole ऑब्जेक्ट इमेज की चौड़ाई। |
| [setWidth(int value)](#setWidth-int-) | Ole ऑब्जेक्ट इमेज की चौड़ाई। |
| [getHeight()](#getHeight--) | Ole ऑब्जेक्ट इमेज की ऊँचाई। |
| [setHeight(int value)](#setHeight-int-) | Ole ऑब्जेक्ट इमेज की ऊँचाई। |
| [getImageData()](#getImageData--) | Ole ऑब्जेक्ट छवि का डेटा। |
### OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleSpreadsheetOptions-byte---byte---java.lang.String-int-}
```
public OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


नए उदाहरण को इनिशियलाइज़ करता है [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| objectData | byte[] | एम्बेडेड ऑब्जेक्ट का डेटा। |
| imageData | byte[] | एम्बेडेड ऑब्जेक्ट का इमेज डेटा। |
| विस्तार | java.lang.String | एम्बेडेड ऑब्जेक्ट का विस्तार। |
| pageNumber | int | एम्बेडेड ऑब्जेक्ट जोड़ने के लिए पेज नंबर। |

### OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-byte---int-}
```
public OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)
```


नए उदाहरण को इनिशियलाइज़ करता है [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | एम्बेडेड ऑब्जेक्ट का फ़ाइल पाथ। |
| imageData | byte[] | एम्बेडेड ऑब्जेक्ट का इमेज डेटा। |
| pageNumber | int | एम्बेडेड ऑब्जेक्ट जोड़ने के लिए पेज नंबर। |

### OleSpreadsheetOptions(String filePath, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-int-}
```
public OleSpreadsheetOptions(String filePath, int pageNumber)
```


नए उदाहरण को इनिशियलाइज़ करता है [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | एम्बेडेड ऑब्जेक्ट का फ़ाइल पाथ। |
| pageNumber | int | एम्बेडेड ऑब्जेक्ट जोड़ने के लिए पेज नंबर। |

### getRowIndex() {#getRowIndex--}
```
public final int getRowIndex()
```


ऊपरी बाएँ पंक्ति सूचकांक।

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public final void setRowIndex(int value)
```


ऊपरी बाएँ पंक्ति सूचकांक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public final int getColumnIndex()
```


ऊपरी बाएँ स्तंभ सूचकांक।

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public final void setColumnIndex(int value)
```


ऊपरी बाएँ स्तंभ सूचकांक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ole ऑब्जेक्ट इमेज की चौड़ाई।

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ole ऑब्जेक्ट इमेज की चौड़ाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ole ऑब्जेक्ट इमेज की ऊँचाई।

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ole ऑब्जेक्ट इमेज की ऊँचाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Ole ऑब्जेक्ट छवि का डेटा।

**Returns:**
byte[]
