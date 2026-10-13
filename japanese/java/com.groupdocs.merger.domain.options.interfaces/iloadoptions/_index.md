---
title: "ILoadOptions"
second_title: "Java 用 GroupDocs.Merger API リファレンス"
description: "ドキュメント読み込みオプション用インターフェイス。"
type: docs
weight: 15
url: /ja/java/com.groupdocs.merger.domain.options.interfaces/iloadoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ILoadOptions extends IOptions
```

ドキュメント読み込みオプション用インターフェイス。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getType()](#getType--) | 開くファイルのタイプです。 |
| [getPassword()](#getPassword--) | パスワードで保護されたファイルを開くためのパスワード。 |
| [getExtension()](#getExtension--) | 開くファイルの拡張子。 |
| [getEncoding()](#getEncoding--) | テキストベースのファイル（例: [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) または [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT)）を開く際に使用されるエンコーディング。 |
### getType() {#getType--}
```
public abstract FileType getType()
```


開くファイルのタイプです。

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


パスワードで保護されたファイルを開くためのパスワード。

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


開くファイルの拡張子。

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public abstract Charset getEncoding()
```


テキストベースのファイル（例: [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) または [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT)）を開く際に使用されるエンコーディング。デフォルト値は [DefaultCharset][] です。


[DefaultCharset]: https://docs.oracle.com/javase/7/docs/api/java/nio/charset/Charset.html#defaultCharset%28%29

**Returns:**
java.nio.charset.Charset
