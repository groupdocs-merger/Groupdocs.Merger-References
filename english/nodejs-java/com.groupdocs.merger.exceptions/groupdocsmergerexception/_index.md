---
title: GroupDocsMergerException
second_title: GroupDocs.Merger for Node.js via Java API Reference
description: Represents errors that occur during document processing.
type: docs
weight: 12
url: /nodejs-java/com.groupdocs.merger.exceptions/groupdocsmergerexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception
```
public class GroupDocsMergerException extends Exception
```

Represents errors that occur during document processing.
## Constructors

| Constructor | Description |
| --- | --- |
| [GroupDocsMergerException(String message)](#GroupDocsMergerException-java.lang.String-) | Initializes a new instance of the [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) class. |
| [GroupDocsMergerException(String message, Exception innerException)](#GroupDocsMergerException-java.lang.String-java.lang.Exception-) | Initializes a new instance of the [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) class. |
## Methods

| Method | Description |
| --- | --- |
| [getException(Exception exception)](#getException-java.lang.Exception-) | Get the GroupDocs Merger exception from input exception. |
### GroupDocsMergerException(String message) {#GroupDocsMergerException-java.lang.String-}
```
public GroupDocsMergerException(String message)
```


Initializes a new instance of the [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message that describes the error.    |

### GroupDocsMergerException(String message, Exception innerException) {#GroupDocsMergerException-java.lang.String-java.lang.Exception-}
```
public GroupDocsMergerException(String message, Exception innerException)
```


Initializes a new instance of the [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message that describes the error. |
| innerException | java.lang.Exception | The inner exception of the error.    |

### getException(Exception exception) {#getException-java.lang.Exception-}
```
public static Exception getException(Exception exception)
```


Get the GroupDocs Merger exception from input exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| exception | java.lang.Exception | The input exception. |

**Returns:**
java.lang.Exception - 
