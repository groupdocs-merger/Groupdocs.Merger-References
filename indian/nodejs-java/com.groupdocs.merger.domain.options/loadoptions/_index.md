---
title: "LoadOptions"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "दस्तावेज़ लोड करने के विकल्प प्रदान करता है।"
type: docs
weight: 16
url: /hi/nodejs-java/com.groupdocs.merger.domain.options/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

दस्तावेज़ लोड करने के विकल्प प्रदान करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-) | एक नया उदाहरण प्रारंभ करता है [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) क्लास का। |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | एक नया उदाहरण प्रारंभ करता है [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) क्लास का। |
| [LoadOptions(String password, Charset encoding)](#LoadOptions-java.lang.String-java.nio.charset.Charset-) | एक नया उदाहरण प्रारंभ करता है [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) क्लास का। |
| [LoadOptions(FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-) | एक नया उदाहरण प्रारंभ करता है [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) क्लास का। |
| [LoadOptions(FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | एक नया उदाहरण प्रारंभ करता है [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) क्लास का। |
| [LoadOptions(String extension, FileType fileType, String password, Charset encoding)](#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | एक नया उदाहरण प्रारंभ करता है [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) क्लास का। |
| [LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | एक नया उदाहरण प्रारंभ करता है [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) क्लास का। |
| [LoadOptions(FileType iniFileType, FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-) | एक नया उदाहरण प्रारंभ करता है [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) क्लास का। |
| [LoadOptions(FileType iniFileType, FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | एक नया उदाहरण प्रारंभ करता है [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getType()](#getType--) | लोड करने वाली फ़ाइल का प्रकार। |
| [getExtension()](#getExtension--) | फ़ाइल को प्रारंभ करने के लिए एक्सटेंशन। |
| [getPassword()](#getPassword--) | पासवर्ड-संरक्षित फ़ाइल खोलने के लिए पासवर्ड। |
| [getEncoding()](#getEncoding--) | टेक्स्ट-आधारित फ़ाइलों को खोलते समय उपयोग किया जाने वाला एन्कोडिंग, जैसे [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) या [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType fileType)
```


एक नया उदाहरण प्रारंभ करता है [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | लोड करने वाली फ़ाइल का प्रकार। |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


एक नया उदाहरण प्रारंभ करता है [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पासवर्ड | java.lang.String | पासवर्ड-संरक्षित फ़ाइल खोलने के लिए पासवर्ड। |

### LoadOptions(String password, Charset encoding) {#LoadOptions-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String password, Charset encoding)
```


एक नया उदाहरण प्रारंभ करता है [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पासवर्ड | java.lang.String | पासवर्ड-संरक्षित फ़ाइल खोलने के लिए पासवर्ड। |
| encoding | java.nio.charset.Charset | टेक्स्ट-आधारित फ़ाइलों को खोलते समय उपयोग किया जाने वाला एन्कोडिंग, जैसे [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) या [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType fileType, String password)
```


एक नया उदाहरण प्रारंभ करता है [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | लोड करने वाली फ़ाइल का प्रकार। |
| पासवर्ड | java.lang.String | पासवर्ड-संरक्षित फ़ाइल खोलने के लिए पासवर्ड। |

### LoadOptions(FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType fileType, String password, Charset encoding)
```


एक नया उदाहरण प्रारंभ करता है [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | लोड करने वाली फ़ाइल का प्रकार। |
| पासवर्ड | java.lang.String | पासवर्ड-संरक्षित फ़ाइल खोलने के लिए पासवर्ड। |
| encoding | java.nio.charset.Charset | टेक्स्ट-आधारित फ़ाइलों को खोलते समय उपयोग किया जाने वाला एन्कोडिंग, जैसे [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) या [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(String extension, FileType fileType, String password, Charset encoding) {#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String extension, FileType fileType, String password, Charset encoding)
```


एक नया उदाहरण प्रारंभ करता है [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| विस्तार | java.lang.String | लोड करने वाली फ़ाइल का एक्सटेंशन। |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | लोड करने वाली फ़ाइल का प्रकार। |
| पासवर्ड | java.lang.String | पासवर्ड-संरक्षित फ़ाइल खोलने के लिए पासवर्ड। |
| encoding | java.nio.charset.Charset | टेक्स्ट-आधारित फ़ाइलों को खोलते समय उपयोग किया जाने वाला एन्कोडिंग, जैसे [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) या [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)
```


एक नया उदाहरण प्रारंभ करता है [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | फ़ाइल को प्रारंभ करने का प्रकार। |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | लोड करने वाली फ़ाइल का प्रकार। |
| पासवर्ड | java.lang.String | पासवर्ड-संरक्षित फ़ाइल खोलने के लिए पासवर्ड। |
| encoding | java.nio.charset.Charset | टेक्स्ट-आधारित फ़ाइलों को खोलते समय उपयोग किया जाने वाला एन्कोडिंग, जैसे [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) या [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password)
```


एक नया उदाहरण प्रारंभ करता है [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | फ़ाइल को प्रारंभ करने का प्रकार। |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | लोड करने वाली फ़ाइल का प्रकार। |
| पासवर्ड | java.lang.String | पासवर्ड-संरक्षित फ़ाइल खोलने के लिए पासवर्ड। |

### LoadOptions(FileType iniFileType, FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType iniFileType, FileType fileType)
```


एक नया उदाहरण प्रारंभ करता है [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | फ़ाइल को प्रारंभ करने का प्रकार। |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | लोड करने वाली फ़ाइल का प्रकार। |

### getType() {#getType--}
```
public final FileType getType()
```


लोड करने वाली फ़ाइल का प्रकार।

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getExtension() {#getExtension--}
```
public final String getExtension()
```


फ़ाइल को प्रारंभ करने के लिए एक्सटेंशन।

**Returns:**
java.lang.String
### getPassword() {#getPassword--}
```
public final String getPassword()
```


पासवर्ड-संरक्षित फ़ाइल खोलने के लिए पासवर्ड।

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


टेक्स्ट-आधारित फ़ाइलें जैसे [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) या [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT) खोलते समय उपयोग किया गया एन्कोडिंग। डिफ़ॉल्ट मान है System.Text.Encoding.Default (java.nio.charset.Charset).

**Returns:**
java.nio.charset.Charset
