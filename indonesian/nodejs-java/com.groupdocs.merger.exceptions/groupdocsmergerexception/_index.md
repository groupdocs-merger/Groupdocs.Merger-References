---
title: "GroupDocsMergerException"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Mewakili kesalahan yang terjadi selama pemrosesan dokumen."
type: docs
weight: 12
url: /id/nodejs-java/com.groupdocs.merger.exceptions/groupdocsmergerexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception
```
public class GroupDocsMergerException extends Exception
```

Mewakili kesalahan yang terjadi selama pemrosesan dokumen.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [GroupDocsMergerException(String message)](#GroupDocsMergerException-java.lang.String-) | Menginisialisasi sebuah instance baru dari kelas [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception). |
| [GroupDocsMergerException(String message, Exception innerException)](#GroupDocsMergerException-java.lang.String-java.lang.Exception-) | Menginisialisasi sebuah instance baru dari kelas [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getException(Exception exception)](#getException-java.lang.Exception-) | Dapatkan pengecualian GroupDocs Merger dari pengecualian input. |
### GroupDocsMergerException(String message) {#GroupDocsMergerException-java.lang.String-}
```
public GroupDocsMergerException(String message)
```


Menginisialisasi sebuah instance baru dari kelas [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pesan | java.lang.String | Pesan yang menjelaskan kesalahan. |

### GroupDocsMergerException(String message, Exception innerException) {#GroupDocsMergerException-java.lang.String-java.lang.Exception-}
```
public GroupDocsMergerException(String message, Exception innerException)
```


Menginisialisasi sebuah instance baru dari kelas [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pesan | java.lang.String | Pesan yang menjelaskan kesalahan. |
| innerException | java.lang.Exception | Pengecualian dalam dari kesalahan. |

### getException(Exception exception) {#getException-java.lang.Exception-}
```
public static Exception getException(Exception exception)
```


Dapatkan pengecualian GroupDocs Merger dari pengecualian input.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| eksepsi | java.lang.Exception | Pengecualian input. |

**Returns:**
java.lang.Exception -
