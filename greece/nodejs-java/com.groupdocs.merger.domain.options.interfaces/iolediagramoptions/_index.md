---
title: "IOleDiagramOptions"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Διεπαφή για επιλογές εισαγωγής του ενσωματωμένου εγγράφου σε Διάγραμμα μέσω OLE."
type: docs
weight: 17
url: /el/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleDiagramOptions extends IImportDocumentOptions, ISizeOptions
```

Διεπαφή για επιλογές εισαγωγής του ενσωματωμένου εγγράφου σε Διάγραμμα μέσω OLE.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getX()](#getX--) | Η X-συντεταγμένη του καρφίτσα του σχήματος του ενσωματωμένου αντικειμένου (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| [setX(int value)](#setX-int-) | Η X-συντεταγμένη του καρφίτσα του σχήματος του ενσωματωμένου αντικειμένου (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| [getY()](#getY--) | Η Y-συντεταγμένη του καρφίτσα του σχήματος του ενσωματωμένου αντικειμένου (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| [setY(int value)](#setY-int-) | Η Y-συντεταγμένη του καρφίτσα του σχήματος του ενσωματωμένου αντικειμένου (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| [getImageData()](#getImageData--) | Τα δεδομένα εικόνας του ενσωματωμένου αντικειμένου. |
### getX() {#getX--}
```
public abstract int getX()
```


Η X-συντεταγμένη του καρφίτσα του σχήματος του ενσωματωμένου αντικειμένου (κέντρο περιστροφής) σε σχέση με τη σελίδα.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


Η X-συντεταγμένη του καρφίτσα του σχήματος του ενσωματωμένου αντικειμένου (κέντρο περιστροφής) σε σχέση με τη σελίδα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


Η Y-συντεταγμένη του καρφίτσα του σχήματος του ενσωματωμένου αντικειμένου (κέντρο περιστροφής) σε σχέση με τη σελίδα.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


Η Y-συντεταγμένη του καρφίτσα του σχήματος του ενσωματωμένου αντικειμένου (κέντρο περιστροφής) σε σχέση με τη σελίδα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Τα δεδομένα εικόνας του ενσωματωμένου αντικειμένου.

**Returns:**
byte[]
