---
title: "LoadOptions"
second_title: "Riferimento API di GroupDocs.Merger per .NET"
description: "Inizializza una nuova istanza della classe LoadOptionsgroupdocs.merger.domain.options/loadoptions."
type: docs
weight: 10
url: /it/net/groupdocs.merger.domain.options/loadoptions/loadoptions/
---
## LoadOptions(FileType) {#constructor}

Inizializza una nuova istanza della classe [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(FileType fileType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | FileType | Il tipo di file da caricare. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *fileType* è nullo. |

### Vedi anche

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string) {#constructor_6}

Inizializza una nuova istanza della classe [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(string password)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | String | La password per aprire un file protetto da password. |

### Vedi anche

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string, Encoding) {#constructor_8}

Inizializza una nuova istanza della classe [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(string password, Encoding encoding)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | String | La password per aprire un file protetto da password. |
| encoding | Encoding | La codifica utilizzata durante l'apertura di file basati su testo come [`CSV`](../../../groupdocs.merger.domain/filetype/csv) o [`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *encoding* è nullo. |

### Vedi anche

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string) {#constructor_4}

Inizializza una nuova istanza della classe [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(FileType fileType, string password)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | FileType | Il tipo di file da caricare. |
| password | String | La password per aprire un file protetto da password. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *fileType* è nullo. |

### Vedi anche

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string, Encoding) {#constructor_5}

Inizializza una nuova istanza della classe [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(FileType fileType, string password, Encoding encoding)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | FileType | Il tipo di file da caricare. |
| password | String | La password per aprire un file protetto da password. |
| encoding | Encoding | La codifica utilizzata durante l'apertura di file basati su testo come [`CSV`](../../../groupdocs.merger.domain/filetype/csv) o [`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *fileType* è nullo. |
| ArgumentNullException | Generata quando *encoding* è nullo. |

### Vedi anche

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string, FileType, string, Encoding) {#constructor_7}

Inizializza una nuova istanza della classe [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(string extension, FileType fileType, string password, Encoding encoding)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| estensione | String | L'estensione del file da caricare. |
| fileType | FileType | Il tipo di file da caricare. |
| password | String | La password per aprire un file protetto da password. |
| encoding | Encoding | La codifica utilizzata durante l'apertura di file basati su testo come [`CSV`](../../../groupdocs.merger.domain/filetype/csv) o [`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *fileType* è nullo. |
| ArgumentNullException | Generata quando *encoding* è nullo. |

### Vedi anche

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string, Encoding) {#constructor_3}

Inizializza una nuova istanza della classe [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password, Encoding encoding)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| iniFileType | FileType | Il tipo di file da inizializzare. |
| fileType | FileType | Il tipo di file da caricare. |
| password | String | La password per aprire un file protetto da password. |
| encoding | Encoding | La codifica utilizzata durante l'apertura di file basati su testo come [`CSV`](../../../groupdocs.merger.domain/filetype/csv) o [`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *iniFileType* è nullo. |
| ArgumentNullException | Generata quando *fileType* è nullo. |
| ArgumentNullException | Generata quando *encoding* è nullo. |

### Vedi anche

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string) {#constructor_2}

Inizializza una nuova istanza della classe [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| iniFileType | FileType | Il tipo di file da inizializzare. |
| fileType | FileType | Il tipo di file da caricare. |
| password | String | La password per aprire un file protetto da password. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *iniFileType* è nullo. |
| ArgumentNullException | Generata quando *fileType* è nullo. |

### Vedi anche

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType) {#constructor_1}

Inizializza una nuova istanza della classe [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(FileType iniFileType, FileType fileType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| iniFileType | FileType | Il tipo di file da inizializzare. |
| fileType | FileType | Il tipo di file da caricare. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *iniFileType* è nullo. |
| ArgumentNullException | Generata quando *fileType* è nullo. |

### Vedi anche

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
