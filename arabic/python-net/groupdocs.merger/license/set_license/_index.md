---
title: "set_license طريقة"
second_title: "مراجع API لـ GroupDocs.Merger للبايثون عبر .NET"
description: 
type: docs
url: /ar/python-net/groupdocs.merger/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

تطبيق ترخيص على العملية الحالية.

```python
def set_license(self, license_source):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| license_source |  | إما مسار سلسلة إلى ملف ``.lic`` أو كائن شبيه بالملف قابل للقراءة يُنتج بايتات الترخيص. يتم كتابة المدخلات الشبيهة بالملف إلى ملف مؤقت قبل تمريره إلى الجسر. |

| يثير | الوصف |
| :- | :- |
| `TypeError` | إذا كان ``license_source`` ليس مسارًا نصيًا ولا كائنًا ملفًا قابلًا للقراءة. |

### انظر أيضًا
* class [`License`](/merger/python-net/groupdocs.merger/license/)
