---
title: "ILoadOptions"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Gränssnitt för alternativ för att ladda dokument."
type: docs
weight: 15
url: /sv/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iloadoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ILoadOptions extends IOptions
```

Gränssnitt för alternativ för att ladda dokument.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getType()](#getType--) | Typen av filen som ska öppnas. |
| [getPassword()](#getPassword--) | Lösenordet för att öppna lösenordsskyddad fil. |
| [getExtension()](#getExtension--) | Filändelsen för filen som ska öppnas. |
| [getEncoding()](#getEncoding--) | Kodningen som används när textbaserade filer öppnas, såsom [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) eller [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### getType() {#getType--}
```
public abstract FileType getType()
```


Typen av filen som ska öppnas.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


Lösenordet för att öppna lösenordsskyddad fil.

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


Filändelsen för filen som ska öppnas.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public abstract Charset getEncoding()
```


Kodningen som används när textbaserade filer öppnas, såsom [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) eller [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). Standardvärdet är [DefaultCharset][].


[DefaultCharset]: https://docs.oracle.com/javase/7/docs/api/java/nio/charset/Charset.html#defaultCharset%28%29

**Returns:**
java.nio.charset.Charset
