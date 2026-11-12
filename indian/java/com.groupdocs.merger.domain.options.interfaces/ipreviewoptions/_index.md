---
title: "IPreviewOptions"
second_title: "GroupDocs.Merger के लिए Java API संदर्भ"
description: "प्रिव्यू विकल्पों के लिए इंटरफ़ेस।"
type: docs
weight: 28
url: /hi/java/com.groupdocs.merger.domain.options.interfaces/ipreviewoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface IPreviewOptions extends IPageOptions
```

प्रिव्यू विकल्पों के लिए इंटरफ़ेस।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getWidth()](#getWidth--) | पूर्वावलोकन की चौड़ाई। |
| [setWidth(int value)](#setWidth-int-) | पूर्वावलोकन की चौड़ाई। |
| [getHeight()](#getHeight--) | पूर्वावलोकन की ऊँचाई। |
| [setHeight(int value)](#setHeight-int-) | पूर्वावलोकन की ऊँचाई। |
| [getResolution()](#getResolution--) | छवि रिज़ॉल्यूशन। |
| [setResolution(int value)](#setResolution-int-) | छवि रिज़ॉल्यूशन। |
| [getMode()](#getMode--) | पूर्वावलोकन के मोड को प्राप्त करता है। |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | विभाजन विकल्पों को मान्य करता है। |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | परिभाषित एक्सटेंशन के साथ पृष्ठ संख्या द्वारा पूर्वावलोकित दस्तावेज़ का पूर्ण फ़ाइल पथ प्राप्त करता है। |
| [getPageStreamFactory()](#getPageStreamFactory--) | डेलीगेट जो आउटपुट पृष्ठ पूर्वावलोकन स्ट्रीम बनाने की विधि को परिभाषित करता है। |
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


पूर्वावलोकन की चौड़ाई।

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public abstract void setWidth(int value)
```


पूर्वावलोकन की चौड़ाई।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


पूर्वावलोकन की ऊँचाई।

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public abstract void setHeight(int value)
```


पूर्वावलोकन की ऊँचाई।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getMode() {#getMode--}
```
public abstract int getMode()
```


पूर्वावलोकन के मोड को प्राप्त करता है।

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


विभाजन विकल्पों को मान्य करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | फ़ाइल प्रकार [FileType](../../com.groupdocs.merger.domain/filetype) क्लास का। |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public abstract String getPathByPageNumber(int pageNumber, String extension)
```


परिभाषित एक्सटेंशन के साथ पृष्ठ संख्या द्वारा पूर्वावलोकित दस्तावेज़ का पूर्ण फ़ाइल पथ प्राप्त करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pageNumber | int | पूर्वावलोकन का पृष्ठ संख्या। |
| एक्सटेंशन | java.lang.String | फ़ाइल का एक्सटेंशन। |

**Returns:**
java.lang.String - पूर्ण फ़ाइल पथ।
### getPageStreamFactory() {#getPageStreamFactory--}
```
public abstract PageStreamFactory getPageStreamFactory()
```


डेलीगेट जो आउटपुट पृष्ठ पूर्वावलोकन स्ट्रीम बनाने की विधि को परिभाषित करता है।

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
