---
title: "SplitOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "문서 페이지 분할을 위한 옵션을 제공합니다."
type: docs
weight: 38
url: /ko/java/com.groupdocs.merger.domain.options/splitoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions)
```
public class SplitOptions extends PageOptions implements ISplitOptions
```

문서 페이지 분할을 위한 옵션을 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SplitOptions(int[] pageNumbers, int splitMode)](#SplitOptions-int---int-) | 새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다. |
| [SplitOptions(int splitMode, int startNumber, int endNumber)](#SplitOptions-int-int-int-) | 새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다. |
| [SplitOptions(int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-int-int-int-int-) | 새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다. |
| [SplitOptions(String filePathFormat, int[] pageNumbers)](#SplitOptions-java.lang.String-int---) | 새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다. |
| [SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)](#SplitOptions-java.lang.String-int---int-) | 새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다. |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-) | 새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다. |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-int-) | 새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다. |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)](#SplitOptions-java.lang.String-int-int-java.lang.Integer-) | 새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다. |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-java.lang.String-int-int-int-int-) | 새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다. |
| [SplitOptions(SplitStreamFactory splitStreamFactory)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-) | 새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | 새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-) | 새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-) | 새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-) | 새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-) | 새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-) | 새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getMode()](#getMode--) | 페이지 분할 모드를 가져옵니다. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | 분할 옵션을 검증합니다. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | 인덱스로 분할된 문서의 전체 파일 경로를 미리 정의된 확장자로 가져옵니다. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory는 출력 페이지 미리보기 스트림을 생성하거나 해제합니다. |
### SplitOptions(int[] pageNumbers, int splitMode) {#SplitOptions-int---int-}
```
public SplitOptions(int[] pageNumbers, int splitMode)
```


새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pageNumbers | int[] | 페이지 번호. |
| splitMode | int | Mode(\#getMode.getMode/\#setMode(int).setMode(int))의 분할 모드. |

### SplitOptions(int splitMode, int startNumber, int endNumber) {#SplitOptions-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber)
```


새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| splitMode | int | Mode(\#getMode.getMode/\#setMode(int).setMode(int))의 분할 모드. |
| startNumber | int | 시작 페이지 번호. |
| endNumber | int | 끝 페이지 번호. |

### SplitOptions(int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-int-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber, int mode)
```


새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| splitMode | int | Mode(\#getMode.getMode/\#setMode(int).setMode(int))의 분할 모드. |
| startNumber | int | 시작 페이지 번호. |
| endNumber | int | 끝 페이지 번호. |
| mode | int | 범위 모드. |

### SplitOptions(String filePathFormat, int[] pageNumbers) {#SplitOptions-java.lang.String-int---}
```
public SplitOptions(String filePathFormat, int[] pageNumbers)
```


새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 파일 경로 형식 예: 'c:/split\{0\}.doc' 또는 'c:/split\{0\}.\{1\}' (이미 미리 정의된 확장자 포함). |
| pageNumbers | int[] | 페이지 번호. |

### SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode) {#SplitOptions-java.lang.String-int---int-}
```
public SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)
```


새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 파일 경로 형식 예: 'c:/split\{0\}.doc' 또는 'c:/split\{0\}.\{1\}' (이미 미리 정의된 확장자 포함). |
| pageNumbers | int[] | 페이지 번호. |
| splitMode | int | Mode(\#getMode.getMode/\#setMode(int).setMode(int))의 분할 모드. |

### SplitOptions(String filePathFormat, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber)
```


새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 파일 경로 형식 예: 'c:/split\{0\}.doc' 또는 'c:/split\{0\}.\{1\}' (이미 미리 정의된 확장자 포함). |
| startNumber | int | 시작 페이지 번호. |
| endNumber | int | 끝 페이지 번호. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)
```


새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 파일 경로 형식 예: 'c:/split\{0\}.doc' 또는 'c:/split\{0\}.\{1\}' (이미 미리 정의된 확장자 포함). |
| splitMode | int | Mode(\#getMode.getMode/\#setMode(int).setMode(int))의 분할 모드. |
| startNumber | int | 시작 페이지 번호. |
| endNumber | int | 끝 페이지 번호. |

### SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode) {#SplitOptions-java.lang.String-int-int-java.lang.Integer-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)
```


새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 파일 경로 형식 예: 'c:/split\{0\}.doc' 또는 'c:/split\{0\}.\{1\}' (이미 미리 정의된 확장자 포함). |
| startNumber | int | 시작 페이지 번호. |
| endNumber | int | 끝 페이지 번호. |
| mode | java.lang.Integer | 범위 모드. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-java.lang.String-int-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)
```


새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 파일 경로 형식 예: 'c:/split\{0\}.doc' 또는 'c:/split\{0\}.\{1\}' (이미 미리 정의된 확장자 포함). |
| splitMode | int | Mode(\#getMode.getMode/\#setMode(int).setMode(int))의 분할 모드. |
| startNumber | int | 시작 페이지 번호. |
| endNumber | int | 끝 페이지 번호. |
| mode | int | 범위 모드. |

### SplitOptions(SplitStreamFactory splitStreamFactory) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory)
```


새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)
```


새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드. |
| pageNumbers | int[] | 페이지 번호. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)
```


새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드. |
| pageNumbers | int[] | 페이지 번호. |
| splitMode | int | Mode(\#getMode.getMode/\#setMode(int).setMode(int))의 분할 모드. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)
```


새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드. |
| startNumber | int | 시작 페이지 번호. |
| endNumber | int | 끝 페이지 번호. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)
```


새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드. |
| splitMode | int | Mode(\#getMode.getMode/\#setMode(int).setMode(int))의 분할 모드. |
| startNumber | int | 시작 페이지 번호. |
| endNumber | int | 끝 페이지 번호. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)
```


새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드. |
| startNumber | int | 시작 페이지 번호. |
| endNumber | int | 끝 페이지 번호. |
| mode | java.lang.Integer | 범위 모드. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)
```


새로운 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드. |
| splitMode | int | Mode(\#getMode.getMode/\#setMode(int).setMode(int))의 분할 모드. |
| startNumber | int | 시작 페이지 번호. |
| endNumber | int | 끝 페이지 번호. |
| mode | int | 범위 모드. |

### getMode() {#getMode--}
```
public final int getMode()
```


페이지 분할 모드를 가져옵니다.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


분할 옵션을 검증합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 클래스 [FileType](../../com.groupdocs.merger.domain/filetype)의 파일 유형입니다. |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


인덱스로 분할된 문서의 전체 파일 경로를 미리 정의된 확장자로 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int | 분할된 문서의 인덱스입니다. |
| 확장자 | java.lang.String | 파일의 확장자입니다. |

**Returns:**
java.lang.String - 전체 파일 경로입니다.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


SplitStreamFactory는 출력 페이지 미리보기 스트림을 생성하거나 해제합니다.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
