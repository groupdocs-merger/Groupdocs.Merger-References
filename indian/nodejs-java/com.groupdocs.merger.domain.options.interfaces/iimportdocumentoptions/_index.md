---
title: "IImportDocumentOptions"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "एम्बेडेड दस्तावेज़ के आयात के लिए इंटरफ़ेस।"
type: docs
weight: 13
url: /hi/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface IImportDocumentOptions extends IOptions
```

एम्बेडेड दस्तावेज़ के आयात के लिए इंटरफ़ेस।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getObjectData()](#getObjectData--) | एम्बेडेड ऑब्जेक्ट का डेटा। |
| [getExtension()](#getExtension--) | एम्बेडेड ऑब्जेक्ट का विस्तार। |
| [getPageNumber()](#getPageNumber--) | एम्बेडेड ऑब्जेक्ट को सम्मिलित करने के लिए पृष्ठ संख्या। |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


एम्बेडेड ऑब्जेक्ट का डेटा।

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


एम्बेडेड ऑब्जेक्ट का विस्तार।

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


एम्बेडेड ऑब्जेक्ट को सम्मिलित करने के लिए पृष्ठ संख्या।

**Returns:**
int
