---
title: "OlePresentationOptions"
second_title: "GroupDocs.Merger Node.js için Java API Referansı"
description: "OLE aracılığıyla gömülü belgenin Presentation'a içe aktarılması için seçenekler sağlar."
type: docs
weight: 19
url: /tr/nodejs-java/com.groupdocs.merger.domain.options/olepresentationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOlePresentationOptions](../../com.groupdocs.merger.domain.options.interfaces/iolepresentationoptions)
```
public class OlePresentationOptions extends ImportDocumentOptions implements IOlePresentationOptions
```

OLE aracılığıyla gömülü belgenin Presentation'a içe aktarılması için seçenekler sağlar.

--------------------

**Learn more**

 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]


[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OlePresentationOptions(byte[] objectData, String extension, int pageNumber)](#OlePresentationOptions-byte---java.lang.String-int-) | Yeni bir [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) sınıfının örneğini başlatır. |
| [OlePresentationOptions(String filePath, int pageNumber)](#OlePresentationOptions-java.lang.String-int-) | Yeni bir [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getX()](#getX--) | Gömülü nesne çerçevesinin X koordinatı. |
| [setX(int value)](#setX-int-) | Gömülü nesne çerçevesinin X koordinatı. |
| [getY()](#getY--) | Gömülü nesne çerçevesinin Y koordinatı. |
| [setY(int value)](#setY-int-) | Gömülü nesne çerçevesinin Y koordinatı. |
| [getWidth()](#getWidth--) | Gömülü nesne çerçevesinin genişliği. |
| [setWidth(int value)](#setWidth-int-) | Gömülü nesne çerçevesinin genişliği. |
| [getHeight()](#getHeight--) | Gömülü nesne çerçevesinin yüksekliği. |
| [setHeight(int value)](#setHeight-int-) | Gömülü nesne çerçevesinin yüksekliği. |
### OlePresentationOptions(byte[] objectData, String extension, int pageNumber) {#OlePresentationOptions-byte---java.lang.String-int-}
```
public OlePresentationOptions(byte[] objectData, String extension, int pageNumber)
```


Yeni bir [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| objectData | byte[] | Yerleştirilmiş nesnenin verileri. |
| uzantı | java.lang.String | Yerleştirilmiş nesnenin uzantısı. |
| pageNumber | int | Gömülü nesneyi eklemek için sayfa numarası. |

### OlePresentationOptions(String filePath, int pageNumber) {#OlePresentationOptions-java.lang.String-int-}
```
public OlePresentationOptions(String filePath, int pageNumber)
```


Yeni bir [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Gömülü nesnenin dosya yolu. |
| pageNumber | int | Gömülü nesneyi eklemek için sayfa numarası. |

### getX() {#getX--}
```
public final int getX()
```


Gömülü nesne çerçevesinin X koordinatı.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Gömülü nesne çerçevesinin X koordinatı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


Gömülü nesne çerçevesinin Y koordinatı.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Gömülü nesne çerçevesinin Y koordinatı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gömülü nesne çerçevesinin genişliği.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Gömülü nesne çerçevesinin genişliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gömülü nesne çerçevesinin yüksekliği.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Gömülü nesne çerçevesinin yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

