---
title: "Error"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Écrit un message d'erreur dans la console. Les messages du journal d'erreur fournissent des informations sur les événements irrécupérables dans le flux de l'application."
type: docs
weight: 20
url: /fr/net/groupdocs.merger.logging/consolelogger/error/
---
## ConsoleLogger.Error method

Écrit un message d'erreur dans la console. Les messages du journal d'erreur fournissent des informations sur les événements irrécupérables dans le flux de l'application.

```csharp
public void Error(string message, Exception exception)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| message | String | Le message d'erreur. |
| exception | Exception | L'exception. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancé lorsque *message* est nul. |
| ArgumentNullException | Levée lorsque *exception* est nulle. |

### Voir aussi

* class [ConsoleLogger](../../consolelogger)
* namespace [GroupDocs.Merger.Logging](../../../groupdocs.merger.logging)
* assembly [GroupDocs.Merger](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
