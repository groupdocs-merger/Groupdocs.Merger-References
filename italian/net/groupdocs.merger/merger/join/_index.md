---
title: "Join"
second_title: "Riferimento API di GroupDocs.Merger per .NET"
description: "Unisce i documenti in un unico documento."
type: docs
weight: 120
url: /it/net/groupdocs.merger/merger/join/
---
## Join(Stream) {#join}

Unisce i documenti in un unico documento.

```csharp
public IMerger Join(Stream document)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Documento unito. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *document* è nullo. |

### Osservazioni

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Vedi anche

* interface [IMerger](../../imerger)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IJoinOptions) {#join_2}

Unisce i documenti in un unico documento.

```csharp
public IMerger Join(Stream document, IJoinOptions joinOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Documento unito. |
| joinOptions | IJoinOptions | Le opzioni di join. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *document* è nullo. |
| ArgumentNullException | Lanciata quando *joinOptions* è null. |

### Osservazioni

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Vedi anche

* interface [IMerger](../../imerger)
* interface [IJoinOptions](../../../groupdocs.merger.domain.options/ijoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IPageJoinOptions) {#join_3}

Unisce i documenti in un unico documento.

```csharp
public IMerger Join(Stream document, IPageJoinOptions joinOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Documento unito. |
| joinOptions | IPageJoinOptions | Le opzioni di join. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *document* è nullo. |
| ArgumentNullException | Lanciata quando *joinOptions* è null. |

### Osservazioni

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Vedi anche

* interface [IMerger](../../imerger)
* interface [IPageJoinOptions](../../../groupdocs.merger.domain.options/ipagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IImageJoinOptions) {#join_1}

Unisce i documenti in un unico documento.

```csharp
public IMerger Join(Stream document, IImageJoinOptions joinOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Documento unito. |
| joinOptions | IImageJoinOptions | Le opzioni di unione delle immagini. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *document* è nullo. |
| ArgumentNullException | Lanciata quando *joinOptions* è null. |

### Osservazioni

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Vedi anche

* interface [IMerger](../../imerger)
* interface [IImageJoinOptions](../../../groupdocs.merger.domain.options/iimagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string) {#join_4}

Unisce i documenti in un unico documento.

```csharp
public IMerger Join(string filePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Percorso file del documento unito. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciata quando *filePath* è null o vuoto. |

### Osservazioni

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Vedi anche

* interface [IMerger](../../imerger)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IJoinOptions) {#join_6}

Unisce i documenti in un unico documento.

```csharp
public IMerger Join(string filePath, IJoinOptions joinOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Percorso file del documento unito. |
| joinOptions | IJoinOptions | Le opzioni di join. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciata quando *filePath* è null o vuoto. |
| ArgumentNullException | Lanciata quando *joinOptions* è null. |

### Osservazioni

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Vedi anche

* interface [IMerger](../../imerger)
* interface [IJoinOptions](../../../groupdocs.merger.domain.options/ijoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IPageJoinOptions) {#join_7}

Unisce i documenti in un unico documento.

```csharp
public IMerger Join(string filePath, IPageJoinOptions joinOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Percorso file del documento unito. |
| joinOptions | IPageJoinOptions | Le opzioni di join. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciata quando *filePath* è null o vuoto. |
| ArgumentNullException | Lanciata quando *joinOptions* è null. |

### Osservazioni

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Vedi anche

* interface [IMerger](../../imerger)
* interface [IPageJoinOptions](../../../groupdocs.merger.domain.options/ipagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IImageJoinOptions) {#join_5}

Unisce i documenti in un unico documento.

```csharp
public IMerger Join(string filePath, IImageJoinOptions joinOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Percorso file del documento unito. |
| joinOptions | IImageJoinOptions | Le opzioni di unione delle immagini. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciata quando *filePath* è null o vuoto. |
| ArgumentNullException | Lanciata quando *joinOptions* è null. |

### Osservazioni

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Vedi anche

* interface [IMerger](../../imerger)
* interface [IImageJoinOptions](../../../groupdocs.merger.domain.options/iimagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
