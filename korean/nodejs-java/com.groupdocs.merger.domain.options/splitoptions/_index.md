---
title: "SplitOptions"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "문서 페이지 분할을 위한 옵션을 제공합니다."
type: docs
weight: 36
url: /ko/nodejs-java/com.groupdocs.merger.domain.options/splitoptions/
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
| [SplitOptions(int[] pageNumbers, int splitMode)](#SplitOptions-int---int-) | 새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스. |
| [SplitOptions(int splitMode, int startNumber, int endNumber)](#SplitOptions-int-int-int-) | 새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스. |
| [SplitOptions(int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-int-int-int-int-) | 새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스. |
| [SplitOptions(String filePathFormat, int[] pageNumbers)](#SplitOptions-java.lang.String-int---) | 새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스. |
| [SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)](#SplitOptions-java.lang.String-int---int-) | 새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스. |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-) | 새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스. |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-int-) | 새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스. |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)](#SplitOptions-java.lang.String-int-int-java.lang.Integer-) | 새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스. |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-java.lang.String-int-int-int-int-) | 새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스. |
| [SplitOptions(SplitStreamFactory splitStreamFactory)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-) | 새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | 새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-) | 새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-) | 새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-) | 새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-) | 새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-) | 새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getMode()](#getMode--) | 페이지 분할 모드를 가져옵니다. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | 분할 옵션을 검증합니다. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | 인덱스로 분할된 문서의 전체 파일 경로를 미리 정의된 확장자를 사용하여 가져옵니다. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory는 출력 페이지 미리보기 스트림을 생성하거나 해제합니다. |
### SplitOptions(int[] pageNumbers, int splitMode) {#SplitOptions-int---int-}
```
public SplitOptions(int[] pageNumbers, int splitMode)
```


새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageNumbers | int[] | 페이지 번호. |
| splitMode | int | Mode의 분할 모드 (\\#getMode.getMode/\\#setMode(int).setMode(int)). |

### SplitOptions(int splitMode, int startNumber, int endNumber) {#SplitOptions-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber)
```


새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| splitMode | int | Mode의 분할 모드 (\\#getMode.getMode/\\#setMode(int).setMode(int)). |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |

### SplitOptions(int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-int-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber, int mode)
```


새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| splitMode | int | Mode의 분할 모드 (\\#getMode.getMode/\\#setMode(int).setMode(int)). |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |
| mode | int | 범위 모드입니다. |

### SplitOptions(String filePathFormat, int[] pageNumbers) {#SplitOptions-java.lang.String-int---}
```
public SplitOptions(String filePathFormat, int[] pageNumbers)
```


새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 파일 경로 형식 예: 'c:/split\\{0\\}.doc' 또는 'c:/split\\{0\\}.\\{1\\}' (이미 미리 정의된 확장자 포함). |
| pageNumbers | int[] | 페이지 번호. |

### SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode) {#SplitOptions-java.lang.String-int---int-}
```
public SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)
```


새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 파일 경로 형식 예: 'c:/split\\{0\\}.doc' 또는 'c:/split\\{0\\}.\\{1\\}' (이미 미리 정의된 확장자 포함). |
| pageNumbers | int[] | 페이지 번호. |
| splitMode | int | Mode의 분할 모드 (\\#getMode.getMode/\\#setMode(int).setMode(int)). |

### SplitOptions(String filePathFormat, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber)
```


새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 파일 경로 형식 예: 'c:/split\\{0\\}.doc' 또는 'c:/split\\{0\\}.\\{1\\}' (이미 미리 정의된 확장자 포함). |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)
```


새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 파일 경로 형식 예: 'c:/split\\{0\\}.doc' 또는 'c:/split\\{0\\}.\\{1\\}' (이미 미리 정의된 확장자 포함). |
| splitMode | int | Mode의 분할 모드 (\\#getMode.getMode/\\#setMode(int).setMode(int)). |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |

### SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode) {#SplitOptions-java.lang.String-int-int-java.lang.Integer-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)
```


새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 파일 경로 형식 예: 'c:/split\\{0\\}.doc' 또는 'c:/split\\{0\\}.\\{1\\}' (이미 미리 정의된 확장자 포함). |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |
| mode | java.lang.Integer | 범위 모드입니다. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-java.lang.String-int-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)
```


새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 파일 경로 형식 예: 'c:/split\\{0\\}.doc' 또는 'c:/split\\{0\\}.\\{1\\}' (이미 미리 정의된 확장자 포함). |
| splitMode | int | Mode의 분할 모드 (\\#getMode.getMode/\\#setMode(int).setMode(int)). |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |
| mode | int | 범위 모드입니다. |

### SplitOptions(SplitStreamFactory splitStreamFactory) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory)
```


새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)
```


새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| pageNumbers | int[] | 페이지 번호. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)
```


새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| pageNumbers | int[] | 페이지 번호. |
| splitMode | int | Mode의 분할 모드 (\\#getMode.getMode/\\#setMode(int).setMode(int)). |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)
```


새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)
```


새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| splitMode | int | Mode의 분할 모드 (\\#getMode.getMode/\\#setMode(int).setMode(int)). |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)
```


새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |
| mode | java.lang.Integer | 범위 모드입니다. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)
```


새 인스턴스를 초기화합니다 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| splitMode | int | Mode의 분할 모드 (\\#getMode.getMode/\\#setMode(int).setMode(int)). |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |
| mode | int | 범위 모드입니다. |

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | [FileType](../../com.groupdocs.merger.domain/filetype) 클래스의 파일 유형. |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


인덱스로 분할된 문서의 전체 파일 경로를 미리 정의된 확장자를 사용하여 가져옵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 인덱스 | int | 분할된 문서의 인덱스. |
| 확장자 | java.lang.String | 파일의 확장자. |

**Returns:**
java.lang.String - 전체 파일 경로.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


SplitStreamFactory는 출력 페이지 미리보기 스트림을 생성하거나 해제합니다.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
