---
title: LoadOptions constructor
second_title: GroupDocs.Merger for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.merger.domain.options/loadoptions/__init__/
is_root: false
weight: 10
---

## __init__ {#groupdocs.merger.domain.FileType}

Initializes new instance of [`LoadOptions`](/merger/python-net/groupdocs.merger.domain.options/loadoptions) class.



```python
def __init__(self, file_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_type | [`FileType`](/merger/python-net/groupdocs.merger.domain/filetype) | The type of the file to load. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `file_type` is null. |




## __init__ {#str}

Initializes new instance of [`LoadOptions`](/merger/python-net/groupdocs.merger.domain.options/loadoptions) class.



```python
def __init__(self, password):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| password | str | The password for opening password-protected file. |


## __init__ {#str-System.Text.Encoding}

Initializes new instance of [`LoadOptions`](/merger/python-net/groupdocs.merger.domain.options/loadoptions) class.



```python
def __init__(self, password, encoding):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| password | str | The password for opening password-protected file. |
| encoding | System.Text.Encoding | The encoding used when opening text-based files such as [`FileType.CSV`](/merger/python-net/groupdocs.merger.domain/filetype) or [`FileType.TXT`](/merger/python-net/groupdocs.merger.domain/filetype). |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `encoding` is null. |




## __init__ {#groupdocs.merger.domain.FileType-str}

Initializes new instance of [`LoadOptions`](/merger/python-net/groupdocs.merger.domain.options/loadoptions) class.



```python
def __init__(self, file_type, password):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_type | [`FileType`](/merger/python-net/groupdocs.merger.domain/filetype) | The type of the file to load. |
| password | str | The password for opening password-protected file. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `file_type` is null. |




## __init__ {#groupdocs.merger.domain.FileType-groupdocs.merger.domain.FileType}

Initializes new instance of [`LoadOptions`](/merger/python-net/groupdocs.merger.domain.options/loadoptions) class.



```python
def __init__(self, ini_file_type, file_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| ini_file_type | [`FileType`](/merger/python-net/groupdocs.merger.domain/filetype) | The type of the file to init. |
| file_type | [`FileType`](/merger/python-net/groupdocs.merger.domain/filetype) | The type of the file to load. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `ini_file_type` is null. |
| ArgumentNullException | Thrown when `file_type` is null. |




## __init__ {#groupdocs.merger.domain.FileType-str-System.Text.Encoding}

Initializes new instance of [`LoadOptions`](/merger/python-net/groupdocs.merger.domain.options/loadoptions) class.



```python
def __init__(self, file_type, password, encoding):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_type | [`FileType`](/merger/python-net/groupdocs.merger.domain/filetype) | The type of the file to load. |
| password | str | The password for opening password-protected file. |
| encoding | System.Text.Encoding | The encoding used when opening text-based files such as [`FileType.CSV`](/merger/python-net/groupdocs.merger.domain/filetype) or [`FileType.TXT`](/merger/python-net/groupdocs.merger.domain/filetype). |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `file_type` is null. |
| ArgumentNullException | Thrown when `encoding` is null. |




## __init__ {#groupdocs.merger.domain.FileType-groupdocs.merger.domain.FileType-str}

Initializes new instance of [`LoadOptions`](/merger/python-net/groupdocs.merger.domain.options/loadoptions) class.



```python
def __init__(self, ini_file_type, file_type, password):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| ini_file_type | [`FileType`](/merger/python-net/groupdocs.merger.domain/filetype) | The type of the file to init. |
| file_type | [`FileType`](/merger/python-net/groupdocs.merger.domain/filetype) | The type of the file to load. |
| password | str | The password for opening password-protected file. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `ini_file_type` is null. |
| ArgumentNullException | Thrown when `file_type` is null. |




## __init__ {#str-groupdocs.merger.domain.FileType-str-System.Text.Encoding}

Initializes new instance of [`LoadOptions`](/merger/python-net/groupdocs.merger.domain.options/loadoptions) class.



```python
def __init__(self, extension, file_type, password, encoding):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| extension | str | The extension of the file to load. |
| file_type | [`FileType`](/merger/python-net/groupdocs.merger.domain/filetype) | The type of the file to load. |
| password | str | The password for opening password-protected file. |
| encoding | System.Text.Encoding | The encoding used when opening text-based files such as [`FileType.CSV`](/merger/python-net/groupdocs.merger.domain/filetype) or [`FileType.TXT`](/merger/python-net/groupdocs.merger.domain/filetype). |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `file_type` is null. |
| ArgumentNullException | Thrown when `encoding` is null. |




## __init__ {#groupdocs.merger.domain.FileType-groupdocs.merger.domain.FileType-str-System.Text.Encoding}

Initializes new instance of [`LoadOptions`](/merger/python-net/groupdocs.merger.domain.options/loadoptions) class.



```python
def __init__(self, ini_file_type, file_type, password, encoding):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| ini_file_type | [`FileType`](/merger/python-net/groupdocs.merger.domain/filetype) | The type of the file to init. |
| file_type | [`FileType`](/merger/python-net/groupdocs.merger.domain/filetype) | The type of the file to load. |
| password | str | The password for opening password-protected file. |
| encoding | System.Text.Encoding | The encoding used when opening text-based files such as [`FileType.CSV`](/merger/python-net/groupdocs.merger.domain/filetype) or [`FileType.TXT`](/merger/python-net/groupdocs.merger.domain/filetype). |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `ini_file_type` is null. |
| ArgumentNullException | Thrown when `file_type` is null. |
| ArgumentNullException | Thrown when `encoding` is null. |





### See Also
* module [`groupdocs.merger.domain.options`](../../)
* class [`LoadOptions`](/merger/python-net/groupdocs.merger.domain.options/loadoptions)
