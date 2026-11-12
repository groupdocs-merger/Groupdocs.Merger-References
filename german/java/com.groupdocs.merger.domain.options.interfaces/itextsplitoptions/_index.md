---
title: "ITextSplitOptions"
second_title: "GroupDocs.Merger für Java API-Referenz"
description: "Schnittstelle für die Textaufteilungsoptionen."
type: docs
weight: 35
url: /de/java/com.groupdocs.merger.domain.options.interfaces/itextsplitoptions/
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
| [getLineNumbers()](#getLineNumbers--) | Zeilennummern für das Aufteilen von Text. |
| [getMode()](#getMode--) | Modus für das Aufteilen von Text. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Validiert die Aufteilungsoptionen. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Ermittelt den vollständigen Dateipfad des aufgeteilten Dokuments anhand des Index mit definierter Erweiterung. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Delegate, der die Methode zum Erstellen des Ausgabesplit‑Streams definiert. |
### getLineNumbers() {#getLineNumbers--}
```
public abstract int[] getLineNumbers()
```


Zeilennummern für das Aufteilen von Text.

**Returns:**
int[]
### getMode() {#getMode--}
```
public abstract int getMode()
```


Modus für das Aufteilen von Text.

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
