---
title: "TextSplitOptions"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Initialise une nouvelle instance de la classe TextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions."
type: docs
weight: 10
url: /fr/net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

Initialise une nouvelle instance de la classe [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | String | Le format du chemin de fichier, par ex. 'c:/split{0}.doc' ou 'c:/split{0}.{1}' avec l'extension déjà définie. |
| lineNumbers | Int32[] | Numéros de ligne pour le fractionnement du texte. |

### Voir aussi

* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

Initialise une nouvelle instance de la classe [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | String | Le format du chemin de fichier, par ex. 'c:/split{0}.doc' ou 'c:/split{0}.{1}' avec l'extension déjà définie. |
| mode | TextSplitMode | Mode de fractionnement du texte. |
| lineNumbers | Int32[] | Numéros de ligne pour le fractionnement du texte. |

### Voir aussi

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

Initialise une nouvelle instance de la classe [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données de sortie fractionnées. |
| lineNumbers | Int32[] | Numéros de ligne pour le fractionnement du texte. |

### Voir aussi

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

Initialise une nouvelle instance de la classe [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données de sortie fractionnées. |
| mode | TextSplitMode | Mode de fractionnement du texte. |
| lineNumbers | Int32[] | Numéros de ligne pour le fractionnement du texte. |

### Voir aussi

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

Initialise une nouvelle instance de la classe [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données de sortie fractionnées. |
| releaseSplitStream | ReleaseSplitStream | La méthode qui libère le flux créé par la méthode createPageStream. |
| lineNumbers | Int32[] | Numéros de ligne pour le fractionnement du texte. |

### Voir aussi

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

Initialise une nouvelle instance de la classe [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données de sortie fractionnées. |
| releaseSplitStream | ReleaseSplitStream | La méthode qui libère le flux créé par la méthode createPageStream. |
| mode | TextSplitMode | Mode de fractionnement du texte. |
| lineNumbers | Int32[] | Numéros de ligne pour le fractionnement du texte. |

### Voir aussi

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
