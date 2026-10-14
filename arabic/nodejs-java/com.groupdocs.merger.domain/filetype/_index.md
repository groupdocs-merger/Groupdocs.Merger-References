---
title: "FileType"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "يمثل نوع الملف."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.merger.domain/filetype/
---
**Inheritance:**
java.lang.Object
```
public final class FileType
```

يمثل نوع الملف. يوفر طرقًا للحصول على قائمة بجميع أنواع الملفات المدعومة من قبل **GroupDocs.Merger**، واكتشاف نوع الملف بالامتداد وما إلى ذلك.

--------------------

**Learn more**

 *  Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats][]
 *  Learn more about getting supported file types in code: [How to get supported file formats in code][]


[Full list of supported document formats]: https://docs.groupdocs.com/display/mergernet/Supported+Document+Types
[How to get supported file formats in code]: https://docs.groupdocs.com/display/mergernet/Get+supported+file+types
## الحقول

| حقل | الوصف |
| --- | --- |
| [Unknown](#Unknown) | يمثل نوع ملف غير معروف. |
| [ZIP](#ZIP) | ملف مضغوط (.zip) |
| [SevenZ](#SevenZ) | ملف مضغوط 7-Zip (.7z) |
| [TAR](#TAR) | أرشيف ملف يونكس موحد (.tar) |
| [RAR](#RAR) | ملف مضغوط Roshal ARchive (.rar) |
| [VSSX](#VSSX) | ملف قوالب Visio (.vssx) هي قوالب رسومات تم إنشاؤها باستخدام Microsoft Visio 2013 وما فوق. |
| [VSDX](#VSDX) | رسمة Visio (.vsdx) تمثل تنسيق ملف Microsoft Visio الذي تم تقديمه منذ Microsoft Office 2013 فصاعدًا. |
| [VSDM](#VSDM) | رسمة Visio المدعومة بالماكرو (.vsdm) هي ملفات رسومات تم إنشاؤها باستخدام تطبيق Microsoft Visio الذي يدعم الماكرو. |
| [VSTX](#VSTX) | قالب رسمة Visio (.vstx) هي ملفات قالب رسومات تم إنشاؤها باستخدام Microsoft Visio 2013 وما فوق. |
| [VSTM](#VSTM) | قالب رسمة Visio المدعومة بالماكرو (.vstm) هي ملفات قالب تم إنشاؤها باستخدام Microsoft Visio الذي يدعم الماكرو. |
| [VSSM](#VSSM) | ملف قالب Visio المدعوم بالماكرو (.vssm) هو ملف قالب Microsoft Visio يوفر دعمًا للماكرو. |
| [VSX](#VSX) | ملف قالب Visio XML (.vsx) يشير إلى القوالب التي تتكون من رسومات وأشكال تُستخدم لإنشاء مخططات في Microsoft Visio. |
| [VTX](#VTX) | ملف قالب Visio XML (.vtx) هو قالب رسمة Microsoft Visio يتم حفظه على القرص بتنسيق ملف XML. |
| [VDX](#VDX) | ملف رسمة Visio XML (.vdx) هو رسمة أو مخطط تم إنشاؤه في Microsoft Visio، لكنه محفوظ بتنسيق XML وله امتداد .VDX. |
| [EPUB](#EPUB) | ملف كتاب إلكتروني مفتوح (.epub) هو تنسيق ملف كتاب إلكتروني يوفر تنسيق نشر رقمي قياسي للناشرين والمستهلكين. |
| [BMP](#BMP) | ملف صورة نقطية (.bmp) يمثل ملفات تُستخدم لتخزين الصور الرقمية النقطية. |
| [JPG](#JPG) | صورة JPEG (.jpg) |
| [JPEG](#JPEG) | صورة JPEG (.jpeg) هي نوع من تنسيقات الصور التي تُحفظ باستخدام طريقة الضغط الفاقد. |
| [PNG](#PNG) | صورة شبكة محمولة (.png) هي نوع من تنسيقات ملفات الصور النقطية التي تستخدم ضغطًا غير فقدان. |
| [PS](#PS) | ملف PostScript (.ps) |
| [TIF](#TIF) | ملف صورة معلمة (.tif) |
| [TIFF](#TIFF) | تنسيق ملف صورة معلمة (.tiff) |
| [GIF](#GIF) | ملف تنسيق تبادل رسومي (.gif) |
| [SVG](#SVG) | ملف رسومات متجهية قابلة للتوسيع (.svg) |
| [SVGZ](#SVGZ) | ملف رسومات متجهية قابلة للتوسيع مضغوط (.svgz) |
| [EMF](#EMF) | ملف Windows Enhanced Metafile (.emf) |
| [EMZ](#EMZ) | ملف Windows Compressed Enhanced Metafile (.emz) |
| [HTML](#HTML) | ملف Hypertext Markup Language (.html) هو الامتداد لصفحات الويب التي تم إنشاؤها للعرض في المتصفحات. |
| [MHT](#MHT) | ملف أرشيف ويب MHTML (.mht) هو تنسيق أرشفة صفحات الويب يمكن إنشاؤه بواسطة عدد من التطبيقات المختلفة. |
| [MHTML](#MHTML) | ملف MIME HTML (.mhtml) هو تنسيق أرشفة صفحات الويب يمكن إنشاؤه بواسطة عدد من التطبيقات المختلفة. |
| [ONE](#ONE) | ملفات OneNote Document (.one) يتم إنشاؤها بواسطة تطبيق Microsoft OneNote. |
| [PDF](#PDF) | ملف Portable Document Format (.pdf) هو تنسيق ملف تم تقديمه كمعيار لتمثيل المستندات والمواد المرجعية الأخرى في تنسيق مستقل عن برامج التطبيقات والعتاد وكذلك نظام التشغيل. |
| [XPS](#XPS) | ملف XML Paper Specification (.xps) يمثل ملفات تخطيط الصفحات التي تستند إلى مواصفات XML Paper التي أنشأتها Microsoft. |
| [TEX](#TEX) | ملف LaTeX Source Document (.tex) هو لغة تشمل البرمجة بالإضافة إلى ميزات الترميز، وتُستخدم لتنسيق المستندات. |
| [PPT](#PPT) | ملف PowerPoint Presentation (.ppt) يمثل ملف PowerPoint يتكون من مجموعة من الشرائح للعرض كعرض تقديمي. |
| [PPTX](#PPTX) | ملف PowerPoint Open XML Presentation (.pptx) هو ملف عرض تم إنشاؤه باستخدام تطبيق Microsoft PowerPoint الشهير. |
| [PPS](#PPS) | ملف PowerPoint Slide Show (.pps) هو ملف تم إنشاؤه باستخدام Microsoft PowerPoint لغرض العرض التقديمي. |
| [PPSX](#PPSX) | ملف PowerPoint Open XML Slide Show (.ppsx) هو ملف تم إنشاؤه باستخدام Microsoft PowerPoint 2007 وما بعده لغرض العرض التقديمي. |
| [ODP](#ODP) | ملف OpenDocument Presentation (.odp) يمثل تنسيق ملف عرض يُستخدم من قبل OpenOffice.org في معيار OASIS Open. |
| [OTP](#OTP) | ملف OpenDocument Presentation Template (.otp) يمثل ملفات قالب عرض تم إنشاؤها بواسطة التطبيقات وفق تنسيق معيار OASIS OpenDocument. |
| [XLS](#XLS) | ملف Excel Spreadsheet (.xls) هو ملف يمكن إنشاؤه بواسطة Microsoft Excel وكذلك برامج الجداول الحسابية المشابهة مثل OpenOffice Calc أو Apple Numbers. |
| [XLSX](#XLSX) | ملف Microsoft Excel Open XML Spreadsheet (.xlsx) هو تنسيق معروف لمستندات Microsoft Excel تم تقديمه من قبل Microsoft مع إصدار Microsoft Office 2007. |
| [XLSM](#XLSM) | ملف Excel Open XML Macro-Enabled Spreadsheet (.xlsm) هو نوع من ملفات الجداول الحسابية التي تدعم الماكرو. |
| [XLSB](#XLSB) | تنسيق ملف Excel Binary Spreadsheet (.xlsb) يحدد تنسيق Excel Binary File Format، وهو مجموعة من السجلات والهياكل التي تحدد محتوى دفتر عمل Excel. |
| [CSV](#CSV) | ملف Comma Separated Values (.csv) يمثل ملفات نصية عادية تحتوي على سجلات بيانات مفصولة بفواصل. |
| [TSV](#TSV) | ملف Tab Separated Values (.tsv) يمثل بيانات مفصولة بعلامات جدولة في تنسيق نص عادي. |
| [ODS](#ODS) | ملف OpenDocument Spreadsheet (.ods). |
| [XLTM](#XLTM) | ملف Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) يمثل ملفات يتم إنشاؤها بواسطة Microsoft Excel كقوالب مفعلة للماكرو. |
| [XLTX](#XLTX) | ملفات Excel Open XML Spreadsheet Template (.xltx) تستند إلى مواصفات تنسيق ملف Office OpenXML. |
| [XLT](#XLT) | ملف Excel Template (.xlt) هو ملف قالب تم إنشاؤه باستخدام Microsoft Excel وهو تطبيق جداول حسابية يأتي كجزء من مجموعة Microsoft Office. |
| [XLAM](#XLAM) | ملحق Excel القابل للماكرو (.xlam). |
| [DOC](#DOC) | تمثل مستندات Microsoft Word (.doc) المستندات التي تم إنشاؤها بواسطة Microsoft Word أو برامج معالجة النصوص الأخرى بصيغة ملف ثنائي. |
| [DOCX](#DOCX) | ملف Microsoft Word Open XML (.docx) هو تنسيق معروف جيدًا لمستندات Microsoft Word. |
| [DOCM](#DOCM) | ملفات Word Open XML Macro-Enabled Document (.docm) هي مستندات تم إنشاؤها بواسطة Microsoft Word 2007 أو أحدث مع القدرة على تشغيل الماكرو. |
| [DOT](#DOT) | ملفات قالب مستند Word (.dot) هي ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة الصياغة لتوليد ملفات DOC أو DOCX إضافية. |
| [DOTX](#DOTX) | قوالب مستند Word Open XML (.dotx) هي ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة الصياغة لتوليد ملفات DOCX إضافية. |
| [DOTM](#DOTM) | قالب Word Open XML Macro-Enabled Document (.dotm) يمثل ملف قالب تم إنشاؤه باستخدام Microsoft Word 2007 أو أحدث. |
| [RTF](#RTF) | ملف Rich Text Format (.rtf) الذي قدمته وثّقته Microsoft، يمثل Rich Text Format (RTF) طريقة لتشفير النص المنسق والرسومات للاستخدام داخل التطبيقات. |
| [TXT](#TXT) | ملف نص عادي (.txt) يمثل مستند نص يحتوي على نص عادي على شكل أسطر. |
| [ERR](#ERR) | ملف سجل الأخطاء (.err) هو ملف نصي يحتوي على رسائل الأخطاء التي يولدها برنامج. |
| [ODT](#ODT) | ملفات OpenDocument Text Document (.odt) هي نوع من المستندات التي تم إنشاؤها باستخدام تطبيقات معالجة النصوص المستندة إلى تنسيق ملف OpenDocument Text. |
| [OTT](#OTT) | قوالب OpenDocument Document (.ott) تمثل مستندات قالب تم إنشاؤها بواسطة التطبيقات وفقًا لتنسيق معيار OASIS OpenDocument. |
| [WAV](#WAV) | WAV، المعروف بـ WAVE (Waveform Audio File Format)، هو مجموعة فرعية من مواصفة Microsoft’s Resource Interchange File Format (RIFF) لتخزين ملفات الصوت الرقمية. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | اسم نوع الملف (مثلاً). |
| [getExtension()](#getExtension--) | لاحقة اسم الملف (بما في ذلك النقطة \".\") (مثلاً). |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | يربط امتداد الملف بنوع الملف. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | يسترجع أنواع الملفات المدعومة |
| [equals(FileType other)](#equals-com.groupdocs.merger.domain.FileType-) | يحدد ما إذا كان [FileType](../../com.groupdocs.merger.domain/filetype) الحالي هو نفسه كائن [FileType](../../com.groupdocs.merger.domain/filetype) المحدد. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان [FileType](../../com.groupdocs.merger.domain/filetype) الحالي هو نفسه الكائن المحدد. |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة لكائن [FileType](../../com.groupdocs.merger.domain/filetype) الحالي. |
| [op_Equality(FileType left, FileType right)](#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | يحدد ما إذا كان كائنان من نوع [FileType](../../com.groupdocs.merger.domain/filetype) متطابقان. |
| [op_Inequality(FileType left, FileType right)](#op-Inequality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | يحدد ما إذا كان كائنان من نوع [FileType](../../com.groupdocs.merger.domain/filetype) غير متطابقين. |
| [toString()](#toString--) | يعيد سلسلة تمثل الكائن الحالي. |
| [isText(FileType fileType)](#isText-com.groupdocs.merger.domain.FileType-) | يحدد ما إذا كان [FileType](../../com.groupdocs.merger.domain/filetype) المدخل هو تنسيق نصي بدائي. |
| [isArchive(FileType fileType)](#isArchive-com.groupdocs.merger.domain.FileType-) | يحدد ما إذا كان [FileType](../../com.groupdocs.merger.domain/filetype) المدخل هو تنسيق أرشيف. |
| [isImage(FileType fileType)](#isImage-com.groupdocs.merger.domain.FileType-) | يحدد ما إذا كان [FileType](../../com.groupdocs.merger.domain/filetype) المدخل هو تنسيق نصي بدائي. |
| [isAudio(FileType fileType)](#isAudio-com.groupdocs.merger.domain.FileType-) | يحدد ما إذا كان نوع الإدخال [FileType](../../com.groupdocs.merger.domain/filetype) هو تنسيق صوتي. |
| [getBase(FileType fileType)](#getBase-com.groupdocs.merger.domain.FileType-) |  |
### Unknown {#Unknown}
```
public static final FileType Unknown
```


يمثل نوع ملف غير معروف.

### ZIP {#ZIP}
```
public static FileType ZIP
```


ملف مضغوط (.zip)

### SevenZ {#SevenZ}
```
public static final FileType SevenZ
```


ملف مضغوط 7-Zip (.7z)

### TAR {#TAR}
```
public static final FileType TAR
```


أرشيف ملف يونكس موحد (.tar)

### RAR {#RAR}
```
public static final FileType RAR
```


ملف مضغوط Roshal ARchive (.rar)

### VSSX {#VSSX}
```
public static final FileType VSSX
```


ملف قالب Visio (.vssx) هو قوالب رسومات تم إنشاؤها باستخدام Microsoft Visio 2013 وما فوق. يمكن فتح تنسيق ملف VSSX باستخدام Visio 2013 وما فوق. تُعرف ملفات Visio بتمثيل مجموعة متنوعة من عناصر الرسم مثل مجموعة الأشكال، الموصلات، المخططات الانسيابية، تخطيط الشبكة، مخططات UML، تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/image/vssx

### VSDX {#VSDX}
```
public static final FileType VSDX
```


يمثل Visio Drawing (.vsdx) تنسيق ملف Microsoft Visio الذي تم تقديمه بدءًا من Microsoft Office 2013 فصاعدًا. تم تطويره لاستبدال تنسيق الملف الثنائي، .VSD، الذي تدعمه الإصدارات السابقة من Microsoft Visio. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/image/vsdx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Visio Macro-Enabled Drawing (.vsdm) هي ملفات رسومات تم إنشاؤها باستخدام تطبيق Microsoft Visio الذي يدعم الماكرو. ملفات VSDM هي رسومات OPC/XML تشبه VSDX، لكنها توفر أيضًا القدرة على تشغيل الماكرو عند فتح الملف. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/image/vsdm

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Visio Drawing Template (.vstx) هي ملفات قوالب رسومات تم إنشاؤها باستخدام Microsoft Visio 2013 وما فوق. توفر هذه الملفات VSTX نقطة انطلاق لإنشاء رسومات Visio، تُحفظ كملفات .VSDX، مع التخطيط والإعدادات الافتراضية. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Visio Macro-Enabled Drawing Template (.vstm) هي ملفات قوالب تم إنشاؤها باستخدام Microsoft Visio التي تدعم الماكرو. على عكس ملفات VSDX، يمكن للملفات التي تم إنشاؤها من قوالب VSTM تشغيل الماكرو الذي تم تطويره بلغة Visual Basic for Applications (VBA). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Visio Macro-Enabled Stencil File (.vssm) هي ملفات قالب Microsoft Visio التي تدعم الماكرو. عند فتح ملف VSSM يسمح بتشغيل الماكرو لتحقيق التنسيق المطلوب ووضع الأشكال في المخطط. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Visio Stencil XML File (.vsx) يشير إلى القوالب التي تتكون من رسومات وأشكال تُستخدم لإنشاء مخططات في Microsoft Visio. تُحفظ ملفات VSX بتنسيق XML وكان يتم دعمها حتى Visio 2013. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Visio Template XML File (.vtx) هو قالب رسم Microsoft Visio يتم حفظه على القرص بتنسيق ملف XML. يهدف القالب إلى توفير ملف بإعدادات أساسية يمكن استخدامها لإنشاء ملفات Visio متعددة بنفس الإعدادات. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/image/vtx

### VDX {#VDX}
```
public static final FileType VDX
```


Visio Drawing XML File (.vdx) هو رسم أو مخطط تم إنشاؤه في Microsoft Visio، لكنه يُحفظ بتنسيق XML بامتداد .VDX. يتم إنشاء ملف Visio Drawing XML في برنامج Visio الذي طورته Microsoft. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Open eBook File (.epub) هو تنسيق ملف كتاب إلكتروني يوفر تنسيق نشر رقمي قياسي للناشرين والمستهلكين. أصبح هذا التنسيق شائعًا إلى درجة أنه مدعوم من قبل العديد من القارئات الإلكترونية وتطبيقات البرمجيات. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/ebook/epub

### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap Image File (.bmp) تمثل ملفات تُستخدم لتخزين الصور الرقمية بتقنية البت ماب. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/image/bmp

### JPG {#JPG}
```
public static final FileType JPG
```


صورة JPEG (.jpg)

### JPEG {#JPEG}
```
public static final FileType JPEG
```


JPEG Image (.jpeg) هو نوع من تنسيقات الصور يُحفظ باستخدام طريقة الضغط الفاقد. الصورة الناتجة، نتيجة الضغط، تمثل موازنة بين حجم التخزين وجودة الصورة. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/image/jpeg

### PNG {#PNG}
```
public static final FileType PNG
```


Portable Network Graphic (.png) هو نوع من تنسيقات ملفات الصور النقطية التي تستخدم ضغط غير فاقد. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/image/png

### PS {#PS}
```
public static final FileType PS
```


ملف PostScript (.ps)

### TIF {#TIF}
```
public static FileType TIF
```


ملف صورة معلمة (.tif)

### TIFF {#TIFF}
```
public static FileType TIFF
```


تنسيق ملف صورة معلمة (.tiff)

### GIF {#GIF}
```
public static FileType GIF
```


ملف تنسيق تبادل رسومي (.gif)

### SVG {#SVG}
```
public static FileType SVG
```


ملف رسومات متجهية قابلة للتوسيع (.svg)

### SVGZ {#SVGZ}
```
public static FileType SVGZ
```


ملف رسومات متجهية قابلة للتوسيع مضغوط (.svgz)

### EMF {#EMF}
```
public static final FileType EMF
```


ملف Windows Enhanced Metafile (.emf)

### EMZ {#EMZ}
```
public static final FileType EMZ
```


ملف Windows Compressed Enhanced Metafile (.emz)

### HTML {#HTML}
```
public static final FileType HTML
```


Hypertext Markup Language File (.html) هو الامتداد لصفحات الويب التي تُنشأ للعرض في المتصفحات. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


MHTML Web Archive (.mht) هو تنسيق أرشيف صفحة ويب يمكن إنشاؤه بواسطة عدد من التطبيقات المختلفة. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/web/mhtml

### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML File (.mhtml) هو تنسيق أرشيف صفحة ويب يمكن إنشاؤه بواسطة عدد من التطبيقات المختلفة. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/web/mhtml

### ONE {#ONE}
```
public static final FileType ONE
```


ملفات مستند OneNote (.one) يتم إنشاؤها بواسطة تطبيق Microsoft OneNote. يتيح لك OneNote جمع المعلومات باستخدام التطبيق كما لو كنت تستخدم دفتر ملاحظاتك لتدوين الملاحظات. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


ملف تنسيق المستند المحمول (.pdf) هو تنسيق ملف تم تقديمه كمعيار لتمثيل المستندات وغيرها من المواد المرجعية في تنسيق لا يعتمد على برامج التطبيقات أو الأجهزة أو نظام التشغيل. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


ملف مواصفات ورق XML (.xps) يمثل ملفات تخطيط الصفحات التي تستند إلى مواصفات ورق XML التي أنشأتها Microsoft. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/page-description-language/xps

### TEX {#TEX}
```
public static final FileType TEX
```


مستند مصدر LaTeX (.tex) هو لغة تتضمن ميزات برمجة وكذلك ميزات توصيف، تُستخدم لتنسيق المستندات. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


عرض PowerPoint (.ppt) يمثل ملف PowerPoint يتكون من مجموعة من الشرائح للعرض كعرض شرائح. يحدد تنسيق الملف الثنائي المستخدم من قبل Microsoft PowerPoint 97-2003. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


عرض PowerPoint Open XML (.pptx) هو ملف عرض تم إنشاؤه باستخدام تطبيق Microsoft PowerPoint الشهير. على عكس نسخة تنسيق ملف العرض السابقة PPT التي كانت ثنائية، يعتمد تنسيق PPTX على تنسيق ملف عرض PowerPoint المفتوح XML. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


عرض شرائح PowerPoint (.pps) هو ملف تم إنشاؤه باستخدام Microsoft PowerPoint لغرض عرض الشرائح. يدعم Microsoft PowerPoint 97-2003 قراءة وإنشاء ملفات PPS. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


عرض شرائح PowerPoint Open XML (.ppsx) هو ملف تم إنشاؤه باستخدام Microsoft PowerPoint 2007 وما بعده لغرض عرض الشرائح. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


عرض OpenDocument (.odp) يمثل تنسيق ملف العرض المستخدم من قبل OpenOffice.org في معيار OASISOpen. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/presentation/odp

### OTP {#OTP}
```
public static final FileType OTP
```


قالب عرض OpenDocument (.otp) يمثل ملفات قوالب العرض التي تم إنشاؤها بواسطة التطبيقات وفق تنسيق معيار OASIS OpenDocument. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


جدول بيانات Excel (.xls) هو ملف يمكن إنشاؤه بواسطة Microsoft Excel وكذلك برامج جداول البيانات المشابهة مثل OpenOffice Calc أو Apple Numbers. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/spreadsheet/xls

### XLSX {#XLSX}
```
public static final FileType XLSX
```


جدول بيانات Microsoft Excel Open XML (.xlsx) هو تنسيق معروف لمستندات Microsoft Excel تم تقديمه من قبل Microsoft مع إصدار Microsoft Office 2007. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


جدول بيانات Excel Open XML المدعم بالماكرو (.xlsm) هو نوع من ملفات جداول البيانات التي تدعم الماكرو. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


تنسيق ملف Excel الثنائي (.xlsb) يحدد تنسيق ملف Excel الثنائي، وهو مجموعة من السجلات والهياكل التي تحدد محتوى دفتر عمل Excel. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


ملف القيم المفصولة بفواصل (.csv) يمثل ملفات نصية عادية تحتوي على سجلات بيانات ذات قيم مفصولة بفواصل. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


ملف القيم المفصولة بعلامات جدولة (.tsv) يمثل بيانات مفصولة بعلامات جدولة في تنسيق نص عادي. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


ملف OpenDocument Spreadsheet (.ods).

### XLTM {#XLTM}
```
public static final FileType XLTM
```


قالب جدول بيانات Excel Open XML المدعم بالماكرو (.xltm) يمثل الملفات التي يتم إنشاؤها بواسطة Microsoft Excel كقوالب مدعومة بالماكرو. ملفات XLTM مشابهة لملفات XLTX في البنية إلا أن الأخيرة لا تدعم إنشاء قوالب بملفات ماكرو. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/spreadsheet/xltm

### XLTX {#XLTX}
```
public static final FileType XLTX
```


قوالب جدول بيانات Excel Open XML (.xltx) تستند إلى مواصفات تنسيق ملف Office OpenXML. تُستخدم لإنشاء ملف قالب قياسي يمكن استخدامه لإنشاء ملفات XLSX التي تعرض نفس الإعدادات المحددة في ملف XLTX. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/spreadsheet/xltx

### XLT {#XLT}
```
public static final FileType XLT
```


ملف قالب إكسل (.xlt) هي ملفات قالب تم إنشاؤها باستخدام مايكروسوفت إكسل وهو تطبيق جداول بيانات يأتي كجزء من مجموعة مايكروسوفت أوفيس. دعم مايكروسوفت أوفيس 97-2003 إنشاء ملفات XLT جديدة وكذلك فتح هذه الملفات. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlt

### XLAM {#XLAM}
```
public static final FileType XLAM
```


ملحق Excel القابل للماكرو (.xlam).

### DOC {#DOC}
```
public static final FileType DOC
```


مستند مايكروسوفت وورد (.doc) يمثل المستندات التي تم إنشاؤها بواسطة مايكروسوفت وورد أو غيرها من برامج معالجة النصوص بصيغة ملف ثنائي. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


مستند مايكروسوفت وورد Open XML (.docx) هو تنسيق معروف لمستندات مايكروسوفت وورد. تم تقديمه منذ عام 2007 مع إصدار مايكروسوفت أوفيس 2007، وتم تغيير بنية هذا التنسيق الجديد من ثنائي بسيط إلى مزيج من ملفات XML وملفات ثنائية. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/word-processing/docx

### DOCM {#DOCM}
```
public static final FileType DOCM
```


ملفات مستند مايكروسوفت وورد Open XML المدعومة بالماكرو (.docm) هي مستندات تم إنشاؤها بواسطة مايكروسوفت وورد 2007 أو أحدث مع إمكانية تشغيل الماكرو. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


ملفات قالب مستند وورد (.dot) هي ملفات قالب تم إنشاؤها بواسطة مايكروسوفت وورد لتحتوي على إعدادات مسبقة الصياغة لتوليد ملفات DOC أو DOCX إضافية. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


قالب مستند مايكروسوفت وورد Open XML (.dotx) هو ملفات قالب تم إنشاؤها بواسطة مايكروسوفت وورد لتحتوي على إعدادات مسبقة الصياغة لتوليد ملفات DOCX إضافية. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


قالب مستند مايكروسوفت وورد Open XML المدعوم بالماكرو (.dotm) يمثل ملف قالب تم إنشاؤه باستخدام مايكروسوفت وورد 2007 أو أحدث. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


ملف تنسيق النص الغني (.rtf) تم تقديمه وتوثيقه من قبل مايكروسوفت، يمثل تنسيق النص الغني (RTF) طريقة لتشفير النص المنسق والرسومات للاستخدام داخل التطبيقات. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


ملف نص عادي (.txt) يمثل مستند نص يحتوي على نص عادي على شكل أسطر. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/word-processing/txt

### ERR {#ERR}
```
public static final FileType ERR
```


ملف سجل الأخطاء (.err) هو ملف نصي يحتوي على رسائل الأخطاء التي يولدها برنامج. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://fileinfo.com/extension/err

### ODT {#ODT}
```
public static final FileType ODT
```


ملفات مستند نص OpenDocument (.odt) هي نوع من المستندات التي تم إنشاؤها باستخدام تطبيقات معالجة النصوص المستندة إلى تنسيق ملف نص OpenDocument. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


قالب مستند OpenDocument (.ott) يمثل مستندات قالب تم إنشاؤها بواسطة التطبيقات وفقًا لتنسيق معيار OpenDocument الخاص بـ OASIS. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/word-processing/ott

### WAV {#WAV}
```
public static FileType WAV
```


WAV، المعروف بـ WAVE (Waveform Audio File Format)، هو مجموعة فرعية من تنسيق ملف تبادل الموارد (RIFF) الخاص بمايكروسوفت\\u2019s لتخزين ملفات الصوت الرقمية. لا يطبق هذا التنسيق أي ضغط على تدفق البتات ويخزن التسجيلات الصوتية بمعدلات عينة ومعدلات بت مختلفة. كان ولا يزال أحد التنسيقات القياسية لأقراص الصوت CD. تعرف على المزيد حول تنسيق هذا الملف  [here][] .


[here]: https://docs.fileformat.com/audio/wav

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


اسم نوع الملف مثال: \"Microsoft Word Document\".

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


لاحقة اسم الملف (بما في ذلك النقطة \".\") مثال: \".doc\".

**Returns:**
java.lang.String
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


يربط امتداد الملف بنوع الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| امتداد | java.lang.String | امتداد الملف (بما في ذلك النقطة \".\"). |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype) - When file type is supported returns it, otherwise returns default \#Unknown.Unknown file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


يسترجع أنواع الملفات المدعومة

**Returns:**
java.util.List<com.groupdocs.merger.domain.FileType> - يعيد تسلسل لأنواع الملفات المدعومة
### equals(FileType other) {#equals-com.groupdocs.merger.domain.FileType-}
```
public final boolean equals(FileType other)
```


يحدد ما إذا كان [FileType](../../com.groupdocs.merger.domain/filetype) الحالي هو نفسه كائن [FileType](../../com.groupdocs.merger.domain/filetype) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [FileType](../../com.groupdocs.merger.domain/filetype) | الكائن للمقارنة مع كائن [FileType](../../com.groupdocs.merger.domain/filetype) الحالي. |

**Returns:**
boolean - ```
true
```

if both [FileType](../../com.groupdocs.merger.domain/filetype) objects are the same; otherwise,

```
false
```
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the current [FileType](../../com.groupdocs.merger.domain/filetype) is the same as specified object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to compare with the current [FileType](../../com.groupdocs.merger.domain/filetype) object. |

**Returns:**
boolean - ```
true
```

if

```
obj
```

المعامل هو [FileType](../../com.groupdocs.merger.domain/filetype) وهو نفسه ككائن [FileType](../../com.groupdocs.merger.domain/filetype) الحالي؛ وإلا،

```
false
```
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز التجزئة لكائن [FileType](../../com.groupdocs.merger.domain/filetype) الحالي.

**Returns:**
int - رمز تجزئة للكائن [FileType](../../com.groupdocs.merger.domain/filetype) الحالي.
### op_Equality(FileType left, FileType right) {#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public static boolean op_Equality(FileType left, FileType right)
```


يحدد ما إذا كان كائنان من نوع [FileType](../../com.groupdocs.merger.domain/filetype) متطابقان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.merger.domain/filetype) | كائن [FileType](../../com.groupdocs.merger.domain/filetype) الأيسر. |
| right | [FileType](../../com.groupdocs.merger.domain/filetype) | كائن [FileType](../../com.groupdocs.merger.domain/filetype) الأيمن. |

**Returns:**
boolean - ```
true
```

if both [FileType](../../com.groupdocs.merger.domain/filetype) objects are the same; otherwise,

```
false
```
### op_Inequality(FileType left, FileType right) {#op-Inequality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public static boolean op_Inequality(FileType left, FileType right)
```


Determines whether two [FileType](../../com.groupdocs.merger.domain/filetype) objects are not the same.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.merger.domain/filetype) | Left [FileType](../../com.groupdocs.merger.domain/filetype) object. |
| right | [FileType](../../com.groupdocs.merger.domain/filetype) | Right [FileType](../../com.groupdocs.merger.domain/filetype) object. |

**Returns:**
boolean - ```
true
```

إذا لم تكن كائنات [FileType](../../com.groupdocs.merger.domain/filetype) كلاهما متطابقة؛ وإلا،

```
false
```
### toString() {#toString--}
```
public String toString()
```


يعيد سلسلة تمثل الكائن الحالي.

**Returns:**
java.lang.String - سلسلة تمثل الكائن الحالي.
### isText(FileType fileType) {#isText-com.groupdocs.merger.domain.FileType-}
```
public static boolean isText(FileType fileType)
```


يحدد ما إذا كان [FileType](../../com.groupdocs.merger.domain/filetype) المدخل هو تنسيق نصي بدائي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | كائن [FileType](../../com.groupdocs.merger.domain/filetype). |

**Returns:**
boolean - ```
true
```

if input [FileType](../../com.groupdocs.merger.domain/filetype) is primitive text format; otherwise,

```
false
```
### isArchive(FileType fileType) {#isArchive-com.groupdocs.merger.domain.FileType-}
```
public static boolean isArchive(FileType fileType)
```


Determines whether input [FileType](../../com.groupdocs.merger.domain/filetype) is archive format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The [FileType](../../com.groupdocs.merger.domain/filetype) object. |

**Returns:**
boolean - ```
true
```

إذا كان [FileType](../../com.groupdocs.merger.domain/filetype) بتنسيق أرشيف؛ وإلا،

```
false
```
### isImage(FileType fileType) {#isImage-com.groupdocs.merger.domain.FileType-}
```
public static boolean isImage(FileType fileType)
```


يحدد ما إذا كان [FileType](../../com.groupdocs.merger.domain/filetype) المدخل هو تنسيق نصي بدائي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | كائن [FileType](../../com.groupdocs.merger.domain/filetype). |

**Returns:**
boolean - ```
true
```

if input [FileType](../../com.groupdocs.merger.domain/filetype) is primitive image format; otherwise,

```
false
```
### isAudio(FileType fileType) {#isAudio-com.groupdocs.merger.domain.FileType-}
```
public static boolean isAudio(FileType fileType)
```


Determines whether input [FileType](../../com.groupdocs.merger.domain/filetype) is audio format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The [FileType](../../com.groupdocs.merger.domain/filetype) object. |

**Returns:**
boolean - ```
true
```

إذا كان [FileType](../../com.groupdocs.merger.domain/filetype) بتنسيق صوتي؛ وإلا،

```
false
```
### getBase(FileType fileType) {#getBase-com.groupdocs.merger.domain.FileType-}
```
public static FileType getBase(FileType fileType)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) |  |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
