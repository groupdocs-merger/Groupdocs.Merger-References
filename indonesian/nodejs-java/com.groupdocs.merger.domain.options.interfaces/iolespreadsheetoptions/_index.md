---
title: "IOleSpreadsheetOptions"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Antarmuka untuk opsi impor dokumen tersemat ke Spreadsheet melalui OLE."
type: docs
weight: 19
url: /id/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleSpreadsheetOptions extends IImportDocumentOptions, ISizeOptions
```

Antarmuka untuk opsi impor dokumen tersemat ke Spreadsheet melalui OLE.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | Indeks baris kiri atas. |
| [setRowIndex(int value)](#setRowIndex-int-) | Indeks baris kiri atas. |
| [getColumnIndex()](#getColumnIndex--) | Indeks kolom kiri atas. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | Indeks kolom kiri atas. |
| [getImageData()](#getImageData--) | Data gambar objek Ole. |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


Indeks baris kiri atas.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


Indeks baris kiri atas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


Indeks kolom kiri atas.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


Indeks kolom kiri atas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Data gambar objek Ole.

**Returns:**
byte[]
