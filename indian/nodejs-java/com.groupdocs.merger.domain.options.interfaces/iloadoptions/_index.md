---
title: "ILoadOptions"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "दस्तावेज़ लोड करने के विकल्पों के लिए इंटरफ़ेस।"
type: docs
weight: 15
url: /hi/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iloadoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ILoadOptions extends IOptions
```

दस्तावेज़ लोड करने के विकल्पों के लिए इंटरफ़ेस।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getType()](#getType--) | खोलने के लिए फ़ाइल का प्रकार। |
| [getPassword()](#getPassword--) | पासवर्ड-संरक्षित फ़ाइल खोलने के लिए पासवर्ड। |
| [getExtension()](#getExtension--) | खोलने के लिए फ़ाइल का एक्सटेंशन। |
| [getEncoding()](#getEncoding--) | टेक्स्ट-आधारित फ़ाइलों को खोलते समय उपयोग किया जाने वाला एन्कोडिंग, जैसे [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) या [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### getType() {#getType--}
```
public abstract FileType getType()
```


खोलने के लिए फ़ाइल का प्रकार।

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


पासवर्ड-संरक्षित फ़ाइल खोलने के लिए पासवर्ड।

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


खोलने के लिए फ़ाइल का एक्सटेंशन।

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public abstract Charset getEncoding()
```


टेक्स्ट-आधारित फ़ाइलों को खोलते समय उपयोग किया जाने वाला एन्कोडिंग, जैसे [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) या [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). डिफ़ॉल्ट मान है [DefaultCharset][].


[DefaultCharset]: https://docs.oracle.com/javase/7/docs/api/java/nio/charset/Charset.html#defaultCharset%28%29

**Returns:**
java.nio.charset.Charset
