---
title: "ISplitOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "분할 옵션을 위한 인터페이스."
type: docs
weight: 33
url: /ko/java/com.groupdocs.merger.domain.options.interfaces/isplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface ISplitOptions extends IPageOptions
```

분할 옵션을 위한 인터페이스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getMode()](#getMode--) | 페이지 분할 모드를 가져옵니다. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | 분할 옵션을 검증합니다. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | 인덱스로 지정된 확장자를 사용하여 분할된 문서의 전체 파일 경로를 가져옵니다. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | 출력 분할 스트림을 생성하는 메서드를 정의하는 대리자입니다. |
### getMode() {#getMode--}
```
public abstract int getMode()
```


페이지 분할 모드를 가져옵니다.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


분할 옵션을 검증합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 클래스 [FileType](../../com.groupdocs.merger.domain/filetype)의 파일 유형입니다. |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public abstract String getPathByIndex(int index, String extension)
```


인덱스로 지정된 확장자를 사용하여 분할된 문서의 전체 파일 경로를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int | 분할된 문서의 인덱스입니다. |
| 확장자 | java.lang.String | 파일의 확장자입니다. |

**Returns:**
java.lang.String - 전체 파일 경로입니다.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public abstract SplitStreamFactory getSplitStreamFactory()
```


출력 분할 스트림을 생성하는 메서드를 정의하는 대리자입니다.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
