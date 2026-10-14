---
title: "OleWordProcessingOptions"
second_title: "GroupDocs.Merger Node.js için Java API Referansı"
description: "OLE aracılığıyla gömülü belgenin Word işleme programına içe aktarılması için seçenekler sağlar."
type: docs
weight: 21
url: /tr/nodejs-java/com.groupdocs.merger.domain.options/olewordprocessingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleWordProcessingOptions](../../com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions)
```
public class OleWordProcessingOptions extends ImportDocumentOptions implements IOleWordProcessingOptions
```

OLE aracılığıyla gömülü belgenin Word işleme programına içe aktarılması için seçenekler sağlar.

--------------------

**Learn more**

 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]


[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleWordProcessingOptions-byte---byte---java.lang.String-int-) | Yeni bir [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) sınıfı örneğini başlatır. |
| [OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)](#OleWordProcessingOptions-java.lang.String-byte---int-) | Yeni bir [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) sınıfı örneğini başlatır. |
| [OleWordProcessingOptions(String filePath, int pageNumber)](#OleWordProcessingOptions-java.lang.String-int-) | Yeni bir [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) sınıfı örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLeft()](#getLeft--) | Ole nesne görüntüsünün sol koordinatı. |
| [setLeft(int value)](#setLeft-int-) | Ole nesne görüntüsünün sol koordinatı. |
| [getTop()](#getTop--) | Ole nesne görüntüsünün üst koordinatı. |
| [setTop(int value)](#setTop-int-) | Ole nesne görüntüsünün üst koordinatı. |
| [getWidth()](#getWidth--) | Ole nesne görüntüsünün genişliği. |
| [setWidth(int value)](#setWidth-int-) | Ole nesne görüntüsünün genişliği. |
| [getHeight()](#getHeight--) | Ole nesne görüntüsünün yüksekliği. |
| [setHeight(int value)](#setHeight-int-) | Ole nesne görüntüsünün yüksekliği. |
| [getImageData()](#getImageData--) | Ole nesne görüntüsünün verileri. |
### OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleWordProcessingOptions-byte---byte---java.lang.String-int-}
```
public OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Yeni bir [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| objectData | byte[] | Yerleştirilmiş nesnenin verileri. |
| imageData | byte[] | Yerleştirilmiş nesnenin görüntü verileri. |
| uzantı | java.lang.String | Yerleştirilmiş nesnenin uzantısı. |
| pageNumber | int | Gömülü nesneyi eklemek için sayfa numarası. |

### OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber) {#OleWordProcessingOptions-java.lang.String-byte---int-}
```
public OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)
```


Yeni bir [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Gömülü nesnenin dosya yolu. |
| imageData | byte[] | Yerleştirilmiş nesnenin görüntü verileri. |
| pageNumber | int | Gömülü nesneyi eklemek için sayfa numarası. |

### OleWordProcessingOptions(String filePath, int pageNumber) {#OleWordProcessingOptions-java.lang.String-int-}
```
public OleWordProcessingOptions(String filePath, int pageNumber)
```


Yeni bir [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Gömülü nesnenin dosya yolu. |
| pageNumber | int | Gömülü nesneyi eklemek için sayfa numarası. |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Ole nesne görüntüsünün sol koordinatı.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Ole nesne görüntüsünün sol koordinatı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Ole nesne görüntüsünün üst koordinatı.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Ole nesne görüntüsünün üst koordinatı.

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
