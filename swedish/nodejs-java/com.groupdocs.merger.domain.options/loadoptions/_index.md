---
title: "LoadOptions"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för dokumentladdning."
type: docs
weight: 16
url: /sv/nodejs-java/com.groupdocs.merger.domain.options/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Tillhandahåller alternativ för dokumentladdning.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-) | Initierar en ny instans av klassen [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Initierar en ny instans av klassen [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password, Charset encoding)](#LoadOptions-java.lang.String-java.nio.charset.Charset-) | Initierar en ny instans av klassen [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-) | Initierar en ny instans av klassen [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Initierar en ny instans av klassen [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String extension, FileType fileType, String password, Charset encoding)](#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Initierar en ny instans av klassen [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Initierar en ny instans av klassen [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-) | Initierar en ny instans av klassen [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Initierar en ny instans av klassen [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getType()](#getType--) | Typen av filen som ska laddas. |
| [getExtension()](#getExtension--) | Filens filändelse för initiering. |
| [getPassword()](#getPassword--) | Lösenordet för att öppna lösenordsskyddad fil. |
| [getEncoding()](#getEncoding--) | Kodningen som används när textbaserade filer öppnas, såsom [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) eller [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType fileType)
```


Initierar en ny instans av klassen [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Typen av filen som ska laddas. |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Initierar en ny instans av klassen [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lösenord | java.lang.String | Lösenordet för att öppna lösenordsskyddad fil. |

### LoadOptions(String password, Charset encoding) {#LoadOptions-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String password, Charset encoding)
```


Initierar en ny instans av klassen [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lösenord | java.lang.String | Lösenordet för att öppna lösenordsskyddad fil. |
| encoding | java.nio.charset.Charset | Kodningen som används när textbaserade filer öppnas, såsom [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) eller [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType fileType, String password)
```


Initierar en ny instans av klassen [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Typen av filen som ska laddas. |
| lösenord | java.lang.String | Lösenordet för att öppna lösenordsskyddad fil. |

### LoadOptions(FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType fileType, String password, Charset encoding)
```


Initierar en ny instans av klassen [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Typen av filen som ska laddas. |
| lösenord | java.lang.String | Lösenordet för att öppna lösenordsskyddad fil. |
| encoding | java.nio.charset.Charset | Kodningen som används när textbaserade filer öppnas, såsom [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) eller [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(String extension, FileType fileType, String password, Charset encoding) {#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String extension, FileType fileType, String password, Charset encoding)
```


Initierar en ny instans av klassen [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filändelse | java.lang.String | Filens filändelse för laddning. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Typen av filen som ska laddas. |
| lösenord | java.lang.String | Lösenordet för att öppna lösenordsskyddad fil. |
| encoding | java.nio.charset.Charset | Kodningen som används när textbaserade filer öppnas, såsom [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) eller [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)
```


Initierar en ny instans av klassen [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Typen av filen för initiering. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Typen av filen som ska laddas. |
| lösenord | java.lang.String | Lösenordet för att öppna lösenordsskyddad fil. |
| encoding | java.nio.charset.Charset | Kodningen som används när textbaserade filer öppnas, såsom [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) eller [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password)
```


Initierar en ny instans av klassen [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Typen av filen för initiering. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Typen av filen som ska laddas. |
| lösenord | java.lang.String | Lösenordet för att öppna lösenordsskyddad fil. |

### LoadOptions(FileType iniFileType, FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType iniFileType, FileType fileType)
```


Initierar en ny instans av klassen [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Typen av filen för initiering. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Typen av filen som ska laddas. |

### getType() {#getType--}
```
public final FileType getType()
```


Typen av filen som ska laddas.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Filens filändelse för initiering.

**Returns:**
java.lang.String
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Lösenordet för att öppna lösenordsskyddad fil.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Kodningen som används när textbaserade filer öppnas, såsom [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) eller [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). Standardvärdet är System.Text.Encoding.Default (java.nio.charset.Charset).

**Returns:**
java.nio.charset.Charset
