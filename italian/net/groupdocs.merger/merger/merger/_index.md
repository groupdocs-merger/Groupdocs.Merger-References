---
title: Merger
second_title: Riferimento API GroupDocs.Merger per .NET
description: Inizializza una nuova istanza diMergergroupdocs.merger/merger classe.
type: docs
weight: 10
url: /it/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

Inizializza una nuova istanza di[`Merger`](../../merger) classe.

```csharp
public Merger(Stream document)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Il flusso leggibile. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*document* è zero. |

### Guarda anche

* class [Merger](../../merger)
* spazio dei nomi [GroupDocs.Merger](../../merger)
* assemblea [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

Inizializza una nuova istanza di[`Merger`](../../merger) classe.

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
| ArgumentNullException | Lanciato quando*document* è zero. |
| ArgumentNullException | Lanciato quando*loadOptions* è zero. |

### Guarda anche

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* spazio dei nomi [GroupDocs.Merger](../../merger)
* assemblea [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

Inizializza una nuova istanza di[`Merger`](../../merger) classe.

```csharp
public Merger(Stream document, MergerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Il flusso leggibile. |
| settings | MergerSettings | Le impostazioni di fusione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*document* è zero. |
| ArgumentNullException | Lanciato quando*settings* è zero. |

### Guarda anche

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* spazio dei nomi [GroupDocs.Merger](../../merger)
* assemblea [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

Inizializza una nuova istanza di[`Merger`](../../merger) classe.

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Il flusso leggibile. |
| loadOptions | ILoadOptions | Le opzioni di caricamento del documento. |
| settings | MergerSettings | Le impostazioni di fusione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*document* è zero. |
| ArgumentNullException | Lanciato quando*loadOptions* è zero. |
| ArgumentNullException | Lanciato quando*settings* è zero. |

### Guarda anche

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* spazio dei nomi [GroupDocs.Merger](../../merger)
* assemblea [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

Inizializza una nuova istanza di[`Merger`](../../merger) classe.

```csharp
public Merger(Func<Stream> getFileStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| getFileStream | Func`1 | Il metodo che restituisce un flusso leggibile. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*getFileStream* è zero. |

### Guarda anche

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* spazio dei nomi [GroupDocs.Merger](../../merger)
* assemblea [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

Inizializza una nuova istanza di[`Merger`](../../merger) classe.

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
| ArgumentNullException | Lanciato quando*getFileStream* è zero. |
| ArgumentNullException | Lanciato quando*loadOptions* è zero. |

### Guarda anche

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* spazio dei nomi [GroupDocs.Merger](../../merger)
* assemblea [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

Inizializza una nuova istanza di[`Merger`](../../merger) classe.

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| getFileStream | Func`1 | Il metodo che restituisce un flusso leggibile. |
| settings | MergerSettings | Le impostazioni di fusione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*getFileStream* è zero. |
| ArgumentNullException | Lanciato quando*settings* è zero. |

### Guarda anche

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* spazio dei nomi [GroupDocs.Merger](../../merger)
* assemblea [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

Inizializza una nuova istanza di[`Merger`](../../merger) classe.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| getFileStream | Func`1 | Il metodo che restituisce un flusso leggibile. |
| loadOptions | ILoadOptions | Le opzioni di caricamento del documento. |
| settings | MergerSettings | Le impostazioni di fusione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*getFileStream* è zero. |
| ArgumentNullException | Lanciato quando*loadOptions* è zero. |
| ArgumentNullException | Lanciato quando*settings* è zero. |

### Guarda anche

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* spazio dei nomi [GroupDocs.Merger](../../merger)
* assemblea [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

Inizializza una nuova istanza di[`Merger`](../../merger) classe.

```csharp
public Merger(string filePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*filePath* è nullo o vuoto. |

### Guarda anche

* class [Merger](../../merger)
* spazio dei nomi [GroupDocs.Merger](../../merger)
* assemblea [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

Inizializza una nuova istanza di[`Merger`](../../merger) classe.

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
| ArgumentNullException | Lanciato quando*filePath* è nullo o vuoto. |
| ArgumentNullException | Lanciato quando*loadOptions* è zero. |

### Guarda anche

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* spazio dei nomi [GroupDocs.Merger](../../merger)
* assemblea [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

Inizializza una nuova istanza di[`Merger`](../../merger) classe.

```csharp
public Merger(string filePath, MergerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file. |
| settings | MergerSettings | Le impostazioni di fusione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*filePath* è nullo o vuoto. |
| ArgumentNullException | Lanciato quando*settings* è zero. |

### Guarda anche

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* spazio dei nomi [GroupDocs.Merger](../../merger)
* assemblea [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

Inizializza una nuova istanza di[`Merger`](../../merger) classe.

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file. |
| loadOptions | ILoadOptions | Le opzioni di caricamento del documento. |
| settings | MergerSettings | Le impostazioni di fusione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*filePath* è nullo o vuoto. |
| ArgumentNullException | Lanciato quando*loadOptions* è zero. |
| ArgumentNullException | Lanciato quando*settings* è zero. |

### Guarda anche

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* spazio dei nomi [GroupDocs.Merger](../../merger)
* assemblea [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
