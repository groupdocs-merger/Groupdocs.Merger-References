---
title: "IOleSpreadsheetOptions"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "OLE를 통한 임베디드 문서를 스프레드시트로 가져오기 옵션을 위한 인터페이스."
type: docs
weight: 19
url: /ko/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleSpreadsheetOptions extends IImportDocumentOptions, ISizeOptions
```

OLE를 통한 임베디드 문서를 스프레드시트로 가져오기 옵션을 위한 인터페이스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | 왼쪽 위 행 인덱스입니다. |
| [setRowIndex(int value)](#setRowIndex-int-) | 왼쪽 위 행 인덱스입니다. |
| [getColumnIndex()](#getColumnIndex--) | 왼쪽 위 열 인덱스입니다. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | 왼쪽 위 열 인덱스입니다. |
| [getImageData()](#getImageData--) | Ole 객체 이미지의 데이터입니다. |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


왼쪽 위 행 인덱스입니다.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


왼쪽 위 행 인덱스입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


왼쪽 위 열 인덱스입니다.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


왼쪽 위 열 인덱스입니다.

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
