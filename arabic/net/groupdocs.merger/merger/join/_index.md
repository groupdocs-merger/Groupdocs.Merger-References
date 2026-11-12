---
title: "Join"
second_title: "مرجع API لـ GroupDocs.Merger لـ .NET"
description: "يجمع المستندات في مستند واحد."
type: docs
weight: 120
url: /ar/net/groupdocs.merger/merger/join/
---
## Join(Stream) {#join}

يجمع المستندات في مستند واحد.

```csharp
public IMerger Join(Stream document)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| document | Stream | المستند المدمج. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم الإلقاء عندما يكون *document* null. |

### ملاحظات

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### انظر أيضًا

* interface [IMerger](../../imerger)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IJoinOptions) {#join_2}

يجمع المستندات في مستند واحد.

```csharp
public IMerger Join(Stream document, IJoinOptions joinOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| document | Stream | المستند المدمج. |
| joinOptions | IJoinOptions | خيارات الجمع. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم الإلقاء عندما يكون *document* null. |
| ArgumentNullException | يُرمى عندما تكون *joinOptions* فارغة (null). |

### ملاحظات

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### انظر أيضًا

* interface [IMerger](../../imerger)
* interface [IJoinOptions](../../../groupdocs.merger.domain.options/ijoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IPageJoinOptions) {#join_3}

يجمع المستندات في مستند واحد.

```csharp
public IMerger Join(Stream document, IPageJoinOptions joinOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| document | Stream | المستند المدمج. |
| joinOptions | IPageJoinOptions | خيارات الجمع. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم الإلقاء عندما يكون *document* null. |
| ArgumentNullException | يُرمى عندما تكون *joinOptions* فارغة (null). |

### ملاحظات

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### انظر أيضًا

* interface [IMerger](../../imerger)
* interface [IPageJoinOptions](../../../groupdocs.merger.domain.options/ipagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IImageJoinOptions) {#join_1}

يجمع المستندات في مستند واحد.

```csharp
public IMerger Join(Stream document, IImageJoinOptions joinOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| document | Stream | المستند المدمج. |
| joinOptions | IImageJoinOptions | خيارات دمج الصور. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم الإلقاء عندما يكون *document* null. |
| ArgumentNullException | يُرمى عندما تكون *joinOptions* فارغة (null). |

### ملاحظات

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### انظر أيضًا

* interface [IMerger](../../imerger)
* interface [IImageJoinOptions](../../../groupdocs.merger.domain.options/iimagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string) {#join_4}

يجمع المستندات في مستند واحد.

```csharp
public IMerger Join(string filePath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف للوثيقة المدمجة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *filePath* فارغًا أو خاليًا (null). |

### ملاحظات

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### انظر أيضًا

* interface [IMerger](../../imerger)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IJoinOptions) {#join_6}

يجمع المستندات في مستند واحد.

```csharp
public IMerger Join(string filePath, IJoinOptions joinOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف للوثيقة المدمجة. |
| joinOptions | IJoinOptions | خيارات الجمع. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *filePath* فارغًا أو خاليًا (null). |
| ArgumentNullException | يُرمى عندما تكون *joinOptions* فارغة (null). |

### ملاحظات

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### انظر أيضًا

* interface [IMerger](../../imerger)
* interface [IJoinOptions](../../../groupdocs.merger.domain.options/ijoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IPageJoinOptions) {#join_7}

يجمع المستندات في مستند واحد.

```csharp
public IMerger Join(string filePath, IPageJoinOptions joinOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف للوثيقة المدمجة. |
| joinOptions | IPageJoinOptions | خيارات الجمع. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *filePath* فارغًا أو خاليًا (null). |
| ArgumentNullException | يُرمى عندما تكون *joinOptions* فارغة (null). |

### ملاحظات

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### انظر أيضًا

* interface [IMerger](../../imerger)
* interface [IPageJoinOptions](../../../groupdocs.merger.domain.options/ipagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IImageJoinOptions) {#join_5}

يجمع المستندات في مستند واحد.

```csharp
public IMerger Join(string filePath, IImageJoinOptions joinOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف للوثيقة المدمجة. |
| joinOptions | IImageJoinOptions | خيارات دمج الصور. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *filePath* فارغًا أو خاليًا (null). |
| ArgumentNullException | يُرمى عندما تكون *joinOptions* فارغة (null). |

### ملاحظات

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### انظر أيضًا

* interface [IMerger](../../imerger)
* interface [IImageJoinOptions](../../../groupdocs.merger.domain.options/iimagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
