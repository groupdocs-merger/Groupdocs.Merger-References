---
title: "IMoveOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "페이지 이동 옵션을 위한 인터페이스."
type: docs
weight: 16
url: /ko/java/com.groupdocs.merger.domain.options.interfaces/imoveoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface IMoveOptions extends IOptions
```

페이지 이동 옵션을 위한 인터페이스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPageNumberToMove()](#getPageNumberToMove--) | 이동할 페이지 번호를 가져오거나 설정합니다. |
| [getNewPageNumber()](#getNewPageNumber--) | 새 페이지 번호를 가져오거나 설정합니다. |
### getPageNumberToMove() {#getPageNumberToMove--}
```
public abstract int getPageNumberToMove()
```


이동할 페이지 번호를 가져오거나 설정합니다.

값: 이동할 페이지 번호.

**Returns:**
int
### getNewPageNumber() {#getNewPageNumber--}
```
public abstract int getNewPageNumber()
```


새 페이지 번호를 가져오거나 설정합니다.

값: 새 페이지 번호.

**Returns:**
int
