---
title: "ConsoleLogger"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Menulis pesan log ke konsol."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.merger.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.logging.ILogger](../../com.groupdocs.merger.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

Menulis pesan log ke konsol.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | Menulis pesan jejak ke konsol. |
| [warning(String message)](#warning-java.lang.String-) | Menulis pesan peringatan ke konsol. |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Menulis pesan kesalahan ke konsol. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Menulis pesan jejak ke konsol. Pesan log jejak menyediakan informasi yang umumnya berguna tentang alur aplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pesan | java.lang.String | Pesan jejak. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Menulis pesan peringatan ke konsol. Pesan log peringatan menyediakan informasi tentang kejadian tak terduga dan dapat dipulihkan dalam alur aplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pesan | java.lang.String | Pesan peringatan. |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Menulis pesan kesalahan ke konsol. Pesan log kesalahan menyediakan informasi tentang kejadian yang tidak dapat dipulihkan dalam alur aplikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pesan | java.lang.String | Pesan kesalahan. |
| eksepsi | java.lang.Exception | Eksepsi. |

