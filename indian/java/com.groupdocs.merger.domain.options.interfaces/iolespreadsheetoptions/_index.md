---
title: "IOleSpreadsheetOptions"
second_title: "GroupDocs.Merger के लिए Java API संदर्भ"
description: "OLE के माध्यम से स्प्रेडशीट में एम्बेडेड दस्तावेज़ के आयात विकल्पों के लिए इंटरफ़ेस।"
type: docs
weight: 19
url: /hi/java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleSpreadsheetOptions extends IImportDocumentOptions, ISizeOptions
```

OLE के माध्यम से स्प्रेडशीट में एम्बेडेड दस्तावेज़ के आयात विकल्पों के लिए इंटरफ़ेस।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | ऊपरी बाएँ पंक्ति सूचकांक। |
| [setRowIndex(int value)](#setRowIndex-int-) | ऊपरी बाएँ पंक्ति सूचकांक। |
| [getColumnIndex()](#getColumnIndex--) | ऊपरी बाएँ स्तंभ सूचकांक। |
| [setColumnIndex(int value)](#setColumnIndex-int-) | ऊपरी बाएँ स्तंभ सूचकांक। |
| [getImageData()](#getImageData--) | Ole ऑब्जेक्ट छवि का डेटा। |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


ऊपरी बाएँ पंक्ति सूचकांक।

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


ऊपरी बाएँ पंक्ति सूचकांक।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


ऊपरी बाएँ स्तंभ सूचकांक।

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


ऊपरी बाएँ स्तंभ सूचकांक।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Ole ऑब्जेक्ट छवि का डेटा।

**Returns:**
byte[]
