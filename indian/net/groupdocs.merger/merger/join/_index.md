---
title: "Join"
second_title: "GroupDocs.Merger .NET के लिए API संदर्भ"
description: "दस्तावेज़ों को एक ही दस्तावेज़ में जोड़ता है।"
type: docs
weight: 120
url: /hi/net/groupdocs.merger/merger/join/
---
## Join(Stream) {#join}

दस्तावेज़ों को एक ही दस्तावेज़ में जोड़ता है।

```csharp
public IMerger Join(Stream document)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | जुड़ा हुआ दस्तावेज़। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *document* शून्य हो, तब फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### साथ ही देखें

* interface [IMerger](../../imerger)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IJoinOptions) {#join_2}

दस्तावेज़ों को एक ही दस्तावेज़ में जोड़ता है।

```csharp
public IMerger Join(Stream document, IJoinOptions joinOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | जुड़ा हुआ दस्तावेज़। |
| joinOptions | IJoinOptions | जॉइन विकल्प। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *document* शून्य हो, तब फेंका जाता है। |
| ArgumentNullException | जब *joinOptions* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### साथ ही देखें

* interface [IMerger](../../imerger)
* interface [IJoinOptions](../../../groupdocs.merger.domain.options/ijoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IPageJoinOptions) {#join_3}

दस्तावेज़ों को एक ही दस्तावेज़ में जोड़ता है।

```csharp
public IMerger Join(Stream document, IPageJoinOptions joinOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | जुड़ा हुआ दस्तावेज़। |
| joinOptions | IPageJoinOptions | जॉइन विकल्प। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *document* शून्य हो, तब फेंका जाता है। |
| ArgumentNullException | जब *joinOptions* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### साथ ही देखें

* interface [IMerger](../../imerger)
* interface [IPageJoinOptions](../../../groupdocs.merger.domain.options/ipagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IImageJoinOptions) {#join_1}

दस्तावेज़ों को एक ही दस्तावेज़ में जोड़ता है।

```csharp
public IMerger Join(Stream document, IImageJoinOptions joinOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | जुड़ा हुआ दस्तावेज़। |
| joinOptions | IImageJoinOptions | छवि जोड़ विकल्प। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *document* शून्य हो, तब फेंका जाता है। |
| ArgumentNullException | जब *joinOptions* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### साथ ही देखें

* interface [IMerger](../../imerger)
* interface [IImageJoinOptions](../../../groupdocs.merger.domain.options/iimagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string) {#join_4}

दस्तावेज़ों को एक ही दस्तावेज़ में जोड़ता है।

```csharp
public IMerger Join(string filePath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | जुड़े दस्तावेज़ का फ़ाइल पाथ। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *filePath* null या खाली हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### साथ ही देखें

* interface [IMerger](../../imerger)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IJoinOptions) {#join_6}

दस्तावेज़ों को एक ही दस्तावेज़ में जोड़ता है।

```csharp
public IMerger Join(string filePath, IJoinOptions joinOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | जुड़े दस्तावेज़ का फ़ाइल पाथ। |
| joinOptions | IJoinOptions | जॉइन विकल्प। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *filePath* null या खाली हो तो फेंका जाता है। |
| ArgumentNullException | जब *joinOptions* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### साथ ही देखें

* interface [IMerger](../../imerger)
* interface [IJoinOptions](../../../groupdocs.merger.domain.options/ijoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IPageJoinOptions) {#join_7}

दस्तावेज़ों को एक ही दस्तावेज़ में जोड़ता है।

```csharp
public IMerger Join(string filePath, IPageJoinOptions joinOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | जुड़े दस्तावेज़ का फ़ाइल पाथ। |
| joinOptions | IPageJoinOptions | जॉइन विकल्प। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *filePath* null या खाली हो तो फेंका जाता है। |
| ArgumentNullException | जब *joinOptions* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### साथ ही देखें

* interface [IMerger](../../imerger)
* interface [IPageJoinOptions](../../../groupdocs.merger.domain.options/ipagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IImageJoinOptions) {#join_5}

दस्तावेज़ों को एक ही दस्तावेज़ में जोड़ता है।

```csharp
public IMerger Join(string filePath, IImageJoinOptions joinOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | जुड़े दस्तावेज़ का फ़ाइल पाथ। |
| joinOptions | IImageJoinOptions | छवि जोड़ विकल्प। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *filePath* null या खाली हो तो फेंका जाता है। |
| ArgumentNullException | जब *joinOptions* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### साथ ही देखें

* interface [IMerger](../../imerger)
* interface [IImageJoinOptions](../../../groupdocs.merger.domain.options/iimagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
