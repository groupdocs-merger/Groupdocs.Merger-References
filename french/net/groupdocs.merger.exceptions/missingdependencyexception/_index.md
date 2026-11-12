---
title: "MissingDependencyException"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "L'exception qui est levée lorsqu'une opération ne peut pas s'exécuter parce qu'une assembly dont elle dépend n'est pas présente dans la sortie de l'application. Le document n'est pas en cause."
type: docs
weight: 900
url: /fr/net/groupdocs.merger.exceptions/missingdependencyexception/
---
## MissingDependencyException class

L'exception qui est levée lorsqu'une opération ne peut pas s'exécuter parce qu'une assembly dont elle dépend n'est pas présente dans la sortie de l'application. Le document n'est pas en cause.

```csharp
public sealed class MissingDependencyException : GroupDocsMergerException
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MissingDependencyException](missingdependencyexception#constructor)() | Initialise une nouvelle instance de la classe [`MissingDependencyException`](../missingdependencyexception). |
| [MissingDependencyException](missingdependencyexception#constructor_1)(string) | Initialise une nouvelle instance de la classe [`MissingDependencyException`](../missingdependencyexception). |
| [MissingDependencyException](missingdependencyexception#constructor_2)(string, Exception) | Initialise une nouvelle instance de la classe [`MissingDependencyException`](../missingdependencyexception). |
| [MissingDependencyException](missingdependencyexception#constructor_3)(string, string, Exception) | Initialise une nouvelle instance de la classe [`MissingDependencyException`](../missingdependencyexception) en nommant l'assembly qui n'a pas pu être chargé. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AssemblyName](../../groupdocs.merger.exceptions/missingdependencyexception/assemblyname) { get; } | Le nom simple de l'assembly qui n'a pas pu être chargé, ou null lorsqu'il n'a pas pu être déterminé. |

### Voir aussi

* class [GroupDocsMergerException](../groupdocsmergerexception)
* namespace [GroupDocs.Merger.Exceptions](../../groupdocs.merger.exceptions)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
