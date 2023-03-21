---
title: Merger
second_title: .NET API संदर्भ के लिए GroupDocs.Merger
description: क नय उदहरण शुरू करत हैMergergroupdocs.merger/merger वर्ग.
type: docs
weight: 10
url: /hi/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

का नया उदाहरण शुरू करता है[`Merger`](../../merger) वर्ग.

```csharp
public Merger(Stream document)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | पठनीय धारा। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*document* शून्य है। |

### यह सभी देखें

* class [Merger](../../merger)
* नाम स्थान [GroupDocs.Merger](../../merger)
* सभा [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

का नया उदाहरण शुरू करता है[`Merger`](../../merger) वर्ग.

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | पठनीय धारा। |
| loadOptions | ILoadOptions | दस्तावेज़ लोड विकल्प। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*document* शून्य है। |
| ArgumentNullException | कब फेंका*loadOptions* शून्य है। |

### यह सभी देखें

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* नाम स्थान [GroupDocs.Merger](../../merger)
* सभा [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

का नया उदाहरण शुरू करता है[`Merger`](../../merger) वर्ग.

```csharp
public Merger(Stream document, MergerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | पठनीय धारा। |
| settings | MergerSettings | विलय सेटिंग्स। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*document* शून्य है। |
| ArgumentNullException | कब फेंका*settings* शून्य है। |

### यह सभी देखें

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* नाम स्थान [GroupDocs.Merger](../../merger)
* सभा [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

का नया उदाहरण शुरू करता है[`Merger`](../../merger) वर्ग.

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | पठनीय धारा। |
| loadOptions | ILoadOptions | दस्तावेज़ लोड विकल्प। |
| settings | MergerSettings | विलय सेटिंग्स। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*document* शून्य है। |
| ArgumentNullException | कब फेंका*loadOptions* शून्य है। |
| ArgumentNullException | कब फेंका*settings* शून्य है। |

### यह सभी देखें

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* नाम स्थान [GroupDocs.Merger](../../merger)
* सभा [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

का नया उदाहरण शुरू करता है[`Merger`](../../merger) वर्ग.

```csharp
public Merger(Func<Stream> getFileStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| getFileStream | Func`1 | वह विधि जो पठनीय स्ट्रीम लौटाती है। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*getFileStream* शून्य है। |

### यह सभी देखें

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* नाम स्थान [GroupDocs.Merger](../../merger)
* सभा [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

का नया उदाहरण शुरू करता है[`Merger`](../../merger) वर्ग.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| getFileStream | Func`1 | वह विधि जो पठनीय स्ट्रीम लौटाती है। |
| loadOptions | ILoadOptions | दस्तावेज़ लोड विकल्प। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*getFileStream* शून्य है। |
| ArgumentNullException | कब फेंका*loadOptions* शून्य है। |

### यह सभी देखें

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* नाम स्थान [GroupDocs.Merger](../../merger)
* सभा [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

का नया उदाहरण शुरू करता है[`Merger`](../../merger) वर्ग.

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| getFileStream | Func`1 | वह विधि जो पठनीय स्ट्रीम लौटाती है। |
| settings | MergerSettings | विलय सेटिंग्स। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*getFileStream* शून्य है। |
| ArgumentNullException | कब फेंका*settings* शून्य है। |

### यह सभी देखें

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* नाम स्थान [GroupDocs.Merger](../../merger)
* सभा [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

का नया उदाहरण शुरू करता है[`Merger`](../../merger) वर्ग.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| getFileStream | Func`1 | वह विधि जो पठनीय स्ट्रीम लौटाती है। |
| loadOptions | ILoadOptions | दस्तावेज़ लोड विकल्प। |
| settings | MergerSettings | विलय सेटिंग्स। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*getFileStream* शून्य है। |
| ArgumentNullException | कब फेंका*loadOptions* शून्य है। |
| ArgumentNullException | कब फेंका*settings* शून्य है। |

### यह सभी देखें

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* नाम स्थान [GroupDocs.Merger](../../merger)
* सभा [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

का नया उदाहरण शुरू करता है[`Merger`](../../merger) वर्ग.

```csharp
public Merger(string filePath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | फ़ाइल पथ। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*filePath* शून्य या खाली है। |

### यह सभी देखें

* class [Merger](../../merger)
* नाम स्थान [GroupDocs.Merger](../../merger)
* सभा [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

का नया उदाहरण शुरू करता है[`Merger`](../../merger) वर्ग.

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | फ़ाइल पथ। |
| loadOptions | ILoadOptions | दस्तावेज़ लोड विकल्प। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*filePath* शून्य या खाली है। |
| ArgumentNullException | कब फेंका*loadOptions* शून्य है। |

### यह सभी देखें

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* नाम स्थान [GroupDocs.Merger](../../merger)
* सभा [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

का नया उदाहरण शुरू करता है[`Merger`](../../merger) वर्ग.

```csharp
public Merger(string filePath, MergerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | फ़ाइल पथ। |
| settings | MergerSettings | विलय सेटिंग्स। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*filePath* शून्य या खाली है। |
| ArgumentNullException | कब फेंका*settings* शून्य है। |

### यह सभी देखें

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* नाम स्थान [GroupDocs.Merger](../../merger)
* सभा [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

का नया उदाहरण शुरू करता है[`Merger`](../../merger) वर्ग.

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | फ़ाइल पथ। |
| loadOptions | ILoadOptions | दस्तावेज़ लोड विकल्प। |
| settings | MergerSettings | विलय सेटिंग्स। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*filePath* शून्य या खाली है। |
| ArgumentNullException | कब फेंका*loadOptions* शून्य है। |
| ArgumentNullException | कब फेंका*settings* शून्य है। |

### यह सभी देखें

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* नाम स्थान [GroupDocs.Merger](../../merger)
* सभा [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
