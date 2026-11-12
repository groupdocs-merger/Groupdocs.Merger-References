---
title: "Mode"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Le mode de jointure de la feuille de calcul. La valeur par défaut est Worksheets."
type: docs
weight: 20
url: /fr/net/groupdocs.merger.domain.options/spreadsheetjoinoptions/mode/
---
## SpreadsheetJoinOptions.Mode property

Le mode de jointure de la feuille de calcul. La valeur par défaut est Worksheets.

```csharp
public SpreadsheetJoinMode Mode { get; set; }
```

### Remarques

En mode Rows, les numéros de page sélectionnent les worksheets du spreadsheet joint dont les rows sont ajoutés. Les cell values, les formulas, les cell styles, les merged cells et les row heights sont conservés ; les charts, les pictures et les autres floating objects, les pivot tables, les tables, le conditional formatting et la data validation ne le sont pas. Les formulas faisant référence à d’autres worksheets ou workbooks peuvent pointer vers des données différentes après la jointure.

### Voir aussi

* enum [SpreadsheetJoinMode](../../spreadsheetjoinmode)
* class [SpreadsheetJoinOptions](../../spreadsheetjoinoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
