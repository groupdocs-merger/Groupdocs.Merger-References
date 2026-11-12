---
title: "OleDiagramOptions"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Παρέχει επιλογές για την εισαγωγή του ενσωματωμένου εγγράφου στο Διάγραμμα μέσω OLE."
type: docs
weight: 18
url: /el/nodejs-java/com.groupdocs.merger.domain.options/olediagramoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleDiagramOptions](../../com.groupdocs.merger.domain.options.interfaces/iolediagramoptions)
```
public class OleDiagramOptions extends ImportDocumentOptions implements IOleDiagramOptions
```

Παρέχει επιλογές για την εισαγωγή του ενσωματωμένου εγγράφου στο Διάγραμμα μέσω OLE.

--------------------

**Learn more**

 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleDiagramOptions-byte---byte---java.lang.String-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
| [OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)](#OleDiagramOptions-java.lang.String-byte---int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
| [OleDiagramOptions(String filePath, int pageNumber)](#OleDiagramOptions-java.lang.String-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getX()](#getX--) | Η X-συντεταγμένη του καρφίτσα του σχήματος του ενσωματωμένου αντικειμένου (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| [setX(int value)](#setX-int-) | Η X-συντεταγμένη του καρφίτσα του σχήματος του ενσωματωμένου αντικειμένου (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| [getY()](#getY--) | Η Y-συντεταγμένη του καρφίτσα του σχήματος του ενσωματωμένου αντικειμένου (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| [setY(int value)](#setY-int-) | Η Y-συντεταγμένη του καρφίτσα του σχήματος του ενσωματωμένου αντικειμένου (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| [getWidth()](#getWidth--) | Το πλάτος του ενσωματωμένου σχήματος αντικειμένου σε ίντσες. |
| [setWidth(int value)](#setWidth-int-) | Το πλάτος του ενσωματωμένου σχήματος αντικειμένου σε ίντσες. |
| [getHeight()](#getHeight--) | Το ύψος του ενσωματωμένου σχήματος αντικειμένου σε ίντσες. |
| [setHeight(int value)](#setHeight-int-) | Το ύψος του ενσωματωμένου σχήματος αντικειμένου σε ίντσες. |
| [getImageData()](#getImageData--) | Τα δεδομένα εικόνας του ενσωματωμένου αντικειμένου. |
### OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleDiagramOptions-byte---byte---java.lang.String-int-}
```
public OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| objectData | byte[] | Τα δεδομένα του ενσωματωμένου αντικειμένου. |
| imageData | byte[] | Τα δεδομένα εικόνας του ενσωματωμένου αντικειμένου. |
| επέκταση | java.lang.String | Η επέκταση του ενσωματωμένου αντικειμένου. |
| pageNumber | int | Ο αριθμός σελίδας για την προσθήκη ενσωματωμένου αντικειμένου. |

### OleDiagramOptions(String filePath, byte[] imageData, int pageNumber) {#OleDiagramOptions-java.lang.String-byte---int-}
```
public OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου του ενσωματωμένου αντικειμένου. |
| imageData | byte[] | Τα δεδομένα εικόνας του ενσωματωμένου αντικειμένου. |
| pageNumber | int | Ο αριθμός σελίδας για την προσθήκη ενσωματωμένου αντικειμένου. |

### OleDiagramOptions(String filePath, int pageNumber) {#OleDiagramOptions-java.lang.String-int-}
```
public OleDiagramOptions(String filePath, int pageNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου του ενσωματωμένου αντικειμένου. |
| pageNumber | int | Ο αριθμός σελίδας για την προσθήκη ενσωματωμένου αντικειμένου. |

### getX() {#getX--}
```
public final int getX()
```


Η X-συντεταγμένη του καρφίτσα του σχήματος του ενσωματωμένου αντικειμένου (κέντρο περιστροφής) σε σχέση με τη σελίδα.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Η X-συντεταγμένη του καρφίτσα του σχήματος του ενσωματωμένου αντικειμένου (κέντρο περιστροφής) σε σχέση με τη σελίδα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


Η Y-συντεταγμένη του καρφίτσα του σχήματος του ενσωματωμένου αντικειμένου (κέντρο περιστροφής) σε σχέση με τη σελίδα.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Η Y-συντεταγμένη του καρφίτσα του σχήματος του ενσωματωμένου αντικειμένου (κέντρο περιστροφής) σε σχέση με τη σελίδα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Το πλάτος του ενσωματωμένου σχήματος αντικειμένου σε ίντσες.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Το πλάτος του ενσωματωμένου σχήματος αντικειμένου σε ίντσες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Το ύψος του ενσωματωμένου σχήματος αντικειμένου σε ίντσες.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Το ύψος του ενσωματωμένου σχήματος αντικειμένου σε ίντσες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Τα δεδομένα εικόνας του ενσωματωμένου αντικειμένου.

**Returns:**
byte[]
