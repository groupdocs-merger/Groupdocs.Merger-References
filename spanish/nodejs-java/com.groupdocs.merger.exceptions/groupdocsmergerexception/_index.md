---
title: "GroupDocsMergerException"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Representa errores que ocurren durante el procesamiento de documentos."
type: docs
weight: 12
url: /es/nodejs-java/com.groupdocs.merger.exceptions/groupdocsmergerexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception
```
public class GroupDocsMergerException extends Exception
```

Representa errores que ocurren durante el procesamiento de documentos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GroupDocsMergerException(String message)](#GroupDocsMergerException-java.lang.String-) | Inicializa una nueva instancia de la clase [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception). |
| [GroupDocsMergerException(String message, Exception innerException)](#GroupDocsMergerException-java.lang.String-java.lang.Exception-) | Inicializa una nueva instancia de la clase [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getException(Exception exception)](#getException-java.lang.Exception-) | Obtén la excepción GroupDocs Merger de la excepción de entrada. |
### GroupDocsMergerException(String message) {#GroupDocsMergerException-java.lang.String-}
```
public GroupDocsMergerException(String message)
```


Inicializa una nueva instancia de la clase [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje que describe el error. |

### GroupDocsMergerException(String message, Exception innerException) {#GroupDocsMergerException-java.lang.String-java.lang.Exception-}
```
public GroupDocsMergerException(String message, Exception innerException)
```


Inicializa una nueva instancia de la clase [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje que describe el error. |
| innerException | java.lang.Exception | La excepción interna del error. |

### getException(Exception exception) {#getException-java.lang.Exception-}
```
public static Exception getException(Exception exception)
```


Obtén la excepción GroupDocs Merger de la excepción de entrada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| excepción | java.lang.Exception | La excepción de entrada. |

**Returns:**
java.lang.Exception -
