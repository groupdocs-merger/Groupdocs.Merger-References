---
title: TextSplitOptions
second_title: Riferimento API GroupDocs.Merger per .NET
description: Inizializza una nuova istanza diTextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions classe.
type: docs
weight: 10
url: /it/net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

Inizializza una nuova istanza di[`TextSplitOptions`](../../textsplitoptions) classe.

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | String | Il formato del percorso del file, ad esempio "c:/split{0}.doc" o "c:/split{0}.{1}" con estensione già definita. |
| lineNumbers | Int32[] | Numeri di riga per la suddivisione del testo. |

### Guarda anche

* class [TextSplitOptions](../../textsplitoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

Inizializza una nuova istanza di[`TextSplitOptions`](../../textsplitoptions) classe.

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | String | Il formato del percorso del file, ad esempio "c:/split{0}.doc" o "c:/split{0}.{1}" con estensione già definita. |
| mode | TextSplitMode | Modalità per la divisione del testo. |
| lineNumbers | Int32[] | Numeri di riga per la suddivisione del testo. |

### Guarda anche

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

Inizializza una nuova istanza di[`TextSplitOptions`](../../textsplitoptions) classe.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Il metodo che crea un'istanza del flusso utilizzato per scrivere i dati suddivisi in output. |
| lineNumbers | Int32[] | Numeri di riga per la suddivisione del testo. |

### Guarda anche

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

Inizializza una nuova istanza di[`TextSplitOptions`](../../textsplitoptions) classe.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Il metodo che crea un'istanza del flusso utilizzato per scrivere i dati suddivisi in output. |
| mode | TextSplitMode | Modalità per la divisione del testo. |
| lineNumbers | Int32[] | Numeri di riga per la suddivisione del testo. |

### Guarda anche

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

Inizializza una nuova istanza di[`TextSplitOptions`](../../textsplitoptions) classe.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Il metodo che crea un'istanza del flusso utilizzato per scrivere i dati suddivisi in output. |
| releaseSplitStream | ReleaseSplitStream | Il metodo che rilascia il flusso creato dal metodo createPageStream. |
| lineNumbers | Int32[] | Numeri di riga per la suddivisione del testo. |

### Guarda anche

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

Inizializza una nuova istanza di[`TextSplitOptions`](../../textsplitoptions) classe.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Il metodo che crea un'istanza del flusso utilizzato per scrivere i dati suddivisi in output. |
| releaseSplitStream | ReleaseSplitStream | Il metodo che rilascia il flusso creato dal metodo createPageStream. |
| mode | TextSplitMode | Modalità per la divisione del testo. |
| lineNumbers | Int32[] | Numeri di riga per la suddivisione del testo. |

### Guarda anche

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* assemblea [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
