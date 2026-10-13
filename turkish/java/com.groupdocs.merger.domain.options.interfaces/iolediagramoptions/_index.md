---
title: "IOleDiagramOptions"
second_title: "GroupDocs.Merger için Java API Referansı"
description: "OLE aracılığıyla Gömülü belgeyi Diyagram'a içe aktarma seçenekleri için arabirim."
type: docs
weight: 17
url: /tr/java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleDiagramOptions extends IImportDocumentOptions, ISizeOptions
```

OLE aracılığıyla Gömülü belgeyi Diyagram'a içe aktarma seçenekleri için arabirim.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getX()](#getX--) | Sayfaya göre gömülü nesne şeklinin piminin (dönme merkezi) X koordinatı. |
| [setX(int value)](#setX-int-) | Sayfaya göre gömülü nesne şeklinin piminin (dönme merkezi) X koordinatı. |
| [getY()](#getY--) | Sayfaya göre gömülü nesne şeklinin piminin (dönme merkezi) Y koordinatı. |
| [setY(int value)](#setY-int-) | Sayfaya göre gömülü nesne şeklinin piminin (dönme merkezi) Y koordinatı. |
| [getImageData()](#getImageData--) | Gömülü nesnenin görüntü verileri. |
### getX() {#getX--}
```
public abstract int getX()
```


Sayfaya göre gömülü nesne şeklinin piminin (dönme merkezi) X koordinatı.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


Sayfaya göre gömülü nesne şeklinin piminin (dönme merkezi) X koordinatı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


Sayfaya göre gömülü nesne şeklinin piminin (dönme merkezi) Y koordinatı.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


Sayfaya göre gömülü nesne şeklinin piminin (dönme merkezi) Y koordinatı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Gömülü nesnenin görüntü verileri.

**Returns:**
byte[]
