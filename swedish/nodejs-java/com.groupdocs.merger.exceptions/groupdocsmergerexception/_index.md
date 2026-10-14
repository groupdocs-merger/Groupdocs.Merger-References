---
title: "GroupDocsMergerException"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Representerar fel som uppstår under dokumentbehandling."
type: docs
weight: 12
url: /sv/nodejs-java/com.groupdocs.merger.exceptions/groupdocsmergerexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception
```
public class GroupDocsMergerException extends Exception
```

Representerar fel som uppstår under dokumentbehandling.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [GroupDocsMergerException(String message)](#GroupDocsMergerException-java.lang.String-) | Initierar en ny instans av klassen [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception). |
| [GroupDocsMergerException(String message, Exception innerException)](#GroupDocsMergerException-java.lang.String-java.lang.Exception-) | Initierar en ny instans av klassen [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getException(Exception exception)](#getException-java.lang.Exception-) | Hämta GroupDocs Merger‑undantaget från indataundantaget. |
### GroupDocsMergerException(String message) {#GroupDocsMergerException-java.lang.String-}
```
public GroupDocsMergerException(String message)
```


Initierar en ny instans av klassen [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Meddelandet som beskriver felet. |

### GroupDocsMergerException(String message, Exception innerException) {#GroupDocsMergerException-java.lang.String-java.lang.Exception-}
```
public GroupDocsMergerException(String message, Exception innerException)
```


Initierar en ny instans av klassen [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Meddelandet som beskriver felet. |
| innerException | java.lang.Exception | Det inre undantaget för felet. |

### getException(Exception exception) {#getException-java.lang.Exception-}
```
public static Exception getException(Exception exception)
```


Hämta GroupDocs Merger‑undantaget från indataundantaget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| undantag | java.lang.Exception | Inmatningsundantaget. |

**Returns:**
java.lang.Exception -
