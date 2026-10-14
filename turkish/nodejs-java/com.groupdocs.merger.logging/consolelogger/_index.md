---
title: "ConsoleLogger"
second_title: "GroupDocs.Merger Node.js için Java API Referansı"
description: "Günlük mesajlarını konsola yazar."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.merger.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.logging.ILogger](../../com.groupdocs.merger.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

Günlük mesajlarını konsola yazar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | İzleme mesajını konsola yazar. |
| [warning(String message)](#warning-java.lang.String-) | Uyarı mesajını konsola yazar. |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Hata mesajını konsola yazar. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


İzleme mesajını konsola yazar. İzleme günlük mesajları, uygulama akışı hakkında genellikle faydalı bilgiler sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | İzleme mesajı. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Uyarı mesajını konsola yazar. Uyarı günlük mesajları, uygulama akışındaki beklenmeyen ve kurtarılabilir olaylar hakkında bilgi sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | Uyarı mesajı. |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Hata mesajını konsola yazar. Hata günlük mesajları, uygulama akışındaki kurtarılamaz olaylar hakkında bilgi sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | Hata mesajı. |
| istisna | java.lang.Exception | İstisna. |

