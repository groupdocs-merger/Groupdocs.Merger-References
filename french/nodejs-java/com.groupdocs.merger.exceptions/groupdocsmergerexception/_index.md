---
title: "GroupDocsMergerException"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Représente les erreurs qui se produisent lors du traitement du document."
type: docs
weight: 12
url: /fr/nodejs-java/com.groupdocs.merger.exceptions/groupdocsmergerexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception
```
public class GroupDocsMergerException extends Exception
```

Représente les erreurs qui se produisent lors du traitement du document.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GroupDocsMergerException(String message)](#GroupDocsMergerException-java.lang.String-) | Initialise une nouvelle instance de la classe [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception). |
| [GroupDocsMergerException(String message, Exception innerException)](#GroupDocsMergerException-java.lang.String-java.lang.Exception-) | Initialise une nouvelle instance de la classe [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getException(Exception exception)](#getException-java.lang.Exception-) | Obtenez l'exception GroupDocs Merger à partir de l'exception d'entrée. |
### GroupDocsMergerException(String message) {#GroupDocsMergerException-java.lang.String-}
```
public GroupDocsMergerException(String message)
```


Initialise une nouvelle instance de la classe [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message qui décrit l'erreur. |

### GroupDocsMergerException(String message, Exception innerException) {#GroupDocsMergerException-java.lang.String-java.lang.Exception-}
```
public GroupDocsMergerException(String message, Exception innerException)
```


Initialise une nouvelle instance de la classe [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message qui décrit l'erreur. |
| innerException | java.lang.Exception | L'exception interne de l'erreur. |

### getException(Exception exception) {#getException-java.lang.Exception-}
```
public static Exception getException(Exception exception)
```


Obtenez l'exception GroupDocs Merger à partir de l'exception d'entrée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| exception | java.lang.Exception | L'exception d'entrée. |

**Returns:**
java.lang.Exception -
