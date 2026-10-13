---
title: "SwapOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "문서 페이지 교환을 위한 옵션을 제공합니다."
type: docs
weight: 39
url: /ko/java/com.groupdocs.merger.domain.options/swapoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISwapOptions](../../com.groupdocs.merger.domain.options.interfaces/iswapoptions)
```
public class SwapOptions implements ISwapOptions
```

문서 페이지 교환을 위한 옵션을 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SwapOptions(int firstPageNumber, int secondPageNumber)](#SwapOptions-int-int-) | 새 인스턴스를 초기화합니다 [SwapOptions](../../com.groupdocs.merger.domain.options/swapoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFirstPageNumber()](#getFirstPageNumber--) | 교환할 첫 페이지 번호. |
| [getSecondPageNumber()](#getSecondPageNumber--) | 교환할 두 번째 페이지 번호. |
### SwapOptions(int firstPageNumber, int secondPageNumber) {#SwapOptions-int-int-}
```
public SwapOptions(int firstPageNumber, int secondPageNumber)
```


새 인스턴스를 초기화합니다 [SwapOptions](../../com.groupdocs.merger.domain.options/swapoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| firstPageNumber | int | 첫 번째 페이지 번호. |
| secondPageNumber | int | 두 번째 페이지 번호. |

### getFirstPageNumber() {#getFirstPageNumber--}
```
public final int getFirstPageNumber()
```


교환할 첫 페이지 번호.

**Returns:**
int
### getSecondPageNumber() {#getSecondPageNumber--}
```
public final int getSecondPageNumber()
```


교환할 두 번째 페이지 번호.

**Returns:**
int
