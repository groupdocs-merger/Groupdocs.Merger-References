---
title: "IOleWordProcessingOptions"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "OLE के माध्यम से वर्ड प्रोसेसिंग में एम्बेडेड दस्तावेज़ के आयात विकल्पों के लिए इंटरफ़ेस।"
type: docs
weight: 20
url: /hi/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleWordProcessingOptions extends IImportDocumentOptions, ISizeOptions
```

OLE के माध्यम से वर्ड प्रोसेसिंग में एम्बेडेड दस्तावेज़ के आयात विकल्पों के लिए इंटरफ़ेस।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLeft()](#getLeft--) | Ole ऑब्जेक्ट छवि का बायाँ निर्देशांक। |
| [setLeft(int value)](#setLeft-int-) | Ole ऑब्जेक्ट छवि का बायाँ निर्देशांक। |
| [getTop()](#getTop--) | Ole ऑब्जेक्ट छवि का ऊपर का निर्देशांक। |
| [setTop(int value)](#setTop-int-) | Ole ऑब्जेक्ट छवि का ऊपर का निर्देशांक। |
| [getImageData()](#getImageData--) | Ole ऑब्जेक्ट छवि का डेटा। |
### getLeft() {#getLeft--}
```
public abstract int getLeft()
```


Ole ऑब्जेक्ट छवि का बायाँ निर्देशांक।

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public abstract void setLeft(int value)
```


Ole ऑब्जेक्ट छवि का बायाँ निर्देशांक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public abstract int getTop()
```


Ole ऑब्जेक्ट छवि का ऊपर का निर्देशांक।

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public abstract void setTop(int value)
```


Ole ऑब्जेक्ट छवि का ऊपर का निर्देशांक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Ole ऑब्जेक्ट छवि का डेटा।

**Returns:**
byte[]
