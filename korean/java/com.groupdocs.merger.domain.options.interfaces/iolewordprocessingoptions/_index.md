---
title: "IOleWordProcessingOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "OLE를 통해 임베디드 문서를 워드 프로세싱으로 가져오는 옵션을 위한 인터페이스."
type: docs
weight: 20
url: /ko/java/com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleWordProcessingOptions extends IImportDocumentOptions, ISizeOptions
```

OLE를 통해 임베디드 문서를 워드 프로세싱으로 가져오는 옵션을 위한 인터페이스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLeft()](#getLeft--) | Ole 객체 이미지의 왼쪽 좌표. |
| [setLeft(int value)](#setLeft-int-) | Ole 객체 이미지의 왼쪽 좌표. |
| [getTop()](#getTop--) | Ole 객체 이미지의 위쪽 좌표. |
| [setTop(int value)](#setTop-int-) | Ole 객체 이미지의 위쪽 좌표. |
| [getImageData()](#getImageData--) | Ole 객체 이미지 데이터. |
### getLeft() {#getLeft--}
```
public abstract int getLeft()
```


Ole 객체 이미지의 왼쪽 좌표.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public abstract void setLeft(int value)
```


Ole 객체 이미지의 왼쪽 좌표.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getTop() {#getTop--}
```
public abstract int getTop()
```


Ole 객체 이미지의 위쪽 좌표.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public abstract void setTop(int value)
```


Ole 객체 이미지의 위쪽 좌표.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Ole 객체 이미지 데이터.

**Returns:**
byte[]
