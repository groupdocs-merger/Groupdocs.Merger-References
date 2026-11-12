---
title: "Unione"
second_title: "Riferimento API di GroupDocs.Merger per .NET"
description: "Inizializza una nuova istanza della classe Mergergroupdocs.merger/merger."
type: docs
weight: 10
url: /it/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

Inizializza una nuova istanza della classe [`Merger`](../../merger).

```csharp
public Merger(Stream document)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Il flusso leggibile. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *document* è nullo. |

### Vedi anche

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

Inizializza una nuova istanza della classe [`Merger`](../../merger).

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Il flusso leggibile. |
| loadOptions | ILoadOptions | Le opzioni di caricamento del documento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *document* è nullo. |
| ArgumentNullException | Lanciata quando *loadOptions* è null. |

### Vedi anche

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

Inizializza una nuova istanza della classe [`Merger`](../../merger).

```csharp
public Merger(Stream document, MergerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Il flusso leggibile. |
| settings | MergerSettings | Le impostazioni di Merger. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *document* è nullo. |
| ArgumentNullException | Lanciata quando *settings* è null. |

### Vedi anche

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

Inizializza una nuova istanza della classe [`Merger`](../../merger).

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Il flusso leggibile. |
| loadOptions | ILoadOptions | Le opzioni di caricamento del documento. |
| settings | MergerSettings | Le impostazioni di Merger. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *document* è nullo. |
| ArgumentNullException | Lanciata quando *loadOptions* è null. |
| ArgumentNullException | Lanciata quando *settings* è null. |

### Vedi anche

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

Inizializza una nuova istanza della classe [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| getFileStream | Func`1 | Il metodo che restituisce un flusso leggibile. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciata quando *getFileStream* è null. |

### Vedi anche

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

Inizializza una nuova istanza della classe [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| getFileStream | Func`1 | Il metodo che restituisce un flusso leggibile. |
| loadOptions | ILoadOptions | Le opzioni di caricamento del documento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciata quando *getFileStream* è null. |
| ArgumentNullException | Lanciata quando *loadOptions* è null. |

### Vedi anche

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

Inizializza una nuova istanza della classe [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| getFileStream | Func`1 | Il metodo che restituisce un flusso leggibile. |
| settings | MergerSettings | Le impostazioni di Merger. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciata quando *getFileStream* è null. |
| ArgumentNullException | Lanciata quando *settings* è null. |

### Vedi anche

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

Inizializza una nuova istanza della classe [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| getFileStream | Func`1 | Il metodo che restituisce un flusso leggibile. |
| loadOptions | ILoadOptions | Le opzioni di caricamento del documento. |
| settings | MergerSettings | Le impostazioni di Merger. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciata quando *getFileStream* è null. |
| ArgumentNullException | Lanciata quando *loadOptions* è null. |
| ArgumentNullException | Lanciata quando *settings* è null. |

### Vedi anche

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

Inizializza una nuova istanza della classe [`Merger`](../../merger).

```csharp
public Merger(string filePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciata quando *filePath* è null o vuoto. |

### Vedi anche

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

Inizializza una nuova istanza della classe [`Merger`](../../merger).

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file. |
| loadOptions | ILoadOptions | Le opzioni di caricamento del documento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciata quando *filePath* è null o vuoto. |
| ArgumentNullException | Lanciata quando *loadOptions* è null. |

### Vedi anche

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

Inizializza una nuova istanza della classe [`Merger`](../../merger).

```csharp
public Merger(string filePath, MergerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file. |
| settings | MergerSettings | Le impostazioni di Merger. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciata quando *filePath* è null o vuoto. |
| ArgumentNullException | Lanciata quando *settings* è null. |

### Vedi anche

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

Inizializza una nuova istanza della classe [`Merger`](../../merger).

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file. |
| loadOptions | ILoadOptions | Le opzioni di caricamento del documento. |
| settings | MergerSettings | Le impostazioni di Merger. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciata quando *filePath* è null o vuoto. |
| ArgumentNullException | Lanciata quando *loadOptions* è null. |
| ArgumentNullException | Lanciata quando *settings* è null. |

### Vedi anche

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
