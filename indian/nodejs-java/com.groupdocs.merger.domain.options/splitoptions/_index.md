---
title: "SplitOptions"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "दस्तावेज़ पृष्ठ विभाजन के विकल्प प्रदान करता है।"
type: docs
weight: 36
url: /hi/nodejs-java/com.groupdocs.merger.domain.options/splitoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions)
```
public class SplitOptions extends PageOptions implements ISplitOptions
```

दस्तावेज़ पृष्ठ विभाजन के विकल्प प्रदान करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [SplitOptions(int[] pageNumbers, int splitMode)](#SplitOptions-int---int-) | एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(int splitMode, int startNumber, int endNumber)](#SplitOptions-int-int-int-) | एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-int-int-int-int-) | एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(String filePathFormat, int[] pageNumbers)](#SplitOptions-java.lang.String-int---) | एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)](#SplitOptions-java.lang.String-int---int-) | एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-) | एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-int-) | एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)](#SplitOptions-java.lang.String-int-int-java.lang.Integer-) | एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-java.lang.String-int-int-int-int-) | एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(SplitStreamFactory splitStreamFactory)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-) | एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-) | एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-) | एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-) | एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-) | एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-) | एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getMode()](#getMode--) | पेज विभाजन के लिए मोड प्राप्त करता है। |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | विभाजन विकल्पों को मान्य करता है। |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | निर्धारित एक्सटेंशन के साथ इंडेक्स द्वारा विभाजित दस्तावेज़ का पूर्ण फ़ाइल पथ प्राप्त करता है। |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | आउटपुट पेज प्रीव्यू स्ट्रीम बनाने या रिलीज़ करने के लिए SplitStreamFactory। |
### SplitOptions(int[] pageNumbers, int splitMode) {#SplitOptions-int---int-}
```
public SplitOptions(int[] pageNumbers, int splitMode)
```


एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageNumbers | int[] | पृष्ठ संख्याएँ। |
| splitMode | int | विभाजन मोड Mode का (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(int splitMode, int startNumber, int endNumber) {#SplitOptions-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber)
```


एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| splitMode | int | विभाजन मोड Mode का (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |

### SplitOptions(int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-int-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber, int mode)
```


एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| splitMode | int | विभाजन मोड Mode का (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |
| mode | int | रेंज मोड। |

### SplitOptions(String filePathFormat, int[] pageNumbers) {#SplitOptions-java.lang.String-int---}
```
public SplitOptions(String filePathFormat, int[] pageNumbers)
```


एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | java.lang.String | फ़ाइल पथ प्रारूप जैसे 'c:/split\{0\}.doc' या 'c:/split\{0\}.\{1\}' पहले से निर्धारित एक्सटेंशन के साथ। |
| pageNumbers | int[] | पृष्ठ संख्याएँ। |

### SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode) {#SplitOptions-java.lang.String-int---int-}
```
public SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)
```


एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | java.lang.String | फ़ाइल पथ प्रारूप जैसे 'c:/split\{0\}.doc' या 'c:/split\{0\}.\{1\}' पहले से निर्धारित एक्सटेंशन के साथ। |
| pageNumbers | int[] | पृष्ठ संख्याएँ। |
| splitMode | int | विभाजन मोड Mode का (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(String filePathFormat, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber)
```


एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | java.lang.String | फ़ाइल पथ प्रारूप जैसे 'c:/split\{0\}.doc' या 'c:/split\{0\}.\{1\}' पहले से निर्धारित एक्सटेंशन के साथ। |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)
```


एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | java.lang.String | फ़ाइल पथ प्रारूप जैसे 'c:/split\{0\}.doc' या 'c:/split\{0\}.\{1\}' पहले से निर्धारित एक्सटेंशन के साथ। |
| splitMode | int | विभाजन मोड Mode का (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |

### SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode) {#SplitOptions-java.lang.String-int-int-java.lang.Integer-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)
```


एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | java.lang.String | फ़ाइल पथ प्रारूप जैसे 'c:/split\{0\}.doc' या 'c:/split\{0\}.\{1\}' पहले से निर्धारित एक्सटेंशन के साथ। |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |
| mode | java.lang.Integer | रेंज मोड। |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-java.lang.String-int-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)
```


एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | java.lang.String | फ़ाइल पथ प्रारूप जैसे 'c:/split\{0\}.doc' या 'c:/split\{0\}.\{1\}' पहले से निर्धारित एक्सटेंशन के साथ। |
| splitMode | int | विभाजन मोड Mode का (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |
| mode | int | रेंज मोड। |

### SplitOptions(SplitStreamFactory splitStreamFactory) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory)
```


एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | वह मेथड जो स्ट्रीम को इंस्टैंसिएट करता है जिसका उपयोग आउटपुट विभाजित डेटा लिखने के लिए किया जाता है। |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)
```


एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | वह मेथड जो स्ट्रीम को इंस्टैंसिएट करता है जिसका उपयोग आउटपुट विभाजित डेटा लिखने के लिए किया जाता है। |
| pageNumbers | int[] | पृष्ठ संख्याएँ। |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)
```


एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | वह मेथड जो स्ट्रीम को इंस्टैंसिएट करता है जिसका उपयोग आउटपुट विभाजित डेटा लिखने के लिए किया जाता है। |
| pageNumbers | int[] | पृष्ठ संख्याएँ। |
| splitMode | int | विभाजन मोड Mode का (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)
```


एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | वह मेथड जो स्ट्रीम को इंस्टैंसिएट करता है जिसका उपयोग आउटपुट विभाजित डेटा लिखने के लिए किया जाता है। |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)
```


एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | वह मेथड जो स्ट्रीम को इंस्टैंसिएट करता है जिसका उपयोग आउटपुट विभाजित डेटा लिखने के लिए किया जाता है। |
| splitMode | int | विभाजन मोड Mode का (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)
```


एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | वह मेथड जो स्ट्रीम को इंस्टैंसिएट करता है जिसका उपयोग आउटपुट विभाजित डेटा लिखने के लिए किया जाता है। |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |
| mode | java.lang.Integer | रेंज मोड। |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)
```


एक नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | वह मेथड जो स्ट्रीम को इंस्टैंसिएट करता है जिसका उपयोग आउटपुट विभाजित डेटा लिखने के लिए किया जाता है। |
| splitMode | int | विभाजन मोड Mode का (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |
| mode | int | रेंज मोड। |

### getMode() {#getMode--}
```
public final int getMode()
```


पेज विभाजन के लिए मोड प्राप्त करता है।

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


विभाजन विकल्पों को मान्य करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | [FileType](../../com.groupdocs.merger.domain/filetype) क्लास का फ़ाइल प्रकार। |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


निर्धारित एक्सटेंशन के साथ इंडेक्स द्वारा विभाजित दस्तावेज़ का पूर्ण फ़ाइल पथ प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| सूचकांक | int | विभाजित दस्तावेज़ का इंडेक्स। |
| विस्तार | java.lang.String | फ़ाइल का विस्तार। |

**Returns:**
java.lang.String - पूर्ण फ़ाइल पथ।
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


आउटपुट पेज प्रीव्यू स्ट्रीम बनाने या रिलीज़ करने के लिए SplitStreamFactory।

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
