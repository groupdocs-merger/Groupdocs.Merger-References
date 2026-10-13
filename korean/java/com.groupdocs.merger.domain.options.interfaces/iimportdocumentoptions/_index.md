---
title: "IImportDocumentOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "임베디드 문서 가져오기를 위한 인터페이스."
type: docs
weight: 13
url: /ko/java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface IImportDocumentOptions extends IOptions
```

임베디드 문서 가져오기를 위한 인터페이스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getObjectData()](#getObjectData--) | 삽입된 객체의 데이터입니다. |
| [getExtension()](#getExtension--) | 삽입된 객체의 확장자입니다. |
| [getPageNumber()](#getPageNumber--) | 삽입된 객체를 넣을 페이지 번호입니다. |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


삽입된 객체의 데이터입니다.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


삽입된 객체의 확장자입니다.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


삽입된 객체를 넣을 페이지 번호입니다.

**Returns:**
int
