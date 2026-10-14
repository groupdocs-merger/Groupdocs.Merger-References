---
title: "GroupDocsMergerException"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Rappresenta gli errori che si verificano durante l'elaborazione del documento."
type: docs
weight: 12
url: /it/nodejs-java/com.groupdocs.merger.exceptions/groupdocsmergerexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception
```
public class GroupDocsMergerException extends Exception
```

Rappresenta gli errori che si verificano durante l'elaborazione del documento.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GroupDocsMergerException(String message)](#GroupDocsMergerException-java.lang.String-) | Inizializza una nuova istanza della classe [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception). |
| [GroupDocsMergerException(String message, Exception innerException)](#GroupDocsMergerException-java.lang.String-java.lang.Exception-) | Inizializza una nuova istanza della classe [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getException(Exception exception)](#getException-java.lang.Exception-) | Ottieni l'eccezione GroupDocs Merger dall'eccezione di input. |
### GroupDocsMergerException(String message) {#GroupDocsMergerException-java.lang.String-}
```
public GroupDocsMergerException(String message)
```


Inizializza una nuova istanza della classe [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggio | java.lang.String | Il messaggio che descrive l'errore. |

### GroupDocsMergerException(String message, Exception innerException) {#GroupDocsMergerException-java.lang.String-java.lang.Exception-}
```
public GroupDocsMergerException(String message, Exception innerException)
```


Inizializza una nuova istanza della classe [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggio | java.lang.String | Il messaggio che descrive l'errore. |
| innerException | java.lang.Exception | L'eccezione interna dell'errore. |

### getException(Exception exception) {#getException-java.lang.Exception-}
```
public static Exception getException(Exception exception)
```


Ottieni l'eccezione GroupDocs Merger dall'eccezione di input.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| eccezione | java.lang.Exception | L'eccezione di input. |

**Returns:**
java.lang.Exception -
