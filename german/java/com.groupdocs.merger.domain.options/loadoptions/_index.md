---
title: "LoadOptions"
second_title: "GroupDocs.Merger für Java API-Referenz"
description: "Bietet Optionen für das Laden von Dokumenten."
type: docs
weight: 16
url: /de/java/com.groupdocs.merger.domain.options/loadoptions/
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
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-) | Initialisiert eine neue Instanz der Klasse [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Initialisiert eine neue Instanz der Klasse [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password, Charset encoding)](#LoadOptions-java.lang.String-java.nio.charset.Charset-) | Initialisiert eine neue Instanz der Klasse [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-) | Initialisiert eine neue Instanz der Klasse [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Initialisiert eine neue Instanz der Klasse [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String extension, FileType fileType, String password, Charset encoding)](#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Initialisiert eine neue Instanz der Klasse [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Initialisiert eine neue Instanz der Klasse [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-) | Initialisiert eine neue Instanz der Klasse [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Initialisiert eine neue Instanz der Klasse [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Der Typ der zu ladenden Datei. |
| [getExtension()](#getExtension--) | Die Erweiterung der zu initialisierenden Datei. |
| [getPassword()](#getPassword--) | Das Passwort zum Öffnen einer passwortgeschützten Datei. |
| [getEncoding()](#getEncoding--) | Die beim Öffnen von textbasierten Dateien verwendete Kodierung, wie z. B. [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) oder [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType fileType)
```


Initialisiert eine neue Instanz der Klasse [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu ladenden Datei. |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Initialisiert eine neue Instanz der Klasse [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Passwort | java.lang.String | Das Passwort zum Öffnen einer passwortgeschützten Datei. |

### LoadOptions(String password, Charset encoding) {#LoadOptions-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String password, Charset encoding)
```


Initialisiert eine neue Instanz der Klasse [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Passwort | java.lang.String | Das Passwort zum Öffnen einer passwortgeschützten Datei. |
| encoding | java.nio.charset.Charset | Die beim Öffnen von textbasierten Dateien verwendete Kodierung, wie z. B. [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) oder [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType fileType, String password)
```


Initialisiert eine neue Instanz der Klasse [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu ladenden Datei. |
| Passwort | java.lang.String | Das Passwort zum Öffnen einer passwortgeschützten Datei. |

### LoadOptions(FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType fileType, String password, Charset encoding)
```


Initialisiert eine neue Instanz der Klasse [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu ladenden Datei. |
| Passwort | java.lang.String | Das Passwort zum Öffnen einer passwortgeschützten Datei. |
| encoding | java.nio.charset.Charset | Die beim Öffnen von textbasierten Dateien verwendete Kodierung, wie z. B. [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) oder [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(String extension, FileType fileType, String password, Charset encoding) {#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String extension, FileType fileType, String password, Charset encoding)
```


Initialisiert eine neue Instanz der Klasse [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Erweiterung | java.lang.String | Die Erweiterung der zu ladenden Datei. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu ladenden Datei. |
| Passwort | java.lang.String | Das Passwort zum Öffnen einer passwortgeschützten Datei. |
| encoding | java.nio.charset.Charset | Die beim Öffnen von textbasierten Dateien verwendete Kodierung, wie z. B. [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) oder [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)
```


Initialisiert eine neue Instanz der Klasse [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu initialisierenden Datei. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu ladenden Datei. |
| Passwort | java.lang.String | Das Passwort zum Öffnen einer passwortgeschützten Datei. |
| encoding | java.nio.charset.Charset | Die beim Öffnen von textbasierten Dateien verwendete Kodierung, wie z. B. [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) oder [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password)
```


Initialisiert eine neue Instanz der Klasse [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu initialisierenden Datei. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu ladenden Datei. |
| Passwort | java.lang.String | Das Passwort zum Öffnen einer passwortgeschützten Datei. |

### LoadOptions(FileType iniFileType, FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType iniFileType, FileType fileType)
```


Initialisiert eine neue Instanz der Klasse [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu initialisierenden Datei. |
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


Die Erweiterung der zu initialisierenden Datei.

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


Die beim Öffnen von textbasierten Dateien wie [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) oder [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT) verwendete Kodierung. Der Standardwert ist System.Text.Encoding.Default (java.nio.charset.Charset).

**Returns:**
java.nio.charset.Charset
