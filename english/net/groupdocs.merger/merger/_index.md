---
title: Merger
second_title: GroupDocs.Merger for .NET API Reference
description: Represents the main class that controls the document merging process.
type: docs
weight: 890
url: /net/groupdocs.merger/merger/
---
## Merger class

Represents the main class that controls the document merging process.

```csharp
public class Merger : IDisposable, IMerger
```

## Constructors

| Name | Description |
| --- | --- |
| [Merger](merger#constructor)(Func&lt;Stream&gt;) | Initializes new instance of [`Merger`](../merger) class. |
| [Merger](merger#constructor_4)(Stream) | Initializes new instance of [`Merger`](../merger) class. |
| [Merger](merger#constructor_8)(string) | Initializes new instance of [`Merger`](../merger) class. |
| [Merger](merger#constructor_1)(Func&lt;Stream&gt;, ILoadOptions) | Initializes new instance of [`Merger`](../merger) class. |
| [Merger](merger#constructor_3)(Func&lt;Stream&gt;, MergerSettings) | Initializes new instance of [`Merger`](../merger) class. |
| [Merger](merger#constructor_5)(Stream, ILoadOptions) | Initializes new instance of [`Merger`](../merger) class. |
| [Merger](merger#constructor_7)(Stream, MergerSettings) | Initializes new instance of [`Merger`](../merger) class. |
| [Merger](merger#constructor_9)(string, ILoadOptions) | Initializes new instance of [`Merger`](../merger) class. |
| [Merger](merger#constructor_11)(string, MergerSettings) | Initializes new instance of [`Merger`](../merger) class. |
| [Merger](merger#constructor_2)(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) | Initializes new instance of [`Merger`](../merger) class. |
| [Merger](merger#constructor_6)(Stream, ILoadOptions, MergerSettings) | Initializes new instance of [`Merger`](../merger) class. |
| [Merger](merger#constructor_10)(string, ILoadOptions, MergerSettings) | Initializes new instance of [`Merger`](../merger) class. |

## Methods

| Name | Description |
| --- | --- |
| [AddPassword](../../groupdocs.merger/merger/addpassword)(IAddPasswordOptions) | Protects document with password. |
| [ApplyPageBuilder](../../groupdocs.merger/merger/applypagebuilder)(PageBuilder) | Applies page builder changes. |
| [ChangeOrientation](../../groupdocs.merger/merger/changeorientation)(IOrientationOptions) | Applies a new orientation mode for the specified pages. |
| [CreatePageBuilder](../../groupdocs.merger/merger/createpagebuilder)(PageBuilderOptions) | Creates a new Page builder with predefined document collection. |
| [Dispose](../../groupdocs.merger/merger/dispose)() | Disposes resources. |
| [ExtractPages](../../groupdocs.merger/merger/extractpages)(IExtractOptions) | Makes a new document with some pages from the source document. |
| [GeneratePreview](../../groupdocs.merger/merger/generatepreview)(IPreviewOptions) | Generates document pages preview. |
| [GetDocumentInfo](../../groupdocs.merger/merger/getdocumentinfo)() | Gets information about document pages: their sizes, maximum page height, the width of a page with the maximum height. |
| [ImportDocument](../../groupdocs.merger/merger/importdocument)(IImportDocumentOptions) | Imports the document as attachment or embedded via Ole. |
| [IsPasswordSet](../../groupdocs.merger/merger/ispasswordset)() | Checks whether document is password protected. |
| [Join](../../groupdocs.merger/merger/join#join)(Stream) | Joins the documents into one single document. |
| [Join](../../groupdocs.merger/merger/join#join_4)(string) | Joins the documents into one single document. |
| [Join](../../groupdocs.merger/merger/join#join_1)(Stream, IImageJoinOptions) | Joins the documents into one single document. |
| [Join](../../groupdocs.merger/merger/join#join_2)(Stream, IJoinOptions) | Joins the documents into one single document. |
| [Join](../../groupdocs.merger/merger/join#join_3)(Stream, IPageJoinOptions) | Joins the documents into one single document. |
| [Join](../../groupdocs.merger/merger/join#join_5)(string, IImageJoinOptions) | Joins the documents into one single document. |
| [Join](../../groupdocs.merger/merger/join#join_6)(string, IJoinOptions) | Joins the documents into one single document. |
| [Join](../../groupdocs.merger/merger/join#join_7)(string, IPageJoinOptions) | Joins the documents into one single document. |
| [MovePage](../../groupdocs.merger/merger/movepage)(IMoveOptions) | Moves page to a new position within document of known format. |
| [RemovePages](../../groupdocs.merger/merger/removepages)(IRemoveOptions) | Removes pages from document of known format. |
| [RemovePassword](../../groupdocs.merger/merger/removepassword)() | Removes password from document. |
| [Rotate](../../groupdocs.merger/merger/rotate)(IRotateOptions) | Rotate image or pages of the document. |
| [Save](../../groupdocs.merger/merger/save#save)(Stream) | Saves the result document to the stream *document*. |
| [Save](../../groupdocs.merger/merger/save#save_1)(string) | Saves the result document file to *filePath*. |
| [Save](../../groupdocs.merger/merger/save#save_2)(string, bool) | Saves the result document file to *filePath*. |
| [Split](../../groupdocs.merger/merger/split#split)(ISplitOptions) | Splits the single document to the multiple documents. |
| [Split](../../groupdocs.merger/merger/split#split_1)(ITextSplitOptions) | Splits the single document to the multiple documents. |
| [SwapPages](../../groupdocs.merger/merger/swappages)(ISwapOptions) | Swaps two pages within document of known format. |
| [UpdatePassword](../../groupdocs.merger/merger/updatepassword)(IUpdatePasswordOptions) | Updates existing password for document. |

### See Also

* interface [IMerger](../imerger)
* namespace [GroupDocs.Merger](../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
