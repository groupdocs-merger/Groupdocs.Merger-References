---
title: "DocumentInfo"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "दस्तावेज़ विवरण गुणों को परिभाषित करता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.merger.domain.result/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IDocumentInfo](../../com.groupdocs.merger.domain.result/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

दस्तावेज़ विवरण गुणों को परिभाषित करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | एक नया उदाहरण प्रारंभ करता है [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) क्लास का। |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-) | एक नया उदाहरण प्रारंभ करता है [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) क्लास का। |
| [DocumentInfo(FileType fileType, IPageInfo[] pages, long size)](#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-) | एक नया उदाहरण प्रारंभ करता है [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getIndex()](#getIndex--) | दस्तावेज़ सूचकांक। |
| [getStream()](#getStream--) | दस्तावेज़ स्ट्रीम। |
| [getPassword()](#getPassword--) | दस्तावेज़ पासवर्ड। |
| [getType()](#getType--) | फ़ाइल प्रकार प्राप्त करता है। |
| [getPages()](#getPages--) | दस्तावेज़ पृष्ठों का संग्रह परिभाषित करता है। |
| [getPageCount()](#getPageCount--) | दस्तावेज़ पृष्ठों की गिनती। |
| [getSize()](#getSize--) | बाइट्स में दस्तावेज़ आकार |
| [toString()](#toString--) | वर्तमान ऑब्जेक्ट को दर्शाने वाली स्ट्रिंग लौटाता है। |
### DocumentInfo(int index, InputStream stream, FileType fileType, String password) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password)
```


एक नया उदाहरण प्रारंभ करता है [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| सूचकांक | int |  |
| स्ट्रीम | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | फ़ाइल का प्रकार। |
| पासवर्ड | java.lang.String |  |

### DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)
```


एक नया उदाहरण प्रारंभ करता है [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| सूचकांक | int |  |
| स्ट्रीम | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | फ़ाइल का प्रकार। |
| पासवर्ड | java.lang.String |  |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | देखने के लिए पृष्ठों की सूची। |
| आकार | long | फ़ाइल का आकार। |

### DocumentInfo(FileType fileType, IPageInfo[] pages, long size) {#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```


एक नया उदाहरण प्रारंभ करता है [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | फ़ाइल का प्रकार। |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | देखने के लिए पृष्ठों की सूची। |
| आकार | long | फ़ाइल का आकार। |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


दस्तावेज़ सूचकांक।

**Returns:**
int
### getStream() {#getStream--}
```
public final InputStream getStream()
```


दस्तावेज़ स्ट्रीम।

**Returns:**
java.io.InputStream
### getPassword() {#getPassword--}
```
public final String getPassword()
```


दस्तावेज़ पासवर्ड।

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final FileType getType()
```


फ़ाइल प्रकार प्राप्त करता है।

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPages() {#getPages--}
```
public final IPageInfo[] getPages()
```


दस्तावेज़ पृष्ठों का संग्रह परिभाषित करता है।

**Returns:**
com.groupdocs.merger.domain.result.IPageInfo[]
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


दस्तावेज़ पृष्ठों की गिनती।

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


बाइट्स में दस्तावेज़ आकार

**Returns:**
long
### toString() {#toString--}
```
public String toString()
```


वर्तमान ऑब्जेक्ट को दर्शाने वाली स्ट्रिंग लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो वर्तमान ऑब्जेक्ट को दर्शाती है।
