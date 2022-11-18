---
title: TextSplitOptions
second_title: GroupDocs.Merger لمرجع .NET API
description: يقوم بتهيئة مثيل جديد لملفTextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions فئة .
type: docs
weight: 10
url: /ar/net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

يقوم بتهيئة مثيل جديد لملف[`TextSplitOptions`](../../textsplitoptions) فئة .

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePathFormat | String | تنسيق مسار الملف مثل "c: / split {0} .doc" أو "c: / split {0}. {1}" بامتداد محدد بالفعل. |
| lineNumbers | Int32[] | أرقام الأسطر لتقسيم النص. |

### أنظر أيضا

* class [TextSplitOptions](../../textsplitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* المجسم [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

يقوم بتهيئة مثيل جديد لملف[`TextSplitOptions`](../../textsplitoptions) فئة .

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePathFormat | String | تنسيق مسار الملف مثل "c: / split {0} .doc" أو "c: / split {0}. {1}" بامتداد محدد بالفعل. |
| mode | TextSplitMode | وضع تقسيم النص. |
| lineNumbers | Int32[] | أرقام الأسطر لتقسيم النص. |

### أنظر أيضا

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* المجسم [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

يقوم بتهيئة مثيل جديد لملف[`TextSplitOptions`](../../textsplitoptions) فئة .

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات تقسيم الإخراج. |
| lineNumbers | Int32[] | أرقام الأسطر لتقسيم النص. |

### أنظر أيضا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* المجسم [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`TextSplitOptions`](../../textsplitoptions) فئة .

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات تقسيم الإخراج. |
| mode | TextSplitMode | وضع تقسيم النص. |
| lineNumbers | Int32[] | أرقام الأسطر لتقسيم النص. |

### أنظر أيضا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* المجسم [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`TextSplitOptions`](../../textsplitoptions) فئة .

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات تقسيم الإخراج. |
| releaseSplitStream | ReleaseSplitStream | الطريقة التي تطلق الدفق الذي تم إنشاؤه بواسطة طريقة createPageStream. |
| lineNumbers | Int32[] | أرقام الأسطر لتقسيم النص. |

### أنظر أيضا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* المجسم [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

يقوم بتهيئة مثيل جديد لملف[`TextSplitOptions`](../../textsplitoptions) فئة .

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | طريقة إنشاء الدفق المستخدمة لكتابة بيانات تقسيم الإخراج. |
| releaseSplitStream | ReleaseSplitStream | الطريقة التي تطلق الدفق الذي تم إنشاؤه بواسطة طريقة createPageStream. |
| mode | TextSplitMode | وضع تقسيم النص. |
| lineNumbers | Int32[] | أرقام الأسطر لتقسيم النص. |

### أنظر أيضا

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* مساحة الاسم [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* المجسم [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
