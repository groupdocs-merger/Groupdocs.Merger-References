---
title: "OleWordProcessingOptions"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "OLE के माध्यम से एम्बेडेड दस्तावेज़ को वर्ड प्रोसेसिंग में आयात करने के विकल्प प्रदान करता है।"
type: docs
weight: 21
url: /hi/nodejs-java/com.groupdocs.merger.domain.options/olewordprocessingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleWordProcessingOptions](../../com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions)
```
public class OleWordProcessingOptions extends ImportDocumentOptions implements IOleWordProcessingOptions
```

OLE के माध्यम से एम्बेडेड दस्तावेज़ को वर्ड प्रोसेसिंग में आयात करने के विकल्प प्रदान करता है।

--------------------

**Learn more**

 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]


[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleWordProcessingOptions-byte---byte---java.lang.String-int-) | नए उदाहरण को इनिशियलाइज़ करता है [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) क्लास का। |
| [OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)](#OleWordProcessingOptions-java.lang.String-byte---int-) | नए उदाहरण को इनिशियलाइज़ करता है [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) क्लास का। |
| [OleWordProcessingOptions(String filePath, int pageNumber)](#OleWordProcessingOptions-java.lang.String-int-) | नए उदाहरण को इनिशियलाइज़ करता है [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLeft()](#getLeft--) | Ole ऑब्जेक्ट छवि का बायाँ निर्देशांक। |
| [setLeft(int value)](#setLeft-int-) | Ole ऑब्जेक्ट छवि का बायाँ निर्देशांक। |
| [getTop()](#getTop--) | Ole ऑब्जेक्ट छवि का ऊपर का निर्देशांक। |
| [setTop(int value)](#setTop-int-) | Ole ऑब्जेक्ट छवि का ऊपर का निर्देशांक। |
| [getWidth()](#getWidth--) | Ole ऑब्जेक्ट इमेज की चौड़ाई। |
| [setWidth(int value)](#setWidth-int-) | Ole ऑब्जेक्ट इमेज की चौड़ाई। |
| [getHeight()](#getHeight--) | Ole ऑब्जेक्ट इमेज की ऊँचाई। |
| [setHeight(int value)](#setHeight-int-) | Ole ऑब्जेक्ट इमेज की ऊँचाई। |
| [getImageData()](#getImageData--) | Ole ऑब्जेक्ट छवि का डेटा। |
### OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleWordProcessingOptions-byte---byte---java.lang.String-int-}
```
public OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


नए उदाहरण को इनिशियलाइज़ करता है [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| objectData | byte[] | एम्बेडेड ऑब्जेक्ट का डेटा। |
| imageData | byte[] | एम्बेडेड ऑब्जेक्ट का इमेज डेटा। |
| विस्तार | java.lang.String | एम्बेडेड ऑब्जेक्ट का विस्तार। |
| pageNumber | int | एम्बेडेड ऑब्जेक्ट जोड़ने के लिए पेज नंबर। |

### OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber) {#OleWordProcessingOptions-java.lang.String-byte---int-}
```
public OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)
```


नए उदाहरण को इनिशियलाइज़ करता है [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | एम्बेडेड ऑब्जेक्ट का फ़ाइल पाथ। |
| imageData | byte[] | एम्बेडेड ऑब्जेक्ट का इमेज डेटा। |
| pageNumber | int | एम्बेडेड ऑब्जेक्ट जोड़ने के लिए पेज नंबर। |

### OleWordProcessingOptions(String filePath, int pageNumber) {#OleWordProcessingOptions-java.lang.String-int-}
```
public OleWordProcessingOptions(String filePath, int pageNumber)
```


नए उदाहरण को इनिशियलाइज़ करता है [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | एम्बेडेड ऑब्जेक्ट का फ़ाइल पाथ। |
| pageNumber | int | एम्बेडेड ऑब्जेक्ट जोड़ने के लिए पेज नंबर। |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Ole ऑब्जेक्ट छवि का बायाँ निर्देशांक।

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Ole ऑब्जेक्ट छवि का बायाँ निर्देशांक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Ole ऑब्जेक्ट छवि का ऊपर का निर्देशांक।

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Ole ऑब्जेक्ट छवि का ऊपर का निर्देशांक।

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
