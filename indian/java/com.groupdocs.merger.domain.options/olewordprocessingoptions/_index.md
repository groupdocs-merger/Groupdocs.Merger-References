---
title: "OleWordProcessingOptions"
second_title: "GroupDocs.Merger के लिए Java API संदर्भ"
description: "OLE के माध्यम से एम्बेडेड दस्तावेज़ को वर्ड प्रोसेसिंग में इम्पोर्ट करने के विकल्प प्रदान करता है।"
type: docs
weight: 21
url: /hi/java/com.groupdocs.merger.domain.options/olewordprocessingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleWordProcessingOptions](../../com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions)
```
public class OleWordProcessingOptions extends ImportDocumentOptions implements IOleWordProcessingOptions
```

OLE के माध्यम से एम्बेडेड दस्तावेज़ को वर्ड प्रोसेसिंग में इम्पोर्ट करने के विकल्प प्रदान करता है।

--------------------

**Learn more**

 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]


[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleWordProcessingOptions-byte---byte---java.lang.String-int-) | नया उदाहरण प्रारंभ करता है [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) वर्ग का. |
| [OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)](#OleWordProcessingOptions-java.lang.String-byte---int-) | नया उदाहरण प्रारंभ करता है [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) वर्ग का. |
| [OleWordProcessingOptions(String filePath, int pageNumber)](#OleWordProcessingOptions-java.lang.String-int-) | नया उदाहरण प्रारंभ करता है [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) वर्ग का. |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getLeft()](#getLeft--) | Ole ऑब्जेक्ट छवि का बायां निर्देशांक। |
| [setLeft(int value)](#setLeft-int-) | Ole ऑब्जेक्ट छवि का बायां निर्देशांक। |
| [getTop()](#getTop--) | Ole ऑब्जेक्ट छवि का ऊपर का निर्देशांक। |
| [setTop(int value)](#setTop-int-) | Ole ऑब्जेक्ट छवि का ऊपर का निर्देशांक। |
| [getWidth()](#getWidth--) | Ole ऑब्जेक्ट छवि की चौड़ाई. |
| [setWidth(int value)](#setWidth-int-) | Ole ऑब्जेक्ट छवि की चौड़ाई. |
| [getHeight()](#getHeight--) | Ole ऑब्जेक्ट छवि की ऊँचाई. |
| [setHeight(int value)](#setHeight-int-) | Ole ऑब्जेक्ट छवि की ऊँचाई. |
| [getImageData()](#getImageData--) | Ole ऑब्जेक्ट छवि का डेटा। |
### OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleWordProcessingOptions-byte---byte---java.lang.String-int-}
```
public OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


नया उदाहरण प्रारंभ करता है [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) वर्ग का.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| objectData | byte[] | एम्बेडेड ऑब्जेक्ट का डेटा। |
| imageData | byte[] | एम्बेडेड ऑब्जेक्ट की इमेज डेटा। |
| एक्सटेंशन | java.lang.String | एम्बेडेड ऑब्जेक्ट का एक्सटेंशन। |
| pageNumber | int | एम्बेडेड ऑब्जेक्ट जोड़ने के लिए पृष्ठ संख्या. |

### OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber) {#OleWordProcessingOptions-java.lang.String-byte---int-}
```
public OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)
```


नया उदाहरण प्रारंभ करता है [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) वर्ग का.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | एम्बेडेड ऑब्जेक्ट का फ़ाइल पथ. |
| imageData | byte[] | एम्बेडेड ऑब्जेक्ट की इमेज डेटा। |
| pageNumber | int | एम्बेडेड ऑब्जेक्ट जोड़ने के लिए पृष्ठ संख्या. |

### OleWordProcessingOptions(String filePath, int pageNumber) {#OleWordProcessingOptions-java.lang.String-int-}
```
public OleWordProcessingOptions(String filePath, int pageNumber)
```


नया उदाहरण प्रारंभ करता है [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) वर्ग का.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | एम्बेडेड ऑब्जेक्ट का फ़ाइल पथ. |
| pageNumber | int | एम्बेडेड ऑब्जेक्ट जोड़ने के लिए पृष्ठ संख्या. |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Ole ऑब्जेक्ट छवि का बायां निर्देशांक।

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Ole ऑब्जेक्ट छवि का बायां निर्देशांक।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ole ऑब्जेक्ट छवि की चौड़ाई.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ole ऑब्जेक्ट छवि की चौड़ाई.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ole ऑब्जेक्ट छवि की ऊँचाई.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ole ऑब्जेक्ट छवि की ऊँचाई.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Ole ऑब्जेक्ट छवि का डेटा।

**Returns:**
byte[]
