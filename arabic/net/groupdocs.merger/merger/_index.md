---
title: "الدمج"
second_title: "مرجع API لـ GroupDocs.Merger لـ .NET"
description: "يمثل الفئة الرئيسية التي تتحكم في عملية دمج المستندات."
type: docs
weight: 960
url: /ar/net/groupdocs.merger/merger/
---
## Merger class

يمثل الفئة الرئيسية التي تتحكم في عملية دمج المستندات.

```csharp
public class Merger : IDisposable, IMerger
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Merger](merger#constructor)(Func&lt;Stream&gt;) | يُهيئ نسخة جديدة من الفئة [`Merger`](../merger). |
| [Merger](merger#constructor_4)(Stream) | يُهيئ نسخة جديدة من الفئة [`Merger`](../merger). |
| [Merger](merger#constructor_8)(string) | يُهيئ نسخة جديدة من الفئة [`Merger`](../merger). |
| [Merger](merger#constructor_1)(Func&lt;Stream&gt;, ILoadOptions) | يُهيئ نسخة جديدة من الفئة [`Merger`](../merger). |
| [Merger](merger#constructor_3)(Func&lt;Stream&gt;, MergerSettings) | يُهيئ نسخة جديدة من الفئة [`Merger`](../merger). |
| [Merger](merger#constructor_5)(Stream, ILoadOptions) | يُهيئ نسخة جديدة من الفئة [`Merger`](../merger). |
| [Merger](merger#constructor_7)(Stream, MergerSettings) | يُهيئ نسخة جديدة من الفئة [`Merger`](../merger). |
| [Merger](merger#constructor_9)(string, ILoadOptions) | يُهيئ نسخة جديدة من الفئة [`Merger`](../merger). |
| [Merger](merger#constructor_11)(string, MergerSettings) | يُهيئ نسخة جديدة من الفئة [`Merger`](../merger). |
| [Merger](merger#constructor_2)(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) | يُهيئ نسخة جديدة من الفئة [`Merger`](../merger). |
| [Merger](merger#constructor_6)(Stream, ILoadOptions, MergerSettings) | يُهيئ نسخة جديدة من الفئة [`Merger`](../merger). |
| [Merger](merger#constructor_10)(string, ILoadOptions, MergerSettings) | يُهيئ نسخة جديدة من الفئة [`Merger`](../merger). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPassword](../../groupdocs.merger/merger/addpassword)(IAddPasswordOptions) | يحمي المستند بكلمة مرور. |
| [ApplyPageBuilder](../../groupdocs.merger/merger/applypagebuilder)(PageBuilder) | يطبق تغييرات مُنشئ الصفحات. |
| [ChangeOrientation](../../groupdocs.merger/merger/changeorientation)(IOrientationOptions) | يطبق وضع توجيه جديد للصفحات المحددة. |
| [CreatePageBuilder](../../groupdocs.merger/merger/createpagebuilder)(PageBuilderOptions) | ينشئ مُنشئ صفحات جديد مع مجموعة مستندات معرفة مسبقًا. |
| [Dispose](../../groupdocs.merger/merger/dispose)() | يحرّر الموارد. |
| [ExtractPages](../../groupdocs.merger/merger/extractpages)(IExtractOptions) | ينشئ مستندًا جديدًا يحتوي على بعض الصفحات من المستند المصدر. |
| [GeneratePreview](../../groupdocs.merger/merger/generatepreview)(IPreviewOptions) | يُولّد معاينة صفحات المستند. |
| [GetDocumentInfo](../../groupdocs.merger/merger/getdocumentinfo)() | يحصل على معلومات حول صفحات المستند: أحجامها، أقصى ارتفاع للصفحة، عرض الصفحة ذات أقصى ارتفاع. |
| [ImportDocument](../../groupdocs.merger/merger/importdocument)(IImportDocumentOptions) | يستورد المستند كمرفق أو مدمج عبر Ole. |
| [IsPasswordSet](../../groupdocs.merger/merger/ispasswordset)() | يتحقق مما إذا كان المستند محميًا بكلمة مرور. |
| [Join](../../groupdocs.merger/merger/join#join)(Stream) | يجمع المستندات في مستند واحد. |
| [Join](../../groupdocs.merger/merger/join#join_4)(string) | يجمع المستندات في مستند واحد. |
| [Join](../../groupdocs.merger/merger/join#join_1)(Stream, IImageJoinOptions) | يجمع المستندات في مستند واحد. |
| [Join](../../groupdocs.merger/merger/join#join_2)(Stream, IJoinOptions) | يجمع المستندات في مستند واحد. |
| [Join](../../groupdocs.merger/merger/join#join_3)(Stream, IPageJoinOptions) | يجمع المستندات في مستند واحد. |
| [Join](../../groupdocs.merger/merger/join#join_5)(string, IImageJoinOptions) | يجمع المستندات في مستند واحد. |
| [Join](../../groupdocs.merger/merger/join#join_6)(string, IJoinOptions) | يجمع المستندات في مستند واحد. |
| [Join](../../groupdocs.merger/merger/join#join_7)(string, IPageJoinOptions) | يجمع المستندات في مستند واحد. |
| [MovePage](../../groupdocs.merger/merger/movepage)(IMoveOptions) | ينقل الصفحة إلى موضع جديد داخل مستند بصيغة معروفة. |
| [RemovePages](../../groupdocs.merger/merger/removepages)(IRemoveOptions) | يزيل الصفحات من مستند بصيغة معروفة. |
| [RemovePassword](../../groupdocs.merger/merger/removepassword)() | يزيل كلمة المرور من المستند. |
| [Rotate](../../groupdocs.merger/merger/rotate)(IRotateOptions) | يدور الصورة أو صفحات المستند. |
| [Save](../../groupdocs.merger/merger/save#save)(Stream, ISaveOptions) | يحفظ المستند الناتج إلى التدفق *document*. |
| [Save](../../groupdocs.merger/merger/save#save_2)(string, ISaveOptions) | يحفظ ملف المستند الناتج إلى *filePath*. |
| [Save](../../groupdocs.merger/merger/save#save_1)(string, bool, ISaveOptions) | يحفظ ملف المستند الناتج إلى *filePath*. |
| [Split](../../groupdocs.merger/merger/split#split)(ISplitOptions) | يقسم المستند الواحد إلى مستندات متعددة. |
| [Split](../../groupdocs.merger/merger/split#split_1)(ITextSplitOptions) | يقسم المستند الواحد إلى مستندات متعددة. |
| [SwapPages](../../groupdocs.merger/merger/swappages)(ISwapOptions) | يقوم بتبديل صفحتين داخل مستند بتنسيق معروف. |
| [UpdatePassword](../../groupdocs.merger/merger/updatepassword)(IUpdatePasswordOptions) | يقوم بتحديث كلمة المرور الحالية للمستند. |

### انظر أيضًا

* interface [IMerger](../imerger)
* namespace [GroupDocs.Merger](../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
