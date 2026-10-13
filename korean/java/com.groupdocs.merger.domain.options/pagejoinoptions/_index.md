---
title: "PageJoinOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "문서 병합을 위한 옵션을 제공합니다."
type: docs
weight: 25
url: /ko/java/com.groupdocs.merger.domain.options/pagejoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions)
```
public class PageJoinOptions extends PageOptions implements IPageJoinOptions
```

문서 병합을 위한 옵션을 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PageJoinOptions()](#PageJoinOptions--) | 새 인스턴스를 초기화합니다 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 클래스. |
| [PageJoinOptions(int[] pageNumbers)](#PageJoinOptions-int---) | 새 인스턴스를 초기화합니다 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 클래스. |
| [PageJoinOptions(int startNumber, int endNumber)](#PageJoinOptions-int-int-) | 새 인스턴스를 초기화합니다 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 클래스. |
| [PageJoinOptions(int startNumber, int endNumber, int mode)](#PageJoinOptions-int-int-int-) | 새 인스턴스를 초기화합니다 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 클래스. |
| [PageJoinOptions(FileType fileType)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-) | 새 인스턴스를 초기화합니다 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 클래스. |
| [PageJoinOptions(FileType fileType, int[] pageNumbers)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---) | 새 인스턴스를 초기화합니다 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 클래스. |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | 새 인스턴스를 초기화합니다 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 클래스. |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | 새 인스턴스를 초기화합니다 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getType()](#getType--) | 결합할 파일 유형입니다. |
### PageJoinOptions() {#PageJoinOptions--}
```
public PageJoinOptions()
```


새 인스턴스를 초기화합니다 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 클래스.

### PageJoinOptions(int[] pageNumbers) {#PageJoinOptions-int---}
```
public PageJoinOptions(int[] pageNumbers)
```


새 인스턴스를 초기화합니다 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pageNumbers | int[] | 페이지 번호. |

### PageJoinOptions(int startNumber, int endNumber) {#PageJoinOptions-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber)
```


새 인스턴스를 초기화합니다 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startNumber | int | 시작 페이지 번호. |
| endNumber | int | 끝 페이지 번호. |

### PageJoinOptions(int startNumber, int endNumber, int mode) {#PageJoinOptions-int-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber, int mode)
```


새 인스턴스를 초기화합니다 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startNumber | int | 시작 페이지 번호. |
| endNumber | int | 끝 페이지 번호. |
| mode | int | 범위 모드. |

### PageJoinOptions(FileType fileType) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public PageJoinOptions(FileType fileType)
```


새 인스턴스를 초기화합니다 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 결합할 파일 유형입니다. |

### PageJoinOptions(FileType fileType, int[] pageNumbers) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public PageJoinOptions(FileType fileType, int[] pageNumbers)
```


새 인스턴스를 초기화합니다 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 결합할 파일 유형입니다. |
| pageNumbers | int[] | 페이지 번호. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber)
```


새 인스턴스를 초기화합니다 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 결합할 파일 유형입니다. |
| startNumber | int | 시작 페이지 번호. |
| endNumber | int | 끝 페이지 번호. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


새 인스턴스를 초기화합니다 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 결합할 파일 유형입니다. |
| startNumber | int | 시작 페이지 번호. |
| endNumber | int | 끝 페이지 번호. |
| mode | int | 범위 모드. |

### getType() {#getType--}
```
public final FileType getType()
```


결합할 파일 유형입니다.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
