---
title: "FileType"
second_title: "مرجع API لـ GroupDocs.Merger لـ .NET"
description: "يمثل نوع الملف. يوفر طرقًا للحصول على قائمة بجميع أنواع الملفات المدعومة من قبل GroupDocs.Merger واكتشاف نوع الملف حسب الامتداد وما إلى ذلك."
type: docs
weight: 110
url: /ar/net/groupdocs.merger.domain/filetype/
---
## FileType class

يمثل نوع الملف. يوفر طرقًا للحصول على قائمة بجميع أنواع الملفات المدعومة من قبل **GroupDocs.Merger**، واكتشاف نوع الملف حسب الامتداد، إلخ.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | لاحقة اسم الملف (بما في ذلك النقطة ".") مثال: ".doc". |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | اسم نوع الملف مثال: "Microsoft Word Document". |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | يربط امتداد الملف بنوع الملف. |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | يحدد ما إذا كان [`FileType`](../filetype) الحالي هو نفسه ككائن [`FileType`](../filetype) المحدد. |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | يحدد ما إذا كان [`FileType`](../filetype) الحالي هو نفسه كالكائن المحدد. |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | يرجع قيمة التجزئة لكائن [`FileType`](../filetype) الحالي. |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | يرجع سلسلة تمثل الكائن الحالي. |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | يسترجع أنواع الملفات المدعومة |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | يحدد ما إذا كان [`FileType`](../filetype) المدخل هو تنسيق أرشيف. |
| static [IsAudio](../../groupdocs.merger.domain/filetype/isaudio)(FileType) | يحدد ما إذا كان [`FileType`](../filetype) المدخل هو تنسيق صوتي. |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | يحدد ما إذا كان [`FileType`](../filetype) المدخل هو تنسيق صورة. |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | يحدد ما إذا كان [`FileType`](../filetype) المدخل هو تنسيق نص بسيط. |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | يحدد ما إذا كان كائنان من نوع [`FileType`](../filetype) متطابقان. |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | يحدد ما إذا كان كائنان من نوع [`FileType`](../filetype) غير متطابقين. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [BMP](../../groupdocs.merger.domain/filetype/bmp) | ملف صورة نقطية (.bmp) يمثل الملفات المستخدمة لتخزين الصور الرقمية النقطية. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/image/bmp). |
| static readonly [BZ2](../../groupdocs.merger.domain/filetype/bz2) | ملف مضغوط Bzip2 (.bz2) |
| static readonly [CSV](../../groupdocs.merger.domain/filetype/csv) | ملف قيم مفصولة بفواصل (.csv) يمثل ملفات نصية عادية تحتوي على سجلات بيانات ذات قيم مفصولة بفواصل. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/spreadsheet/csv). |
| static readonly [DOC](../../groupdocs.merger.domain/filetype/doc) | مستند Microsoft Word (.doc) يمثل المستندات التي تم إنشاؤها بواسطة Microsoft Word أو برامج معالجة النصوص الأخرى بصيغة ملف ثنائي. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/word-processing/doc). |
| static readonly [DOCM](../../groupdocs.merger.domain/filetype/docm) | ملفات Word Open XML Macro-Enabled Document (.docm) هي مستندات تم إنشاؤها بواسطة Microsoft Word 2007 أو أحدث مع القدرة على تشغيل الماكرو. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/word-processing/docm). |
| static readonly [DOCX](../../groupdocs.merger.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) هو تنسيق معروف لمستندات Microsoft Word. تم تقديمه منذ عام 2007 مع إصدار Microsoft Office 2007، وتم تغيير بنية هذا التنسيق الجديد من ثنائي بسيط إلى مزيج من ملفات XML وملفات ثنائية. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/word-processing/docx). |
| static readonly [DOT](../../groupdocs.merger.domain/filetype/dot) | ملفات Word Document Template (.dot) هي ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة الصياغة لإنشاء ملفات DOC أو DOCX إضافية. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/word-processing/dot). |
| static readonly [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) يمثل ملف قالب تم إنشاؤه باستخدام Microsoft Word 2007 أو أحدث. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/word-processing/dotm). |
| static readonly [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Word Open XML Document Template (.dotx) هي ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة الصياغة لإنشاء ملفات DOCX إضافية. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/word-processing/dotx). |
| static readonly [EMF](../../groupdocs.merger.domain/filetype/emf) | ملف Windows Enhanced Metafile (.emf) |
| static readonly [EMZ](../../groupdocs.merger.domain/filetype/emz) | ملف Windows Compressed Enhanced Metafile (.emz) |
| static readonly [EPUB](../../groupdocs.merger.domain/filetype/epub) | ملف Open eBook (.epub) هو تنسيق ملف إلكتروني يوفر تنسيق نشر رقمي قياسي للناشرين والمستهلكين. أصبح هذا التنسيق شائعًا إلى حد أنه مدعوم من قبل العديد من القارئات الإلكترونية وتطبيقات البرمجيات. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/ebook/epub). |
| static readonly [ERR](../../groupdocs.merger.domain/filetype/err) | ملف سجل الأخطاء (.err) هو ملف نصي يحتوي على رسائل الأخطاء التي يولدها برنامج. تعرف على المزيد حول هذا التنسيق [هنا](https://fileinfo.com/extension/err). |
| static readonly [GIF](../../groupdocs.merger.domain/filetype/gif) | ملف Graphical Interchange Format (.gif) |
| static readonly [GZ](../../groupdocs.merger.domain/filetype/gz) | ملف G-Zip مضغوط (.gz) |
| static readonly [HTML](../../groupdocs.merger.domain/filetype/html) | ملف Hypertext Markup Language (.html) هو الامتداد لصفحات الويب التي تُنشأ للعرض في المتصفحات. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/web/html). |
| static readonly [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | صورة JPEG (.jpeg) هي نوع من تنسيقات الصور يتم حفظها باستخدام طريقة الضغط الفاقد. الصورة الناتجة، نتيجة الضغط، هي موازنة بين حجم التخزين وجودة الصورة. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/image/jpeg). |
| static readonly [JPG](../../groupdocs.merger.domain/filetype/jpg) | صورة JPEG (.jpg) |
| static readonly [MHT](../../groupdocs.merger.domain/filetype/mht) | MHTML Web Archive (.mht) هو تنسيق أرشيف صفحة ويب يمكن إنشاؤه بواسطة عدد من التطبيقات المختلفة. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/web/mhtml). |
| static readonly [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | ملف MIME HTML (.mhtml) هو تنسيق أرشيف صفحة ويب يمكن إنشاؤه بواسطة عدد من التطبيقات المختلفة. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/web/mhtml). |
| static readonly [MP3](../../groupdocs.merger.domain/filetype/mp3) | الملفات ذات امتداد .mp3 هي تنسيقات ملفات مشفرة رقمياً للملفات الصوتية تعتمد رسمياً على MPEG-1 Audio Layer III أو MPEG-2 Audio Layer III. تم تطويرها بواسطة مجموعة خبراء الصور المتحركة (MPEG) التي تستخدم ضغط الصوت من الطبقة 3. حجم الضغط الذي يحققه تنسيق MP3 هو عُشر حجم ملفات .WAV أو .AIF. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/audio/mp3). |
| static readonly [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument Presentation (.odp) يمثل تنسيق ملف عرض تقديمي يُستخدم بواسطة OpenOffice.org في معيار OASISOpen. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/presentation/odp). |
| static readonly [ODS](../../groupdocs.merger.domain/filetype/ods) | OpenDocument Spreadsheet (.ods) تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/spreadsheet/ods). |
| static readonly [ODT](../../groupdocs.merger.domain/filetype/odt) | ملفات OpenDocument Text Document (.odt) هي نوع من المستندات التي تُنشأ باستخدام تطبيقات معالجة النصوص وتعتمد على تنسيق OpenDocument Text File. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/word-processing/odt). |
| static readonly [ONE](../../groupdocs.merger.domain/filetype/one) | ملفات مستند OneNote (.one) تُنشأ بواسطة تطبيق Microsoft OneNote. يتيح لك OneNote جمع المعلومات باستخدام التطبيق كما لو كنت تستخدم دفتر ملاحظاتك لتدوين الملاحظات. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/note-taking/one). |
| static readonly [OTP](../../groupdocs.merger.domain/filetype/otp) | قالب عرض OpenDocument Presentation (.otp) يمثل ملفات قوالب العروض التي تُنشأ بواسطة التطبيقات وفق معيار OASIS OpenDocument. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/presentation/otp). |
| static readonly [OTT](../../groupdocs.merger.domain/filetype/ott) | قالب مستند OpenDocument Document (.ott) يمثل مستندات القوالب التي تُولّد بواسطة التطبيقات وفقًا لمعيار OASIS OpenDocument. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/word-processing/ott). |
| static readonly [PDF](../../groupdocs.merger.domain/filetype/pdf) | ملف تنسيق المستندات القابلة للنقل (.pdf) هو تنسيق ملف تم تقديمه كمعيار لتمثيل المستندات وغيرها من المواد المرجعية في تنسيق مستقل عن برامج التطبيقات والعتاد ونظام التشغيل. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/view/pdf). |
| static readonly [PNG](../../groupdocs.merger.domain/filetype/png) | ملف صورة شبكة محمولة (.png) هو نوع من تنسيقات ملفات الصور النقطية التي تستخدم ضغطًا غير فقدان للبيانات. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/image/png). |
| static readonly [POTM](../../groupdocs.merger.domain/filetype/potm) | قالب عرض PowerPoint Open XML مع تمكين الماكرو (.potm) |
| static readonly [POTX](../../groupdocs.merger.domain/filetype/potx) | قالب عرض PowerPoint Open XML (.potx) |
| static readonly [PPS](../../groupdocs.merger.domain/filetype/pps) | عرض شرائح PowerPoint (.pps) هو ملف يُنشأ باستخدام Microsoft PowerPoint لغرض عرض الشرائح. يدعم قراءة وإنشاء ملفات PPS بواسطة Microsoft PowerPoint 97-2003. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/presentation/pps). |
| static readonly [PPSM](../../groupdocs.merger.domain/filetype/ppsm) | شريحة PowerPoint Open XML مع تمكين الماكرو (.ppsm) |
| static readonly [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | عرض شرائح PowerPoint Open XML (.ppsx) هو ملف يُنشأ باستخدام Microsoft PowerPoint 2007 وما فوق لغرض عرض الشرائح. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/presentation/ppsx). |
| static readonly [PPT](../../groupdocs.merger.domain/filetype/ppt) | عرض PowerPoint (.ppt) يمثل ملف PowerPoint يتكون من مجموعة من الشرائح للعرض كعرض شرائح. يحدد تنسيق الملف الثنائي المستخدم من قبل Microsoft PowerPoint 97-2003. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/presentation/ppt). |
| static readonly [PPTM](../../groupdocs.merger.domain/filetype/pptm) | عرض PowerPoint Open XML مع تمكين الماكرو |
| static readonly [PPTX](../../groupdocs.merger.domain/filetype/pptx) | عرض PowerPoint Open XML (.pptx) هو ملف عرض تم إنشاؤه باستخدام تطبيق Microsoft PowerPoint الشهير. على عكس النسخة السابقة من تنسيق ملف العرض PPT الذي كان ثنائيًا، يعتمد تنسيق PPTX على تنسيق عرض PowerPoint المفتوح XML. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/presentation/pptx). |
| static readonly [PS](../../groupdocs.merger.domain/filetype/ps) | ملف PostScript (.ps) |
| static readonly [RAR](../../groupdocs.merger.domain/filetype/rar) | ملف أرشيف Roshal المضغوط (.rar) |
| static readonly [RTF](../../groupdocs.merger.domain/filetype/rtf) | ملف تنسيق النص الغني (.rtf) تم تقديمه وتوثيقه من قبل Microsoft، يمثل تنسيق النص الغني (RTF) طريقة لتشفير النص المنسق والرسومات للاستخدام داخل التطبيقات. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/word-processing/rtf). |
| static readonly [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | ملف مضغوط 7-Zip (.7z) |
| static readonly [SVG](../../groupdocs.merger.domain/filetype/svg) | ملف رسومات متجهية قابلة للتوسع (.svg) |
| static readonly [SVGZ](../../groupdocs.merger.domain/filetype/svgz) | ملف رسومات متجهية قابلة للتوسع مضغوط (.svgz) |
| static readonly [TAR](../../groupdocs.merger.domain/filetype/tar) | أرشيف ملفات Unix الموحد (.tar) |
| static readonly [TEX](../../groupdocs.merger.domain/filetype/tex) | مستند مصدر LaTeX (.tex) هو لغة تشمل البرمجة وكذلك ميزات الترميز، تُستخدم لتنسيق المستندات. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/page-description-language/tex). |
| static readonly [TIF](../../groupdocs.merger.domain/filetype/tif) | ملف صورة مُوسومة (.tif) |
| static readonly [TIFF](../../groupdocs.merger.domain/filetype/tiff) | تنسيق ملف صورة مُوسومة (.tiff) |
| static readonly [TSV](../../groupdocs.merger.domain/filetype/tsv) | ملف قيم مفصولة بفواصل جدولة (.tsv) يمثل بيانات مفصولة بفواصل جدولة في تنسيق نص عادي. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/spreadsheet/tsv). |
| static readonly [TXT](../../groupdocs.merger.domain/filetype/txt) | ملف نص عادي (.txt) يمثل مستند نص يحتوي على نص عادي على شكل أسطر. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/word-processing/txt). |
| static readonly [Unknown](../../groupdocs.merger.domain/filetype/unknown) | يمثل نوع ملف غير معروف. |
| static readonly [VDX](../../groupdocs.merger.domain/filetype/vdx) | ملف Visio Drawing XML (.vdx) هو رسم أو مخطط تم إنشاؤه في Microsoft Visio، لكنه محفوظ بتنسيق XML بامتداد .VDX. يتم إنشاء ملف Visio drawing XML في برنامج Visio الذي تطوره Microsoft. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/image/vdx). |
| static readonly [VSD](../../groupdocs.merger.domain/filetype/vsd) | ملف Visio Drawing (.vsd) |
| static readonly [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | ملف Visio Macro-Enabled Drawing (.vsdm) هو ملفات رسم تم إنشاؤها باستخدام تطبيق Microsoft Visio الذي يدعم الماكرو. ملفات VSDM هي رسومات OPC/XML مشابهة لملفات VSDX، لكنها توفر أيضًا القدرة على تشغيل الماكرو عند فتح الملف. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/image/vsdm). |
| static readonly [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | يمثل Visio Drawing (.vsdx) تنسيق ملفات Microsoft Visio الذي تم تقديمه بدءًا من Microsoft Office 2013 فصاعدًا. تم تطويره لاستبدال تنسيق الملف الثنائي .VSD، الذي كان مدعومًا في الإصدارات السابقة من Microsoft Visio. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/image/vsdx). |
| static readonly [VSS](../../groupdocs.merger.domain/filetype/vss) | ملف Visio Stencil (.vss) |
| static readonly [VSSM](../../groupdocs.merger.domain/filetype/vssm) | ملف Visio Macro-Enabled Stencil (.vssm) هو ملفات Stencil من Microsoft Visio تدعم الماكرو. عند فتح ملف VSSM يسمح بتشغيل الماكرو لتحقيق التنسيق المطلوب ووضع الأشكال في المخطط. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/image/vssm). |
| static readonly [VSSX](../../groupdocs.merger.domain/filetype/vssx) | ملف Visio Stencil (.vssx) هو قوالب رسم تم إنشاؤها باستخدام Microsoft Visio 2013 وما بعده. يمكن فتح تنسيق ملف VSSX باستخدام Visio 2013 وما بعده. تُعرف ملفات Visio بتمثيل مجموعة متنوعة من عناصر الرسم مثل مجموعة الأشكال، الموصلات، المخططات الانسيابية، تخطيط الشبكات، مخططات UML. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/image/vssx). |
| static readonly [VST](../../groupdocs.merger.domain/filetype/vst) | قالب Visio Drawing (.vst) |
| static readonly [VSTM](../../groupdocs.merger.domain/filetype/vstm) | قالب Visio Macro-Enabled Drawing (.vstm) هو ملفات قالب تم إنشاؤها باستخدام Microsoft Visio وتدعم الماكرو. على عكس ملفات VSDX، يمكن للملفات التي تم إنشاؤها من قوالب VSTM تشغيل الماكرو المطور بلغة Visual Basic for Applications (VBA). تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/image/vstm). |
| static readonly [VSTX](../../groupdocs.merger.domain/filetype/vstx) | قالب Visio Drawing (.vstx) هو ملفات قالب رسم تم إنشاؤها باستخدام Microsoft Visio 2013 وما بعده. توفر ملفات VSTX نقطة انطلاق لإنشاء رسومات Visio، تُحفظ كملفات .VSDX، مع التخطيط والإعدادات الافتراضية. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/image/vstx). |
| static readonly [VSX](../../groupdocs.merger.domain/filetype/vsx) | ملف Visio Stencil XML (.vsx) يشير إلى القوالب التي تتكون من رسومات وأشكال تُستخدم لإنشاء مخططات في Microsoft Visio. تُحفظ ملفات VSX بتنسيق XML وكان يُدعم حتى Visio 2013. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/image/vsx). |
| static readonly [VTX](../../groupdocs.merger.domain/filetype/vtx) | ملف Visio Template XML (.vtx) هو قالب رسم Microsoft Visio يُحفظ على القرص بتنسيق XML. يهدف القالب إلى توفير ملف بإعدادات أساسية يمكن استخدامها لإنشاء ملفات Visio متعددة بنفس الإعدادات. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/image/vtx). |
| static readonly [WAV](../../groupdocs.merger.domain/filetype/wav) | WAV، المعروف بـ WAVE (Waveform Audio File Format)، هو مجموعة فرعية من مواصفة تنسيق ملف تبادل الموارد (RIFF) من Microsoft لتخزين ملفات الصوت الرقمية. لا يطبق هذا التنسيق أي ضغط على تدفق البتات ويخزن التسجيلات الصوتية بمعدلات عينة ومعدلات بت مختلفة. كان ولا يزال أحد التنسيقات القياسية لأقراص الصوت CD. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/audio/wav). |
| static readonly [XLAM](../../groupdocs.merger.domain/filetype/xlam) | إضافة Excel Macro-Enabled (.xlam) |
| static readonly [XLS](../../groupdocs.merger.domain/filetype/xls) | ملف Excel Spreadsheet (.xls) هو ملف يمكن إنشاؤه بواسطة Microsoft Excel وكذلك برامج جداول البيانات المشابهة مثل OpenOffice Calc أو Apple Numbers. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/spreadsheet/xls). |
| static readonly [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | تنسيق ملف Excel Binary Spreadsheet (.xlsb) يحدد تنسيق ملف Excel الثنائي، وهو مجموعة من السجلات والهياكل التي تحدد محتوى دفتر عمل Excel. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/spreadsheet/xlsb). |
| static readonly [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) هو نوع من ملفات جداول البيانات التي تدعم الماكرو. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/spreadsheet/xlsm). |
| static readonly [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) هو تنسيق معروف لمستندات Microsoft Excel تم تقديمه من قبل Microsoft مع إصدار Microsoft Office 2007. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/spreadsheet/xlsx). |
| static readonly [XLT](../../groupdocs.merger.domain/filetype/xlt) | Excel Template File (.xlt) هي ملفات قالب تم إنشاؤها باستخدام Microsoft Excel وهو تطبيق جداول بيانات يأتي كجزء من مجموعة Microsoft Office. دعم Microsoft Office 97-2003 إنشاء ملفات XLT جديدة وكذلك فتحها. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/spreadsheet/xlt). |
| static readonly [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) يمثل ملفات يتم إنشاؤها بواسطة Microsoft Excel كقوالب مُمكّنة للماكرو. ملفات XLTM مشابهة لملفات XLTX في البنية باستثناء أن الأخيرة لا تدعم إنشاء قوالب مع ماكرو. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/spreadsheet/xltm). |
| static readonly [XLTX](../../groupdocs.merger.domain/filetype/xltx) | Excel Open XML Spreadsheet Template (.xltx) هي ملفات تعتمد على مواصفات تنسيق ملفات Office OpenXML. تُستخدم لإنشاء ملف قالب قياسي يمكن الاستفادة منه لتوليد ملفات XLSX التي تتضمن نفس الإعدادات المحددة في ملف XLTX. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/spreadsheet/xltx). |
| static readonly [XPS](../../groupdocs.merger.domain/filetype/xps) | XML Paper Specification File (.xps) يمثل ملفات تخطيط الصفحات التي تعتمد على مواصفات XML Paper التي أنشأتها Microsoft. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/page-description-language/xps). |
| static readonly [ZIP](../../groupdocs.merger.domain/filetype/zip) | ملف مضغوط (.zip) |

### ملاحظات

**Learn more**

* Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* Learn more about getting supported file types in code: [How to get supported file formats in code](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### انظر أيضًا

* namespace [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* assembly [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
