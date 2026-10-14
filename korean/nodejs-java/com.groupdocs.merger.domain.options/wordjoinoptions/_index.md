---
title: "WordJoinOptions"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "Word 결합 옵션입니다."
type: docs
weight: 43
url: /ko/nodejs-java/com.groupdocs.merger.domain.options/wordjoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions), [com.groupdocs.merger.domain.options.PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions)
```
public class WordJoinOptions extends PageJoinOptions
```

Word 결합 옵션입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [WordJoinOptions()](#WordJoinOptions--) | 새 인스턴스를 초기화합니다 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 클래스. |
| [WordJoinOptions(int[] pageNumbers)](#WordJoinOptions-int---) | 새 인스턴스를 초기화합니다 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 클래스. |
| [WordJoinOptions(int startNumber, int endNumber)](#WordJoinOptions-int-int-) | 새 인스턴스를 초기화합니다 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 클래스. |
| [WordJoinOptions(int startNumber, int endNumber, int mode)](#WordJoinOptions-int-int-int-) | 새 인스턴스를 초기화합니다 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 클래스. |
| [WordJoinOptions(FileType fileType)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-) | 새 인스턴스를 초기화합니다 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 클래스. |
| [WordJoinOptions(FileType fileType, int[] pageNumbers)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---) | 새 인스턴스를 초기화합니다 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 클래스. |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | 새 인스턴스를 초기화합니다 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 클래스. |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | 새 인스턴스를 초기화합니다 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getMode()](#getMode--) | Word 결합 모드. |
| [setMode(int value)](#setMode-int-) | Word 결합 모드. |
| [getCompliance()](#getCompliance--) | Word Ooxml 형식에 대한 호환 모드 |
| [setCompliance(int value)](#setCompliance-int-) | Word Ooxml 형식에 대한 호환 모드 |
### WordJoinOptions() {#WordJoinOptions--}
```
public WordJoinOptions()
```


새 인스턴스를 초기화합니다 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 클래스.

### WordJoinOptions(int[] pageNumbers) {#WordJoinOptions-int---}
```
public WordJoinOptions(int[] pageNumbers)
```


새 인스턴스를 초기화합니다 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageNumbers | int[] | 페이지 번호. |

### WordJoinOptions(int startNumber, int endNumber) {#WordJoinOptions-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber)
```


새 인스턴스를 초기화합니다 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |

### WordJoinOptions(int startNumber, int endNumber, int mode) {#WordJoinOptions-int-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber, int mode)
```


새 인스턴스를 초기화합니다 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |
| mode | int | 범위 모드입니다. |

### WordJoinOptions(FileType fileType) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public WordJoinOptions(FileType fileType)
```


새 인스턴스를 초기화합니다 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 병합할 파일의 유형. |

### WordJoinOptions(FileType fileType, int[] pageNumbers) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public WordJoinOptions(FileType fileType, int[] pageNumbers)
```


새 인스턴스를 초기화합니다 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 병합할 파일의 유형. |
| pageNumbers | int[] | 페이지 번호. |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber)
```


새 인스턴스를 초기화합니다 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 병합할 파일의 유형. |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


새 인스턴스를 초기화합니다 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 병합할 파일의 유형. |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |
| mode | int | 범위 모드입니다. |

### getMode() {#getMode--}
```
public final int getMode()
```


Word 결합 모드.

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Word 결합 모드.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Word Ooxml 형식에 대한 호환 모드

**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Word Ooxml 형식에 대한 호환 모드

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

