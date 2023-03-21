---
title: LoadOptions
second_title: GroupDocs.Merger for .NET API Reference
description: Αρχικοποιεί νέα παρουσία τουLoadOptionsgroupdocs.merger.domain.options/loadoptions τάξη.
type: docs
weight: 10
url: /el/net/groupdocs.merger.domain.options/loadoptions/loadoptions/
---
## LoadOptions(FileType) {#constructor}

Αρχικοποιεί νέα παρουσία του[`LoadOptions`](../../loadoptions) τάξη.

```csharp
public LoadOptions(FileType fileType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileType | FileType | Ο τύπος του αρχείου προς φόρτωση. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*fileType* είναι μηδενικό. |

### Δείτε επίσης

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../loadoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## LoadOptions(string) {#constructor_6}

Αρχικοποιεί νέα παρουσία του[`LoadOptions`](../../loadoptions) τάξη.

```csharp
public LoadOptions(string password)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| password | String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου που προστατεύεται με κωδικό πρόσβασης. |

### Δείτε επίσης

* class [LoadOptions](../../loadoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../loadoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## LoadOptions(string, Encoding) {#constructor_8}

Αρχικοποιεί νέα παρουσία του[`LoadOptions`](../../loadoptions) τάξη.

```csharp
public LoadOptions(string password, Encoding encoding)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| password | String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου που προστατεύεται με κωδικό πρόσβασης. |
| encoding | Encoding | Η κωδικοποίηση που χρησιμοποιείται κατά το άνοιγμα αρχείων που βασίζονται σε κείμενο, όπως π.χ[`CSV`](../../../groupdocs.merger.domain/filetype/csv) ή[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*encoding* είναι μηδενικό. |

### Δείτε επίσης

* class [LoadOptions](../../loadoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../loadoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string) {#constructor_4}

Αρχικοποιεί νέα παρουσία του[`LoadOptions`](../../loadoptions) τάξη.

```csharp
public LoadOptions(FileType fileType, string password)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileType | FileType | Ο τύπος του αρχείου προς φόρτωση. |
| password | String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου που προστατεύεται με κωδικό πρόσβασης. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*fileType* είναι μηδενικό. |

### Δείτε επίσης

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../loadoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string, Encoding) {#constructor_5}

Αρχικοποιεί νέα παρουσία του[`LoadOptions`](../../loadoptions) τάξη.

```csharp
public LoadOptions(FileType fileType, string password, Encoding encoding)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileType | FileType | Ο τύπος του αρχείου προς φόρτωση. |
| password | String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου που προστατεύεται με κωδικό πρόσβασης. |
| encoding | Encoding | Η κωδικοποίηση που χρησιμοποιείται κατά το άνοιγμα αρχείων που βασίζονται σε κείμενο, όπως π.χ[`CSV`](../../../groupdocs.merger.domain/filetype/csv) ή[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*fileType* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*encoding* είναι μηδενικό. |

### Δείτε επίσης

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../loadoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## LoadOptions(string, FileType, string, Encoding) {#constructor_7}

Αρχικοποιεί νέα παρουσία του[`LoadOptions`](../../loadoptions) τάξη.

```csharp
public LoadOptions(string extension, FileType fileType, string password, Encoding encoding)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| extension | String | Η επέκταση του αρχείου προς φόρτωση. |
| fileType | FileType | Ο τύπος του αρχείου προς φόρτωση. |
| password | String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου που προστατεύεται με κωδικό πρόσβασης. |
| encoding | Encoding | Η κωδικοποίηση που χρησιμοποιείται κατά το άνοιγμα αρχείων που βασίζονται σε κείμενο, όπως π.χ[`CSV`](../../../groupdocs.merger.domain/filetype/csv) ή[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*fileType* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*encoding* είναι μηδενικό. |

### Δείτε επίσης

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../loadoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string, Encoding) {#constructor_3}

Αρχικοποιεί νέα παρουσία του[`LoadOptions`](../../loadoptions) τάξη.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password, Encoding encoding)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| iniFileType | FileType | Ο τύπος του αρχείου που θα ξεκινήσει. |
| fileType | FileType | Ο τύπος του αρχείου προς φόρτωση. |
| password | String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου που προστατεύεται με κωδικό πρόσβασης. |
| encoding | Encoding | Η κωδικοποίηση που χρησιμοποιείται κατά το άνοιγμα αρχείων που βασίζονται σε κείμενο, όπως π.χ[`CSV`](../../../groupdocs.merger.domain/filetype/csv) ή[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*iniFileType* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*fileType* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*encoding* είναι μηδενικό. |

### Δείτε επίσης

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../loadoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string) {#constructor_2}

Αρχικοποιεί νέα παρουσία του[`LoadOptions`](../../loadoptions) τάξη.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| iniFileType | FileType | Ο τύπος του αρχείου που θα ξεκινήσει. |
| fileType | FileType | Ο τύπος του αρχείου προς φόρτωση. |
| password | String | Ο κωδικός πρόσβασης για το άνοιγμα αρχείου που προστατεύεται με κωδικό πρόσβασης. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*iniFileType* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*fileType* είναι μηδενικό. |

### Δείτε επίσης

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../loadoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType) {#constructor_1}

Αρχικοποιεί νέα παρουσία του[`LoadOptions`](../../loadoptions) τάξη.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| iniFileType | FileType | Ο τύπος του αρχείου που θα ξεκινήσει. |
| fileType | FileType | Ο τύπος του αρχείου προς φόρτωση. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*iniFileType* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*fileType* είναι μηδενικό. |

### Δείτε επίσης

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../loadoptions)
* συνέλευση [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
