---
title: SplitOptions
second_title: GroupDocs.Merger لمرجع .NET API
description: يقوم بتهيئة مثيل جديد لملفSplitOptionsgroupdocs.merger.domain.options/splitoptions فئة .
type: docs
weight: 10
url: /ar/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

يقوم بتهيئة مثيل جديد لملف[`SplitOptions`](../../splitoptions) فئة .

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePathFormat | String | تنسيق مسار الملف مثل "c: / split {0} .doc" أو "c: / split {0}. {1}" بامتداد محدد مسبقًا. |
| pageNumbers | Int32[] | أرقام الصفحات. |

### أنظر أيضا

* class [SplitOptions](../../splitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../splitoptions)
* المجسم [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

يقوم بتهيئة مثيل جديد لملف[`SplitOptions`](../../splitoptions) فئة .

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePathFormat | String | تنسيق مسار الملف مثل "c: / split {0} .doc" أو "c: / split {0}. {1}" بامتداد محدد مسبقًا. |
| pageNumbers | Int32[] | أرقام الصفحات. |
| splitMode | SplitMode | وضع تقسيم[`Mode`](../mode). |

### أنظر أيضا

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../splitoptions)
* المجسم [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

يقوم بتهيئة مثيل جديد لملف[`SplitOptions`](../../splitoptions) فئة .

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePathFormat | String | تنسيق مسار الملف مثل "c: / split {0} .doc" أو "c: / split {0}. {1}" بامتداد محدد مسبقًا. |
| startNumber | Int32 | رقم صفحة البداية. |
| endNumber | Int32 | رقم صفحة النهاية. |

### أنظر أيضا

* class [SplitOptions](../../splitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../splitoptions)
* المجسم [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

يقوم بتهيئة مثيل جديد لملف[`SplitOptions`](../../splitoptions) فئة .

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePathFormat | String | تنسيق مسار الملف مثل "c: / split {0} .doc" أو "c: / split {0}. {1}" بامتداد محدد مسبقًا. |
| startNumber | Int32 | رقم صفحة البداية. |
| endNumber | Int32 | رقم صفحة النهاية. |
| mode | RangeMode | وضع النطاق. |

### أنظر أيضا

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../splitoptions)
* المجسم [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

يقوم بتهيئة مثيل جديد لملف[`SplitOptions`](../../splitoptions) فئة .

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات تقسيم الإخراج. |

### أنظر أيضا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../splitoptions)
* المجسم [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

يقوم بتهيئة مثيل جديد لملف[`SplitOptions`](../../splitoptions) فئة .

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات تقسيم الإخراج. |
| pageNumbers | Int32[] | أرقام الصفحات. |

### أنظر أيضا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../splitoptions)
* المجسم [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

يقوم بتهيئة مثيل جديد لملف[`SplitOptions`](../../splitoptions) فئة .

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات تقسيم الإخراج. |
| pageNumbers | Int32[] | أرقام الصفحات. |
| splitMode | SplitMode | وضع تقسيم[`Mode`](../mode). |

### أنظر أيضا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../splitoptions)
* المجسم [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

يقوم بتهيئة مثيل جديد لملف[`SplitOptions`](../../splitoptions) فئة .

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات تقسيم الإخراج. |
| startNumber | Int32 | رقم صفحة البداية. |
| endNumber | Int32 | رقم صفحة النهاية. |

### أنظر أيضا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../splitoptions)
* المجسم [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

يقوم بتهيئة مثيل جديد لملف[`SplitOptions`](../../splitoptions) فئة .

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات تقسيم الإخراج. |
| startNumber | Int32 | رقم صفحة البداية. |
| endNumber | Int32 | رقم صفحة النهاية. |
| mode | RangeMode | وضع النطاق. |

### أنظر أيضا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../splitoptions)
* المجسم [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`SplitOptions`](../../splitoptions) فئة .

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات تقسيم الإخراج. |
| releaseSplitStream | ReleaseSplitStream | الطريقة التي تطلق الدفق الذي تم إنشاؤه بواسطة طريقة createPageStream. |

### أنظر أيضا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../splitoptions)
* المجسم [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

يقوم بتهيئة مثيل جديد لملف[`SplitOptions`](../../splitoptions) فئة .

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات تقسيم الإخراج. |
| releaseSplitStream | ReleaseSplitStream | الطريقة التي تطلق الدفق الذي تم إنشاؤه بواسطة طريقة createPageStream. |
| pageNumbers | Int32[] | أرقام الصفحات. |

### أنظر أيضا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../splitoptions)
* المجسم [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

يقوم بتهيئة مثيل جديد لملف[`SplitOptions`](../../splitoptions) فئة .

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات تقسيم الإخراج. |
| releaseSplitStream | ReleaseSplitStream | الطريقة التي تطلق الدفق الذي تم إنشاؤه بواسطة طريقة createPageStream. |
| pageNumbers | Int32[] | أرقام الصفحات. |
| splitMode | SplitMode | وضع تقسيم[`Mode`](../mode). |

### أنظر أيضا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../splitoptions)
* المجسم [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`SplitOptions`](../../splitoptions) فئة .

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات تقسيم الإخراج. |
| releaseSplitStream | ReleaseSplitStream | الطريقة التي تطلق الدفق الذي تم إنشاؤه بواسطة طريقة createPageStream. |
| startNumber | Int32 | رقم صفحة البداية. |
| endNumber | Int32 | رقم صفحة النهاية. |

### أنظر أيضا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../splitoptions)
* المجسم [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

يقوم بتهيئة مثيل جديد لملف[`SplitOptions`](../../splitoptions) فئة .

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات تقسيم الإخراج. |
| releaseSplitStream | ReleaseSplitStream | الطريقة التي تطلق الدفق الذي تم إنشاؤه بواسطة طريقة createPageStream. |
| startNumber | Int32 | رقم صفحة البداية. |
| endNumber | Int32 | رقم صفحة النهاية. |
| mode | RangeMode | وضع النطاق. |

### أنظر أيضا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../splitoptions)
* المجسم [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
