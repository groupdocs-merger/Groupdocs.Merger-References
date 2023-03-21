---
title: Merger
second_title: .NET API संदर्भ के लिए GroupDocs.Merger
description: दस्तवेज़ वलय प्रक्रय क नयंत्रत करने वले मुख्य वर्ग क प्रतनधत्व करत है
type: docs
weight: 790
url: /hi/net/groupdocs.merger/merger/
---
## Merger class

दस्तावेज़ विलय प्रक्रिया को नियंत्रित करने वाले मुख्य वर्ग का प्रतिनिधित्व करता है।

```csharp
public class Merger : IDisposable
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Merger](merger#constructor)(Func&lt;Stream&gt;) | का नया उदाहरण शुरू करता है[`Merger`](../merger) वर्ग. |
| [Merger](merger#constructor_4)(Stream) | का नया उदाहरण शुरू करता है[`Merger`](../merger) वर्ग. |
| [Merger](merger#constructor_8)(string) | का नया उदाहरण शुरू करता है[`Merger`](../merger) वर्ग. |
| [Merger](merger#constructor_1)(Func&lt;Stream&gt;, ILoadOptions) | का नया उदाहरण शुरू करता है[`Merger`](../merger) वर्ग. |
| [Merger](merger#constructor_3)(Func&lt;Stream&gt;, MergerSettings) | का नया उदाहरण शुरू करता है[`Merger`](../merger) वर्ग. |
| [Merger](merger#constructor_5)(Stream, ILoadOptions) | का नया उदाहरण शुरू करता है[`Merger`](../merger) वर्ग. |
| [Merger](merger#constructor_7)(Stream, MergerSettings) | का नया उदाहरण शुरू करता है[`Merger`](../merger) वर्ग. |
| [Merger](merger#constructor_9)(string, ILoadOptions) | का नया उदाहरण शुरू करता है[`Merger`](../merger) वर्ग. |
| [Merger](merger#constructor_11)(string, MergerSettings) | का नया उदाहरण शुरू करता है[`Merger`](../merger) वर्ग. |
| [Merger](merger#constructor_2)(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) | का नया उदाहरण शुरू करता है[`Merger`](../merger) वर्ग. |
| [Merger](merger#constructor_6)(Stream, ILoadOptions, MergerSettings) | का नया उदाहरण शुरू करता है[`Merger`](../merger) वर्ग. |
| [Merger](merger#constructor_10)(string, ILoadOptions, MergerSettings) | का नया उदाहरण शुरू करता है[`Merger`](../merger) वर्ग. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddPassword](../../groupdocs.merger/merger/addpassword)(IAddPasswordOptions) | दस्तावेज़ को पासवर्ड से सुरक्षित रखता है. |
| [ChangeOrientation](../../groupdocs.merger/merger/changeorientation)(IOrientationOptions) | निर्दिष्ट पृष्ठों के लिए एक नया ओरिएंटेशन मोड लागू करता है। |
| [Dispose](../../groupdocs.merger/merger/dispose)() | संसाधनों का निपटान करता है। |
| [ExtractPages](../../groupdocs.merger/merger/extractpages)(IExtractOptions) | स्रोत दस्तावेज़ से कुछ पृष्ठों के साथ एक नया दस्तावेज़ बनाता है। |
| [GeneratePreview](../../groupdocs.merger/merger/generatepreview)(IPreviewOptions) | दस्तावेज़ पृष्ठों का पूर्वावलोकन बनाता है. |
| [GetDocumentInfo](../../groupdocs.merger/merger/getdocumentinfo)() | दस्तावेज़ पृष्ठों के बारे में जानकारी प्राप्त करता है: उनके आकार, अधिकतम पृष्ठ ऊंचाई, अधिकतम ऊंचाई वाले पृष्ठ की चौड़ाई। |
| [ImportDocument](../../groupdocs.merger/merger/importdocument)(IImportDocumentOptions) | दस्तावेज़ को अनुलग्नक के रूप में आयात करता है या ओले के माध्यम से एम्बेड किया जाता है. |
| [IsPasswordSet](../../groupdocs.merger/merger/ispasswordset)() | जांचता है कि दस्तावेज़ पासवर्ड से सुरक्षित है या नहीं. |
| [Join](../../groupdocs.merger/merger/join#join)(Stream) | दस्तावेज़ों को एक दस्तावेज़ में जोड़ता है. |
| [Join](../../groupdocs.merger/merger/join#join_3)(string) | दस्तावेज़ों को एक दस्तावेज़ में जोड़ता है. |
| [Join](../../groupdocs.merger/merger/join#join_1)(Stream, IImageJoinOptions) | दस्तावेज़ों को एक दस्तावेज़ में जोड़ता है. |
| [Join](../../groupdocs.merger/merger/join#join_2)(Stream, IJoinOptions) | दस्तावेज़ों को एक दस्तावेज़ में जोड़ता है. |
| [Join](../../groupdocs.merger/merger/join#join_4)(string, IImageJoinOptions) | दस्तावेज़ों को एक दस्तावेज़ में जोड़ता है. |
| [Join](../../groupdocs.merger/merger/join#join_5)(string, IJoinOptions) | दस्तावेज़ों को एक दस्तावेज़ में जोड़ता है. |
| [MovePage](../../groupdocs.merger/merger/movepage)(IMoveOptions) | ज्ञात प्रारूप के दस्तावेज़ के भीतर पृष्ठ को एक नई स्थिति में ले जाता है। |
| [RemovePages](../../groupdocs.merger/merger/removepages)(IRemoveOptions) | ज्ञात प्रारूप के दस्तावेज़ से पृष्ठ निकालता है। |
| [RemovePassword](../../groupdocs.merger/merger/removepassword)() | दस्तावेज़ से पासवर्ड निकालता है. |
| [RotatePages](../../groupdocs.merger/merger/rotatepages)(IRotateOptions) | दस्तावेज़ के पृष्ठों को घुमाएं. |
| [Save](../../groupdocs.merger/merger/save#save)(Stream) | परिणाम दस्तावेज़ को स्ट्रीम में सहेजता है*document* . |
| [Save](../../groupdocs.merger/merger/save#save_1)(string) | परिणाम दस्तावेज़ फ़ाइल को इसमें सहेजता है*filePath* . |
| [Save](../../groupdocs.merger/merger/save#save_2)(string, bool) | परिणाम दस्तावेज़ फ़ाइल को इसमें सहेजता है*filePath* . |
| [Split](../../groupdocs.merger/merger/split#split)(ISplitOptions) | एक दस्तावेज़ को कई दस्तावेज़ों में विभाजित करता है। |
| [Split](../../groupdocs.merger/merger/split#split_1)(ITextSplitOptions) | एक दस्तावेज़ को कई दस्तावेज़ों में विभाजित करता है। |
| [SwapPages](../../groupdocs.merger/merger/swappages)(ISwapOptions) | ज्ञात प्रारूप के दस्तावेज़ के भीतर दो पृष्ठों को स्वैप करता है। |
| [UpdatePassword](../../groupdocs.merger/merger/updatepassword)(IUpdatePasswordOptions) | दस्तावेज़ के लिए मौजूदा पासवर्ड अपडेट करता है। |

### यह सभी देखें

* नाम स्थान [GroupDocs.Merger](../../groupdocs.merger)
* सभा [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
