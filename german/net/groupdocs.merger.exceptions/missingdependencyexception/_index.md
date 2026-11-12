---
title: "MissingDependencyException"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Die Ausnahme, die ausgelöst wird, wenn ein Vorgang nicht ausgeführt werden kann, weil eine Assembly, von der er abhängt, nicht in der Ausgabe der Anwendung vorhanden ist. Das Dokument ist nicht schuld."
type: docs
weight: 900
url: /de/net/groupdocs.merger.exceptions/missingdependencyexception/
---
## MissingDependencyException class

Die Ausnahme, die ausgelöst wird, wenn ein Vorgang nicht ausgeführt werden kann, weil eine abhängige Assembly nicht im Ausgabeverzeichnis der Anwendung vorhanden ist. Das Dokument ist nicht schuld.

```csharp
public sealed class MissingDependencyException : GroupDocsMergerException
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MissingDependencyException](missingdependencyexception#constructor)() | Initialisiert eine neue Instanz der [`MissingDependencyException`](../missingdependencyexception)-Klasse. |
| [MissingDependencyException](missingdependencyexception#constructor_1)(string) | Initialisiert eine neue Instanz der [`MissingDependencyException`](../missingdependencyexception)-Klasse. |
| [MissingDependencyException](missingdependencyexception#constructor_2)(string, Exception) | Initialisiert eine neue Instanz der [`MissingDependencyException`](../missingdependencyexception)-Klasse. |
| [MissingDependencyException](missingdependencyexception#constructor_3)(string, string, Exception) | Initialisiert eine neue Instanz der [`MissingDependencyException`](../missingdependencyexception)-Klasse und benennt die Assembly, die nicht geladen werden konnte. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AssemblyName](../../groupdocs.merger.exceptions/missingdependencyexception/assemblyname) { get; } | Der einfache Name der Assembly, die nicht geladen werden konnte, oder null, wenn er nicht bestimmt werden konnte. |

### Siehe auch

* class [GroupDocsMergerException](../groupdocsmergerexception)
* namespace [GroupDocs.Merger.Exceptions](../../groupdocs.merger.exceptions)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
