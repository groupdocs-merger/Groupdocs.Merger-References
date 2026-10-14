---
title: "OleSpreadsheetOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Biedt opties voor het importeren van het ingebedde document naar Spreadsheet via OLE."
type: docs
weight: 20
url: /nl/nodejs-java/com.groupdocs.merger.domain.options/olespreadsheetoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleSpreadsheetOptions](../../com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions)
```
public class OleSpreadsheetOptions extends ImportDocumentOptions implements IOleSpreadsheetOptions
```

Biedt opties voor het importeren van het ingebedde document naar Spreadsheet via OLE.

--------------------

**Learn more**

 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]


[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleSpreadsheetOptions-byte---byte---java.lang.String-int-) | Initialiseert een nieuw exemplaar van de klasse [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
| [OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-byte---int-) | Initialiseert een nieuw exemplaar van de klasse [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
| [OleSpreadsheetOptions(String filePath, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-int-) | Initialiseert een nieuw exemplaar van de klasse [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | De index van de bovenste linker rij. |
| [setRowIndex(int value)](#setRowIndex-int-) | De index van de bovenste linker rij. |
| [getColumnIndex()](#getColumnIndex--) | De index van de bovenste linker kolom. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | De index van de bovenste linker kolom. |
| [getWidth()](#getWidth--) | De breedte van de Ole-objectafbeelding. |
| [setWidth(int value)](#setWidth-int-) | De breedte van de Ole-objectafbeelding. |
| [getHeight()](#getHeight--) | De hoogte van de Ole-objectafbeelding. |
| [setHeight(int value)](#setHeight-int-) | De hoogte van de Ole-objectafbeelding. |
| [getImageData()](#getImageData--) | De gegevens van de Ole‑objectafbeelding. |
### OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleSpreadsheetOptions-byte---byte---java.lang.String-int-}
```
public OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Initialiseert een nieuw exemplaar van de klasse [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| objectData | byte[] | De gegevens van het ingesloten object. |
| imageData | byte[] | De afbeeldingsgegevens van het ingesloten object. |
| extensie | java.lang.String | De extensie van het ingesloten object. |
| pageNumber | int | Het paginanummer voor het toevoegen van een ingebed object. |

### OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-byte---int-}
```
public OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)
```


Initialiseert een nieuw exemplaar van de klasse [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad van het ingebedde object. |
| imageData | byte[] | De afbeeldingsgegevens van het ingesloten object. |
| pageNumber | int | Het paginanummer voor het toevoegen van een ingebed object. |

### OleSpreadsheetOptions(String filePath, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-int-}
```
public OleSpreadsheetOptions(String filePath, int pageNumber)
```


Initialiseert een nieuw exemplaar van de klasse [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad van het ingebedde object. |
| pageNumber | int | Het paginanummer voor het toevoegen van een ingebed object. |

### getRowIndex() {#getRowIndex--}
```
public final int getRowIndex()
```


De index van de bovenste linker rij.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public final void setRowIndex(int value)
```


De index van de bovenste linker rij.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public final int getColumnIndex()
```


De index van de bovenste linker kolom.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public final void setColumnIndex(int value)
```


De index van de bovenste linker kolom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


De breedte van de Ole-objectafbeelding.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


De breedte van de Ole-objectafbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


De hoogte van de Ole-objectafbeelding.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


De hoogte van de Ole-objectafbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


De gegevens van de Ole‑objectafbeelding.

**Returns:**
byte[]
