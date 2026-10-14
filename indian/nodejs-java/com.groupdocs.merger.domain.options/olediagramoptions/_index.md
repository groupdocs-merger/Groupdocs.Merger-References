---
title: "OleDiagramOptions"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "OLE के माध्यम से एम्बेडेड दस्तावेज़ को डायग्राम में आयात करने के विकल्प प्रदान करता है।"
type: docs
weight: 18
url: /hi/nodejs-java/com.groupdocs.merger.domain.options/olediagramoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleDiagramOptions](../../com.groupdocs.merger.domain.options.interfaces/iolediagramoptions)
```
public class OleDiagramOptions extends ImportDocumentOptions implements IOleDiagramOptions
```

OLE के माध्यम से एम्बेडेड दस्तावेज़ को डायग्राम में आयात करने के विकल्प प्रदान करता है।

--------------------

**Learn more**

 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleDiagramOptions-byte---byte---java.lang.String-int-) | एक नया उदाहरण प्रारंभ करता है [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) क्लास का। |
| [OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)](#OleDiagramOptions-java.lang.String-byte---int-) | एक नया उदाहरण प्रारंभ करता है [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) क्लास का। |
| [OleDiagramOptions(String filePath, int pageNumber)](#OleDiagramOptions-java.lang.String-int-) | एक नया उदाहरण प्रारंभ करता है [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getX()](#getX--) | पृष्ठ के सापेक्ष एम्बेडेड ऑब्जेक्ट आकार के पिन (घूर्णन केंद्र) का X निर्देशांक। |
| [setX(int value)](#setX-int-) | पृष्ठ के सापेक्ष एम्बेडेड ऑब्जेक्ट आकार के पिन (घूर्णन केंद्र) का X निर्देशांक। |
| [getY()](#getY--) | पृष्ठ के सापेक्ष एम्बेडेड ऑब्जेक्ट आकार के पिन (घूर्णन केंद्र) का Y निर्देशांक। |
| [setY(int value)](#setY-int-) | पृष्ठ के सापेक्ष एम्बेडेड ऑब्जेक्ट आकार के पिन (घूर्णन केंद्र) का Y निर्देशांक। |
| [getWidth()](#getWidth--) | एम्बेडेड ऑब्जेक्ट आकार की चौड़ाई इंच में। |
| [setWidth(int value)](#setWidth-int-) | एम्बेडेड ऑब्जेक्ट आकार की चौड़ाई इंच में। |
| [getHeight()](#getHeight--) | एम्बेडेड ऑब्जेक्ट आकार की ऊँचाई इंच में। |
| [setHeight(int value)](#setHeight-int-) | एम्बेडेड ऑब्जेक्ट आकार की ऊँचाई इंच में। |
| [getImageData()](#getImageData--) | एम्बेडेड ऑब्जेक्ट का इमेज डेटा। |
### OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleDiagramOptions-byte---byte---java.lang.String-int-}
```
public OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


एक नया उदाहरण प्रारंभ करता है [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| objectData | byte[] | एम्बेडेड ऑब्जेक्ट का डेटा। |
| imageData | byte[] | एम्बेडेड ऑब्जेक्ट का इमेज डेटा। |
| विस्तार | java.lang.String | एम्बेडेड ऑब्जेक्ट का विस्तार। |
| pageNumber | int | एम्बेडेड ऑब्जेक्ट जोड़ने के लिए पेज नंबर। |

### OleDiagramOptions(String filePath, byte[] imageData, int pageNumber) {#OleDiagramOptions-java.lang.String-byte---int-}
```
public OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)
```


एक नया उदाहरण प्रारंभ करता है [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | एम्बेडेड ऑब्जेक्ट का फ़ाइल पाथ। |
| imageData | byte[] | एम्बेडेड ऑब्जेक्ट का इमेज डेटा। |
| pageNumber | int | एम्बेडेड ऑब्जेक्ट जोड़ने के लिए पेज नंबर। |

### OleDiagramOptions(String filePath, int pageNumber) {#OleDiagramOptions-java.lang.String-int-}
```
public OleDiagramOptions(String filePath, int pageNumber)
```


एक नया उदाहरण प्रारंभ करता है [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | एम्बेडेड ऑब्जेक्ट का फ़ाइल पाथ। |
| pageNumber | int | एम्बेडेड ऑब्जेक्ट जोड़ने के लिए पेज नंबर। |

### getX() {#getX--}
```
public final int getX()
```


पृष्ठ के सापेक्ष एम्बेडेड ऑब्जेक्ट आकार के पिन (घूर्णन केंद्र) का X निर्देशांक।

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


पृष्ठ के सापेक्ष एम्बेडेड ऑब्जेक्ट आकार के पिन (घूर्णन केंद्र) का X निर्देशांक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


पृष्ठ के सापेक्ष एम्बेडेड ऑब्जेक्ट आकार के पिन (घूर्णन केंद्र) का Y निर्देशांक।

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


पृष्ठ के सापेक्ष एम्बेडेड ऑब्जेक्ट आकार के पिन (घूर्णन केंद्र) का Y निर्देशांक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


एम्बेडेड ऑब्जेक्ट आकार की चौड़ाई इंच में।

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


एम्बेडेड ऑब्जेक्ट आकार की चौड़ाई इंच में।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


एम्बेडेड ऑब्जेक्ट आकार की ऊँचाई इंच में।

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


एम्बेडेड ऑब्जेक्ट आकार की ऊँचाई इंच में।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


एम्बेडेड ऑब्जेक्ट का इमेज डेटा।

**Returns:**
byte[]
