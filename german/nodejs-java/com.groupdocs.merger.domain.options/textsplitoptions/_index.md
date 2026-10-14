---
title: "TextSplitOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Bietet Optionen für das Aufteilen von Dokumenttext."
type: docs
weight: 39
url: /de/nodejs-java/com.groupdocs.merger.domain.options/textsplitoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions)
```
public class TextSplitOptions implements ITextSplitOptions
```

Bietet Optionen für das Aufteilen von Dokumenttext.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextSplitOptions(int[] lineNumbers)](#TextSplitOptions-int---) | Initialisiert eine neue Instanz der [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) Klasse. |
| [TextSplitOptions(int mode, int[] lineNumbers)](#TextSplitOptions-int-int---) | Initialisiert eine neue Instanz der [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) Klasse. |
| [TextSplitOptions(String filePathFormat, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int---) | Initialisiert eine neue Instanz der [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) Klasse. |
| [TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int-int---) | Initialisiert eine neue Instanz der [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) Klasse. |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Initialisiert eine neue Instanz der [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) Klasse. |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---) | Initialisiert eine neue Instanz der [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMode()](#getMode--) | Modus für die Textaufteilung. |
| [getLineNumbers()](#getLineNumbers--) | Zeilennummern für die Textaufteilung. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Validiert die Aufteilungsoptionen. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Ermittelt den vollständigen Dateipfad des gesplitteten Dokuments nach Index mit definierter Erweiterung. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory zum Erstellen oder Freigeben des Ausgabeseiten-Vorschau-Streams. |
### TextSplitOptions(int[] lineNumbers) {#TextSplitOptions-int---}
```
public TextSplitOptions(int[] lineNumbers)
```


Initialisiert eine neue Instanz der [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lineNumbers | int[] | Zeilennummern für die Textaufteilung. |

### TextSplitOptions(int mode, int[] lineNumbers) {#TextSplitOptions-int-int---}
```
public TextSplitOptions(int mode, int[] lineNumbers)
```


Initialisiert eine neue Instanz der [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mode | int | Modus für die Textaufteilung. |
| lineNumbers | int[] | Zeilennummern für die Textaufteilung. |

### TextSplitOptions(String filePathFormat, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int---}
```
public TextSplitOptions(String filePathFormat, int[] lineNumbers)
```


Initialisiert eine neue Instanz der [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | java.lang.String | Das Dateipfadformat, z. B. 'c:/split\{0\}.doc' oder 'c:/split\{0\}.\{1\}', mit bereits definierter Erweiterung. |
| lineNumbers | int[] | Zeilennummern für die Textaufteilung. |

### TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int-int---}
```
public TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)
```


Initialisiert eine neue Instanz der [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | java.lang.String | Das Dateipfadformat, z. B. 'c:/split\{0\}.doc' oder 'c:/split\{0\}.\{1\}', mit bereits definierter Erweiterung. |
| mode | int | Modus für die Textaufteilung. |
| lineNumbers | int[] | Zeilennummern für die Textaufteilung. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)
```


Initialisiert eine neue Instanz der [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Die Methode, die den Stream instanziiert, der zum Schreiben der ausgegebenen geteilten Daten verwendet wird. |
| lineNumbers | int[] | Zeilennummern für die Textaufteilung. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)
```


Initialisiert eine neue Instanz der [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Die Methode, die den Stream instanziiert, der zum Schreiben der ausgegebenen geteilten Daten verwendet wird. |
| mode | int | Modus für die Textaufteilung. |
| lineNumbers | int[] | Zeilennummern für die Textaufteilung. |

### getMode() {#getMode--}
```
public final int getMode()
```


Modus für die Textaufteilung.

**Returns:**
int
### getLineNumbers() {#getLineNumbers--}
```
public final int[] getLineNumbers()
```


Zeilennummern für die Textaufteilung.

**Returns:**
int[]
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Validiert die Aufteilungsoptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Dateityp der Klasse [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


Ermittelt den vollständigen Dateipfad des gesplitteten Dokuments nach Index mit definierter Erweiterung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int | Index des geteilten Dokuments. |
| Erweiterung | java.lang.String | Erweiterung der Datei. |

**Returns:**
java.lang.String - Der vollständige Dateipfad.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


SplitStreamFactory zum Erstellen oder Freigeben des Ausgabeseiten-Vorschau-Streams.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
