---
title: Merger
second_title: Riferimento API GroupDocs.Merger per .NET
description: Rappresenta la classe principale che controlla il processo di unione dei documenti.
type: docs
weight: 790
url: /it/net/groupdocs.merger/merger/
---
## Merger class

Rappresenta la classe principale che controlla il processo di unione dei documenti.

```csharp
public class Merger : IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Merger](merger#constructor)(Func&lt;Stream&gt;) | Inizializza una nuova istanza di[`Merger`](../merger) classe. |
| [Merger](merger#constructor_4)(Stream) | Inizializza una nuova istanza di[`Merger`](../merger) classe. |
| [Merger](merger#constructor_8)(string) | Inizializza una nuova istanza di[`Merger`](../merger) classe. |
| [Merger](merger#constructor_1)(Func&lt;Stream&gt;, ILoadOptions) | Inizializza una nuova istanza di[`Merger`](../merger) classe. |
| [Merger](merger#constructor_3)(Func&lt;Stream&gt;, MergerSettings) | Inizializza una nuova istanza di[`Merger`](../merger) classe. |
| [Merger](merger#constructor_5)(Stream, ILoadOptions) | Inizializza una nuova istanza di[`Merger`](../merger) classe. |
| [Merger](merger#constructor_7)(Stream, MergerSettings) | Inizializza una nuova istanza di[`Merger`](../merger) classe. |
| [Merger](merger#constructor_9)(string, ILoadOptions) | Inizializza una nuova istanza di[`Merger`](../merger) classe. |
| [Merger](merger#constructor_11)(string, MergerSettings) | Inizializza una nuova istanza di[`Merger`](../merger) classe. |
| [Merger](merger#constructor_2)(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) | Inizializza una nuova istanza di[`Merger`](../merger) classe. |
| [Merger](merger#constructor_6)(Stream, ILoadOptions, MergerSettings) | Inizializza una nuova istanza di[`Merger`](../merger) classe. |
| [Merger](merger#constructor_10)(string, ILoadOptions, MergerSettings) | Inizializza una nuova istanza di[`Merger`](../merger) classe. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddPassword](../../groupdocs.merger/merger/addpassword)(IAddPasswordOptions) | Protegge il documento con password. |
| [ChangeOrientation](../../groupdocs.merger/merger/changeorientation)(IOrientationOptions) | Applica una nuova modalità di orientamento per le pagine specificate. |
| [Dispose](../../groupdocs.merger/merger/dispose)() | Smaltisce le risorse. |
| [ExtractPages](../../groupdocs.merger/merger/extractpages)(IExtractOptions) | Crea un nuovo documento con alcune pagine del documento di origine. |
| [GeneratePreview](../../groupdocs.merger/merger/generatepreview)(IPreviewOptions) | Genera l'anteprima delle pagine del documento. |
| [GetDocumentInfo](../../groupdocs.merger/merger/getdocumentinfo)() | Ottiene informazioni sulle pagine del documento: le loro dimensioni, l'altezza massima della pagina, la larghezza di una pagina con l'altezza massima. |
| [ImportDocument](../../groupdocs.merger/merger/importdocument)(IImportDocumentOptions) | Importa il documento come allegato o incorporato tramite Ole. |
| [IsPasswordSet](../../groupdocs.merger/merger/ispasswordset)() | Controlla se il documento è protetto da password. |
| [Join](../../groupdocs.merger/merger/join#join)(Stream) | Unisce i documenti in un unico documento. |
| [Join](../../groupdocs.merger/merger/join#join_3)(string) | Unisce i documenti in un unico documento. |
| [Join](../../groupdocs.merger/merger/join#join_1)(Stream, IImageJoinOptions) | Unisce i documenti in un unico documento. |
| [Join](../../groupdocs.merger/merger/join#join_2)(Stream, IJoinOptions) | Unisce i documenti in un unico documento. |
| [Join](../../groupdocs.merger/merger/join#join_4)(string, IImageJoinOptions) | Unisce i documenti in un unico documento. |
| [Join](../../groupdocs.merger/merger/join#join_5)(string, IJoinOptions) | Unisce i documenti in un unico documento. |
| [MovePage](../../groupdocs.merger/merger/movepage)(IMoveOptions) | Sposta la pagina in una nuova posizione all'interno del documento di formato noto. |
| [RemovePages](../../groupdocs.merger/merger/removepages)(IRemoveOptions) | Rimuove le pagine dal documento di formato noto. |
| [RemovePassword](../../groupdocs.merger/merger/removepassword)() | Rimuove la password dal documento. |
| [RotatePages](../../groupdocs.merger/merger/rotatepages)(IRotateOptions) | Ruota le pagine del documento. |
| [Save](../../groupdocs.merger/merger/save#save)(Stream) | Salva il documento dei risultati nello stream*document* . |
| [Save](../../groupdocs.merger/merger/save#save_1)(string) | Salva il file del documento dei risultati in*filePath* . |
| [Save](../../groupdocs.merger/merger/save#save_2)(string, bool) | Salva il file del documento dei risultati in*filePath* . |
| [Split](../../groupdocs.merger/merger/split#split)(ISplitOptions) | Divide il singolo documento in più documenti. |
| [Split](../../groupdocs.merger/merger/split#split_1)(ITextSplitOptions) | Divide il singolo documento in più documenti. |
| [SwapPages](../../groupdocs.merger/merger/swappages)(ISwapOptions) | Scambia due pagine all'interno di un documento di formato noto. |
| [UpdatePassword](../../groupdocs.merger/merger/updatepassword)(IUpdatePasswordOptions) | Aggiorna la password esistente per il documento. |

### Guarda anche

* spazio dei nomi [GroupDocs.Merger](../../groupdocs.merger)
* assemblea [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
