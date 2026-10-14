---
title: "ConsoleLogger"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Skriver loggmeddelanden till konsolen."
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.merger.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.logging.ILogger](../../com.groupdocs.merger.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

Skriver loggmeddelanden till konsolen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | Skriver spårningsmeddelande till konsolen. |
| [warning(String message)](#warning-java.lang.String-) | Skriver varningsmeddelande till konsolen. |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Skriver felmeddelande till konsolen. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Skriver spårningsmeddelande till konsolen. Spårningsloggmeddelanden ger allmänt användbar information om applikationsflödet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Spårningsmeddelandet. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Skriver varningsmeddelande till konsolen. Varningsloggmeddelanden ger information om oväntade och återhämtningsbara händelser i applikationsflödet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Varningsmeddelandet. |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Skriver felmeddelande till konsolen. Fel-loggmeddelanden ger information om oåterhämtningsbara händelser i applikationsflödet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String | Felmeddelandet. |
| undantag | java.lang.Exception | Undantaget. |

