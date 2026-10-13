---
title: "IPreviewOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "미리보기 옵션을 위한 인터페이스."
type: docs
weight: 28
url: /ko/java/com.groupdocs.merger.domain.options.interfaces/ipreviewoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface IPreviewOptions extends IPageOptions
```

미리보기 옵션을 위한 인터페이스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getWidth()](#getWidth--) | 미리보기 너비. |
| [setWidth(int value)](#setWidth-int-) | 미리보기 너비. |
| [getHeight()](#getHeight--) | 미리보기 높이. |
| [setHeight(int value)](#setHeight-int-) | 미리보기 높이. |
| [getResolution()](#getResolution--) | 이미지 해상도. |
| [setResolution(int value)](#setResolution-int-) | 이미지 해상도. |
| [getMode()](#getMode--) | 미리보기 모드를 가져옵니다. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | 분할 옵션을 검증합니다. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | 페이지 번호와 정의된 확장자를 사용하여 미리보기 문서의 전체 파일 경로를 가져옵니다. |
| [getPageStreamFactory()](#getPageStreamFactory--) | 출력 페이지 미리보기 스트림을 생성하는 메서드를 정의하는 대리자. |
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


미리보기 너비.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public abstract void setWidth(int value)
```


미리보기 너비.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


미리보기 높이.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public abstract void setHeight(int value)
```


미리보기 높이.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getResolution() {#getResolution--}
```
public abstract int getResolution()
```


이미지 해상도.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public abstract void setResolution(int value)
```


이미지 해상도.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getMode() {#getMode--}
```
public abstract int getMode()
```


미리보기 모드를 가져옵니다.

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

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public abstract String getPathByPageNumber(int pageNumber, String extension)
```


페이지 번호와 정의된 확장자를 사용하여 미리보기 문서의 전체 파일 경로를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pageNumber | int | 미리보기 페이지 번호. |
| 확장자 | java.lang.String | 파일의 확장자입니다. |

**Returns:**
java.lang.String - 전체 파일 경로입니다.
### getPageStreamFactory() {#getPageStreamFactory--}
```
public abstract PageStreamFactory getPageStreamFactory()
```


출력 페이지 미리보기 스트림을 생성하는 메서드를 정의하는 대리자.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
