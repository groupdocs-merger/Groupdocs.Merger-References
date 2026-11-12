---
title: "SplitOptions"
second_title: "GroupDocs.Merger के लिए Java API संदर्भ"
description: "दस्तावेज़ पृष्ठ विभाजन के विकल्प प्रदान करता है।"
type: docs
weight: 38
url: /hi/java/com.groupdocs.merger.domain.options/splitoptions/
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
| [SplitOptions(int[] pageNumbers, int splitMode)](#SplitOptions-int---int-) | नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(int splitMode, int startNumber, int endNumber)](#SplitOptions-int-int-int-) | नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-int-int-int-int-) | नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(String filePathFormat, int[] pageNumbers)](#SplitOptions-java.lang.String-int---) | नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)](#SplitOptions-java.lang.String-int---int-) | नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-) | नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-int-) | नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)](#SplitOptions-java.lang.String-int-int-java.lang.Integer-) | नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-java.lang.String-int-int-int-int-) | नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(SplitStreamFactory splitStreamFactory)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-) | नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-) | नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-) | नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-) | नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-) | नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-) | नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getMode()](#getMode--) | पृष्ठ विभाजन के लिए मोड प्राप्त करता है। |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | विभाजन विकल्पों को मान्य करता है। |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | इंडेक्स द्वारा विभाजित दस्तावेज़ का पूर्ण फ़ाइल पथ प्राप्त करता है, पूर्व-परिभाषित एक्सटेंशन के साथ। |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | आउटपुट पृष्ठ पूर्वावलोकन स्ट्रीम बनाने या रिलीज़ करने के लिए SplitStreamFactory। |
### SplitOptions(int[] pageNumbers, int splitMode) {#SplitOptions-int---int-}
```
public SplitOptions(int[] pageNumbers, int splitMode)
```


नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pageNumbers | int[] | पृष्ठ संख्याएँ। |
| splitMode | int | विभाजन मोड Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)). |

### SplitOptions(int splitMode, int startNumber, int endNumber) {#SplitOptions-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber)
```


नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| splitMode | int | विभाजन मोड Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)). |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |

### SplitOptions(int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-int-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber, int mode)
```


नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| splitMode | int | विभाजन मोड Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)). |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |
| मोड | int | रेंज मोड। |

### SplitOptions(String filePathFormat, int[] pageNumbers) {#SplitOptions-java.lang.String-int---}
```
public SplitOptions(String filePathFormat, int[] pageNumbers)
```


नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePathFormat | java.lang.String | फ़ाइल पथ प्रारूप जैसे 'c:/split\\{0\\}.doc' या 'c:/split\\{0\\}.\\{1\\}' पहले से परिभाषित एक्सटेंशन के साथ। |
| pageNumbers | int[] | पृष्ठ संख्याएँ। |

### SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode) {#SplitOptions-java.lang.String-int---int-}
```
public SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)
```


नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePathFormat | java.lang.String | फ़ाइल पथ प्रारूप जैसे 'c:/split\\{0\\}.doc' या 'c:/split\\{0\\}.\\{1\\}' पहले से परिभाषित एक्सटेंशन के साथ। |
| pageNumbers | int[] | पृष्ठ संख्याएँ। |
| splitMode | int | विभाजन मोड Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)). |

### SplitOptions(String filePathFormat, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber)
```


नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePathFormat | java.lang.String | फ़ाइल पथ प्रारूप जैसे 'c:/split\\{0\\}.doc' या 'c:/split\\{0\\}.\\{1\\}' पहले से परिभाषित एक्सटेंशन के साथ। |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)
```


नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePathFormat | java.lang.String | फ़ाइल पथ प्रारूप जैसे 'c:/split\\{0\\}.doc' या 'c:/split\\{0\\}.\\{1\\}' पहले से परिभाषित एक्सटेंशन के साथ। |
| splitMode | int | विभाजन मोड Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)). |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |

### SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode) {#SplitOptions-java.lang.String-int-int-java.lang.Integer-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)
```


नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePathFormat | java.lang.String | फ़ाइल पथ प्रारूप जैसे 'c:/split\\{0\\}.doc' या 'c:/split\\{0\\}.\\{1\\}' पहले से परिभाषित एक्सटेंशन के साथ। |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |
| मोड | java.lang.Integer | रेंज मोड। |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-java.lang.String-int-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)
```


नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePathFormat | java.lang.String | फ़ाइल पथ प्रारूप जैसे 'c:/split\\{0\\}.doc' या 'c:/split\\{0\\}.\\{1\\}' पहले से परिभाषित एक्सटेंशन के साथ। |
| splitMode | int | विभाजन मोड Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)). |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |
| मोड | int | रेंज मोड। |

### SplitOptions(SplitStreamFactory splitStreamFactory) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory)
```


नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | वह मेथड जो आउटपुट विभाजित डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंसिएट करता है। |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)
```


नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | वह मेथड जो आउटपुट विभाजित डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंसिएट करता है। |
| pageNumbers | int[] | पृष्ठ संख्याएँ। |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)
```


नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | वह मेथड जो आउटपुट विभाजित डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंसिएट करता है। |
| pageNumbers | int[] | पृष्ठ संख्याएँ। |
| splitMode | int | विभाजन मोड Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)). |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)
```


नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | वह मेथड जो आउटपुट विभाजित डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंसिएट करता है। |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)
```


नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | वह मेथड जो आउटपुट विभाजित डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंसिएट करता है। |
| splitMode | int | विभाजन मोड Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)). |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)
```


नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | वह मेथड जो आउटपुट विभाजित डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंसिएट करता है। |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |
| मोड | java.lang.Integer | रेंज मोड। |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)
```


नया उदाहरण प्रारंभ करता है [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) क्लास का।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | वह मेथड जो आउटपुट विभाजित डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंसिएट करता है। |
| splitMode | int | विभाजन मोड Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)). |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |
| मोड | int | रेंज मोड। |

### getMode() {#getMode--}
```
public final int getMode()
```


पृष्ठ विभाजन के लिए मोड प्राप्त करता है।

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


विभाजन विकल्पों को मान्य करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | फ़ाइल प्रकार [FileType](../../com.groupdocs.merger.domain/filetype) क्लास का। |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


इंडेक्स द्वारा विभाजित दस्तावेज़ का पूर्ण फ़ाइल पथ प्राप्त करता है, पूर्व-परिभाषित एक्सटेंशन के साथ।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| इंडेक्स | int | विभाजित दस्तावेज़ का इंडेक्स। |
| एक्सटेंशन | java.lang.String | फ़ाइल का एक्सटेंशन। |

**Returns:**
java.lang.String - पूर्ण फ़ाइल पथ।
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


आउटपुट पृष्ठ पूर्वावलोकन स्ट्रीम बनाने या रिलीज़ करने के लिए SplitStreamFactory।

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
