---
title: "OlePresentationOptions"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "OLE के माध्यम से एम्बेडेड दस्तावेज़ को प्रेजेंटेशन में आयात करने के विकल्प प्रदान करता है।"
type: docs
weight: 19
url: /hi/nodejs-java/com.groupdocs.merger.domain.options/olepresentationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOlePresentationOptions](../../com.groupdocs.merger.domain.options.interfaces/iolepresentationoptions)
```
public class OlePresentationOptions extends ImportDocumentOptions implements IOlePresentationOptions
```

OLE के माध्यम से एम्बेडेड दस्तावेज़ को प्रेजेंटेशन में आयात करने के विकल्प प्रदान करता है।

--------------------

**Learn more**

 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]


[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [OlePresentationOptions(byte[] objectData, String extension, int pageNumber)](#OlePresentationOptions-byte---java.lang.String-int-) | एक नया उदाहरण प्रारंभ करता है [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) क्लास का। |
| [OlePresentationOptions(String filePath, int pageNumber)](#OlePresentationOptions-java.lang.String-int-) | एक नया उदाहरण प्रारंभ करता है [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getX()](#getX--) | एम्बेडेड ऑब्जेक्ट फ्रेम का X निर्देशांक। |
| [setX(int value)](#setX-int-) | एम्बेडेड ऑब्जेक्ट फ्रेम का X निर्देशांक। |
| [getY()](#getY--) | एम्बेडेड ऑब्जेक्ट फ्रेम का Y निर्देशांक। |
| [setY(int value)](#setY-int-) | एम्बेडेड ऑब्जेक्ट फ्रेम का Y निर्देशांक। |
| [getWidth()](#getWidth--) | एम्बेडेड ऑब्जेक्ट फ्रेम की चौड़ाई। |
| [setWidth(int value)](#setWidth-int-) | एम्बेडेड ऑब्जेक्ट फ्रेम की चौड़ाई। |
| [getHeight()](#getHeight--) | एम्बेडेड ऑब्जेक्ट फ्रेम की ऊँचाई। |
| [setHeight(int value)](#setHeight-int-) | एम्बेडेड ऑब्जेक्ट फ्रेम की ऊँचाई। |
### OlePresentationOptions(byte[] objectData, String extension, int pageNumber) {#OlePresentationOptions-byte---java.lang.String-int-}
```
public OlePresentationOptions(byte[] objectData, String extension, int pageNumber)
```


एक नया उदाहरण प्रारंभ करता है [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| objectData | byte[] | एम्बेडेड ऑब्जेक्ट का डेटा। |
| विस्तार | java.lang.String | एम्बेडेड ऑब्जेक्ट का विस्तार। |
| pageNumber | int | एम्बेडेड ऑब्जेक्ट जोड़ने के लिए पेज नंबर। |

### OlePresentationOptions(String filePath, int pageNumber) {#OlePresentationOptions-java.lang.String-int-}
```
public OlePresentationOptions(String filePath, int pageNumber)
```


एक नया उदाहरण प्रारंभ करता है [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | एम्बेडेड ऑब्जेक्ट का फ़ाइल पाथ। |
| pageNumber | int | एम्बेडेड ऑब्जेक्ट जोड़ने के लिए पेज नंबर। |

### getX() {#getX--}
```
public final int getX()
```


एम्बेडेड ऑब्जेक्ट फ्रेम का X निर्देशांक।

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


एम्बेडेड ऑब्जेक्ट फ्रेम का X निर्देशांक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


एम्बेडेड ऑब्जेक्ट फ्रेम का Y निर्देशांक।

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


एम्बेडेड ऑब्जेक्ट फ्रेम का Y निर्देशांक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


एम्बेडेड ऑब्जेक्ट फ्रेम की चौड़ाई।

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


एम्बेडेड ऑब्जेक्ट फ्रेम की चौड़ाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


एम्बेडेड ऑब्जेक्ट फ्रेम की ऊँचाई।

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


एम्बेडेड ऑब्जेक्ट फ्रेम की ऊँचाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

