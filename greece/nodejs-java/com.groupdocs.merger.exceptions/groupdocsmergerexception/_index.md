---
title: "GroupDocsMergerException"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Αναπαριστά σφάλματα που συμβαίνουν κατά την επεξεργασία εγγράφου."
type: docs
weight: 12
url: /el/nodejs-java/com.groupdocs.merger.exceptions/groupdocsmergerexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception
```
public class GroupDocsMergerException extends Exception
```

Αναπαριστά σφάλματα που συμβαίνουν κατά την επεξεργασία εγγράφου.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [GroupDocsMergerException(String message)](#GroupDocsMergerException-java.lang.String-) | Δημιουργεί μια νέα παρουσία της κλάσης [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception). |
| [GroupDocsMergerException(String message, Exception innerException)](#GroupDocsMergerException-java.lang.String-java.lang.Exception-) | Δημιουργεί μια νέα παρουσία της κλάσης [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getException(Exception exception)](#getException-java.lang.Exception-) | Αποκτήστε την εξαίρεση GroupDocs Merger από την εξαίρεση εισόδου. |
### GroupDocsMergerException(String message) {#GroupDocsMergerException-java.lang.String-}
```
public GroupDocsMergerException(String message)
```


Δημιουργεί μια νέα παρουσία της κλάσης [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήνυμα | java.lang.String | Το μήνυμα που περιγράφει το σφάλμα. |

### GroupDocsMergerException(String message, Exception innerException) {#GroupDocsMergerException-java.lang.String-java.lang.Exception-}
```
public GroupDocsMergerException(String message, Exception innerException)
```


Δημιουργεί μια νέα παρουσία της κλάσης [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήνυμα | java.lang.String | Το μήνυμα που περιγράφει το σφάλμα. |
| innerException | java.lang.Exception | Η εσωτερική εξαίρεση του σφάλματος. |

### getException(Exception exception) {#getException-java.lang.Exception-}
```
public static Exception getException(Exception exception)
```


Αποκτήστε την εξαίρεση GroupDocs Merger από την εξαίρεση εισόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εξαίρεση | java.lang.Exception | Η εξαίρεση εισόδου. |

**Returns:**
java.lang.Exception -
