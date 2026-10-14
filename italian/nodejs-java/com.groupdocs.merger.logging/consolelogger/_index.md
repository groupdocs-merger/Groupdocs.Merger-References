---
title: "ConsoleLogger"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Scrive messaggi di log sulla console."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.merger.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.logging.ILogger](../../com.groupdocs.merger.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

Scrive messaggi di log sulla console.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | Scrive un messaggio di traccia sulla console. |
| [warning(String message)](#warning-java.lang.String-) | Scrive un messaggio di avviso sulla console. |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Scrive un messaggio di errore sulla console. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Scrive un messaggio di traccia sulla console. I messaggi di log di traccia forniscono informazioni generalmente utili sul flusso dell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggio | java.lang.String | Il messaggio di traccia. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Scrive un messaggio di avviso sulla console. I messaggi di log di avviso forniscono informazioni su eventi inaspettati e recuperabili nel flusso dell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggio | java.lang.String | Il messaggio di avviso. |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Scrive un messaggio di errore sulla console. I messaggi di log di errore forniscono informazioni su eventi non recuperabili nel flusso dell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggio | java.lang.String | Il messaggio di errore. |
| eccezione | java.lang.Exception | L'eccezione. |

