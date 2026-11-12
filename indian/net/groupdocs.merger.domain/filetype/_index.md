---
title: "FileType"
second_title: "GroupDocs.Merger .NET के लिए API संदर्भ"
description: "फ़ाइल प्रकार का प्रतिनिधित्व करता है। GroupDocs.Merger द्वारा समर्थित सभी फ़ाइल प्रकारों की सूची प्राप्त करने, एक्सटेंशन द्वारा फ़ाइल प्रकार का पता लगाने आदि के लिए मेथड प्रदान करता है।"
type: docs
weight: 110
url: /hi/net/groupdocs.merger.domain/filetype/
---
## FileType class

फ़ाइल प्रकार का प्रतिनिधित्व करता है। सभी फ़ाइल प्रकारों की सूची प्राप्त करने के लिए मेथड प्रदान करता है जो **GroupDocs.Merger** द्वारा समर्थित हैं, एक्सटेंशन द्वारा फ़ाइल प्रकार का पता लगाता है आदि।

```csharp
public sealed class FileType : IEquatable<FileType>
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | फ़ाइलनाम प्रत्यय (बिंदु \".\" सहित) जैसे \".doc\"। |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | फ़ाइल प्रकार का नाम जैसे \"Microsoft Word Document\"। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | फ़ाइल एक्सटेंशन को फ़ाइल प्रकार से मैप करता है। |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | निर्धारित करता है कि वर्तमान [`FileType`](../filetype) निर्दिष्ट [`FileType`](../filetype) ऑब्जेक्ट के समान है या नहीं। |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | निर्धारित करता है कि वर्तमान [`FileType`](../filetype) निर्दिष्ट ऑब्जेक्ट के समान है या नहीं। |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | वर्तमान [`FileType`](../filetype) ऑब्जेक्ट के लिए हैश कोड लौटाता है। |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | समर्थित फ़ाइल प्रकारों को प्राप्त करता है |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | निर्धारित करता है कि इनपुट [`FileType`](../filetype) अभिलेख प्रारूप है या नहीं। |
| static [IsAudio](../../groupdocs.merger.domain/filetype/isaudio)(FileType) | निर्धारित करता है कि इनपुट [`FileType`](../filetype) ऑडियो प्रारूप है या नहीं। |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | निर्धारित करता है कि इनपुट [`FileType`](../filetype) छवि प्रारूप है या नहीं। |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | निर्धारित करता है कि इनपुट [`FileType`](../filetype) मूलभूत पाठ प्रारूप है या नहीं। |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | निर्धारित करता है कि दो [`FileType`](../filetype) ऑब्जेक्ट समान हैं या नहीं। |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | निर्धारित करता है कि दो [`FileType`](../filetype) ऑब्जेक्ट समान नहीं हैं या नहीं। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| static readonly [BMP](../../groupdocs.merger.domain/filetype/bmp) | Bitmap Image File (.bmp) उन फ़ाइलों को दर्शाता है जो बिटमैप डिजिटल छवियों को संग्रहीत करने के लिए उपयोग की जाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/image/bmp)। |
| static readonly [BZ2](../../groupdocs.merger.domain/filetype/bz2) | Bzip2 संपीड़ित फ़ाइल (.bz2) |
| static readonly [CSV](../../groupdocs.merger.domain/filetype/csv) | Comma Separated Values File (.csv) उन साधारण टेक्स्ट फ़ाइलों को दर्शाता है जिनमें अल्पविराम से अलग किए गए मानों के साथ डेटा रिकॉर्ड होते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/spreadsheet/csv)। |
| static readonly [DOC](../../groupdocs.merger.domain/filetype/doc) | Microsoft Word Document (.doc) उन दस्तावेज़ों को दर्शाता है जो Microsoft Word या अन्य वर्ड प्रोसेसिंग सॉफ़्टवेयर द्वारा बाइनरी फ़ाइल फ़ॉर्मेट में उत्पन्न होते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/word-processing/doc)। |
| static readonly [DOCM](../../groupdocs.merger.domain/filetype/docm) | Word Open XML मैक्रो-सक्षम दस्तावेज़ (.docm) फ़ाइलें Microsoft Word 2007 या उससे ऊपर के द्वारा निर्मित दस्तावेज़ हैं जिनमें मैक्रो चलाने की क्षमता होती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/word-processing/docm)। |
| static readonly [DOCX](../../groupdocs.merger.domain/filetype/docx) | Microsoft Word Open XML दस्तावेज़ (.docx) Microsoft Word दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है। यह 2007 में Microsoft Office 2007 के रिलीज़ के साथ प्रस्तुत किया गया, जहाँ इस नए दस्तावेज़ फ़ॉर्मेट की संरचना साधारण बाइनरी से XML और बाइनरी फ़ाइलों के संयोजन में बदल दी गई। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/word-processing/docx)। |
| static readonly [DOT](../../groupdocs.merger.domain/filetype/dot) | Word दस्तावेज़ टेम्पलेट (.dot) फ़ाइलें Microsoft Word द्वारा बनाई गई टेम्पलेट फ़ाइलें हैं, जिनमें आगे के DOC या DOCX फ़ाइलों के निर्माण के लिए पूर्व-फ़ॉर्मेटेड सेटिंग्स होती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/word-processing/dot)। |
| static readonly [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Word Open XML मैक्रो-सक्षम दस्तावेज़ टेम्पलेट (.dotm) Microsoft Word 2007 या उससे ऊपर के साथ बनाई गई टेम्पलेट फ़ाइल को दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/word-processing/dotm)। |
| static readonly [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Word Open XML दस्तावेज़ टेम्पलेट (.dotx) Microsoft Word द्वारा बनाई गई टेम्पलेट फ़ाइलें हैं, जिनमें आगे के DOCX फ़ाइलों के निर्माण के लिए पूर्व-फ़ॉर्मेटेड सेटिंग्स होती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/word-processing/dotx)। |
| static readonly [EMF](../../groupdocs.merger.domain/filetype/emf) | Windows एन्हांस्ड मेटाफाइल (.emf) |
| static readonly [EMZ](../../groupdocs.merger.domain/filetype/emz) | Windows संकुचित एन्हांस्ड मेटाफाइल (.emz) |
| static readonly [EPUB](../../groupdocs.merger.domain/filetype/epub) | Open eBook फ़ाइल (.epub) एक ई-बुक फ़ाइल फ़ॉर्मेट है जो प्रकाशकों और उपभोक्ताओं के लिए एक मानक डिजिटल प्रकाशन फ़ॉर्मेट प्रदान करता है। यह फ़ॉर्मेट अब इतना सामान्य हो गया है कि इसे कई ई-रीडर और सॉफ़्टवेयर एप्लिकेशन समर्थन करते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/ebook/epub)। |
| static readonly [ERR](../../groupdocs.merger.domain/filetype/err) | Error Log फ़ाइल (.err) एक टेक्स्ट फ़ाइल है जिसमें प्रोग्राम द्वारा उत्पन्न त्रुटि संदेश होते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://fileinfo.com/extension/err)। |
| static readonly [GIF](../../groupdocs.merger.domain/filetype/gif) | ग्राफ़िकल इंटरचेंज फ़ॉर्मेट फ़ाइल (.gif) |
| static readonly [GZ](../../groupdocs.merger.domain/filetype/gz) | G-Zip संकुचित फ़ाइल (.gz) |
| static readonly [HTML](../../groupdocs.merger.domain/filetype/html) | Hypertext Markup Language फ़ाइल (.html) वेब पेजों के लिए एक्सटेंशन है जो ब्राउज़र में प्रदर्शित होने के लिए बनाई जाती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/web/html)। |
| static readonly [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | JPEG इमेज (.jpeg) एक इमेज फ़ॉर्मेट प्रकार है जिसे लॉसी कम्प्रेशन विधि से सहेजा जाता है। कम्प्रेशन के परिणामस्वरूप उत्पन्न इमेज, स्टोरेज आकार और इमेज गुणवत्ता के बीच संतुलन बनाती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/image/jpeg)। |
| static readonly [JPG](../../groupdocs.merger.domain/filetype/jpg) | JPEG इमेज (.jpg) |
| static readonly [MHT](../../groupdocs.merger.domain/filetype/mht) | MHTML वेब आर्काइव (.mht) एक वेब पेज आर्काइव फ़ॉर्मेट है जिसे कई विभिन्न एप्लिकेशन द्वारा बनाया जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/web/mhtml)। |
| static readonly [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | MIME HTML फ़ाइल (.mhtml) एक वेब पेज आर्काइव फ़ॉर्मेट है जिसे कई विभिन्न एप्लिकेशन द्वारा बनाया जा सकता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/web/mhtml)। |
| static readonly [MP3](../../groupdocs.merger.domain/filetype/mp3) | .mp3 एक्सटेंशन वाली फ़ाइलें डिजिटल रूप से एन्कोडेड ऑडियो फ़ाइल फ़ॉर्मेट हैं जो औपचारिक रूप से MPEG-1 ऑडियो लेयर III या MPEG-2 ऑडियो लेयर III पर आधारित हैं। इसे मूविंग पिक्चर एक्सपर्ट्स ग्रुप (MPEG) द्वारा विकसित किया गया है जो लेयर 3 ऑडियो कम्प्रेशन का उपयोग करता है। MP3 फ़ाइल फ़ॉर्मेट द्वारा प्राप्त कम्प्रेशन .WAV या .AIF फ़ाइलों के आकार का 1/10 है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/audio/mp3)। |
| static readonly [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument प्रेज़ेंटेशन (.odp) वह प्रेज़ेंटेशन फ़ाइल फ़ॉर्मेट दर्शाता है जो OpenOffice.org द्वारा OASISOpen मानक में उपयोग किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/presentation/odp)। |
| static readonly [ODS](../../groupdocs.merger.domain/filetype/ods) | OpenDocument स्प्रेडशीट (.ods) इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/spreadsheet/ods)। |
| static readonly [ODT](../../groupdocs.merger.domain/filetype/odt) | OpenDocument टेक्स्ट डॉक्यूमेंट (.odt) फ़ाइलें उन दस्तावेज़ों का प्रकार हैं जो वर्ड प्रोसेसिंग एप्लिकेशन द्वारा बनाए जाते हैं और OpenDocument टेक्स्ट फ़ाइल फ़ॉर्मेट पर आधारित होते हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](https://docs.fileformat.com/word-processing/odt)। |
| static readonly [ONE](../../groupdocs.merger.domain/filetype/one) | OneNote Document (.one) फ़ाइलें Microsoft OneNote एप्लिकेशन द्वारा बनाई जाती हैं। OneNote आपको जानकारी इकट्ठा करने की अनुमति देता है जैसे आप नोट्स लेने के लिए अपने ड्राफ्टपैड का उपयोग कर रहे हों। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/note-taking/one) देखें। |
| static readonly [OTP](../../groupdocs.merger.domain/filetype/otp) | OpenDocument Presentation Template (.otp) OASIS OpenDocument मानक फ़ॉर्मेट में अनुप्रयोगों द्वारा बनाई गई प्रस्तुति टेम्पलेट फ़ाइलों का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/presentation/otp) देखें। |
| static readonly [OTT](../../groupdocs.merger.domain/filetype/ott) | OpenDocument Document Template (.ott) OASIS के OpenDocument मानक फ़ॉर्मेट के अनुरूप अनुप्रयोगों द्वारा उत्पन्न टेम्पलेट दस्तावेज़ों का प्रतिनिधित्व करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/word-processing/ott) देखें। |
| static readonly [PDF](../../groupdocs.merger.domain/filetype/pdf) | Portable Document Format File (.pdf) एक फ़ाइल फ़ॉर्मेट है जिसे दस्तावेज़ों और अन्य संदर्भ सामग्री को ऐसे फ़ॉर्मेट में प्रस्तुत करने के मानक के रूप में पेश किया गया था जो एप्लिकेशन सॉफ़्टवेयर, हार्डवेयर और ऑपरेटिंग सिस्टम से स्वतंत्र हो। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/view/pdf) देखें। |
| static readonly [PNG](../../groupdocs.merger.domain/filetype/png) | Portable Network Graphic (.png) एक प्रकार का रास्टर इमेज फ़ाइल फ़ॉर्मेट है जो लॉसलेस संपीड़न का उपयोग करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/image/png) देखें। |
| static readonly [POTM](../../groupdocs.merger.domain/filetype/potm) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) |
| static readonly [POTX](../../groupdocs.merger.domain/filetype/potx) | PowerPoint Open XML Presentation Template (.potx) |
| static readonly [PPS](../../groupdocs.merger.domain/filetype/pps) | PowerPoint Slide Show (.pps) Microsoft PowerPoint का उपयोग करके स्लाइड शो उद्देश्य के लिए बनाई गई फ़ाइल है। PPS फ़ाइल पढ़ना और बनाना Microsoft PowerPoint 97-2003 द्वारा समर्थित है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/presentation/pps) देखें। |
| static readonly [PPSM](../../groupdocs.merger.domain/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) |
| static readonly [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | PowerPoint Open XML Slide Show (.ppsx) Microsoft PowerPoint 2007 और उसके बाद के संस्करणों का उपयोग करके स्लाइड शो उद्देश्य के लिए बनाई गई फ़ाइल है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/presentation/ppsx) देखें। |
| static readonly [PPT](../../groupdocs.merger.domain/filetype/ppt) | PowerPoint Presentation (.ppt) PowerPoint फ़ाइल का प्रतिनिधित्व करता है जिसमें स्लाइडों का संग्रह होता है जिसे स्लाइडशो के रूप में प्रदर्शित किया जाता है। यह Microsoft PowerPoint 97-2003 द्वारा उपयोग किए जाने वाले बाइनरी फ़ाइल फ़ॉर्मेट को निर्दिष्ट करता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/presentation/ppt) देखें। |
| static readonly [PPTM](../../groupdocs.merger.domain/filetype/pptm) | PowerPoint Open XML Macro-Enabled Presentation |
| static readonly [PPTX](../../groupdocs.merger.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) एक प्रस्तुति फ़ाइल है जो लोकप्रिय Microsoft PowerPoint एप्लिकेशन द्वारा बनाई गई है। पहले के प्रस्तुति फ़ाइल फ़ॉर्मेट PPT जो बाइनरी था, के विपरीत, PPTX फ़ॉर्मेट Microsoft PowerPoint ओपन XML प्रस्तुति फ़ाइल फ़ॉर्मेट पर आधारित है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/presentation/pptx) देखें। |
| static readonly [PS](../../groupdocs.merger.domain/filetype/ps) | PostScript File (.ps) |
| static readonly [RAR](../../groupdocs.merger.domain/filetype/rar) | Roshal ARchive Compressed File (.rar) |
| static readonly [RTF](../../groupdocs.merger.domain/filetype/rtf) | Rich Text Format File (.rtf) Microsoft द्वारा प्रस्तुत और प्रलेखित, Rich Text Format (RTF) एक विधि का प्रतिनिधित्व करता है जो फ़ॉर्मेटेड टेक्स्ट और ग्राफिक्स को एप्लिकेशन के भीतर उपयोग के लिए एन्कोड करती है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/word-processing/rtf) देखें। |
| static readonly [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | 7-Zip Compressed File (.7z) |
| static readonly [SVG](../../groupdocs.merger.domain/filetype/svg) | Scalable Vector Graphics File (.svg) |
| static readonly [SVGZ](../../groupdocs.merger.domain/filetype/svgz) | Scalable Vector Graphics Compressed File (.svgz) |
| static readonly [TAR](../../groupdocs.merger.domain/filetype/tar) | Consolidated Unix File Archive (.tar) |
| static readonly [TEX](../../groupdocs.merger.domain/filetype/tex) | LaTeX Source Document (.tex) एक भाषा है जिसमें प्रोग्रामिंग और मार्क‑अप दोनों विशेषताएँ शामिल हैं, जिसका उपयोग दस्तावेज़ टाइपसेट करने के लिए किया जाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/page-description-language/tex) देखें। |
| static readonly [TIF](../../groupdocs.merger.domain/filetype/tif) | Tagged Image File (.tif) |
| static readonly [TIFF](../../groupdocs.merger.domain/filetype/tiff) | Tagged Image File Format (.tiff) |
| static readonly [TSV](../../groupdocs.merger.domain/filetype/tsv) | Tab Separated Values File (.tsv) डेटा को टैब द्वारा अलग किए गए साधारण टेक्स्ट फ़ॉर्मेट में दर्शाता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/spreadsheet/tsv) देखें। |
| static readonly [TXT](../../groupdocs.merger.domain/filetype/txt) | Plain Text File (.txt) एक टेक्स्ट दस्तावेज़ का प्रतिनिधित्व करता है जिसमें साधारण टेक्स्ट पंक्तियों के रूप में होता है। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/word-processing/txt) देखें। |
| static readonly [Unknown](../../groupdocs.merger.domain/filetype/unknown) | अज्ञात फ़ाइल प्रकार का प्रतिनिधित्व करता है। |
| static readonly [VDX](../../groupdocs.merger.domain/filetype/vdx) | Visio Drawing XML File (.vdx) Microsoft Visio में बनाया गया एक चित्र या चार्ट है, लेकिन XML प्रारूप में सहेजा गया है और इसका विस्तार .VDX है। Visio सॉफ़्टवेयर, जो Microsoft द्वारा विकसित किया गया है, में Visio drawing XML फ़ाइल बनाई जाती है। इस फ़ाइल स्वरूप के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/image/vdx). |
| static readonly [VSD](../../groupdocs.merger.domain/filetype/vsd) | Visio Drawing File (.vsd) |
| static readonly [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Visio Macro-Enabled Drawing (.vsdm) Microsoft Visio एप्लिकेशन के साथ बनाए गए ड्रॉइंग फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। VSDM फ़ाइलें OPC/XML ड्रॉइंग हैं जो VSDX के समान हैं, लेकिन फ़ाइल खोलने पर मैक्रो चलाने की क्षमता भी प्रदान करती हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/image/vsdm). |
| static readonly [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Visio Drawing (.vsdx) Microsoft Visio फ़ाइल स्वरूप का प्रतिनिधित्व करता है जो Microsoft Office 2013 से शुरू होकर पेश किया गया। इसे बाइनरी फ़ाइल स्वरूप .VSD को बदलने के लिए विकसित किया गया था, जो Microsoft Visio के पहले संस्करणों द्वारा समर्थित था। इस फ़ाइल स्वरूप के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/image/vsdx). |
| static readonly [VSS](../../groupdocs.merger.domain/filetype/vss) | Visio Stencil File(.vss) |
| static readonly [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Visio Macro-Enabled Stencil File (.vssm) Microsoft Visio स्टेंसिल फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। जब VSSM फ़ाइल खोली जाती है, तो यह डायग्राम में आकृतियों के वांछित स्वरूपण और स्थान निर्धारण के लिए मैक्रो चलाने की अनुमति देती है। इस फ़ाइल स्वरूप के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/image/vssm). |
| static readonly [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Visio Stencil File (.vssx) Microsoft Visio 2013 और उसके बाद के संस्करणों के साथ बनाए गए ड्रॉइंग स्टेंसिल हैं। VSSX फ़ाइल स्वरूप Visio 2013 और उसके बाद के संस्करणों में खोला जा सकता है। Visio फ़ाइलें विभिन्न ड्रॉइंग तत्वों जैसे आकृतियों का संग्रह, कनेक्टर, फ्लोचार्ट, नेटवर्क लेआउट, UML डायग्राम आदि के प्रतिनिधित्व के लिए जानी जाती हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/image/vssx). |
| static readonly [VST](../../groupdocs.merger.domain/filetype/vst) | Visio Drawing Template (.vst) |
| static readonly [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Visio Macro-Enabled Drawing Template (.vstm) Microsoft Visio के साथ बनाए गए टेम्पलेट फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। VSDX फ़ाइलों के विपरीत, VSTM टेम्पलेट से बनाई गई फ़ाइलें Visual Basic for Applications (VBA) कोड में विकसित मैक्रो चलाने में सक्षम होती हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/image/vstm). |
| static readonly [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Visio Drawing Template (.vstx) Microsoft Visio 2013 और उसके बाद के संस्करणों के साथ बनाए गए ड्रॉइंग टेम्पलेट फ़ाइलें हैं। ये VSTX फ़ाइलें Visio ड्रॉइंग बनाने के लिए प्रारंभिक बिंदु प्रदान करती हैं, जो .VSDX फ़ाइलों के रूप में सहेजी जाती हैं, और डिफ़ॉल्ट लेआउट और सेटिंग्स के साथ आती हैं। इस फ़ाइल स्वरूप के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/image/vstx). |
| static readonly [VSX](../../groupdocs.merger.domain/filetype/vsx) | Visio Stencil XML File (.vsx) उन स्टेंसिल को दर्शाता है जिनमें ड्रॉइंग और आकृतियां होती हैं जो Microsoft Visio में डायग्राम बनाने के लिए उपयोग की जाती हैं। VSX फ़ाइलें XML फ़ाइल स्वरूप में सहेजी जाती हैं और Visio 2013 तक समर्थित थीं। इस फ़ाइल स्वरूप के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/image/vsx). |
| static readonly [VTX](../../groupdocs.merger.domain/filetype/vtx) | Visio Template XML File (.vtx) एक Microsoft Visio ड्रॉइंग टेम्पलेट है जो XML फ़ाइल स्वरूप में डिस्क पर सहेजा जाता है। यह टेम्पलेट मूल सेटिंग्स वाली फ़ाइल प्रदान करने के लिए बनाया गया है, जिसका उपयोग समान सेटिंग्स वाली कई Visio फ़ाइलें बनाने में किया जा सकता है। इस फ़ाइल स्वरूप के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/image/vtx). |
| static readonly [WAV](../../groupdocs.merger.domain/filetype/wav) | WAV, जिसे WAVE (Waveform Audio File Format) के नाम से जाना जाता है, Microsoft के Resource Interchange File Format (RIFF) विनिर्देशन का एक उपसमुच्चय है जो डिजिटल ऑडियो फ़ाइलों को संग्रहीत करता है। यह स्वरूप बिटस्ट्रीम पर कोई संपीड़न लागू नहीं करता और विभिन्न सैंपलिंग रेट और बिटरेट के साथ ऑडियो रिकॉर्डिंग को संग्रहीत करता है। यह ऑडियो सीडीज़ के लिए मानक स्वरूपों में से एक रहा और अभी भी है। इस फ़ाइल स्वरूप के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/audio/wav). |
| static readonly [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Excel Macro-Enabled Add-In (.xlam) |
| static readonly [XLS](../../groupdocs.merger.domain/filetype/xls) | Excel Spreadsheet (.xls) एक फ़ाइल है जिसे Microsoft Excel के साथ-साथ OpenOffice Calc या Apple Numbers जैसे अन्य समान स्प्रेडशीट प्रोग्रामों द्वारा भी बनाया जा सकता है। इस फ़ाइल स्वरूप के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/spreadsheet/xls). |
| static readonly [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | Excel Binary Spreadsheet (.xlsb) फ़ाइल स्वरूप Excel Binary File Format को निर्दिष्ट करता है, जो रिकॉर्ड और संरचनाओं का संग्रह है जो Excel वर्कबुक की सामग्री को परिभाषित करता है। इस फ़ाइल स्वरूप के बारे में अधिक जानने के लिए [here](https://docs.fileformat.com/spreadsheet/xlsb). |
| static readonly [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) एक प्रकार की स्प्रेडशीट फ़ाइलें हैं जो मैक्रो का समर्थन करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/spreadsheet/xlsm) देखें। |
| static readonly [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) Microsoft Excel दस्तावेज़ों के लिए एक प्रसिद्ध फ़ॉर्मेट है जिसे Microsoft ने Microsoft Office 2007 के रिलीज़ के साथ पेश किया था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/spreadsheet/xlsx) देखें। |
| static readonly [XLT](../../groupdocs.merger.domain/filetype/xlt) | Excel Template File (.xlt) Microsoft Excel के साथ बनाई गई टेम्पलेट फ़ाइलें हैं, जो एक स्प्रेडशीट एप्लिकेशन है और Microsoft Office सूट का हिस्सा है। Microsoft Office 97-2003 ने नए XLT फ़ाइलें बनाने और इन्हें खोलने दोनों का समर्थन किया था। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/spreadsheet/xlt) देखें। |
| static readonly [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) उन फ़ाइलों को दर्शाता है जो Microsoft Excel द्वारा मैक्रो-सक्षम टेम्पलेट फ़ाइलों के रूप में उत्पन्न की जाती हैं। XLTM फ़ाइलें संरचना में XLTX के समान हैं, केवल बाद वाला मैक्रो के साथ टेम्पलेट फ़ाइलें बनाने का समर्थन नहीं करता। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/spreadsheet/xltm) देखें। |
| static readonly [XLTX](../../groupdocs.merger.domain/filetype/xltx) | Excel Open XML Spreadsheet Template (.xltx) फ़ाइलें Office OpenXML फ़ाइल फ़ॉर्मेट विनिर्देशों पर आधारित हैं। इन्हें एक मानक टेम्पलेट फ़ाइल बनाने के लिए उपयोग किया जाता है, जिसका उपयोग करके XLSX फ़ाइलें बनाई जा सकती हैं जो XLTX फ़ाइल में निर्दिष्ट समान सेटिंग्स प्रदर्शित करती हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/spreadsheet/xltx) देखें। |
| static readonly [XPS](../../groupdocs.merger.domain/filetype/xps) | XML Paper Specification File (.xps) उन पेज लेआउट फ़ाइलों को दर्शाता है जो Microsoft द्वारा निर्मित XML Paper Specifications पर आधारित हैं। इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानने के लिए [यहाँ](https://docs.fileformat.com/page-description-language/xps) देखें। |
| static readonly [ZIP](../../groupdocs.merger.domain/filetype/zip) | ज़िप्ड फ़ाइल (.zip) |

### टिप्पणियाँ

**Learn more**

* Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* Learn more about getting supported file types in code: [How to get supported file formats in code](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### साथ ही देखें

* namespace [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* assembly [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
