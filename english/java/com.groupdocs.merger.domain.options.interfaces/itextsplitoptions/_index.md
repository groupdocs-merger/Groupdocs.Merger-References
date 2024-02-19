---
title: ITextSplitOptions
second_title: GroupDocs.Merger for Java API Reference
description: Interface for the text splitting options.
type: docs
weight: 35
url: /java/com.groupdocs.merger.domain.options.interfaces/itextsplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ITextSplitOptions extends IOptions
```

Interface for the text splitting options.
## Methods

| Method | Description |
| --- | --- |
| [getLineNumbers()](#getLineNumbers--) | Line numbers for text splitting. |
| [getMode()](#getMode--) | Mode for text splitting. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Validates the split options. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Gets the full file path of splitted document by index with defined extension. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Delegate that defines method to create output split stream. |
### getLineNumbers() {#getLineNumbers--}
```
public abstract int[] getLineNumbers()
```


Line numbers for text splitting.

**Returns:**
int[]
### getMode() {#getMode--}
```
public abstract int getMode()
```


Mode for text splitting.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


Validates the split options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The file type of [FileType](../../com.groupdocs.merger.domain/filetype) class. |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public abstract String getPathByIndex(int index, String extension)
```


Gets the full file path of splitted document by index with defined extension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of splitted document. |
| extension | java.lang.String | Extension of file. |

**Returns:**
java.lang.String - The full file path.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public abstract SplitStreamFactory getSplitStreamFactory()
```


Delegate that defines method to create output split stream.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
