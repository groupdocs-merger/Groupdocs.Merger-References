---
title: "FileType"
second_title: "GroupDocs.Merger Node.js için Java API Referansı"
description: "Dosya türünü temsil eder."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.merger.domain/filetype/
---
**Inheritance:**
java.lang.Object
```
public final class FileType
```

Dosya tipini temsil eder. **GroupDocs.Merger** tarafından desteklenen tüm dosya tiplerinin listesini elde etmek, uzantıya göre dosya tipini tespit etmek vb. yöntemler sağlar.

--------------------

**Learn more**

 *  Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats][]
 *  Learn more about getting supported file types in code: [How to get supported file formats in code][]


[Full list of supported document formats]: https://docs.groupdocs.com/display/mergernet/Supported+Document+Types
[How to get supported file formats in code]: https://docs.groupdocs.com/display/mergernet/Get+supported+file+types
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Unknown](#Unknown) | Bilinmeyen dosya türünü temsil eder. |
| [ZIP](#ZIP) | Sıkıştırılmış Dosya (.zip) |
| [SevenZ](#SevenZ) | 7-Zip Sıkıştırılmış Dosya (.7z) |
| [TAR](#TAR) | Konsolide Unix Dosya Arşivi (.tar) |
| [RAR](#RAR) | Roshal ARchive Sıkıştırılmış Dosya (.rar) |
| [VSSX](#VSSX) | Visio Stencil File (.vssx) Microsoft Visio 2013 ve üzeri sürümlerle oluşturulan çizim şablonlarıdır. |
| [VSDX](#VSDX) | Visio Drawing (.vsdx) Microsoft Office 2013'ten itibaren tanıtılan Microsoft Visio dosya formatını temsil eder. |
| [VSDM](#VSDM) | Visio Macro-Enabled Drawing (.vsdm) makroları destekleyen Microsoft Visio uygulamasıyla oluşturulan çizim dosyalarıdır. |
| [VSTX](#VSTX) | Visio Drawing Template (.vstx) Microsoft Visio 2013 ve üzeri sürümlerle oluşturulan çizim şablon dosyalarıdır. |
| [VSTM](#VSTM) | Visio Macro-Enabled Drawing Template (.vstm) makroları destekleyen Microsoft Visio ile oluşturulan şablon dosyalarıdır. |
| [VSSM](#VSSM) | Visio Macro-Enabled Stencil File (.vssm) makroları destekleyen Microsoft Visio Stencil dosyalarıdır. |
| [VSX](#VSX) | Visio Stencil XML File (.vsx) çizimler ve şekillerden oluşan ve Microsoft Visio'da diyagram oluşturmak için kullanılan şablonları ifade eder. |
| [VTX](#VTX) | Visio Template XML File (.vtx) XML dosya formatında diske kaydedilen bir Microsoft Visio çizim şablonudur. |
| [VDX](#VDX) | Visio Drawing XML File (.vdx) Microsoft Visio'da oluşturulan bir çizim veya grafik olup, XML formatında kaydedildiğinde .VDX uzantısına sahiptir. |
| [EPUB](#EPUB) | Open eBook File (.epub) yayıncılar ve tüketiciler için standart bir dijital yayın formatı sağlayan bir e-kitap dosya formatıdır. |
| [BMP](#BMP) | Bitmap Image File (.bmp) bitmap dijital görüntüleri depolamak için kullanılan dosyaları temsil eder. |
| [JPG](#JPG) | JPEG Görüntüsü (.jpg) |
| [JPEG](#JPEG) | JPEG Image (.jpeg) kayıplı sıkıştırma yöntemiyle kaydedilen bir görüntü formatı türüdür. |
| [PNG](#PNG) | Portable Network Graphic (.png) kayıpsız sıkıştırma kullanan bir raster görüntü dosya formatı türdür. |
| [PS](#PS) | PostScript Dosyası (.ps) |
| [TIF](#TIF) | Tagged Image File (.tif) |
| [TIFF](#TIFF) | Tagged Image File Format (.tiff) |
| [GIF](#GIF) | Graphical Interchange Format File (.gif) |
| [SVG](#SVG) | Scalable Vector Graphics File (.svg) |
| [SVGZ](#SVGZ) | Scalable Vector Graphics Compressed File (.svgz) |
| [EMF](#EMF) | Windows Gelişmiş Metafile (.emf) |
| [EMZ](#EMZ) | Windows Sıkıştırılmış Gelişmiş Metafile (.emz) |
| [HTML](#HTML) | Hypertext Markup Language Dosyası (.html), tarayıcılarda görüntülenmek üzere oluşturulan web sayfaları için uzantıdır. |
| [MHT](#MHT) | MHTML Web Arşivi (.mht), çeşitli farklı uygulamalar tarafından oluşturulabilen bir web sayfası arşiv formatıdır. |
| [MHTML](#MHTML) | MIME HTML Dosyası (.mhtml), çeşitli farklı uygulamalar tarafından oluşturulabilen bir web sayfası arşiv formatıdır. |
| [ONE](#ONE) | OneNote Belgesi (.one) dosyaları Microsoft OneNote uygulaması tarafından oluşturulur. |
| [PDF](#PDF) | Portable Document Format Dosyası (.pdf), belgelerin ve diğer referans materyallerinin uygulama yazılımı, donanım ve işletim sisteminden bağımsız bir formatta temsil edilmesi için standart olarak tanıtılan bir dosya formatıdır. |
| [XPS](#XPS) | XML Paper Specification Dosyası (.xps), Microsoft tarafından oluşturulan XML Paper Specification tabanlı sayfa düzeni dosyalarını temsil eder. |
| [TEX](#TEX) | LaTeX Kaynak Belgesi (.tex), programlama ve işaretleme özelliklerini içeren, belgeleri biçimlendirmek için kullanılan bir dildir. |
| [PPT](#PPT) | PowerPoint Sunumu (.ppt), slayt gösterisi olarak görüntülenmek üzere bir dizi slayttan oluşan PowerPoint dosyasını temsil eder. |
| [PPTX](#PPTX) | PowerPoint Open XML Sunumu (.pptx), popüler Microsoft PowerPoint uygulamasıyla oluşturulan bir sunum dosyasıdır. |
| [PPS](#PPS) | PowerPoint Slayt Gösterisi (.pps), Microsoft PowerPoint kullanılarak slayt gösterisi amacıyla oluşturulan bir dosyadır. |
| [PPSX](#PPSX) | PowerPoint Open XML Slayt Gösterisi (.ppsx), Microsoft PowerPoint 2007 ve üzeri sürümlerle slayt gösterisi amacıyla oluşturulan bir dosyadır. |
| [ODP](#ODP) | OpenDocument Sunumu (.odp), OpenOffice.org tarafından OASIS Open standardında kullanılan sunum dosya formatını temsil eder. |
| [OTP](#OTP) | OpenDocument Sunum Şablonu (.otp), OASIS OpenDocument standart formatında uygulamalar tarafından oluşturulan sunum şablonu dosyalarını temsil eder. |
| [XLS](#XLS) | Excel Çalışma Sayfası (.xls), Microsoft Excel'in yanı sıra OpenOffice Calc veya Apple Numbers gibi benzer hesap tablosu programlarıyla da oluşturulabilen bir dosyadır. |
| [XLSX](#XLSX) | Microsoft Excel Open XML Çalışma Sayfası (.xlsx), Microsoft Office 2007'nin yayınlanmasıyla Microsoft tarafından tanıtılan, Microsoft Excel belgeleri için yaygın bir formattır. |
| [XLSM](#XLSM) | Excel Open XML Makro Etkin Çalışma Sayfası (.xlsm), makroları destekleyen bir tür çalışma sayfası dosyasıdır. |
| [XLSB](#XLSB) | Excel Binary Çalışma Sayfası (.xlsb) dosya formatı, Excel çalışma kitabı içeriğini tanımlayan kayıt ve yapılar koleksiyonunu içeren Excel Binary Dosya Formatını belirtir. |
| [CSV](#CSV) | Virgülle Ayrılmış Değerler Dosyası (.csv), virgülle ayrılmış değerler içeren veri kayıtlarını barındıran düz metin dosyalarını temsil eder. |
| [TSV](#TSV) | Sekme Ayrılmış Değerler Dosyası (.tsv), sekmelerle ayrılmış verileri içeren düz metin formatındaki dosyaları temsil eder. |
| [ODS](#ODS) | OpenDocument Çalışma Sayfası (.ods). |
| [XLTM](#XLTM) | Excel Open XML Makro Etkin Çalışma Sayfası Şablonu (.xltm), Microsoft Excel tarafından makro etkin şablon dosyaları olarak oluşturulan dosyaları temsil eder. |
| [XLTX](#XLTX) | Excel Open XML Çalışma Sayfası Şablonu (.xltx) dosyaları, Office OpenXML dosya formatı özelliklerine dayanır. |
| [XLT](#XLT) | Excel Şablon Dosyası (.xlt), Microsoft Office paketinin bir parçası olan bir hesap tablosu uygulaması Microsoft Excel ile oluşturulan şablon dosyalarıdır. |
| [XLAM](#XLAM) | Excel Makro Etkin Eklentisi (.xlam). |
| [DOC](#DOC) | Microsoft Word Belgesi (.doc) Microsoft Word veya diğer kelime işlem programları tarafından ikili dosya formatında oluşturulan belgeleri temsil eder. |
| [DOCX](#DOCX) | Microsoft Word Open XML Belgesi (.docx), Microsoft Word belgeleri için yaygın bilinen bir formattır. |
| [DOCM](#DOCM) | Word Open XML Makro Etkin Belgesi (.docm) dosyaları, makroları çalıştırma yeteneğine sahip Microsoft Word 2007 veya daha yeni sürümlerle oluşturulan belgelerdir. |
| [DOT](#DOT) | Word Belge Şablonu (.dot) dosyaları, daha sonraki DOC veya DOCX dosyalarının oluşturulması için önceden biçimlendirilmiş ayarlara sahip olmak amacıyla Microsoft Word tarafından oluşturulan şablon dosyalarıdır. |
| [DOTX](#DOTX) | Word Open XML Belge Şablonu (.dotx), daha sonraki DOCX dosyalarının oluşturulması için önceden biçimlendirilmiş ayarlara sahip olmak amacıyla Microsoft Word tarafından oluşturulan şablon dosyalarıdır. |
| [DOTM](#DOTM) | Word Open XML Makro Etkin Belge Şablonu (.dotm), Microsoft Word 2007 veya daha yeni sürümlerle oluşturulan şablon dosyasını temsil eder. |
| [RTF](#RTF) | Rich Text Format Dosyası (.rtf), Microsoft tarafından tanıtılmış ve belgelenmiştir; Rich Text Format (RTF), uygulamalar içinde kullanılmak üzere biçimlendirilmiş metin ve grafiklerin kodlanma yöntemini temsil eder. |
| [TXT](#TXT) | Düz Metin Dosyası (.txt), satır biçiminde düz metin içeren bir metin belgesini temsil eder. |
| [ERR](#ERR) | Hata Günlüğü Dosyası (.err), bir program tarafından oluşturulan hata mesajlarını içeren bir metin dosyasıdır. |
| [ODT](#ODT) | OpenDocument Metin Belgesi (.odt) dosyaları, OpenDocument Metin Dosyası formatına dayalı kelime işlem uygulamalarıyla oluşturulan belge türleridir. |
| [OTT](#OTT) | OpenDocument Belge Şablonu (.ott), OASIS'in OpenDocument standart formatına uygun olarak uygulamalar tarafından oluşturulan şablon belgeleri temsil eder. |
| [WAV](#WAV) | WAV, WAVE (Waveform Audio File Format) olarak bilinir, dijital ses dosyalarını depolamak için Microsoft'un Resource Interchange File Format (RIFF) spesifikasyonunun bir alt kümesidir. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Dosya türü adı örn. |
| [getExtension()](#getExtension--) | Dosya adı son eki (nokta "." dahil) örn. |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Dosya uzantısını dosya türüne eşler. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Desteklenen dosya türlerini alır |
| [equals(FileType other)](#equals-com.groupdocs.merger.domain.FileType-) | Mevcut [FileType](../../com.groupdocs.merger.domain/filetype) nesnesinin belirtilen [FileType](../../com.groupdocs.merger.domain/filetype) nesnesiyle aynı olup olmadığını belirler. |
| [equals(Object obj)](#equals-java.lang.Object-) | Mevcut [FileType](../../com.groupdocs.merger.domain/filetype) nesnesinin belirtilen nesneyle aynı olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Mevcut [FileType](../../com.groupdocs.merger.domain/filetype) nesnesi için hash kodunu döndürür. |
| [op_Equality(FileType left, FileType right)](#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | İki [FileType](../../com.groupdocs.merger.domain/filetype) nesnesinin aynı olup olmadığını belirler. |
| [op_Inequality(FileType left, FileType right)](#op-Inequality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | İki [FileType](../../com.groupdocs.merger.domain/filetype) nesnesinin aynı olmama durumunu belirler. |
| [toString()](#toString--) | Mevcut nesneyi temsil eden bir dize döndürür. |
| [isText(FileType fileType)](#isText-com.groupdocs.merger.domain.FileType-) | Girdi [FileType](../../com.groupdocs.merger.domain/filetype) nesnesinin ilkel metin formatı olup olmadığını belirler. |
| [isArchive(FileType fileType)](#isArchive-com.groupdocs.merger.domain.FileType-) | Girdi [FileType](../../com.groupdocs.merger.domain/filetype) nesnesinin arşiv formatı olup olmadığını belirler. |
| [isImage(FileType fileType)](#isImage-com.groupdocs.merger.domain.FileType-) | Girdi [FileType](../../com.groupdocs.merger.domain/filetype) nesnesinin ilkel metin formatı olup olmadığını belirler. |
| [isAudio(FileType fileType)](#isAudio-com.groupdocs.merger.domain.FileType-) | Giriş [FileType](../../com.groupdocs.merger.domain/filetype) dosyasının ses formatı olup olmadığını belirler. |
| [getBase(FileType fileType)](#getBase-com.groupdocs.merger.domain.FileType-) |  |
### Unknown {#Unknown}
```
public static final FileType Unknown
```


Bilinmeyen dosya türünü temsil eder.

### ZIP {#ZIP}
```
public static FileType ZIP
```


Sıkıştırılmış Dosya (.zip)

### SevenZ {#SevenZ}
```
public static final FileType SevenZ
```


7-Zip Sıkıştırılmış Dosya (.7z)

### TAR {#TAR}
```
public static final FileType TAR
```


Konsolide Unix Dosya Arşivi (.tar)

### RAR {#RAR}
```
public static final FileType RAR
```


Roshal ARchive Sıkıştırılmış Dosya (.rar)

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Visio Stencil File (.vssx), Microsoft Visio 2013 ve üzeri sürümlerle oluşturulan çizim şablonlarıdır. VSSX dosya formatı Visio 2013 ve üzeri sürümlerle açılabilir. Visio dosyaları, şekil koleksiyonları, bağlayıcılar, akış şemaları, ağ düzeni, UML diyagramları gibi çeşitli çizim öğelerinin temsil edilmesiyle bilinir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/image/vssx

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Visio Drawing (.vsdx), Microsoft Office 2013'ten itibaren tanıtılan Microsoft Visio dosya formatını temsil eder. Önceki Microsoft Visio sürümlerinin desteklediği ikili dosya formatı .VSD'nin yerine geçecek şekilde geliştirilmiştir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/image/vsdx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Visio Macro-Enabled Drawing (.vsdm), makroları destekleyen Microsoft Visio uygulamasıyla oluşturulan çizim dosyalarıdır. VSDM dosyaları, VSDX'ye benzer OPC/XML çizimleridir, ancak dosya açıldığında makroları çalıştırma yeteneği de sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/image/vsdm

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Visio Drawing Template (.vstx), Microsoft Visio 2013 ve üzeri sürümlerle oluşturulan çizim şablon dosyalarıdır. Bu VSTX dosyaları, varsayılan düzen ve ayarlarla .VSDX dosyaları olarak kaydedilen Visio çizimleri oluşturmak için bir başlangıç noktası sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Visio Macro-Enabled Drawing Template (.vstm), makroları destekleyen Microsoft Visio ile oluşturulan şablon dosyalarıdır. VSDX dosyalarının aksine, VSTM şablonlarından oluşturulan dosyalar Visual Basic for Applications (VBA) kodunda geliştirilen makroları çalıştırabilir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Visio Macro-Enabled Stencil File (.vssm), makroları destekleyen Microsoft Visio Stencil dosyalarıdır. Bir VSSM dosyası açıldığında, diyagramdaki şekillerin istenen biçimlendirilmesi ve yerleştirilmesi için makroları çalıştırmaya izin verir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Visio Stencil XML File (.vsx), Microsoft Visio'da diyagram oluşturmak için kullanılan çizimler ve şekillerden oluşan şablonları ifade eder. VSX dosyaları XML dosya formatında kaydedilir ve Visio 2013'e kadar desteklenmiştir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Visio Template XML File (.vtx), XML dosya formatında diske kaydedilen bir Microsoft Visio çizim şablonudur. Şablon, aynı ayarlara sahip birden fazla Visio dosyası oluşturmak için kullanılabilecek temel ayarları içeren bir dosya sağlamayı amaçlar. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/image/vtx

### VDX {#VDX}
```
public static final FileType VDX
```


Visio Drawing XML File (.vdx), Microsoft Visio'da oluşturulan ancak .VDX uzantısına sahip XML formatında kaydedilen bir çizim veya grafiktir. Visio çizim XML dosyası, Microsoft tarafından geliştirilen Visio yazılımında oluşturulur. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Open eBook File (.epub), yayıncılar ve tüketiciler için standart bir dijital yayın formatı sağlayan bir e-kitap dosya formatıdır. Bu format artık o kadar yaygın ki birçok e-okuyucu ve yazılım uygulaması tarafından desteklenmektedir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/ebook/epub

### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap Image File (.bmp), bitmap dijital görüntüleri depolamak için kullanılan dosyaları temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/image/bmp

### JPG {#JPG}
```
public static final FileType JPG
```


JPEG Görüntüsü (.jpg)

### JPEG {#JPEG}
```
public static final FileType JPEG
```


JPEG Image (.jpeg), kayıplı sıkıştırma yöntemiyle kaydedilen bir görüntü formatıdır. Sıkıştırmanın sonucu olarak ortaya çıkan çıktı görüntüsü, depolama boyutu ile görüntü kalitesi arasında bir denge sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/image/jpeg

### PNG {#PNG}
```
public static final FileType PNG
```


Portable Network Graphic (.png), kayıpsız sıkıştırma kullanan bir raster görüntü dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/image/png

### PS {#PS}
```
public static final FileType PS
```


PostScript Dosyası (.ps)

### TIF {#TIF}
```
public static FileType TIF
```


Tagged Image File (.tif)

### TIFF {#TIFF}
```
public static FileType TIFF
```


Tagged Image File Format (.tiff)

### GIF {#GIF}
```
public static FileType GIF
```


Graphical Interchange Format File (.gif)

### SVG {#SVG}
```
public static FileType SVG
```


Scalable Vector Graphics File (.svg)

### SVGZ {#SVGZ}
```
public static FileType SVGZ
```


Scalable Vector Graphics Compressed File (.svgz)

### EMF {#EMF}
```
public static final FileType EMF
```


Windows Gelişmiş Metafile (.emf)

### EMZ {#EMZ}
```
public static final FileType EMZ
```


Windows Sıkıştırılmış Gelişmiş Metafile (.emz)

### HTML {#HTML}
```
public static final FileType HTML
```


Hypertext Markup Language File (.html), tarayıcılarda görüntülenmek üzere oluşturulan web sayfalarının uzantısıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


MHTML Web Archive (.mht), çeşitli uygulamalar tarafından oluşturulabilen bir web sayfası arşiv formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/web/mhtml

### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML File (.mhtml), çeşitli uygulamalar tarafından oluşturulabilen bir web sayfası arşiv formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/web/mhtml

### ONE {#ONE}
```
public static final FileType ONE
```


OneNote Belgesi (.one) dosyaları Microsoft OneNote uygulaması tarafından oluşturulur. OneNote, not alırken taslak defterinizi kullandığınız gibi uygulamayı kullanarak bilgi toplamanıza olanak tanır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Portable Document Format Dosyası (.pdf), belgeler ve diğer referans materyallerinin uygulama yazılımı, donanım ve işletim sisteminden bağımsız bir formatta temsil edilmesi için standart olarak tanıtılan bir dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


XML Paper Specification Dosyası (.xps), Microsoft tarafından oluşturulan XML Paper Specification temelli sayfa düzeni dosyalarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/page-description-language/xps

### TEX {#TEX}
```
public static final FileType TEX
```


LaTeX Kaynak Belgesi (.tex), programlama ve işaretleme özelliklerini içeren ve belgeleri biçimlendirmek için kullanılan bir dildir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


PowerPoint Sunumu (.ppt), slayt gösterisi olarak görüntülenmek üzere bir dizi slayt içeren PowerPoint dosyasını temsil eder. Microsoft PowerPoint 97-2003 tarafından kullanılan İkili Dosya Formatını belirtir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


PowerPoint Open XML Sunumu (.pptx), popüler Microsoft PowerPoint uygulamasıyla oluşturulan bir sunum dosyasıdır. Önceki ikili PPT sunum dosyası formatının aksine, PPTX formatı Microsoft PowerPoint açık XML sunum dosyası formatına dayanır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


PowerPoint Slayt Gösterisi (.pps), Microsoft PowerPoint kullanılarak Slayt Gösterisi amacıyla oluşturulan bir dosyadır. PPS dosyalarının okunması ve oluşturulması Microsoft PowerPoint 97-2003 tarafından desteklenir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


PowerPoint Open XML Slayt Gösterisi (.ppsx), Microsoft PowerPoint 2007 ve üzeri sürümlerle Slayt Gösterisi amacıyla oluşturulan bir dosyadır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument Sunumu (.odp), OpenOffice.org tarafından OASIS Open standardında kullanılan sunum dosyası formatını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/presentation/odp

### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument Sunum Şablonu (.otp), OASIS OpenDocument standart formatında uygulamalar tarafından oluşturulan sunum şablonu dosyalarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Excel Çalışma Sayfası (.xls), Microsoft Excel'in yanı sıra OpenOffice Calc veya Apple Numbers gibi benzer tablo programlarıyla da oluşturulabilen bir dosyadır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/spreadsheet/xls

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel Open XML Çalışma Sayfası (.xlsx), Microsoft Office 2007 sürümüyle Microsoft tarafından tanıtılan, Microsoft Excel belgeleri için yaygın bir formattır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Excel Open XML Makro Etkin Çalışma Sayfası (.xlsm), makroları destekleyen bir tür çalışma sayfası dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Excel İkili Çalışma Sayfası (.xlsb) dosya formatı, Excel çalışma kitabı içeriğini belirleyen kayıt ve yapılar koleksiyonunu içeren Excel İkili Dosya Formatını tanımlar. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Virgülle Ayrılmış Değerler Dosyası (.csv), virgülle ayrılmış değerler içeren veri kayıtlarını barındıran düz metin dosyalarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Sekme Ayrılmış Değerler Dosyası (.tsv), sekmelerle ayrılmış verileri içeren düz metin formatındaki dosyaları temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument Çalışma Sayfası (.ods).

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Excel Open XML Makro Etkin Çalışma Sayfası Şablonu (.xltm), Microsoft Excel tarafından makro etkin şablon dosyaları olarak oluşturulan dosyaları temsil eder. XLTM dosyaları, XLTX dosyalarına benzer bir yapıya sahiptir; ancak XLTX makrolu şablon dosyaları oluşturmayı desteklemez. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/spreadsheet/xltm

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Excel Open XML Çalışma Sayfası Şablonu (.xltx) dosyaları, Office OpenXML dosya formatı spesifikasyonlarına dayanır. Bu dosyalar, XLTX dosyasında belirtilen aynı ayarları taşıyan XLSX dosyaları oluşturmak için kullanılabilecek standart bir şablon dosyası yaratmak amacıyla kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/spreadsheet/xltx

### XLT {#XLT}
```
public static final FileType XLT
```


Excel Şablon Dosyası (.xlt), Microsoft Excel ile oluşturulan şablon dosyalarıdır; Excel, Microsoft Office paketinin bir parçası olan bir tablo uygulamasıdır. Microsoft Office 97-2003, yeni XLT dosyaları oluşturmayı ve bu dosyaları açmayı destekliyordu. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/spreadsheet/xlt

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Excel Makro Etkin Eklentisi (.xlam).

### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word Belgesi (.doc), Microsoft Word veya diğer kelime işlemci programları tarafından ikili dosya formatında oluşturulan belgeleri temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word Open XML Belgesi (.docx), Microsoft Word belgeleri için yaygın bir formattır. 2007'de Microsoft Office 2007'in yayınlanmasıyla tanıtılan bu yeni belge formatının yapısı, düz ikili formatından XML ve ikili dosyaların bir kombinasyonuna değiştirildi. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/word-processing/docx

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Word Open XML Makro Etkin Belgesi (.docm) dosyaları, makroları çalıştırma yeteneğine sahip Microsoft Word 2007 veya daha yeni sürümlerle oluşturulan belgelerdir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Word Belge Şablonu (.dot) dosyaları, sonraki DOC veya DOCX dosyalarının oluşturulması için önceden biçimlendirilmiş ayarlara sahip olmak amacıyla Microsoft Word tarafından oluşturulan şablon dosyalarıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Word Open XML Belge Şablonu (.dotx), sonraki DOCX dosyalarının oluşturulması için önceden biçimlendirilmiş ayarlara sahip olmak amacıyla Microsoft Word tarafından oluşturulan şablon dosyalarıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Word Open XML Makro Etkin Belge Şablonu (.dotm), Microsoft Word 2007 veya daha yeni sürümlerle oluşturulan şablon dosyasını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Rich Text Format Dosyası (.rtf), Microsoft tarafından tanıtılmış ve belgelenmiştir; Rich Text Format (RTF), uygulamalar içinde kullanılmak üzere biçimlendirilmiş metin ve grafiklerin kodlanma yöntemini temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Düz Metin Dosyası (.txt), satır şeklinde düz metin içeren bir metin belgesini temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/word-processing/txt

### ERR {#ERR}
```
public static final FileType ERR
```


Hata Günlüğü Dosyası (.err), bir program tarafından oluşturulan hata mesajlarını içeren bir metin dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://fileinfo.com/extension/err

### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument Metin Belgesi (.odt) dosyaları, OpenDocument Metin Dosyası formatına dayalı kelime işlemci uygulamalarıyla oluşturulan belge türleridir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument Belge Şablonu (.ott), OASIS'in OpenDocument standart formatına uygun olarak uygulamalar tarafından oluşturulan şablon belgeleri temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/word-processing/ott

### WAV {#WAV}
```
public static FileType WAV
```


WAV, WAVE (Waveform Audio File Format) olarak bilinir, dijital ses dosyalarını depolamak için Microsoft\u2019s Resource Interchange File Format (RIFF) spesifikasyonunun bir alt kümesidir. Bu format, bit akışına herhangi bir sıkıştırma uygulamaz ve ses kayıtlarını farklı örnekleme oranları ve bit hızlarıyla depolar. Ses CD'leri için standart formatlardan biri olmuştur ve hâlâdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/audio/wav

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Dosya türü adı ör. "Microsoft Word Document".

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Dosya adı eki (nokta "." dahil) ör. ".doc".

**Returns:**
java.lang.String
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Dosya uzantısını dosya türüne eşler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uzantı | java.lang.String | Dosya uzantısı (nokta "." dahil). |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype) - When file type is supported returns it, otherwise returns default \#Unknown.Unknown file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Desteklenen dosya türlerini alır

**Returns:**
java.util.List<com.groupdocs.merger.domain.FileType> - Desteklenen dosya türlerinin sırasını döndürür
### equals(FileType other) {#equals-com.groupdocs.merger.domain.FileType-}
```
public final boolean equals(FileType other)
```


Mevcut [FileType](../../com.groupdocs.merger.domain/filetype) nesnesinin belirtilen [FileType](../../com.groupdocs.merger.domain/filetype) nesnesiyle aynı olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [FileType](../../com.groupdocs.merger.domain/filetype) | Mevcut [FileType](../../com.groupdocs.merger.domain/filetype) nesnesiyle karşılaştırılacak nesne. |

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

parametre [FileType](../../com.groupdocs.merger.domain/filetype) olup mevcut [FileType](../../com.groupdocs.merger.domain/filetype) nesnesiyle aynı ise; aksi takdirde,

```
false
```
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mevcut [FileType](../../com.groupdocs.merger.domain/filetype) nesnesi için hash kodunu döndürür.

**Returns:**
int - Mevcut [FileType](../../com.groupdocs.merger.domain/filetype) nesnesi için bir karma kodu.
### op_Equality(FileType left, FileType right) {#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public static boolean op_Equality(FileType left, FileType right)
```


İki [FileType](../../com.groupdocs.merger.domain/filetype) nesnesinin aynı olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.merger.domain/filetype) | Sol [FileType](../../com.groupdocs.merger.domain/filetype) nesnesi. |
| right | [FileType](../../com.groupdocs.merger.domain/filetype) | Sağ [FileType](../../com.groupdocs.merger.domain/filetype) nesnesi. |

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

eğer her iki [FileType](../../com.groupdocs.merger.domain/filetype) nesnesi aynı değilse; aksi takdirde,

```
false
```
### toString() {#toString--}
```
public String toString()
```


Mevcut nesneyi temsil eden bir dize döndürür.

**Returns:**
java.lang.String - Geçerli nesneyi temsil eden bir dize.
### isText(FileType fileType) {#isText-com.groupdocs.merger.domain.FileType-}
```
public static boolean isText(FileType fileType)
```


Girdi [FileType](../../com.groupdocs.merger.domain/filetype) nesnesinin ilkel metin formatı olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Bu [FileType](../../com.groupdocs.merger.domain/filetype) nesnesi. |

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

eğer giriş [FileType](../../com.groupdocs.merger.domain/filetype) arşiv formatındaysa; aksi takdirde,

```
false
```
### isImage(FileType fileType) {#isImage-com.groupdocs.merger.domain.FileType-}
```
public static boolean isImage(FileType fileType)
```


Girdi [FileType](../../com.groupdocs.merger.domain/filetype) nesnesinin ilkel metin formatı olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Bu [FileType](../../com.groupdocs.merger.domain/filetype) nesnesi. |

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

eğer giriş [FileType](../../com.groupdocs.merger.domain/filetype) ses formatındaysa; aksi takdirde,

```
false
```
### getBase(FileType fileType) {#getBase-com.groupdocs.merger.domain.FileType-}
```
public static FileType getBase(FileType fileType)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) |  |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
