---
title: "ImportDocumentOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "提供嵌入文档导入的选项。"
type: docs
weight: 14
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/importdocumentoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions)
```
public abstract class ImportDocumentOptions implements IImportDocumentOptions
```

提供嵌入文档导入的选项。

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
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)](#ImportDocumentOptions-byte---java.lang.String-int-) | 初始化一个新的 [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) 类的实例。 |
| [ImportDocumentOptions(String filePath, int pageNumber)](#ImportDocumentOptions-java.lang.String-int-) | 初始化一个新的 [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getObjectData()](#getObjectData--) | 嵌入对象的数据。 |
| [getExtension()](#getExtension--) | 嵌入对象的扩展名。 |
| [getPageNumber()](#getPageNumber--) | 嵌入对象插入的页码。 |
| [getImageData(String filePath)](#getImageData-java.lang.String-) | 获取嵌入对象的图像数据。 |
### ImportDocumentOptions(byte[] objectData, String extension, int pageNumber) {#ImportDocumentOptions-byte---java.lang.String-int-}
```
public ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)
```


初始化一个新的 [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| objectData | byte[] | 嵌入对象的数据。 |
| 扩展名 | java.lang.String | 嵌入对象的扩展名。 |
| pageNumber | int | 用于添加嵌入对象的页码。 |

### ImportDocumentOptions(String filePath, int pageNumber) {#ImportDocumentOptions-java.lang.String-int-}
```
public ImportDocumentOptions(String filePath, int pageNumber)
```


初始化一个新的 [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 嵌入对象的文件路径。 |
| pageNumber | int | 用于添加嵌入对象的页码。 |

### getObjectData() {#getObjectData--}
```
public final byte[] getObjectData()
```


嵌入对象的数据。

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public final String getExtension()
```


嵌入对象的扩展名。

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


嵌入对象插入的页码。

**Returns:**
int
### getImageData(String filePath) {#getImageData-java.lang.String-}
```
public final byte[] getImageData(String filePath)
```


获取嵌入对象的图像数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 嵌入对象的文件路径。 |

**Returns:**
byte[]
