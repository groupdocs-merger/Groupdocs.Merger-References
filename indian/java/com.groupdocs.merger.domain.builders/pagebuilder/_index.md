---
title: "PageBuilder"
second_title: "GroupDocs.Merger के लिए Java API संदर्भ"
description: "दस्तावेज़ों से पृष्ठ संग्रह प्राप्त करने के लिए PageInfo बिल्डर।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

दस्तावेज़ों से पृष्ठ संग्रह प्राप्त करने के लिए PageInfo बिल्डर।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | एक नया उदाहरण प्रारंभ करता है [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) क्लास का। |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | एक नया उदाहरण प्रारंभ करता है [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) क्लास का। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getOptions()](#getOptions--) | पेज बिल्डर विकल्प। |
| [getPages()](#getPages--) | पेज संग्रह। |
| [getDocuments()](#getDocuments--) | डॉक्यूमेंट संग्रह। |
| [addDocument(int index, InputStream stream, FileType fileType, String password)](#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | डॉक्यूमेंट को डॉक्यूमेंट संग्रह में जोड़ें। |
| [addDocument(DocumentInfo document)](#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | डॉक्यूमेंट को डॉक्यूमेंट संग्रह में जोड़ें। |
| [addPage(int documentIndex, int pageNumber)](#addPage-int-int-) | पेज को पेज संग्रह में जोड़ें। |
| [addPage(IPageInfo page)](#addPage-com.groupdocs.merger.domain.result.IPageInfo-) | पेज को पेज संग्रह में जोड़ें। |
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | पेजेज को पेज संग्रह में जोड़ें। |
| [clear()](#clear--) | आंतरिक संग्रह साफ़ करें। |
### PageBuilder() {#PageBuilder--}
```
public PageBuilder()
```


एक नया उदाहरण प्रारंभ करता है [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) क्लास का।

### PageBuilder(PageBuilderOptions options) {#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public PageBuilder(PageBuilderOptions options)
```


एक नया उदाहरण प्रारंभ करता है [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) क्लास का।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) | पेज बिल्डर विकल्प। |

### getOptions() {#getOptions--}
```
public final PageBuilderOptions getOptions()
```


पेज बिल्डर विकल्प।

**Returns:**
[PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions)
### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


पेज संग्रह।

**Returns:**
java.util.List<com.groupdocs.merger.domain.result.PageInfo>
### getDocuments() {#getDocuments--}
```
public final Map<Integer,DocumentInfo> getDocuments()
```


डॉक्यूमेंट संग्रह।

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.merger.domain.result.DocumentInfo>
### addDocument(int index, InputStream stream, FileType fileType, String password) {#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public final void addDocument(int index, InputStream stream, FileType fileType, String password)
```


डॉक्यूमेंट को डॉक्यूमेंट संग्रह में जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| इंडेक्स | int | DocumentInfo इंडेक्स। |
| स्ट्रीम | java.io.InputStream | DocumentInfo स्ट्रीम। |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | DocumentInfo टाइप। |
| पासवर्ड | java.lang.String | DocumentInfo पासवर्ड। |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


डॉक्यूमेंट को डॉक्यूमेंट संग्रह में जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | DocumentInfo इंस्टेंस। |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


पेज को पेज संग्रह में जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| documentIndex | int | DocumentInfo इंडेक्स। |
| pageNumber | int | PageInfo संख्या। |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


पेज को पेज संग्रह में जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | PageInfo इंस्टेंस। |

### addPageRange(IPageInfo[] pages) {#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---}
```
public final void addPageRange(IPageInfo[] pages)
```


पेजेज को पेज संग्रह में जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Pages एरे। |

### clear() {#clear--}
```
public final void clear()
```


आंतरिक संग्रह साफ़ करें।

