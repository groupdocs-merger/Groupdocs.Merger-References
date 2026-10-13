---
title: "LoadOptions"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Αρχικοποιεί νέα παρουσία της LoadOptionsgroupdocs.merger.domain.options/loadoptions κλάσης."
type: docs
weight: 10
url: /el/net/groupdocs.merger.domain.options/loadoptions/loadoptions/
---
## LoadOptions(FileType) {#constructor}

Αρχικοποιεί νέα παρουσία της [`LoadOptions`](../../loadoptions) κλάσης.

```csharp
public LoadOptions(FileType fileType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileType | FileType | Ο τύπος του αρχείου για φόρτωση. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Πετάγεται όταν *fileType* είναι null. |

### Δείτε επίσης

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string) {#constructor_6}

Αρχικοποιεί νέα παρουσία της [`LoadOptions`](../../loadoptions) κλάσης.

```csharp
public LoadOptions(string password)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κωδικός πρόσβασης | String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου προστατευμένου με κωδικό. |

### Δείτε επίσης

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string, Encoding) {#constructor_8}

Αρχικοποιεί νέα παρουσία της [`LoadOptions`](../../loadoptions) κλάσης.

```csharp
public LoadOptions(string password, Encoding encoding)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κωδικός πρόσβασης | String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου προστατευμένου με κωδικό. |
| encoding | Encoding | Η κωδικοποίηση που χρησιμοποιείται κατά το άνοιγμα αρχείων κειμένου όπως [`CSV`](../../../groupdocs.merger.domain/filetype/csv) ή [`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Πετάγεται όταν *encoding* είναι null. |

### Δείτε επίσης

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string) {#constructor_4}

Αρχικοποιεί νέα παρουσία της [`LoadOptions`](../../loadoptions) κλάσης.

```csharp
public LoadOptions(FileType fileType, string password)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileType | FileType | Ο τύπος του αρχείου για φόρτωση. |
| κωδικός πρόσβασης | String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου προστατευμένου με κωδικό. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Πετάγεται όταν *fileType* είναι null. |

### Δείτε επίσης

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string, Encoding) {#constructor_5}

Αρχικοποιεί νέα παρουσία της [`LoadOptions`](../../loadoptions) κλάσης.

```csharp
public LoadOptions(FileType fileType, string password, Encoding encoding)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileType | FileType | Ο τύπος του αρχείου για φόρτωση. |
| κωδικός πρόσβασης | String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου προστατευμένου με κωδικό. |
| encoding | Encoding | Η κωδικοποίηση που χρησιμοποιείται κατά το άνοιγμα αρχείων κειμένου όπως [`CSV`](../../../groupdocs.merger.domain/filetype/csv) ή [`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Πετάγεται όταν *fileType* είναι null. |
| ArgumentNullException | Πετάγεται όταν *encoding* είναι null. |

### Δείτε επίσης

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string, FileType, string, Encoding) {#constructor_7}

Αρχικοποιεί νέα παρουσία της [`LoadOptions`](../../loadoptions) κλάσης.

```csharp
public LoadOptions(string extension, FileType fileType, string password, Encoding encoding)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| επέκταση | String | Η επέκταση του αρχείου προς φόρτωση. |
| fileType | FileType | Ο τύπος του αρχείου για φόρτωση. |
| κωδικός πρόσβασης | String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου προστατευμένου με κωδικό. |
| encoding | Encoding | Η κωδικοποίηση που χρησιμοποιείται κατά το άνοιγμα αρχείων κειμένου όπως [`CSV`](../../../groupdocs.merger.domain/filetype/csv) ή [`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Πετάγεται όταν *fileType* είναι null. |
| ArgumentNullException | Πετάγεται όταν *encoding* είναι null. |

### Δείτε επίσης

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string, Encoding) {#constructor_3}

Αρχικοποιεί νέα παρουσία της [`LoadOptions`](../../loadoptions) κλάσης.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password, Encoding encoding)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| iniFileType | FileType | Ο τύπος του αρχείου για αρχικοποίηση. |
| fileType | FileType | Ο τύπος του αρχείου για φόρτωση. |
| κωδικός πρόσβασης | String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου προστατευμένου με κωδικό. |
| encoding | Encoding | Η κωδικοποίηση που χρησιμοποιείται κατά το άνοιγμα αρχείων κειμένου όπως [`CSV`](../../../groupdocs.merger.domain/filetype/csv) ή [`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Πετάγεται όταν *iniFileType* είναι null. |
| ArgumentNullException | Πετάγεται όταν *fileType* είναι null. |
| ArgumentNullException | Πετάγεται όταν *encoding* είναι null. |

### Δείτε επίσης

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string) {#constructor_2}

Αρχικοποιεί νέα παρουσία της [`LoadOptions`](../../loadoptions) κλάσης.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| iniFileType | FileType | Ο τύπος του αρχείου για αρχικοποίηση. |
| fileType | FileType | Ο τύπος του αρχείου για φόρτωση. |
| κωδικός πρόσβασης | String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου προστατευμένου με κωδικό. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Πετάγεται όταν *iniFileType* είναι null. |
| ArgumentNullException | Πετάγεται όταν *fileType* είναι null. |

### Δείτε επίσης

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType) {#constructor_1}

Αρχικοποιεί νέα παρουσία της [`LoadOptions`](../../loadoptions) κλάσης.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| iniFileType | FileType | Ο τύπος του αρχείου για αρχικοποίηση. |
| fileType | FileType | Ο τύπος του αρχείου για φόρτωση. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Πετάγεται όταν *iniFileType* είναι null. |
| ArgumentNullException | Πετάγεται όταν *fileType* είναι null. |

### Δείτε επίσης

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
