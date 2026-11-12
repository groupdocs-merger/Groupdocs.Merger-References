---
title: "ImportDocumentOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "임베디드 문서 가져오기를 위한 옵션을 제공합니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.merger.domain.options/importdocumentoptions/
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
| [getObjectData()](#getObjectData--) | 삽입된 객체의 데이터입니다. |
| [getExtension()](#getExtension--) | 삽입된 객체의 확장자입니다. |
| [getPageNumber()](#getPageNumber--) | 삽입된 객체를 넣을 페이지 번호입니다. |
| [getImageData(String filePath)](#getImageData-java.lang.String-) | 임베디드 객체의 이미지 데이터를 가져옵니다. |
### ImportDocumentOptions(byte[] objectData, String extension, int pageNumber) {#ImportDocumentOptions-byte---java.lang.String-int-}
```
public ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)
```


새 인스턴스를 초기화합니다 [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| objectData | byte[] | 삽입된 객체의 데이터입니다. |
| 확장자 | java.lang.String | 삽입된 객체의 확장자입니다. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호. |

### ImportDocumentOptions(String filePath, int pageNumber) {#ImportDocumentOptions-java.lang.String-int-}
```
public ImportDocumentOptions(String filePath, int pageNumber)
```


새 인스턴스를 초기화합니다 [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 임베디드 객체의 파일 경로. |
| pageNumber | int | 임베디드 객체를 추가하기 위한 페이지 번호. |

### getObjectData() {#getObjectData--}
```
public final byte[] getObjectData()
```


삽입된 객체의 데이터입니다.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public final String getExtension()
```


삽입된 객체의 확장자입니다.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


삽입된 객체를 넣을 페이지 번호입니다.

**Returns:**
int
### getImageData(String filePath) {#getImageData-java.lang.String-}
```
public final byte[] getImageData(String filePath)
```


임베디드 객체의 이미지 데이터를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 임베디드 객체의 파일 경로. |

**Returns:**
byte[]
