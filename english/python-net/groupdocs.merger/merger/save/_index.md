---
title: save method
second_title: GroupDocs.Merger for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.merger/merger/save/
is_root: false
weight: 160
---

## save {#io.RawIOBase}

Saves the result document to the stream `document`.



```python
def save(self, document):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | io.RawIOBase | The document stream. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `document` is null. |




## save {#str}

Saves the result document file to `file_path`.



```python
def save(self, file_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | str | The file name or full file path. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `file_path` is null or empty. |




## save {#str-bool}

Saves the result document file to `file_path`.



```python
def save(self, file_path, use_default_directory):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | str | The file path or name in case of default directory usage. |
| use_default_directory | bool | Use the default directory from settings. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `file_path` is null or empty. |





### See Also
* module [`groupdocs.merger`](../../)
* class [`Merger`](/merger/python-net/groupdocs.merger/merger)
