---
title: "PageBuilder"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "डॉक्यूमेंट्स से पृष्ठ संग्रह प्राप्त करने के लिए PageInfo बिल्डर।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

डॉक्यूमेंट्स से पृष्ठ संग्रह प्राप्त करने के लिए PageInfo बिल्डर।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | एक नया उदाहरण प्रारंभ करता है [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) क्लास का। |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | एक नया उदाहरण प्रारंभ करता है [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getOptions()](#getOptions--) | पेज बिल्डर विकल्प। |
| [getPages()](#getPages--) | पेज संग्रह। |
| [getDocuments()](#getDocuments--) | दस्तावेज़ संग्रह। |
| [addDocument(int index, InputStream stream, FileType fileType, String password)](#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | दस्तावेज़ को दस्तावेज़ संग्रह में जोड़ें। |
| [addDocument(DocumentInfo document)](#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | दस्तावेज़ को दस्तावेज़ संग्रह में जोड़ें। |
| [addPage(int documentIndex, int pageNumber)](#addPage-int-int-) | पेज को पेज संग्रह में जोड़ें। |
| [addPage(IPageInfo page)](#addPage-com.groupdocs.merger.domain.result.IPageInfo-) | पेज को पेज संग्रह में जोड़ें। |
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | पेजों को पेज संग्रह में जोड़ें। |
| [clear()](#clear--) | आंतरिक संग्रहों को साफ़ करें। |
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
| पैरामीटर | प्रकार | विवरण |
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


दस्तावेज़ संग्रह।

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.merger.domain.result.DocumentInfo>
### addDocument(int index, InputStream stream, FileType fileType, String password) {#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public final void addDocument(int index, InputStream stream, FileType fileType, String password)
```


दस्तावेज़ को दस्तावेज़ संग्रह में जोड़ें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| सूचकांक | int | DocumentInfo सूचकांक। |
| स्ट्रीम | java.io.InputStream | DocumentInfo स्ट्रीम। |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | DocumentInfo प्रकार। |
| पासवर्ड | java.lang.String | DocumentInfo पासवर्ड। |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


दस्तावेज़ को दस्तावेज़ संग्रह में जोड़ें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | DocumentInfo उदाहरण। |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


पेज को पेज संग्रह में जोड़ें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| documentIndex | int | DocumentInfo सूचकांक। |
| pageNumber | int | PageInfo संख्या। |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


पेज को पेज संग्रह में जोड़ें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | PageInfo उदाहरण। |

### addPageRange(IPageInfo[] pages) {#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---}
```
public final void addPageRange(IPageInfo[] pages)
```


पेजों को पेज संग्रह में जोड़ें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Pages सरणी। |

### clear() {#clear--}
```
public final void clear()
```


आंतरिक संग्रहों को साफ़ करें।

