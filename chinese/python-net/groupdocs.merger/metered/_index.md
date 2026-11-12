---
title: "Metered 类"
second_title: "适用于 Python via .NET 的 GroupDocs.Merger API 参考"
description: 
type: docs
url: /zh/python-net/groupdocs.merger/metered/
is_root: false
weight: 90
---


## Metered class

管理计量（按使用付费）许可。

Metered 许可证根据实际消耗计费（通常是页面或
已处理的文档）。设置公钥/私钥对一次于
应用启动时；包装器将使用情况报告回 GroupDocs
后台的许可证服务器。

该 Metered 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [get_consumption_credit](/merger/python-net/groupdocs.merger/metered/get_consumption_credit/) | 返回当前密钥的剩余计量信用。 |
| [get_consumption_quantity](/merger/python-net/groupdocs.merger/metered/get_consumption_quantity/) | 返回迄今为止已消耗的计量总量。 |
| [set_metered_key](/merger/python-net/groupdocs.merger/metered/set_metered_key/#public_key-private_key) | 使用给定的公钥/私钥对激活计量计费。 |

### 另见
* module [`groupdocs.merger`](/merger/python-net/groupdocs.merger/)
