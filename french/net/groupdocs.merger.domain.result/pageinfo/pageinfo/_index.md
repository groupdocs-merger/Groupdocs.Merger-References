---
title: "PageInfo"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Initialise une nouvelle instance de la classe PageInfogroupdocs.merger.domain.result/pageinfo."
type: docs
weight: 10
url: /fr/net/groupdocs.merger.domain.result/pageinfo/pageinfo/
---
## PageInfo(int, bool) {#constructor}

Initialise une nouvelle instance de la classe [`PageInfo`](../../pageinfo).

```csharp
public PageInfo(int number, bool visible)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nombre | Int32 | Le numéro de page. |
| visible | Boolean | L'indicateur de visibilité de la page. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *number* est inférieur ou égal à zéro. |

### Voir aussi

* class [PageInfo](../../pageinfo)
* namespace [GroupDocs.Merger.Domain.Result](../../../groupdocs.merger.domain.result)
* assembly [GroupDocs.Merger](../../../)

---

## PageInfo(int, bool, int, int) {#constructor_1}

Initialise une nouvelle instance de la classe [`PageInfo`](../../pageinfo).

```csharp
public PageInfo(int number, bool visible, int width, int height)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nombre | Int32 | Le numéro de page. |
| visible | Boolean | L'indicateur de visibilité de la page. |
| largeur | Int32 | La largeur de la page en pixels lors de l'affichage en JPG ou PNG. |
| hauteur | Int32 | La hauteur de la page en pixels lors de l'affichage en JPG ou PNG. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *number* est inférieur ou égal à zéro. |
| ArgumentException | Lancée lorsque *width* est inférieur ou égal à zéro. |
| ArgumentException | Lancée lorsque *height* est inférieur ou égal à zéro. |

### Voir aussi

* class [PageInfo](../../pageinfo)
* namespace [GroupDocs.Merger.Domain.Result](../../../groupdocs.merger.domain.result)
* assembly [GroupDocs.Merger](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
