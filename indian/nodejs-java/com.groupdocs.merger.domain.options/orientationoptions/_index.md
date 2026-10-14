---
title: "OrientationOptions"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "पृष्ठ अभिविन्यास के विकल्प प्रदान करता है।"
type: docs
weight: 23
url: /hi/nodejs-java/com.groupdocs.merger.domain.options/orientationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions)
```
public class OrientationOptions extends PageOptions implements IOrientationOptions
```

पृष्ठ अभिविन्यास के विकल्प प्रदान करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [OrientationOptions(int orientationMode)](#OrientationOptions-int-) | एक नया उदाहरण प्रारंभ करता है [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) क्लास का। |
| [OrientationOptions(int orientationMode, int[] pageNumbers)](#OrientationOptions-int-int---) | एक नया उदाहरण प्रारंभ करता है [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) क्लास का। |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber)](#OrientationOptions-int-int-int-) | एक नया उदाहरण प्रारंभ करता है [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) क्लास का। |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)](#OrientationOptions-int-int-int-int-) | एक नया उदाहरण प्रारंभ करता है [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getMode()](#getMode--) | पृष्ठ अभिविन्यास के लिए मोड प्राप्त करता है। |
### OrientationOptions(int orientationMode) {#OrientationOptions-int-}
```
public OrientationOptions(int orientationMode)
```


एक नया उदाहरण प्रारंभ करता है [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) का अभिविन्यास मोड। |

### OrientationOptions(int orientationMode, int[] pageNumbers) {#OrientationOptions-int-int---}
```
public OrientationOptions(int orientationMode, int[] pageNumbers)
```


एक नया उदाहरण प्रारंभ करता है [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) का अभिविन्यास मोड। |
| pageNumbers | int[] | पृष्ठ संख्याएँ। |

### OrientationOptions(int orientationMode, int startNumber, int endNumber) {#OrientationOptions-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber)
```


एक नया उदाहरण प्रारंभ करता है [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) का अभिविन्यास मोड। |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |

### OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode) {#OrientationOptions-int-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)
```


एक नया उदाहरण प्रारंभ करता है [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) का अभिविन्यास मोड। |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |
| mode | int | रेंज मोड। |

### getMode() {#getMode--}
```
public final int getMode()
```


पृष्ठ अभिविन्यास के लिए मोड प्राप्त करता है।

**Returns:**
int
