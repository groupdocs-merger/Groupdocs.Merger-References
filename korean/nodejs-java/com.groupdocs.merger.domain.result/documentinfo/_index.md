---
title: "DocumentInfo"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "문서 설명 속성을 정의합니다."
type: docs
weight: 10
url: /ko/nodejs-java/com.groupdocs.merger.domain.result/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IDocumentInfo](../../com.groupdocs.merger.domain.result/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

문서 설명 속성을 정의합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | 새로운 [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) 클래스 인스턴스를 초기화합니다. |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-) | 새로운 [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) 클래스 인스턴스를 초기화합니다. |
| [DocumentInfo(FileType fileType, IPageInfo[] pages, long size)](#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-) | 새로운 [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getIndex()](#getIndex--) | 문서 인덱스. |
| [getStream()](#getStream--) | 문서 스트림. |
| [getPassword()](#getPassword--) | 문서 비밀번호. |
| [getType()](#getType--) | 파일 유형을 가져옵니다. |
| [getPages()](#getPages--) | 문서 페이지 컬렉션을 정의합니다. |
| [getPageCount()](#getPageCount--) | 문서 페이지 수. |
| [getSize()](#getSize--) | 바이트 단위 문서 크기 |
| [toString()](#toString--) | 현재 객체를 나타내는 문자열을 반환합니다. |
### DocumentInfo(int index, InputStream stream, FileType fileType, String password) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password)
```


새로운 [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 인덱스 | int |  |
| 스트림 | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 파일 유형입니다. |
| 비밀번호 | java.lang.String |  |

### DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)
```


새로운 [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 인덱스 | int |  |
| 스트림 | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 파일 유형입니다. |
| 비밀번호 | java.lang.String |  |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | 볼 페이지 목록. |
| 크기 | long | 파일 크기. |

### DocumentInfo(FileType fileType, IPageInfo[] pages, long size) {#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```


새로운 [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 파일 유형입니다. |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | 볼 페이지 목록. |
| 크기 | long | 파일 크기. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


문서 인덱스.

**Returns:**
int
### getStream() {#getStream--}
```
public final InputStream getStream()
```


문서 스트림.

**Returns:**
java.io.InputStream
### getPassword() {#getPassword--}
```
public final String getPassword()
```


문서 비밀번호.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final FileType getType()
```


파일 유형을 가져옵니다.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPages() {#getPages--}
```
public final IPageInfo[] getPages()
```


문서 페이지 컬렉션을 정의합니다.

**Returns:**
com.groupdocs.merger.domain.result.IPageInfo[]
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


문서 페이지 수.

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


바이트 단위 문서 크기

**Returns:**
long
### toString() {#toString--}
```
public String toString()
```


현재 객체를 나타내는 문자열을 반환합니다.

**Returns:**
java.lang.String - 현재 객체를 나타내는 문자열입니다.
