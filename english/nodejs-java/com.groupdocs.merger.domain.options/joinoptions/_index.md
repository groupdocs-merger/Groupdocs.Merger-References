---
title: JoinOptions
second_title: GroupDocs.Merger for Node.js via Java API Reference
description: Provides options for the document joining.
type: docs
weight: 15
url: /nodejs-java/com.groupdocs.merger.domain.options/joinoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ijoinoptions)
```
public class JoinOptions implements IJoinOptions
```

Provides options for the document joining.
## Constructors

| Constructor | Description |
| --- | --- |
| [JoinOptions()](#JoinOptions--) | Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class. |
| [JoinOptions(FileType fileType)](#JoinOptions-com.groupdocs.merger.domain.FileType-) | Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | The type of the file to join. |
### JoinOptions() {#JoinOptions--}
```
public JoinOptions()
```


Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class.

### JoinOptions(FileType fileType) {#JoinOptions-com.groupdocs.merger.domain.FileType-}
```
public JoinOptions(FileType fileType)
```


Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The type of the file to join. |

### getType() {#getType--}
```
public final FileType getType()
```


The type of the file to join.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
