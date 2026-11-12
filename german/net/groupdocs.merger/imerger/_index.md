---
title: "IMerger"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Schnittstelle für die Hauptklasse, die den Dokumenten‑Zusammenführungsprozess steuert."
type: docs
weight: 920
url: /de/net/groupdocs.merger/imerger/
---
## IMerger interface

Schnittstelle für die Hauptklasse, die den Dokumenten‑Zusammenführungsprozess steuert.

```csharp
public interface IMerger
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPassword](../../groupdocs.merger/imerger/addpassword)(IAddPasswordOptions) | Schützt das Dokument mit einem Passwort. |
| [ChangeOrientation](../../groupdocs.merger/imerger/changeorientation)(IOrientationOptions) | Wendet einen neuen Ausrichtungsmodus für die angegebenen Seiten an. |
| [ExtractPages](../../groupdocs.merger/imerger/extractpages)(IExtractOptions) | Erstellt ein neues Dokument mit einigen Seiten aus dem Quell‑Dokument. |
| [ImportDocument](../../groupdocs.merger/imerger/importdocument)(IImportDocumentOptions) | Importiert das Dokument als Anhang oder eingebettet über Ole. |
| [Join](../../groupdocs.merger/imerger/join#join)(Stream) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [Join](../../groupdocs.merger/imerger/join#join_4)(string) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [Join](../../groupdocs.merger/imerger/join#join_1)(Stream, IImageJoinOptions) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [Join](../../groupdocs.merger/imerger/join#join_2)(Stream, IJoinOptions) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [Join](../../groupdocs.merger/imerger/join#join_3)(Stream, IPageJoinOptions) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [Join](../../groupdocs.merger/imerger/join#join_5)(string, IImageJoinOptions) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [Join](../../groupdocs.merger/imerger/join#join_6)(string, IJoinOptions) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [Join](../../groupdocs.merger/imerger/join#join_7)(string, IPageJoinOptions) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [MovePage](../../groupdocs.merger/imerger/movepage)(IMoveOptions) | Verschiebt die Seite zu einer neuen Position innerhalb eines Dokuments bekannten Formats. |
| [RemovePages](../../groupdocs.merger/imerger/removepages)(IRemoveOptions) | Entfernt Seiten aus einem Dokument bekannten Formats. |
| [RemovePassword](../../groupdocs.merger/imerger/removepassword)() | Entfernt das Passwort aus dem Dokument. |
| [Rotate](../../groupdocs.merger/imerger/rotate)(IRotateOptions) | Dreht die Seiten des Dokuments. |
| [Save](../../groupdocs.merger/imerger/save#save)(Stream, ISaveOptions) | Speichert das Ergebnisdokument in den Stream *document*. |
| [Save](../../groupdocs.merger/imerger/save#save_2)(string, ISaveOptions) | Speichert die Ergebnisdokumentdatei nach *filePath*. |
| [Save](../../groupdocs.merger/imerger/save#save_1)(string, bool, ISaveOptions) | Speichert die Ergebnisdokumentdatei nach *filePath*. |
| [Split](../../groupdocs.merger/imerger/split#split)(ISplitOptions) | Teilt das einzelne Dokument in mehrere Dokumente auf. |
| [Split](../../groupdocs.merger/imerger/split#split_1)(ITextSplitOptions) | Teilt das einzelne Dokument in mehrere Dokumente auf. |
| [SwapPages](../../groupdocs.merger/imerger/swappages)(ISwapOptions) | Vertauscht zwei Seiten innerhalb eines Dokuments mit bekanntem Format. |
| [UpdatePassword](../../groupdocs.merger/imerger/updatepassword)(IUpdatePasswordOptions) | Aktualisiert das vorhandene Passwort für das Dokument. |

### Siehe auch

* namespace [GroupDocs.Merger](../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
