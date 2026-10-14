---
title: "ILoadOptions"
second_title: "GroupDocs.Merger Node.js için Java API Referansı"
description: "Belge yükleme seçenekleri için arabirim."
type: docs
weight: 15
url: /tr/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iloadoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ILoadOptions extends IOptions
```

Belge yükleme seçenekleri için arabirim.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Açılacak dosyanın türü. |
| [getPassword()](#getPassword--) | Şifre korumalı dosyayı açmak için şifre. |
| [getExtension()](#getExtension--) | Açılacak dosyanın uzantısı. |
| [getEncoding()](#getEncoding--) | Metin tabanlı dosyalar açılırken kullanılan kodlama, örneğin [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) veya [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### getType() {#getType--}
```
public abstract FileType getType()
```


Açılacak dosyanın türü.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


Şifre korumalı dosyayı açmak için şifre.

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


Açılacak dosyanın uzantısı.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public abstract Charset getEncoding()
```


Metin tabanlı dosyalar açılırken kullanılan kodlama, örneğin [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) veya [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). Varsayılan değer [DefaultCharset][].


[DefaultCharset]: https://docs.oracle.com/javase/7/docs/api/java/nio/charset/Charset.html#defaultCharset%28%29

**Returns:**
java.nio.charset.Charset
