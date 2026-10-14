---
title: "ConsoleLogger"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Escribe mensajes de registro en la consola."
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.merger.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.logging.ILogger](../../com.groupdocs.merger.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

Escribe mensajes de registro en la consola.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | Escribe un mensaje de rastreo en la consola. |
| [warning(String message)](#warning-java.lang.String-) | Escribe un mensaje de advertencia en la consola. |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Escribe un mensaje de error en la consola. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Escribe un mensaje de rastreo en la consola. Los mensajes de registro de rastreo proporcionan información generalmente útil sobre el flujo de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje de rastreo. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Escribe un mensaje de advertencia en la consola. Los mensajes de registro de advertencia proporcionan información sobre eventos inesperados y recuperables en el flujo de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje de advertencia. |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Escribe un mensaje de error en la consola. Los mensajes de registro de error proporcionan información sobre eventos irrecuperables en el flujo de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje de error. |
| excepción | java.lang.Exception | La excepción. |

