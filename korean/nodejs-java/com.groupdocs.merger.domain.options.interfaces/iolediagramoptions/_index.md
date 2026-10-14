---
title: "IOleDiagramOptions"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "OLE를 통한 임베디드 문서를 다이어그램으로 가져오기 옵션을 위한 인터페이스."
type: docs
weight: 17
url: /ko/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleDiagramOptions extends IImportDocumentOptions, ISizeOptions
```

OLE를 통한 임베디드 문서를 다이어그램으로 가져오기 옵션을 위한 인터페이스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getX()](#getX--) | 페이지와 관련된 임베디드 객체 형태의 핀(회전 중심)의 X 좌표. |
| [setX(int value)](#setX-int-) | 페이지와 관련된 임베디드 객체 형태의 핀(회전 중심)의 X 좌표. |
| [getY()](#getY--) | 페이지와 관련된 임베디드 객체 형태의 핀(회전 중심)의 Y 좌표. |
| [setY(int value)](#setY-int-) | 페이지와 관련된 임베디드 객체 형태의 핀(회전 중심)의 Y 좌표. |
| [getImageData()](#getImageData--) | 임베디드 객체의 이미지 데이터. |
### getX() {#getX--}
```
public abstract int getX()
```


페이지와 관련된 임베디드 객체 형태의 핀(회전 중심)의 X 좌표.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


페이지와 관련된 임베디드 객체 형태의 핀(회전 중심)의 X 좌표.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


페이지와 관련된 임베디드 객체 형태의 핀(회전 중심)의 Y 좌표.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


페이지와 관련된 임베디드 객체 형태의 핀(회전 중심)의 Y 좌표.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


임베디드 객체의 이미지 데이터.

**Returns:**
byte[]
