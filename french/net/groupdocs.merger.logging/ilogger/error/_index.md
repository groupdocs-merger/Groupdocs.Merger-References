---
title: "Error"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Écrit le message du journal d'erreur. Les messages du journal d'erreur fournissent des informations sur les événements irrécupérables dans le flux de l'application."
type: docs
weight: 10
url: /fr/net/groupdocs.merger.logging/ilogger/error/
---
## ILogger.Error method

Écrit un message de journal d'erreur ; les messages de journal d'erreur fournissent des informations sur les événements irrécouvrables dans le flux de l'application.

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

* interface [ILogger](../../ilogger)
* namespace [GroupDocs.Merger.Logging](../../../groupdocs.merger.logging)
* assembly [GroupDocs.Merger](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
