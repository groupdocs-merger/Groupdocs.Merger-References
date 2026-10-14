---
title: "OlePresentationOptions"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Παρέχει επιλογές για την εισαγωγή του ενσωματωμένου εγγράφου στην Παρουσίαση μέσω OLE."
type: docs
weight: 19
url: /el/nodejs-java/com.groupdocs.merger.domain.options/olepresentationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOlePresentationOptions](../../com.groupdocs.merger.domain.options.interfaces/iolepresentationoptions)
```
public class OlePresentationOptions extends ImportDocumentOptions implements IOlePresentationOptions
```

Παρέχει επιλογές για την εισαγωγή του ενσωματωμένου εγγράφου στην Παρουσίαση μέσω OLE.

--------------------

**Learn more**

 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]


[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [OlePresentationOptions(byte[] objectData, String extension, int pageNumber)](#OlePresentationOptions-byte---java.lang.String-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions). |
| [OlePresentationOptions(String filePath, int pageNumber)](#OlePresentationOptions-java.lang.String-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getX()](#getX--) | Η συντεταγμένη X του ενσωματωμένου πλαισίου αντικειμένου. |
| [setX(int value)](#setX-int-) | Η συντεταγμένη X του ενσωματωμένου πλαισίου αντικειμένου. |
| [getY()](#getY--) | Η συντεταγμένη Y του ενσωματωμένου πλαισίου αντικειμένου. |
| [setY(int value)](#setY-int-) | Η συντεταγμένη Y του ενσωματωμένου πλαισίου αντικειμένου. |
| [getWidth()](#getWidth--) | Το πλάτος του πλαισίου του ενσωματωμένου αντικειμένου. |
| [setWidth(int value)](#setWidth-int-) | Το πλάτος του πλαισίου του ενσωματωμένου αντικειμένου. |
| [getHeight()](#getHeight--) | Το ύψος του πλαισίου του ενσωματωμένου αντικειμένου. |
| [setHeight(int value)](#setHeight-int-) | Το ύψος του πλαισίου του ενσωματωμένου αντικειμένου. |
### OlePresentationOptions(byte[] objectData, String extension, int pageNumber) {#OlePresentationOptions-byte---java.lang.String-int-}
```
public OlePresentationOptions(byte[] objectData, String extension, int pageNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| objectData | byte[] | Τα δεδομένα του ενσωματωμένου αντικειμένου. |
| επέκταση | java.lang.String | Η επέκταση του ενσωματωμένου αντικειμένου. |
| pageNumber | int | Ο αριθμός σελίδας για την προσθήκη ενσωματωμένου αντικειμένου. |

### OlePresentationOptions(String filePath, int pageNumber) {#OlePresentationOptions-java.lang.String-int-}
```
public OlePresentationOptions(String filePath, int pageNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου του ενσωματωμένου αντικειμένου. |
| pageNumber | int | Ο αριθμός σελίδας για την προσθήκη ενσωματωμένου αντικειμένου. |

### getX() {#getX--}
```
public final int getX()
```


Η συντεταγμένη X του ενσωματωμένου πλαισίου αντικειμένου.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Η συντεταγμένη X του ενσωματωμένου πλαισίου αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


Η συντεταγμένη Y του ενσωματωμένου πλαισίου αντικειμένου.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Η συντεταγμένη Y του ενσωματωμένου πλαισίου αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Το πλάτος του πλαισίου του ενσωματωμένου αντικειμένου.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Το πλάτος του πλαισίου του ενσωματωμένου αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Το ύψος του πλαισίου του ενσωματωμένου αντικειμένου.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Το ύψος του πλαισίου του ενσωματωμένου αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

