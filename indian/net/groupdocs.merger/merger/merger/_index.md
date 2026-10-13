---
title: "मर्जर"
second_title: "GroupDocs.Merger .NET के लिए API संदर्भ"
description: "Mergergroupdocs.merger/merger क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

[`Merger`](../../merger) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Merger(Stream document)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | पढ़ने योग्य स्ट्रीम। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *document* शून्य हो, तब फेंका जाता है। |

### साथ ही देखें

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

[`Merger`](../../merger) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | पढ़ने योग्य स्ट्रीम। |
| loadOptions | ILoadOptions | दस्तावेज़ लोड विकल्प। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *document* शून्य हो, तब फेंका जाता है। |
| ArgumentNullException | जब *loadOptions* null हो तो फेंका जाता है। |

### साथ ही देखें

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

[`Merger`](../../merger) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Merger(Stream document, MergerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | पढ़ने योग्य स्ट्रीम। |
| settings | MergerSettings | Merger सेटिंग्स। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *document* शून्य हो, तब फेंका जाता है। |
| ArgumentNullException | जब *settings* null हो तो फेंका जाता है। |

### साथ ही देखें

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

[`Merger`](../../merger) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | पढ़ने योग्य स्ट्रीम। |
| loadOptions | ILoadOptions | दस्तावेज़ लोड विकल्प। |
| settings | MergerSettings | Merger सेटिंग्स। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *document* शून्य हो, तब फेंका जाता है। |
| ArgumentNullException | जब *loadOptions* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *settings* null हो तो फेंका जाता है। |

### साथ ही देखें

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

[`Merger`](../../merger) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Merger(Func<Stream> getFileStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| getFileStream | Func`1 | वह मेथड जो पढ़ने योग्य स्ट्रीम रिटर्न करता है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *getFileStream* null हो तो फेंका जाता है। |

### साथ ही देखें

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

[`Merger`](../../merger) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| getFileStream | Func`1 | वह मेथड जो पढ़ने योग्य स्ट्रीम रिटर्न करता है। |
| loadOptions | ILoadOptions | दस्तावेज़ लोड विकल्प। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *getFileStream* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *loadOptions* null हो तो फेंका जाता है। |

### साथ ही देखें

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

[`Merger`](../../merger) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| getFileStream | Func`1 | वह मेथड जो पढ़ने योग्य स्ट्रीम रिटर्न करता है। |
| settings | MergerSettings | Merger सेटिंग्स। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *getFileStream* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *settings* null हो तो फेंका जाता है। |

### साथ ही देखें

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

[`Merger`](../../merger) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| getFileStream | Func`1 | वह मेथड जो पढ़ने योग्य स्ट्रीम रिटर्न करता है। |
| loadOptions | ILoadOptions | दस्तावेज़ लोड विकल्प। |
| settings | MergerSettings | Merger सेटिंग्स। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *getFileStream* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *loadOptions* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *settings* null हो तो फेंका जाता है। |

### साथ ही देखें

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

[`Merger`](../../merger) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Merger(string filePath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | फ़ाइल पाथ। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *filePath* null या खाली हो तो फेंका जाता है। |

### साथ ही देखें

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

[`Merger`](../../merger) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | फ़ाइल पाथ। |
| loadOptions | ILoadOptions | दस्तावेज़ लोड विकल्प। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *filePath* null या खाली हो तो फेंका जाता है। |
| ArgumentNullException | जब *loadOptions* null हो तो फेंका जाता है। |

### साथ ही देखें

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

[`Merger`](../../merger) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Merger(string filePath, MergerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | फ़ाइल पाथ। |
| settings | MergerSettings | Merger सेटिंग्स। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *filePath* null या खाली हो तो फेंका जाता है। |
| ArgumentNullException | जब *settings* null हो तो फेंका जाता है। |

### साथ ही देखें

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

[`Merger`](../../merger) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | फ़ाइल पाथ। |
| loadOptions | ILoadOptions | दस्तावेज़ लोड विकल्प। |
| settings | MergerSettings | Merger सेटिंग्स। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *filePath* null या खाली हो तो फेंका जाता है। |
| ArgumentNullException | जब *loadOptions* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *settings* null हो तो फेंका जाता है। |

### साथ ही देखें

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
