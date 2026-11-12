---
title: "SplitOptions"
second_title: "GroupDocs.Merger .NET के लिए API संदर्भ"
description: "एक नया उदाहरण प्रारंभ करता है SplitOptionsgroupdocs.merger.domain.options/splitoptions क्लास का।"
type: docs
weight: 10
url: /hi/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

एक नया उदाहरण प्रारंभ करता है [`SplitOptions`](../../splitoptions) क्लास का।

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | String | फ़ाइल पथ स्वरूप, उदाहरण के लिए 'c:/split{0}.doc' या 'c:/split{0}.{1}' जिसमें पहले से परिभाषित एक्सटेंशन हो। |
| pageNumbers | Int32[] | पृष्ठ संख्याएँ। |

### साथ ही देखें

* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

एक नया उदाहरण प्रारंभ करता है [`SplitOptions`](../../splitoptions) क्लास का।

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | String | फ़ाइल पथ स्वरूप, उदाहरण के लिए 'c:/split{0}.doc' या 'c:/split{0}.{1}' जिसमें पहले से परिभाषित एक्सटेंशन हो। |
| pageNumbers | Int32[] | पृष्ठ संख्याएँ। |
| splitMode | SplitMode | [`Mode`](../mode) का विभाजन मोड। |

### साथ ही देखें

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

एक नया उदाहरण प्रारंभ करता है [`SplitOptions`](../../splitoptions) क्लास का।

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | String | फ़ाइल पथ स्वरूप, उदाहरण के लिए 'c:/split{0}.doc' या 'c:/split{0}.{1}' जिसमें पहले से परिभाषित एक्सटेंशन हो। |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | समाप्ति पृष्ठ संख्या। |

### साथ ही देखें

* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

एक नया उदाहरण प्रारंभ करता है [`SplitOptions`](../../splitoptions) क्लास का।

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | String | फ़ाइल पथ स्वरूप, उदाहरण के लिए 'c:/split{0}.doc' या 'c:/split{0}.{1}' जिसमें पहले से परिभाषित एक्सटेंशन हो। |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | समाप्ति पृष्ठ संख्या। |
| mode | RangeMode | रेंज मोड। |

### साथ ही देखें

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

एक नया उदाहरण प्रारंभ करता है [`SplitOptions`](../../splitoptions) क्लास का।

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंशिएट करने वाला मेथड। |

### साथ ही देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

एक नया उदाहरण प्रारंभ करता है [`SplitOptions`](../../splitoptions) क्लास का।

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंशिएट करने वाला मेथड। |
| pageNumbers | Int32[] | पृष्ठ संख्याएँ। |

### साथ ही देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

एक नया उदाहरण प्रारंभ करता है [`SplitOptions`](../../splitoptions) क्लास का।

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंशिएट करने वाला मेथड। |
| pageNumbers | Int32[] | पृष्ठ संख्याएँ। |
| splitMode | SplitMode | [`Mode`](../mode) का विभाजन मोड। |

### साथ ही देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

एक नया उदाहरण प्रारंभ करता है [`SplitOptions`](../../splitoptions) क्लास का।

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंशिएट करने वाला मेथड। |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | समाप्ति पृष्ठ संख्या। |

### साथ ही देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

एक नया उदाहरण प्रारंभ करता है [`SplitOptions`](../../splitoptions) क्लास का।

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंशिएट करने वाला मेथड। |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | समाप्ति पृष्ठ संख्या। |
| mode | RangeMode | रेंज मोड। |

### साथ ही देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

एक नया उदाहरण प्रारंभ करता है [`SplitOptions`](../../splitoptions) क्लास का।

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंशिएट करने वाला मेथड। |
| releaseSplitStream | ReleaseSplitStream | यह मेथड createPageStream मेथड द्वारा निर्मित स्ट्रीम को रिलीज़ करता है। |

### साथ ही देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

एक नया उदाहरण प्रारंभ करता है [`SplitOptions`](../../splitoptions) क्लास का।

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंशिएट करने वाला मेथड। |
| releaseSplitStream | ReleaseSplitStream | यह मेथड createPageStream मेथड द्वारा निर्मित स्ट्रीम को रिलीज़ करता है। |
| pageNumbers | Int32[] | पृष्ठ संख्याएँ। |

### साथ ही देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

एक नया उदाहरण प्रारंभ करता है [`SplitOptions`](../../splitoptions) क्लास का।

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंशिएट करने वाला मेथड। |
| releaseSplitStream | ReleaseSplitStream | यह मेथड createPageStream मेथड द्वारा निर्मित स्ट्रीम को रिलीज़ करता है। |
| pageNumbers | Int32[] | पृष्ठ संख्याएँ। |
| splitMode | SplitMode | [`Mode`](../mode) का विभाजन मोड। |

### साथ ही देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

एक नया उदाहरण प्रारंभ करता है [`SplitOptions`](../../splitoptions) क्लास का।

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंशिएट करने वाला मेथड। |
| releaseSplitStream | ReleaseSplitStream | यह मेथड createPageStream मेथड द्वारा निर्मित स्ट्रीम को रिलीज़ करता है। |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | समाप्ति पृष्ठ संख्या। |

### साथ ही देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

एक नया उदाहरण प्रारंभ करता है [`SplitOptions`](../../splitoptions) क्लास का।

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | आउटपुट स्प्लिट डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंशिएट करने वाला मेथड। |
| releaseSplitStream | ReleaseSplitStream | यह मेथड createPageStream मेथड द्वारा निर्मित स्ट्रीम को रिलीज़ करता है। |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | समाप्ति पृष्ठ संख्या। |
| mode | RangeMode | रेंज मोड। |

### साथ ही देखें

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
