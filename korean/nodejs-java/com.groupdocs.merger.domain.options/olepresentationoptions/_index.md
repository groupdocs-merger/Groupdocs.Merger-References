---
title: "OlePresentationOptions"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "OLE를 통해 임베디드 문서를 Presentation으로 가져오기 위한 옵션을 제공합니다."
type: docs
weight: 19
url: /ko/nodejs-java/com.groupdocs.merger.domain.options/olepresentationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOlePresentationOptions](../../com.groupdocs.merger.domain.options.interfaces/iolepresentationoptions)
```
public class OlePresentationOptions extends ImportDocumentOptions implements IOlePresentationOptions
```

OLE를 통해 임베디드 문서를 Presentation으로 가져오기 위한 옵션을 제공합니다.

--------------------

**Learn more**

 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]


[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OlePresentationOptions(byte[] objectData, String extension, int pageNumber)](#OlePresentationOptions-byte---java.lang.String-int-) | 새 인스턴스를 초기화합니다 [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) 클래스. |
| [OlePresentationOptions(String filePath, int pageNumber)](#OlePresentationOptions-java.lang.String-int-) | 새 인스턴스를 초기화합니다 [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getX()](#getX--) | 내장 객체 프레임의 X 좌표. |
| [setX(int value)](#setX-int-) | 내장 객체 프레임의 X 좌표. |
| [getY()](#getY--) | 내장 객체 프레임의 Y 좌표. |
| [setY(int value)](#setY-int-) | 내장 객체 프레임의 Y 좌표. |
| [getWidth()](#getWidth--) | 임베디드 객체 프레임의 너비입니다. |
| [setWidth(int value)](#setWidth-int-) | 임베디드 객체 프레임의 너비입니다. |
| [getHeight()](#getHeight--) | 임베디드 객체 프레임의 높이입니다. |
| [setHeight(int value)](#setHeight-int-) | 임베디드 객체 프레임의 높이입니다. |
### OlePresentationOptions(byte[] objectData, String extension, int pageNumber) {#OlePresentationOptions-byte---java.lang.String-int-}
```
public OlePresentationOptions(byte[] objectData, String extension, int pageNumber)
```


새 인스턴스를 초기화합니다 [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| objectData | byte[] | 임베디드 객체의 데이터. |
| 확장자 | java.lang.String | 임베디드 객체의 확장자. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호입니다. |

### OlePresentationOptions(String filePath, int pageNumber) {#OlePresentationOptions-java.lang.String-int-}
```
public OlePresentationOptions(String filePath, int pageNumber)
```


새 인스턴스를 초기화합니다 [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 임베디드 객체의 파일 경로입니다. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호입니다. |

### getX() {#getX--}
```
public final int getX()
```


내장 객체 프레임의 X 좌표.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


내장 객체 프레임의 X 좌표.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


내장 객체 프레임의 Y 좌표.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


내장 객체 프레임의 Y 좌표.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


임베디드 객체 프레임의 너비입니다.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


임베디드 객체 프레임의 너비입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


임베디드 객체 프레임의 높이입니다.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


임베디드 객체 프레임의 높이입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

