---
title: "RotateOptions"
second_title: "GroupDocs.Merger के लिए Java API संदर्भ"
description: "पृष्ठ घुमाव के विकल्प प्रदान करता है।"
type: docs
weight: 35
url: /hi/java/com.groupdocs.merger.domain.options/rotateoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions)
```
public class RotateOptions extends PageOptions implements IRotateOptions
```

पृष्ठ घुमाव के विकल्प प्रदान करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [RotateOptions(int rotateMode)](#RotateOptions-int-) | नए [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [RotateOptions(int rotateMode, int[] pageNumbers)](#RotateOptions-int-int---) | नए [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [RotateOptions(int rotateMode, int startNumber, int endNumber)](#RotateOptions-int-int-int-) | नए [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)](#RotateOptions-int-int-int-int-) | नए [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) क्लास का एक नया उदाहरण प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getMode()](#getMode--) | घुमाने के मोड को प्राप्त करता है (90, 180 या 270 डिग्री)। |
### RotateOptions(int rotateMode) {#RotateOptions-int-}
```
public RotateOptions(int rotateMode)
```


नए [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| rotateMode | int | Mode का घूर्णन मोड (\#getMode.getMode/\#setMode(int).setMode(int)) |

### RotateOptions(int rotateMode, int[] pageNumbers) {#RotateOptions-int-int---}
```
public RotateOptions(int rotateMode, int[] pageNumbers)
```


नए [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| rotateMode | int | Mode का घूर्णन मोड (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | पृष्ठ संख्याएँ। |

### RotateOptions(int rotateMode, int startNumber, int endNumber) {#RotateOptions-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber)
```


नए [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| rotateMode | int | Mode का घूर्णन मोड (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |

### RotateOptions(int rotateMode, int startNumber, int endNumber, int mode) {#RotateOptions-int-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)
```


नए [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| rotateMode | int | Mode का घूर्णन मोड (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | प्रारंभ पृष्ठ संख्या। |
| endNumber | int | अंत पृष्ठ संख्या। |
| मोड | int | रेंज मोड। |

### getMode() {#getMode--}
```
public final int getMode()
```


घुमाने के मोड को प्राप्त करता है (90, 180 या 270 डिग्री)।

**Returns:**
int
