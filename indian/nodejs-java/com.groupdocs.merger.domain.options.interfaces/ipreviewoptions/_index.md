---
title: "IPreviewOptions"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "पूर्वावलोकन विकल्पों के लिए इंटरफ़ेस।"
type: docs
weight: 28
url: /hi/nodejs-java/com.groupdocs.merger.domain.options.interfaces/ipreviewoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface IPreviewOptions extends IPageOptions
```

पूर्वावलोकन विकल्पों के लिए इंटरफ़ेस।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getWidth()](#getWidth--) | पूर्वावलोकन चौड़ाई। |
| [setWidth(int value)](#setWidth-int-) | पूर्वावलोकन चौड़ाई। |
| [getHeight()](#getHeight--) | पूर्वावलोकन ऊँचाई। |
| [setHeight(int value)](#setHeight-int-) | पूर्वावलोकन ऊँचाई। |
| [getResolution()](#getResolution--) | छवि रिज़ॉल्यूशन। |
| [setResolution(int value)](#setResolution-int-) | छवि रिज़ॉल्यूशन। |
| [getMode()](#getMode--) | पूर्वावलोकन के लिए मोड प्राप्त करता है। |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | विभाजन विकल्पों को मान्य करता है। |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | पृष्ठ संख्या के आधार पर परिभाषित एक्सटेंशन के साथ पूर्वावलोकित दस्तावेज़ का पूर्ण फ़ाइल पथ प्राप्त करता है। |
| [getPageStreamFactory()](#getPageStreamFactory--) | आउटपुट पृष्ठ पूर्वावलोकन स्ट्रीम बनाने की विधि को परिभाषित करने वाला डेलीगेट। |
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


पूर्वावलोकन चौड़ाई।

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public abstract void setWidth(int value)
```


पूर्वावलोकन चौड़ाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


पूर्वावलोकन ऊँचाई।

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public abstract void setHeight(int value)
```


पूर्वावलोकन ऊँचाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public abstract int getResolution()
```


छवि रिज़ॉल्यूशन।

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public abstract void setResolution(int value)
```


छवि रिज़ॉल्यूशन।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public abstract int getMode()
```


पूर्वावलोकन के लिए मोड प्राप्त करता है।

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


विभाजन विकल्पों को मान्य करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | [FileType](../../com.groupdocs.merger.domain/filetype) क्लास का फ़ाइल प्रकार। |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public abstract String getPathByPageNumber(int pageNumber, String extension)
```


पृष्ठ संख्या के आधार पर परिभाषित एक्सटेंशन के साथ पूर्वावलोकित दस्तावेज़ का पूर्ण फ़ाइल पथ प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageNumber | int | पूर्वावलोकन का पृष्ठ संख्या। |
| विस्तार | java.lang.String | फ़ाइल का विस्तार। |

**Returns:**
java.lang.String - पूर्ण फ़ाइल पथ।
### getPageStreamFactory() {#getPageStreamFactory--}
```
public abstract PageStreamFactory getPageStreamFactory()
```


आउटपुट पृष्ठ पूर्वावलोकन स्ट्रीम बनाने की विधि को परिभाषित करने वाला डेलीगेट।

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
