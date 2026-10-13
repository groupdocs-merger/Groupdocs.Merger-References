---
title: "LoadOptions"
second_title: "GroupDocs.Merger .NET के लिए API संदर्भ"
description: "LoadOptionsgroupdocs.merger.domain.options/loadoptions क्लास का नया उदाहरण प्रारंभ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.merger.domain.options/loadoptions/loadoptions/
---
## LoadOptions(FileType) {#constructor}

[`LoadOptions`](../../loadoptions) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public LoadOptions(FileType fileType)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | FileType | लोड करने वाली फ़ाइल का प्रकार। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *fileType* null हो तो फेंका जाता है। |

### साथ ही देखें

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string) {#constructor_6}

[`LoadOptions`](../../loadoptions) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public LoadOptions(string password)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पासवर्ड | String | पासवर्ड-प्रोटेक्टेड फ़ाइल खोलने के लिए पासवर्ड। |

### साथ ही देखें

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string, Encoding) {#constructor_8}

[`LoadOptions`](../../loadoptions) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public LoadOptions(string password, Encoding encoding)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पासवर्ड | String | पासवर्ड-प्रोटेक्टेड फ़ाइल खोलने के लिए पासवर्ड। |
| encoding | Encoding | टेक्स्ट-आधारित फ़ाइलों जैसे [`CSV`](../../../groupdocs.merger.domain/filetype/csv) या [`TXT`](../../../groupdocs.merger.domain/filetype/txt) को खोलते समय उपयोग किया जाने वाला एन्कोडिंग। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *encoding* null हो तो फेंका जाता है। |

### साथ ही देखें

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string) {#constructor_4}

[`LoadOptions`](../../loadoptions) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public LoadOptions(FileType fileType, string password)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | FileType | लोड करने वाली फ़ाइल का प्रकार। |
| पासवर्ड | String | पासवर्ड-प्रोटेक्टेड फ़ाइल खोलने के लिए पासवर्ड। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *fileType* null हो तो फेंका जाता है। |

### साथ ही देखें

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string, Encoding) {#constructor_5}

[`LoadOptions`](../../loadoptions) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public LoadOptions(FileType fileType, string password, Encoding encoding)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | FileType | लोड करने वाली फ़ाइल का प्रकार। |
| पासवर्ड | String | पासवर्ड-प्रोटेक्टेड फ़ाइल खोलने के लिए पासवर्ड। |
| encoding | Encoding | टेक्स्ट-आधारित फ़ाइलों जैसे [`CSV`](../../../groupdocs.merger.domain/filetype/csv) या [`TXT`](../../../groupdocs.merger.domain/filetype/txt) को खोलते समय उपयोग किया जाने वाला एन्कोडिंग। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *fileType* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *encoding* null हो तो फेंका जाता है। |

### साथ ही देखें

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string, FileType, string, Encoding) {#constructor_7}

[`LoadOptions`](../../loadoptions) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public LoadOptions(string extension, FileType fileType, string password, Encoding encoding)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| extension | String | लोड करने वाली फ़ाइल का एक्सटेंशन। |
| fileType | FileType | लोड करने वाली फ़ाइल का प्रकार। |
| पासवर्ड | String | पासवर्ड-प्रोटेक्टेड फ़ाइल खोलने के लिए पासवर्ड। |
| encoding | Encoding | टेक्स्ट-आधारित फ़ाइलों जैसे [`CSV`](../../../groupdocs.merger.domain/filetype/csv) या [`TXT`](../../../groupdocs.merger.domain/filetype/txt) को खोलते समय उपयोग किया जाने वाला एन्कोडिंग। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *fileType* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *encoding* null हो तो फेंका जाता है। |

### साथ ही देखें

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string, Encoding) {#constructor_3}

[`LoadOptions`](../../loadoptions) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password, Encoding encoding)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| iniFileType | FileType | फ़ाइल को इनिशियलाइज़ करने का प्रकार। |
| fileType | FileType | लोड करने वाली फ़ाइल का प्रकार। |
| पासवर्ड | String | पासवर्ड-प्रोटेक्टेड फ़ाइल खोलने के लिए पासवर्ड। |
| encoding | Encoding | टेक्स्ट-आधारित फ़ाइलों जैसे [`CSV`](../../../groupdocs.merger.domain/filetype/csv) या [`TXT`](../../../groupdocs.merger.domain/filetype/txt) को खोलते समय उपयोग किया जाने वाला एन्कोडिंग। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *iniFileType* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *fileType* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *encoding* null हो तो फेंका जाता है। |

### साथ ही देखें

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string) {#constructor_2}

[`LoadOptions`](../../loadoptions) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| iniFileType | FileType | फ़ाइल को इनिशियलाइज़ करने का प्रकार। |
| fileType | FileType | लोड करने वाली फ़ाइल का प्रकार। |
| पासवर्ड | String | पासवर्ड-प्रोटेक्टेड फ़ाइल खोलने के लिए पासवर्ड। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *iniFileType* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *fileType* null हो तो फेंका जाता है। |

### साथ ही देखें

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType) {#constructor_1}

[`LoadOptions`](../../loadoptions) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public LoadOptions(FileType iniFileType, FileType fileType)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| iniFileType | FileType | फ़ाइल को इनिशियलाइज़ करने का प्रकार। |
| fileType | FileType | लोड करने वाली फ़ाइल का प्रकार। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *iniFileType* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *fileType* null हो तो फेंका जाता है। |

### साथ ही देखें

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
