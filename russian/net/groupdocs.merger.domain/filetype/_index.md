---
title: FileType
second_title: Справочник по API GroupDocs.Merge для .NET
description: Представляет тип файла. Предоставляет методы для получения списка всех типов файлов поддерживаемыхGroupDocs.Объединение  определить тип файла по расширению и т. д.
type: docs
weight: 100
url: /ru/net/groupdocs.merger.domain/filetype/
---
## FileType class

Представляет тип файла. Предоставляет методы для получения списка всех типов файлов, поддерживаемых**GroupDocs.Объединение** , определить тип файла по расширению и т. д.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | Суффикс имени файла (включая точку "."), например, ".doc". |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | Имя типа файла, например, "Документ Microsoft Word". |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | Сопоставляет расширение файла с типом файла. |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | Определяет, является ли текущий[`FileType`](../filetype) такое же, как указано[`FileType`](../filetype) объект. |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | Определяет, является ли текущий[`FileType`](../filetype) совпадает с указанным объектом. |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | Возвращает хеш-код для текущего[`FileType`](../filetype) объект. |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | Возвращает строку, представляющую текущий объект. |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | Извлекает поддерживаемые типы файлов |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | Определяет, будет ли ввод[`FileType`](../filetype) формат архива. |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | Определяет, будет ли ввод[`FileType`](../filetype) формат изображения. |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | Определяет, будет ли ввод[`FileType`](../filetype) это примитивный текстовый формат. |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | Определяет, являются ли два[`FileType`](../filetype) объекты одинаковые. |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | Определяет, являются ли два[`FileType`](../filetype) объекты не одинаковы. |

## Поля

| Имя | Описание |
| --- | --- |
| static [BMP](../../groupdocs.merger.domain/filetype/bmp) | Файл растрового изображения (.bmp) представляет собой файлы, используемые для хранения растровых цифровых изображений. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/image/bmp) . |
| static [BZ2](../../groupdocs.merger.domain/filetype/bz2) | Сжатый файл Bzip2 (.bz2) |
| static [CSV](../../groupdocs.merger.domain/filetype/csv) | Файл значений, разделенных запятыми (.csv), представляет собой текстовые файлы, содержащие записи данных со значениями, разделенными запятыми. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/spreadsheet/csv) . |
| static [DOC](../../groupdocs.merger.domain/filetype/doc) | Документ Microsoft Word (.doc) представляет собой документы, сгенерированные Microsoft Word или другими текстовыми редакторами в двоичном формате. Подробнее об этом формате файлов[здесь](https://docs.fileformat.com/word-processing/doc) . |
| static [DOCM](../../groupdocs.merger.domain/filetype/docm) | Файлы документов Word Open XML с поддержкой макросов (.docm) — это документы, созданные в Microsoft Word 2007 или более поздней версии с возможностью запуска макросов. Подробнее об этом формате файлов[здесь](https://docs.fileformat.com/word-processing/docm) . |
| static [DOCX](../../groupdocs.merger.domain/filetype/docx) | Документ Microsoft Word Open XML (.docx) — широко известный формат документов Microsoft Word. Представленный в 2007 году с выпуском Microsoft Office 2007, структура этого нового формата документа была изменена с простого двоичного файла на комбинацию XML и двоичных файлов. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/word-processing/docx) . |
| static [DOT](../../groupdocs.merger.domain/filetype/dot) | Файлы шаблонов документов Word (.dot) — это файлы шаблонов, созданные Microsoft Word с предварительно отформатированными настройками для создания дополнительных файлов DOC или DOCX. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/word-processing/dot) . |
| static [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Шаблон документа Word Open XML с поддержкой макросов (.dotm) представляет собой файл шаблона, созданный с помощью Microsoft Word 2007 или более поздней версии. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/word-processing/dotm) . |
| static [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Шаблон документа Word Open XML (.dotx) — это файлы шаблонов, созданные Microsoft Word для предварительно отформатированных настроек для создания дополнительных файлов DOCX. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/word-processing/dotx) . |
| static [EPUB](../../groupdocs.merger.domain/filetype/epub) | Open eBook File (.epub) — это формат файла электронной книги, который представляет собой стандартный формат цифровой публикации для издателей и потребителей. К настоящему времени этот формат стал настолько распространенным, что его поддерживают многие электронные книги и программные приложения. Узнайте больше об этом формате файла.[здесь](https://docs.fileformat.com/ebook/epub) . |
| static [ERR](../../groupdocs.merger.domain/filetype/err) | Файл журнала ошибок (.err) — это текстовый файл, содержащий сообщения об ошибках, созданные программой. Узнайте больше об этом формате файла[здесь](https://fileinfo.com/extension/err) . |
| static [GIF](../../groupdocs.merger.domain/filetype/gif) | Графический файл формата обмена (.gif) |
| static [GZ](../../groupdocs.merger.domain/filetype/gz) | Сжатый файл G-Zip (.gz) |
| static [HTML](../../groupdocs.merger.domain/filetype/html) | Файл языка гипертекстовой разметки (.html) — это расширение для веб-страниц, созданных для отображения в браузерах. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/web/html) . |
| static [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | Изображение JPEG (.jpeg) — это тип формата изображения, который сохраняется с использованием метода сжатия с потерями. Выходное изображение, полученное в результате сжатия, представляет собой компромисс между размером хранилища и качеством изображения. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/image/jpeg) . |
| static [JPG](../../groupdocs.merger.domain/filetype/jpg) | Изображение JPEG (.jpg) |
| static [MHT](../../groupdocs.merger.domain/filetype/mht) | Веб-архив MHTML (.mht) — это формат архива веб-страницы, который может быть создан рядом различных приложений. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/web/mhtml) . |
| static [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | HTML-файл MIME (.mhtml) — это формат архива веб-страницы, который может быть создан рядом различных приложений. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/web/mhtml) . |
| static [ODP](../../groupdocs.merger.domain/filetype/odp) | Презентация OpenDocument (.odp) представляет собой формат файла презентации, используемый OpenOffice.org в стандарте OASISOpen. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/presentation/odp) . |
| static [ODS](../../groupdocs.merger.domain/filetype/ods) | Электронная таблица OpenDocument (.ods) Подробнее об этом формате файла[здесь](https://docs.fileformat.com/spreadsheet/ods) . |
| static [ODT](../../groupdocs.merger.domain/filetype/odt) | Файлы текстовых документов OpenDocument (.odt) представляют собой тип документов, созданных с помощью приложений для обработки текстов, основанных на формате текстовых файлов OpenDocument. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/word-processing/odt) . |
| static [ONE](../../groupdocs.merger.domain/filetype/one) | Файлы документов OneNote (.one) создаются приложением Microsoft OneNote. OneNote позволяет собирать информацию с помощью приложения, как если бы вы использовали черновик для создания заметок. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/note-taking/one) . |
| static [OTP](../../groupdocs.merger.domain/filetype/otp) | Шаблон презентации OpenDocument (.otp) представляет собой файлы шаблонов презентаций, созданные приложениями в стандартном формате OASIS OpenDocument. Подробнее об этом формате файлов[здесь](https://docs.fileformat.com/presentation/otp) . |
| static [OTT](../../groupdocs.merger.domain/filetype/ott) | Шаблон документа OpenDocument (.ott) представляют собой шаблоны документов, созданные приложениями в соответствии со стандартным форматом OpenDocument OASIS. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/word-processing/ott) . |
| static [PDF](../../groupdocs.merger.domain/filetype/pdf) | Файл переносимого формата документа (.pdf) — это формат файла, который должен был быть введен в качестве стандарта для представления документов и других справочных материалов в формате, который не зависит от прикладного программного обеспечения, оборудования и операционной системы. Подробнее об этом файле формат[здесь](https://docs.fileformat.com/view/pdf) . |
| static [PNG](../../groupdocs.merger.domain/filetype/png) | Portable Network Graphics (.png) — это тип файла растрового изображения, в котором используется сжатие без потерь. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/image/png) . |
| static [PPS](../../groupdocs.merger.domain/filetype/pps) | Слайд-шоу PowerPoint (.pps) — это файл, созданный с помощью Microsoft PowerPoint для целей слайд-шоу. Чтение и создание файла PPS поддерживается Microsoft PowerPoint 97-2003. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/presentation/pps) . |
| static [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | Слайд-шоу PowerPoint Open XML (.ppsx) — это файл, созданный с помощью Microsoft PowerPoint 2007 и более поздних версий для целей слайд-шоу. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/presentation/ppsx) . |
| static [PPT](../../groupdocs.merger.domain/filetype/ppt) | Презентация PowerPoint (.ppt) представляет собой файл PowerPoint, состоящий из набора слайдов для отображения в виде слайд-шоу. Он указывает формат двоичного файла, используемый Microsoft PowerPoint 97-2003. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/presentation/ppt) . |
| static [PPTX](../../groupdocs.merger.domain/filetype/pptx) | Презентация PowerPoint Open XML (.pptx) — это файл презентации, созданный с помощью популярного приложения Microsoft PowerPoint. В отличие от предыдущей версии формата файла презентации PPT, которая была двоичной, формат PPTX основан на формате файла презентации Microsoft PowerPoint open XML. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/presentation/pptx) . |
| static [PS](../../groupdocs.merger.domain/filetype/ps) | Файл PostScript (.ps) |
| static [RAR](../../groupdocs.merger.domain/filetype/rar) | Архив Рошаля Сжатый файл (.rar) |
| static [RTF](../../groupdocs.merger.domain/filetype/rtf) | Форматированный текстовый файл (.rtf), представленный и задокументированный Microsoft, форматированный текстовый формат (RTF) представляет собой метод кодирования форматированного текста и графики для использования в приложениях. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/word-processing/rtf) . |
| static [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | Сжатый файл 7-Zip (.7z) |
| static [TAR](../../groupdocs.merger.domain/filetype/tar) | Объединенный файловый архив Unix (.tar) |
| static [TEX](../../groupdocs.merger.domain/filetype/tex) | Исходный документ LaTeX (.tex) — это язык, который включает в себя программирование, а также функции разметки, используемые для набора документов. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/page-description-language/tex) . |
| static [TIF](../../groupdocs.merger.domain/filetype/tif) | Файл изображения с тегами (.tif) |
| static [TIFF](../../groupdocs.merger.domain/filetype/tiff) | Формат файла изображения с тегами (.tiff) |
| static [TSV](../../groupdocs.merger.domain/filetype/tsv) | Файл значений, разделенных табуляцией (.tsv) представляет данные, разделенные табуляцией, в текстовом формате. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/spreadsheet/tsv) . |
| static [TXT](../../groupdocs.merger.domain/filetype/txt) | Файл обычного текста (.txt) представляет собой текстовый документ, содержащий обычный текст в виде строк. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/word-processing/txt) . |
| static [Unknown](../../groupdocs.merger.domain/filetype/unknown) | Представляет неизвестный тип файла. |
| static [VDX](../../groupdocs.merger.domain/filetype/vdx) | XML-файл чертежа Visio (.vdx) — это рисунок или диаграмма, созданная в Microsoft Visio, но сохраненная в формате XML с расширением .VDX. XML-файл чертежа Visio создается в программном обеспечении Visio, разработанном Microsoft. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/image/vdx) . |
| static [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Чертеж Visio с поддержкой макросов (.vsdm) — это файлы чертежей, созданные с помощью приложения Microsoft Visio, которое поддерживает макросы. Файлы VSDM представляют собой чертежи OPC/XML, похожие на VSDX, но также обеспечивающие возможность запуска макросов при открытии файла. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/image/vsdm) . |
| static [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Чертеж Visio (.vsdx) представляет формат файлов Microsoft Visio, появившийся в Microsoft Office 2013 и более поздних версиях. Он был разработан для замены двоичного формата файла .VSD, который поддерживается более ранними версиями Microsoft Visio. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/image/vsdx) . |
| static [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Файл шаблона Visio с поддержкой макросов (.vssm) — это файлы шаблона Microsoft Visio, поддерживающие поддержку макросов. Файл VSSM при открытии позволяет запускать макросы для достижения желаемого форматирования и размещения фигур на диаграмме. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/image/vssm) . |
| static [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Файл шаблона Visio (.vssx) — это наборы элементов для рисования, созданные с помощью Microsoft Visio 2013 и более поздних версий. Формат файла VSSX можно открыть с помощью Visio 2013 и более поздних версий. Файлы Visio известны тем, что представляют различные элементы рисования, такие как набор фигур, соединители, блок-схемы, макет сети, диаграммы UML, Подробнее об этом формате файла[здесь](https://docs.fileformat.com/image/vssx) . |
| static [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Шаблон чертежа Visio с поддержкой макросов (.vstm) — это файлы шаблонов, созданные с помощью Microsoft Visio и поддерживающие макросы. В отличие от файлов VSDX, файлы, созданные из шаблонов VSTM, могут запускать макросы, разработанные в коде Visual Basic для приложений (VBA). Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/image/vstm) . |
| static [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Шаблон чертежа Visio (.vstx) — это файлы шаблонов чертежей, созданные с помощью Microsoft Visio 2013 и более поздних версий. Эти файлы VSTX служат отправной точкой для создания рисунков Visio, сохраненных в виде файлов .VSDX, с макетом и настройками по умолчанию. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/image/vstx) . |
| static [VSX](../../groupdocs.merger.domain/filetype/vsx) | XML-файл Visio Stencil (.vsx) относится к наборам элементов, состоящим из рисунков и фигур, которые используются для создания диаграмм в Microsoft Visio. Файлы VSX сохраняются в формате XML и поддерживались до Visio 2013. Подробнее об этом формате файлов[здесь](https://docs.fileformat.com/image/vsx) . |
| static [VTX](../../groupdocs.merger.domain/filetype/vtx) | XML-файл шаблона Visio (.vtx) — это шаблон чертежа Microsoft Visio, который сохраняется на диск в формате XML-файла. Шаблон предназначен для предоставления файла с основными настройками, который можно использовать для создания нескольких файлов Visio с одинаковыми настройками. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/image/vtx) . |
| static [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Надстройка Excel с поддержкой макросов (.xlam) |
| static [XLS](../../groupdocs.merger.domain/filetype/xls) | Электронная таблица Excel (.xls) — это файл, который может быть создан Microsoft Excel, а также другими подобными программами для работы с электронными таблицами, такими как OpenOffice Calc или Apple Numbers. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/spreadsheet/xls) . |
| static [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | Формат файла двоичной электронной таблицы Excel (.xlsb) определяет формат двоичного файла Excel, который представляет собой набор записей и структур, определяющих содержимое книги Excel. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/spreadsheet/xlsb) . |
| static [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Электронная таблица Excel Open XML с поддержкой макросов (.xlsm) — это тип файлов электронных таблиц, поддерживающих макросы. Подробнее об этом формате файлов[здесь](https://docs.fileformat.com/spreadsheet/xlsm) . |
| static [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Электронная таблица Microsoft Excel Open XML (.xlsx) — широко известный формат документов Microsoft Excel, который был представлен корпорацией Майкрософт в выпуске Microsoft Office 2007. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/spreadsheet/xlsx) . |
| static [XLT](../../groupdocs.merger.domain/filetype/xlt) | Файл шаблона Excel (.xlt) — это файлы шаблонов, созданные с помощью Microsoft Excel, приложения для работы с электронными таблицами, входящего в состав пакета Microsoft Office. Microsoft Office 97-2003 поддерживает создание новых файлов XLT, а также их открытие. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/spreadsheet/xlt) . |
| static [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Шаблон электронной таблицы Excel Open XML с поддержкой макросов (.xltm) представляет файлы, созданные Microsoft Excel, как файлы шаблонов с поддержкой макросов. Файлы XLTM аналогичны XLTX по структуре, за исключением того, что последний не поддерживает создание файлов шаблонов с макросами. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/spreadsheet/xltm) . |
| static [XLTX](../../groupdocs.merger.domain/filetype/xltx) | Файлы шаблонов электронных таблиц Excel Open XML (.xltx) основаны на спецификациях формата файлов Office OpenXML. Он используется для создания стандартного файла шаблона, который можно использовать для создания файлов XLSX с теми же настройками, что и в файле XLTX. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/spreadsheet/xltx) . |
| static [XPS](../../groupdocs.merger.domain/filetype/xps) | Файл спецификации XML Paper (.xps) представляет собой файлы макета страницы, основанные на спецификациях XML Paper, созданных Microsoft. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/page-description-language/xps) . |
| static [ZIP](../../groupdocs.merger.domain/filetype/zip) | Заархивированный файл (.zip) |

### Примечания

**Узнать больше**

* Узнайте больше о форматах файлов, поддерживаемых GroupDocs.Merge: [Полный список поддерживаемых форматов документов](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* Узнайте больше о том, как получить поддерживаемые типы файлов в коде: [Как получить поддерживаемые форматы файлов в коде](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### Смотрите также

* пространство имен [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* сборка [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
