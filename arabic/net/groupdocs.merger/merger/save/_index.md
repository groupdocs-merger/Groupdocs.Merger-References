---
title: Save
second_title: GroupDocs.Merger لمرجع .NET API
description: يحفظ المستند الناتج في الدفقdocument .
type: docs
weight: 150
url: /ar/net/groupdocs.merger/merger/save/
---
## Save(Stream) {#save}

يحفظ المستند الناتج في الدفق*document* .

```csharp
public void Save(Stream document)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| document | Stream | دفق الوثيقة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*document* باطل. |

### أنظر أيضا

* class [Merger](../../merger)
* مساحة الاسم [GroupDocs.Merger](../../merger)
* المجسم [GroupDocs.Merger](../../../)

---

## Save(string) {#save_1}

يحفظ ملف المستند الناتج في*filePath* .

```csharp
public void Save(string filePath)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | اسم الملف أو مسار الملف الكامل. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*filePath* فارغ أو فارغ. |

### أنظر أيضا

* class [Merger](../../merger)
* مساحة الاسم [GroupDocs.Merger](../../merger)
* المجسم [GroupDocs.Merger](../../../)

---

## Save(string, bool) {#save_2}

يحفظ ملف المستند الناتج في*filePath* .

```csharp
public void Save(string filePath, bool useDefaultDirectory)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف أو الاسم في حالة استخدام الدليل الافتراضي. |
| useDefaultDirectory | Boolean | استخدم الدليل الافتراضي من الإعدادات. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*filePath* فارغ أو فارغ. |

### أنظر أيضا

* class [Merger](../../merger)
* مساحة الاسم [GroupDocs.Merger](../../merger)
* المجسم [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->