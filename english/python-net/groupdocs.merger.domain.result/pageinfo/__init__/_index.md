---
title: PageInfo constructor
second_title: GroupDocs.Merger for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.merger.domain.result/pageinfo/__init__/
is_root: false
weight: 10
---

## __init__ {#int-bool}

Initializes new instance of [`PageInfo`](/merger/python-net/groupdocs.merger.domain.result/pageinfo) class.



```python
def __init__(self, number, visible):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| number | int | The page number. |
| visible | bool | The page visibility indicator. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `number` is less or equal to zero. |




## __init__ {#int-bool-int-int}

Initializes new instance of [`PageInfo`](/merger/python-net/groupdocs.merger.domain.result/pageinfo) class.



```python
def __init__(self, number, visible, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| number | int | The page number. |
| visible | bool | The page visibility indicator. |
| width | int | The width of the page in pixels when viewing as JPG or PNG. |
| height | int | The height of the page in pixels when viewing as JPG or PNG. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `number` is less or equal to zero. |
| ArgumentException | Thrown when `width` is less or equal to zero. |
| ArgumentException | Thrown when `height` is less or equal to zero. |





### See Also
* module [`groupdocs.merger.domain.result`](../../)
* class [`PageInfo`](/merger/python-net/groupdocs.merger.domain.result/pageinfo)
