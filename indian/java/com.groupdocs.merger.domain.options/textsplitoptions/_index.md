---
title: "TextSplitOptions"
second_title: "GroupDocs.Merger के लिए Java API संदर्भ"
description: "दस्तावेज़ पाठ विभाजन के विकल्प प्रदान करता है।"
type: docs
weight: 41
url: /hi/java/com.groupdocs.merger.domain.options/textsplitoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions)
```
public class TextSplitOptions implements ITextSplitOptions
```

दस्तावेज़ पाठ विभाजन के विकल्प प्रदान करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [TextSplitOptions(int[] lineNumbers)](#TextSplitOptions-int---) | नए [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [TextSplitOptions(int mode, int[] lineNumbers)](#TextSplitOptions-int-int---) | नए [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [TextSplitOptions(String filePathFormat, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int---) | नए [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int-int---) | नए [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | नए [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---) | नए [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) क्लास का एक नया उदाहरण प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getMode()](#getMode--) | पाठ विभाजन का मोड। |
| [getLineNumbers()](#getLineNumbers--) | पाठ विभाजन के लिए पंक्ति संख्याएँ। |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | विभाजन विकल्पों को मान्य करता है। |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | निर्दिष्ट एक्सटेंशन के साथ इंडेक्स द्वारा विभाजित दस्तावेज़ का पूर्ण फ़ाइल पथ प्राप्त करता है। |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | आउटपुट पृष्ठ पूर्वावलोकन स्ट्रीम बनाने या रिलीज़ करने के लिए SplitStreamFactory। |
### TextSplitOptions(int[] lineNumbers) {#TextSplitOptions-int---}
```
public TextSplitOptions(int[] lineNumbers)
```


नए [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| lineNumbers | int[] | पाठ विभाजन के लिए पंक्ति संख्याएँ। |

### TextSplitOptions(int mode, int[] lineNumbers) {#TextSplitOptions-int-int---}
```
public TextSplitOptions(int mode, int[] lineNumbers)
```


नए [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मोड | int | पाठ विभाजन का मोड। |
| lineNumbers | int[] | पाठ विभाजन के लिए पंक्ति संख्याएँ। |

### TextSplitOptions(String filePathFormat, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int---}
```
public TextSplitOptions(String filePathFormat, int[] lineNumbers)
```


नए [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePathFormat | java.lang.String | फ़ाइल पाथ फ़ॉर्मेट जैसे 'c:/split\{0\}.doc' या 'c:/split\{0\}.\{1\}' जिसमें पहले से परिभाषित एक्सटेंशन हो। |
| lineNumbers | int[] | पाठ विभाजन के लिए पंक्ति संख्याएँ। |

### TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int-int---}
```
public TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)
```


नए [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| filePathFormat | java.lang.String | फ़ाइल पाथ फ़ॉर्मेट जैसे 'c:/split\{0\}.doc' या 'c:/split\{0\}.\{1\}' जिसमें पहले से परिभाषित एक्सटेंशन हो। |
| मोड | int | पाठ विभाजन का मोड। |
| lineNumbers | int[] | पाठ विभाजन के लिए पंक्ति संख्याएँ। |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)
```


नए [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | वह मेथड जो आउटपुट विभाजित डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंसिएट करता है। |
| lineNumbers | int[] | पाठ विभाजन के लिए पंक्ति संख्याएँ। |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)
```


नए [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | वह मेथड जो आउटपुट विभाजित डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंसिएट करता है। |
| मोड | int | पाठ विभाजन का मोड। |
| lineNumbers | int[] | पाठ विभाजन के लिए पंक्ति संख्याएँ। |

### getMode() {#getMode--}
```
public final int getMode()
```


पाठ विभाजन का मोड।

**Returns:**
int
### getLineNumbers() {#getLineNumbers--}
```
public final int[] getLineNumbers()
```


पाठ विभाजन के लिए पंक्ति संख्याएँ।

**Returns:**
int[]
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


निर्दिष्ट एक्सटेंशन के साथ इंडेक्स द्वारा विभाजित दस्तावेज़ का पूर्ण फ़ाइल पथ प्राप्त करता है।

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
