---
title: "ConsoleLogger"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Schrijft logberichten naar de console."
type: docs
weight: 10
url: /nl/nodejs-java/com.groupdocs.merger.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.logging.ILogger](../../com.groupdocs.merger.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

Schrijft logberichten naar de console.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | Schrijft tracebericht naar de console. |
| [warning(String message)](#warning-java.lang.String-) | Schrijft waarschuwingsbericht naar de console. |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Schrijft foutbericht naar de console. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Schrijft tracebericht naar de console. Trace-logberichten bieden over het algemeen nuttige informatie over de applicatiestroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het tracebericht. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Schrijft waarschuwingsbericht naar de console. Waarschuwingslogberichten bieden informatie over onverwachte en herstelbare gebeurtenissen in de applicatiestroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het waarschuwingsbericht. |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Schrijft foutbericht naar de console. Foutlogberichten bieden informatie over onherstelbare gebeurtenissen in de applicatiestroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het foutbericht. |
| exceptie | java.lang.Exception | De exceptie. |

