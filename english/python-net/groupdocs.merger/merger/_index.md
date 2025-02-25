---
title: Merger class
second_title: GroupDocs.Merger for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.merger/merger/
is_root: false
weight: 30
---

## Merger class

Represents the main class that controls the document merging process.



The Merger type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/merger/python-net/groupdocs.merger/merger/__init__/#io.RawIOBase) | Initializes new instance of [`Merger`](/merger/python-net/groupdocs.merger/merger) class. |
| [__init__](/merger/python-net/groupdocs.merger/merger/__init__/#io.RawIOBase-groupdocs.merger.domain.options.ILoadOptions) | Initializes new instance of [`Merger`](/merger/python-net/groupdocs.merger/merger) class. |
| [__init__](/merger/python-net/groupdocs.merger/merger/__init__/#io.RawIOBase-groupdocs.merger.MergerSettings) | Initializes new instance of [`Merger`](/merger/python-net/groupdocs.merger/merger) class. |
| [__init__](/merger/python-net/groupdocs.merger/merger/__init__/#io.RawIOBase-groupdocs.merger.domain.options.ILoadOptions-groupdocs.merger.MergerSettings) | Initializes new instance of [`Merger`](/merger/python-net/groupdocs.merger/merger) class. |
| [__init__](/merger/python-net/groupdocs.merger/merger/__init__/#str) | Initializes new instance of [`Merger`](/merger/python-net/groupdocs.merger/merger) class. |
| [__init__](/merger/python-net/groupdocs.merger/merger/__init__/#str-groupdocs.merger.domain.options.ILoadOptions) | Initializes new instance of [`Merger`](/merger/python-net/groupdocs.merger/merger) class. |
| [__init__](/merger/python-net/groupdocs.merger/merger/__init__/#str-groupdocs.merger.MergerSettings) | Initializes new instance of [`Merger`](/merger/python-net/groupdocs.merger/merger) class. |
| [__init__](/merger/python-net/groupdocs.merger/merger/__init__/#str-groupdocs.merger.domain.options.ILoadOptions-groupdocs.merger.MergerSettings) | Initializes new instance of [`Merger`](/merger/python-net/groupdocs.merger/merger) class. |


### Methods
| Method | Description |
| :- | :- |
| [join](/merger/python-net/groupdocs.merger/merger/join/#io.RawIOBase) | Joins the documents into one single document. |
| [join](/merger/python-net/groupdocs.merger/merger/join/#io.RawIOBase-groupdocs.merger.domain.options.IJoinOptions) | Joins the documents into one single document. |
| [join](/merger/python-net/groupdocs.merger/merger/join/#io.RawIOBase-groupdocs.merger.domain.options.IPageJoinOptions) | Joins the documents into one single document. |
| [join](/merger/python-net/groupdocs.merger/merger/join/#io.RawIOBase-groupdocs.merger.domain.options.IImageJoinOptions) | Joins the documents into one single document. |
| [join](/merger/python-net/groupdocs.merger/merger/join/#str) | Joins the documents into one single document. |
| [join](/merger/python-net/groupdocs.merger/merger/join/#str-groupdocs.merger.domain.options.IJoinOptions) | Joins the documents into one single document. |
| [join](/merger/python-net/groupdocs.merger/merger/join/#str-groupdocs.merger.domain.options.IPageJoinOptions) | Joins the documents into one single document. |
| [join](/merger/python-net/groupdocs.merger/merger/join/#str-groupdocs.merger.domain.options.IImageJoinOptions) | Joins the documents into one single document. |
| [split](/merger/python-net/groupdocs.merger/merger/split/#groupdocs.merger.domain.options.ISplitOptions) | Splits the single document to the multiple documents. |
| [split](/merger/python-net/groupdocs.merger/merger/split/#groupdocs.merger.domain.options.ITextSplitOptions) | Splits the single document to the multiple documents. |
| [save](/merger/python-net/groupdocs.merger/merger/save/#io.RawIOBase) | Saves the result document to the stream `document`. |
| [save](/merger/python-net/groupdocs.merger/merger/save/#str) | Saves the result document file to `file_path`. |
| [save](/merger/python-net/groupdocs.merger/merger/save/#str-bool) | Saves the result document file to `file_path`. |
| [import_document](/merger/python-net/groupdocs.merger/merger/import_document/#groupdocs.merger.domain.options.IImportDocumentOptions) | Imports the document as attachment or embedded via Ole. |
| [create_page_builder](/merger/python-net/groupdocs.merger/merger/create_page_builder/#groupdocs.merger.domain.options.PageBuilderOptions) | Creates a new Page builder with predefined document collection. |
| [apply_page_builder](/merger/python-net/groupdocs.merger/merger/apply_page_builder/#groupdocs.merger.domain.builders.PageBuilder) | Applies page builder changes. |
| [extract_pages](/merger/python-net/groupdocs.merger/merger/extract_pages/#groupdocs.merger.domain.options.IExtractOptions) | Makes a new document with some pages from the source document. |
| [add_password](/merger/python-net/groupdocs.merger/merger/add_password/#groupdocs.merger.domain.options.IAddPasswordOptions) | Protects document with password. |
| [is_password_set](/merger/python-net/groupdocs.merger/merger/is_password_set/#) | Checks whether document is password protected. |
| [remove_password](/merger/python-net/groupdocs.merger/merger/remove_password/#) | Removes password from document. |
| [update_password](/merger/python-net/groupdocs.merger/merger/update_password/#groupdocs.merger.domain.options.IUpdatePasswordOptions) | Updates existing password for document. |
| [change_orientation](/merger/python-net/groupdocs.merger/merger/change_orientation/#groupdocs.merger.domain.options.IOrientationOptions) | Applies a new orientation mode for the specified pages. |
| [move_page](/merger/python-net/groupdocs.merger/merger/move_page/#groupdocs.merger.domain.options.IMoveOptions) | Moves page to a new position within document of known format. |
| [remove_pages](/merger/python-net/groupdocs.merger/merger/remove_pages/#groupdocs.merger.domain.options.IRemoveOptions) | Removes pages from document of known format. |
| [swap_pages](/merger/python-net/groupdocs.merger/merger/swap_pages/#groupdocs.merger.domain.options.ISwapOptions) | Swaps two pages within document of known format. |
| [rotate_pages](/merger/python-net/groupdocs.merger/merger/rotate_pages/#groupdocs.merger.domain.options.IRotateOptions) | Rotate pages of the document. |
| [get_document_info](/merger/python-net/groupdocs.merger/merger/get_document_info/#) | Gets information about document pages: their sizes, maximum page height, the width of a page with the maximum height. |
| [generate_preview](/merger/python-net/groupdocs.merger/merger/generate_preview/#groupdocs.merger.domain.options.IPreviewOptions) | Generates document pages preview. |



### See Also
* module [`groupdocs.merger`](..)
* class [`IMerger`](/merger/python-net/groupdocs.merger/imerger)
* class [`Merger`](/merger/python-net/groupdocs.merger/merger)
