---
title: FuncT1T2TResult
second_title: GroupDocs.Merger for .NET API リファレンス
description: 2 つのパラメーターを持ちメソッドによって指定された型の値を返すメソッドをカプセル化しますTResultパラメータ.
type: docs
weight: 50
url: /ja/net/groupdocs.merger.domain.common/func-3/
---
## Func&lt;T1,T2,TResult&gt; delegate

2 つのパラメーターを持ち、メソッドによって指定された型の値を返すメソッドをカプセル化します。*TResult*パラメータ.

```csharp
public delegate TResult Func<in T1, in T2, out TResult>(T1 arg1, T2 arg2);
```

| パラメータ | 説明 |
| --- | --- |
| T1 | このデリゲートがカプセル化するメソッドの最初のパラメーターの型。 |
| T2 | このデリゲートがカプセル化するメソッドの 2 番目のパラメーターの型。 |
| TResult | このデリゲートがカプセル化するメソッドの戻り値の型。 |
| arg1 | このデリゲートがカプセル化するメソッドの最初のパラメーター。 |
| arg2 | このデリゲートがカプセル化するメソッドの 2 番目のパラメーター。 |

### 戻り値

このデリゲートがカプセル化するメソッドの戻り値。

### 関連項目

* 名前空間 [GroupDocs.Merger.Domain.Common](../../groupdocs.merger.domain.common)
* 組み立て [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->