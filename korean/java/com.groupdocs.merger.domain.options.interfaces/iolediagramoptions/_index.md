---
title: "IOleDiagramOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "OLE를 통해 임베디드 문서를 다이어그램으로 가져오는 옵션을 위한 인터페이스."
type: docs
weight: 17
url: /ko/java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleDiagramOptions extends IImportDocumentOptions, ISizeOptions
```

OLE를 통해 임베디드 문서를 다이어그램으로 가져오는 옵션을 위한 인터페이스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getX()](#getX--) | 페이지와 관련된 삽입된 객체 모양 핀(회전 중심)의 X 좌표입니다. |
| [setX(int value)](#setX-int-) | 페이지와 관련된 삽입된 객체 모양 핀(회전 중심)의 X 좌표입니다. |
| [getY()](#getY--) | 페이지와 관련된 삽입된 객체 모양 핀(회전 중심)의 Y 좌표입니다. |
| [setY(int value)](#setY-int-) | 페이지와 관련된 삽입된 객체 모양 핀(회전 중심)의 Y 좌표입니다. |
| [getImageData()](#getImageData--) | 삽입된 객체의 이미지 데이터입니다. |
### getX() {#getX--}
```
public abstract int getX()
```


페이지와 관련된 삽입된 객체 모양 핀(회전 중심)의 X 좌표입니다.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


페이지와 관련된 삽입된 객체 모양 핀(회전 중심)의 X 좌표입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


페이지와 관련된 삽입된 객체 모양 핀(회전 중심)의 Y 좌표입니다.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


페이지와 관련된 삽입된 객체 모양 핀(회전 중심)의 Y 좌표입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


삽입된 객체의 이미지 데이터입니다.

**Returns:**
byte[]
