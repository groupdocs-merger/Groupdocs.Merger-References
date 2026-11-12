---
title: "PageInfo"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "페이지 설명 속성을 정의합니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.merger.domain.result/pageinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo)
```
public class PageInfo implements IPageInfo
```

페이지 설명 속성을 정의합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PageInfo(int number, boolean visible)](#PageInfo-int-boolean-) | 새로운 [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) 클래스 인스턴스를 초기화합니다. |
| [PageInfo(int number, boolean visible, int width, int height)](#PageInfo-int-boolean-int-int-) | 새로운 [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDocument()](#getDocument--) | 문서 정보를 가져옵니다. |
| [setDocument(DocumentInfo value)](#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | 문서 정보를 가져옵니다. |
| [getNumber()](#getNumber--) | 페이지 번호를 가져옵니다. |
| [getVisible()](#getVisible--) | 페이지가 표시되는지 여부를 나타냅니다. |
| [getWidth()](#getWidth--) | 이미지로 변환될 때 페이지 너비를 픽셀 단위로 가져옵니다. |
| [getHeight()](#getHeight--) | 이미지로 변환될 때 페이지 높이를 픽셀 단위로 가져옵니다. |
### PageInfo(int number, boolean visible) {#PageInfo-int-boolean-}
```
public PageInfo(int number, boolean visible)
```


새로운 [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 숫자 | int | 페이지 번호입니다. |
| 표시됨 | boolean | 페이지 표시 여부 표시기입니다. |

### PageInfo(int number, boolean visible, int width, int height) {#PageInfo-int-boolean-int-int-}
```
public PageInfo(int number, boolean visible, int width, int height)
```


새로운 [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 숫자 | int | 페이지 번호입니다. |
| 표시됨 | boolean | 페이지 표시 여부 표시기입니다. |
| 너비 | int | JPG 또는 PNG로 볼 때 페이지의 너비(픽셀)입니다. |
| 높이 | int | JPG 또는 PNG로 볼 때 페이지의 높이(픽셀)입니다. |

### getDocument() {#getDocument--}
```
public final DocumentInfo getDocument()
```


문서 정보를 가져옵니다.

**Returns:**
[DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo)
### setDocument(DocumentInfo value) {#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void setDocument(DocumentInfo value)
```


문서 정보를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) |  |

### getNumber() {#getNumber--}
```
public final int getNumber()
```


페이지 번호를 가져옵니다.

**Returns:**
int
### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


페이지가 표시되는지 여부를 나타냅니다.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public final int getWidth()
```


이미지로 변환될 때 페이지 너비를 픽셀 단위로 가져옵니다.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


이미지로 변환될 때 페이지 높이를 픽셀 단위로 가져옵니다.

**Returns:**
int
