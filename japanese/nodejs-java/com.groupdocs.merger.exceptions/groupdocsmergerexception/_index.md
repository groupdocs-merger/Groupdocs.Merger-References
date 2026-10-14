---
title: "GroupDocsMergerException"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "ドキュメント処理中に発生するエラーを表します。"
type: docs
weight: 12
url: /ja/nodejs-java/com.groupdocs.merger.exceptions/groupdocsmergerexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception
```
public class GroupDocsMergerException extends Exception
```

ドキュメント処理中に発生するエラーを表します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [GroupDocsMergerException(String message)](#GroupDocsMergerException-java.lang.String-) | 新しいインスタンスを初期化します [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) クラス。 |
| [GroupDocsMergerException(String message, Exception innerException)](#GroupDocsMergerException-java.lang.String-java.lang.Exception-) | 新しいインスタンスを初期化します [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) クラス。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getException(Exception exception)](#getException-java.lang.Exception-) | 入力例外から GroupDocs Merger 例外を取得します。 |
### GroupDocsMergerException(String message) {#GroupDocsMergerException-java.lang.String-}
```
public GroupDocsMergerException(String message)
```


新しいインスタンスを初期化します [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) クラス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | エラーを説明するメッセージです。 |

### GroupDocsMergerException(String message, Exception innerException) {#GroupDocsMergerException-java.lang.String-java.lang.Exception-}
```
public GroupDocsMergerException(String message, Exception innerException)
```


新しいインスタンスを初期化します [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) クラス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | エラーを説明するメッセージです。 |
| innerException | java.lang.Exception | エラーの内部例外です。 |

### getException(Exception exception) {#getException-java.lang.Exception-}
```
public static Exception getException(Exception exception)
```


入力例外から GroupDocs Merger 例外を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 例外 | java.lang.Exception | 入力例外です。 |

**Returns:**
java.lang.Exception -
