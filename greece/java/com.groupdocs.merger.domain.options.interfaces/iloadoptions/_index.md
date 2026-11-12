---
title: "ILoadOptions"
second_title: "GroupDocs.Merger για Java API Reference"
description: "Διεπαφή για τις επιλογές φόρτωσης εγγράφου."
type: docs
weight: 15
url: /el/java/com.groupdocs.merger.domain.options.interfaces/iloadoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ILoadOptions extends IOptions
```

Διεπαφή για τις επιλογές φόρτωσης εγγράφου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getType()](#getType--) | Ο τύπος του αρχείου προς άνοιγμα. |
| [getPassword()](#getPassword--) | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου με προστασία κωδικού. |
| [getExtension()](#getExtension--) | Η επέκταση του αρχείου προς άνοιγμα. |
| [getEncoding()](#getEncoding--) | Η κωδικοποίηση που χρησιμοποιείται κατά το άνοιγμα αρχείων κειμένου όπως [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) ή [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### getType() {#getType--}
```
public abstract FileType getType()
```


Ο τύπος του αρχείου προς άνοιγμα.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


Ο κωδικός πρόσβασης για το άνοιγμα αρχείου με προστασία κωδικού.

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


Η επέκταση του αρχείου προς άνοιγμα.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public abstract Charset getEncoding()
```


Η κωδικοποίηση που χρησιμοποιείται κατά το άνοιγμα αρχείων κειμένου όπως [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) ή [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). Η προεπιλεγμένη τιμή είναι [DefaultCharset][].


[DefaultCharset]: https://docs.oracle.com/javase/7/docs/api/java/nio/charset/Charset.html#defaultCharset%28%29

**Returns:**
java.nio.charset.Charset
