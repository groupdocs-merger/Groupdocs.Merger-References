---
title: "GroupDocsMergerException"
second_title: "GroupDocs.Merger for Java API-referentie"
description: "Stelt fouten voor die optreden tijdens de documentverwerking."
type: docs
weight: 12
url: /nl/java/com.groupdocs.merger.exceptions/groupdocsmergerexception/
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
| [GroupDocsMergerException(String message)](#GroupDocsMergerException-java.lang.String-) | Initialiseert een nieuw exemplaar van de klasse [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception). |
| [GroupDocsMergerException(String message, Exception innerException)](#GroupDocsMergerException-java.lang.String-java.lang.Exception-) | Initialiseert een nieuw exemplaar van de klasse [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getException(Exception exception)](#getException-java.lang.Exception-) | Haal de GroupDocs Merger-exceptie op uit de invoerexceptie. |
### GroupDocsMergerException(String message) {#GroupDocsMergerException-java.lang.String-}
```
public GroupDocsMergerException(String message)
```


Initialiseert een nieuw exemplaar van de klasse [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | De boodschap die de fout beschrijft. |

### GroupDocsMergerException(String message, Exception innerException) {#GroupDocsMergerException-java.lang.String-java.lang.Exception-}
```
public GroupDocsMergerException(String message, Exception innerException)
```


Initialiseert een nieuw exemplaar van de klasse [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | De boodschap die de fout beschrijft. |
| innerException | java.lang.Exception | De interne exceptie van de fout. |

### getException(Exception exception) {#getException-java.lang.Exception-}
```
public static Exception getException(Exception exception)
```


Haal de GroupDocs Merger-exceptie op uit de invoerexceptie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| exceptie | java.lang.Exception | De invoerexceptie. |

**Returns:**
java.lang.Exception -
