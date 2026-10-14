---
title: "FileType"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Представляет тип файла."
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.merger.domain/filetype/
---
**Inheritance:**
java.lang.Object
```
public final class FileType
```

Представляет тип файла. Предоставляет методы для получения списка всех типов файлов, поддерживаемых **GroupDocs.Merger**, определения типа файла по расширению и т.д.

--------------------

**Learn more**

 *  Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats][]
 *  Learn more about getting supported file types in code: [How to get supported file formats in code][]


[Full list of supported document formats]: https://docs.groupdocs.com/display/mergernet/Supported+Document+Types
[How to get supported file formats in code]: https://docs.groupdocs.com/display/mergernet/Get+supported+file+types
## Поля

| Поле | Описание |
| --- | --- |
| [Unknown](#Unknown) | Представляет неизвестный тип файла. |
| [ZIP](#ZIP) | Сжатый файл (.zip) |
| [SevenZ](#SevenZ) | Сжатый файл 7-Zip (.7z) |
| [TAR](#TAR) | Консолидированный архив Unix (.tar) |
| [RAR](#RAR) | Сжатый файл Roshal ARchive (.rar) |
| [VSSX](#VSSX) | Visio Stencil File (.vssx) — это шаблоны чертежей, созданные в Microsoft Visio 2013 и выше. |
| [VSDX](#VSDX) | Visio Drawing (.vsdx) представляет формат файлов Microsoft Visio, введённый начиная с Microsoft Office 2013. |
| [VSDM](#VSDM) | Visio Macro-Enabled Drawing (.vsdm) — это файлы чертежей, созданные в приложении Microsoft Visio, поддерживающем макросы. |
| [VSTX](#VSTX) | Visio Drawing Template (.vstx) — это файлы шаблонов чертежей, созданные в Microsoft Visio 2013 и более новых версиях. |
| [VSTM](#VSTM) | Visio Macro-Enabled Drawing Template (.vstm) — это файлы шаблонов, созданные в Microsoft Visio и поддерживающие макросы. |
| [VSSM](#VSSM) | Visio Macro-Enabled Stencil File (.vssm) — это файлы шаблонов Microsoft Visio, предоставляющие поддержку макросов. |
| [VSX](#VSX) | Visio Stencil XML File (.vsx) относится к шаблонам, состоящим из чертежей и фигур, используемых для создания диаграмм в Microsoft Visio. |
| [VTX](#VTX) | Visio Template XML File (.vtx) — это шаблон чертежа Microsoft Visio, сохраняемый на диск в формате XML. |
| [VDX](#VDX) | Visio Drawing XML File (.vdx) — это чертеж или диаграмма, созданные в Microsoft Visio, но сохранённые в формате XML с расширением .VDX. |
| [EPUB](#EPUB) | Open eBook File (.epub) — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций для издателей и читателей. |
| [BMP](#BMP) | Bitmap Image File (.bmp) представляет файлы, используемые для хранения растровых цифровых изображений. |
| [JPG](#JPG) | Изображение JPEG (.jpg) |
| [JPEG](#JPEG) | JPEG Image (.jpeg) — это тип формата изображения, сохраняемый с использованием метода сжатия с потерями. |
| [PNG](#PNG) | Portable Network Graphic (.png) — это тип растрового формата изображения, использующий сжатие без потерь. |
| [PS](#PS) | Файл PostScript (.ps) |
| [TIF](#TIF) | Тегированный файл изображения (.tif) |
| [TIFF](#TIFF) | Тегированный формат изображения (.tiff) |
| [GIF](#GIF) | Файл графического формата обмена (.gif) |
| [SVG](#SVG) | Файл масштабируемой векторной графики (.svg) |
| [SVGZ](#SVGZ) | Сжатый файл масштабируемой векторной графики (.svgz) |
| [EMF](#EMF) | Windows Enhanced Metafile (.emf) |
| [EMZ](#EMZ) | Windows Compressed Enhanced Metafile (.emz) |
| [HTML](#HTML) | Файл Hypertext Markup Language (.html) — это расширение для веб-страниц, созданных для отображения в браузерах. |
| [MHT](#MHT) | Веб-архив MHTML (.mht) — это формат архива веб-страниц, который может быть создан рядом различных приложений. |
| [MHTML](#MHTML) | Файл MIME HTML (.mhtml) — это формат архива веб-страниц, который может быть создан рядом различных приложений. |
| [ONE](#ONE) | Файлы OneNote Document (.one) создаются приложением Microsoft OneNote. |
| [PDF](#PDF) | Файл Portable Document Format (.pdf) — это формат, введённый в качестве стандарта представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. |
| [XPS](#XPS) | Файл XML Paper Specification (.xps) представляет файлы макетов страниц, основанные на спецификации XML Paper, созданной Microsoft. |
| [TEX](#TEX) | Исходный документ LaTeX (.tex) — это язык, включающий программные и разметочные возможности, используемый для наборa документов. |
| [PPT](#PPT) | Презентация PowerPoint (.ppt) представляет файл PowerPoint, содержащий набор слайдов для показа в виде слайд-шоу. |
| [PPTX](#PPTX) | Презентация PowerPoint Open XML (.pptx) — это файл презентации, созданный популярным приложением Microsoft PowerPoint. |
| [PPS](#PPS) | Слайд-шоу PowerPoint (.pps) — это файл, созданный с помощью Microsoft PowerPoint для целей слайд-шоу. |
| [PPSX](#PPSX) | Слайд-шоу PowerPoint Open XML (.ppsx) — это файл, созданный с помощью Microsoft PowerPoint 2007 и более новых версий для целей слайд-шоу. |
| [ODP](#ODP) | Презентация OpenDocument (.odp) представляет формат файлов презентаций, используемый OpenOffice.org в стандарте OASIS Open. |
| [OTP](#OTP) | Шаблон презентации OpenDocument (.otp) представляет файлы шаблонов презентаций, созданные приложениями в формате стандарта OASIS OpenDocument. |
| [XLS](#XLS) | Электронная таблица Excel (.xls) — это файл, который может быть создан Microsoft Excel, а также другими аналогичными программами, такими как OpenOffice Calc или Apple Numbers. |
| [XLSX](#XLSX) | Электронная таблица Microsoft Excel Open XML (.xlsx) — это известный формат документов Microsoft Excel, представленный Microsoft вместе с выпуском Microsoft Office 2007. |
| [XLSM](#XLSM) | Электронная таблица Excel Open XML с поддержкой макросов (.xlsm) — это тип файлов таблиц, поддерживающих макросы. |
| [XLSB](#XLSB) | Формат файла Excel Binary Spreadsheet (.xlsb) определяет Excel Binary File Format, представляющий собой набор записей и структур, описывающих содержимое книги Excel. |
| [CSV](#CSV) | Файл значений, разделённых запятыми (.csv), представляет собой текстовые файлы, содержащие записи данных с запятыми в качестве разделителей. |
| [TSV](#TSV) | Файл значений, разделённых табуляцией (.tsv), представляет данные, разделённые табуляцией, в текстовом формате. |
| [ODS](#ODS) | Электронная таблица OpenDocument (.ods). |
| [XLTM](#XLTM) | Шаблон электронной таблицы Excel Open XML с поддержкой макросов (.xltm) представляет файлы, генерируемые Microsoft Excel как шаблоны с поддержкой макросов. |
| [XLTX](#XLTX) | Шаблоны электронной таблицы Excel Open XML (.xltx) основаны на спецификациях формата файлов Office OpenXML. |
| [XLT](#XLT) | Файл шаблона Excel (.xlt) — это шаблоны, созданные с помощью Microsoft Excel, который является приложением для работы с таблицами и входит в состав пакета Microsoft Office. |
| [XLAM](#XLAM) | Надстройка Excel с поддержкой макросов (.xlam). |
| [DOC](#DOC) | Документ Microsoft Word (.doc) представляет документы, созданные Microsoft Word или другими текстовыми процессорами, в бинарном файловом формате. |
| [DOCX](#DOCX) | Документ Microsoft Word Open XML (.docx) — это широко известный формат для документов Microsoft Word. |
| [DOCM](#DOCM) | Файлы Word Open XML с поддержкой макросов (.docm) — это документы, созданные в Microsoft Word 2007 и новее, с возможностью выполнения макросов. |
| [DOT](#DOT) | Файлы шаблонов документов Word (.dot) — это шаблоны, созданные Microsoft Word, содержащие предварительно отформатированные настройки для создания дальнейших файлов DOC или DOCX. |
| [DOTX](#DOTX) | Шаблоны документов Word Open XML (.dotx) — это файлы шаблонов, созданные Microsoft Word, содержащие предварительно отформатированные настройки для создания дальнейших файлов DOCX. |
| [DOTM](#DOTM) | Шаблон Word Open XML с поддержкой макросов (.dotm) представляет собой файл шаблона, созданный в Microsoft Word 2007 и новее. |
| [RTF](#RTF) | Файл Rich Text Format (.rtf), представленный и документированный Microsoft, представляет метод кодирования отформатированного текста и графики для использования в приложениях. |
| [TXT](#TXT) | Файл обычного текста (.txt) представляет текстовый документ, содержащий обычный текст в виде строк. |
| [ERR](#ERR) | Файл журнала ошибок (.err) — это текстовый файл, содержащий сообщения об ошибках, сгенерированные программой. |
| [ODT](#ODT) | Файлы OpenDocument Text Document (.odt) — это тип документов, создаваемых с помощью текстовых процессоров, основанных на формате OpenDocument Text File. |
| [OTT](#OTT) | Шаблоны документов OpenDocument (.ott) представляют собой шаблоны, генерируемые приложениями в соответствии со стандартным форматом OpenDocument от OASIS. |
| [WAV](#WAV) | WAV, известный как WAVE (Waveform Audio File Format), является подмножеством спецификации Resource Interchange File Format (RIFF) от Microsoft\\u2019s для хранения цифровых аудиофайлов. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Имя типа файла, например. |
| [getExtension()](#getExtension--) | Суффикс имени файла (включая точку \".\") например. |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Отображает расширение файла на тип файла. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Получает поддерживаемые типы файлов |
| [equals(FileType other)](#equals-com.groupdocs.merger.domain.FileType-) | Определяет, является ли текущий [FileType](../../com.groupdocs.merger.domain/filetype) тем же, что указанный объект [FileType](../../com.groupdocs.merger.domain/filetype). |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, является ли текущий [FileType](../../com.groupdocs.merger.domain/filetype) тем же, что указанный объект. |
| [hashCode()](#hashCode--) | Возвращает хеш-код текущего объекта [FileType](../../com.groupdocs.merger.domain/filetype). |
| [op_Equality(FileType left, FileType right)](#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Определяет, являются ли два объекта [FileType](../../com.groupdocs.merger.domain/filetype) одинаковыми. |
| [op_Inequality(FileType left, FileType right)](#op-Inequality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Определяет, не являются ли два объекта [FileType](../../com.groupdocs.merger.domain/filetype) одинаковыми. |
| [toString()](#toString--) | Возвращает строку, представляющую текущий объект. |
| [isText(FileType fileType)](#isText-com.groupdocs.merger.domain.FileType-) | Определяет, является ли входной [FileType](../../com.groupdocs.merger.domain/filetype) простым текстовым форматом. |
| [isArchive(FileType fileType)](#isArchive-com.groupdocs.merger.domain.FileType-) | Определяет, является ли входной [FileType](../../com.groupdocs.merger.domain/filetype) форматом архива. |
| [isImage(FileType fileType)](#isImage-com.groupdocs.merger.domain.FileType-) | Определяет, является ли входной [FileType](../../com.groupdocs.merger.domain/filetype) простым текстовым форматом. |
| [isAudio(FileType fileType)](#isAudio-com.groupdocs.merger.domain.FileType-) | Определяет, является ли входной [FileType](../../com.groupdocs.merger.domain/filetype) аудиоформатом. |
| [getBase(FileType fileType)](#getBase-com.groupdocs.merger.domain.FileType-) |  |
### Unknown {#Unknown}
```
public static final FileType Unknown
```


Представляет неизвестный тип файла.

### ZIP {#ZIP}
```
public static FileType ZIP
```


Сжатый файл (.zip)

### SevenZ {#SevenZ}
```
public static final FileType SevenZ
```


Сжатый файл 7-Zip (.7z)

### TAR {#TAR}
```
public static final FileType TAR
```


Консолидированный архив Unix (.tar)

### RAR {#RAR}
```
public static final FileType RAR
```


Сжатый файл Roshal ARchive (.rar)

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Файл шаблона Visio (.vssx) — это шаблоны чертежей, созданные в Microsoft Visio 2013 и более новых версиях. Формат файла VSSX можно открыть в Visio 2013 и более новых версиях. Файлы Visio известны представлением различных элементов чертежа, таких как набор фигур, соединителей, блок‑схем, сетевых схем, UML‑диаграмм. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/image/vssx

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Visio Drawing (.vsdx) представляет формат файлов Microsoft Visio, введённый, начиная с Microsoft Office 2013. Он был разработан для замены бинарного формата файлов .VSD, поддерживаемого более ранними версиями Microsoft Visio. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/image/vsdx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Visio Macro-Enabled Drawing (.vsdm) — это файлы чертежей, созданные в приложении Microsoft Visio, поддерживающем макросы. Файлы VSDM представляют собой чертежи OPC/XML, похожие на VSDX, но также позволяют выполнять макросы при открытии файла. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/image/vsdm

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Visio Drawing Template (.vstx) — это файлы шаблонов чертежей, созданные в Microsoft Visio 2013 и более новых версиях. Эти файлы VSTX предоставляют отправную точку для создания чертежей Visio, сохраняемых как файлы .VSDX, с макетом и настройками по умолчанию. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Visio Macro-Enabled Drawing Template (.vstm) — это файлы шаблонов, созданные в Microsoft Visio с поддержкой макросов. В отличие от файлов VSDX, файлы, созданные из шаблонов VSTM, могут выполнять макросы, разработанные на языке Visual Basic for Applications (VBA). Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Visio Macro-Enabled Stencil File (.vssm) — это файлы шаблонов Microsoft Visio, поддерживающие макросы. При открытии файла VSSM позволяют выполнять макросы для достижения требуемого форматирования и размещения фигур в диаграмме. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Visio Stencil XML File (.vsx) относится к шаблонам, содержащим чертежи и фигуры, используемые для создания диаграмм в Microsoft Visio. Файлы VSX сохраняются в формате XML и поддерживались до Visio 2013. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Visio Template XML File (.vtx) — это шаблон чертежа Microsoft Visio, сохраняемый на диск в формате XML. Шаблон предназначен для предоставления файла с базовыми настройками, которые можно использовать для создания нескольких файлов Visio с одинаковыми параметрами. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/image/vtx

### VDX {#VDX}
```
public static final FileType VDX
```


Visio Drawing XML File (.vdx) — это чертеж или диаграмма, созданные в Microsoft Visio, но сохранённые в формате XML с расширением .VDX. Файл XML‑чертежа Visio создаётся в программном обеспечении Visio, разработанном компанией Microsoft. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Open eBook File (.epub) — это формат файлов электронных книг, предоставляющий стандартный цифровой формат публикаций для издателей и читателей. Формат стал настолько распространённым, что поддерживается многими электронными читалками и программными приложениями. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/ebook/epub

### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap Image File (.bmp) представляет файлы, используемые для хранения растровых цифровых изображений. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/image/bmp

### JPG {#JPG}
```
public static final FileType JPG
```


Изображение JPEG (.jpg)

### JPEG {#JPEG}
```
public static final FileType JPEG
```


JPEG Image (.jpeg) — это тип формата изображения, сохраняемый с использованием метода сжатия с потерями. Получаемое изображение в результате сжатия представляет собой компромисс между размером хранения и качеством изображения. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/image/jpeg

### PNG {#PNG}
```
public static final FileType PNG
```


Portable Network Graphic (.png) — это тип растрового формата изображения, использующий сжатие без потерь. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/image/png

### PS {#PS}
```
public static final FileType PS
```


Файл PostScript (.ps)

### TIF {#TIF}
```
public static FileType TIF
```


Тегированный файл изображения (.tif)

### TIFF {#TIFF}
```
public static FileType TIFF
```


Тегированный формат изображения (.tiff)

### GIF {#GIF}
```
public static FileType GIF
```


Файл графического формата обмена (.gif)

### SVG {#SVG}
```
public static FileType SVG
```


Файл масштабируемой векторной графики (.svg)

### SVGZ {#SVGZ}
```
public static FileType SVGZ
```


Сжатый файл масштабируемой векторной графики (.svgz)

### EMF {#EMF}
```
public static final FileType EMF
```


Windows Enhanced Metafile (.emf)

### EMZ {#EMZ}
```
public static final FileType EMZ
```


Windows Compressed Enhanced Metafile (.emz)

### HTML {#HTML}
```
public static final FileType HTML
```


Hypertext Markup Language File (.html) — это расширение для веб‑страниц, созданных для отображения в браузерах. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


MHTML Web Archive (.mht) — это формат архива веб‑страницы, который может быть создан различными приложениями. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/web/mhtml

### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML File (.mhtml) — это формат архива веб‑страницы, который может быть создан различными приложениями. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/web/mhtml

### ONE {#ONE}
```
public static final FileType ONE
```


Файлы OneNote Document (.one) создаются приложением Microsoft OneNote. OneNote позволяет собирать информацию, используя приложение, как если бы вы использовали свой черновик для записи заметок. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Файл Portable Document Format (.pdf) — это формат файла, который был введён как стандарт представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


Файл XML Paper Specification (.xps) представляет файлы разметки страниц, основанные на спецификации XML Paper, созданной Microsoft. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/page-description-language/xps

### TEX {#TEX}
```
public static final FileType TEX
```


Документ исходного кода LaTeX (.tex) — это язык, включающий программные и разметочные возможности, используемый для наборa документов. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


Презентация PowerPoint (.ppt) представляет файл PowerPoint, состоящий из набора слайдов для отображения в виде слайд-шоу. Он определяет бинарный формат файла, используемый Microsoft PowerPoint 97‑2003. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


Презентация PowerPoint Open XML (.pptx) — это файл презентации, созданный популярным приложением Microsoft PowerPoint. В отличие от предыдущей версии формата PPT, который был бинарным, формат PPTX основан на открытом XML‑формате презентаций Microsoft PowerPoint. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


Слайд-шоу PowerPoint (.pps) — это файл, созданный с помощью Microsoft PowerPoint для показа слайдов. Чтение и создание файлов PPS поддерживается Microsoft PowerPoint 97‑2003. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


Слайд-шоу PowerPoint Open XML (.ppsx) — это файл, созданный с помощью Microsoft PowerPoint 2007 и более новых версий для показа слайдов. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


Презентация OpenDocument (.odp) представляет формат файлов презентаций, используемый OpenOffice.org в стандарте OASIS Open. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/presentation/odp

### OTP {#OTP}
```
public static final FileType OTP
```


Шаблон презентации OpenDocument (.otp) представляет файлы шаблонов презентаций, созданные приложениями в формате стандарта OASIS OpenDocument. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Электронная таблица Excel (.xls) — это файл, который может быть создан Microsoft Excel, а также другими похожими программами для работы с таблицами, такими как OpenOffice Calc или Apple Numbers. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/spreadsheet/xls

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel Open XML Spreadsheet (.xlsx) — это известный формат документов Microsoft Excel, который был представлен Microsoft вместе с выпуском Microsoft Office 2007. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Электронная таблица Excel Open XML с поддержкой макросов (.xlsm) — это тип файлов таблиц, поддерживающих макросы. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Формат файла Excel Binary Spreadsheet (.xlsb) определяет бинарный формат файлов Excel, представляющий собой набор записей и структур, описывающих содержимое рабочей книги Excel. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Файл со значениями, разделёнными запятыми (.csv), представляет собой обычные текстовые файлы, содержащие записи данных с запятыми в качестве разделителей. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Файл со значениями, разделёнными табуляцией (.tsv), представляет данные, разделённые табуляторами, в обычном текстовом формате. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


Электронная таблица OpenDocument (.ods).

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Шаблон электронной таблицы Excel Open XML с поддержкой макросов (.xltm) представляет файлы, генерируемые Microsoft Excel как шаблоны с поддержкой макросов. Файлы XLTM похожи на XLTX по структуре, за исключением того, что последние не поддерживают создание шаблонов с макросами. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/spreadsheet/xltm

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Шаблоны электронной таблицы Excel Open XML (.xltx) основаны на спецификациях формата Office OpenXML. Они используются для создания стандартного шаблона, который может быть применён для генерации файлов XLSX с теми же настройками, что указаны в файле XLTX. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/spreadsheet/xltx

### XLT {#XLT}
```
public static final FileType XLT
```


Файлы шаблонов Excel (.xlt) — это шаблонные файлы, созданные с помощью Microsoft Excel, который является приложением для работы с электронными таблицами и входит в состав пакета Microsoft Office. Microsoft Office 97‑2003 поддерживал создание новых файлов XLT, а также их открытие. Узнайте больше о этом формате файла [здесь][].


[here]: https://docs.fileformat.com/spreadsheet/xlt

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Надстройка Excel с поддержкой макросов (.xlam).

### DOC {#DOC}
```
public static final FileType DOC
```


Документы Microsoft Word (.doc) представляют файлы, созданные в Microsoft Word или других текстовых процессорах, в бинарном формате. Узнайте больше о этом формате файла [здесь][].


[here]: https://docs.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word Open XML Document (.docx) — известный формат документов Microsoft Word. Появился в 2007 году с выпуском Microsoft Office 2007, структура этого нового формата документа была изменена с простого бинарного на комбинацию XML и бинарных файлов. Узнайте больше о этом формате файла [здесь][].


[here]: https://docs.fileformat.com/word-processing/docx

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Файлы Word Open XML Macro-Enabled Document (.docm) — это документы, созданные в Microsoft Word 2007 и более новых версиях, с возможностью выполнения макросов. Узнайте больше о этом формате файла [здесь][].


[here]: https://docs.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Файлы шаблонов Word Document Template (.dot) — это шаблонные файлы, созданные в Microsoft Word с предустановленными настройками для создания последующих файлов DOC или DOCX. Узнайте больше о этом формате файла [здесь][].


[here]: https://docs.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Файлы шаблонов Word Open XML Document Template (.dotx) — это шаблонные файлы, созданные в Microsoft Word с предустановленными настройками для создания последующих файлов DOCX. Узнайте больше о этом формате файла [здесь][].


[here]: https://docs.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Word Open XML Macro-Enabled Document Template (.dotm) представляет собой шаблонный файл, созданный в Microsoft Word 2007 и более новых версиях. Узнайте больше о этом формате файла [здесь][].


[here]: https://docs.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Файл Rich Text Format (.rtf), представленный и задокументированный Microsoft, представляет собой метод кодирования форматированного текста и графики для использования в приложениях. Узнайте больше о этом формате файла [здесь][].


[here]: https://docs.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Файл обычного текста (.txt) представляет собой текстовый документ, содержащий простой текст в виде строк. Узнайте больше о этом формате файла [здесь][].


[here]: https://docs.fileformat.com/word-processing/txt

### ERR {#ERR}
```
public static final FileType ERR
```


Файл журнала ошибок (.err) — это текстовый файл, содержащий сообщения об ошибках, сгенерированные программой. Узнайте больше о этом формате файла [здесь][].


[here]: https://fileinfo.com/extension/err

### ODT {#ODT}
```
public static final FileType ODT
```


Файлы OpenDocument Text Document (.odt) — это тип документов, созданных в текстовых процессорах, основанных на формате OpenDocument Text File. Узнайте больше о этом формате файла [здесь][].


[here]: https://docs.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument Document Template (.ott) представляет шаблонные документы, генерируемые приложениями в соответствии со стандартным форматом OASIS OpenDocument. Узнайте больше о этом формате файла [здесь][].


[here]: https://docs.fileformat.com/word-processing/ott

### WAV {#WAV}
```
public static FileType WAV
```


WAV, известный как WAVE (Waveform Audio File Format), является подмножеством спецификации Microsoft\u2019s Resource Interchange File Format (RIFF) для хранения цифровых аудиофайлов. Формат не применяет сжатие к битовому потоку и сохраняет аудиозаписи с различными частотами дискретизации и битрейтами. Он был и остаётся одним из стандартных форматов для аудио CD. Узнайте больше о этом формате файла [здесь][].


[here]: https://docs.fileformat.com/audio/wav

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Имя типа файла, например "Microsoft Word Document".

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Суффикс имени файла (включая точку "."), например ".doc".

**Returns:**
java.lang.String
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Отображает расширение файла на тип файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| расширение | java.lang.String | Расширение файла (включая точку "."). |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype) - When file type is supported returns it, otherwise returns default \#Unknown.Unknown file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Получает поддерживаемые типы файлов

**Returns:**
java.util.List<com.groupdocs.merger.domain.FileType> — возвращает последовательность поддерживаемых типов файлов
### equals(FileType other) {#equals-com.groupdocs.merger.domain.FileType-}
```
public final boolean equals(FileType other)
```


Определяет, является ли текущий [FileType](../../com.groupdocs.merger.domain/filetype) тем же, что указанный объект [FileType](../../com.groupdocs.merger.domain/filetype).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [FileType](../../com.groupdocs.merger.domain/filetype) | Объект, с которым сравнивается текущий объект [FileType](../../com.groupdocs.merger.domain/filetype). |

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

параметр является [FileType](../../com.groupdocs.merger.domain/filetype) и совпадает с текущим объектом [FileType](../../com.groupdocs.merger.domain/filetype); иначе,

```
false
```
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код текущего объекта [FileType](../../com.groupdocs.merger.domain/filetype).

**Returns:**
int — хеш-код текущего объекта [FileType](../../com.groupdocs.merger.domain/filetype).
### op_Equality(FileType left, FileType right) {#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public static boolean op_Equality(FileType left, FileType right)
```


Определяет, являются ли два объекта [FileType](../../com.groupdocs.merger.domain/filetype) одинаковыми.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.merger.domain/filetype) | Левый объект [FileType](../../com.groupdocs.merger.domain/filetype). |
| right | [FileType](../../com.groupdocs.merger.domain/filetype) | Правый объект [FileType](../../com.groupdocs.merger.domain/filetype). |

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

если оба объекта [FileType](../../com.groupdocs.merger.domain/filetype) не одинаковы; иначе,

```
false
```
### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую текущий объект.

**Returns:**
java.lang.String — строка, представляющая текущий объект.
### isText(FileType fileType) {#isText-com.groupdocs.merger.domain.FileType-}
```
public static boolean isText(FileType fileType)
```


Определяет, является ли входной [FileType](../../com.groupdocs.merger.domain/filetype) простым текстовым форматом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Объект [FileType](../../com.groupdocs.merger.domain/filetype). |

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

если входной [FileType](../../com.groupdocs.merger.domain/filetype) имеет архивный формат; иначе,

```
false
```
### isImage(FileType fileType) {#isImage-com.groupdocs.merger.domain.FileType-}
```
public static boolean isImage(FileType fileType)
```


Определяет, является ли входной [FileType](../../com.groupdocs.merger.domain/filetype) простым текстовым форматом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Объект [FileType](../../com.groupdocs.merger.domain/filetype). |

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

если входной [FileType](../../com.groupdocs.merger.domain/filetype) имеет аудио формат; иначе,

```
false
```
### getBase(FileType fileType) {#getBase-com.groupdocs.merger.domain.FileType-}
```
public static FileType getBase(FileType fileType)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) |  |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
