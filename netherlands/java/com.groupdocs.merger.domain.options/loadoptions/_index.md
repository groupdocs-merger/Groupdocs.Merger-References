---
title: "LoadOptions"
second_title: "GroupDocs.Merger for Java API-referentie"
description: "Biedt opties voor het laden van documenten."
type: docs
weight: 16
url: /nl/java/com.groupdocs.merger.domain.options/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Biedt opties voor het laden van documenten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-) | Initialiseert een nieuw exemplaar van de [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) klasse. |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Initialiseert een nieuw exemplaar van de [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) klasse. |
| [LoadOptions(String password, Charset encoding)](#LoadOptions-java.lang.String-java.nio.charset.Charset-) | Initialiseert een nieuw exemplaar van de [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) klasse. |
| [LoadOptions(FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-) | Initialiseert een nieuw exemplaar van de [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) klasse. |
| [LoadOptions(FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Initialiseert een nieuw exemplaar van de [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) klasse. |
| [LoadOptions(String extension, FileType fileType, String password, Charset encoding)](#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Initialiseert een nieuw exemplaar van de [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) klasse. |
| [LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Initialiseert een nieuw exemplaar van de [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) klasse. |
| [LoadOptions(FileType iniFileType, FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-) | Initialiseert een nieuw exemplaar van de [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) klasse. |
| [LoadOptions(FileType iniFileType, FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Initialiseert een nieuw exemplaar van de [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Het type van het bestand om te laden. |
| [getExtension()](#getExtension--) | De extensie van het bestand om te initialiseren. |
| [getPassword()](#getPassword--) | Het wachtwoord voor het openen van een met wachtwoord beveiligd bestand. |
| [getEncoding()](#getEncoding--) | De codering die wordt gebruikt bij het openen van tekstgebaseerde bestanden, zoals [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) of [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType fileType)
```


Initialiseert een nieuw exemplaar van de [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het type van het bestand om te laden. |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Initialiseert een nieuw exemplaar van de [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| wachtwoord | java.lang.String | Het wachtwoord voor het openen van een met wachtwoord beveiligd bestand. |

### LoadOptions(String password, Charset encoding) {#LoadOptions-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String password, Charset encoding)
```


Initialiseert een nieuw exemplaar van de [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| wachtwoord | java.lang.String | Het wachtwoord voor het openen van een met wachtwoord beveiligd bestand. |
| encoding | java.nio.charset.Charset | De codering die wordt gebruikt bij het openen van tekstgebaseerde bestanden, zoals [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) of [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType fileType, String password)
```


Initialiseert een nieuw exemplaar van de [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het type van het bestand om te laden. |
| wachtwoord | java.lang.String | Het wachtwoord voor het openen van een met wachtwoord beveiligd bestand. |

### LoadOptions(FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType fileType, String password, Charset encoding)
```


Initialiseert een nieuw exemplaar van de [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het type van het bestand om te laden. |
| wachtwoord | java.lang.String | Het wachtwoord voor het openen van een met wachtwoord beveiligd bestand. |
| encoding | java.nio.charset.Charset | De codering die wordt gebruikt bij het openen van tekstgebaseerde bestanden, zoals [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) of [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(String extension, FileType fileType, String password, Charset encoding) {#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String extension, FileType fileType, String password, Charset encoding)
```


Initialiseert een nieuw exemplaar van de [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| extensie | java.lang.String | De extensie van het bestand om te laden. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het type van het bestand om te laden. |
| wachtwoord | java.lang.String | Het wachtwoord voor het openen van een met wachtwoord beveiligd bestand. |
| encoding | java.nio.charset.Charset | De codering die wordt gebruikt bij het openen van tekstgebaseerde bestanden, zoals [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) of [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)
```


Initialiseert een nieuw exemplaar van de [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het type van het bestand om te initialiseren. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het type van het bestand om te laden. |
| wachtwoord | java.lang.String | Het wachtwoord voor het openen van een met wachtwoord beveiligd bestand. |
| encoding | java.nio.charset.Charset | De codering die wordt gebruikt bij het openen van tekstgebaseerde bestanden, zoals [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) of [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password)
```


Initialiseert een nieuw exemplaar van de [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het type van het bestand om te initialiseren. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het type van het bestand om te laden. |
| wachtwoord | java.lang.String | Het wachtwoord voor het openen van een met wachtwoord beveiligd bestand. |

### LoadOptions(FileType iniFileType, FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType iniFileType, FileType fileType)
```


Initialiseert een nieuw exemplaar van de [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het type van het bestand om te initialiseren. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het type van het bestand om te laden. |

### getType() {#getType--}
```
public final FileType getType()
```


Het type van het bestand om te laden.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getExtension() {#getExtension--}
```
public final String getExtension()
```


De extensie van het bestand om te initialiseren.

**Returns:**
java.lang.String
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Het wachtwoord voor het openen van een met wachtwoord beveiligd bestand.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


De codering die wordt gebruikt bij het openen van tekstgebaseerde bestanden, zoals [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) of [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). Standaardwaarde is System.Text.Encoding.Default (java.nio.charset.Charset).

**Returns:**
java.nio.charset.Charset
