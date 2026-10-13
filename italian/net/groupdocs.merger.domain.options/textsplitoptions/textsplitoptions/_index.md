---
title: "TextSplitOptions"
second_title: "Riferimento API di GroupDocs.Merger per .NET"
description: "Inizializza una nuova istanza della classe TextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions."
type: docs
weight: 10
url: /it/net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

Inizializza una nuova istanza della classe [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | String | Il formato del percorso file, ad es. 'c:/split{0}.doc' o 'c:/split{0}.{1}' con estensione già definita. |
| lineNumbers | Int32[] | Numeri di riga per la suddivisione del testo. |

### Vedi anche

* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

Inizializza una nuova istanza della classe [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | String | Il formato del percorso file, ad es. 'c:/split{0}.doc' o 'c:/split{0}.{1}' con estensione già definita. |
| mode | TextSplitMode | Modalità per la suddivisione del testo. |
| lineNumbers | Int32[] | Numeri di riga per la suddivisione del testo. |

### Vedi anche

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

Inizializza una nuova istanza della classe [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Il metodo che istanzia lo stream usato per scrivere i dati di output divisi. |
| lineNumbers | Int32[] | Numeri di riga per la suddivisione del testo. |

### Vedi anche

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

Inizializza una nuova istanza della classe [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Il metodo che istanzia lo stream usato per scrivere i dati di output divisi. |
| mode | TextSplitMode | Modalità per la suddivisione del testo. |
| lineNumbers | Int32[] | Numeri di riga per la suddivisione del testo. |

### Vedi anche

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

Inizializza una nuova istanza della classe [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Il metodo che istanzia lo stream usato per scrivere i dati di output divisi. |
| releaseSplitStream | ReleaseSplitStream | Il metodo che rilascia lo stream creato dal metodo createPageStream. |
| lineNumbers | Int32[] | Numeri di riga per la suddivisione del testo. |

### Vedi anche

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

Inizializza una nuova istanza della classe [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Il metodo che istanzia lo stream usato per scrivere i dati di output divisi. |
| releaseSplitStream | ReleaseSplitStream | Il metodo che rilascia lo stream creato dal metodo createPageStream. |
| mode | TextSplitMode | Modalità per la suddivisione del testo. |
| lineNumbers | Int32[] | Numeri di riga per la suddivisione del testo. |

### Vedi anche

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
