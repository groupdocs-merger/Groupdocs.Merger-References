---
title: "MoveOptions"
second_title: "GroupDocs.Merger Node.js için Java API Referansı"
description: "Belge sayfasını taşıma için seçenekler sağlar."
type: docs
weight: 17
url: /tr/nodejs-java/com.groupdocs.merger.domain.options/moveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions)
```
public class MoveOptions implements IMoveOptions
```

Belge sayfasını taşıma için seçenekler sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MoveOptions(int pageNumberToMove, int newPageNumber)](#MoveOptions-int-int-) | Yeni bir [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPageNumberToMove()](#getPageNumberToMove--) | Taşınacak sayfa numarasını alır veya ayarlar. |
| [getNewPageNumber()](#getNewPageNumber--) | Yeni sayfa numarasını alır veya ayarlar. |
### MoveOptions(int pageNumberToMove, int newPageNumber) {#MoveOptions-int-int-}
```
public MoveOptions(int pageNumberToMove, int newPageNumber)
```


Yeni bir [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumberToMove | int | Taşınacak sayfa numarası. |
| newPageNumber | int | Yeni sayfa numarası. |

### getPageNumberToMove() {#getPageNumberToMove--}
```
public final int getPageNumberToMove()
```


Taşınacak sayfa numarasını alır veya ayarlar.

Değer: Taşınacak sayfa numarası.

**Returns:**
int
### getNewPageNumber() {#getNewPageNumber--}
```
public final int getNewPageNumber()
```


Yeni sayfa numarasını alır veya ayarlar.

Değer: Yeni sayfa numarası.

**Returns:**
int
