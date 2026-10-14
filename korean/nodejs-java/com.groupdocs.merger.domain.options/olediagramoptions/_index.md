---
title: "OleDiagramOptions"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "OLE를 통해 임베디드 문서를 Diagram으로 가져오기 위한 옵션을 제공합니다."
type: docs
weight: 18
url: /ko/nodejs-java/com.groupdocs.merger.domain.options/olediagramoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleDiagramOptions](../../com.groupdocs.merger.domain.options.interfaces/iolediagramoptions)
```
public class OleDiagramOptions extends ImportDocumentOptions implements IOleDiagramOptions
```

OLE를 통해 임베디드 문서를 Diagram으로 가져오기 위한 옵션을 제공합니다.

--------------------

**Learn more**

 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleDiagramOptions-byte---byte---java.lang.String-int-) | 새 인스턴스를 초기화합니다 [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) 클래스. |
| [OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)](#OleDiagramOptions-java.lang.String-byte---int-) | 새 인스턴스를 초기화합니다 [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) 클래스. |
| [OleDiagramOptions(String filePath, int pageNumber)](#OleDiagramOptions-java.lang.String-int-) | 새 인스턴스를 초기화합니다 [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getX()](#getX--) | 페이지와 관련된 임베디드 객체 형태의 핀(회전 중심)의 X 좌표. |
| [setX(int value)](#setX-int-) | 페이지와 관련된 임베디드 객체 형태의 핀(회전 중심)의 X 좌표. |
| [getY()](#getY--) | 페이지와 관련된 임베디드 객체 형태의 핀(회전 중심)의 Y 좌표. |
| [setY(int value)](#setY-int-) | 페이지와 관련된 임베디드 객체 형태의 핀(회전 중심)의 Y 좌표. |
| [getWidth()](#getWidth--) | 삽입된 객체 모양의 너비(인치). |
| [setWidth(int value)](#setWidth-int-) | 삽입된 객체 모양의 너비(인치). |
| [getHeight()](#getHeight--) | 삽입된 객체 모양의 높이(인치). |
| [setHeight(int value)](#setHeight-int-) | 삽입된 객체 모양의 높이(인치). |
| [getImageData()](#getImageData--) | 임베디드 객체의 이미지 데이터. |
### OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleDiagramOptions-byte---byte---java.lang.String-int-}
```
public OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


새 인스턴스를 초기화합니다 [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| objectData | byte[] | 임베디드 객체의 데이터. |
| imageData | byte[] | 임베디드 객체의 이미지 데이터. |
| 확장자 | java.lang.String | 임베디드 객체의 확장자. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호입니다. |

### OleDiagramOptions(String filePath, byte[] imageData, int pageNumber) {#OleDiagramOptions-java.lang.String-byte---int-}
```
public OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)
```


새 인스턴스를 초기화합니다 [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 임베디드 객체의 파일 경로입니다. |
| imageData | byte[] | 임베디드 객체의 이미지 데이터. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호입니다. |

### OleDiagramOptions(String filePath, int pageNumber) {#OleDiagramOptions-java.lang.String-int-}
```
public OleDiagramOptions(String filePath, int pageNumber)
```


새 인스턴스를 초기화합니다 [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 임베디드 객체의 파일 경로입니다. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호입니다. |

### getX() {#getX--}
```
public final int getX()
```


페이지와 관련된 임베디드 객체 형태의 핀(회전 중심)의 X 좌표.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


페이지와 관련된 임베디드 객체 형태의 핀(회전 중심)의 X 좌표.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


페이지와 관련된 임베디드 객체 형태의 핀(회전 중심)의 Y 좌표.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


페이지와 관련된 임베디드 객체 형태의 핀(회전 중심)의 Y 좌표.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


삽입된 객체 모양의 너비(인치).

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


삽입된 객체 모양의 너비(인치).

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


삽입된 객체 모양의 높이(인치).

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


삽입된 객체 모양의 높이(인치).

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


임베디드 객체의 이미지 데이터.

**Returns:**
byte[]
