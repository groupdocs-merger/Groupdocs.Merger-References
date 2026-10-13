---
title: "IOleSpreadsheetOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "OLE를 통해 임베디드 문서를 스프레드시트로 가져오는 옵션을 위한 인터페이스."
type: docs
weight: 19
url: /ko/java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleSpreadsheetOptions extends IImportDocumentOptions, ISizeOptions
```

OLE를 통해 임베디드 문서를 스프레드시트로 가져오는 옵션을 위한 인터페이스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | 왼쪽 위 행 인덱스. |
| [setRowIndex(int value)](#setRowIndex-int-) | 왼쪽 위 행 인덱스. |
| [getColumnIndex()](#getColumnIndex--) | 왼쪽 위 열 인덱스. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | 왼쪽 위 열 인덱스. |
| [getImageData()](#getImageData--) | Ole 객체 이미지 데이터. |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


왼쪽 위 행 인덱스.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


왼쪽 위 행 인덱스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


왼쪽 위 열 인덱스.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


왼쪽 위 열 인덱스.

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
