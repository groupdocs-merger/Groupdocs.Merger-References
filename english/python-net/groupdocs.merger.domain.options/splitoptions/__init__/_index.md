---
title: SplitOptions constructor
second_title: GroupDocs.Merger for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.merger.domain.options/splitoptions/__init__/
is_root: false
weight: 10
---

## __init__ {#str-list}

Initializes a new instance of the [`SplitOptions`](/merger/python-net/groupdocs.merger.domain.options/splitoptions) class.



```python
def __init__(self, file_path_format, page_numbers):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path_format | str | The file path format e.g. 'c:/split{0}.doc' or 'c:/split{0}.{1}' with already pre-defined extension. |
| page_numbers | list | Page numbers. |


## __init__ {#str-list-groupdocs.merger.domain.options.SplitMode}

Initializes a new instance of the [`SplitOptions`](/merger/python-net/groupdocs.merger.domain.options/splitoptions) class.



```python
def __init__(self, file_path_format, page_numbers, split_mode):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path_format | str | The file path format e.g. 'c:/split{0}.doc' or 'c:/split{0}.{1}' with already pre-defined extension. |
| page_numbers | list | Page numbers. |
| split_mode | [`SplitMode`](/merger/python-net/groupdocs.merger.domain.options/splitmode) | The splitting mode of [`SplitOptions.mode`](/merger/python-net/groupdocs.merger.domain.options/splitoptions#mode). |


## __init__ {#str-int-int}

Initializes a new instance of the [`SplitOptions`](/merger/python-net/groupdocs.merger.domain.options/splitoptions) class.



```python
def __init__(self, file_path_format, start_number, end_number):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path_format | str | The file path format e.g. 'c:/split{0}.doc' or 'c:/split{0}.{1}' with already pre-defined extension. |
| start_number | int | The start page number. |
| end_number | int | The end page number. |


## __init__ {#str-int-int-groupdocs.merger.domain.options.RangeMode}

Initializes a new instance of the [`SplitOptions`](/merger/python-net/groupdocs.merger.domain.options/splitoptions) class.



```python
def __init__(self, file_path_format, start_number, end_number, mode):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path_format | str | The file path format e.g. 'c:/split{0}.doc' or 'c:/split{0}.{1}' with already pre-defined extension. |
| start_number | int | The start page number. |
| end_number | int | The end page number. |
| mode | [`RangeMode`](/merger/python-net/groupdocs.merger.domain.options/rangemode) | The range mode. |



### See Also
* module [`groupdocs.merger.domain.options`](../../)
* class [`SplitOptions`](/merger/python-net/groupdocs.merger.domain.options/splitoptions)
