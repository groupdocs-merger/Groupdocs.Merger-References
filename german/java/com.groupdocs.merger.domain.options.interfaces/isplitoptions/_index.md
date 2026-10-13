---
title: "ISplitOptions"
second_title: "GroupDocs.Merger für Java API-Referenz"
description: "Schnittstelle für die Aufteilungsoptionen."
type: docs
weight: 33
url: /de/java/com.groupdocs.merger.domain.options.interfaces/isplitoptions/
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
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Ermittelt den vollständigen Dateipfad des aufgeteilten Dokuments anhand des Index mit definierter Erweiterung. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Delegate, der die Methode zum Erstellen des Ausgabesplit‑Streams definiert. |
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


Ermittelt den vollständigen Dateipfad des aufgeteilten Dokuments anhand des Index mit definierter Erweiterung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int | Index des aufgeteilten Dokuments. |
| Erweiterung | java.lang.String | Dateierweiterung. |

**Returns:**
java.lang.String – Der vollständige Dateipfad.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public abstract SplitStreamFactory getSplitStreamFactory()
```


Delegate, der die Methode zum Erstellen des Ausgabesplit‑Streams definiert.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
