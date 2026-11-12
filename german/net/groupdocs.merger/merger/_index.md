---
title: "Zusammenführer"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Stellt die Hauptklasse dar, die den Dokumentzusammenführungsprozess steuert."
type: docs
weight: 960
url: /de/net/groupdocs.merger/merger/
---
## Merger class

Stellt die Hauptklasse dar, die den Dokumentzusammenführungsprozess steuert.

```csharp
public class Merger : IDisposable, IMerger
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Merger](merger#constructor)(Func&lt;Stream&gt;) | Initialisiert eine neue Instanz der Klasse [`Merger`](../merger). |
| [Merger](merger#constructor_4)(Stream) | Initialisiert eine neue Instanz der Klasse [`Merger`](../merger). |
| [Merger](merger#constructor_8)(string) | Initialisiert eine neue Instanz der Klasse [`Merger`](../merger). |
| [Merger](merger#constructor_1)(Func&lt;Stream&gt;, ILoadOptions) | Initialisiert eine neue Instanz der Klasse [`Merger`](../merger). |
| [Merger](merger#constructor_3)(Func&lt;Stream&gt;, MergerSettings) | Initialisiert eine neue Instanz der Klasse [`Merger`](../merger). |
| [Merger](merger#constructor_5)(Stream, ILoadOptions) | Initialisiert eine neue Instanz der Klasse [`Merger`](../merger). |
| [Merger](merger#constructor_7)(Stream, MergerSettings) | Initialisiert eine neue Instanz der Klasse [`Merger`](../merger). |
| [Merger](merger#constructor_9)(string, ILoadOptions) | Initialisiert eine neue Instanz der Klasse [`Merger`](../merger). |
| [Merger](merger#constructor_11)(string, MergerSettings) | Initialisiert eine neue Instanz der Klasse [`Merger`](../merger). |
| [Merger](merger#constructor_2)(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) | Initialisiert eine neue Instanz der Klasse [`Merger`](../merger). |
| [Merger](merger#constructor_6)(Stream, ILoadOptions, MergerSettings) | Initialisiert eine neue Instanz der Klasse [`Merger`](../merger). |
| [Merger](merger#constructor_10)(string, ILoadOptions, MergerSettings) | Initialisiert eine neue Instanz der Klasse [`Merger`](../merger). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPassword](../../groupdocs.merger/merger/addpassword)(IAddPasswordOptions) | Schützt das Dokument mit einem Passwort. |
| [ApplyPageBuilder](../../groupdocs.merger/merger/applypagebuilder)(PageBuilder) | Wendet Änderungen des Seiten‑Builders an. |
| [ChangeOrientation](../../groupdocs.merger/merger/changeorientation)(IOrientationOptions) | Wendet einen neuen Ausrichtungsmodus für die angegebenen Seiten an. |
| [CreatePageBuilder](../../groupdocs.merger/merger/createpagebuilder)(PageBuilderOptions) | Erstellt einen neuen Seiten‑Builder mit vordefinierter Dokumentensammlung. |
| [Dispose](../../groupdocs.merger/merger/dispose)() | Gibt Ressourcen frei. |
| [ExtractPages](../../groupdocs.merger/merger/extractpages)(IExtractOptions) | Erstellt ein neues Dokument mit einigen Seiten aus dem Quell‑Dokument. |
| [GeneratePreview](../../groupdocs.merger/merger/generatepreview)(IPreviewOptions) | Erzeugt eine Vorschau der Dokumentseiten. |
| [GetDocumentInfo](../../groupdocs.merger/merger/getdocumentinfo)() | Liefert Informationen über Dokumentseiten: deren Größen, maximale Seitenhöhe, die Breite einer Seite mit der maximalen Höhe. |
| [ImportDocument](../../groupdocs.merger/merger/importdocument)(IImportDocumentOptions) | Importiert das Dokument als Anhang oder eingebettet über Ole. |
| [IsPasswordSet](../../groupdocs.merger/merger/ispasswordset)() | Prüft, ob das Dokument passwortgeschützt ist. |
| [Join](../../groupdocs.merger/merger/join#join)(Stream) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [Join](../../groupdocs.merger/merger/join#join_4)(string) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [Join](../../groupdocs.merger/merger/join#join_1)(Stream, IImageJoinOptions) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [Join](../../groupdocs.merger/merger/join#join_2)(Stream, IJoinOptions) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [Join](../../groupdocs.merger/merger/join#join_3)(Stream, IPageJoinOptions) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [Join](../../groupdocs.merger/merger/join#join_5)(string, IImageJoinOptions) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [Join](../../groupdocs.merger/merger/join#join_6)(string, IJoinOptions) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [Join](../../groupdocs.merger/merger/join#join_7)(string, IPageJoinOptions) | Fügt die Dokumente zu einem einzigen Dokument zusammen. |
| [MovePage](../../groupdocs.merger/merger/movepage)(IMoveOptions) | Verschiebt die Seite zu einer neuen Position innerhalb eines Dokuments bekannten Formats. |
| [RemovePages](../../groupdocs.merger/merger/removepages)(IRemoveOptions) | Entfernt Seiten aus einem Dokument bekannten Formats. |
| [RemovePassword](../../groupdocs.merger/merger/removepassword)() | Entfernt das Passwort aus dem Dokument. |
| [Rotate](../../groupdocs.merger/merger/rotate)(IRotateOptions) | Dreht das Bild oder die Seiten des Dokuments. |
| [Save](../../groupdocs.merger/merger/save#save)(Stream, ISaveOptions) | Speichert das Ergebnisdokument in den Stream *document*. |
| [Save](../../groupdocs.merger/merger/save#save_2)(string, ISaveOptions) | Speichert die Ergebnisdokumentdatei nach *filePath*. |
| [Save](../../groupdocs.merger/merger/save#save_1)(string, bool, ISaveOptions) | Speichert die Ergebnisdokumentdatei nach *filePath*. |
| [Split](../../groupdocs.merger/merger/split#split)(ISplitOptions) | Teilt das einzelne Dokument in mehrere Dokumente auf. |
| [Split](../../groupdocs.merger/merger/split#split_1)(ITextSplitOptions) | Teilt das einzelne Dokument in mehrere Dokumente auf. |
| [SwapPages](../../groupdocs.merger/merger/swappages)(ISwapOptions) | Vertauscht zwei Seiten innerhalb eines Dokuments mit bekanntem Format. |
| [UpdatePassword](../../groupdocs.merger/merger/updatepassword)(IUpdatePasswordOptions) | Aktualisiert das vorhandene Passwort für das Dokument. |

### Siehe auch

* interface [IMerger](../imerger)
* namespace [GroupDocs.Merger](../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
