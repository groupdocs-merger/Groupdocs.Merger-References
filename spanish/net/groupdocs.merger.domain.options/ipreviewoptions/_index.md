---
title: IPreviewOptions
second_title: Referencia de API de GroupDocs.Merger para .NET
description: Interfaz para las opciones de vista previa.
type: docs
weight: 290
url: /es/net/groupdocs.merger.domain.options/ipreviewoptions/
---
## IPreviewOptions interface

Interfaz para las opciones de vista previa.

```csharp
public interface IPreviewOptions : IPageOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/ipreviewoptions/createstream) { get; } | Delegado que define el método para crear el flujo de vista previa de la página de salida. |
| [Height](../../groupdocs.merger.domain.options/ipreviewoptions/height) { get; set; } | Altura de vista previa. |
| [Mode](../../groupdocs.merger.domain.options/ipreviewoptions/mode) { get; } | Obtiene el modo de vista previa. |
| [ReleaseStream](../../groupdocs.merger.domain.options/ipreviewoptions/releasestream) { get; } | Delegado que define el método para liberar el flujo de vista previa de la página de salida. |
| [Width](../../groupdocs.merger.domain.options/ipreviewoptions/width) { get; set; } | Ancho de vista previa. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetPathByPageNumber](../../groupdocs.merger.domain.options/ipreviewoptions/getpathbypagenumber)(int, string) | Obtiene la ruta completa del archivo del documento en vista previa por número de página con extensión definida. |
| [Validate](../../groupdocs.merger.domain.options/ipreviewoptions/validate)(FileType) | Valida las opciones de split. |

### Ver también

* interface [IPageOptions](../ipageoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* asamblea [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->