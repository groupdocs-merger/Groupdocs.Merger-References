---
title: ExtractOptions
second_title: GroupDocs.Signature for Java API Reference
description: Provides options to extract the document pages.
type: docs
weight: 11
url: /java/com.groupdocs.merger.domain.options/extractoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IExtractOptions](../../com.groupdocs.merger.domain.options.interfaces/iextractoptions)
```
public class ExtractOptions extends PageOptions implements IExtractOptions
```

Provides options to extract the document pages.
## Constructors

| Constructor | Description |
| --- | --- |
| [ExtractOptions()](#ExtractOptions--) | Initializes a new instance of the [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) class. |
| [ExtractOptions(int[] pageNumbers)](#ExtractOptions-int---) | Initializes a new instance of the [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) class. |
| [ExtractOptions(int startNumber, int endNumber)](#ExtractOptions-int-int-) | Initializes a new instance of the [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) class. |
| [ExtractOptions(int startNumber, int endNumber, int mode)](#ExtractOptions-int-int-int-) | Initializes a new instance of the [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) class. |
### ExtractOptions() {#ExtractOptions--}
```
public ExtractOptions()
```


Initializes a new instance of the [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) class.

### ExtractOptions(int[] pageNumbers) {#ExtractOptions-int---}
```
public ExtractOptions(int[] pageNumbers)
```


Initializes a new instance of the [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumbers | int[] | Page numbers. |

### ExtractOptions(int startNumber, int endNumber) {#ExtractOptions-int-int-}
```
public ExtractOptions(int startNumber, int endNumber)
```


Initializes a new instance of the [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |

### ExtractOptions(int startNumber, int endNumber, int mode) {#ExtractOptions-int-int-int-}
```
public ExtractOptions(int startNumber, int endNumber, int mode)
```


Initializes a new instance of the [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |
| mode | int | The range mode. |

