---
title: "OleSpreadsheetOptions"
second_title: "GroupDocs.Merger için Java API Referansı"
description: "OLE aracılığıyla gömülü belgenin Elektronik Tablo'ya içe aktarılması için seçenekler sağlar."
type: docs
weight: 20
url: /tr/java/com.groupdocs.merger.domain.options/olespreadsheetoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleSpreadsheetOptions](../../com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions)
```
public class OleSpreadsheetOptions extends ImportDocumentOptions implements IOleSpreadsheetOptions
```

OLE aracılığıyla gömülü belgenin Elektronik Tablo'ya içe aktarılması için seçenekler sağlar.

--------------------

**Learn more**

 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]


[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleSpreadsheetOptions-byte---byte---java.lang.String-int-) | Yeni bir [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) sınıfı örneği başlatır. |
| [OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-byte---int-) | Yeni bir [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) sınıfı örneği başlatır. |
| [OleSpreadsheetOptions(String filePath, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-int-) | Yeni bir [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | Üst sol satır indeksi. |
| [setRowIndex(int value)](#setRowIndex-int-) | Üst sol satır indeksi. |
| [getColumnIndex()](#getColumnIndex--) | Üst sol sütun indeksi. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | Üst sol sütun indeksi. |
| [getWidth()](#getWidth--) | Ole nesne görüntüsünün genişliği. |
| [setWidth(int value)](#setWidth-int-) | Ole nesne görüntüsünün genişliği. |
| [getHeight()](#getHeight--) | Ole nesne görüntüsünün yüksekliği. |
| [setHeight(int value)](#setHeight-int-) | Ole nesne görüntüsünün yüksekliği. |
| [getImageData()](#getImageData--) | Ole nesne görüntüsünün verileri. |
### OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleSpreadsheetOptions-byte---byte---java.lang.String-int-}
```
public OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Yeni bir [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| objectData | byte[] | Gömülü nesnenin verileri. |
| imageData | byte[] | Gömülü nesnenin görüntü verileri. |
| uzantı | java.lang.String | Gömülü nesnenin uzantısı. |
| pageNumber | int | Gömülü nesneyi eklemek için sayfa numarası. |

### OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-byte---int-}
```
public OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)
```


Yeni bir [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Gömülü nesnenin dosya yolu. |
| imageData | byte[] | Gömülü nesnenin görüntü verileri. |
| pageNumber | int | Gömülü nesneyi eklemek için sayfa numarası. |

### OleSpreadsheetOptions(String filePath, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-int-}
```
public OleSpreadsheetOptions(String filePath, int pageNumber)
```


Yeni bir [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Gömülü nesnenin dosya yolu. |
| pageNumber | int | Gömülü nesneyi eklemek için sayfa numarası. |

### getRowIndex() {#getRowIndex--}
```
public final int getRowIndex()
```


Üst sol satır indeksi.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public final void setRowIndex(int value)
```


Üst sol satır indeksi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public final int getColumnIndex()
```


Üst sol sütun indeksi.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public final void setColumnIndex(int value)
```


Üst sol sütun indeksi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ole nesne görüntüsünün genişliği.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ole nesne görüntüsünün genişliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ole nesne görüntüsünün yüksekliği.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ole nesne görüntüsünün yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Ole nesne görüntüsünün verileri.

**Returns:**
byte[]
