---
title: "IImportDocumentOptions"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "임베디드 문서 가져오기를 위한 인터페이스."
type: docs
weight: 13
url: /ko/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
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
| [getObjectData()](#getObjectData--) | 임베디드 객체의 데이터. |
| [getExtension()](#getExtension--) | 임베디드 객체의 확장자. |
| [getPageNumber()](#getPageNumber--) | 임베디드 객체를 삽입할 페이지 번호. |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


임베디드 객체의 데이터.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


임베디드 객체의 확장자.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


임베디드 객체를 삽입할 페이지 번호.

**Returns:**
int
