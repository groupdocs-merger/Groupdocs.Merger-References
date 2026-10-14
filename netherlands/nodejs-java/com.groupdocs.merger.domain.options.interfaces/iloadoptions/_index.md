---
title: "ILoadOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Interface voor de opties voor het laden van documenten."
type: docs
weight: 15
url: /nl/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iloadoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ILoadOptions extends IOptions
```

Interface voor de opties voor het laden van documenten.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Het type van het bestand om te openen. |
| [getPassword()](#getPassword--) | Het wachtwoord om een wachtwoordbeveiligd bestand te openen. |
| [getExtension()](#getExtension--) | De extensie van het bestand om te openen. |
| [getEncoding()](#getEncoding--) | De codering die wordt gebruikt bij het openen van tekstgebaseerde bestanden zoals [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) of [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### getType() {#getType--}
```
public abstract FileType getType()
```


Het type van het bestand om te openen.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


Het wachtwoord om een wachtwoordbeveiligd bestand te openen.

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


De extensie van het bestand om te openen.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public abstract Charset getEncoding()
```


De codering die wordt gebruikt bij het openen van tekstgebaseerde bestanden zoals [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) of [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). Standaardwaarde is [DefaultCharset][].


[DefaultCharset]: https://docs.oracle.com/javase/7/docs/api/java/nio/charset/Charset.html#defaultCharset%28%29

**Returns:**
java.nio.charset.Charset
