---
title: "Error"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Γράφει μήνυμα σφάλματος στην κονσόλα. Τα μηνύματα καταγραφής σφαλμάτων παρέχουν πληροφορίες για μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής."
type: docs
weight: 20
url: /el/net/groupdocs.merger.logging/consolelogger/error/
---
## ConsoleLogger.Error method

Γράφει μήνυμα σφάλματος στην κονσόλα. Τα μηνύματα καταγραφής σφαλμάτων παρέχουν πληροφορίες για μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής.

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

* class [ConsoleLogger](../../consolelogger)
* namespace [GroupDocs.Merger.Logging](../../../groupdocs.merger.logging)
* assembly [GroupDocs.Merger](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
