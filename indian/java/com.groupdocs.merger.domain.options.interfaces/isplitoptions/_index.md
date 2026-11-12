---
title: "ISplitOptions"
second_title: "GroupDocs.Merger के लिए Java API संदर्भ"
description: "स्प्लिटिंग विकल्पों के लिए इंटरफ़ेस।"
type: docs
weight: 33
url: /hi/java/com.groupdocs.merger.domain.options.interfaces/isplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface ISplitOptions extends IPageOptions
```

स्प्लिटिंग विकल्पों के लिए इंटरफ़ेस।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getMode()](#getMode--) | पृष्ठ विभाजन के लिए मोड प्राप्त करता है। |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | विभाजन विकल्पों को मान्य करता है। |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | निर्दिष्ट एक्सटेंशन के साथ इंडेक्स द्वारा विभाजित दस्तावेज़ का पूर्ण फ़ाइल पथ प्राप्त करता है। |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | डेलीगेट जो आउटपुट विभाजन स्ट्रीम बनाने की विधि को परिभाषित करता है। |
### getMode() {#getMode--}
```
public abstract int getMode()
```


पृष्ठ विभाजन के लिए मोड प्राप्त करता है।

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

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public abstract String getPathByIndex(int index, String extension)
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
public abstract SplitStreamFactory getSplitStreamFactory()
```


डेलीगेट जो आउटपुट विभाजन स्ट्रीम बनाने की विधि को परिभाषित करता है।

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
