---
title: Error
second_title: GroupDocs.Merger for .NET API Reference
description: Γράφει μήνυμα αρχείου καταγραφής σφαλμάτων. Τα μηνύματα καταγραφής σφαλμάτων παρέχουν πληροφορίες σχετικά με μη ανακτήσιμα συμβάντα στη ροή της εφαρμογής.
type: docs
weight: 10
url: /el/net/groupdocs.merger.logging/ilogger/error/
---
## ILogger.Error method

Γράφει μήνυμα αρχείου καταγραφής σφαλμάτων. Τα μηνύματα καταγραφής σφαλμάτων παρέχουν πληροφορίες σχετικά με μη ανακτήσιμα συμβάντα στη ροή της εφαρμογής.

```csharp
public void Error(string message, Exception exception)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| message | String | Το μήνυμα σφάλματος. |
| exception | Exception | Η εξαίρεση. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*message* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*exception* είναι μηδενικό. |

### Δείτε επίσης

* interface [ILogger](../../ilogger)
* χώρος ονομάτων [GroupDocs.Merger.Logging](../../ilogger)
* συνέλευση [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->