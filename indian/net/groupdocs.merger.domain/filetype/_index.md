---
title: FileType
second_title: .NET API संदर्भ के लिए GroupDocs.Merger
description: फ़इल प्रकर क प्रतनधत्व करत है द्वर समर्थत सभ फ़इल प्रकरं क सूच प्रप्त करने के तरके प्रदन करत हैGroupDocs.Merger  एक्सटेंशन आद द्वर फ़इल प्रकर क पत लगएं.
type: docs
weight: 100
url: /hi/net/groupdocs.merger.domain/filetype/
---
## FileType class

फ़ाइल प्रकार का प्रतिनिधित्व करता है। द्वारा समर्थित सभी फ़ाइल प्रकारों की सूची प्राप्त करने के तरीके प्रदान करता है**GroupDocs.Merger** , एक्सटेंशन आदि द्वारा फ़ाइल प्रकार का पता लगाएं.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | फ़ाइल नाम प्रत्यय (अवधि "." सहित) उदाहरण के लिए ".doc". |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | फ़ाइल प्रकार नाम जैसे "माइक्रोसॉफ्ट वर्ड दस्तावेज़"। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | फ़ाइल प्रकार के लिए मानचित्र फ़ाइल एक्सटेंशन. |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | निर्धारित करता है कि क्या वर्तमान[`FileType`](../filetype) निर्दिष्ट के समान है[`FileType`](../filetype) वस्तु. |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | निर्धारित करता है कि क्या वर्तमान[`FileType`](../filetype) निर्दिष्ट वस्तु के समान है। |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | वर्तमान के लिए हैश कोड लौटाता है[`FileType`](../filetype) वस्तु. |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | एक स्ट्रिंग लौटाता है जो वर्तमान वस्तु का प्रतिनिधित्व करता है। |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | समर्थित फ़ाइल प्रकारों को पुनः प्राप्त करता है |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | निर्धारित करता है कि क्या इनपुट[`FileType`](../filetype) संग्रह स्वरूप है. |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | निर्धारित करता है कि क्या इनपुट[`FileType`](../filetype) छवि प्रारूप है. |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | निर्धारित करता है कि क्या इनपुट[`FileType`](../filetype) आदिम पाठ स्वरूप है. |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | निर्धारित करता है कि क्या दो[`FileType`](../filetype) वस्तुएं समान हैं। |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | निर्धारित करता है कि क्या दो[`FileType`](../filetype) वस्तुएं समान नहीं हैं। |

## खेत

| नाम | विवरण |
| --- | --- |
| static [BMP](../../groupdocs.merger.domain/filetype/bmp) | बिटमैप छवि फ़ाइल (.bmp) उन फ़ाइलों का प्रतिनिधित्व करती है जिनका उपयोग बिटमैप डिजिटल छवियों को संग्रहीत करने के लिए किया जाता है। इस फ़ाइल स्वरूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/image/bmp) . |
| static [BZ2](../../groupdocs.merger.domain/filetype/bz2) | Bzip2 संपीड़ित फ़ाइल (.bz2) |
| static [CSV](../../groupdocs.merger.domain/filetype/csv) | अल्पविराम से अलग की गई मान फ़ाइल (.csv) सादे पाठ फ़ाइलों का प्रतिनिधित्व करती है जिनमें अल्पविराम से अलग किए गए मानों के साथ डेटा के रिकॉर्ड होते हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/spreadsheet/csv) . |
| static [DOC](../../groupdocs.merger.domain/filetype/doc) | Microsoft Word दस्तावेज़ (.doc) Microsoft Word या अन्य शब्द संसाधन दस्तावेज़ों द्वारा बाइनरी फ़ाइल स्वरूप में जनरेट किए गए दस्तावेज़ों का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/word-processing/doc) . |
| static [DOCM](../../groupdocs.merger.domain/filetype/docm) | Word Open XML मैक्रो-सक्षम दस्तावेज़ (.docm) फ़ाइलें Microsoft Word 2007 या मैक्रोज़ चलाने की क्षमता के साथ उच्चतर जनरेट किए गए दस्तावेज़ हैं। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/word-processing/docm) . |
| static [DOCX](../../groupdocs.merger.domain/filetype/docx) | माइक्रोसॉफ्ट वर्ड ओपन एक्सएमएल दस्तावेज़ (.docx) माइक्रोसॉफ्ट वर्ड दस्तावेज़ों के लिए एक प्रसिद्ध प्रारूप है। Microsoft Office 2007 की रिलीज़ के साथ 2007 से पेश किया गया, इस नए दस्तावेज़ प्रारूप की संरचना को सादे बाइनरी से XML और बाइनरी फ़ाइलों के संयोजन में बदल दिया गया था। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/word-processing/docx) . |
| static [DOT](../../groupdocs.merger.domain/filetype/dot) | Word दस्तावेज़ टेम्प्लेट (.dot) फ़ाइलें Microsoft Word द्वारा बनाई गई टेम्प्लेट फ़ाइलें हैं जिनमें आगे DOC या DOCX फ़ाइलों के निर्माण के लिए पूर्व-स्वरूपित सेटिंग्स होती हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/word-processing/dot) . |
| static [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Word Open XML मैक्रो-सक्षम दस्तावेज़ टेम्पलेट (.dotm) Microsoft Word 2007 या उच्चतर के साथ बनाई गई टेम्पलेट फ़ाइल का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/word-processing/dotm) . |
| static [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Word Open XML दस्तावेज़ टेम्पलेट (.dotx) Microsoft Word द्वारा बनाई गई टेम्पलेट फ़ाइलें हैं, जिनमें आगे DOCX फ़ाइलों के निर्माण के लिए पूर्व-स्वरूपित सेटिंग्स हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/word-processing/dotx) . |
| static [EPUB](../../groupdocs.merger.domain/filetype/epub) | ओपन ईबुक फ़ाइल (.epub) एक ई-बुक फ़ाइल स्वरूप है जो प्रकाशकों और उपभोक्ताओं के लिए एक मानक डिजिटल प्रकाशन प्रारूप प्रदान करता है। प्रारूप अब तक इतना सामान्य हो गया है कि यह कई ई-रीडर और सॉफ्टवेयर अनुप्रयोगों द्वारा समर्थित है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/ebook/epub) . |
| static [ERR](../../groupdocs.merger.domain/filetype/err) | त्रुटि लॉग फ़ाइल (.err) एक पाठ फ़ाइल है जिसमें प्रोग्राम द्वारा उत्पन्न त्रुटि संदेश होते हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://fileinfo.com/extension/err) . |
| static [GIF](../../groupdocs.merger.domain/filetype/gif) | ग्राफ़िकल इंटरचेंज फ़ॉर्मेट फ़ाइल (.gif) |
| static [GZ](../../groupdocs.merger.domain/filetype/gz) | जी-ज़िप संपीड़ित फ़ाइल (.gz) |
| static [HTML](../../groupdocs.merger.domain/filetype/html) | हाइपरटेक्स्ट मार्कअप लैंग्वेज फ़ाइल (.html) ब्राउज़रों में प्रदर्शन के लिए बनाए गए वेब पेजों का एक्सटेंशन है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/web/html) . |
| static [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | JPEG छवि (.jpeg) एक प्रकार का छवि प्रारूप है जिसे हानिकारक संपीड़न की विधि का उपयोग करके सहेजा जाता है। संपीड़न के परिणाम के रूप में आउटपुट छवि, भंडारण आकार और छवि गुणवत्ता के बीच एक समझौता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/image/jpeg) . |
| static [JPG](../../groupdocs.merger.domain/filetype/jpg) | JPEG इमेज (.jpg) |
| static [MHT](../../groupdocs.merger.domain/filetype/mht) | एमएचटीएमएल वेब आर्काइव (.एमएचटी) एक वेब पेज आर्काइव प्रारूप है जिसे कई अलग-अलग एप्लिकेशन द्वारा बनाया जा सकता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/web/mhtml) . |
| static [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | MIME HTML फ़ाइल (.mhtml) एक वेब पेज संग्रह प्रारूप है जिसे कई अलग-अलग अनुप्रयोगों द्वारा बनाया जा सकता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/web/mhtml) . |
| static [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument प्रस्तुतिकरण (.odp) OASISOpen मानक में OpenOffice.org द्वारा प्रयुक्त प्रस्तुति फ़ाइल स्वरूप का प्रतिनिधित्व करता है. इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/presentation/odp) . |
| static [ODS](../../groupdocs.merger.domain/filetype/ods) | OpenDocument स्प्रेडशीट (.ods) इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/spreadsheet/ods) . |
| static [ODT](../../groupdocs.merger.domain/filetype/odt) | OpenDocument टेक्स्ट डॉक्यूमेंट (.odt) फाइलें वर्ड प्रोसेसिंग एप्लिकेशन के साथ बनाए गए दस्तावेज़ हैं जो OpenDocument टेक्स्ट फ़ाइल प्रारूप पर आधारित हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/word-processing/odt) . |
| static [ONE](../../groupdocs.merger.domain/filetype/one) | OneNote दस्तावेज़ (.one) फ़ाइलें Microsoft OneNote एप्लिकेशन द्वारा बनाई गई हैं। OneNote आपको एप्लिकेशन का उपयोग करके जानकारी एकत्र करने देता है जैसे कि आप नोट्स लेने के लिए अपने ड्राफ्टपैड का उपयोग कर रहे हों। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/note-taking/one) . |
| static [OTP](../../groupdocs.merger.domain/filetype/otp) | OpenDocument प्रस्तुति टेम्पलेट (.otp) OASIS OpenDocument मानक प्रारूप में एप्लिकेशन द्वारा बनाई गई प्रस्तुति टेम्पलेट फ़ाइलों का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/presentation/otp) . |
| static [OTT](../../groupdocs.merger.domain/filetype/ott) | OpenDocument दस्तावेज़ टेम्पलेट (.ott) OASIS 'OpenDocument मानक प्रारूप के अनुपालन में अनुप्रयोगों द्वारा उत्पन्न टेम्पलेट दस्तावेज़ों का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/word-processing/ott) . |
| static [PDF](../../groupdocs.merger.domain/filetype/pdf) | पोर्टेबल दस्तावेज़ स्वरूप फ़ाइल (.पीडीएफ) एक फ़ाइल प्रारूप है जिसे दस्तावेजों और अन्य संदर्भ सामग्री के प्रतिनिधित्व के लिए एक मानक के रूप में एक ऐसे प्रारूप में पेश किया जाना था जो एप्लिकेशन सॉफ़्टवेयर, हार्डवेयर के साथ-साथ ऑपरेटिंग सिस्टम से स्वतंत्र है। इस फ़ाइल के बारे में अधिक जानें प्रारूप[यहाँ](https://docs.fileformat.com/view/pdf) . |
| static [PNG](../../groupdocs.merger.domain/filetype/png) | पोर्टेबल नेटवर्क ग्राफ़िक (.png) एक प्रकार का रेखापुंज छवि फ़ाइल प्रारूप है जो लूज़लेस संपीड़न का उपयोग करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/image/png) . |
| static [PPS](../../groupdocs.merger.domain/filetype/pps) | PowerPoint स्लाइड शो (.pps) स्लाइड शो उद्देश्य के लिए Microsoft PowerPoint का उपयोग करके बनाई गई फ़ाइल है। PPS फ़ाइल पढ़ना और बनाना Microsoft PowerPoint 97-2003 द्वारा समर्थित है. इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/presentation/pps) . |
| static [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | PowerPoint ओपन XML स्लाइड शो (.ppsx) स्लाइड शो उद्देश्य के लिए Microsoft PowerPoint 2007 और इसके बाद के संस्करण का उपयोग करके बनाई गई फ़ाइल है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/presentation/ppsx) . |
| static [PPT](../../groupdocs.merger.domain/filetype/ppt) | PowerPoint प्रस्तुति (.ppt) PowerPoint फ़ाइल का प्रतिनिधित्व करती है जिसमें स्लाइड शो के रूप में प्रदर्शित करने के लिए स्लाइड का संग्रह होता है। यह Microsoft PowerPoint 97-2003 द्वारा उपयोग किए जाने वाले बाइनरी फ़ाइल स्वरूप को निर्दिष्ट करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/presentation/ppt) . |
| static [PPTX](../../groupdocs.merger.domain/filetype/pptx) | पावरपॉइंट ओपन एक्सएमएल प्रेजेंटेशन (.pptx) एक प्रेजेंटेशन फाइल है जिसे लोकप्रिय माइक्रोसॉफ्ट पॉवरपॉइंट एप्लिकेशन के साथ बनाया गया है। प्रस्तुति फ़ाइल प्रारूप पीपीटी के पिछले संस्करण के विपरीत जो बाइनरी था, पीपीटीएक्स प्रारूप माइक्रोसॉफ्ट पावरपॉइंट ओपन एक्सएमएल प्रस्तुति फ़ाइल प्रारूप पर आधारित है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/presentation/pptx) . |
| static [PS](../../groupdocs.merger.domain/filetype/ps) | पोस्टस्क्रिप्ट फ़ाइल (.ps) |
| static [RAR](../../groupdocs.merger.domain/filetype/rar) | रोशल आर्काइव कंप्रेस्ड फ़ाइल (.rar) |
| static [RTF](../../groupdocs.merger.domain/filetype/rtf) | रिच टेक्स्ट फ़ॉर्मेट फ़ाइल (.rtf) Microsoft द्वारा प्रस्तुत और प्रलेखित, रिच टेक्स्ट फ़ॉर्मेट (RTF) अनुप्रयोगों के भीतर उपयोग के लिए स्वरूपित टेक्स्ट और ग्राफ़िक्स को एन्कोडिंग की एक विधि का प्रतिनिधित्व करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/word-processing/rtf) . |
| static [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | 7-ज़िप कंप्रेस्ड फ़ाइल (.7z) |
| static [TAR](../../groupdocs.merger.domain/filetype/tar) | समेकित यूनिक्स फ़ाइल संग्रह (.tar) |
| static [TEX](../../groupdocs.merger.domain/filetype/tex) | LaTeX स्रोत दस्तावेज़ (.tex) एक ऐसी भाषा है जिसमें प्रोग्रामिंग के साथ-साथ मार्क-अप सुविधाएँ भी शामिल हैं, जिनका उपयोग दस्तावेज़ों को टाइप करने के लिए किया जाता है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/page-description-language/tex) . |
| static [TIF](../../groupdocs.merger.domain/filetype/tif) | टैग की गई छवि फ़ाइल (.tif) |
| static [TIFF](../../groupdocs.merger.domain/filetype/tiff) | टैग की गई छवि फ़ाइल प्रारूप (.tiff) |
| static [TSV](../../groupdocs.merger.domain/filetype/tsv) | टैब सेपरेटेड वैल्यू फ़ाइल (.tsv) सादे पाठ प्रारूप में टैब से अलग किए गए डेटा का प्रतिनिधित्व करती है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/spreadsheet/tsv) . |
| static [TXT](../../groupdocs.merger.domain/filetype/txt) | सादा पाठ फ़ाइल (.txt) एक पाठ दस्तावेज़ का प्रतिनिधित्व करता है जिसमें पंक्तियों के रूप में सादा पाठ होता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/word-processing/txt) . |
| static [Unknown](../../groupdocs.merger.domain/filetype/unknown) | अज्ञात फ़ाइल प्रकार का प्रतिनिधित्व करता है। |
| static [VDX](../../groupdocs.merger.domain/filetype/vdx) | Visio ड्रॉइंग XML फ़ाइल (.vdx) Microsoft Visio में बनाई गई एक ड्राइंग या चार्ट है, लेकिन XML प्रारूप में सहेजी गई है। VDX एक्सटेंशन। Visio ड्रॉइंग XML फ़ाइल Visio सॉफ़्टवेयर में बनाई गई है, जिसे Microsoft द्वारा विकसित किया गया है. इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/image/vdx) . |
| static [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Visio मैक्रो-सक्षम आरेखण (.vsdm) मैक्रोज़ का समर्थन करने वाले Microsoft Visio एप्लिकेशन के साथ बनाई गई फ़ाइलें आरेखित कर रहे हैं। वीएसडीएम फाइलें ओपीसी/एक्सएमएल ड्रॉइंग हैं जो वीएसडीएक्स के समान हैं, लेकिन फाइल खोलने पर मैक्रोज़ चलाने की क्षमता भी प्रदान करती हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/image/vsdm) . |
| static [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Visio Drawing (.vsdx) Microsoft Office 2013 से पेश किए गए Microsoft Visio फ़ाइल स्वरूप का प्रतिनिधित्व करता है। इसे बाइनरी फ़ाइल स्वरूप, .VSD को बदलने के लिए विकसित किया गया था, जो Microsoft Visio के पुराने संस्करणों द्वारा समर्थित है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/image/vsdx) . |
| static [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Visio मैक्रो-सक्षम स्टैंसिल फ़ाइल (.vssm) Microsoft Visio स्टैंसिल फ़ाइलें हैं जो मैक्रोज़ के लिए समर्थन प्रदान करती हैं। एक वीएसएसएम फ़ाइल जब खोली जाती है तो आरेख में वांछित स्वरूपण और आकृतियों के प्लेसमेंट को प्राप्त करने के लिए मैक्रोज़ को चलाने की अनुमति देती है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/image/vssm) . |
| static [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Visio स्टैंसिल फ़ाइल (.vssx) Microsoft Visio 2013 और इसके बाद के संस्करण के साथ बनाए गए स्टेंसिल खींच रहे हैं। VSSX फ़ाइल स्वरूप को Visio 2013 और इसके बाद के संस्करण के साथ खोला जा सकता है। Visio फ़ाइलें विभिन्न प्रकार के आरेखण तत्वों के प्रतिनिधित्व के लिए जानी जाती हैं, जैसे आकृतियों का संग्रह, कनेक्टर्स, फ़्लोचार्ट, नेटवर्क लेआउट, UML आरेख, इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/image/vssx) . |
| static [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Visio मैक्रो-सक्षम ड्रॉइंग टेम्प्लेट (.vstm) Microsoft Visio के साथ बनाई गई टेम्प्लेट फ़ाइलें हैं जो मैक्रोज़ का समर्थन करती हैं। VSDX फ़ाइलों के विपरीत, VSTM टेम्प्लेट से बनाई गई फ़ाइलें मैक्रोज़ चला सकती हैं जो कि Visual Basic for Applications (VBA) कोड में विकसित की गई हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/image/vstm) . |
| static [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Visio आरेखण टेम्प्लेट (.vstx) Microsoft Visio 2013 और इसके बाद के संस्करण के साथ बनाई गई टेम्पलेट फ़ाइलें आरेखित कर रहे हैं। ये वीएसटीएक्स फाइलें डिफ़ॉल्ट लेआउट और सेटिंग्स के साथ .VSDX फाइलों के रूप में सहेजी गई Visio ड्रॉइंग बनाने के लिए शुरुआती बिंदु प्रदान करती हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/image/vstx) . |
| static [VSX](../../groupdocs.merger.domain/filetype/vsx) | Visio स्टैंसिल XML फ़ाइल (.vsx) स्टैंसिल को संदर्भित करता है जिसमें आरेखण और आकृतियाँ होती हैं जिनका उपयोग Microsoft Visio में आरेख बनाने के लिए किया जाता है। VSX फ़ाइलें XML फ़ाइल स्वरूप में सहेजी जाती हैं और Visio 2013 तक समर्थित थीं. इस फ़ाइल स्वरूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/image/vsx) . |
| static [VTX](../../groupdocs.merger.domain/filetype/vtx) | Visio Template XML फ़ाइल (.vtx) Microsoft Visio आरेखण टेम्पलेट है जिसे XML फ़ाइल स्वरूप में डिस्क में सहेजा जाता है. टेम्प्लेट का उद्देश्य मूल सेटिंग्स वाली एक फ़ाइल प्रदान करना है जिसका उपयोग समान सेटिंग्स की एकाधिक Visio फ़ाइलें बनाने के लिए किया जा सकता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/image/vtx) . |
| static [XLAM](../../groupdocs.merger.domain/filetype/xlam) | एक्सेल मैक्रो-सक्षम ऐड-इन (.xlam) |
| static [XLS](../../groupdocs.merger.domain/filetype/xls) | एक्सेल स्प्रेडशीट (.xls) एक फाइल है जिसे माइक्रोसॉफ्ट एक्सेल के साथ-साथ अन्य समान स्प्रेडशीट प्रोग्राम जैसे ओपनऑफिस कैल्क या ऐप्पल नंबर द्वारा बनाया जा सकता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/spreadsheet/xls) . |
| static [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | एक्सेल बाइनरी स्प्रेडशीट (.xlsb) फ़ाइल स्वरूप एक्सेल बाइनरी फ़ाइल स्वरूप को निर्दिष्ट करता है, जो रिकॉर्ड और संरचनाओं का एक संग्रह है जो एक्सेल कार्यपुस्तिका सामग्री को निर्दिष्ट करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/spreadsheet/xlsb) . |
| static [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | एक्सेल ओपन एक्सएमएल मैक्रो-इनेबल्ड स्प्रेडशीट (.xlsm) एक प्रकार की स्प्रेशीट फाइल है जो मैक्रो का समर्थन करती है। इस फाइल फॉर्मेट के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/spreadsheet/xlsm) . |
| static [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | माइक्रोसॉफ्ट एक्सेल ओपन एक्सएमएल स्प्रेडशीट (.xlsx) माइक्रोसॉफ्ट एक्सेल दस्तावेज़ों के लिए एक प्रसिद्ध प्रारूप है जिसे माइक्रोसॉफ्ट द्वारा माइक्रोसॉफ्ट ऑफिस 2007 के रिलीज के साथ पेश किया गया था। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/spreadsheet/xlsx) . |
| static [XLT](../../groupdocs.merger.domain/filetype/xlt) | एक्सेल टेम्प्लेट फाइल (.xlt) माइक्रोसॉफ्ट एक्सेल के साथ बनाई गई टेम्प्लेट फाइलें हैं जो एक स्प्रेडशीट एप्लिकेशन है जो माइक्रोसॉफ्ट ऑफिस सूट के हिस्से के रूप में आती है। Microsoft Office 97-2003 ने नई XLT फ़ाइलों को बनाने के साथ-साथ इन्हें खोलने का भी समर्थन किया। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/spreadsheet/xlt) . |
| static [XLTM](../../groupdocs.merger.domain/filetype/xltm) | एक्सेल ओपन एक्सएमएल मैक्रो-सक्षम स्प्रेडशीट टेम्पलेट (.xltm) उन फ़ाइलों का प्रतिनिधित्व करता है जो मैक्रो-सक्षम टेम्पलेट फ़ाइलों के रूप में माइक्रोसॉफ्ट एक्सेल द्वारा उत्पन्न होती हैं। XLTM फाइलें संरचना में XLTX के समान हैं, इसके अलावा बाद में मैक्रोज़ के साथ टेम्पलेट फ़ाइलों को बनाने का समर्थन नहीं करता है। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/spreadsheet/xltm) . |
| static [XLTX](../../groupdocs.merger.domain/filetype/xltx) | एक्सेल ओपन एक्सएमएल स्प्रेडशीट टेम्प्लेट (.xltx) फाइलें ऑफिस ओपनएक्सएमएल फाइल फॉर्मेट विनिर्देशों पर आधारित हैं। इसका उपयोग एक मानक टेम्पलेट फ़ाइल बनाने के लिए किया जाता है जिसका उपयोग XLTX फ़ाइल बनाने के लिए किया जा सकता है जो XLTX फ़ाइल में निर्दिष्ट सेटिंग्स को प्रदर्शित करती है। इस फ़ाइल प्रारूप के बारे में अधिक जानें[यहाँ](https://docs.fileformat.com/spreadsheet/xltx) . |
| static [XPS](../../groupdocs.merger.domain/filetype/xps) | XML पेपर विशिष्टता फ़ाइल (.xps) पृष्ठ लेआउट फ़ाइलों का प्रतिनिधित्व करती है जो Microsoft द्वारा बनाए गए XML पेपर विनिर्देशों पर आधारित हैं। इस फ़ाइल प्रारूप के बारे में और जानें[यहाँ](https://docs.fileformat.com/page-description-language/xps) . |
| static [ZIP](../../groupdocs.merger.domain/filetype/zip) | ज़िप की गई फ़ाइल (.zip) |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs.Merger: द्वारा समर्थित फ़ाइल स्वरूपों के बारे में अधिक जानें[समर्थित दस्तावेज़ स्वरूपों की पूरी सूची](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* कोड में समर्थित फ़ाइल प्रकार प्राप्त करने के बारे में अधिक जानें: [कोड में समर्थित फ़ाइल स्वरूप कैसे प्राप्त करें](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### यह सभी देखें

* नाम स्थान [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* सभा [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
