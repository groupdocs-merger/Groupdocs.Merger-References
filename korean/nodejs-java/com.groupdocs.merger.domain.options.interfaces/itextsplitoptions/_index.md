---
title: "ITextSplitOptions"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "텍스트 분할 옵션을 위한 인터페이스."
type: docs
weight: 35
url: /ko/nodejs-java/com.groupdocs.merger.domain.options.interfaces/itextsplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ITextSplitOptions extends IOptions
```

텍스트 분할 옵션을 위한 인터페이스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLineNumbers()](#getLineNumbers--) | 텍스트 분할을 위한 행 번호입니다. |
| [getMode()](#getMode--) | 텍스트 분할 모드입니다. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | 분할 옵션을 검증합니다. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | 인덱스로 지정된 확장자를 사용하여 분할된 문서의 전체 파일 경로를 가져옵니다. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | 출력 분할 스트림을 생성하는 메서드를 정의하는 대리자. |
### getLineNumbers() {#getLineNumbers--}
```
public abstract int[] getLineNumbers()
```


텍스트 분할을 위한 행 번호입니다.

**Returns:**
int[]
### getMode() {#getMode--}
```
public abstract int getMode()
```


텍스트 분할 모드입니다.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


분할 옵션을 검증합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | [FileType](../../com.groupdocs.merger.domain/filetype) 클래스의 파일 유형. |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public abstract String getPathByIndex(int index, String extension)
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
public abstract SplitStreamFactory getSplitStreamFactory()
```


출력 분할 스트림을 생성하는 메서드를 정의하는 대리자.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
