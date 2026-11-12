---
title: "Error"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Schreibt Fehlerprotokollnachricht Fehlerprotokollnachrichten liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf."
type: docs
weight: 10
url: /de/net/groupdocs.merger.logging/ilogger/error/
---
## ILogger.Error method

Schreibt Fehlermeldung; Fehlermeldungen liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf.

```csharp
public void Error(string message, Exception exception)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | String | Die Fehlermeldung. |
| Ausnahme | Exception | Die Ausnahme. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *message* null ist. |
| ArgumentNullException | Ausgelöst, wenn *exception* null ist. |

### Siehe auch

* interface [ILogger](../../ilogger)
* namespace [GroupDocs.Merger.Logging](../../../groupdocs.merger.logging)
* assembly [GroupDocs.Merger](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
