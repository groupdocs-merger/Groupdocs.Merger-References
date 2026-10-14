---
title: "LoadOptions"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Παρέχει επιλογές για τη φόρτωση εγγράφων."
type: docs
weight: 16
url: /el/nodejs-java/com.groupdocs.merger.domain.options/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Παρέχει επιλογές για τη φόρτωση εγγράφων.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password, Charset encoding)](#LoadOptions-java.lang.String-java.nio.charset.Charset-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String extension, FileType fileType, String password, Charset encoding)](#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getType()](#getType--) | Ο τύπος του αρχείου για φόρτωση. |
| [getExtension()](#getExtension--) | Η επέκταση του αρχείου για αρχικοποίηση. |
| [getPassword()](#getPassword--) | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου προστατευμένου με κωδικό. |
| [getEncoding()](#getEncoding--) | Η κωδικοποίηση που χρησιμοποιείται κατά το άνοιγμα αρχείων κειμένου όπως [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) ή [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType fileType)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Ο τύπος του αρχείου για φόρτωση. |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κωδικός | java.lang.String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου προστατευμένου με κωδικό. |

### LoadOptions(String password, Charset encoding) {#LoadOptions-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String password, Charset encoding)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κωδικός | java.lang.String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου προστατευμένου με κωδικό. |
| encoding | java.nio.charset.Charset | Η κωδικοποίηση που χρησιμοποιείται κατά το άνοιγμα αρχείων κειμένου όπως [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) ή [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType fileType, String password)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Ο τύπος του αρχείου για φόρτωση. |
| κωδικός | java.lang.String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου προστατευμένου με κωδικό. |

### LoadOptions(FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType fileType, String password, Charset encoding)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Ο τύπος του αρχείου για φόρτωση. |
| κωδικός | java.lang.String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου προστατευμένου με κωδικό. |
| encoding | java.nio.charset.Charset | Η κωδικοποίηση που χρησιμοποιείται κατά το άνοιγμα αρχείων κειμένου όπως [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) ή [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(String extension, FileType fileType, String password, Charset encoding) {#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String extension, FileType fileType, String password, Charset encoding)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| επέκταση | java.lang.String | Η επέκταση του αρχείου για φόρτωση. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Ο τύπος του αρχείου για φόρτωση. |
| κωδικός | java.lang.String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου προστατευμένου με κωδικό. |
| encoding | java.nio.charset.Charset | Η κωδικοποίηση που χρησιμοποιείται κατά το άνοιγμα αρχείων κειμένου όπως [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) ή [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Ο τύπος του αρχείου για αρχικοποίηση. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Ο τύπος του αρχείου για φόρτωση. |
| κωδικός | java.lang.String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου προστατευμένου με κωδικό. |
| encoding | java.nio.charset.Charset | Η κωδικοποίηση που χρησιμοποιείται κατά το άνοιγμα αρχείων κειμένου όπως [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) ή [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Ο τύπος του αρχείου για αρχικοποίηση. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Ο τύπος του αρχείου για φόρτωση. |
| κωδικός | java.lang.String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου προστατευμένου με κωδικό. |

### LoadOptions(FileType iniFileType, FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType iniFileType, FileType fileType)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Ο τύπος του αρχείου για αρχικοποίηση. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Ο τύπος του αρχείου για φόρτωση. |

### getType() {#getType--}
```
public final FileType getType()
```


Ο τύπος του αρχείου για φόρτωση.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Η επέκταση του αρχείου για αρχικοποίηση.

**Returns:**
java.lang.String
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ο κωδικός πρόσβασης για το άνοιγμα αρχείου προστατευμένου με κωδικό.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Η κωδικοποίηση που χρησιμοποιείται κατά το άνοιγμα αρχείων κειμένου όπως [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) ή [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). Η προεπιλεγμένη τιμή είναι System.Text.Encoding.Default (java.nio.charset.Charset).

**Returns:**
java.nio.charset.Charset
