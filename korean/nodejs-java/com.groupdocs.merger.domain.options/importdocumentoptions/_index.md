---
title: "ImportDocumentOptions"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "임베디드 문서 가져오기를 위한 옵션을 제공합니다."
type: docs
weight: 14
url: /ko/nodejs-java/com.groupdocs.merger.domain.options/importdocumentoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions)
```
public abstract class ImportDocumentOptions implements IImportDocumentOptions
```

임베디드 문서 가져오기를 위한 옵션을 제공합니다.

--------------------

**Learn more**

 *  More about adding attachment to PDF documents: [How to add attachment to PDF document.][]
 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]
 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]
 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]
 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[How to add attachment to PDF document.]: https://docs.groupdocs.com/merger/java/how-to-add-attachment-to-pdf-document/
[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)](#ImportDocumentOptions-byte---java.lang.String-int-) | 새 인스턴스를 초기화합니다 [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) 클래스. |
| [ImportDocumentOptions(String filePath, int pageNumber)](#ImportDocumentOptions-java.lang.String-int-) | 새 인스턴스를 초기화합니다 [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getObjectData()](#getObjectData--) | 임베디드 객체의 데이터. |
| [getExtension()](#getExtension--) | 임베디드 객체의 확장자. |
| [getPageNumber()](#getPageNumber--) | 임베디드 객체를 삽입할 페이지 번호. |
| [getImageData(String filePath)](#getImageData-java.lang.String-) | 임베디드 객체의 이미지 데이터를 가져옵니다. |
### ImportDocumentOptions(byte[] objectData, String extension, int pageNumber) {#ImportDocumentOptions-byte---java.lang.String-int-}
```
public ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)
```


새 인스턴스를 초기화합니다 [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| objectData | byte[] | 임베디드 객체의 데이터. |
| 확장자 | java.lang.String | 임베디드 객체의 확장자. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호입니다. |

### ImportDocumentOptions(String filePath, int pageNumber) {#ImportDocumentOptions-java.lang.String-int-}
```
public ImportDocumentOptions(String filePath, int pageNumber)
```


새 인스턴스를 초기화합니다 [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 임베디드 객체의 파일 경로입니다. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호입니다. |

### getObjectData() {#getObjectData--}
```
public final byte[] getObjectData()
```


임베디드 객체의 데이터.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public final String getExtension()
```


임베디드 객체의 확장자.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


임베디드 객체를 삽입할 페이지 번호.

**Returns:**
int
### getImageData(String filePath) {#getImageData-java.lang.String-}
```
public final byte[] getImageData(String filePath)
```


임베디드 객체의 이미지 데이터를 가져옵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 임베디드 객체의 파일 경로입니다. |

**Returns:**
byte[]
