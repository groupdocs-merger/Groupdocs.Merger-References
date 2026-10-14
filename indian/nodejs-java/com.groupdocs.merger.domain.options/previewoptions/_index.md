---
title: "PreviewOptions"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "दस्तावेज़ पूर्वावलोकन विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 29
url: /hi/nodejs-java/com.groupdocs.merger.domain.options/previewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions)
```
public class PreviewOptions extends PageOptions implements IPreviewOptions
```

दस्तावेज़ पूर्वावलोकन विकल्पों का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-) | नया उदाहरण प्रारंभ करता है [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) क्लास का। |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---) | नया उदाहरण प्रारंभ करता है [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) क्लास का। |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-) | नया उदाहरण प्रारंभ करता है [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) क्लास का। |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-) | नया उदाहरण प्रारंभ करता है [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getWidth()](#getWidth--) | पूर्वावलोकन चौड़ाई। |
| [setWidth(int value)](#setWidth-int-) | पूर्वावलोकन चौड़ाई। |
| [getHeight()](#getHeight--) | पूर्वावलोकन ऊँचाई। |
| [setHeight(int value)](#setHeight-int-) | पूर्वावलोकन ऊँचाई। |
| [getResolution()](#getResolution--) | छवि रिज़ॉल्यूशन। |
| [setResolution(int value)](#setResolution-int-) | छवि रिज़ॉल्यूशन। |
| [getMode()](#getMode--) | पूर्वावलोकन के लिए मोड। |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | पूर्वावलोकन विकल्पों को मान्य करता है। |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | पृष्ठ संख्या के आधार पर परिभाषित एक्सटेंशन के साथ पूर्वावलोकित दस्तावेज़ का पूर्ण फ़ाइल पथ प्राप्त करता है। |
| [getPageStreamFactory()](#getPageStreamFactory--) | आउटपुट पृष्ठ पूर्वावलोकन स्ट्रीम बनाने या रिलीज़ करने के लिए PageStreamFactory। |
### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)
```


नया उदाहरण प्रारंभ करता है [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | वह विधि जो आउटपुट पृष्ठ डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंसिएट करती है। |
| previewMode | int | Mode का पूर्वावलोकन मोड (\#getMode.getMode/\#setMode(int).setMode(int)) |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)
```


नया उदाहरण प्रारंभ करता है [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | वह विधि जो आउटपुट पृष्ठ डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंसिएट करती है। |
| previewMode | int | Mode का पूर्वावलोकन मोड (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | पृष्ठ संख्याएँ। |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)
```


नया उदाहरण प्रारंभ करता है [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | वह विधि जो आउटपुट पृष्ठ डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंसिएट करती है। |
| previewMode | int | Mode का पूर्वावलोकन मोड (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)
```


नया उदाहरण प्रारंभ करता है [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | वह विधि जो आउटपुट पृष्ठ डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंसिएट करती है। |
| previewMode | int | Mode का पूर्वावलोकन मोड (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |
| mode | int | रेंज मोड। |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


पूर्वावलोकन चौड़ाई।

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


पूर्वावलोकन चौड़ाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


पूर्वावलोकन ऊँचाई।

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


पूर्वावलोकन ऊँचाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


छवि रिज़ॉल्यूशन।

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


छवि रिज़ॉल्यूशन।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public final int getMode()
```


पूर्वावलोकन के लिए मोड।

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


पूर्वावलोकन विकल्पों को मान्य करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | फ़ाइल प्रकार। |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public final String getPathByPageNumber(int pageNumber, String extension)
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
public PageStreamFactory getPageStreamFactory()
```


आउटपुट पृष्ठ पूर्वावलोकन स्ट्रीम बनाने या रिलीज़ करने के लिए PageStreamFactory।

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
