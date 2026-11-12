---
title: "OleWordProcessingOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "OLE를 통해 임베디드 문서를 Word 처리에 가져오기 위한 옵션을 제공합니다."
type: docs
weight: 21
url: /ko/java/com.groupdocs.merger.domain.options/olewordprocessingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleWordProcessingOptions](../../com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions)
```
public class OleWordProcessingOptions extends ImportDocumentOptions implements IOleWordProcessingOptions
```

OLE를 통해 임베디드 문서를 Word 처리에 가져오기 위한 옵션을 제공합니다.

--------------------

**Learn more**

 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]


[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleWordProcessingOptions-byte---byte---java.lang.String-int-) | 새 인스턴스를 초기화합니다 [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) 클래스. |
| [OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)](#OleWordProcessingOptions-java.lang.String-byte---int-) | 새 인스턴스를 초기화합니다 [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) 클래스. |
| [OleWordProcessingOptions(String filePath, int pageNumber)](#OleWordProcessingOptions-java.lang.String-int-) | 새 인스턴스를 초기화합니다 [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLeft()](#getLeft--) | Ole 객체 이미지의 왼쪽 좌표. |
| [setLeft(int value)](#setLeft-int-) | Ole 객체 이미지의 왼쪽 좌표. |
| [getTop()](#getTop--) | Ole 객체 이미지의 위쪽 좌표. |
| [setTop(int value)](#setTop-int-) | Ole 객체 이미지의 위쪽 좌표. |
| [getWidth()](#getWidth--) | Ole 객체 이미지의 너비. |
| [setWidth(int value)](#setWidth-int-) | Ole 객체 이미지의 너비. |
| [getHeight()](#getHeight--) | Ole 객체 이미지의 높이. |
| [setHeight(int value)](#setHeight-int-) | Ole 객체 이미지의 높이. |
| [getImageData()](#getImageData--) | Ole 객체 이미지 데이터. |
### OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleWordProcessingOptions-byte---byte---java.lang.String-int-}
```
public OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


새 인스턴스를 초기화합니다 [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| objectData | byte[] | 삽입된 객체의 데이터입니다. |
| imageData | byte[] | 삽입된 객체의 이미지 데이터입니다. |
| 확장자 | java.lang.String | 삽입된 객체의 확장자입니다. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호. |

### OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber) {#OleWordProcessingOptions-java.lang.String-byte---int-}
```
public OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)
```


새 인스턴스를 초기화합니다 [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 임베디드 객체의 파일 경로. |
| imageData | byte[] | 삽입된 객체의 이미지 데이터입니다. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호. |

### OleWordProcessingOptions(String filePath, int pageNumber) {#OleWordProcessingOptions-java.lang.String-int-}
```
public OleWordProcessingOptions(String filePath, int pageNumber)
```


새 인스턴스를 초기화합니다 [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 임베디드 객체의 파일 경로. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호. |

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Ole 객체 이미지의 위쪽 좌표.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Ole 객체 이미지의 위쪽 좌표.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ole 객체 이미지의 너비.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ole 객체 이미지의 너비.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ole 객체 이미지의 높이.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ole 객체 이미지의 높이.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Ole 객체 이미지 데이터.

**Returns:**
byte[]
