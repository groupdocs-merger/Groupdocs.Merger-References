---
title: "GroupDocsMergerException"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Stelt fouten voor die optreden tijdens de documentverwerking."
type: docs
weight: 12
url: /nl/nodejs-java/com.groupdocs.merger.exceptions/groupdocsmergerexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception
```
public class GroupDocsMergerException extends Exception
```

Stelt fouten voor die optreden tijdens de documentverwerking.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [GroupDocsMergerException(String message)](#GroupDocsMergerException-java.lang.String-) | Initialiseert een nieuw exemplaar van de [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) klasse. |
| [GroupDocsMergerException(String message, Exception innerException)](#GroupDocsMergerException-java.lang.String-java.lang.Exception-) | Initialiseert een nieuw exemplaar van de [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getException(Exception exception)](#getException-java.lang.Exception-) | Haal de GroupDocs Merger-exception op uit de invoer-exception. |
### GroupDocsMergerException(String message) {#GroupDocsMergerException-java.lang.String-}
```
public GroupDocsMergerException(String message)
```


Initialiseert een nieuw exemplaar van de [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het bericht dat de fout beschrijft. |

### GroupDocsMergerException(String message, Exception innerException) {#GroupDocsMergerException-java.lang.String-java.lang.Exception-}
```
public GroupDocsMergerException(String message, Exception innerException)
```


Initialiseert een nieuw exemplaar van de [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het bericht dat de fout beschrijft. |
| innerException | java.lang.Exception | De interne uitzondering van de fout. |

### getException(Exception exception) {#getException-java.lang.Exception-}
```
public static Exception getException(Exception exception)
```


Haal de GroupDocs Merger-exception op uit de invoer-exception.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| exceptie | java.lang.Exception | De invoer-exception. |

**Returns:**
java.lang.Exception -
