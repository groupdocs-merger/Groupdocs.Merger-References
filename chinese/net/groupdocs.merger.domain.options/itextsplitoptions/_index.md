---
title: ITextSplitOptions
second_title: GroupDocs.Merger for .NET API 参考
description: 文本拆分选项的界面
type: docs
weight: 360
url: /zh/net/groupdocs.merger.domain.options/itextsplitoptions/
---
## ITextSplitOptions interface

文本拆分选项的界面。

```csharp
public interface ITextSplitOptions : IOptions
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/itextsplitoptions/createstream) { get; } | 定义创建输出拆分流的方法的委托。 |
| [LineNumbers](../../groupdocs.merger.domain.options/itextsplitoptions/linenumbers) { get; } | 文本拆分的行号。 |
| [Mode](../../groupdocs.merger.domain.options/itextsplitoptions/mode) { get; } | 文本拆分模式。 |
| [ReleaseStream](../../groupdocs.merger.domain.options/itextsplitoptions/releasestream) { get; } | 定义释放输出拆分流的方法的委托。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetPathByIndex](../../groupdocs.merger.domain.options/itextsplitoptions/getpathbyindex)(int, string) | 通过定义的扩展名的索引获取拆分文档的完整文件路径。 |
| [Validate](../../groupdocs.merger.domain.options/itextsplitoptions/validate)(FileType) | 验证拆分选项。 |

### 也可以看看

* interface [IOptions](../ioptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* 部件 [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
