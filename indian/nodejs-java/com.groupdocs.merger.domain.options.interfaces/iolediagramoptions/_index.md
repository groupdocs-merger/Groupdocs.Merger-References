---
title: "IOleDiagramOptions"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "OLE के माध्यम से डायग्राम में एम्बेडेड दस्तावेज़ के आयात विकल्पों के लिए इंटरफ़ेस।"
type: docs
weight: 17
url: /hi/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleDiagramOptions extends IImportDocumentOptions, ISizeOptions
```

OLE के माध्यम से डायग्राम में एम्बेडेड दस्तावेज़ के आयात विकल्पों के लिए इंटरफ़ेस।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getX()](#getX--) | पृष्ठ के सापेक्ष एम्बेडेड ऑब्जेक्ट आकार के पिन (घूर्णन केंद्र) का X निर्देशांक। |
| [setX(int value)](#setX-int-) | पृष्ठ के सापेक्ष एम्बेडेड ऑब्जेक्ट आकार के पिन (घूर्णन केंद्र) का X निर्देशांक। |
| [getY()](#getY--) | पृष्ठ के सापेक्ष एम्बेडेड ऑब्जेक्ट आकार के पिन (घूर्णन केंद्र) का Y निर्देशांक। |
| [setY(int value)](#setY-int-) | पृष्ठ के सापेक्ष एम्बेडेड ऑब्जेक्ट आकार के पिन (घूर्णन केंद्र) का Y निर्देशांक। |
| [getImageData()](#getImageData--) | एम्बेडेड ऑब्जेक्ट का इमेज डेटा। |
### getX() {#getX--}
```
public abstract int getX()
```


पृष्ठ के सापेक्ष एम्बेडेड ऑब्जेक्ट आकार के पिन (घूर्णन केंद्र) का X निर्देशांक।

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


पृष्ठ के सापेक्ष एम्बेडेड ऑब्जेक्ट आकार के पिन (घूर्णन केंद्र) का X निर्देशांक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


पृष्ठ के सापेक्ष एम्बेडेड ऑब्जेक्ट आकार के पिन (घूर्णन केंद्र) का Y निर्देशांक।

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


पृष्ठ के सापेक्ष एम्बेडेड ऑब्जेक्ट आकार के पिन (घूर्णन केंद्र) का Y निर्देशांक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


एम्बेडेड ऑब्जेक्ट का इमेज डेटा।

**Returns:**
byte[]
