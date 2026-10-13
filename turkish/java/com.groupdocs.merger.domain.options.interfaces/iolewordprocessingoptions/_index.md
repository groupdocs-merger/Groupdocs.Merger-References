---
title: "IOleWordProcessingOptions"
second_title: "GroupDocs.Merger için Java API Referansı"
description: "OLE aracılığıyla Gömülü belgeyi Kelime İşlemeye içe aktarma seçenekleri için arabirim."
type: docs
weight: 20
url: /tr/java/com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleWordProcessingOptions extends IImportDocumentOptions, ISizeOptions
```

OLE aracılığıyla Gömülü belgeyi Kelime İşlemeye içe aktarma seçenekleri için arabirim.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLeft()](#getLeft--) | Ole nesne görüntüsünün sol koordinatı. |
| [setLeft(int value)](#setLeft-int-) | Ole nesne görüntüsünün sol koordinatı. |
| [getTop()](#getTop--) | Ole nesne görüntüsünün üst koordinatı. |
| [setTop(int value)](#setTop-int-) | Ole nesne görüntüsünün üst koordinatı. |
| [getImageData()](#getImageData--) | Ole nesne görüntüsünün verileri. |
### getLeft() {#getLeft--}
```
public abstract int getLeft()
```


Ole nesne görüntüsünün sol koordinatı.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public abstract void setLeft(int value)
```


Ole nesne görüntüsünün sol koordinatı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public abstract int getTop()
```


Ole nesne görüntüsünün üst koordinatı.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public abstract void setTop(int value)
```


Ole nesne görüntüsünün üst koordinatı.

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
