---
title: "OleWordProcessingOptions"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "OLE를 통해 임베디드 문서를 Word 처리로 가져오기 위한 옵션을 제공합니다."
type: docs
weight: 21
url: /ko/nodejs-java/com.groupdocs.merger.domain.options/olewordprocessingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleWordProcessingOptions](../../com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions)
```
public class OleWordProcessingOptions extends ImportDocumentOptions implements IOleWordProcessingOptions
```

OLE를 통해 임베디드 문서를 Word 처리로 가져오기 위한 옵션을 제공합니다.

--------------------

**Learn more**

 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]


[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleWordProcessingOptions-byte---byte---java.lang.String-int-) | [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) 클래스의 새 인스턴스를 초기화합니다. |
| [OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)](#OleWordProcessingOptions-java.lang.String-byte---int-) | [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) 클래스의 새 인스턴스를 초기화합니다. |
| [OleWordProcessingOptions(String filePath, int pageNumber)](#OleWordProcessingOptions-java.lang.String-int-) | [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLeft()](#getLeft--) | Ole 객체 이미지의 왼쪽 좌표. |
| [setLeft(int value)](#setLeft-int-) | Ole 객체 이미지의 왼쪽 좌표. |
| [getTop()](#getTop--) | Ole 객체 이미지의 상단 좌표. |
| [setTop(int value)](#setTop-int-) | Ole 객체 이미지의 상단 좌표. |
| [getWidth()](#getWidth--) | Ole 객체 이미지의 너비입니다. |
| [setWidth(int value)](#setWidth-int-) | Ole 객체 이미지의 너비입니다. |
| [getHeight()](#getHeight--) | Ole 객체 이미지의 높이입니다. |
| [setHeight(int value)](#setHeight-int-) | Ole 객체 이미지의 높이입니다. |
| [getImageData()](#getImageData--) | Ole 객체 이미지의 데이터입니다. |
### OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleWordProcessingOptions-byte---byte---java.lang.String-int-}
```
public OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


[OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| objectData | byte[] | 임베디드 객체의 데이터. |
| imageData | byte[] | 임베디드 객체의 이미지 데이터. |
| 확장자 | java.lang.String | 임베디드 객체의 확장자. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호입니다. |

### OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber) {#OleWordProcessingOptions-java.lang.String-byte---int-}
```
public OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)
```


[OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 임베디드 객체의 파일 경로입니다. |
| imageData | byte[] | 임베디드 객체의 이미지 데이터. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호입니다. |

### OleWordProcessingOptions(String filePath, int pageNumber) {#OleWordProcessingOptions-java.lang.String-int-}
```
public OleWordProcessingOptions(String filePath, int pageNumber)
```


[OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 임베디드 객체의 파일 경로입니다. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호입니다. |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Ole 객체 이미지의 왼쪽 좌표.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Ole 객체 이미지의 왼쪽 좌표.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Ole 객체 이미지의 상단 좌표.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Ole 객체 이미지의 상단 좌표.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ole 객체 이미지의 너비입니다.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ole 객체 이미지의 너비입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ole 객체 이미지의 높이입니다.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ole 객체 이미지의 높이입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Ole 객체 이미지의 데이터입니다.

**Returns:**
byte[]
