---
title: "set_license 方法"
second_title: "适用于 Python via .NET 的 GroupDocs.Merger API 参考"
description: 
type: docs
url: /zh/python-net/groupdocs.merger/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

将许可证应用于当前进程。

```python
def set_license(self, license_source):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| license_source |  | 可以是指向 ``.lic`` 文件的字符串路径，或是可读取的类文件对象（file-like object），该对象会产生许可证字节。类文件输入会先写入临时文件，然后再传递给桥接层。 |

| 抛出 | 描述 |
| :- | :- |
| `TypeError` | 如果 ``license_source`` 既不是字符串路径，也不是可读取的类文件对象。 |

### 另见
* class [`License`](/merger/python-net/groupdocs.merger/license/)
