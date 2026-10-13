---
title: "LoadOptions"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Initialise une nouvelle instance de la classe LoadOptionsgroupdocs.merger.domain.options/loadoptions."
type: docs
weight: 10
url: /fr/net/groupdocs.merger.domain.options/loadoptions/loadoptions/
---
## LoadOptions(FileType) {#constructor}

Initialise une nouvelle instance de la classe [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(FileType fileType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | FileType | Le type du fichier à charger. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *fileType* est nul. |

### Voir aussi

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string) {#constructor_6}

Initialise une nouvelle instance de la classe [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(string password)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| mot de passe | String | Le mot de passe pour ouvrir le fichier protégé par mot de passe. |

### Voir aussi

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string, Encoding) {#constructor_8}

Initialise une nouvelle instance de la classe [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(string password, Encoding encoding)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| mot de passe | String | Le mot de passe pour ouvrir le fichier protégé par mot de passe. |
| encoding | Encoding | L'encodage utilisé lors de l'ouverture de fichiers texte tels que [`CSV`](../../../groupdocs.merger.domain/filetype/csv) ou [`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *encoding* est nul. |

### Voir aussi

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string) {#constructor_4}

Initialise une nouvelle instance de la classe [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(FileType fileType, string password)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | FileType | Le type du fichier à charger. |
| mot de passe | String | Le mot de passe pour ouvrir le fichier protégé par mot de passe. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *fileType* est nul. |

### Voir aussi

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string, Encoding) {#constructor_5}

Initialise une nouvelle instance de la classe [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(FileType fileType, string password, Encoding encoding)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | FileType | Le type du fichier à charger. |
| mot de passe | String | Le mot de passe pour ouvrir le fichier protégé par mot de passe. |
| encoding | Encoding | L'encodage utilisé lors de l'ouverture de fichiers texte tels que [`CSV`](../../../groupdocs.merger.domain/filetype/csv) ou [`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *fileType* est nul. |
| ArgumentNullException | Lancée lorsque *encoding* est nul. |

### Voir aussi

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string, FileType, string, Encoding) {#constructor_7}

Initialise une nouvelle instance de la classe [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(string extension, FileType fileType, string password, Encoding encoding)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| extension | String | L'extension du fichier à charger. |
| fileType | FileType | Le type du fichier à charger. |
| mot de passe | String | Le mot de passe pour ouvrir le fichier protégé par mot de passe. |
| encoding | Encoding | L'encodage utilisé lors de l'ouverture de fichiers texte tels que [`CSV`](../../../groupdocs.merger.domain/filetype/csv) ou [`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *fileType* est nul. |
| ArgumentNullException | Lancée lorsque *encoding* est nul. |

### Voir aussi

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string, Encoding) {#constructor_3}

Initialise une nouvelle instance de la classe [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password, Encoding encoding)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| iniFileType | FileType | Le type du fichier à initialiser. |
| fileType | FileType | Le type du fichier à charger. |
| mot de passe | String | Le mot de passe pour ouvrir le fichier protégé par mot de passe. |
| encoding | Encoding | L'encodage utilisé lors de l'ouverture de fichiers texte tels que [`CSV`](../../../groupdocs.merger.domain/filetype/csv) ou [`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *iniFileType* est nul. |
| ArgumentNullException | Lancée lorsque *fileType* est nul. |
| ArgumentNullException | Lancée lorsque *encoding* est nul. |

### Voir aussi

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string) {#constructor_2}

Initialise une nouvelle instance de la classe [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| iniFileType | FileType | Le type du fichier à initialiser. |
| fileType | FileType | Le type du fichier à charger. |
| mot de passe | String | Le mot de passe pour ouvrir le fichier protégé par mot de passe. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *iniFileType* est nul. |
| ArgumentNullException | Lancée lorsque *fileType* est nul. |

### Voir aussi

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType) {#constructor_1}

Initialise une nouvelle instance de la classe [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(FileType iniFileType, FileType fileType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| iniFileType | FileType | Le type du fichier à initialiser. |
| fileType | FileType | Le type du fichier à charger. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *iniFileType* est nul. |
| ArgumentNullException | Lancée lorsque *fileType* est nul. |

### Voir aussi

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
