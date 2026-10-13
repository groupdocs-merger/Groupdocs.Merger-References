---
title: "ConsoleLogger"
second_title: "GroupDocs.Merger για Java API Reference"
description: "Γράφει μηνύματα καταγραφής στην κονσόλα."
type: docs
weight: 10
url: /el/java/com.groupdocs.merger.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.logging.ILogger](../../com.groupdocs.merger.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

Γράφει μηνύματα καταγραφής στην κονσόλα.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | Γράφει μήνυμα ανίχνευσης στην κονσόλα. |
| [warning(String message)](#warning-java.lang.String-) | Γράφει προειδοποιητικό μήνυμα στην κονσόλα. |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Γράφει μήνυμα σφάλματος στην κονσόλα. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Γράφει μήνυμα ανίχνευσης στην κονσόλα. Τα μηνύματα καταγραφής ανίχνευσης παρέχουν γενικά χρήσιμες πληροφορίες σχετικά με τη ροή της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήνυμα | java.lang.String | Το μήνυμα ανίχνευσης. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Γράφει προειδοποιητικό μήνυμα στην κονσόλα. Τα προειδοποιητικά μηνύματα καταγραφής παρέχουν πληροφορίες για απρόσμενα και ανακτήσιμα γεγονότα στη ροή της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήνυμα | java.lang.String | Το προειδοποιητικό μήνυμα. |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Γράφει μήνυμα σφάλματος στην κονσόλα. Τα μηνύματα καταγραφής σφαλμάτων παρέχουν πληροφορίες για μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήνυμα | java.lang.String | Το μήνυμα σφάλματος. |
| εξαίρεση | java.lang.Exception | Η εξαίρεση. |

