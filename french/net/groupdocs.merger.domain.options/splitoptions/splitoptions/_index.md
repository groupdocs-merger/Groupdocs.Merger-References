---
title: SplitOptions
second_title: Référence de l'API GroupDocs.Merger pour .NET
description: Initialise une nouvelle instance duSplitOptionsgroupdocs.merger.domain.options/splitoptions classe.
type: docs
weight: 10
url: /fr/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

Initialise une nouvelle instance du[`SplitOptions`](../../splitoptions) classe.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePathFormat | String | Le format du chemin de fichier, par exemple 'c:/split{0}.doc' ou 'c:/split{0}.{1}' avec une extension déjà prédéfinie. |
| pageNumbers | Int32[] | Numéros de page. |

### Voir également

* class [SplitOptions](../../splitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Assemblée [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

Initialise une nouvelle instance du[`SplitOptions`](../../splitoptions) classe.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePathFormat | String | Le format du chemin de fichier, par exemple 'c:/split{0}.doc' ou 'c:/split{0}.{1}' avec une extension déjà prédéfinie. |
| pageNumbers | Int32[] | Numéros de page. |
| splitMode | SplitMode | Le mode de fractionnement de[`Mode`](../mode). |

### Voir également

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Assemblée [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

Initialise une nouvelle instance du[`SplitOptions`](../../splitoptions) classe.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePathFormat | String | Le format du chemin de fichier, par exemple 'c:/split{0}.doc' ou 'c:/split{0}.{1}' avec une extension déjà prédéfinie. |
| startNumber | Int32 | Le numéro de la page de démarrage. |
| endNumber | Int32 | Le numéro de la page de fin. |

### Voir également

* class [SplitOptions](../../splitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Assemblée [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

Initialise une nouvelle instance du[`SplitOptions`](../../splitoptions) classe.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePathFormat | String | Le format du chemin de fichier, par exemple 'c:/split{0}.doc' ou 'c:/split{0}.{1}' avec une extension déjà prédéfinie. |
| startNumber | Int32 | Le numéro de la page de démarrage. |
| endNumber | Int32 | Le numéro de la page de fin. |
| mode | RangeMode | Le mode gamme. |

### Voir également

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Assemblée [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

Initialise une nouvelle instance du[`SplitOptions`](../../splitoptions) classe.

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données fractionnées de sortie. |

### Voir également

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Assemblée [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

Initialise une nouvelle instance du[`SplitOptions`](../../splitoptions) classe.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données fractionnées de sortie. |
| pageNumbers | Int32[] | Numéros de page. |

### Voir également

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Assemblée [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

Initialise une nouvelle instance du[`SplitOptions`](../../splitoptions) classe.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données fractionnées de sortie. |
| pageNumbers | Int32[] | Numéros de page. |
| splitMode | SplitMode | Le mode de fractionnement de[`Mode`](../mode). |

### Voir également

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Assemblée [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

Initialise une nouvelle instance du[`SplitOptions`](../../splitoptions) classe.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données fractionnées de sortie. |
| startNumber | Int32 | Le numéro de la page de démarrage. |
| endNumber | Int32 | Le numéro de la page de fin. |

### Voir également

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Assemblée [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

Initialise une nouvelle instance du[`SplitOptions`](../../splitoptions) classe.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données fractionnées de sortie. |
| startNumber | Int32 | Le numéro de la page de démarrage. |
| endNumber | Int32 | Le numéro de la page de fin. |
| mode | RangeMode | Le mode gamme. |

### Voir également

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Assemblée [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

Initialise une nouvelle instance du[`SplitOptions`](../../splitoptions) classe.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données fractionnées de sortie. |
| releaseSplitStream | ReleaseSplitStream | La méthode qui libère le flux créé par la méthode createPageStream. |

### Voir également

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Assemblée [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

Initialise une nouvelle instance du[`SplitOptions`](../../splitoptions) classe.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données fractionnées de sortie. |
| releaseSplitStream | ReleaseSplitStream | La méthode qui libère le flux créé par la méthode createPageStream. |
| pageNumbers | Int32[] | Numéros de page. |

### Voir également

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Assemblée [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

Initialise une nouvelle instance du[`SplitOptions`](../../splitoptions) classe.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données fractionnées de sortie. |
| releaseSplitStream | ReleaseSplitStream | La méthode qui libère le flux créé par la méthode createPageStream. |
| pageNumbers | Int32[] | Numéros de page. |
| splitMode | SplitMode | Le mode de fractionnement de[`Mode`](../mode). |

### Voir également

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Assemblée [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

Initialise une nouvelle instance du[`SplitOptions`](../../splitoptions) classe.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données fractionnées de sortie. |
| releaseSplitStream | ReleaseSplitStream | La méthode qui libère le flux créé par la méthode createPageStream. |
| startNumber | Int32 | Le numéro de la page de démarrage. |
| endNumber | Int32 | Le numéro de la page de fin. |

### Voir également

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Assemblée [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

Initialise une nouvelle instance du[`SplitOptions`](../../splitoptions) classe.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | La méthode qui instancie le flux utilisé pour écrire les données fractionnées de sortie. |
| releaseSplitStream | ReleaseSplitStream | La méthode qui libère le flux créé par la méthode createPageStream. |
| startNumber | Int32 | Le numéro de la page de démarrage. |
| endNumber | Int32 | Le numéro de la page de fin. |
| mode | RangeMode | Le mode gamme. |

### Voir également

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* espace de noms [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Assemblée [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
