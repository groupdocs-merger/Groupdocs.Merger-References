---
title: FileType
second_title: GroupDocs.Merger لمرجع .NET API
description: يمثل نوع الملف. يوفر طرقًا للحصول على قائمة بجميع أنواع الملفات التي يدعمهاGroupDocs.Merger  كشف نوع الملف بالامتداد وما إلى ذلك.
type: docs
weight: 100
url: /ar/net/groupdocs.merger.domain/filetype/
---
## FileType class

يمثل نوع الملف. يوفر طرقًا للحصول على قائمة بجميع أنواع الملفات التي يدعمها**GroupDocs.Merger** ، كشف نوع الملف بالامتداد وما إلى ذلك.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | لاحقة اسم الملف (بما في ذلك النقطة ".") مثل ".doc" . |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | اسم نوع الملف ، مثل "مستند Microsoft Word". |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | امتداد ملف الخرائط لنوع الملف. |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | يحدد ما إذا كان التيار[`FileType`](../filetype) هو نفسه كما هو محدد[`FileType`](../filetype) الكائن . |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | يحدد ما إذا كان التيار[`FileType`](../filetype) هو نفس الكائن المحدد. |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | إرجاع كود التجزئة الحالي[`FileType`](../filetype) الكائن . |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | إرجاع سلسلة تمثل الكائن الحالي. |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | استرداد أنواع الملفات المدعومة |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | تحديد ما إذا كان الإدخال[`FileType`](../filetype) هو تنسيق أرشيف . |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | تحديد ما إذا كان الإدخال[`FileType`](../filetype) هو تنسيق الصورة . |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | تحديد ما إذا كان الإدخال[`FileType`](../filetype) هو تنسيق نص بدائي. |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | تحديد ما إذا كان اثنان[`FileType`](../filetype) الكائنات هي نفسها. |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | تحديد ما إذا كان اثنان[`FileType`](../filetype) الكائنات ليست هي نفسها. |

## مجالات

| اسم | وصف |
| --- | --- |
| static [BMP](../../groupdocs.merger.domain/filetype/bmp) | يمثل ملف الصور النقطية (.bmp) الملفات التي تُستخدم لتخزين الصور الرقمية النقطية. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/image/bmp) . |
| static [BZ2](../../groupdocs.merger.domain/filetype/bz2) | ملف مضغوط Bzip2 (.bz2) |
| static [CSV](../../groupdocs.merger.domain/filetype/csv) | يمثل ملف القيم المفصولة بفواصل (.csv) ملفات نصية عادية تحتوي على سجلات بيانات بقيم مفصولة بفواصل . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/spreadsheet/csv) . |
| static [DOC](../../groupdocs.merger.domain/filetype/doc) | يمثل مستند Microsoft Word (.doc) المستندات التي تم إنشاؤها بواسطة Microsoft Word أو مستندات معالجة النصوص الأخرى بتنسيق ملف ثنائي. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/word-processing/doc) . |
| static [DOCM](../../groupdocs.merger.domain/filetype/docm) | ملفات مستند Word Open XML الممكنة بماكرو (.docm) هي مستندات تم إنشاؤها بواسطة Microsoft Word 2007 أو أحدث مع إمكانية تشغيل وحدات الماكرو . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/word-processing/docm) . |
| static [DOCX](../../groupdocs.merger.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) هو تنسيق معروف لمستندات Microsoft Word. تم تقديمه من عام 2007 مع إصدار Microsoft Office 2007 ، تم تغيير هيكل تنسيق المستند الجديد هذا من ثنائي عادي إلى مجموعة من ملفات XML والملفات الثنائية. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/word-processing/docx) . |
| static [DOT](../../groupdocs.merger.domain/filetype/dot) | ملفات Word Document Template (.dot) هي ملفات قوالب تم إنشاؤها بواسطة Microsoft Word للحصول على إعدادات مهيأة مسبقًا لإنشاء المزيد من ملفات DOC أو DOCX. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/word-processing/dot) . |
| static [DOTM](../../groupdocs.merger.domain/filetype/dotm) | قالب مستند Word Open XML ممكّن بماكرو (.dotm) يمثل ملف قالب تم إنشاؤه باستخدام Microsoft Word 2007 أو أعلى . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/word-processing/dotm) . |
| static [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Word Open XML Document Template (.dotx) عبارة عن ملفات قوالب تم إنشاؤها بواسطة Microsoft Word للحصول على إعدادات منسقة مسبقًا لإنشاء ملفات DOCX أخرى. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/word-processing/dotx) . |
| static [EPUB](../../groupdocs.merger.domain/filetype/epub) | ملف الكتاب الإلكتروني المفتوح (.epub) هو تنسيق ملف كتاب إلكتروني يوفر تنسيقًا قياسيًا للنشر الرقمي للناشرين والمستهلكين. أصبح التنسيق شائعًا جدًا حتى الآن لدرجة أنه مدعوم من قبل العديد من برامج القراءة الإلكترونية وتطبيقات البرامج . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/ebook/epub) . |
| static [ERR](../../groupdocs.merger.domain/filetype/err) | ملف سجل الأخطاء (.err) هو ملف نصي يحتوي على رسائل خطأ تم إنشاؤها بواسطة أحد البرامج. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://fileinfo.com/extension/err) . |
| static [GIF](../../groupdocs.merger.domain/filetype/gif) | ملف تنسيق التبادل الرسومي (.gif) |
| static [GZ](../../groupdocs.merger.domain/filetype/gz) | ملف مضغوط G-Zip (.gz) |
| static [HTML](../../groupdocs.merger.domain/filetype/html) | ملف لغة توصيف النص التشعبي (.html) هو امتداد لصفحات الويب التي تم إنشاؤها للعرض في المستعرضات. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/web/html) . |
| static [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | صورة JPEG (.jpeg) هي نوع من تنسيق الصورة يتم حفظها باستخدام طريقة الضغط مع فقدان البيانات. الصورة الناتجة ، كنتيجة للضغط ، هي مقايضة بين حجم التخزين وجودة الصورة . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/image/jpeg) . |
| static [JPG](../../groupdocs.merger.domain/filetype/jpg) | صورة JPEG (.jpg) |
| static [MHT](../../groupdocs.merger.domain/filetype/mht) | أرشيف الويب MHTML (.mht) هو تنسيق أرشيف لصفحة الويب يمكن إنشاؤه بواسطة عدد من التطبيقات المختلفة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/web/mhtml) . |
| static [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | ملف MIME HTML (.mhtml) هو تنسيق أرشيف لصفحة الويب يمكن إنشاؤه بواسطة عدد من التطبيقات المختلفة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/web/mhtml) . |
| static [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument Presentation (.odp) يمثل تنسيق ملف العرض التقديمي المستخدم بواسطة OpenOffice.org في معيار OASISOpen . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/presentation/odp) . |
| static [ODS](../../groupdocs.merger.domain/filetype/ods) | جدول بيانات OpenDocument (.ods) تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/spreadsheet/ods) . |
| static [ODT](../../groupdocs.merger.domain/filetype/odt) | ملفات OpenDocument Text Document (.odt) هي نوع من المستندات التي تم إنشاؤها باستخدام تطبيقات معالجة الكلمات التي تستند إلى تنسيق OpenDocument Text File. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/word-processing/odt) . |
| static [ONE](../../groupdocs.merger.domain/filetype/one) | يتم إنشاء ملفات OneNote Document (.one) بواسطة تطبيق Microsoft OneNote. يتيح لك OneNote جمع المعلومات باستخدام التطبيق كما لو كنت تستخدم لوحة المسودة لتدوين الملاحظات . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/note-taking/one) . |
| static [OTP](../../groupdocs.merger.domain/filetype/otp) | قالب العرض التقديمي OpenDocument (.otp) يمثل ملفات قالب العرض التقديمي التي تم إنشاؤها بواسطة تطبيقات بتنسيق OASIS OpenDocument القياسي . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/presentation/otp) . |
| static [OTT](../../groupdocs.merger.domain/filetype/ott) | قالب مستند OpenDocument (.ott) يمثل مستندات النموذج التي تم إنشاؤها بواسطة التطبيقات وفقًا للتنسيق القياسي OpenDocument الخاص بـ OASIS. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/word-processing/ott) . |
| static [PDF](../../groupdocs.merger.domain/filetype/pdf) | ملف تنسيق المستند المحمول (.pdf) هو تنسيق ملف تم تقديمه كمعيار لتمثيل المستندات والمواد المرجعية الأخرى بتنسيق مستقل عن البرامج التطبيقية والأجهزة وكذلك نظام التشغيل. تعرف على المزيد حول هذا الملف شكل[هنا](https://docs.fileformat.com/view/pdf) . |
| static [PNG](../../groupdocs.merger.domain/filetype/png) | Portable Network Graphic (.png) هو نوع من تنسيق ملف الصورة النقطية الذي يستخدم ضغط بدون فقدان . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/image/png) . |
| static [PPS](../../groupdocs.merger.domain/filetype/pps) | PowerPoint Slide Show (.pps) هو ملف تم إنشاؤه باستخدام Microsoft PowerPoint لغرض عرض الشرائح. يتم دعم قراءة ملف PPS وإنشائه بواسطة Microsoft PowerPoint 97-2003. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/presentation/pps) . |
| static [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | PowerPoint Open XML Slide Show (.ppsx) هو ملف تم إنشاؤه باستخدام Microsoft PowerPoint 2007 والإصدارات الأحدث لغرض عرض الشرائح . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/presentation/ppsx) . |
| static [PPT](../../groupdocs.merger.domain/filetype/ppt) | PowerPoint Presentation (.ppt) يمثل ملف PowerPoint يتكون من مجموعة من الشرائح لعرضها على هيئة SlideShow. تحدد تنسيق الملف الثنائي المستخدم بواسطة Microsoft PowerPoint 97-2003. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/presentation/ppt) . |
| static [PPTX](../../groupdocs.merger.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) هو ملف عرض تقديمي تم إنشاؤه باستخدام تطبيق Microsoft PowerPoint الشهير. على عكس الإصدار السابق من تنسيق ملف العرض التقديمي PPT الذي كان ثنائيًا ، يعتمد تنسيق PPTX على تنسيق ملف العرض التقديمي XML المفتوح لبرنامج Microsoft PowerPoint. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/presentation/pptx) . |
| static [PS](../../groupdocs.merger.domain/filetype/ps) | ملف PostScript (.ps) |
| static [RAR](../../groupdocs.merger.domain/filetype/rar) | ملف مضغوط Roshal ARchive (.rar) |
| static [RTF](../../groupdocs.merger.domain/filetype/rtf) | ملف Rich Text Format (.rtf) الذي تم تقديمه وتوثيقه بواسطة Microsoft ، يمثل Rich Text Format (RTF) طريقة لترميز النص والرسومات المنسقة للاستخدام داخل التطبيقات. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/word-processing/rtf) . |
| static [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | ملف مضغوط 7-Zip (.7z) |
| static [TAR](../../groupdocs.merger.domain/filetype/tar) | أرشيف ملفات Unix الموحدة (.tar) |
| static [TEX](../../groupdocs.merger.domain/filetype/tex) | وثيقة مصدر LaTeX (.tex) هي لغة تتكون من ميزات البرمجة والترميز المستخدمة في طباعة المستندات. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/page-description-language/tex) . |
| static [TIF](../../groupdocs.merger.domain/filetype/tif) | ملف الصور الموسومة (.tif) |
| static [TIFF](../../groupdocs.merger.domain/filetype/tiff) | تنسيق ملف الصورة الموسوم (.tiff) |
| static [TSV](../../groupdocs.merger.domain/filetype/tsv) | يمثل ملف القيم المفصولة بعلامات جدولة (.tsv) بيانات مفصولة بعلامات تبويب بتنسيق نص عادي. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/spreadsheet/tsv) . |
| static [TXT](../../groupdocs.merger.domain/filetype/txt) | ملف نصي عادي (.txt) يمثل مستندًا نصيًا يحتوي على نص عادي في شكل أسطر. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/word-processing/txt) . |
| static [Unknown](../../groupdocs.merger.domain/filetype/unknown) | يمثل نوع ملف غير معروف. |
| static [VDX](../../groupdocs.merger.domain/filetype/vdx) | ملف Visio Drawing XML (.vdx) هو رسم أو مخطط تم إنشاؤه في Microsoft Visio ، ولكن تم حفظه بتنسيق XML بامتداد .VDX. يتم إنشاء ملف Visio للرسم XML في برنامج Visio ، الذي تم تطويره بواسطة Microsoft . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/image/vdx) . |
| static [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | رسم Visio ممكّن بماكرو (.vsdm) عبارة عن ملفات رسم تم إنشاؤها باستخدام تطبيق Microsoft Visio الذي يدعم وحدات الماكرو. ملفات VSDM هي رسومات OPC / XML تشبه VSDX ، ولكنها توفر أيضًا القدرة على تشغيل وحدات الماكرو عند فتح الملف. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/image/vsdm) . |
| static [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | يمثل Visio Drawing (.vsdx) تنسيق ملف Microsoft Visio المقدم من Microsoft Office 2013 وما بعده. تم تطويره ليحل محل تنسيق الملف الثنائي ، .VSD ، الذي تدعمه الإصدارات السابقة من Microsoft Visio . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/image/vsdx) . |
| static [VSSM](../../groupdocs.merger.domain/filetype/vssm) | ملف الاستنسل الممكّن بماكرو Visio (.vssm) هي ملفات Microsoft Visio Stencil التي تدعم توفير الدعم لوحدات الماكرو. يسمح ملف VSSM عند فتحه بتشغيل وحدات الماكرو لتحقيق التنسيق المطلوب ووضع الأشكال في رسم تخطيطي . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/image/vssm) . |
| static [VSSX](../../groupdocs.merger.domain/filetype/vssx) | ملف استنسل Visio (.vssx) يرسم قوالب استنسل تم إنشاؤها باستخدام Microsoft Visio 2013 وما بعده. يمكن فتح تنسيق ملف VSSX باستخدام Visio 2013 وما فوق. تُعرف ملفات Visio بتمثيل مجموعة متنوعة من عناصر الرسم مثل مجموعة الأشكال والموصلات والمخططات الانسيابية وتخطيط الشبكة ومخططات UML و تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/image/vssx) . |
| static [VSTM](../../groupdocs.merger.domain/filetype/vstm) | قالب الرسم الممكّن بماكرو Visio (.vstm) عبارة عن ملفات قوالب تم إنشاؤها باستخدام Microsoft Visio التي تدعم وحدات الماكرو. بخلاف ملفات VSDX ، يمكن للملفات التي تم إنشاؤها من قوالب VSTM تشغيل وحدات الماكرو التي تم تطويرها في التعليمات البرمجية لـ Visual Basic for Applications (VBA). تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/image/vstm) . |
| static [VSTX](../../groupdocs.merger.domain/filetype/vstx) | قالب رسم Visio (.vstx) عبارة عن ملفات قالب رسم تم إنشاؤها باستخدام Microsoft Visio 2013 وما بعده. توفر ملفات VSTX هذه نقطة بداية لإنشاء رسومات Visio ، المحفوظة كملفات .VSDX ، مع التخطيط والإعدادات الافتراضية. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/image/vstx) . |
| static [VSX](../../groupdocs.merger.domain/filetype/vsx) | يشير ملف Visio Stencil XML (.vsx) إلى قوالب استنسل تتكون من رسومات وأشكال تُستخدم لإنشاء الرسوم التخطيطية في Microsoft Visio. يتم حفظ ملفات VSX بتنسيق ملف XML وتم دعمها حتى Visio 2013. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/image/vsx) . |
| static [VTX](../../groupdocs.merger.domain/filetype/vtx) | Visio Template XML File (.vtx) هو قالب رسم Microsoft Visio يتم حفظه على قرص بتنسيق ملف XML. يهدف القالب إلى توفير ملف بالإعدادات الأساسية التي يمكن استخدامها لإنشاء ملفات Visio متعددة بنفس الإعدادات . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/image/vtx) . |
| static [XLAM](../../groupdocs.merger.domain/filetype/xlam) | الوظيفة الإضافية الممكنة بماكرو في Excel (.xlam) |
| static [XLS](../../groupdocs.merger.domain/filetype/xls) | Excel Spreadsheet (.xls) هو ملف يمكن إنشاؤه بواسطة Microsoft Excel بالإضافة إلى برامج جداول البيانات المماثلة الأخرى مثل OpenOffice Calc أو Apple Numbers. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/spreadsheet/xls) . |
| static [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | يحدد تنسيق ملف Excel Binary Spreadsheet (.xlsb) تنسيق ملف Excel الثنائي ، وهو عبارة عن مجموعة من السجلات والهياكل التي تحدد محتوى مصنف Excel. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/spreadsheet/xlsb) . |
| static [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) هو نوع من ملفات Spreasheet التي تدعم وحدات الماكرو . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/spreadsheet/xlsm) . |
| static [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) هو تنسيق معروف لمستندات Microsoft Excel تم تقديمه بواسطة Microsoft مع إصدار Microsoft Office 2007. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/spreadsheet/xlsx) . |
| static [XLT](../../groupdocs.merger.domain/filetype/xlt) | ملف قالب Excel (.xlt) عبارة عن ملفات قوالب تم إنشاؤها باستخدام Microsoft Excel وهو تطبيق جداول بيانات يأتي كجزء من مجموعة Microsoft Office. دعم Microsoft Office 97-2003 إنشاء ملفات XLT جديدة بالإضافة إلى فتحها. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/spreadsheet/xlt) . |
| static [XLTM](../../groupdocs.merger.domain/filetype/xltm) | يمثل قالب جدول البيانات الممكّن بماكرو XML المفتوح (xltm.) الملفات التي تم إنشاؤها بواسطة Microsoft Excel كملفات قوالب ممكّنة بماكرو. تتشابه ملفات XLTM مع XLTX من حيث البنية بخلاف أن أحدثها لا يدعم إنشاء ملفات القوالب باستخدام وحدات الماكرو. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/spreadsheet/xltm) . |
| static [XLTX](../../groupdocs.merger.domain/filetype/xltx) | ملفات Excel Open XML Spreadsheet Template (xltx) تستند إلى مواصفات تنسيق ملف Office OpenXML. يتم استخدامه لإنشاء ملف قالب قياسي يمكن استخدامه لإنشاء ملفات XLSX التي تعرض نفس الإعدادات المحددة في ملف XLTX . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/spreadsheet/xltx) . |
| static [XPS](../../groupdocs.merger.domain/filetype/xps) | ملف مواصفات ورق XML (.xps) يمثل ملفات تخطيط الصفحة التي تستند إلى مواصفات ورق XML التي أنشأتها Microsoft . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/page-description-language/xps) . |
| static [ZIP](../../groupdocs.merger.domain/filetype/zip) | ملف مضغوط (.zip) |

### ملاحظات

**يتعلم أكثر**

* تعرف على المزيد حول تنسيقات الملفات التي يدعمها GroupDocs.Merger: [قائمة كاملة بتنسيقات المستندات المدعومة](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* تعرف على المزيد حول الحصول على أنواع الملفات المدعومة في التعليمات البرمجية: [كيفية الحصول على تنسيقات الملفات المدعومة في التعليمات البرمجية](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### أنظر أيضا

* مساحة الاسم [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* المجسم [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
