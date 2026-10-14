---
title: "GroupDocsMergerException"
second_title: "GroupDocs.Merger Node.js için Java API Referansı"
description: "Belge işleme sırasında oluşan hataları temsil eder."
type: docs
weight: 12
url: /tr/nodejs-java/com.groupdocs.merger.exceptions/groupdocsmergerexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception
```
public class GroupDocsMergerException extends Exception
```

Belge işleme sırasında oluşan hataları temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GroupDocsMergerException(String message)](#GroupDocsMergerException-java.lang.String-) | Yeni bir [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) sınıfı örneği başlatır. |
| [GroupDocsMergerException(String message, Exception innerException)](#GroupDocsMergerException-java.lang.String-java.lang.Exception-) | Yeni bir [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getException(Exception exception)](#getException-java.lang.Exception-) | Girdi istisnasından GroupDocs Merger istisnasını al. |
### GroupDocsMergerException(String message) {#GroupDocsMergerException-java.lang.String-}
```
public GroupDocsMergerException(String message)
```


Yeni bir [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | Hata açıklamasını içeren mesaj. |

### GroupDocsMergerException(String message, Exception innerException) {#GroupDocsMergerException-java.lang.String-java.lang.Exception-}
```
public GroupDocsMergerException(String message, Exception innerException)
```


Yeni bir [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | Hata açıklamasını içeren mesaj. |
| innerException | java.lang.Exception | Hatanın iç istisnası. |

### getException(Exception exception) {#getException-java.lang.Exception-}
```
public static Exception getException(Exception exception)
```


Girdi istisnasından GroupDocs Merger istisnasını al.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| istisna | java.lang.Exception | Girdi istisnası. |

**Returns:**
java.lang.Exception -
