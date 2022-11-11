---
title: TextSplitOptions
second_title: Référence de l'API GroupDocs.Merger pour .NET
description: Initialise une nouvelle instance duTextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions classe.
type: docs
weight: 10
url: /fr/net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

Initialise une nouvelle instance du[`TextSplitOptions`](../../textsplitoptions) classe.

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePathFormat | String | Le format du chemin d'accès au fichier, par exemple 'c:/split{0}.doc' ou 'c:/split{0}.{1}' avec une extension déjà définie. |
| lineNumbers | Int32[] | Numéros de ligne pour le fractionnement de texte. |

### Voir également

* class [TextSplitOptions](../../textsplitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* Assemblée [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

Initialise une nouvelle instance du[`TextSplitOptions`](../../textsplitoptions) classe.

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePathFormat | String | Le format du chemin d'accès au fichier, par exemple 'c:/split{0}.doc' ou 'c:/split{0}.{1}' avec une extension déjà définie. |
| mode | TextSplitMode | Mode de fractionnement de texte. |
| lineNumbers | Int32[] | Numéros de ligne pour le fractionnement de texte. |

### Voir également

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* Assemblée [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

Initialise une nouvelle instance du[`TextSplitOptions`](../../textsplitoptions) classe.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données fractionnées de sortie. |
| lineNumbers | Int32[] | Numéros de ligne pour le fractionnement de texte. |

### Voir également

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* Assemblée [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

Initialise une nouvelle instance du[`TextSplitOptions`](../../textsplitoptions) classe.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données fractionnées de sortie. |
| mode | TextSplitMode | Mode de fractionnement de texte. |
| lineNumbers | Int32[] | Numéros de ligne pour le fractionnement de texte. |

### Voir également

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* Assemblée [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

Initialise une nouvelle instance du[`TextSplitOptions`](../../textsplitoptions) classe.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données fractionnées de sortie. |
| releaseSplitStream | ReleaseSplitStream | La méthode qui libère le flux créé par la méthode createPageStream. |
| lineNumbers | Int32[] | Numéros de ligne pour le fractionnement de texte. |

### Voir également

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* Assemblée [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

Initialise une nouvelle instance du[`TextSplitOptions`](../../textsplitoptions) classe.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données fractionnées de sortie. |
| releaseSplitStream | ReleaseSplitStream | La méthode qui libère le flux créé par la méthode createPageStream. |
| mode | TextSplitMode | Mode de fractionnement de texte. |
| lineNumbers | Int32[] | Numéros de ligne pour le fractionnement de texte. |

### Voir également

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* Assemblée [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
