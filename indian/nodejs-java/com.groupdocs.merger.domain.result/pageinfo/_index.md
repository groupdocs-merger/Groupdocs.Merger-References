---
title: "PageInfo"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "पृष्ठ विवरण गुणों को परिभाषित करता है।"
type: docs
weight: 11
url: /hi/nodejs-java/com.groupdocs.merger.domain.result/pageinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo)
```
public class PageInfo implements IPageInfo
```

पृष्ठ विवरण गुणों को परिभाषित करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PageInfo(int number, boolean visible)](#PageInfo-int-boolean-) | नया उदाहरण इनिशियलाइज़ करता है [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) क्लास का। |
| [PageInfo(int number, boolean visible, int width, int height)](#PageInfo-int-boolean-int-int-) | नया उदाहरण इनिशियलाइज़ करता है [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getDocument()](#getDocument--) | दस्तावेज़ की जानकारी प्राप्त करता है। |
| [setDocument(DocumentInfo value)](#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | दस्तावेज़ की जानकारी प्राप्त करता है। |
| [getNumber()](#getNumber--) | पृष्ठ संख्या प्राप्त करता है। |
| [getVisible()](#getVisible--) | यह संकेत देता है कि पृष्ठ दृश्यमान है या नहीं। |
| [getWidth()](#getWidth--) | छवि में परिवर्तित होने पर पृष्ठ की चौड़ाई पिक्सेल में प्राप्त करता है। |
| [getHeight()](#getHeight--) | छवि में परिवर्तित होने पर पृष्ठ की ऊँचाई पिक्सेल में प्राप्त करता है। |
### PageInfo(int number, boolean visible) {#PageInfo-int-boolean-}
```
public PageInfo(int number, boolean visible)
```


नया उदाहरण इनिशियलाइज़ करता है [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संख्या | int | पृष्ठ संख्या। |
| दृश्यमान | boolean | पृष्ठ दृश्यमानता संकेतक। |

### PageInfo(int number, boolean visible, int width, int height) {#PageInfo-int-boolean-int-int-}
```
public PageInfo(int number, boolean visible, int width, int height)
```


नया उदाहरण इनिशियलाइज़ करता है [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संख्या | int | पृष्ठ संख्या। |
| दृश्यमान | boolean | पृष्ठ दृश्यमानता संकेतक। |
| चौड़ाई | int | JPG या PNG के रूप में देखने पर पृष्ठ की चौड़ाई पिक्सेल में। |
| ऊँचाई | int | JPG या PNG के रूप में देखने पर पृष्ठ की ऊँचाई पिक्सेल में। |

### getDocument() {#getDocument--}
```
public final DocumentInfo getDocument()
```


दस्तावेज़ की जानकारी प्राप्त करता है।

**Returns:**
[DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo)
### setDocument(DocumentInfo value) {#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void setDocument(DocumentInfo value)
```


दस्तावेज़ की जानकारी प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) |  |

### getNumber() {#getNumber--}
```
public final int getNumber()
```


पृष्ठ संख्या प्राप्त करता है।

**Returns:**
int
### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


यह संकेत देता है कि पृष्ठ दृश्यमान है या नहीं।

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public final int getWidth()
```


छवि में परिवर्तित होने पर पृष्ठ की चौड़ाई पिक्सेल में प्राप्त करता है।

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


छवि में परिवर्तित होने पर पृष्ठ की ऊँचाई पिक्सेल में प्राप्त करता है।

**Returns:**
int
