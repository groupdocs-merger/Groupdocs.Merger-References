---
title: "ConsoleLogger"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Écrit les messages de journal dans la console."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.merger.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.logging.ILogger](../../com.groupdocs.merger.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

Écrit les messages de journal dans la console.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | Écrit un message de trace dans la console. |
| [warning(String message)](#warning-java.lang.String-) | Écrit un message d'avertissement dans la console. |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Écrit un message d'erreur dans la console. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Écrit un message de trace dans la console. Les messages de journal de trace fournissent des informations généralement utiles sur le flux de l'application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message de trace. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Écrit un message d'avertissement dans la console. Les messages de journal d'avertissement fournissent des informations sur les événements inattendus et récupérables dans le flux de l'application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message d'avertissement. |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Écrit un message d'erreur dans la console. Les messages de journal d'erreur fournissent des informations sur les événements irrécupérables dans le flux de l'application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message d'erreur. |
| exception | java.lang.Exception | L'exception. |

