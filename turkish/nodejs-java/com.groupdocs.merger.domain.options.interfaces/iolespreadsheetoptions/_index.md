---
title: "IOleSpreadsheetOptions"
second_title: "GroupDocs.Merger Node.js için Java API Referansı"
description: "OLE aracılığıyla Gömülü belgeyi Elektronik Tablo'ya içe aktarma seçenekleri için arabirim."
type: docs
weight: 19
url: /tr/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleSpreadsheetOptions extends IImportDocumentOptions, ISizeOptions
```

OLE aracılığıyla Gömülü belgeyi Elektronik Tablo'ya içe aktarma seçenekleri için arabirim.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | Üst sol satır indeksi. |
| [setRowIndex(int value)](#setRowIndex-int-) | Üst sol satır indeksi. |
| [getColumnIndex()](#getColumnIndex--) | Üst sol sütun indeksi. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | Üst sol sütun indeksi. |
| [getImageData()](#getImageData--) | Ole nesne görüntüsünün verileri. |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


Üst sol satır indeksi.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


Üst sol satır indeksi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


Üst sol sütun indeksi.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


Üst sol sütun indeksi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Ole nesne görüntüsünün verileri.

**Returns:**
byte[]
