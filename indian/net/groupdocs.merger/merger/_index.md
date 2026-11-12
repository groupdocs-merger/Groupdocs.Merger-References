---
title: "मर्जर"
second_title: "GroupDocs.Merger .NET के लिए API संदर्भ"
description: "दस्तावेज़ मर्ज प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास का प्रतिनिधित्व करता है।"
type: docs
weight: 960
url: /hi/net/groupdocs.merger/merger/
---
## Merger class

दस्तावेज़ मर्ज प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास का प्रतिनिधित्व करता है।

```csharp
public class Merger : IDisposable, IMerger
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Merger](merger#constructor)(Func&lt;Stream&gt;) | नया इंस्टेंस इनिशियलाइज़ करता है [`Merger`](../merger) क्लास का। |
| [Merger](merger#constructor_4)(Stream) | नया इंस्टेंस इनिशियलाइज़ करता है [`Merger`](../merger) क्लास का। |
| [Merger](merger#constructor_8)(string) | नया इंस्टेंस इनिशियलाइज़ करता है [`Merger`](../merger) क्लास का। |
| [Merger](merger#constructor_1)(Func&lt;Stream&gt;, ILoadOptions) | नया इंस्टेंस इनिशियलाइज़ करता है [`Merger`](../merger) क्लास का। |
| [Merger](merger#constructor_3)(Func&lt;Stream&gt;, MergerSettings) | नया इंस्टेंस इनिशियलाइज़ करता है [`Merger`](../merger) क्लास का। |
| [Merger](merger#constructor_5)(Stream, ILoadOptions) | नया इंस्टेंस इनिशियलाइज़ करता है [`Merger`](../merger) क्लास का। |
| [Merger](merger#constructor_7)(Stream, MergerSettings) | नया इंस्टेंस इनिशियलाइज़ करता है [`Merger`](../merger) क्लास का। |
| [Merger](merger#constructor_9)(string, ILoadOptions) | नया इंस्टेंस इनिशियलाइज़ करता है [`Merger`](../merger) क्लास का। |
| [Merger](merger#constructor_11)(string, MergerSettings) | नया इंस्टेंस इनिशियलाइज़ करता है [`Merger`](../merger) क्लास का। |
| [Merger](merger#constructor_2)(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) | नया इंस्टेंस इनिशियलाइज़ करता है [`Merger`](../merger) क्लास का। |
| [Merger](merger#constructor_6)(Stream, ILoadOptions, MergerSettings) | नया इंस्टेंस इनिशियलाइज़ करता है [`Merger`](../merger) क्लास का। |
| [Merger](merger#constructor_10)(string, ILoadOptions, MergerSettings) | नया इंस्टेंस इनिशियलाइज़ करता है [`Merger`](../merger) क्लास का। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddPassword](../../groupdocs.merger/merger/addpassword)(IAddPasswordOptions) | दस्तावेज़ को पासवर्ड से सुरक्षित करता है। |
| [ApplyPageBuilder](../../groupdocs.merger/merger/applypagebuilder)(PageBuilder) | पेज बिल्डर में बदलाव लागू करता है। |
| [ChangeOrientation](../../groupdocs.merger/merger/changeorientation)(IOrientationOptions) | निर्दिष्ट पेजों के लिए नया ओरिएंटेशन मोड लागू करता है। |
| [CreatePageBuilder](../../groupdocs.merger/merger/createpagebuilder)(PageBuilderOptions) | पूर्वनिर्धारित दस्तावेज़ संग्रह के साथ नया पेज बिल्डर बनाता है। |
| [Dispose](../../groupdocs.merger/merger/dispose)() | संसाधनों को डिस्पोज़ करता है। |
| [ExtractPages](../../groupdocs.merger/merger/extractpages)(IExtractOptions) | स्रोत दस्तावेज़ से कुछ पेजों के साथ नया दस्तावेज़ बनाता है। |
| [GeneratePreview](../../groupdocs.merger/merger/generatepreview)(IPreviewOptions) | दस्तावेज़ पेजों का प्रीव्यू जेनरेट करता है। |
| [GetDocumentInfo](../../groupdocs.merger/merger/getdocumentinfo)() | दस्तावेज़ पेजों के बारे में जानकारी प्राप्त करता है: उनके आकार, अधिकतम पेज ऊँचाई, और अधिकतम ऊँचाई वाले पेज की चौड़ाई। |
| [ImportDocument](../../groupdocs.merger/merger/importdocument)(IImportDocumentOptions) | दस्तावेज़ को अटैचमेंट या Ole के माध्यम से एम्बेडेड के रूप में इम्पोर्ट करता है। |
| [IsPasswordSet](../../groupdocs.merger/merger/ispasswordset)() | जाँचता है कि दस्तावेज़ पासवर्ड से सुरक्षित है या नहीं। |
| [Join](../../groupdocs.merger/merger/join#join)(Stream) | दस्तावेज़ों को एक ही दस्तावेज़ में जोड़ता है। |
| [Join](../../groupdocs.merger/merger/join#join_4)(string) | दस्तावेज़ों को एक ही दस्तावेज़ में जोड़ता है। |
| [Join](../../groupdocs.merger/merger/join#join_1)(Stream, IImageJoinOptions) | दस्तावेज़ों को एक ही दस्तावेज़ में जोड़ता है। |
| [Join](../../groupdocs.merger/merger/join#join_2)(Stream, IJoinOptions) | दस्तावेज़ों को एक ही दस्तावेज़ में जोड़ता है। |
| [Join](../../groupdocs.merger/merger/join#join_3)(Stream, IPageJoinOptions) | दस्तावेज़ों को एक ही दस्तावेज़ में जोड़ता है। |
| [Join](../../groupdocs.merger/merger/join#join_5)(string, IImageJoinOptions) | दस्तावेज़ों को एक ही दस्तावेज़ में जोड़ता है। |
| [Join](../../groupdocs.merger/merger/join#join_6)(string, IJoinOptions) | दस्तावेज़ों को एक ही दस्तावेज़ में जोड़ता है। |
| [Join](../../groupdocs.merger/merger/join#join_7)(string, IPageJoinOptions) | दस्तावेज़ों को एक ही दस्तावेज़ में जोड़ता है। |
| [MovePage](../../groupdocs.merger/merger/movepage)(IMoveOptions) | ज्ञात फ़ॉर्मेट के दस्तावेज़ में पेज को नई स्थिति में ले जाता है। |
| [RemovePages](../../groupdocs.merger/merger/removepages)(IRemoveOptions) | ज्ञात फ़ॉर्मेट के दस्तावेज़ से पेज हटाता है। |
| [RemovePassword](../../groupdocs.merger/merger/removepassword)() | दस्तावेज़ से पासवर्ड हटाता है। |
| [Rotate](../../groupdocs.merger/merger/rotate)(IRotateOptions) | दस्तावेज़ की इमेज या पेजों को घुमाता है। |
| [Save](../../groupdocs.merger/merger/save#save)(Stream, ISaveOptions) | परिणाम दस्तावेज़ को स्ट्रीम *document* में सहेजता है। |
| [Save](../../groupdocs.merger/merger/save#save_2)(string, ISaveOptions) | परिणाम दस्तावेज़ फ़ाइल को *filePath* में सहेजता है। |
| [Save](../../groupdocs.merger/merger/save#save_1)(string, bool, ISaveOptions) | परिणाम दस्तावेज़ फ़ाइल को *filePath* में सहेजता है। |
| [Split](../../groupdocs.merger/merger/split#split)(ISplitOptions) | एकल दस्तावेज़ को कई दस्तावेज़ों में विभाजित करता है। |
| [Split](../../groupdocs.merger/merger/split#split_1)(ITextSplitOptions) | एकल दस्तावेज़ को कई दस्तावेज़ों में विभाजित करता है। |
| [SwapPages](../../groupdocs.merger/merger/swappages)(ISwapOptions) | ज्ञात प्रारूप के दस्तावेज़ में दो पृष्ठों की अदला‑बदली करता है। |
| [UpdatePassword](../../groupdocs.merger/merger/updatepassword)(IUpdatePasswordOptions) | दस्तावेज़ के मौजूदा पासवर्ड को अपडेट करता है। |

### साथ ही देखें

* interface [IMerger](../imerger)
* namespace [GroupDocs.Merger](../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
