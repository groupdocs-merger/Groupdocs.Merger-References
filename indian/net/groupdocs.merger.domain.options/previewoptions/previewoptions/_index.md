---
title: "PreviewOptions"
second_title: "GroupDocs.Merger .NET के लिए API संदर्भ"
description: "PreviewOptionsgroupdocs.merger.domain.options/previewoptions क्लास का नया उदाहरण प्रारंभ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.merger.domain.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream, PreviewMode) {#constructor_4}

[`PreviewOptions`](../../previewoptions) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | आउटपुट पृष्ठ डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करने वाली विधि। |
| previewMode | PreviewMode | [`Mode`](../mode) का प्रीव्यू मोड। |

### साथ ही देखें

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int[]) {#constructor_7}

[`PreviewOptions`](../../previewoptions) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int[] pageNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | आउटपुट पृष्ठ डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करने वाली विधि। |
| previewMode | PreviewMode | [`Mode`](../mode) का प्रीव्यू मोड। |
| pageNumbers | Int32[] | पृष्ठ संख्याएँ। |

### साथ ही देखें

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int) {#constructor_5}

[`PreviewOptions`](../../previewoptions) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | आउटपुट पृष्ठ डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करने वाली विधि। |
| previewMode | PreviewMode | [`Mode`](../mode) का प्रीव्यू मोड। |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | समाप्ति पृष्ठ संख्या। |

### साथ ही देखें

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int, RangeMode) {#constructor_6}

[`PreviewOptions`](../../previewoptions) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber, RangeMode mode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | आउटपुट पृष्ठ डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करने वाली विधि। |
| previewMode | PreviewMode | [`Mode`](../mode) का प्रीव्यू मोड। |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | समाप्ति पृष्ठ संख्या। |
| mode | RangeMode | रेंज मोड। |

### साथ ही देखें

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode) {#constructor}

[`PreviewOptions`](../../previewoptions) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | आउटपुट पृष्ठ डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करने वाली विधि। |
| releasePageStream | ReleasePageStream | यह मेथड createPageStream मेथड द्वारा निर्मित स्ट्रीम को रिलीज़ करता है। |
| previewMode | PreviewMode | [`Mode`](../mode) का प्रीव्यू मोड। |

### साथ ही देखें

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int[]) {#constructor_3}

[`PreviewOptions`](../../previewoptions) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int[] pageNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | आउटपुट पृष्ठ डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करने वाली विधि। |
| releasePageStream | ReleasePageStream | यह मेथड createPageStream मेथड द्वारा निर्मित स्ट्रीम को रिलीज़ करता है। |
| previewMode | PreviewMode | [`Mode`](../mode) का प्रीव्यू मोड। |
| pageNumbers | Int32[] | पृष्ठ संख्याएँ। |

### साथ ही देखें

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int) {#constructor_1}

[`PreviewOptions`](../../previewoptions) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | आउटपुट पृष्ठ डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करने वाली विधि। |
| releasePageStream | ReleasePageStream | यह मेथड createPageStream मेथड द्वारा निर्मित स्ट्रीम को रिलीज़ करता है। |
| previewMode | PreviewMode | [`Mode`](../mode) का प्रीव्यू मोड। |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | समाप्ति पृष्ठ संख्या। |

### साथ ही देखें

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int, RangeMode) {#constructor_2}

[`PreviewOptions`](../../previewoptions) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber, RangeMode mode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | आउटपुट पृष्ठ डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करने वाली विधि। |
| releasePageStream | ReleasePageStream | यह मेथड createPageStream मेथड द्वारा निर्मित स्ट्रीम को रिलीज़ करता है। |
| previewMode | PreviewMode | [`Mode`](../mode) का प्रीव्यू मोड। |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | समाप्ति पृष्ठ संख्या। |
| mode | RangeMode | रेंज मोड। |

### साथ ही देखें

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
