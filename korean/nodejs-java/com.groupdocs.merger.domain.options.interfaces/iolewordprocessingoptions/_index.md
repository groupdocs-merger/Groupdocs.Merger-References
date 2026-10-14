---
title: "IOleWordProcessingOptions"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "OLE를 통한 임베디드 문서를 워드 프로세싱으로 가져오기 옵션을 위한 인터페이스."
type: docs
weight: 20
url: /ko/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleWordProcessingOptions extends IImportDocumentOptions, ISizeOptions
```

OLE를 통한 임베디드 문서를 워드 프로세싱으로 가져오기 옵션을 위한 인터페이스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLeft()](#getLeft--) | Ole 객체 이미지의 왼쪽 좌표. |
| [setLeft(int value)](#setLeft-int-) | Ole 객체 이미지의 왼쪽 좌표. |
| [getTop()](#getTop--) | Ole 객체 이미지의 상단 좌표. |
| [setTop(int value)](#setTop-int-) | Ole 객체 이미지의 상단 좌표. |
| [getImageData()](#getImageData--) | Ole 객체 이미지의 데이터입니다. |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public abstract int getTop()
```


Ole 객체 이미지의 상단 좌표.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public abstract void setTop(int value)
```


Ole 객체 이미지의 상단 좌표.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Ole 객체 이미지의 데이터입니다.

**Returns:**
byte[]
