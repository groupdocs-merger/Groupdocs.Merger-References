---
title: "ConsoleLogger"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Schreibt Protokollnachrichten in die Konsole."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.merger.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.logging.ILogger](../../com.groupdocs.merger.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

Schreibt Protokollnachrichten in die Konsole.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | Schreibt Trace-Nachricht in die Konsole. |
| [warning(String message)](#warning-java.lang.String-) | Schreibt Warnmeldung in die Konsole. |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Schreibt Fehlermeldung in die Konsole. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Schreibt Trace-Nachricht in die Konsole. Trace-Protokollnachrichten liefern allgemein nützliche Informationen über den Anwendungsablauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Trace-Nachricht. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Schreibt Warnmeldung in die Konsole. Warn-Protokollnachrichten liefern Informationen über unerwartete und wiederherstellbare Ereignisse im Anwendungsablauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Warnmeldung. |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Schreibt Fehlermeldung in die Konsole. Fehler-Protokollnachrichten liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Fehlermeldung. |
| Ausnahme | java.lang.Exception | Die Ausnahme. |

