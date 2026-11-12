---
title: "Fusionneur"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Initialise une nouvelle instance de la classe Mergergroupdocs.merger/merger."
type: docs
weight: 10
url: /fr/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

Initialise une nouvelle instance de la classe [`Merger`](../../merger).

```csharp
public Merger(Stream document)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Le flux lisible. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancé lorsque *document* est nul. |

### Voir aussi

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

Initialise une nouvelle instance de la classe [`Merger`](../../merger).

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Le flux lisible. |
| loadOptions | ILoadOptions | Les options de chargement du document. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancé lorsque *document* est nul. |
| ArgumentNullException | Lancée lorsque *loadOptions* est nul. |

### Voir aussi

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

Initialise une nouvelle instance de la classe [`Merger`](../../merger).

```csharp
public Merger(Stream document, MergerSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Le flux lisible. |
| settings | MergerSettings | Les paramètres du Merger. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancé lorsque *document* est nul. |
| ArgumentNullException | Lancée lorsque *settings* est nul. |

### Voir aussi

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

Initialise une nouvelle instance de la classe [`Merger`](../../merger).

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Stream | Le flux lisible. |
| loadOptions | ILoadOptions | Les options de chargement du document. |
| settings | MergerSettings | Les paramètres du Merger. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancé lorsque *document* est nul. |
| ArgumentNullException | Lancée lorsque *loadOptions* est nul. |
| ArgumentNullException | Lancée lorsque *settings* est nul. |

### Voir aussi

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

Initialise une nouvelle instance de la classe [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| getFileStream | Func`1 | La méthode qui renvoie un flux lisible. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *getFileStream* est nul. |

### Voir aussi

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

Initialise une nouvelle instance de la classe [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| getFileStream | Func`1 | La méthode qui renvoie un flux lisible. |
| loadOptions | ILoadOptions | Les options de chargement du document. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *getFileStream* est nul. |
| ArgumentNullException | Lancée lorsque *loadOptions* est nul. |

### Voir aussi

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

Initialise une nouvelle instance de la classe [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| getFileStream | Func`1 | La méthode qui renvoie un flux lisible. |
| settings | MergerSettings | Les paramètres du Merger. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *getFileStream* est nul. |
| ArgumentNullException | Lancée lorsque *settings* est nul. |

### Voir aussi

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

Initialise une nouvelle instance de la classe [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| getFileStream | Func`1 | La méthode qui renvoie un flux lisible. |
| loadOptions | ILoadOptions | Les options de chargement du document. |
| settings | MergerSettings | Les paramètres du Merger. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *getFileStream* est nul. |
| ArgumentNullException | Lancée lorsque *loadOptions* est nul. |
| ArgumentNullException | Lancée lorsque *settings* est nul. |

### Voir aussi

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

Initialise une nouvelle instance de la classe [`Merger`](../../merger).

```csharp
public Merger(string filePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *filePath* est nul ou vide. |

### Voir aussi

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

Initialise une nouvelle instance de la classe [`Merger`](../../merger).

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier. |
| loadOptions | ILoadOptions | Les options de chargement du document. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *filePath* est nul ou vide. |
| ArgumentNullException | Lancée lorsque *loadOptions* est nul. |

### Voir aussi

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

Initialise une nouvelle instance de la classe [`Merger`](../../merger).

```csharp
public Merger(string filePath, MergerSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier. |
| settings | MergerSettings | Les paramètres du Merger. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *filePath* est nul ou vide. |
| ArgumentNullException | Lancée lorsque *settings* est nul. |

### Voir aussi

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

Initialise une nouvelle instance de la classe [`Merger`](../../merger).

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier. |
| loadOptions | ILoadOptions | Les options de chargement du document. |
| settings | MergerSettings | Les paramètres du Merger. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *filePath* est nul ou vide. |
| ArgumentNullException | Lancée lorsque *loadOptions* est nul. |
| ArgumentNullException | Lancée lorsque *settings* est nul. |

### Voir aussi

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
