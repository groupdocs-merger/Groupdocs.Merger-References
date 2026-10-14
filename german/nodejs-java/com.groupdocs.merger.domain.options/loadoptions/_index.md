---
title: "LoadOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Bietet Optionen für das Laden von Dokumenten."
type: docs
weight: 16
url: /de/nodejs-java/com.groupdocs.merger.domain.options/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Bietet Optionen für das Laden von Dokumenten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-) | Initialisiert eine neue Instanz der [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) Klasse. |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Initialisiert eine neue Instanz der [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) Klasse. |
| [LoadOptions(String password, Charset encoding)](#LoadOptions-java.lang.String-java.nio.charset.Charset-) | Initialisiert eine neue Instanz der [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) Klasse. |
| [LoadOptions(FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-) | Initialisiert eine neue Instanz der [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) Klasse. |
| [LoadOptions(FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Initialisiert eine neue Instanz der [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) Klasse. |
| [LoadOptions(String extension, FileType fileType, String password, Charset encoding)](#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Initialisiert eine neue Instanz der [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) Klasse. |
| [LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Initialisiert eine neue Instanz der [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) Klasse. |
| [LoadOptions(FileType iniFileType, FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-) | Initialisiert eine neue Instanz der [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) Klasse. |
| [LoadOptions(FileType iniFileType, FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Initialisiert eine neue Instanz der [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Der Typ der zu ladenden Datei. |
| [getExtension()](#getExtension--) | Die Erweiterung der Datei zum Initialisieren. |
| [getPassword()](#getPassword--) | Das Passwort zum Öffnen einer passwortgeschützten Datei. |
| [getEncoding()](#getEncoding--) | Die beim Öffnen von textbasierten Dateien wie [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) oder [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT) verwendete Kodierung. |
### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType fileType)
```


Initialisiert eine neue Instanz der [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu ladenden Datei. |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Initialisiert eine neue Instanz der [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Passwort | java.lang.String | Das Passwort zum Öffnen einer passwortgeschützten Datei. |

### LoadOptions(String password, Charset encoding) {#LoadOptions-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String password, Charset encoding)
```


Initialisiert eine neue Instanz der [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Passwort | java.lang.String | Das Passwort zum Öffnen einer passwortgeschützten Datei. |
| encoding | java.nio.charset.Charset | Die beim Öffnen von textbasierten Dateien wie [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) oder [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT) verwendete Kodierung. |

### LoadOptions(FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType fileType, String password)
```


Initialisiert eine neue Instanz der [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu ladenden Datei. |
| Passwort | java.lang.String | Das Passwort zum Öffnen einer passwortgeschützten Datei. |

### LoadOptions(FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType fileType, String password, Charset encoding)
```


Initialisiert eine neue Instanz der [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu ladenden Datei. |
| Passwort | java.lang.String | Das Passwort zum Öffnen einer passwortgeschützten Datei. |
| encoding | java.nio.charset.Charset | Die beim Öffnen von textbasierten Dateien wie [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) oder [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT) verwendete Kodierung. |

### LoadOptions(String extension, FileType fileType, String password, Charset encoding) {#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String extension, FileType fileType, String password, Charset encoding)
```


Initialisiert eine neue Instanz der [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Erweiterung | java.lang.String | Die Erweiterung der Datei zum Laden. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu ladenden Datei. |
| Passwort | java.lang.String | Das Passwort zum Öffnen einer passwortgeschützten Datei. |
| encoding | java.nio.charset.Charset | Die beim Öffnen von textbasierten Dateien wie [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) oder [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT) verwendete Kodierung. |

### LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)
```


Initialisiert eine neue Instanz der [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der Datei zum Initialisieren. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu ladenden Datei. |
| Passwort | java.lang.String | Das Passwort zum Öffnen einer passwortgeschützten Datei. |
| encoding | java.nio.charset.Charset | Die beim Öffnen von textbasierten Dateien wie [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) oder [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT) verwendete Kodierung. |

### LoadOptions(FileType iniFileType, FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password)
```


Initialisiert eine neue Instanz der [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der Datei zum Initialisieren. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu ladenden Datei. |
| Passwort | java.lang.String | Das Passwort zum Öffnen einer passwortgeschützten Datei. |

### LoadOptions(FileType iniFileType, FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType iniFileType, FileType fileType)
```


Initialisiert eine neue Instanz der [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der Datei zum Initialisieren. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu ladenden Datei. |

### getType() {#getType--}
```
public final FileType getType()
```


Der Typ der zu ladenden Datei.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Die Erweiterung der Datei zum Initialisieren.

**Returns:**
java.lang.String
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Das Passwort zum Öffnen einer passwortgeschützten Datei.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Die Kodierung, die beim Öffnen von textbasierten Dateien wie [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) oder [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT) verwendet wird. Der Standardwert ist  System.Text.Encoding.Default (java.nio.charset.Charset).

**Returns:**
java.nio.charset.Charset
