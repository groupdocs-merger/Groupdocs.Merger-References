---
title: "Save"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Enregistre le document résultat dans le flux du document."
type: docs
weight: 170
url: /fr/net/groupdocs.merger/merger/save/
---
## Save(Stream, ISaveOptions) {#save}

Enregistre le document résultant dans le flux *document*.

```csharp
public IMerger Save(Stream document, ISaveOptions saveOptions = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Le flux du document. |
| saveOptions | ISaveOptions | Les options d'enregistrement. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancé lorsque *document* est nul. |

### Voir aussi

* interface [IMerger](../../imerger)
* interface [ISaveOptions](../../../groupdocs.merger.domain.options/isaveoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Save(string, ISaveOptions) {#save_2}

Enregistre le fichier du document résultant dans *filePath*.

```csharp
public IMerger Save(string filePath, ISaveOptions saveOptions = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le nom du fichier ou le chemin complet. |
| saveOptions | ISaveOptions | Les options d'enregistrement. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *filePath* est nul ou vide. |

### Voir aussi

* interface [IMerger](../../imerger)
* interface [ISaveOptions](../../../groupdocs.merger.domain.options/isaveoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Save(string, bool, ISaveOptions) {#save_1}

Enregistre le fichier du document résultant dans *filePath*.

```csharp
public IMerger Save(string filePath, bool useDefaultDirectory, ISaveOptions saveOptions = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin ou le nom du fichier en cas d'utilisation du répertoire par défaut. |
| useDefaultDirectory | Boolean | Utiliser le répertoire par défaut depuis les paramètres. |
| saveOptions | ISaveOptions | Les options d'enregistrement. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *filePath* est nul ou vide. |

### Voir aussi

* interface [IMerger](../../imerger)
* interface [ISaveOptions](../../../groupdocs.merger.domain.options/isaveoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
