---
title: "LoadOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Fournit des options pour le chargement du document."
type: docs
weight: 16
url: /fr/nodejs-java/com.groupdocs.merger.domain.options/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Fournit des options pour le chargement du document.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-) | Initialise une nouvelle instance de la classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Initialise une nouvelle instance de la classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password, Charset encoding)](#LoadOptions-java.lang.String-java.nio.charset.Charset-) | Initialise une nouvelle instance de la classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-) | Initialise une nouvelle instance de la classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Initialise une nouvelle instance de la classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String extension, FileType fileType, String password, Charset encoding)](#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Initialise une nouvelle instance de la classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Initialise une nouvelle instance de la classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-) | Initialise une nouvelle instance de la classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Initialise une nouvelle instance de la classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Le type du fichier à charger. |
| [getExtension()](#getExtension--) | L'extension du fichier à initialiser. |
| [getPassword()](#getPassword--) | Le mot de passe pour ouvrir le fichier protégé par mot de passe. |
| [getEncoding()](#getEncoding--) | L'encodage utilisé lors de l'ouverture de fichiers texte tels que [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) ou [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType fileType)
```


Initialise une nouvelle instance de la classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier à charger. |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Initialise une nouvelle instance de la classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mot de passe | java.lang.String | Le mot de passe pour ouvrir le fichier protégé par mot de passe. |

### LoadOptions(String password, Charset encoding) {#LoadOptions-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String password, Charset encoding)
```


Initialise une nouvelle instance de la classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mot de passe | java.lang.String | Le mot de passe pour ouvrir le fichier protégé par mot de passe. |
| encoding | java.nio.charset.Charset | L'encodage utilisé lors de l'ouverture de fichiers texte tels que [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) ou [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType fileType, String password)
```


Initialise une nouvelle instance de la classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier à charger. |
| mot de passe | java.lang.String | Le mot de passe pour ouvrir le fichier protégé par mot de passe. |

### LoadOptions(FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType fileType, String password, Charset encoding)
```


Initialise une nouvelle instance de la classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier à charger. |
| mot de passe | java.lang.String | Le mot de passe pour ouvrir le fichier protégé par mot de passe. |
| encoding | java.nio.charset.Charset | L'encodage utilisé lors de l'ouverture de fichiers texte tels que [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) ou [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(String extension, FileType fileType, String password, Charset encoding) {#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String extension, FileType fileType, String password, Charset encoding)
```


Initialise une nouvelle instance de la classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | L'extension du fichier à charger. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier à charger. |
| mot de passe | java.lang.String | Le mot de passe pour ouvrir le fichier protégé par mot de passe. |
| encoding | java.nio.charset.Charset | L'encodage utilisé lors de l'ouverture de fichiers texte tels que [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) ou [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)
```


Initialise une nouvelle instance de la classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier à initialiser. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier à charger. |
| mot de passe | java.lang.String | Le mot de passe pour ouvrir le fichier protégé par mot de passe. |
| encoding | java.nio.charset.Charset | L'encodage utilisé lors de l'ouverture de fichiers texte tels que [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) ou [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password)
```


Initialise une nouvelle instance de la classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier à initialiser. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier à charger. |
| mot de passe | java.lang.String | Le mot de passe pour ouvrir le fichier protégé par mot de passe. |

### LoadOptions(FileType iniFileType, FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType iniFileType, FileType fileType)
```


Initialise une nouvelle instance de la classe [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier à initialiser. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier à charger. |

### getType() {#getType--}
```
public final FileType getType()
```


Le type du fichier à charger.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getExtension() {#getExtension--}
```
public final String getExtension()
```


L'extension du fichier à initialiser.

**Returns:**
java.lang.String
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Le mot de passe pour ouvrir le fichier protégé par mot de passe.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


L'encodage utilisé lors de l'ouverture de fichiers texte tels que [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) ou [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). La valeur par défaut est System.Text.Encoding.Default (java.nio.charset.Charset).

**Returns:**
java.nio.charset.Charset
