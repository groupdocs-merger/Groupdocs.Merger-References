---
title: SwapOptions
second_title: GroupDocs.Merger for Java API Reference
description: Provides options for swapping document pages.
type: docs
weight: 37
url: /java/com.groupdocs.merger.domain.options/swapoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISwapOptions](../../com.groupdocs.merger.domain.options.interfaces/iswapoptions)
```
public class SwapOptions implements ISwapOptions
```

Provides options for swapping document pages.
## Constructors

| Constructor | Description |
| --- | --- |
| [SwapOptions(int firstPageNumber, int secondPageNumber)](#SwapOptions-int-int-) | Initializes a new instance of the [SwapOptions](../../com.groupdocs.merger.domain.options/swapoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFirstPageNumber()](#getFirstPageNumber--) | First page number to exchange. |
| [getSecondPageNumber()](#getSecondPageNumber--) | Second page number to exchange. |
### SwapOptions(int firstPageNumber, int secondPageNumber) {#SwapOptions-int-int-}
```
public SwapOptions(int firstPageNumber, int secondPageNumber)
```


Initializes a new instance of the [SwapOptions](../../com.groupdocs.merger.domain.options/swapoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstPageNumber | int | The first page number. |
| secondPageNumber | int | The second page number. |

### getFirstPageNumber() {#getFirstPageNumber--}
```
public final int getFirstPageNumber()
```


First page number to exchange.

**Returns:**
int
### getSecondPageNumber() {#getSecondPageNumber--}
```
public final int getSecondPageNumber()
```


Second page number to exchange.

**Returns:**
int
