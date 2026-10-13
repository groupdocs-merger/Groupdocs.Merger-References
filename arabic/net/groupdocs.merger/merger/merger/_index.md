---
title: "الدمج"
second_title: "مرجع API لـ GroupDocs.Merger لـ .NET"
description: "ينشئ مثيلاً جديدًا من الفئة Mergergroupdocs.merger/merger."
type: docs
weight: 10
url: /ar/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

ينشئ مثيلاً جديدًا من الفئة [`Merger`](../../merger).

```csharp
public Merger(Stream document)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| document | Stream | دفق القراءة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم الإلقاء عندما يكون *document* null. |

### انظر أيضًا

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

ينشئ مثيلاً جديدًا من الفئة [`Merger`](../../merger).

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| document | Stream | دفق القراءة. |
| loadOptions | ILoadOptions | خيارات تحميل المستند. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم الإلقاء عندما يكون *document* null. |
| ArgumentNullException | يُرمى عندما يكون *loadOptions* فارغًا (null). |

### انظر أيضًا

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

ينشئ مثيلاً جديدًا من الفئة [`Merger`](../../merger).

```csharp
public Merger(Stream document, MergerSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| document | Stream | دفق القراءة. |
| settings | MergerSettings | إعدادات Merger. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم الإلقاء عندما يكون *document* null. |
| ArgumentNullException | يُرمى عندما تكون *settings* فارغة (null). |

### انظر أيضًا

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

ينشئ مثيلاً جديدًا من الفئة [`Merger`](../../merger).

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| document | Stream | دفق القراءة. |
| loadOptions | ILoadOptions | خيارات تحميل المستند. |
| settings | MergerSettings | إعدادات Merger. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم الإلقاء عندما يكون *document* null. |
| ArgumentNullException | يُرمى عندما يكون *loadOptions* فارغًا (null). |
| ArgumentNullException | يُرمى عندما تكون *settings* فارغة (null). |

### انظر أيضًا

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

ينشئ مثيلاً جديدًا من الفئة [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| getFileStream | Func`1 | الطريقة التي تُعيد دفق القراءة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *getFileStream* فارغًا (null). |

### انظر أيضًا

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

ينشئ مثيلاً جديدًا من الفئة [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| getFileStream | Func`1 | الطريقة التي تُعيد دفق القراءة. |
| loadOptions | ILoadOptions | خيارات تحميل المستند. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *getFileStream* فارغًا (null). |
| ArgumentNullException | يُرمى عندما يكون *loadOptions* فارغًا (null). |

### انظر أيضًا

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

ينشئ مثيلاً جديدًا من الفئة [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| getFileStream | Func`1 | الطريقة التي تُعيد دفق القراءة. |
| settings | MergerSettings | إعدادات Merger. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *getFileStream* فارغًا (null). |
| ArgumentNullException | يُرمى عندما تكون *settings* فارغة (null). |

### انظر أيضًا

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

ينشئ مثيلاً جديدًا من الفئة [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| getFileStream | Func`1 | الطريقة التي تُعيد دفق القراءة. |
| loadOptions | ILoadOptions | خيارات تحميل المستند. |
| settings | MergerSettings | إعدادات Merger. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *getFileStream* فارغًا (null). |
| ArgumentNullException | يُرمى عندما يكون *loadOptions* فارغًا (null). |
| ArgumentNullException | يُرمى عندما تكون *settings* فارغة (null). |

### انظر أيضًا

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

ينشئ مثيلاً جديدًا من الفئة [`Merger`](../../merger).

```csharp
public Merger(string filePath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *filePath* فارغًا أو خاليًا (null). |

### انظر أيضًا

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

ينشئ مثيلاً جديدًا من الفئة [`Merger`](../../merger).

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |
| loadOptions | ILoadOptions | خيارات تحميل المستند. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *filePath* فارغًا أو خاليًا (null). |
| ArgumentNullException | يُرمى عندما يكون *loadOptions* فارغًا (null). |

### انظر أيضًا

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

ينشئ مثيلاً جديدًا من الفئة [`Merger`](../../merger).

```csharp
public Merger(string filePath, MergerSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |
| settings | MergerSettings | إعدادات Merger. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *filePath* فارغًا أو خاليًا (null). |
| ArgumentNullException | يُرمى عندما تكون *settings* فارغة (null). |

### انظر أيضًا

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

ينشئ مثيلاً جديدًا من الفئة [`Merger`](../../merger).

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |
| loadOptions | ILoadOptions | خيارات تحميل المستند. |
| settings | MergerSettings | إعدادات Merger. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *filePath* فارغًا أو خاليًا (null). |
| ArgumentNullException | يُرمى عندما يكون *loadOptions* فارغًا (null). |
| ArgumentNullException | يُرمى عندما تكون *settings* فارغة (null). |

### انظر أيضًا

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
