---
title: "Zusammenführer"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der Klasse Mergergroupdocs.merger/merger."
type: docs
weight: 10
url: /de/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

Initialisiert eine neue Instanz der Klasse [`Merger`](../../merger).

```csharp
public Merger(Stream document)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Der lesbare Stream. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *document* null ist. |

### Siehe auch

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

Initialisiert eine neue Instanz der Klasse [`Merger`](../../merger).

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Der lesbare Stream. |
| loadOptions | ILoadOptions | Die Dokument-Ladeoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *document* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *loadOptions* null ist. |

### Siehe auch

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

Initialisiert eine neue Instanz der Klasse [`Merger`](../../merger).

```csharp
public Merger(Stream document, MergerSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Der lesbare Stream. |
| settings | MergerSettings | Die Merger-Einstellungen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *document* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *settings* null ist. |

### Siehe auch

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

Initialisiert eine neue Instanz der Klasse [`Merger`](../../merger).

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Der lesbare Stream. |
| loadOptions | ILoadOptions | Die Dokument-Ladeoptionen. |
| settings | MergerSettings | Die Merger-Einstellungen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *document* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *loadOptions* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *settings* null ist. |

### Siehe auch

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

Initialisiert eine neue Instanz der Klasse [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| getFileStream | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *getFileStream* null ist. |

### Siehe auch

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

Initialisiert eine neue Instanz der Klasse [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| getFileStream | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |
| loadOptions | ILoadOptions | Die Dokument-Ladeoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *getFileStream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *loadOptions* null ist. |

### Siehe auch

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

Initialisiert eine neue Instanz der Klasse [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| getFileStream | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |
| settings | MergerSettings | Die Merger-Einstellungen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *getFileStream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *settings* null ist. |

### Siehe auch

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

Initialisiert eine neue Instanz der Klasse [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| getFileStream | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |
| loadOptions | ILoadOptions | Die Dokument-Ladeoptionen. |
| settings | MergerSettings | Die Merger-Einstellungen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *getFileStream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *loadOptions* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *settings* null ist. |

### Siehe auch

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

Initialisiert eine neue Instanz der Klasse [`Merger`](../../merger).

```csharp
public Merger(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *filePath* null oder leer ist. |

### Siehe auch

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

Initialisiert eine neue Instanz der Klasse [`Merger`](../../merger).

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad. |
| loadOptions | ILoadOptions | Die Dokument-Ladeoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *filePath* null oder leer ist. |
| ArgumentNullException | Wird ausgelöst, wenn *loadOptions* null ist. |

### Siehe auch

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

Initialisiert eine neue Instanz der Klasse [`Merger`](../../merger).

```csharp
public Merger(string filePath, MergerSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad. |
| settings | MergerSettings | Die Merger-Einstellungen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *filePath* null oder leer ist. |
| ArgumentNullException | Wird ausgelöst, wenn *settings* null ist. |

### Siehe auch

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

Initialisiert eine neue Instanz der Klasse [`Merger`](../../merger).

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad. |
| loadOptions | ILoadOptions | Die Dokument-Ladeoptionen. |
| settings | MergerSettings | Die Merger-Einstellungen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *filePath* null oder leer ist. |
| ArgumentNullException | Wird ausgelöst, wenn *loadOptions* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *settings* null ist. |

### Siehe auch

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
