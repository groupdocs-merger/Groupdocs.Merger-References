---
title: "OlePresentationOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "OLE를 통해 임베디드 문서를 Presentation에 가져오기 위한 옵션을 제공합니다."
type: docs
weight: 19
url: /ko/java/com.groupdocs.merger.domain.options/olepresentationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOlePresentationOptions](../../com.groupdocs.merger.domain.options.interfaces/iolepresentationoptions)
```
public class OlePresentationOptions extends ImportDocumentOptions implements IOlePresentationOptions
```

OLE를 통해 임베디드 문서를 Presentation에 가져오기 위한 옵션을 제공합니다.

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
| [getX()](#getX--) | 임베드된 객체 프레임의 X 좌표. |
| [setX(int value)](#setX-int-) | 임베드된 객체 프레임의 X 좌표. |
| [getY()](#getY--) | 임베드된 객체 프레임의 Y 좌표. |
| [setY(int value)](#setY-int-) | 임베드된 객체 프레임의 Y 좌표. |
| [getWidth()](#getWidth--) | 임베디드 객체 프레임의 너비. |
| [setWidth(int value)](#setWidth-int-) | 임베디드 객체 프레임의 너비. |
| [getHeight()](#getHeight--) | 임베디드 객체 프레임의 높이. |
| [setHeight(int value)](#setHeight-int-) | 임베디드 객체 프레임의 높이. |
### OlePresentationOptions(byte[] objectData, String extension, int pageNumber) {#OlePresentationOptions-byte---java.lang.String-int-}
```
public OlePresentationOptions(byte[] objectData, String extension, int pageNumber)
```


새 인스턴스를 초기화합니다 [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| objectData | byte[] | 삽입된 객체의 데이터입니다. |
| 확장자 | java.lang.String | 삽입된 객체의 확장자입니다. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호. |

### OlePresentationOptions(String filePath, int pageNumber) {#OlePresentationOptions-java.lang.String-int-}
```
public OlePresentationOptions(String filePath, int pageNumber)
```


새 인스턴스를 초기화합니다 [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 임베디드 객체의 파일 경로. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호. |

### getX() {#getX--}
```
public final int getX()
```


임베드된 객체 프레임의 X 좌표.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


임베드된 객체 프레임의 X 좌표.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getY() {#getY--}
```
public final int getY()
```


임베드된 객체 프레임의 Y 좌표.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


임베드된 객체 프레임의 Y 좌표.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


임베디드 객체 프레임의 너비.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


임베디드 객체 프레임의 너비.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


임베디드 객체 프레임의 높이.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


임베디드 객체 프레임의 높이.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

