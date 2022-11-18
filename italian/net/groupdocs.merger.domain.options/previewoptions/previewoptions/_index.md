---
title: PreviewOptions
second_title: Riferimento API GroupDocs.Merger per .NET
description: Inizializza una nuova istanza diPreviewOptionsgroupdocs.merger.domain.options/previewoptions classe.
type: docs
weight: 10
url: /it/net/groupdocs.merger.domain.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream, PreviewMode) {#constructor_4}

Inizializza una nuova istanza di[`PreviewOptions`](../../previewoptions) classe.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che crea un'istanza del flusso utilizzato per scrivere i dati della pagina di output. |
| previewMode | PreviewMode | La modalità di anteprima di[`Mode`](../mode) |

### Guarda anche

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../previewoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int[]) {#constructor_7}

Inizializza una nuova istanza di[`PreviewOptions`](../../previewoptions) classe.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int[] pageNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che crea un'istanza del flusso utilizzato per scrivere i dati della pagina di output. |
| previewMode | PreviewMode | La modalità di anteprima di[`Mode`](../mode) |
| pageNumbers | Int32[] | Numeri di pagina. |

### Guarda anche

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../previewoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int) {#constructor_5}

Inizializza una nuova istanza di[`PreviewOptions`](../../previewoptions) classe.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che crea un'istanza del flusso utilizzato per scrivere i dati della pagina di output. |
| previewMode | PreviewMode | La modalità di anteprima di[`Mode`](../mode) |
| startNumber | Int32 | Il numero della pagina iniziale. |
| endNumber | Int32 | Il numero di fine pagina. |

### Guarda anche

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../previewoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int, RangeMode) {#constructor_6}

Inizializza una nuova istanza di[`PreviewOptions`](../../previewoptions) classe.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber, RangeMode mode)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che crea un'istanza del flusso utilizzato per scrivere i dati della pagina di output. |
| previewMode | PreviewMode | La modalità di anteprima di[`Mode`](../mode) |
| startNumber | Int32 | Il numero della pagina iniziale. |
| endNumber | Int32 | Il numero di fine pagina. |
| mode | RangeMode | La modalità gamma. |

### Guarda anche

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../previewoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode) {#constructor}

Inizializza una nuova istanza di[`PreviewOptions`](../../previewoptions) classe.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che crea un'istanza del flusso utilizzato per scrivere i dati della pagina di output. |
| releasePageStream | ReleasePageStream | Il metodo che rilascia il flusso creato dal metodo createPageStream. |
| previewMode | PreviewMode | La modalità di anteprima di[`Mode`](../mode) |

### Guarda anche

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../previewoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int[]) {#constructor_3}

Inizializza una nuova istanza di[`PreviewOptions`](../../previewoptions) classe.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int[] pageNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che crea un'istanza del flusso utilizzato per scrivere i dati della pagina di output. |
| releasePageStream | ReleasePageStream | Il metodo che rilascia il flusso creato dal metodo createPageStream. |
| previewMode | PreviewMode | La modalità di anteprima di[`Mode`](../mode) |
| pageNumbers | Int32[] | Numeri di pagina. |

### Guarda anche

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../previewoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int) {#constructor_1}

Inizializza una nuova istanza di[`PreviewOptions`](../../previewoptions) classe.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che crea un'istanza del flusso utilizzato per scrivere i dati della pagina di output. |
| releasePageStream | ReleasePageStream | Il metodo che rilascia il flusso creato dal metodo createPageStream. |
| previewMode | PreviewMode | La modalità di anteprima di[`Mode`](../mode) |
| startNumber | Int32 | Il numero della pagina iniziale. |
| endNumber | Int32 | Il numero di fine pagina. |

### Guarda anche

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../previewoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int, RangeMode) {#constructor_2}

Inizializza una nuova istanza di[`PreviewOptions`](../../previewoptions) classe.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber, RangeMode mode)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che crea un'istanza del flusso utilizzato per scrivere i dati della pagina di output. |
| releasePageStream | ReleasePageStream | Il metodo che rilascia il flusso creato dal metodo createPageStream. |
| previewMode | PreviewMode | La modalità di anteprima di[`Mode`](../mode) |
| startNumber | Int32 | Il numero della pagina iniziale. |
| endNumber | Int32 | Il numero di fine pagina. |
| mode | RangeMode | La modalità gamma. |

### Guarda anche

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../previewoptions)
* assemblea [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
