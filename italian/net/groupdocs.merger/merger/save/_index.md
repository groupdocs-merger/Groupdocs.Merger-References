---
title: Save
second_title: Riferimento API GroupDocs.Merger per .NET
description: Salva il documento dei risultati nello streamdocument .
type: docs
weight: 150
url: /it/net/groupdocs.merger/merger/save/
---
## Save(Stream) {#save}

Salva il documento dei risultati nello stream*document* .

```csharp
public void Save(Stream document)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Stream | Il flusso di documenti. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*document* è zero. |

### Guarda anche

* class [Merger](../../merger)
* spazio dei nomi [GroupDocs.Merger](../../merger)
* assemblea [GroupDocs.Merger](../../../)

---

## Save(string) {#save_1}

Salva il file del documento dei risultati in*filePath* .

```csharp
public void Save(string filePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il nome del file o il percorso completo del file. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*filePath* è nullo o vuoto. |

### Guarda anche

* class [Merger](../../merger)
* spazio dei nomi [GroupDocs.Merger](../../merger)
* assemblea [GroupDocs.Merger](../../../)

---

## Save(string, bool) {#save_2}

Salva il file del documento dei risultati in*filePath* .

```csharp
public void Save(string filePath, bool useDefaultDirectory)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso o il nome del file in caso di utilizzo della directory predefinita. |
| useDefaultDirectory | Boolean | Usa la directory predefinita dalle impostazioni. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*filePath* è nullo o vuoto. |

### Guarda anche

* class [Merger](../../merger)
* spazio dei nomi [GroupDocs.Merger](../../merger)
* assemblea [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
