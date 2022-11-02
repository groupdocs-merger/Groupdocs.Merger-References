---
title: Merger
second_title: GroupDocs.Merger für .NET-API-Referenz
description: Stellt die Hauptklasse dar die den Dokumentenzusammenführungsprozess steuert.
type: docs
weight: 790
url: /de/net/groupdocs.merger/merger/
---
## Merger class

Stellt die Hauptklasse dar, die den Dokumentenzusammenführungsprozess steuert.

```csharp
public class Merger : IDisposable
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Merger](merger#constructor)(Func&lt;Stream&gt;) | Initialisiert eine neue Instanz von[`Merger`](../merger) Klasse. |
| [Merger](merger#constructor_4)(Stream) | Initialisiert eine neue Instanz von[`Merger`](../merger) Klasse. |
| [Merger](merger#constructor_8)(string) | Initialisiert eine neue Instanz von[`Merger`](../merger) Klasse. |
| [Merger](merger#constructor_1)(Func&lt;Stream&gt;, ILoadOptions) | Initialisiert eine neue Instanz von[`Merger`](../merger) Klasse. |
| [Merger](merger#constructor_3)(Func&lt;Stream&gt;, MergerSettings) | Initialisiert eine neue Instanz von[`Merger`](../merger) Klasse. |
| [Merger](merger#constructor_5)(Stream, ILoadOptions) | Initialisiert eine neue Instanz von[`Merger`](../merger) Klasse. |
| [Merger](merger#constructor_7)(Stream, MergerSettings) | Initialisiert eine neue Instanz von[`Merger`](../merger) Klasse. |
| [Merger](merger#constructor_9)(string, ILoadOptions) | Initialisiert eine neue Instanz von[`Merger`](../merger) Klasse. |
| [Merger](merger#constructor_11)(string, MergerSettings) | Initialisiert eine neue Instanz von[`Merger`](../merger) Klasse. |
| [Merger](merger#constructor_2)(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) | Initialisiert eine neue Instanz von[`Merger`](../merger) Klasse. |
| [Merger](merger#constructor_6)(Stream, ILoadOptions, MergerSettings) | Initialisiert eine neue Instanz von[`Merger`](../merger) Klasse. |
| [Merger](merger#constructor_10)(string, ILoadOptions, MergerSettings) | Initialisiert eine neue Instanz von[`Merger`](../merger) Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPassword](../../groupdocs.merger/merger/addpassword)(IAddPasswordOptions) | Schützt Dokument mit Passwort. |
| [ChangeOrientation](../../groupdocs.merger/merger/changeorientation)(IOrientationOptions) | Wendet einen neuen Ausrichtungsmodus für die angegebenen Seiten an. |
| [Dispose](../../groupdocs.merger/merger/dispose)() | Gibt Ressourcen frei. |
| [ExtractPages](../../groupdocs.merger/merger/extractpages)(IExtractOptions) | Erstellt ein neues Dokument mit einigen Seiten aus dem Quelldokument. |
| [GeneratePreview](../../groupdocs.merger/merger/generatepreview)(IPreviewOptions) | Erstellt eine Vorschau der Dokumentseiten. |
| [GetDocumentInfo](../../groupdocs.merger/merger/getdocumentinfo)() | Ruft Informationen über Dokumentseiten ab: ihre Größe, maximale Seitenhöhe, die Breite einer Seite mit der maximalen Höhe. |
| [ImportDocument](../../groupdocs.merger/merger/importdocument)(IImportDocumentOptions) | Importiert das Dokument als Anhang oder eingebettet über Ole. |
| [IsPasswordSet](../../groupdocs.merger/merger/ispasswordset)() | Prüft, ob das Dokument passwortgeschützt ist. |
| [Join](../../groupdocs.merger/merger/join#join)(Stream) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [Join](../../groupdocs.merger/merger/join#join_3)(string) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [Join](../../groupdocs.merger/merger/join#join_1)(Stream, IImageJoinOptions) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [Join](../../groupdocs.merger/merger/join#join_2)(Stream, IJoinOptions) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [Join](../../groupdocs.merger/merger/join#join_4)(string, IImageJoinOptions) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [Join](../../groupdocs.merger/merger/join#join_5)(string, IJoinOptions) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [MovePage](../../groupdocs.merger/merger/movepage)(IMoveOptions) | Verschiebt die Seite an eine neue Position innerhalb des Dokuments mit bekanntem Format. |
| [RemovePages](../../groupdocs.merger/merger/removepages)(IRemoveOptions) | Entfernt Seiten aus einem Dokument mit bekanntem Format. |
| [RemovePassword](../../groupdocs.merger/merger/removepassword)() | Entfernt das Passwort aus dem Dokument. |
| [RotatePages](../../groupdocs.merger/merger/rotatepages)(IRotateOptions) | Seiten des Dokuments drehen. |
| [Save](../../groupdocs.merger/merger/save#save)(Stream) | Speichert das Ergebnisdokument im Stream*document* . |
| [Save](../../groupdocs.merger/merger/save#save_1)(string) | Speichert die Ergebnisdokumentdatei unter*filePath* . |
| [Save](../../groupdocs.merger/merger/save#save_2)(string, bool) | Speichert die Ergebnisdokumentdatei unter*filePath* . |
| [Split](../../groupdocs.merger/merger/split#split)(ISplitOptions) | Teilt das einzelne Dokument in mehrere Dokumente auf. |
| [Split](../../groupdocs.merger/merger/split#split_1)(ITextSplitOptions) | Teilt das einzelne Dokument in mehrere Dokumente auf. |
| [SwapPages](../../groupdocs.merger/merger/swappages)(ISwapOptions) | Vertauscht zwei Seiten innerhalb eines Dokuments mit bekanntem Format. |
| [UpdatePassword](../../groupdocs.merger/merger/updatepassword)(IUpdatePasswordOptions) | Aktualisiert das vorhandene Passwort für das Dokument. |

### Siehe auch

* namensraum [GroupDocs.Merger](../../groupdocs.merger)
* Montage [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
