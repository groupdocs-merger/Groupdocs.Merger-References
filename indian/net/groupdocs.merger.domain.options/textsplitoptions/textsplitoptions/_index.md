---
title: TextSplitOptions
second_title: .NET API संदर्भ के लिए GroupDocs.Merger
description: क एक नय उदहरण प्ररंभ करत हैTextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions वर्ग.
type: docs
weight: 10
url: /hi/net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

का एक नया उदाहरण प्रारंभ करता है[`TextSplitOptions`](../../textsplitoptions) वर्ग.

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | String | फ़ाइल पथ स्वरूप जैसे 'c:/split{0}.doc' या 'c:/split{0}.{1}' पहले से परिभाषित एक्सटेंशन के साथ। |
| lineNumbers | Int32[] | टेक्स्ट स्प्लिटिंग के लिए लाइन नंबर। |

### यह सभी देखें

* class [TextSplitOptions](../../textsplitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* सभा [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

का एक नया उदाहरण प्रारंभ करता है[`TextSplitOptions`](../../textsplitoptions) वर्ग.

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | String | फ़ाइल पथ स्वरूप जैसे 'c:/split{0}.doc' या 'c:/split{0}.{1}' पहले से परिभाषित एक्सटेंशन के साथ। |
| mode | TextSplitMode | पाठ विभाजन के लिए मोड। |
| lineNumbers | Int32[] | टेक्स्ट स्प्लिटिंग के लिए लाइन नंबर। |

### यह सभी देखें

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* सभा [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

का एक नया उदाहरण प्रारंभ करता है[`TextSplitOptions`](../../textsplitoptions) वर्ग.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| lineNumbers | Int32[] | टेक्स्ट स्प्लिटिंग के लिए लाइन नंबर। |

### यह सभी देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* सभा [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

का एक नया उदाहरण प्रारंभ करता है[`TextSplitOptions`](../../textsplitoptions) वर्ग.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| mode | TextSplitMode | पाठ विभाजन के लिए मोड। |
| lineNumbers | Int32[] | टेक्स्ट स्प्लिटिंग के लिए लाइन नंबर। |

### यह सभी देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* सभा [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

का एक नया उदाहरण प्रारंभ करता है[`TextSplitOptions`](../../textsplitoptions) वर्ग.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| releaseSplitStream | ReleaseSplitStream | विधि जो createPageStream विधि द्वारा बनाई गई स्ट्रीम को रिलीज़ करती है। |
| lineNumbers | Int32[] | टेक्स्ट स्प्लिटिंग के लिए लाइन नंबर। |

### यह सभी देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* सभा [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

का एक नया उदाहरण प्रारंभ करता है[`TextSplitOptions`](../../textsplitoptions) वर्ग.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| releaseSplitStream | ReleaseSplitStream | विधि जो createPageStream विधि द्वारा बनाई गई स्ट्रीम को रिलीज़ करती है। |
| mode | TextSplitMode | पाठ विभाजन के लिए मोड। |
| lineNumbers | Int32[] | टेक्स्ट स्प्लिटिंग के लिए लाइन नंबर। |

### यह सभी देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* सभा [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
