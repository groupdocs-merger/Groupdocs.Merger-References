---
title: ILoadOptions
second_title: GroupDocs.Merger for Java API Reference
description: Interface for the document loading options.
type: docs
weight: 15
url: /java/com.groupdocs.merger.domain.options.interfaces/iloadoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ILoadOptions extends IOptions
```

Interface for the document loading options.
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | The type of the file to open. |
| [getPassword()](#getPassword--) | The password for opening password-protected file. |
| [getExtension()](#getExtension--) | The extension of the file to open. |
| [getEncoding()](#getEncoding--) | The encoding used when opening text-based files such as [FileType\#CSV](../../com.groupdocs.merger.domain/filetype\#CSV) or [FileType\#TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### getType() {#getType--}
```
public abstract FileType getType()
```


The type of the file to open.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


The password for opening password-protected file.

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


The extension of the file to open.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public abstract Charset getEncoding()
```


The encoding used when opening text-based files such as [FileType\#CSV](../../com.groupdocs.merger.domain/filetype\#CSV) or [FileType\#TXT](../../com.groupdocs.merger.domain/filetype\#TXT). Default value is [DefaultCharset][].


[DefaultCharset]: https://docs.oracle.com/javase/7/docs/api/java/nio/charset/Charset.html#defaultCharset%28%29

**Returns:**
java.nio.charset.Charset
