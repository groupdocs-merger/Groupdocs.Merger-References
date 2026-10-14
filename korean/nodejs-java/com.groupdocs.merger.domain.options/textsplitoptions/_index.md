---
title: "TextSplitOptions"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "문서 텍스트 분할을 위한 옵션을 제공합니다."
type: docs
weight: 39
url: /ko/nodejs-java/com.groupdocs.merger.domain.options/textsplitoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions)
```
public class TextSplitOptions implements ITextSplitOptions
```

문서 텍스트 분할을 위한 옵션을 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TextSplitOptions(int[] lineNumbers)](#TextSplitOptions-int---) | 새 인스턴스를 초기화합니다 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 클래스. |
| [TextSplitOptions(int mode, int[] lineNumbers)](#TextSplitOptions-int-int---) | 새 인스턴스를 초기화합니다 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 클래스. |
| [TextSplitOptions(String filePathFormat, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int---) | 새 인스턴스를 초기화합니다 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 클래스. |
| [TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int-int---) | 새 인스턴스를 초기화합니다 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 클래스. |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | 새 인스턴스를 초기화합니다 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 클래스. |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---) | 새 인스턴스를 초기화합니다 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getMode()](#getMode--) | 텍스트 분할 모드입니다. |
| [getLineNumbers()](#getLineNumbers--) | 텍스트 분할을 위한 행 번호입니다. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | 분할 옵션을 검증합니다. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | 인덱스로 지정된 확장자를 사용하여 분할된 문서의 전체 파일 경로를 가져옵니다. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory는 출력 페이지 미리보기 스트림을 생성하거나 해제합니다. |
### TextSplitOptions(int[] lineNumbers) {#TextSplitOptions-int---}
```
public TextSplitOptions(int[] lineNumbers)
```


새 인스턴스를 초기화합니다 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| lineNumbers | int[] | 텍스트 분할을 위한 행 번호입니다. |

### TextSplitOptions(int mode, int[] lineNumbers) {#TextSplitOptions-int-int---}
```
public TextSplitOptions(int mode, int[] lineNumbers)
```


새 인스턴스를 초기화합니다 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mode | int | 텍스트 분할 모드입니다. |
| lineNumbers | int[] | 텍스트 분할을 위한 행 번호입니다. |

### TextSplitOptions(String filePathFormat, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int---}
```
public TextSplitOptions(String filePathFormat, int[] lineNumbers)
```


새 인스턴스를 초기화합니다 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 파일 경로 형식 예: 'c:/split\\{0\\}.doc' 또는 'c:/split\\{0\\}.\\{1\\}' (이미 정의된 확장자를 포함). |
| lineNumbers | int[] | 텍스트 분할을 위한 행 번호입니다. |

### TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int-int---}
```
public TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)
```


새 인스턴스를 초기화합니다 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 파일 경로 형식 예: 'c:/split\\{0\\}.doc' 또는 'c:/split\\{0\\}.\\{1\\}' (이미 정의된 확장자를 포함). |
| mode | int | 텍스트 분할 모드입니다. |
| lineNumbers | int[] | 텍스트 분할을 위한 행 번호입니다. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)
```


새 인스턴스를 초기화합니다 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| lineNumbers | int[] | 텍스트 분할을 위한 행 번호입니다. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)
```


새 인스턴스를 초기화합니다 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| mode | int | 텍스트 분할 모드입니다. |
| lineNumbers | int[] | 텍스트 분할을 위한 행 번호입니다. |

### getMode() {#getMode--}
```
public final int getMode()
```


텍스트 분할 모드입니다.

**Returns:**
int
### getLineNumbers() {#getLineNumbers--}
```
public final int[] getLineNumbers()
```


텍스트 분할을 위한 행 번호입니다.

**Returns:**
int[]
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


인덱스로 지정된 확장자를 사용하여 분할된 문서의 전체 파일 경로를 가져옵니다.

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
