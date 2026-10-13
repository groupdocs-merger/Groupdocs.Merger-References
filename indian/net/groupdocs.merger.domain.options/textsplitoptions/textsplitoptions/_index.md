---
title: "TextSplitOptions"
second_title: "GroupDocs.Merger .NET के लिए API संदर्भ"
description: "TextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

[`TextSplitOptions`](../../textsplitoptions) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | String | फ़ाइल पाथ फ़ॉर्मेट, उदाहरण के लिए 'c:/split{0}.doc' या 'c:/split{0}.{1}' जिसमें पहले से परिभाषित एक्सटेंशन है। |
| lineNumbers | Int32[] | पाठ विभाजन के लिए पंक्ति संख्याएँ। |

### साथ ही देखें

* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

[`TextSplitOptions`](../../textsplitoptions) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | String | फ़ाइल पाथ फ़ॉर्मेट, उदाहरण के लिए 'c:/split{0}.doc' या 'c:/split{0}.{1}' जिसमें पहले से परिभाषित एक्सटेंशन है। |
| mode | TextSplitMode | पाठ विभाजन के लिए मोड। |
| lineNumbers | Int32[] | पाठ विभाजन के लिए पंक्ति संख्याएँ। |

### साथ ही देखें

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

[`TextSplitOptions`](../../textsplitoptions) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंशिएट करने वाला मेथड। |
| lineNumbers | Int32[] | पाठ विभाजन के लिए पंक्ति संख्याएँ। |

### साथ ही देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

[`TextSplitOptions`](../../textsplitoptions) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंशिएट करने वाला मेथड। |
| mode | TextSplitMode | पाठ विभाजन के लिए मोड। |
| lineNumbers | Int32[] | पाठ विभाजन के लिए पंक्ति संख्याएँ। |

### साथ ही देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

[`TextSplitOptions`](../../textsplitoptions) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंशिएट करने वाला मेथड। |
| releaseSplitStream | ReleaseSplitStream | यह मेथड createPageStream मेथड द्वारा निर्मित स्ट्रीम को रिलीज़ करता है। |
| lineNumbers | Int32[] | पाठ विभाजन के लिए पंक्ति संख्याएँ। |

### साथ ही देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

[`TextSplitOptions`](../../textsplitoptions) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंशिएट करने वाला मेथड। |
| releaseSplitStream | ReleaseSplitStream | यह मेथड createPageStream मेथड द्वारा निर्मित स्ट्रीम को रिलीज़ करता है। |
| mode | TextSplitMode | पाठ विभाजन के लिए मोड। |
| lineNumbers | Int32[] | पाठ विभाजन के लिए पंक्ति संख्याएँ। |

### साथ ही देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
