---
title: "OleDiagramOptions"
second_title: "GroupDocs.Merger Node.js için Java API Referansı"
description: "OLE aracılığıyla gömülü belgenin Diagram'a içe aktarılması için seçenekler sağlar."
type: docs
weight: 18
url: /tr/nodejs-java/com.groupdocs.merger.domain.options/olediagramoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleDiagramOptions](../../com.groupdocs.merger.domain.options.interfaces/iolediagramoptions)
```
public class OleDiagramOptions extends ImportDocumentOptions implements IOleDiagramOptions
```

OLE aracılığıyla gömülü belgenin Diagram'a içe aktarılması için seçenekler sağlar.

--------------------

**Learn more**

 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleDiagramOptions-byte---byte---java.lang.String-int-) | Yeni bir [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) sınıfı örneği başlatır. |
| [OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)](#OleDiagramOptions-java.lang.String-byte---int-) | Yeni bir [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) sınıfı örneği başlatır. |
| [OleDiagramOptions(String filePath, int pageNumber)](#OleDiagramOptions-java.lang.String-int-) | Yeni bir [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getX()](#getX--) | Sayfaya göre yerleştirilmiş nesne şeklinin piminin (dönme merkezi) X koordinatı. |
| [setX(int value)](#setX-int-) | Sayfaya göre yerleştirilmiş nesne şeklinin piminin (dönme merkezi) X koordinatı. |
| [getY()](#getY--) | Sayfaya göre yerleştirilmiş nesne şeklinin piminin (dönme merkezi) Y koordinatı. |
| [setY(int value)](#setY-int-) | Sayfaya göre yerleştirilmiş nesne şeklinin piminin (dönme merkezi) Y koordinatı. |
| [getWidth()](#getWidth--) | Gömülü nesne şeklinin inç cinsinden genişliği. |
| [setWidth(int value)](#setWidth-int-) | Gömülü nesne şeklinin inç cinsinden genişliği. |
| [getHeight()](#getHeight--) | Gömülü nesne şeklinin inç cinsinden yüksekliği. |
| [setHeight(int value)](#setHeight-int-) | Gömülü nesne şeklinin inç cinsinden yüksekliği. |
| [getImageData()](#getImageData--) | Yerleştirilmiş nesnenin görüntü verileri. |
### OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleDiagramOptions-byte---byte---java.lang.String-int-}
```
public OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Yeni bir [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| objectData | byte[] | Yerleştirilmiş nesnenin verileri. |
| imageData | byte[] | Yerleştirilmiş nesnenin görüntü verileri. |
| uzantı | java.lang.String | Yerleştirilmiş nesnenin uzantısı. |
| pageNumber | int | Gömülü nesneyi eklemek için sayfa numarası. |

### OleDiagramOptions(String filePath, byte[] imageData, int pageNumber) {#OleDiagramOptions-java.lang.String-byte---int-}
```
public OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)
```


Yeni bir [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Gömülü nesnenin dosya yolu. |
| imageData | byte[] | Yerleştirilmiş nesnenin görüntü verileri. |
| pageNumber | int | Gömülü nesneyi eklemek için sayfa numarası. |

### OleDiagramOptions(String filePath, int pageNumber) {#OleDiagramOptions-java.lang.String-int-}
```
public OleDiagramOptions(String filePath, int pageNumber)
```


Yeni bir [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Gömülü nesnenin dosya yolu. |
| pageNumber | int | Gömülü nesneyi eklemek için sayfa numarası. |

### getX() {#getX--}
```
public final int getX()
```


Sayfaya göre yerleştirilmiş nesne şeklinin piminin (dönme merkezi) X koordinatı.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Sayfaya göre yerleştirilmiş nesne şeklinin piminin (dönme merkezi) X koordinatı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


Sayfaya göre yerleştirilmiş nesne şeklinin piminin (dönme merkezi) Y koordinatı.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Sayfaya göre yerleştirilmiş nesne şeklinin piminin (dönme merkezi) Y koordinatı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gömülü nesne şeklinin inç cinsinden genişliği.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Gömülü nesne şeklinin inç cinsinden genişliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gömülü nesne şeklinin inç cinsinden yüksekliği.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Gömülü nesne şeklinin inç cinsinden yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Yerleştirilmiş nesnenin görüntü verileri.

**Returns:**
byte[]
