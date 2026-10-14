---
title: "ISplitOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Schnittstelle für die Aufteilungsoptionen."
type: docs
weight: 33
url: /de/nodejs-java/com.groupdocs.merger.domain.options.interfaces/isplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface ISplitOptions extends IPageOptions
```

Schnittstelle für die Aufteilungsoptionen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMode()](#getMode--) | Ermittelt den Modus für das Aufteilen von Seiten. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Validiert die Aufteilungsoptionen. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Ermittelt den vollständigen Dateipfad des gesplitteten Dokuments nach Index mit definierter Erweiterung. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Delegat, der die Methode zum Erstellen eines Ausgabesplit-Streams definiert. |
### getMode() {#getMode--}
```
public abstract int getMode()
```


Ermittelt den Modus für das Aufteilen von Seiten.

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
