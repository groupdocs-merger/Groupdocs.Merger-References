---
title: "TextSplitOptions"
second_title: "مرجع API لـ GroupDocs.Merger لـ .NET"
description: "يُنشئ مثيلًا جديدًا لفئة TextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions."
type: docs
weight: 10
url: /ar/net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

يُنشئ مثيلًا جديدًا لفئة [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePathFormat | String | تنسيق مسار الملف مثل 'c:/split{0}.doc' أو 'c:/split{0}.{1}' مع الامتداد المحدد مسبقًا. |
| lineNumbers | Int32[] | أرقام الأسطر لتقسيم النص. |

### انظر أيضًا

* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

يُنشئ مثيلًا جديدًا لفئة [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePathFormat | String | تنسيق مسار الملف مثل 'c:/split{0}.doc' أو 'c:/split{0}.{1}' مع الامتداد المحدد مسبقًا. |
| mode | TextSplitMode | الوضع لتقسيم النص. |
| lineNumbers | Int32[] | أرقام الأسطر لتقسيم النص. |

### انظر أيضًا

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

يُنشئ مثيلًا جديدًا لفئة [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | الطريقة التي تُنشئ الدفق المستخدم لكتابة بيانات الانقسام الناتجة. |
| lineNumbers | Int32[] | أرقام الأسطر لتقسيم النص. |

### انظر أيضًا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

يُنشئ مثيلًا جديدًا لفئة [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | الطريقة التي تُنشئ الدفق المستخدم لكتابة بيانات الانقسام الناتجة. |
| mode | TextSplitMode | الوضع لتقسيم النص. |
| lineNumbers | Int32[] | أرقام الأسطر لتقسيم النص. |

### انظر أيضًا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

يُنشئ مثيلًا جديدًا لفئة [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | الطريقة التي تُنشئ الدفق المستخدم لكتابة بيانات الانقسام الناتجة. |
| releaseSplitStream | ReleaseSplitStream | الطريقة التي تُفرج عن الدفق الذي تم إنشاؤه بواسطة طريقة createPageStream. |
| lineNumbers | Int32[] | أرقام الأسطر لتقسيم النص. |

### انظر أيضًا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

يُنشئ مثيلًا جديدًا لفئة [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | الطريقة التي تُنشئ الدفق المستخدم لكتابة بيانات الانقسام الناتجة. |
| releaseSplitStream | ReleaseSplitStream | الطريقة التي تُفرج عن الدفق الذي تم إنشاؤه بواسطة طريقة createPageStream. |
| mode | TextSplitMode | الوضع لتقسيم النص. |
| lineNumbers | Int32[] | أرقام الأسطر لتقسيم النص. |

### انظر أيضًا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
