---
title: "PageJoinOptions"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "दस्तावेज़ जॉइनिंग के विकल्प प्रदान करता है।"
type: docs
weight: 25
url: /hi/nodejs-java/com.groupdocs.merger.domain.options/pagejoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions)
```
public class PageJoinOptions extends PageOptions implements IPageJoinOptions
```

दस्तावेज़ जॉइनिंग के विकल्प प्रदान करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PageJoinOptions()](#PageJoinOptions--) | एक नया उदाहरण प्रारंभ करता है [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) क्लास का। |
| [PageJoinOptions(int[] pageNumbers)](#PageJoinOptions-int---) | एक नया उदाहरण प्रारंभ करता है [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) क्लास का। |
| [PageJoinOptions(int startNumber, int endNumber)](#PageJoinOptions-int-int-) | एक नया उदाहरण प्रारंभ करता है [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) क्लास का। |
| [PageJoinOptions(int startNumber, int endNumber, int mode)](#PageJoinOptions-int-int-int-) | एक नया उदाहरण प्रारंभ करता है [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) क्लास का। |
| [PageJoinOptions(FileType fileType)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-) | एक नया उदाहरण प्रारंभ करता है [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) क्लास का। |
| [PageJoinOptions(FileType fileType, int[] pageNumbers)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---) | एक नया उदाहरण प्रारंभ करता है [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) क्लास का। |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | एक नया उदाहरण प्रारंभ करता है [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) क्लास का। |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | एक नया उदाहरण प्रारंभ करता है [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getType()](#getType--) | जोड़ने के लिए फ़ाइल का प्रकार। |
### PageJoinOptions() {#PageJoinOptions--}
```
public PageJoinOptions()
```


एक नया उदाहरण प्रारंभ करता है [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) क्लास का।

### PageJoinOptions(int[] pageNumbers) {#PageJoinOptions-int---}
```
public PageJoinOptions(int[] pageNumbers)
```


एक नया उदाहरण प्रारंभ करता है [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageNumbers | int[] | पृष्ठ संख्याएँ। |

### PageJoinOptions(int startNumber, int endNumber) {#PageJoinOptions-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber)
```


एक नया उदाहरण प्रारंभ करता है [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |

### PageJoinOptions(int startNumber, int endNumber, int mode) {#PageJoinOptions-int-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber, int mode)
```


एक नया उदाहरण प्रारंभ करता है [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |
| mode | int | रेंज मोड। |

### PageJoinOptions(FileType fileType) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public PageJoinOptions(FileType fileType)
```


एक नया उदाहरण प्रारंभ करता है [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | जोड़ने के लिए फ़ाइल का प्रकार। |

### PageJoinOptions(FileType fileType, int[] pageNumbers) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public PageJoinOptions(FileType fileType, int[] pageNumbers)
```


एक नया उदाहरण प्रारंभ करता है [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | जोड़ने के लिए फ़ाइल का प्रकार। |
| pageNumbers | int[] | पृष्ठ संख्याएँ। |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber)
```


एक नया उदाहरण प्रारंभ करता है [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | जोड़ने के लिए फ़ाइल का प्रकार। |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


एक नया उदाहरण प्रारंभ करता है [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | जोड़ने के लिए फ़ाइल का प्रकार। |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |
| mode | int | रेंज मोड। |

### getType() {#getType--}
```
public final FileType getType()
```


जोड़ने के लिए फ़ाइल का प्रकार।

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
