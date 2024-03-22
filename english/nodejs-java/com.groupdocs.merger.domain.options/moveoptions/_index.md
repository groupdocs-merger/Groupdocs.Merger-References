---
title: MoveOptions
second_title: GroupDocs.Merger for Node.js via Java API Reference
description: Provides options for moving document page.
type: docs
weight: 17
url: /nodejs-java/com.groupdocs.merger.domain.options/moveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions)
```
public class MoveOptions implements IMoveOptions
```

Provides options for moving document page.
## Constructors

| Constructor | Description |
| --- | --- |
| [MoveOptions(int pageNumberToMove, int newPageNumber)](#MoveOptions-int-int-) | Initializes a new instance of the [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getPageNumberToMove()](#getPageNumberToMove--) | Gets or sets the page number to move. |
| [getNewPageNumber()](#getNewPageNumber--) | Gets or sets the new page number. |
### MoveOptions(int pageNumberToMove, int newPageNumber) {#MoveOptions-int-int-}
```
public MoveOptions(int pageNumberToMove, int newPageNumber)
```


Initializes a new instance of the [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumberToMove | int | The page number to move. |
| newPageNumber | int | The new page number. |

### getPageNumberToMove() {#getPageNumberToMove--}
```
public final int getPageNumberToMove()
```


Gets or sets the page number to move.

Value: The page number to move.

**Returns:**
int
### getNewPageNumber() {#getNewPageNumber--}
```
public final int getNewPageNumber()
```


Gets or sets the new page number.

Value: The new page number.

**Returns:**
int
