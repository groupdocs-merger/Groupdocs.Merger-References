---
title: "ILoadOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Interfaccia per le opzioni di caricamento del documento."
type: docs
weight: 15
url: /it/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iloadoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ILoadOptions extends IOptions
```

Interfaccia per le opzioni di caricamento del documento.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Il tipo del file da aprire. |
| [getPassword()](#getPassword--) | La password per aprire il file protetto da password. |
| [getExtension()](#getExtension--) | L'estensione del file da aprire. |
| [getEncoding()](#getEncoding--) | La codifica utilizzata durante l'apertura di file basati su testo come [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) o [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### getType() {#getType--}
```
public abstract FileType getType()
```


Il tipo del file da aprire.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


La password per aprire il file protetto da password.

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


L'estensione del file da aprire.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public abstract Charset getEncoding()
```


La codifica utilizzata durante l'apertura di file basati su testo come [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) o [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). Il valore predefinito è [DefaultCharset][].


[DefaultCharset]: https://docs.oracle.com/javase/7/docs/api/java/nio/charset/Charset.html#defaultCharset%28%29

**Returns:**
java.nio.charset.Charset
