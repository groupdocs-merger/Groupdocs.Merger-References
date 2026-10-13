---
title: "SplitOptions"
second_title: "مرجع API لـ GroupDocs.Merger لـ .NET"
description: "يقوم بإنشاء نسخة جديدة من الفئة SplitOptionsgroupdocs.merger.domain.options/splitoptions."
type: docs
weight: 10
url: /ar/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

يقوم بإنشاء نسخة جديدة من الفئة [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePathFormat | String | تنسيق مسار الملف مثل 'c:/split{0}.doc' أو 'c:/split{0}.{1}' مع الامتداد المحدد مسبقًا. |
| pageNumbers | Int32[] | أرقام الصفحات. |

### انظر أيضًا

* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

يقوم بإنشاء نسخة جديدة من الفئة [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePathFormat | String | تنسيق مسار الملف مثل 'c:/split{0}.doc' أو 'c:/split{0}.{1}' مع الامتداد المحدد مسبقًا. |
| pageNumbers | Int32[] | أرقام الصفحات. |
| splitMode | SplitMode | وضع التقسيم لـ [`Mode`](../mode). |

### انظر أيضًا

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

يقوم بإنشاء نسخة جديدة من الفئة [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePathFormat | String | تنسيق مسار الملف مثل 'c:/split{0}.doc' أو 'c:/split{0}.{1}' مع الامتداد المحدد مسبقًا. |
| startNumber | Int32 | رقم الصفحة البداية. |
| endNumber | Int32 | رقم الصفحة النهائية. |

### انظر أيضًا

* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

يقوم بإنشاء نسخة جديدة من الفئة [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePathFormat | String | تنسيق مسار الملف مثل 'c:/split{0}.doc' أو 'c:/split{0}.{1}' مع الامتداد المحدد مسبقًا. |
| startNumber | Int32 | رقم الصفحة البداية. |
| endNumber | Int32 | رقم الصفحة النهائية. |
| mode | RangeMode | وضع النطاق. |

### انظر أيضًا

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

يقوم بإنشاء نسخة جديدة من الفئة [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | الطريقة التي تُنشئ الدفق المستخدم لكتابة بيانات الانقسام الناتجة. |

### انظر أيضًا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

يقوم بإنشاء نسخة جديدة من الفئة [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | الطريقة التي تُنشئ الدفق المستخدم لكتابة بيانات الانقسام الناتجة. |
| pageNumbers | Int32[] | أرقام الصفحات. |

### انظر أيضًا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

يقوم بإنشاء نسخة جديدة من الفئة [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | الطريقة التي تُنشئ الدفق المستخدم لكتابة بيانات الانقسام الناتجة. |
| pageNumbers | Int32[] | أرقام الصفحات. |
| splitMode | SplitMode | وضع التقسيم لـ [`Mode`](../mode). |

### انظر أيضًا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

يقوم بإنشاء نسخة جديدة من الفئة [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | الطريقة التي تُنشئ الدفق المستخدم لكتابة بيانات الانقسام الناتجة. |
| startNumber | Int32 | رقم الصفحة البداية. |
| endNumber | Int32 | رقم الصفحة النهائية. |

### انظر أيضًا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

يقوم بإنشاء نسخة جديدة من الفئة [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | الطريقة التي تُنشئ الدفق المستخدم لكتابة بيانات الانقسام الناتجة. |
| startNumber | Int32 | رقم الصفحة البداية. |
| endNumber | Int32 | رقم الصفحة النهائية. |
| mode | RangeMode | وضع النطاق. |

### انظر أيضًا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

يقوم بإنشاء نسخة جديدة من الفئة [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | الطريقة التي تُنشئ الدفق المستخدم لكتابة بيانات الانقسام الناتجة. |
| releaseSplitStream | ReleaseSplitStream | الطريقة التي تُفرج عن الدفق الذي تم إنشاؤه بواسطة طريقة createPageStream. |

### انظر أيضًا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

يقوم بإنشاء نسخة جديدة من الفئة [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | الطريقة التي تُنشئ الدفق المستخدم لكتابة بيانات الانقسام الناتجة. |
| releaseSplitStream | ReleaseSplitStream | الطريقة التي تُفرج عن الدفق الذي تم إنشاؤه بواسطة طريقة createPageStream. |
| pageNumbers | Int32[] | أرقام الصفحات. |

### انظر أيضًا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

يقوم بإنشاء نسخة جديدة من الفئة [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | الطريقة التي تُنشئ الدفق المستخدم لكتابة بيانات الانقسام الناتجة. |
| releaseSplitStream | ReleaseSplitStream | الطريقة التي تُفرج عن الدفق الذي تم إنشاؤه بواسطة طريقة createPageStream. |
| pageNumbers | Int32[] | أرقام الصفحات. |
| splitMode | SplitMode | وضع التقسيم لـ [`Mode`](../mode). |

### انظر أيضًا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

يقوم بإنشاء نسخة جديدة من الفئة [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | الطريقة التي تُنشئ الدفق المستخدم لكتابة بيانات الانقسام الناتجة. |
| releaseSplitStream | ReleaseSplitStream | الطريقة التي تُفرج عن الدفق الذي تم إنشاؤه بواسطة طريقة createPageStream. |
| startNumber | Int32 | رقم الصفحة البداية. |
| endNumber | Int32 | رقم الصفحة النهائية. |

### انظر أيضًا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

يقوم بإنشاء نسخة جديدة من الفئة [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | الطريقة التي تُنشئ الدفق المستخدم لكتابة بيانات الانقسام الناتجة. |
| releaseSplitStream | ReleaseSplitStream | الطريقة التي تُفرج عن الدفق الذي تم إنشاؤه بواسطة طريقة createPageStream. |
| startNumber | Int32 | رقم الصفحة البداية. |
| endNumber | Int32 | رقم الصفحة النهائية. |
| mode | RangeMode | وضع النطاق. |

### انظر أيضًا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
