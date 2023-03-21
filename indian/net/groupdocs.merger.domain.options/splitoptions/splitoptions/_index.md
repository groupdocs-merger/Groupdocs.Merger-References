---
title: SplitOptions
second_title: .NET API संदर्भ के लिए GroupDocs.Merger
description: क एक नय उदहरण प्ररंभ करत हैSplitOptionsgroupdocs.merger.domain.options/splitoptions वर्ग.
type: docs
weight: 10
url: /hi/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

का एक नया उदाहरण प्रारंभ करता है[`SplitOptions`](../../splitoptions) वर्ग.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | String | फ़ाइल पथ प्रारूप जैसे 'c:/split{0}.doc' या 'c:/split{0}.{1}' पहले से ही पूर्व-निर्धारित एक्सटेंशन के साथ। |
| pageNumbers | Int32[] | पेज नंबर। |

### यह सभी देखें

* class [SplitOptions](../../splitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../splitoptions)
* सभा [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

का एक नया उदाहरण प्रारंभ करता है[`SplitOptions`](../../splitoptions) वर्ग.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | String | फ़ाइल पथ प्रारूप जैसे 'c:/split{0}.doc' या 'c:/split{0}.{1}' पहले से ही पूर्व-निर्धारित एक्सटेंशन के साथ। |
| pageNumbers | Int32[] | पेज नंबर। |
| splitMode | SplitMode | का बंटवारा मोड[`Mode`](../mode). |

### यह सभी देखें

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../splitoptions)
* सभा [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

का एक नया उदाहरण प्रारंभ करता है[`SplitOptions`](../../splitoptions) वर्ग.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | String | फ़ाइल पथ प्रारूप जैसे 'c:/split{0}.doc' या 'c:/split{0}.{1}' पहले से ही पूर्व-निर्धारित एक्सटेंशन के साथ। |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | अंतिम पृष्ठ संख्या। |

### यह सभी देखें

* class [SplitOptions](../../splitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../splitoptions)
* सभा [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

का एक नया उदाहरण प्रारंभ करता है[`SplitOptions`](../../splitoptions) वर्ग.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | String | फ़ाइल पथ प्रारूप जैसे 'c:/split{0}.doc' या 'c:/split{0}.{1}' पहले से ही पूर्व-निर्धारित एक्सटेंशन के साथ। |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | अंतिम पृष्ठ संख्या। |
| mode | RangeMode | रेंज मोड। |

### यह सभी देखें

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../splitoptions)
* सभा [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

का एक नया उदाहरण प्रारंभ करता है[`SplitOptions`](../../splitoptions) वर्ग.

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |

### यह सभी देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../splitoptions)
* सभा [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

का एक नया उदाहरण प्रारंभ करता है[`SplitOptions`](../../splitoptions) वर्ग.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| pageNumbers | Int32[] | पेज नंबर। |

### यह सभी देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../splitoptions)
* सभा [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

का एक नया उदाहरण प्रारंभ करता है[`SplitOptions`](../../splitoptions) वर्ग.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| pageNumbers | Int32[] | पेज नंबर। |
| splitMode | SplitMode | का बंटवारा मोड[`Mode`](../mode). |

### यह सभी देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../splitoptions)
* सभा [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

का एक नया उदाहरण प्रारंभ करता है[`SplitOptions`](../../splitoptions) वर्ग.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | अंतिम पृष्ठ संख्या। |

### यह सभी देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../splitoptions)
* सभा [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

का एक नया उदाहरण प्रारंभ करता है[`SplitOptions`](../../splitoptions) वर्ग.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | अंतिम पृष्ठ संख्या। |
| mode | RangeMode | रेंज मोड। |

### यह सभी देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../splitoptions)
* सभा [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

का एक नया उदाहरण प्रारंभ करता है[`SplitOptions`](../../splitoptions) वर्ग.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| releaseSplitStream | ReleaseSplitStream | विधि जो createPageStream विधि द्वारा बनाई गई स्ट्रीम को रिलीज़ करती है। |

### यह सभी देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../splitoptions)
* सभा [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

का एक नया उदाहरण प्रारंभ करता है[`SplitOptions`](../../splitoptions) वर्ग.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| releaseSplitStream | ReleaseSplitStream | विधि जो createPageStream विधि द्वारा बनाई गई स्ट्रीम को रिलीज़ करती है। |
| pageNumbers | Int32[] | पेज नंबर। |

### यह सभी देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../splitoptions)
* सभा [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

का एक नया उदाहरण प्रारंभ करता है[`SplitOptions`](../../splitoptions) वर्ग.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| releaseSplitStream | ReleaseSplitStream | विधि जो createPageStream विधि द्वारा बनाई गई स्ट्रीम को रिलीज़ करती है। |
| pageNumbers | Int32[] | पेज नंबर। |
| splitMode | SplitMode | का बंटवारा मोड[`Mode`](../mode). |

### यह सभी देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../splitoptions)
* सभा [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

का एक नया उदाहरण प्रारंभ करता है[`SplitOptions`](../../splitoptions) वर्ग.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| releaseSplitStream | ReleaseSplitStream | विधि जो createPageStream विधि द्वारा बनाई गई स्ट्रीम को रिलीज़ करती है। |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | अंतिम पृष्ठ संख्या। |

### यह सभी देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../splitoptions)
* सभा [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

का एक नया उदाहरण प्रारंभ करता है[`SplitOptions`](../../splitoptions) वर्ग.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| releaseSplitStream | ReleaseSplitStream | विधि जो createPageStream विधि द्वारा बनाई गई स्ट्रीम को रिलीज़ करती है। |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | अंतिम पृष्ठ संख्या। |
| mode | RangeMode | रेंज मोड। |

### यह सभी देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../splitoptions)
* सभा [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
