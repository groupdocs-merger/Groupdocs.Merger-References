---
title: "ILoadOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Interface pour les options de chargement du document."
type: docs
weight: 15
url: /fr/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iloadoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ILoadOptions extends IOptions
```

Interface pour les options de chargement du document.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Le type du fichier à ouvrir. |
| [getPassword()](#getPassword--) | Le mot de passe pour ouvrir le fichier protégé par mot de passe. |
| [getExtension()](#getExtension--) | L'extension du fichier à ouvrir. |
| [getEncoding()](#getEncoding--) | L'encodage utilisé lors de l'ouverture de fichiers texte tels que [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) ou [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### getType() {#getType--}
```
public abstract FileType getType()
```


Le type du fichier à ouvrir.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


Le mot de passe pour ouvrir le fichier protégé par mot de passe.

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


L'extension du fichier à ouvrir.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public abstract Charset getEncoding()
```


L'encodage utilisé lors de l'ouverture de fichiers texte tels que [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) ou [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). La valeur par défaut est [DefaultCharset][].


[DefaultCharset]: https://docs.oracle.com/javase/7/docs/api/java/nio/charset/Charset.html#defaultCharset%28%29

**Returns:**
java.nio.charset.Charset
