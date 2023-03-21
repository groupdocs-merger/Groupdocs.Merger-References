---
title: FileType
second_title: .NET API Başvurusu için GroupDocs.Merger
description: Dosya türünü temsil eder. Tarafından desteklenen tüm dosya türlerinin listesini elde etmek için yöntemler sağlar.GroupDocs.Birleşme  dosya türünü uzantıya göre algıla vb.
type: docs
weight: 100
url: /tr/net/groupdocs.merger.domain/filetype/
---
## FileType class

Dosya türünü temsil eder. Tarafından desteklenen tüm dosya türlerinin listesini elde etmek için yöntemler sağlar.**GroupDocs.Birleşme** , dosya türünü uzantıya göre algıla vb.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | Dosya adı soneki ("." noktası dahil) ör. ".doc". |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | Dosya türü adı, örneğin "Microsoft Word Belgesi". |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | Dosya uzantısını dosya türüyle eşler. |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | Mevcut olup olmadığını belirler.[`FileType`](../filetype) belirtilenle aynı[`FileType`](../filetype) nesne. |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | Mevcut olup olmadığını belirler.[`FileType`](../filetype) belirtilen nesneyle aynı. |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | Mevcut için hash kodunu döndürür[`FileType`](../filetype) nesne. |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | Desteklenen dosya türlerini alır |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | Girdi olup olmadığını belirler[`FileType`](../filetype) arşiv biçimidir. |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | Girdi olup olmadığını belirler[`FileType`](../filetype) resim formatıdır. |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | Girdi olup olmadığını belirler[`FileType`](../filetype) ilkel metin biçimidir. |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | İki olup olmadığını belirler[`FileType`](../filetype) nesneler aynıdır. |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | İki olup olmadığını belirler[`FileType`](../filetype) nesneler aynı değil. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| static [BMP](../../groupdocs.merger.domain/filetype/bmp) | Bitmap Görüntü Dosyası (.bmp), bitmap dijital görüntüleri depolamak için kullanılan dosyaları temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/image/bmp) . |
| static [BZ2](../../groupdocs.merger.domain/filetype/bz2) | Bzip2 Sıkıştırılmış Dosya (.bz2) |
| static [CSV](../../groupdocs.merger.domain/filetype/csv) | Virgülle Ayrılmış Değerler Dosyası (.csv), virgülle ayrılmış değerler içeren veri kayıtlarını içeren düz metin dosyalarını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/spreadsheet/csv) . |
| static [DOC](../../groupdocs.merger.domain/filetype/doc) | Microsoft Word Belgesi (.doc), Microsoft Word veya diğer kelime işlem belgeleri tarafından ikili dosya biçiminde oluşturulan belgeleri temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/word-processing/doc) . |
| static [DOCM](../../groupdocs.merger.domain/filetype/docm) | Word Open XML Macro-Enabled Document (.docm) dosyaları, Microsoft Word 2007 veya daha yüksek sürümde oluşturulmuş ve makro çalıştırabilen belgelerdir. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/word-processing/docm) . |
| static [DOCX](../../groupdocs.merger.domain/filetype/docx) | Microsoft Word Açık XML Belgesi (.docx), Microsoft Word belgeleri için iyi bilinen bir biçimdir. 2007'den itibaren Microsoft Office 2007'nin piyasaya sürülmesiyle tanıtılan bu yeni Belge biçiminin yapısı, düz ikiliden XML ve ikili dosyaların birleşimine değiştirildi. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/word-processing/docx) . |
| static [DOT](../../groupdocs.merger.domain/filetype/dot) | Word Belge Şablonu (.dot) dosyaları, daha fazla DOC veya DOCX dosyası oluşturmak için önceden biçimlendirilmiş ayarlara sahip olmak üzere Microsoft Word tarafından oluşturulan şablon dosyalarıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/word-processing/dot) . |
| static [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Word Açık XML Makro Etkin Belge Şablonu (.dotm), Microsoft Word 2007 veya üstü ile oluşturulan şablon dosyasını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/word-processing/dotm) . |
| static [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Word Açık XML Belge Şablonu (.dotx), daha fazla DOCX dosyası oluşturmak için önceden biçimlendirilmiş ayarlara sahip olmak üzere Microsoft Word tarafından oluşturulan şablon dosyalarıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/word-processing/dotx) . |
| static [EPUB](../../groupdocs.merger.domain/filetype/epub) | Açık eKitap Dosyası (.epub), yayıncılar ve tüketiciler için standart bir dijital yayın biçimi sağlayan bir e-kitap dosyası biçimidir. Format şimdiye kadar o kadar yaygın hale geldi ki birçok e-okuyucu ve yazılım uygulaması tarafından destekleniyor. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/ebook/epub) . |
| static [ERR](../../groupdocs.merger.domain/filetype/err) | Hata Günlük Dosyası (.err), bir program tarafından oluşturulan hata mesajlarını içeren bir metin dosyasıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://fileinfo.com/extension/err) . |
| static [GIF](../../groupdocs.merger.domain/filetype/gif) | Grafik Değişim Formatı Dosyası (.gif) |
| static [GZ](../../groupdocs.merger.domain/filetype/gz) | G-Zip Sıkıştırılmış Dosya (.gz) |
| static [HTML](../../groupdocs.merger.domain/filetype/html) | Köprü Metni Biçimlendirme Dili Dosyası (.html), tarayıcılarda görüntülenmek üzere oluşturulan web sayfalarının uzantısıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/web/html) . |
| static [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | JPEG Görüntüsü (.jpeg), kayıplı sıkıştırma yöntemi kullanılarak kaydedilen bir tür görüntü biçimidir. Çıktı görüntüsü, sıkıştırmanın bir sonucu olarak, depolama boyutu ile görüntü kalitesi arasında bir değiş tokuştur. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/image/jpeg) . |
| static [JPG](../../groupdocs.merger.domain/filetype/jpg) | JPEG Resmi (.jpg) |
| static [MHT](../../groupdocs.merger.domain/filetype/mht) | MHTML Web Arşivi (.mht), bir dizi farklı uygulama tarafından oluşturulabilen bir web sayfası arşiv biçimidir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/web/mhtml) . |
| static [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | MIME HTML Dosyası (.mhtml), bir dizi farklı uygulama tarafından oluşturulabilen bir web sayfası arşiv biçimidir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/web/mhtml) . |
| static [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument Presentation (.odp), OpenOffice.org tarafından OASISOpen standardında kullanılan sunum dosyası formatını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/presentation/odp) . |
| static [ODS](../../groupdocs.merger.domain/filetype/ods) | OpenDocument Elektronik Tablosu (.ods) Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/spreadsheet/ods) . |
| static [ODT](../../groupdocs.merger.domain/filetype/odt) | OpenDocument Metin Belgesi (.odt) dosyaları, OpenDocument Metin Dosyası biçimini temel alan kelime işlem uygulamalarıyla oluşturulan belge türüdür. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/word-processing/odt) . |
| static [ONE](../../groupdocs.merger.domain/filetype/one) | OneNote Document (.one) dosyaları Microsoft OneNote uygulaması tarafından oluşturulur. OneNote, not almak için taslak defterinizi kullanıyormuşsunuz gibi uygulamayı kullanarak bilgi toplamanıza olanak tanır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/note-taking/one) . |
| static [OTP](../../groupdocs.merger.domain/filetype/otp) | OpenDocument Sunum Şablonu (.otp), uygulamalar tarafından OASIS OpenDocument standart formatında oluşturulan sunum şablonu dosyalarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/presentation/otp) . |
| static [OTT](../../groupdocs.merger.domain/filetype/ott) | OpenDocument Belge Şablonu (.ott), OASIS'in OpenDocument standart formatına uygun olarak uygulamalar tarafından oluşturulan şablon belgeleri temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/word-processing/ott) . |
| static [PDF](../../groupdocs.merger.domain/filetype/pdf) | Taşınabilir Belge Biçimi Dosyası (.pdf), belgelerin ve diğer referans malzemelerinin uygulama yazılımı, donanım ve İşletim Sisteminden bağımsız bir biçimde temsil edilmesi için bir standart olarak sunulan bir dosya biçimidir. Bu dosya hakkında daha fazla bilgi edinin biçim[Burada](https://docs.fileformat.com/view/pdf) . |
| static [PNG](../../groupdocs.merger.domain/filetype/png) | Taşınabilir Ağ Grafiği (.png), kayıpsız sıkıştırma kullanan bir tür raster görüntü dosyası formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/image/png) . |
| static [PPS](../../groupdocs.merger.domain/filetype/pps) | PowerPoint Slayt Gösterisi (.pps), Slayt Gösterisi amacıyla Microsoft PowerPoint kullanılarak oluşturulan bir dosyadır. PPS dosyası okuma ve oluşturma, Microsoft PowerPoint 97-2003 tarafından desteklenir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/presentation/pps) . |
| static [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | PowerPoint Açık XML Slayt Gösterisi (.ppsx), Slayt Gösterisi amacıyla Microsoft PowerPoint 2007 ve üzeri kullanılarak oluşturulan bir dosyadır. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/presentation/ppsx) . |
| static [PPT](../../groupdocs.merger.domain/filetype/ppt) | PowerPoint Sunumu (.ppt), SlideShow olarak görüntülemek için bir slayt koleksiyonundan oluşan PowerPoint dosyasını temsil eder. Microsoft PowerPoint 97-2003 tarafından kullanılan İkili Dosya Biçimini belirtir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/presentation/ppt) . |
| static [PPTX](../../groupdocs.merger.domain/filetype/pptx) | PowerPoint Açık XML Sunumu (.pptx), popüler Microsoft PowerPoint uygulamasıyla oluşturulmuş bir sunum dosyasıdır. İkili olan sunum dosyası biçimi PPT'nin önceki sürümünün aksine, PPTX biçimi Microsoft PowerPoint açık XML sunum dosyası biçimini temel alır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/presentation/pptx) . |
| static [PS](../../groupdocs.merger.domain/filetype/ps) | PostScript Dosyası (.ps) |
| static [RAR](../../groupdocs.merger.domain/filetype/rar) | Roshal ARchive Sıkıştırılmış Dosya (.rar) |
| static [RTF](../../groupdocs.merger.domain/filetype/rtf) | Microsoft tarafından tanıtılan ve belgelenen Zengin Metin Biçimi Dosyası (.rtf), Zengin Metin Biçimi (RTF), uygulamalarda kullanılmak üzere biçimlendirilmiş metin ve grafikleri kodlama yöntemini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/word-processing/rtf) . |
| static [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | 7-Zip Sıkıştırılmış Dosya (.7z) |
| static [TAR](../../groupdocs.merger.domain/filetype/tar) | Birleştirilmiş Unix Dosya Arşivi (.tar) |
| static [TEX](../../groupdocs.merger.domain/filetype/tex) | LaTeX Kaynak Belgesi (.tex), belgeleri dizmek için kullanılan programlama ve biçimlendirme özelliklerinden oluşan bir dildir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/page-description-language/tex) . |
| static [TIF](../../groupdocs.merger.domain/filetype/tif) | Etiketli Resim Dosyası (.tif) |
| static [TIFF](../../groupdocs.merger.domain/filetype/tiff) | Etiketli Görüntü Dosyası Formatı (.tiff) |
| static [TSV](../../groupdocs.merger.domain/filetype/tsv) | Sekmeyle Ayrılmış Değerler Dosyası (.tsv), düz metin biçiminde sekmelerle ayrılmış verileri temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/spreadsheet/tsv) . |
| static [TXT](../../groupdocs.merger.domain/filetype/txt) | Düz Metin Dosyası (.txt), satır biçiminde düz metin içeren bir metin belgesini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/word-processing/txt) . |
| static [Unknown](../../groupdocs.merger.domain/filetype/unknown) | Bilinmeyen dosya türünü temsil eder. |
| static [VDX](../../groupdocs.merger.domain/filetype/vdx) | Visio Çizim XML Dosyası (.vdx), Microsoft Visio'da oluşturulan, ancak XML biçiminde kaydedilen ve .VDX uzantılı bir çizim veya grafiktir. Microsoft tarafından geliştirilen Visio yazılımında bir Visio çizim XML dosyası oluşturulur. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/image/vdx) . |
| static [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Visio Makro Etkin Çizim (.vsdm), makroları destekleyen Microsoft Visio uygulamasıyla oluşturulan çizim dosyalarıdır. VSDM dosyaları, VSDX'e benzer OPC/XML çizimleridir, ancak dosya açıldığında makro çalıştırma özelliği de sağlar. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/image/vsdm) . |
| static [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Visio Çizimi (.vsdx), Microsoft Office 2013'ten itibaren sunulan Microsoft Visio dosya formatını temsil eder. Microsoft Visio'nun önceki sürümleri tarafından desteklenen ikili dosya biçimi .VSD'nin yerini almak üzere geliştirilmiştir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/image/vsdx) . |
| static [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Visio Macro-Enabled Stencil File (.vssm), makro desteği sağlayan Microsoft Visio Stencil dosyalarıdır. Açıldığında bir VSSM dosyası, bir şemada şekillerin istenen biçimlendirmesini ve yerleşimini elde etmek için makroların çalıştırılmasına izin verir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/image/vssm) . |
| static [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Visio Kalıp Dosyası (.vssx), Microsoft Visio 2013 ve üstü ile oluşturulan çizim kalıplarıdır. VSSX dosya formatı, Visio 2013 ve üstü ile açılabilir. Visio dosyaları, şekiller koleksiyonu, bağlayıcılar, akış şemaları, ağ düzeni, UML diyagramları, gibi çeşitli çizim öğelerini temsil etmesiyle bilinir. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/image/vssx) . |
| static [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Visio Makro Etkin Çizim Şablonu (.vstm), Microsoft Visio ile oluşturulan ve makroları destekleyen şablon dosyalarıdır. VSDX dosyalarının aksine, VSTM şablonlarından oluşturulan dosyalar, Visual Basic for Applications (VBA) kodunda geliştirilen makroları çalıştırabilir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/image/vstm) . |
| static [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Visio Çizim Şablonu (.vstx), Microsoft Visio 2013 ve üzeri sürümlerle oluşturulan çizim şablonu dosyalarıdır. Bu VSTX dosyaları, varsayılan düzen ve ayarlarla .VSDX dosyaları olarak kaydedilen Visio çizimleri oluşturmak için başlangıç noktası sağlar. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/image/vstx) . |
| static [VSX](../../groupdocs.merger.domain/filetype/vsx) | Visio Kalıp XML Dosyası (.vsx), Microsoft Visio'da diyagram oluşturmak için kullanılan çizimlerden ve şekillerden oluşan kalıpları ifade eder. VSX dosyaları XML dosya biçiminde kaydedilir ve Visio 2013'e kadar desteklenir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/image/vsx) . |
| static [VTX](../../groupdocs.merger.domain/filetype/vtx) | Visio Şablonu XML Dosyası (.vtx), diske XML dosya biçiminde kaydedilen bir Microsoft Visio çizim şablonudur. Şablonun amacı, aynı ayarlara sahip birden çok Visio dosyası oluşturmak için kullanılabilecek temel ayarlara sahip bir dosya sağlamaktır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/image/vtx) . |
| static [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Excel Makro Etkin Eklenti (.xlam) |
| static [XLS](../../groupdocs.merger.domain/filetype/xls) | Excel Elektronik Tablosu (.xls), Microsoft Excel'in yanı sıra OpenOffice Calc veya Apple Numbers gibi diğer benzer elektronik tablo programları tarafından oluşturulabilen bir dosyadır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/spreadsheet/xls) . |
| static [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | Excel İkili Hesap Tablosu (.xlsb) dosya formatı, Excel çalışma kitabı içeriğini belirten bir kayıt ve yapı koleksiyonu olan Excel İkili Dosya Formatını belirtir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/spreadsheet/xlsb) . |
| static [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Açık XML Makro Etkin Elektronik Tablo (.xlsm), makroları destekleyen bir Elektronik Tablo dosyası türüdür. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/spreadsheet/xlsm) . |
| static [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Açık XML Elektronik Tablosu (.xlsx), Microsoft tarafından Microsoft Office 2007'nin piyasaya sürülmesiyle tanıtılan, Microsoft Excel belgeleri için iyi bilinen bir biçimdir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/spreadsheet/xlsx) . |
| static [XLT](../../groupdocs.merger.domain/filetype/xlt) | Excel Şablon Dosyası (.xlt), Microsoft Office paketinin bir parçası olarak gelen bir elektronik tablo uygulaması olan Microsoft Excel ile oluşturulan şablon dosyalarıdır. Microsoft Office 97-2003, yeni XLT dosyaları oluşturmayı ve bunları açmayı destekledi. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/spreadsheet/xlt) . |
| static [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Excel Açık XML Makro Etkin Elektronik Tablo Şablonu (.xltm), Microsoft Excel tarafından Makro etkin şablon dosyaları olarak oluşturulan dosyaları temsil eder. XLTM dosyaları, daha sonra makrolarla şablon dosyaları oluşturmayı desteklememesi dışında yapı olarak XLTX'e benzer. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/spreadsheet/xltm) . |
| static [XLTX](../../groupdocs.merger.domain/filetype/xltx) | Excel Açık XML Elektronik Tablo Şablonu (.xltx) dosyaları, Office OpenXML dosya biçimi belirtimlerini temel alır. XLTX dosyasında belirtilen ayarların aynısını sergileyen XLSX dosyaları oluşturmak için kullanılabilecek standart bir şablon dosyası oluşturmak için kullanılır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/spreadsheet/xltx) . |
| static [XPS](../../groupdocs.merger.domain/filetype/xps) | XML Kağıt Belirtim Dosyası (.xps), Microsoft tarafından oluşturulan XML Kağıt Belirtimlerini temel alan sayfa düzeni dosyalarını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/page-description-language/xps) . |
| static [ZIP](../../groupdocs.merger.domain/filetype/zip) | Sıkıştırılmış Dosya (.zip) |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs tarafından desteklenen dosya biçimleri hakkında daha fazla bilgi edinin.Merger: [Desteklenen belge biçimlerinin tam listesi](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* Kodda desteklenen dosya türlerini alma hakkında daha fazla bilgi edinin: [Kodda desteklenen dosya biçimleri nasıl elde edilir](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### Ayrıca bakınız

* ad alanı [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* toplantı [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
