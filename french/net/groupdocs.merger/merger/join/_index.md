---
title: "Join"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Fusionne les documents en un seul document."
type: docs
weight: 120
url: /fr/net/groupdocs.merger/merger/join/
---
## Join(Stream) {#join}

Fusionne les documents en un seul document.

```csharp
public IMerger Join(Stream document)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Document joint. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancé lorsque *document* est nul. |

### Remarques

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Voir aussi

* interface [IMerger](../../imerger)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IJoinOptions) {#join_2}

Fusionne les documents en un seul document.

```csharp
public IMerger Join(Stream document, IJoinOptions joinOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Document joint. |
| joinOptions | IJoinOptions | Les options de jointure. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancé lorsque *document* est nul. |
| ArgumentNullException | Lancée lorsque *joinOptions* est nul. |

### Remarques

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Voir aussi

* interface [IMerger](../../imerger)
* interface [IJoinOptions](../../../groupdocs.merger.domain.options/ijoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IPageJoinOptions) {#join_3}

Fusionne les documents en un seul document.

```csharp
public IMerger Join(Stream document, IPageJoinOptions joinOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Document joint. |
| joinOptions | IPageJoinOptions | Les options de jointure. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancé lorsque *document* est nul. |
| ArgumentNullException | Lancée lorsque *joinOptions* est nul. |

### Remarques

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Voir aussi

* interface [IMerger](../../imerger)
* interface [IPageJoinOptions](../../../groupdocs.merger.domain.options/ipagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IImageJoinOptions) {#join_1}

Fusionne les documents en un seul document.

```csharp
public IMerger Join(Stream document, IImageJoinOptions joinOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Document joint. |
| joinOptions | IImageJoinOptions | Les options de fusion d'images. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancé lorsque *document* est nul. |
| ArgumentNullException | Lancée lorsque *joinOptions* est nul. |

### Remarques

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Voir aussi

* interface [IMerger](../../imerger)
* interface [IImageJoinOptions](../../../groupdocs.merger.domain.options/iimagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string) {#join_4}

Fusionne les documents en un seul document.

```csharp
public IMerger Join(string filePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Chemin d'accès du document joint. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *filePath* est nul ou vide. |

### Remarques

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Voir aussi

* interface [IMerger](../../imerger)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IJoinOptions) {#join_6}

Fusionne les documents en un seul document.

```csharp
public IMerger Join(string filePath, IJoinOptions joinOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Chemin d'accès du document joint. |
| joinOptions | IJoinOptions | Les options de jointure. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *filePath* est nul ou vide. |
| ArgumentNullException | Lancée lorsque *joinOptions* est nul. |

### Remarques

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Voir aussi

* interface [IMerger](../../imerger)
* interface [IJoinOptions](../../../groupdocs.merger.domain.options/ijoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IPageJoinOptions) {#join_7}

Fusionne les documents en un seul document.

```csharp
public IMerger Join(string filePath, IPageJoinOptions joinOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Chemin d'accès du document joint. |
| joinOptions | IPageJoinOptions | Les options de jointure. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *filePath* est nul ou vide. |
| ArgumentNullException | Lancée lorsque *joinOptions* est nul. |

### Remarques

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Voir aussi

* interface [IMerger](../../imerger)
* interface [IPageJoinOptions](../../../groupdocs.merger.domain.options/ipagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IImageJoinOptions) {#join_5}

Fusionne les documents en un seul document.

```csharp
public IMerger Join(string filePath, IImageJoinOptions joinOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Chemin d'accès du document joint. |
| joinOptions | IImageJoinOptions | Les options de fusion d'images. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *filePath* est nul ou vide. |
| ArgumentNullException | Lancée lorsque *joinOptions* est nul. |

### Remarques

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Voir aussi

* interface [IMerger](../../imerger)
* interface [IImageJoinOptions](../../../groupdocs.merger.domain.options/iimagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
