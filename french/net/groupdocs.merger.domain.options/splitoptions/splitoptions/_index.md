---
title: "SplitOptions"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Initialise une nouvelle instance de la classe SplitOptionsgroupdocs.merger.domain.options/splitoptions."
type: docs
weight: 10
url: /fr/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

Initialise une nouvelle instance de la classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | String | Le format du chemin de fichier, par ex. 'c:/split{0}.doc' ou 'c:/split{0}.{1}' avec une extension déjà pré‑définie. |
| pageNumbers | Int32[] | Numéros de page. |

### Voir aussi

* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

Initialise une nouvelle instance de la classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | String | Le format du chemin de fichier, par ex. 'c:/split{0}.doc' ou 'c:/split{0}.{1}' avec une extension déjà pré‑définie. |
| pageNumbers | Int32[] | Numéros de page. |
| splitMode | SplitMode | Le mode de division de [`Mode`](../mode). |

### Voir aussi

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

Initialise une nouvelle instance de la classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | String | Le format du chemin de fichier, par ex. 'c:/split{0}.doc' ou 'c:/split{0}.{1}' avec une extension déjà pré‑définie. |
| startNumber | Int32 | Le numéro de page de début. |
| endNumber | Int32 | Le numéro de page de fin. |

### Voir aussi

* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

Initialise une nouvelle instance de la classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | String | Le format du chemin de fichier, par ex. 'c:/split{0}.doc' ou 'c:/split{0}.{1}' avec une extension déjà pré‑définie. |
| startNumber | Int32 | Le numéro de page de début. |
| endNumber | Int32 | Le numéro de page de fin. |
| mode | RangeMode | Le mode de plage. |

### Voir aussi

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

Initialise une nouvelle instance de la classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données de sortie fractionnées. |

### Voir aussi

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

Initialise une nouvelle instance de la classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données de sortie fractionnées. |
| pageNumbers | Int32[] | Numéros de page. |

### Voir aussi

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

Initialise une nouvelle instance de la classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données de sortie fractionnées. |
| pageNumbers | Int32[] | Numéros de page. |
| splitMode | SplitMode | Le mode de division de [`Mode`](../mode). |

### Voir aussi

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

Initialise une nouvelle instance de la classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données de sortie fractionnées. |
| startNumber | Int32 | Le numéro de page de début. |
| endNumber | Int32 | Le numéro de page de fin. |

### Voir aussi

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

Initialise une nouvelle instance de la classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données de sortie fractionnées. |
| startNumber | Int32 | Le numéro de page de début. |
| endNumber | Int32 | Le numéro de page de fin. |
| mode | RangeMode | Le mode de plage. |

### Voir aussi

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

Initialise une nouvelle instance de la classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données de sortie fractionnées. |
| releaseSplitStream | ReleaseSplitStream | La méthode qui libère le flux créé par la méthode createPageStream. |

### Voir aussi

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

Initialise une nouvelle instance de la classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données de sortie fractionnées. |
| releaseSplitStream | ReleaseSplitStream | La méthode qui libère le flux créé par la méthode createPageStream. |
| pageNumbers | Int32[] | Numéros de page. |

### Voir aussi

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

Initialise une nouvelle instance de la classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données de sortie fractionnées. |
| releaseSplitStream | ReleaseSplitStream | La méthode qui libère le flux créé par la méthode createPageStream. |
| pageNumbers | Int32[] | Numéros de page. |
| splitMode | SplitMode | Le mode de division de [`Mode`](../mode). |

### Voir aussi

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

Initialise une nouvelle instance de la classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données de sortie fractionnées. |
| releaseSplitStream | ReleaseSplitStream | La méthode qui libère le flux créé par la méthode createPageStream. |
| startNumber | Int32 | Le numéro de page de début. |
| endNumber | Int32 | Le numéro de page de fin. |

### Voir aussi

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

Initialise une nouvelle instance de la classe [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données de sortie fractionnées. |
| releaseSplitStream | ReleaseSplitStream | La méthode qui libère le flux créé par la méthode createPageStream. |
| startNumber | Int32 | Le numéro de page de début. |
| endNumber | Int32 | Le numéro de page de fin. |
| mode | RangeMode | Le mode de plage. |

### Voir aussi

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
