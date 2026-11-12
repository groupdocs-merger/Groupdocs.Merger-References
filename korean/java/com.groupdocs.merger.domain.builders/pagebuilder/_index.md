---
title: "PageBuilder"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "문서에서 페이지 컬렉션을 가져오기 위한 PageInfo 빌더."
type: docs
weight: 10
url: /ko/java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

문서에서 페이지 컬렉션을 가져오기 위한 PageInfo 빌더.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | 새로운 [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) 클래스의 인스턴스를 초기화합니다. |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | 새로운 [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) 클래스의 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getOptions()](#getOptions--) | 페이지 빌더 옵션. |
| [getPages()](#getPages--) | 페이지 컬렉션. |
| [getDocuments()](#getDocuments--) | 문서 컬렉션. |
| [addDocument(int index, InputStream stream, FileType fileType, String password)](#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | 문서를 문서 컬렉션에 추가합니다. |
| [addDocument(DocumentInfo document)](#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | 문서를 문서 컬렉션에 추가합니다. |
| [addPage(int documentIndex, int pageNumber)](#addPage-int-int-) | 페이지를 페이지 컬렉션에 추가합니다. |
| [addPage(IPageInfo page)](#addPage-com.groupdocs.merger.domain.result.IPageInfo-) | 페이지를 페이지 컬렉션에 추가합니다. |
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | 여러 페이지를 페이지 컬렉션에 추가합니다. |
| [clear()](#clear--) | 내부 컬렉션을 정리합니다. |
### PageBuilder() {#PageBuilder--}
```
public PageBuilder()
```


새로운 [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) 클래스의 인스턴스를 초기화합니다.

### PageBuilder(PageBuilderOptions options) {#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public PageBuilder(PageBuilderOptions options)
```


새로운 [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) 클래스의 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) | 페이지 빌더 옵션. |

### getOptions() {#getOptions--}
```
public final PageBuilderOptions getOptions()
```


페이지 빌더 옵션.

**Returns:**
[PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions)
### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


페이지 컬렉션.

**Returns:**
java.util.List<com.groupdocs.merger.domain.result.PageInfo>
### getDocuments() {#getDocuments--}
```
public final Map<Integer,DocumentInfo> getDocuments()
```


문서 컬렉션.

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.merger.domain.result.DocumentInfo>
### addDocument(int index, InputStream stream, FileType fileType, String password) {#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public final void addDocument(int index, InputStream stream, FileType fileType, String password)
```


문서를 문서 컬렉션에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int | DocumentInfo 인덱스. |
| 스트림 | java.io.InputStream | DocumentInfo 스트림. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | DocumentInfo 유형. |
| 비밀번호 | java.lang.String | DocumentInfo 비밀번호. |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


문서를 문서 컬렉션에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | DocumentInfo 인스턴스. |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


페이지를 페이지 컬렉션에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| documentIndex | int | DocumentInfo 인덱스. |
| pageNumber | int | PageInfo 번호. |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


페이지를 페이지 컬렉션에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | PageInfo 인스턴스. |

### addPageRange(IPageInfo[] pages) {#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---}
```
public final void addPageRange(IPageInfo[] pages)
```


여러 페이지를 페이지 컬렉션에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Pages 배열. |

### clear() {#clear--}
```
public final void clear()
```


내부 컬렉션을 정리합니다.

