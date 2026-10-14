---
title: "PreviewOptions"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "문서 미리보기 옵션을 나타냅니다."
type: docs
weight: 29
url: /ko/nodejs-java/com.groupdocs.merger.domain.options/previewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions)
```
public class PreviewOptions extends PageOptions implements IPreviewOptions
```

문서 미리보기 옵션을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-) | 새 인스턴스를 초기화합니다 [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) 클래스. |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---) | 새 인스턴스를 초기화합니다 [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) 클래스. |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-) | 새 인스턴스를 초기화합니다 [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) 클래스. |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-) | 새 인스턴스를 초기화합니다 [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getWidth()](#getWidth--) | 미리보기 너비. |
| [setWidth(int value)](#setWidth-int-) | 미리보기 너비. |
| [getHeight()](#getHeight--) | 미리보기 높이. |
| [setHeight(int value)](#setHeight-int-) | 미리보기 높이. |
| [getResolution()](#getResolution--) | 이미지 해상도. |
| [setResolution(int value)](#setResolution-int-) | 이미지 해상도. |
| [getMode()](#getMode--) | 미리보기를 위한 모드. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | 미리보기 옵션을 검증합니다. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | 페이지 번호와 정의된 확장자를 사용하여 미리보기된 문서의 전체 파일 경로를 가져옵니다. |
| [getPageStreamFactory()](#getPageStreamFactory--) | 출력 페이지 미리보기 스트림을 생성하거나 해제하기 위한 PageStreamFactory. |
### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)
```


새 인스턴스를 초기화합니다 [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| previewMode | int | Mode의 미리보기 모드 (\#getMode.getMode/\#setMode(int).setMode(int)) |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)
```


새 인스턴스를 초기화합니다 [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| previewMode | int | Mode의 미리보기 모드 (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | 페이지 번호. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)
```


새 인스턴스를 초기화합니다 [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| previewMode | int | Mode의 미리보기 모드 (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)
```


새 인스턴스를 초기화합니다 [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| previewMode | int | Mode의 미리보기 모드 (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |
| mode | int | 범위 모드입니다. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


미리보기 너비.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


미리보기 너비.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


미리보기 높이.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


미리보기 높이.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


이미지 해상도.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


이미지 해상도.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public final int getMode()
```


미리보기를 위한 모드.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


미리보기 옵션을 검증합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 파일 형식입니다. |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public final String getPathByPageNumber(int pageNumber, String extension)
```


페이지 번호와 정의된 확장자를 사용하여 미리보기된 문서의 전체 파일 경로를 가져옵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageNumber | int | 미리보기 페이지 번호. |
| 확장자 | java.lang.String | 파일의 확장자. |

**Returns:**
java.lang.String - 전체 파일 경로.
### getPageStreamFactory() {#getPageStreamFactory--}
```
public PageStreamFactory getPageStreamFactory()
```


출력 페이지 미리보기 스트림을 생성하거나 해제하기 위한 PageStreamFactory.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
