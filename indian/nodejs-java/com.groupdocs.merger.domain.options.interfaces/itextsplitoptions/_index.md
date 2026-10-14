---
title: "ITextSplitOptions"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "पाठ विभाजन विकल्पों के लिए इंटरफ़ेस।"
type: docs
weight: 35
url: /hi/nodejs-java/com.groupdocs.merger.domain.options.interfaces/itextsplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ITextSplitOptions extends IOptions
```

पाठ विभाजन विकल्पों के लिए इंटरफ़ेस।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLineNumbers()](#getLineNumbers--) | पाठ विभाजन के लिए पंक्ति संख्याएँ। |
| [getMode()](#getMode--) | पाठ विभाजन के लिए मोड। |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | विभाजन विकल्पों को मान्य करता है। |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | निर्दिष्ट एक्सटेंशन के साथ इंडेक्स द्वारा विभाजित दस्तावेज़ का पूर्ण फ़ाइल पथ प्राप्त करता है। |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | आउटपुट विभाजित स्ट्रीम बनाने के लिए विधि को परिभाषित करने वाला डेलीगेट। |
### getLineNumbers() {#getLineNumbers--}
```
public abstract int[] getLineNumbers()
```


पाठ विभाजन के लिए पंक्ति संख्याएँ।

**Returns:**
int[]
### getMode() {#getMode--}
```
public abstract int getMode()
```


पाठ विभाजन के लिए मोड।

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

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public abstract String getPathByIndex(int index, String extension)
```


निर्दिष्ट एक्सटेंशन के साथ इंडेक्स द्वारा विभाजित दस्तावेज़ का पूर्ण फ़ाइल पथ प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| सूचकांक | int | विभाजित दस्तावेज़ का इंडेक्स। |
| विस्तार | java.lang.String | फ़ाइल का विस्तार। |

**Returns:**
java.lang.String - पूर्ण फ़ाइल पथ।
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public abstract SplitStreamFactory getSplitStreamFactory()
```


आउटपुट विभाजित स्ट्रीम बनाने के लिए विधि को परिभाषित करने वाला डेलीगेट।

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
