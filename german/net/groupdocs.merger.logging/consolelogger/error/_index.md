---
title: "Error"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Schreibt Fehlermeldung in die Konsole. Fehlermeldungen im Protokoll liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf."
type: docs
weight: 20
url: /de/net/groupdocs.merger.logging/consolelogger/error/
---
## ConsoleLogger.Error method

Schreibt Fehlermeldung in die Konsole. Fehlermeldungen im Protokoll liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf.

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

* class [ConsoleLogger](../../consolelogger)
* namespace [GroupDocs.Merger.Logging](../../../groupdocs.merger.logging)
* assembly [GroupDocs.Merger](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
