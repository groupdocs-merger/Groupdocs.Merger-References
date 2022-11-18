---
title: Merger
second_title: GroupDocs.Merger لمرجع .NET API
description: تهيئة مثيل جديد لـMergergroupdocs.merger/merger فئة .
type: docs
weight: 10
url: /ar/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

تهيئة مثيل جديد لـ[`Merger`](../../merger) فئة .

```csharp
public Merger(Stream document)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Stream | الدفق المقروء. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*document* باطل. |

### أنظر أيضا

* class [Merger](../../merger)
* مساحة الاسم [GroupDocs.Merger](../../merger)
* المجسم [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

تهيئة مثيل جديد لـ[`Merger`](../../merger) فئة .

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Stream | الدفق المقروء. |
| loadOptions | ILoadOptions | خيارات تحميل المستند. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*document* باطل. |
| ArgumentNullException | عندما ألقيت*loadOptions* باطل. |

### أنظر أيضا

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* مساحة الاسم [GroupDocs.Merger](../../merger)
* المجسم [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

تهيئة مثيل جديد لـ[`Merger`](../../merger) فئة .

```csharp
public Merger(Stream document, MergerSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Stream | الدفق المقروء. |
| settings | MergerSettings | إعدادات الدمج. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*document* باطل. |
| ArgumentNullException | عندما ألقيت*settings* باطل. |

### أنظر أيضا

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* مساحة الاسم [GroupDocs.Merger](../../merger)
* المجسم [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

تهيئة مثيل جديد لـ[`Merger`](../../merger) فئة .

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Stream | الدفق المقروء. |
| loadOptions | ILoadOptions | خيارات تحميل المستند. |
| settings | MergerSettings | إعدادات الدمج. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*document* باطل. |
| ArgumentNullException | عندما ألقيت*loadOptions* باطل. |
| ArgumentNullException | عندما ألقيت*settings* باطل. |

### أنظر أيضا

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* مساحة الاسم [GroupDocs.Merger](../../merger)
* المجسم [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

تهيئة مثيل جديد لـ[`Merger`](../../merger) فئة .

```csharp
public Merger(Func<Stream> getFileStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| getFileStream | Func`1 | الطريقة التي ترجع الدفق المقروء. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*getFileStream* باطل. |

### أنظر أيضا

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* مساحة الاسم [GroupDocs.Merger](../../merger)
* المجسم [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

تهيئة مثيل جديد لـ[`Merger`](../../merger) فئة .

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| getFileStream | Func`1 | الطريقة التي ترجع الدفق المقروء. |
| loadOptions | ILoadOptions | خيارات تحميل المستند. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*getFileStream* باطل. |
| ArgumentNullException | عندما ألقيت*loadOptions* باطل. |

### أنظر أيضا

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* مساحة الاسم [GroupDocs.Merger](../../merger)
* المجسم [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

تهيئة مثيل جديد لـ[`Merger`](../../merger) فئة .

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| getFileStream | Func`1 | الطريقة التي ترجع الدفق المقروء. |
| settings | MergerSettings | إعدادات الدمج. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*getFileStream* باطل. |
| ArgumentNullException | عندما ألقيت*settings* باطل. |

### أنظر أيضا

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* مساحة الاسم [GroupDocs.Merger](../../merger)
* المجسم [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

تهيئة مثيل جديد لـ[`Merger`](../../merger) فئة .

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| getFileStream | Func`1 | الطريقة التي ترجع الدفق المقروء. |
| loadOptions | ILoadOptions | خيارات تحميل المستند. |
| settings | MergerSettings | إعدادات الدمج. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*getFileStream* باطل. |
| ArgumentNullException | عندما ألقيت*loadOptions* باطل. |
| ArgumentNullException | عندما ألقيت*settings* باطل. |

### أنظر أيضا

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* مساحة الاسم [GroupDocs.Merger](../../merger)
* المجسم [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

تهيئة مثيل جديد لـ[`Merger`](../../merger) فئة .

```csharp
public Merger(string filePath)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*filePath* فارغ أو فارغ. |

### أنظر أيضا

* class [Merger](../../merger)
* مساحة الاسم [GroupDocs.Merger](../../merger)
* المجسم [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

تهيئة مثيل جديد لـ[`Merger`](../../merger) فئة .

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |
| loadOptions | ILoadOptions | خيارات تحميل المستند. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*filePath* فارغ أو فارغ. |
| ArgumentNullException | عندما ألقيت*loadOptions* باطل. |

### أنظر أيضا

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* مساحة الاسم [GroupDocs.Merger](../../merger)
* المجسم [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

تهيئة مثيل جديد لـ[`Merger`](../../merger) فئة .

```csharp
public Merger(string filePath, MergerSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |
| settings | MergerSettings | إعدادات الدمج. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*filePath* فارغ أو فارغ. |
| ArgumentNullException | عندما ألقيت*settings* باطل. |

### أنظر أيضا

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* مساحة الاسم [GroupDocs.Merger](../../merger)
* المجسم [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

تهيئة مثيل جديد لـ[`Merger`](../../merger) فئة .

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |
| loadOptions | ILoadOptions | خيارات تحميل المستند. |
| settings | MergerSettings | إعدادات الدمج. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*filePath* فارغ أو فارغ. |
| ArgumentNullException | عندما ألقيت*loadOptions* باطل. |
| ArgumentNullException | عندما ألقيت*settings* باطل. |

### أنظر أيضا

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* مساحة الاسم [GroupDocs.Merger](../../merger)
* المجسم [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
