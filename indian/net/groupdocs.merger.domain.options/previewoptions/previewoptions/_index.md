---
title: PreviewOptions
second_title: .NET API संदर्भ के लिए GroupDocs.Merger
description: क एक नय उदहरण प्ररंभ करत हैPreviewOptionsgroupdocs.merger.domain.options/previewoptions वर्ग.
type: docs
weight: 10
url: /hi/net/groupdocs.merger.domain.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream, PreviewMode) {#constructor_4}

का एक नया उदाहरण प्रारंभ करता है[`PreviewOptions`](../../previewoptions) वर्ग.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | आउटपुट पेज डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| previewMode | PreviewMode | का पूर्वावलोकन मोड[`Mode`](../mode) |

### यह सभी देखें

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../previewoptions)
* सभा [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int[]) {#constructor_7}

का एक नया उदाहरण प्रारंभ करता है[`PreviewOptions`](../../previewoptions) वर्ग.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int[] pageNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | आउटपुट पेज डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| previewMode | PreviewMode | का पूर्वावलोकन मोड[`Mode`](../mode) |
| pageNumbers | Int32[] | पेज नंबर। |

### यह सभी देखें

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../previewoptions)
* सभा [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int) {#constructor_5}

का एक नया उदाहरण प्रारंभ करता है[`PreviewOptions`](../../previewoptions) वर्ग.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | आउटपुट पेज डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| previewMode | PreviewMode | का पूर्वावलोकन मोड[`Mode`](../mode) |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | अंतिम पृष्ठ संख्या। |

### यह सभी देखें

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../previewoptions)
* सभा [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int, RangeMode) {#constructor_6}

का एक नया उदाहरण प्रारंभ करता है[`PreviewOptions`](../../previewoptions) वर्ग.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber, RangeMode mode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | आउटपुट पेज डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| previewMode | PreviewMode | का पूर्वावलोकन मोड[`Mode`](../mode) |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | अंतिम पृष्ठ संख्या। |
| mode | RangeMode | रेंज मोड। |

### यह सभी देखें

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../previewoptions)
* सभा [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode) {#constructor}

का एक नया उदाहरण प्रारंभ करता है[`PreviewOptions`](../../previewoptions) वर्ग.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | आउटपुट पेज डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| releasePageStream | ReleasePageStream | विधि जो createPageStream विधि द्वारा बनाई गई स्ट्रीम को रिलीज़ करती है। |
| previewMode | PreviewMode | का पूर्वावलोकन मोड[`Mode`](../mode) |

### यह सभी देखें

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../previewoptions)
* सभा [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int[]) {#constructor_3}

का एक नया उदाहरण प्रारंभ करता है[`PreviewOptions`](../../previewoptions) वर्ग.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int[] pageNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | आउटपुट पेज डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| releasePageStream | ReleasePageStream | विधि जो createPageStream विधि द्वारा बनाई गई स्ट्रीम को रिलीज़ करती है। |
| previewMode | PreviewMode | का पूर्वावलोकन मोड[`Mode`](../mode) |
| pageNumbers | Int32[] | पेज नंबर। |

### यह सभी देखें

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../previewoptions)
* सभा [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int) {#constructor_1}

का एक नया उदाहरण प्रारंभ करता है[`PreviewOptions`](../../previewoptions) वर्ग.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | आउटपुट पेज डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| releasePageStream | ReleasePageStream | विधि जो createPageStream विधि द्वारा बनाई गई स्ट्रीम को रिलीज़ करती है। |
| previewMode | PreviewMode | का पूर्वावलोकन मोड[`Mode`](../mode) |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | अंतिम पृष्ठ संख्या। |

### यह सभी देखें

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../previewoptions)
* सभा [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int, RangeMode) {#constructor_2}

का एक नया उदाहरण प्रारंभ करता है[`PreviewOptions`](../../previewoptions) वर्ग.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber, RangeMode mode)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | CreatePageStream | आउटपुट पेज डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टेंट करने वाली विधि। |
| releasePageStream | ReleasePageStream | विधि जो createPageStream विधि द्वारा बनाई गई स्ट्रीम को रिलीज़ करती है। |
| previewMode | PreviewMode | का पूर्वावलोकन मोड[`Mode`](../mode) |
| startNumber | Int32 | प्रारंभ पृष्ठ संख्या। |
| endNumber | Int32 | अंतिम पृष्ठ संख्या। |
| mode | RangeMode | रेंज मोड। |

### यह सभी देखें

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* नाम स्थान [GroupDocs.Merger.Domain.Options](../../previewoptions)
* सभा [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
