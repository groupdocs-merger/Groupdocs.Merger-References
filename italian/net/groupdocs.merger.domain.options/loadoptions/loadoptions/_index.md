---
title: LoadOptions
second_title: Riferimento API GroupDocs.Merger per .NET
description: Inizializza una nuova istanza diLoadOptionsgroupdocs.merger.domain.options/loadoptions classe.
type: docs
weight: 10
url: /it/net/groupdocs.merger.domain.options/loadoptions/loadoptions/
---
## LoadOptions(FileType) {#constructor}

Inizializza una nuova istanza di[`LoadOptions`](../../loadoptions) classe.

```csharp
public LoadOptions(FileType fileType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | FileType | Il tipo di file da caricare. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*fileType* è zero. |

### Guarda anche

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../loadoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## LoadOptions(string) {#constructor_6}

Inizializza una nuova istanza di[`LoadOptions`](../../loadoptions) classe.

```csharp
public LoadOptions(string password)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | String | La password per l'apertura del file protetto da password. |

### Guarda anche

* class [LoadOptions](../../loadoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../loadoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## LoadOptions(string, Encoding) {#constructor_8}

Inizializza una nuova istanza di[`LoadOptions`](../../loadoptions) classe.

```csharp
public LoadOptions(string password, Encoding encoding)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | String | La password per l'apertura del file protetto da password. |
| encoding | Encoding | La codifica utilizzata durante l'apertura di file basati su testo come[`CSV`](../../../groupdocs.merger.domain/filetype/csv) O[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*encoding* è zero. |

### Guarda anche

* class [LoadOptions](../../loadoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../loadoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string) {#constructor_4}

Inizializza una nuova istanza di[`LoadOptions`](../../loadoptions) classe.

```csharp
public LoadOptions(FileType fileType, string password)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | FileType | Il tipo di file da caricare. |
| password | String | La password per l'apertura del file protetto da password. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*fileType* è zero. |

### Guarda anche

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../loadoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string, Encoding) {#constructor_5}

Inizializza una nuova istanza di[`LoadOptions`](../../loadoptions) classe.

```csharp
public LoadOptions(FileType fileType, string password, Encoding encoding)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | FileType | Il tipo di file da caricare. |
| password | String | La password per l'apertura del file protetto da password. |
| encoding | Encoding | La codifica utilizzata durante l'apertura di file basati su testo come[`CSV`](../../../groupdocs.merger.domain/filetype/csv) O[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*fileType* è zero. |
| ArgumentNullException | Lanciato quando*encoding* è zero. |

### Guarda anche

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../loadoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## LoadOptions(string, FileType, string, Encoding) {#constructor_7}

Inizializza una nuova istanza di[`LoadOptions`](../../loadoptions) classe.

```csharp
public LoadOptions(string extension, FileType fileType, string password, Encoding encoding)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| extension | String | L'estensione del file da caricare. |
| fileType | FileType | Il tipo di file da caricare. |
| password | String | La password per l'apertura del file protetto da password. |
| encoding | Encoding | La codifica utilizzata durante l'apertura di file basati su testo come[`CSV`](../../../groupdocs.merger.domain/filetype/csv) O[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*fileType* è zero. |
| ArgumentNullException | Lanciato quando*encoding* è zero. |

### Guarda anche

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../loadoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string, Encoding) {#constructor_3}

Inizializza una nuova istanza di[`LoadOptions`](../../loadoptions) classe.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password, Encoding encoding)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| iniFileType | FileType | Il tipo di file da inizializzare. |
| fileType | FileType | Il tipo di file da caricare. |
| password | String | La password per l'apertura del file protetto da password. |
| encoding | Encoding | La codifica utilizzata durante l'apertura di file basati su testo come[`CSV`](../../../groupdocs.merger.domain/filetype/csv) O[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*iniFileType* è zero. |
| ArgumentNullException | Lanciato quando*fileType* è zero. |
| ArgumentNullException | Lanciato quando*encoding* è zero. |

### Guarda anche

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../loadoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string) {#constructor_2}

Inizializza una nuova istanza di[`LoadOptions`](../../loadoptions) classe.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| iniFileType | FileType | Il tipo di file da inizializzare. |
| fileType | FileType | Il tipo di file da caricare. |
| password | String | La password per l'apertura del file protetto da password. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*iniFileType* è zero. |
| ArgumentNullException | Lanciato quando*fileType* è zero. |

### Guarda anche

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../loadoptions)
* assemblea [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType) {#constructor_1}

Inizializza una nuova istanza di[`LoadOptions`](../../loadoptions) classe.

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
| ArgumentNullException | Lanciato quando*iniFileType* è zero. |
| ArgumentNullException | Lanciato quando*fileType* è zero. |

### Guarda anche

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* spazio dei nomi [GroupDocs.Merger.Domain.Options](../../loadoptions)
* assemblea [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
