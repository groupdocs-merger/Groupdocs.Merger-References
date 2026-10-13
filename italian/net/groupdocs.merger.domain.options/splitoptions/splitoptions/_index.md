---
title: "SplitOptions"
second_title: "Riferimento API di GroupDocs.Merger per .NET"
description: "Inizializza una nuova istanza della classe SplitOptionsgroupdocs.merger.domain.options/splitoptions."
type: docs
weight: 10
url: /it/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

Inizializza una nuova istanza della classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | String | Il formato del percorso file, ad es. 'c:/split{0}.doc' o 'c:/split{0}.{1}', con estensione già predefinita. |
| pageNumbers | Int32[] | Numeri di pagina. |

### Vedi anche

* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

Inizializza una nuova istanza della classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | String | Il formato del percorso file, ad es. 'c:/split{0}.doc' o 'c:/split{0}.{1}', con estensione già predefinita. |
| pageNumbers | Int32[] | Numeri di pagina. |
| splitMode | SplitMode | La modalità di divisione di [`Mode`](../mode). |

### Vedi anche

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

Inizializza una nuova istanza della classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | String | Il formato del percorso file, ad es. 'c:/split{0}.doc' o 'c:/split{0}.{1}', con estensione già predefinita. |
| startNumber | Int32 | Il numero di pagina iniziale. |
| endNumber | Int32 | Il numero di pagina finale. |

### Vedi anche

* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

Inizializza una nuova istanza della classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | String | Il formato del percorso file, ad es. 'c:/split{0}.doc' o 'c:/split{0}.{1}', con estensione già predefinita. |
| startNumber | Int32 | Il numero di pagina iniziale. |
| endNumber | Int32 | Il numero di pagina finale. |
| mode | RangeMode | La modalità di intervallo. |

### Vedi anche

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

Inizializza una nuova istanza della classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Il metodo che istanzia lo stream usato per scrivere i dati di output divisi. |

### Vedi anche

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

Inizializza una nuova istanza della classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Il metodo che istanzia lo stream usato per scrivere i dati di output divisi. |
| pageNumbers | Int32[] | Numeri di pagina. |

### Vedi anche

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

Inizializza una nuova istanza della classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Il metodo che istanzia lo stream usato per scrivere i dati di output divisi. |
| pageNumbers | Int32[] | Numeri di pagina. |
| splitMode | SplitMode | La modalità di divisione di [`Mode`](../mode). |

### Vedi anche

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

Inizializza una nuova istanza della classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Il metodo che istanzia lo stream usato per scrivere i dati di output divisi. |
| startNumber | Int32 | Il numero di pagina iniziale. |
| endNumber | Int32 | Il numero di pagina finale. |

### Vedi anche

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

Inizializza una nuova istanza della classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Il metodo che istanzia lo stream usato per scrivere i dati di output divisi. |
| startNumber | Int32 | Il numero di pagina iniziale. |
| endNumber | Int32 | Il numero di pagina finale. |
| mode | RangeMode | La modalità di intervallo. |

### Vedi anche

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

Inizializza una nuova istanza della classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Il metodo che istanzia lo stream usato per scrivere i dati di output divisi. |
| releaseSplitStream | ReleaseSplitStream | Il metodo che rilascia lo stream creato dal metodo createPageStream. |

### Vedi anche

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

Inizializza una nuova istanza della classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Il metodo che istanzia lo stream usato per scrivere i dati di output divisi. |
| releaseSplitStream | ReleaseSplitStream | Il metodo che rilascia lo stream creato dal metodo createPageStream. |
| pageNumbers | Int32[] | Numeri di pagina. |

### Vedi anche

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

Inizializza una nuova istanza della classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Il metodo che istanzia lo stream usato per scrivere i dati di output divisi. |
| releaseSplitStream | ReleaseSplitStream | Il metodo che rilascia lo stream creato dal metodo createPageStream. |
| pageNumbers | Int32[] | Numeri di pagina. |
| splitMode | SplitMode | La modalità di divisione di [`Mode`](../mode). |

### Vedi anche

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

Inizializza una nuova istanza della classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Il metodo che istanzia lo stream usato per scrivere i dati di output divisi. |
| releaseSplitStream | ReleaseSplitStream | Il metodo che rilascia lo stream creato dal metodo createPageStream. |
| startNumber | Int32 | Il numero di pagina iniziale. |
| endNumber | Int32 | Il numero di pagina finale. |

### Vedi anche

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

Inizializza una nuova istanza della classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Il metodo che istanzia lo stream usato per scrivere i dati di output divisi. |
| releaseSplitStream | ReleaseSplitStream | Il metodo che rilascia lo stream creato dal metodo createPageStream. |
| startNumber | Int32 | Il numero di pagina iniziale. |
| endNumber | Int32 | Il numero di pagina finale. |
| mode | RangeMode | La modalità di intervallo. |

### Vedi anche

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
