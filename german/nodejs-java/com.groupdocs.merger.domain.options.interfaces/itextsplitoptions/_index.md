---
title: "ITextSplitOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Schnittstelle für die Textaufteilungsoptionen."
type: docs
weight: 35
url: /de/nodejs-java/com.groupdocs.merger.domain.options.interfaces/itextsplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ITextSplitOptions extends IOptions
```

Schnittstelle für die Textaufteilungsoptionen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLineNumbers()](#getLineNumbers--) | Zeilennummern für die Textaufteilung. |
| [getMode()](#getMode--) | Modus für die Textaufteilung. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Validiert die Aufteilungsoptionen. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Ermittelt den vollständigen Dateipfad des gesplitteten Dokuments nach Index mit definierter Erweiterung. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Delegat, der die Methode zum Erstellen eines Ausgabesplit-Streams definiert. |
### getLineNumbers() {#getLineNumbers--}
```
public abstract int[] getLineNumbers()
```


Zeilennummern für die Textaufteilung.

**Returns:**
int[]
### getMode() {#getMode--}
```
public abstract int getMode()
```


Modus für die Textaufteilung.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


Validiert die Aufteilungsoptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Dateityp der Klasse [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public abstract String getPathByIndex(int index, String extension)
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
public abstract SplitStreamFactory getSplitStreamFactory()
```


Delegat, der die Methode zum Erstellen eines Ausgabesplit-Streams definiert.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
