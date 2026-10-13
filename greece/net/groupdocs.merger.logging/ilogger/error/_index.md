---
title: "Error"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Γράφει μήνυμα καταγραφής σφάλματος. Τα μηνύματα καταγραφής σφάλματος παρέχουν πληροφορίες για μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής."
type: docs
weight: 10
url: /el/net/groupdocs.merger.logging/ilogger/error/
---
## ILogger.Error method

Γράφει μήνυμα καταγραφής σφάλματος· Τα μηνύματα καταγραφής σφάλματος παρέχουν πληροφορίες σχετικά με μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής.

```csharp
public void Error(string message, Exception exception)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| message | String | Το μήνυμα σφάλματος. |
| εξαίρεση | Exception | Η εξαίρεση. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *message* είναι null. |
| ArgumentNullException | Ρίχνεται όταν η *exception* είναι null. |

### Δείτε επίσης

* interface [ILogger](../../ilogger)
* namespace [GroupDocs.Merger.Logging](../../../groupdocs.merger.logging)
* assembly [GroupDocs.Merger](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
