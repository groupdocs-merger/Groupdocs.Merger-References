---
title: "MoveOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "문서 페이지 이동을 위한 옵션을 제공합니다."
type: docs
weight: 17
url: /ko/java/com.groupdocs.merger.domain.options/moveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions)
```
public class MoveOptions implements IMoveOptions
```

문서 페이지 이동을 위한 옵션을 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MoveOptions(int pageNumberToMove, int newPageNumber)](#MoveOptions-int-int-) | 새 인스턴스를 초기화합니다 [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPageNumberToMove()](#getPageNumberToMove--) | 이동할 페이지 번호를 가져오거나 설정합니다. |
| [getNewPageNumber()](#getNewPageNumber--) | 새 페이지 번호를 가져오거나 설정합니다. |
### MoveOptions(int pageNumberToMove, int newPageNumber) {#MoveOptions-int-int-}
```
public MoveOptions(int pageNumberToMove, int newPageNumber)
```


새 인스턴스를 초기화합니다 [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pageNumberToMove | int | 이동할 페이지 번호. |
| newPageNumber | int | 새 페이지 번호. |

### getPageNumberToMove() {#getPageNumberToMove--}
```
public final int getPageNumberToMove()
```


이동할 페이지 번호를 가져오거나 설정합니다.

값: 이동할 페이지 번호.

**Returns:**
int
### getNewPageNumber() {#getNewPageNumber--}
```
public final int getNewPageNumber()
```


새 페이지 번호를 가져오거나 설정합니다.

값: 새 페이지 번호.

**Returns:**
int
