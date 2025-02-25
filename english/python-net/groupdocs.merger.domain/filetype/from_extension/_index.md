---
title: from_extension method
second_title: GroupDocs.Merger for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.merger.domain/filetype/from_extension/
is_root: false
weight: 30
---

## from_extension {#str}

Maps file extension to file type.


### Returns 


When file type is supported returns it, otherwise returns default [`FileType.Unknown`](/merger/python-net/groupdocs.merger.domain/filetype) file type.


```python
def from_extension(self, extension):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| extension | str | File extension (including the period "."). |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `extension` is null or empty string. |





### See Also
* module [`groupdocs.merger.domain`](../../)
* class [`FileType`](/merger/python-net/groupdocs.merger.domain/filetype)
