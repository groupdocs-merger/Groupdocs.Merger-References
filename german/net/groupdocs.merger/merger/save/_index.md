---
title: "Speichern"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Speichert das Ergebnisdokument in den Dokumenten-Stream."
type: docs
weight: 170
url: /de/net/groupdocs.merger/merger/save/
---
## Save(Stream, ISaveOptions) {#save}

Speichert das Ergebnisdokument in den Stream *document*.

```csharp
public IMerger Save(Stream document, ISaveOptions saveOptions = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Der Dokumenten-Stream. |
| saveOptions | ISaveOptions | Die Optionen zum Speichern. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *document* null ist. |

### Siehe auch

* interface [IMerger](../../imerger)
* interface [ISaveOptions](../../../groupdocs.merger.domain.options/isaveoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Save(string, ISaveOptions) {#save_2}

Speichert die Ergebnisdokumentdatei nach *filePath*.

```csharp
public IMerger Save(string filePath, ISaveOptions saveOptions = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateiname oder der vollständige Dateipfad. |
| saveOptions | ISaveOptions | Die Optionen zum Speichern. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *filePath* null oder leer ist. |

### Siehe auch

* interface [IMerger](../../imerger)
* interface [ISaveOptions](../../../groupdocs.merger.domain.options/isaveoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Save(string, bool, ISaveOptions) {#save_1}

Speichert die Ergebnisdokumentdatei nach *filePath*.

```csharp
public IMerger Save(string filePath, bool useDefaultDirectory, ISaveOptions saveOptions = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad oder -name bei Verwendung des Standardverzeichnisses. |
| useDefaultDirectory | Boolesch | Verwende das Standardverzeichnis aus den Einstellungen. |
| saveOptions | ISaveOptions | Die Optionen zum Speichern. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *filePath* null oder leer ist. |

### Siehe auch

* interface [IMerger](../../imerger)
* interface [ISaveOptions](../../../groupdocs.merger.domain.options/isaveoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
