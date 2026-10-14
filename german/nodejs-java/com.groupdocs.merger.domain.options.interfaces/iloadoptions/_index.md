---
title: "ILoadOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Schnittstelle für die Optionen zum Laden von Dokumenten."
type: docs
weight: 15
url: /de/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iloadoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ILoadOptions extends IOptions
```

Schnittstelle für die Optionen zum Laden von Dokumenten.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Der Typ der zu öffnenden Datei. |
| [getPassword()](#getPassword--) | Das Passwort zum Öffnen einer passwortgeschützten Datei. |
| [getExtension()](#getExtension--) | Die Erweiterung der zu öffnenden Datei. |
| [getEncoding()](#getEncoding--) | Die beim Öffnen von textbasierten Dateien wie [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) oder [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT) verwendete Kodierung. |
### getType() {#getType--}
```
public abstract FileType getType()
```


Der Typ der zu öffnenden Datei.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


Das Passwort zum Öffnen einer passwortgeschützten Datei.

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


Die Erweiterung der zu öffnenden Datei.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public abstract Charset getEncoding()
```


Die beim Öffnen von textbasierten Dateien wie [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) oder [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT) verwendete Kodierung. Der Standardwert ist [DefaultCharset][].


[DefaultCharset]: https://docs.oracle.com/javase/7/docs/api/java/nio/charset/Charset.html#defaultCharset%28%29

**Returns:**
java.nio.charset.Charset
