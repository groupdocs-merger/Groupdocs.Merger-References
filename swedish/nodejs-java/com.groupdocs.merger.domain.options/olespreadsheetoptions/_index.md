---
title: "OleSpreadsheetOptions"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för import av inbäddat dokument till Kalkylblad via OLE."
type: docs
weight: 20
url: /sv/nodejs-java/com.groupdocs.merger.domain.options/olespreadsheetoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleSpreadsheetOptions](../../com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions)
```
public class OleSpreadsheetOptions extends ImportDocumentOptions implements IOleSpreadsheetOptions
```

Tillhandahåller alternativ för import av inbäddat dokument till Kalkylblad via OLE.

--------------------

**Learn more**

 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]


[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleSpreadsheetOptions-byte---byte---java.lang.String-int-) | Initierar en ny instans av klassen [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
| [OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-byte---int-) | Initierar en ny instans av klassen [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
| [OleSpreadsheetOptions(String filePath, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-int-) | Initierar en ny instans av klassen [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | Det övre vänstra radindexet. |
| [setRowIndex(int value)](#setRowIndex-int-) | Det övre vänstra radindexet. |
| [getColumnIndex()](#getColumnIndex--) | Det övre vänstra kolumnindexet. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | Det övre vänstra kolumnindexet. |
| [getWidth()](#getWidth--) | Bredden på Ole-objektets bild. |
| [setWidth(int value)](#setWidth-int-) | Bredden på Ole-objektets bild. |
| [getHeight()](#getHeight--) | Höjden på Ole-objektets bild. |
| [setHeight(int value)](#setHeight-int-) | Höjden på Ole-objektets bild. |
| [getImageData()](#getImageData--) | Data för Ole-objektets bild. |
### OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleSpreadsheetOptions-byte---byte---java.lang.String-int-}
```
public OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Initierar en ny instans av klassen [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objectData | byte[] | Data för det inbäddade objektet. |
| imageData | byte[] | Bilddata för det inbäddade objektet. |
| filändelse | java.lang.String | Filändelse för det inbäddade objektet. |
| pageNumber | int | Sidnumret för att lägga till ett inbäddat objekt. |

### OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-byte---int-}
```
public OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)
```


Initierar en ny instans av klassen [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen för det inbäddade objektet. |
| imageData | byte[] | Bilddata för det inbäddade objektet. |
| pageNumber | int | Sidnumret för att lägga till ett inbäddat objekt. |

### OleSpreadsheetOptions(String filePath, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-int-}
```
public OleSpreadsheetOptions(String filePath, int pageNumber)
```


Initierar en ny instans av klassen [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen för det inbäddade objektet. |
| pageNumber | int | Sidnumret för att lägga till ett inbäddat objekt. |

### getRowIndex() {#getRowIndex--}
```
public final int getRowIndex()
```


Det övre vänstra radindexet.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public final void setRowIndex(int value)
```


Det övre vänstra radindexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public final int getColumnIndex()
```


Det övre vänstra kolumnindexet.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public final void setColumnIndex(int value)
```


Det övre vänstra kolumnindexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Bredden på Ole-objektets bild.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Bredden på Ole-objektets bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Höjden på Ole-objektets bild.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Höjden på Ole-objektets bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Data för Ole-objektets bild.

**Returns:**
byte[]
