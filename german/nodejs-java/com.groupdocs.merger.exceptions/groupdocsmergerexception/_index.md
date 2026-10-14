---
title: "GroupDocsMergerException"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Stellt Fehler dar, die bei der Dokumentenverarbeitung auftreten."
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.merger.exceptions/groupdocsmergerexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception
```
public class GroupDocsMergerException extends Exception
```

Stellt Fehler dar, die bei der Dokumentenverarbeitung auftreten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GroupDocsMergerException(String message)](#GroupDocsMergerException-java.lang.String-) | Initialisiert eine neue Instanz der [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) Klasse. |
| [GroupDocsMergerException(String message, Exception innerException)](#GroupDocsMergerException-java.lang.String-java.lang.Exception-) | Initialisiert eine neue Instanz der [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getException(Exception exception)](#getException-java.lang.Exception-) | Hole die GroupDocs Merger-Ausnahme von der Eingabeausnahme. |
### GroupDocsMergerException(String message) {#GroupDocsMergerException-java.lang.String-}
```
public GroupDocsMergerException(String message)
```


Initialisiert eine neue Instanz der [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Nachricht, die den Fehler beschreibt. |

### GroupDocsMergerException(String message, Exception innerException) {#GroupDocsMergerException-java.lang.String-java.lang.Exception-}
```
public GroupDocsMergerException(String message, Exception innerException)
```


Initialisiert eine neue Instanz der [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Nachricht, die den Fehler beschreibt. |
| innerException | java.lang.Exception | Die innere Ausnahme des Fehlers. |

### getException(Exception exception) {#getException-java.lang.Exception-}
```
public static Exception getException(Exception exception)
```


Hole die GroupDocs Merger-Ausnahme von der Eingabeausnahme.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ausnahme | java.lang.Exception | Die Eingabeausnahme. |

**Returns:**
java.lang.Exception -
