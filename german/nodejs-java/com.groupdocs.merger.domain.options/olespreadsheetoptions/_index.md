---
title: "OleSpreadsheetOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Bietet Optionen für den Import des eingebetteten Dokuments in Tabellenkalkulationen via OLE."
type: docs
weight: 20
url: /de/nodejs-java/com.groupdocs.merger.domain.options/olespreadsheetoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleSpreadsheetOptions](../../com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions)
```
public class OleSpreadsheetOptions extends ImportDocumentOptions implements IOleSpreadsheetOptions
```

Bietet Optionen für den Import des eingebetteten Dokuments in Tabellenkalkulationen via OLE.

--------------------

**Learn more**

 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]


[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleSpreadsheetOptions-byte---byte---java.lang.String-int-) | Initialisiert eine neue Instanz der Klasse [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
| [OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-byte---int-) | Initialisiert eine neue Instanz der Klasse [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
| [OleSpreadsheetOptions(String filePath, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-int-) | Initialisiert eine neue Instanz der Klasse [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | Der Index der oberen linken Zeile. |
| [setRowIndex(int value)](#setRowIndex-int-) | Der Index der oberen linken Zeile. |
| [getColumnIndex()](#getColumnIndex--) | Der Index der oberen linken Spalte. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | Der Index der oberen linken Spalte. |
| [getWidth()](#getWidth--) | Die Breite des Ole-Objektbildes. |
| [setWidth(int value)](#setWidth-int-) | Die Breite des Ole-Objektbildes. |
| [getHeight()](#getHeight--) | Die Höhe des Ole-Objektbildes. |
| [setHeight(int value)](#setHeight-int-) | Die Höhe des Ole-Objektbildes. |
| [getImageData()](#getImageData--) | Die Daten des Ole-Objektbildes. |
### OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleSpreadsheetOptions-byte---byte---java.lang.String-int-}
```
public OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Initialisiert eine neue Instanz der Klasse [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| objectData | byte[] | Die Daten des eingebetteten Objekts. |
| imageData | byte[] | Die Bilddaten des eingebetteten Objekts. |
| Erweiterung | java.lang.String | Die Erweiterung des eingebetteten Objekts. |
| pageNumber | int | Die Seitennummer zum Hinzufügen des eingebetteten Objekts. |

### OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-byte---int-}
```
public OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)
```


Initialisiert eine neue Instanz der Klasse [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad des eingebetteten Objekts. |
| imageData | byte[] | Die Bilddaten des eingebetteten Objekts. |
| pageNumber | int | Die Seitennummer zum Hinzufügen des eingebetteten Objekts. |

### OleSpreadsheetOptions(String filePath, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-int-}
```
public OleSpreadsheetOptions(String filePath, int pageNumber)
```


Initialisiert eine neue Instanz der Klasse [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad des eingebetteten Objekts. |
| pageNumber | int | Die Seitennummer zum Hinzufügen des eingebetteten Objekts. |

### getRowIndex() {#getRowIndex--}
```
public final int getRowIndex()
```


Der Index der oberen linken Zeile.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public final void setRowIndex(int value)
```


Der Index der oberen linken Zeile.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public final int getColumnIndex()
```


Der Index der oberen linken Spalte.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public final void setColumnIndex(int value)
```


Der Index der oberen linken Spalte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Die Breite des Ole-Objektbildes.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Die Breite des Ole-Objektbildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Die Höhe des Ole-Objektbildes.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Die Höhe des Ole-Objektbildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Die Daten des Ole-Objektbildes.

**Returns:**
byte[]
