---
title: "OleSpreadsheetOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "OLE를 통해 임베디드 문서를 Spreadsheet에 가져오기 위한 옵션을 제공합니다."
type: docs
weight: 20
url: /ko/java/com.groupdocs.merger.domain.options/olespreadsheetoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleSpreadsheetOptions](../../com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions)
```
public class OleSpreadsheetOptions extends ImportDocumentOptions implements IOleSpreadsheetOptions
```

OLE를 통해 임베디드 문서를 Spreadsheet에 가져오기 위한 옵션을 제공합니다.

--------------------

**Learn more**

 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]


[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleSpreadsheetOptions-byte---byte---java.lang.String-int-) | 새 인스턴스를 초기화합니다 [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) 클래스. |
| [OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-byte---int-) | 새 인스턴스를 초기화합니다 [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) 클래스. |
| [OleSpreadsheetOptions(String filePath, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-int-) | 새 인스턴스를 초기화합니다 [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | 왼쪽 위 행 인덱스. |
| [setRowIndex(int value)](#setRowIndex-int-) | 왼쪽 위 행 인덱스. |
| [getColumnIndex()](#getColumnIndex--) | 왼쪽 위 열 인덱스. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | 왼쪽 위 열 인덱스. |
| [getWidth()](#getWidth--) | Ole 객체 이미지의 너비. |
| [setWidth(int value)](#setWidth-int-) | Ole 객체 이미지의 너비. |
| [getHeight()](#getHeight--) | Ole 객체 이미지의 높이. |
| [setHeight(int value)](#setHeight-int-) | Ole 객체 이미지의 높이. |
| [getImageData()](#getImageData--) | Ole 객체 이미지 데이터. |
### OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleSpreadsheetOptions-byte---byte---java.lang.String-int-}
```
public OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


새 인스턴스를 초기화합니다 [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| objectData | byte[] | 삽입된 객체의 데이터입니다. |
| imageData | byte[] | 삽입된 객체의 이미지 데이터입니다. |
| 확장자 | java.lang.String | 삽입된 객체의 확장자입니다. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호. |

### OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-byte---int-}
```
public OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)
```


새 인스턴스를 초기화합니다 [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 임베디드 객체의 파일 경로. |
| imageData | byte[] | 삽입된 객체의 이미지 데이터입니다. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호. |

### OleSpreadsheetOptions(String filePath, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-int-}
```
public OleSpreadsheetOptions(String filePath, int pageNumber)
```


새 인스턴스를 초기화합니다 [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 임베디드 객체의 파일 경로. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호. |

### getRowIndex() {#getRowIndex--}
```
public final int getRowIndex()
```


왼쪽 위 행 인덱스.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public final void setRowIndex(int value)
```


왼쪽 위 행 인덱스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public final int getColumnIndex()
```


왼쪽 위 열 인덱스.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public final void setColumnIndex(int value)
```


왼쪽 위 열 인덱스.

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
