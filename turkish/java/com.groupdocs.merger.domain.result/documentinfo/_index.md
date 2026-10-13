---
title: "DocumentInfo"
second_title: "GroupDocs.Merger için Java API Referansı"
description: "Belge tanım özelliklerini tanımlar."
type: docs
weight: 10
url: /tr/java/com.groupdocs.merger.domain.result/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IDocumentInfo](../../com.groupdocs.merger.domain.result/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Belge tanım özelliklerini tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Yeni bir [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) sınıfının örneğini başlatır. |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-) | Yeni bir [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) sınıfının örneğini başlatır. |
| [DocumentInfo(FileType fileType, IPageInfo[] pages, long size)](#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-) | Yeni bir [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getIndex()](#getIndex--) | Belge indeksi. |
| [getStream()](#getStream--) | Belge akışı. |
| [getPassword()](#getPassword--) | Belge şifresi. |
| [getType()](#getType--) | Dosya tipini alır. |
| [getPages()](#getPages--) | Belge sayfaları koleksiyonunu tanımlar. |
| [getPageCount()](#getPageCount--) | Belge sayfa sayısı. |
| [getSize()](#getSize--) | Belge boyutu bayt cinsinden |
| [toString()](#toString--) | Mevcut nesneyi temsil eden bir dize döndürür. |
### DocumentInfo(int index, InputStream stream, FileType fileType, String password) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password)
```


Yeni bir [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int |  |
| stream | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Dosyanın türü. |
| parola | java.lang.String |  |

### DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)
```


Yeni bir [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int |  |
| stream | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Dosyanın türü. |
| parola | java.lang.String |  |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Görüntülenecek sayfaların listesi. |
| boyut | uzun | Dosyanın boyutu. |

### DocumentInfo(FileType fileType, IPageInfo[] pages, long size) {#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```


Yeni bir [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Dosyanın türü. |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Görüntülenecek sayfaların listesi. |
| boyut | uzun | Dosyanın boyutu. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


Belge indeksi.

**Returns:**
int
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Belge akışı.

**Returns:**
java.io.InputStream
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Belge şifresi.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final FileType getType()
```


Dosya tipini alır.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPages() {#getPages--}
```
public final IPageInfo[] getPages()
```


Belge sayfaları koleksiyonunu tanımlar.

**Returns:**
com.groupdocs.merger.domain.result.IPageInfo[]
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Belge sayfa sayısı.

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Belge boyutu bayt cinsinden

**Returns:**
uzun
### toString() {#toString--}
```
public String toString()
```


Mevcut nesneyi temsil eden bir dize döndürür.

**Returns:**
java.lang.String - Geçerli nesneyi temsil eden bir dize.
