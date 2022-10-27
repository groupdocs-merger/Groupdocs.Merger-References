---
title: Merger
second_title: Referencia de API de GroupDocs.Merger para .NET
description: Representa la clase principal que controla el proceso de fusión de documentos.
type: docs
weight: 790
url: /es/net/groupdocs.merger/merger/
---
## Merger class

Representa la clase principal que controla el proceso de fusión de documentos.

```csharp
public class Merger : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Merger](merger#constructor)(Func&lt;Stream&gt;) | Inicializa una nueva instancia de[`Merger`](../merger) clase. |
| [Merger](merger#constructor_4)(Stream) | Inicializa una nueva instancia de[`Merger`](../merger) clase. |
| [Merger](merger#constructor_8)(string) | Inicializa una nueva instancia de[`Merger`](../merger) clase. |
| [Merger](merger#constructor_1)(Func&lt;Stream&gt;, ILoadOptions) | Inicializa una nueva instancia de[`Merger`](../merger) clase. |
| [Merger](merger#constructor_3)(Func&lt;Stream&gt;, MergerSettings) | Inicializa una nueva instancia de[`Merger`](../merger) clase. |
| [Merger](merger#constructor_5)(Stream, ILoadOptions) | Inicializa una nueva instancia de[`Merger`](../merger) clase. |
| [Merger](merger#constructor_7)(Stream, MergerSettings) | Inicializa una nueva instancia de[`Merger`](../merger) clase. |
| [Merger](merger#constructor_9)(string, ILoadOptions) | Inicializa una nueva instancia de[`Merger`](../merger) clase. |
| [Merger](merger#constructor_11)(string, MergerSettings) | Inicializa una nueva instancia de[`Merger`](../merger) clase. |
| [Merger](merger#constructor_2)(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) | Inicializa una nueva instancia de[`Merger`](../merger) clase. |
| [Merger](merger#constructor_6)(Stream, ILoadOptions, MergerSettings) | Inicializa una nueva instancia de[`Merger`](../merger) clase. |
| [Merger](merger#constructor_10)(string, ILoadOptions, MergerSettings) | Inicializa una nueva instancia de[`Merger`](../merger) clase. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddPassword](../../groupdocs.merger/merger/addpassword)(IAddPasswordOptions) | Protege documento con contraseña. |
| [ChangeOrientation](../../groupdocs.merger/merger/changeorientation)(IOrientationOptions) | Aplica un nuevo modo de orientación para las páginas especificadas. |
| [Dispose](../../groupdocs.merger/merger/dispose)() | Elimina recursos. |
| [ExtractPages](../../groupdocs.merger/merger/extractpages)(IExtractOptions) | Crea un nuevo documento con algunas páginas del documento de origen. |
| [GeneratePreview](../../groupdocs.merger/merger/generatepreview)(IPreviewOptions) | Genera vista previa de las páginas del documento. |
| [GetDocumentInfo](../../groupdocs.merger/merger/getdocumentinfo)() | Obtiene información sobre las páginas del documento: sus tamaños, la altura máxima de página, el ancho de una página con la altura máxima. |
| [ImportDocument](../../groupdocs.merger/merger/importdocument)(IImportDocumentOptions) | Importa el documento como archivo adjunto o incrustado a través de Ole. |
| [IsPasswordSet](../../groupdocs.merger/merger/ispasswordset)() | Comprueba si el documento está protegido con contraseña. |
| [Join](../../groupdocs.merger/merger/join#join)(Stream) | Une los documentos en un solo documento. |
| [Join](../../groupdocs.merger/merger/join#join_3)(string) | Une los documentos en un solo documento. |
| [Join](../../groupdocs.merger/merger/join#join_1)(Stream, IImageJoinOptions) | Une los documentos en un solo documento. |
| [Join](../../groupdocs.merger/merger/join#join_2)(Stream, IJoinOptions) | Une los documentos en un solo documento. |
| [Join](../../groupdocs.merger/merger/join#join_4)(string, IImageJoinOptions) | Une los documentos en un solo documento. |
| [Join](../../groupdocs.merger/merger/join#join_5)(string, IJoinOptions) | Une los documentos en un solo documento. |
| [MovePage](../../groupdocs.merger/merger/movepage)(IMoveOptions) | Mueve la página a una nueva posición dentro del documento de formato conocido. |
| [RemovePages](../../groupdocs.merger/merger/removepages)(IRemoveOptions) | Elimina páginas del documento de formato conocido. |
| [RemovePassword](../../groupdocs.merger/merger/removepassword)() | Elimina la contraseña del documento. |
| [RotatePages](../../groupdocs.merger/merger/rotatepages)(IRotateOptions) | Rotar páginas del documento. |
| [Save](../../groupdocs.merger/merger/save#save)(Stream) | Guarda el documento de resultados en la secuencia*document* . |
| [Save](../../groupdocs.merger/merger/save#save_1)(string) | Guarda el archivo del documento de resultados en*filePath* . |
| [Save](../../groupdocs.merger/merger/save#save_2)(string, bool) | Guarda el archivo del documento de resultados en*filePath* . |
| [Split](../../groupdocs.merger/merger/split#split)(ISplitOptions) | Divide el documento único en varios documentos. |
| [Split](../../groupdocs.merger/merger/split#split_1)(ITextSplitOptions) | Divide el documento único en varios documentos. |
| [SwapPages](../../groupdocs.merger/merger/swappages)(ISwapOptions) | Intercambia dos páginas dentro de un documento de formato conocido. |
| [UpdatePassword](../../groupdocs.merger/merger/updatepassword)(IUpdatePasswordOptions) | Actualiza la contraseña existente para document. |

### Ver también

* espacio de nombres [GroupDocs.Merger](../../groupdocs.merger)
* asamblea [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
