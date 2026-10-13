---
title: "GroupDocsMergerException"
second_title: "GroupDocs.Merger για Java API Reference"
description: "Αντιπροσωπεύει σφάλματα που εμφανίζονται κατά την επεξεργασία εγγράφων."
type: docs
weight: 12
url: /el/java/com.groupdocs.merger.exceptions/groupdocsmergerexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception
```
public class GroupDocsMergerException extends Exception
```

Αντιπροσωπεύει σφάλματα που εμφανίζονται κατά την επεξεργασία εγγράφων.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [GroupDocsMergerException(String message)](#GroupDocsMergerException-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) κλάσης. |
| [GroupDocsMergerException(String message, Exception innerException)](#GroupDocsMergerException-java.lang.String-java.lang.Exception-) | Αρχικοποιεί μια νέα παρουσία της [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) κλάσης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getException(Exception exception)](#getException-java.lang.Exception-) | Αποκτήστε την εξαίρεση GroupDocs Merger από την εξαίρεση εισόδου. |
### GroupDocsMergerException(String message) {#GroupDocsMergerException-java.lang.String-}
```
public GroupDocsMergerException(String message)
```


Αρχικοποιεί μια νέα παρουσία της [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήνυμα | java.lang.String | Το μήνυμα που περιγράφει το σφάλμα. |

### GroupDocsMergerException(String message, Exception innerException) {#GroupDocsMergerException-java.lang.String-java.lang.Exception-}
```
public GroupDocsMergerException(String message, Exception innerException)
```


Αρχικοποιεί μια νέα παρουσία της [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) κλάσης.

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
