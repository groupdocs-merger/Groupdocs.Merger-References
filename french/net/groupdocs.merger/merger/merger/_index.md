---
title: Merger
second_title: Référence de l'API GroupDocs.Merger pour .NET
description: Initialise la nouvelle instance deMergergroupdocs.merger/merger classe.
type: docs
weight: 10
url: /fr/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

Initialise la nouvelle instance de[`Merger`](../../merger) classe.

```csharp
public Merger(Stream document)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Stream | Le flux lisible. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*document* est nul. |

### Voir également

* class [Merger](../../merger)
* espace de noms [GroupDocs.Merger](../../merger)
* Assemblée [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

Initialise la nouvelle instance de[`Merger`](../../merger) classe.

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Stream | Le flux lisible. |
| loadOptions | ILoadOptions | Les options de chargement des documents. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*document* est nul. |
| ArgumentNullException | Jeté quand*loadOptions* est nul. |

### Voir également

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* espace de noms [GroupDocs.Merger](../../merger)
* Assemblée [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

Initialise la nouvelle instance de[`Merger`](../../merger) classe.

```csharp
public Merger(Stream document, MergerSettings settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Stream | Le flux lisible. |
| settings | MergerSettings | Les paramètres de fusion. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*document* est nul. |
| ArgumentNullException | Jeté quand*settings* est nul. |

### Voir également

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* espace de noms [GroupDocs.Merger](../../merger)
* Assemblée [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

Initialise la nouvelle instance de[`Merger`](../../merger) classe.

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Stream | Le flux lisible. |
| loadOptions | ILoadOptions | Les options de chargement des documents. |
| settings | MergerSettings | Les paramètres de fusion. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*document* est nul. |
| ArgumentNullException | Jeté quand*loadOptions* est nul. |
| ArgumentNullException | Jeté quand*settings* est nul. |

### Voir également

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* espace de noms [GroupDocs.Merger](../../merger)
* Assemblée [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

Initialise la nouvelle instance de[`Merger`](../../merger) classe.

```csharp
public Merger(Func<Stream> getFileStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| getFileStream | Func`1 | La méthode qui renvoie un flux lisible. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*getFileStream* est nul. |

### Voir également

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* espace de noms [GroupDocs.Merger](../../merger)
* Assemblée [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

Initialise la nouvelle instance de[`Merger`](../../merger) classe.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| getFileStream | Func`1 | La méthode qui renvoie un flux lisible. |
| loadOptions | ILoadOptions | Les options de chargement des documents. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*getFileStream* est nul. |
| ArgumentNullException | Jeté quand*loadOptions* est nul. |

### Voir également

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* espace de noms [GroupDocs.Merger](../../merger)
* Assemblée [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

Initialise la nouvelle instance de[`Merger`](../../merger) classe.

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| getFileStream | Func`1 | La méthode qui renvoie un flux lisible. |
| settings | MergerSettings | Les paramètres de fusion. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*getFileStream* est nul. |
| ArgumentNullException | Jeté quand*settings* est nul. |

### Voir également

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* espace de noms [GroupDocs.Merger](../../merger)
* Assemblée [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

Initialise la nouvelle instance de[`Merger`](../../merger) classe.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| getFileStream | Func`1 | La méthode qui renvoie un flux lisible. |
| loadOptions | ILoadOptions | Les options de chargement des documents. |
| settings | MergerSettings | Les paramètres de fusion. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*getFileStream* est nul. |
| ArgumentNullException | Jeté quand*loadOptions* est nul. |
| ArgumentNullException | Jeté quand*settings* est nul. |

### Voir également

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* espace de noms [GroupDocs.Merger](../../merger)
* Assemblée [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

Initialise la nouvelle instance de[`Merger`](../../merger) classe.

```csharp
public Merger(string filePath)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*filePath* est nul ou vide. |

### Voir également

* class [Merger](../../merger)
* espace de noms [GroupDocs.Merger](../../merger)
* Assemblée [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

Initialise la nouvelle instance de[`Merger`](../../merger) classe.

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier. |
| loadOptions | ILoadOptions | Les options de chargement des documents. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*filePath* est nul ou vide. |
| ArgumentNullException | Jeté quand*loadOptions* est nul. |

### Voir également

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* espace de noms [GroupDocs.Merger](../../merger)
* Assemblée [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

Initialise la nouvelle instance de[`Merger`](../../merger) classe.

```csharp
public Merger(string filePath, MergerSettings settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier. |
| settings | MergerSettings | Les paramètres de fusion. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*filePath* est nul ou vide. |
| ArgumentNullException | Jeté quand*settings* est nul. |

### Voir également

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* espace de noms [GroupDocs.Merger](../../merger)
* Assemblée [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

Initialise la nouvelle instance de[`Merger`](../../merger) classe.

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier. |
| loadOptions | ILoadOptions | Les options de chargement des documents. |
| settings | MergerSettings | Les paramètres de fusion. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*filePath* est nul ou vide. |
| ArgumentNullException | Jeté quand*loadOptions* est nul. |
| ArgumentNullException | Jeté quand*settings* est nul. |

### Voir également

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* espace de noms [GroupDocs.Merger](../../merger)
* Assemblée [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
