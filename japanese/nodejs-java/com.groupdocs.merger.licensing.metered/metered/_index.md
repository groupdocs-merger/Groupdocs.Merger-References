---
title: "Metered"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "Metered ライセンスを適用するためのメソッドを提供します。"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.merger.licensing.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

[Metered][] ライセンスを適用するためのメソッドを提供します。


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Metered()](#Metered--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Metered キーで製品を有効化します。 |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 処理された MB の量を取得します。 |
| [getConsumptionCredit()](#getConsumptionCredit--) | 使用されたクレジットの量を取得します |
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Metered キーで製品を有効化します。

--------------------

> ```
> Following example demonstrates how to activate product with Metered keys.
>  
>  string publicKey = "Public Key";
>  string privateKey = "Private Key";
>  Metered metered = new Metered();
>  metered.SetMeteredKey(publicKey, privateKey);
> ```

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| publicKey | java.lang.String | 公開鍵です。 |
| privateKey | java.lang.String | 秘密鍵です。 |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


処理された MB の量を取得します。

--------------------

> ```
> Following example demonstrates how to retrieve amount of MBs processed.
>   
>   string publicKey = "Public Key";
>   string privateKey = "Private Key";
> 
>   Metered metered = new Metered();
>   metered.SetMeteredKey(publicKey, privateKey);
>   decimal mbProcessed = Metered.GetConsumptionQuantity();
> ```

**Returns:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


使用されたクレジットの量を取得します

--------------------

> ```
> Following example demonstrates how to retrieve amount of MBs processed.
>   
>   string publicKey = "Public Key";
>   string privateKey = "Private Key";
> 
>   Metered metered = new Metered();
>   metered.SetMeteredKey(publicKey, privateKey);
>   decimal usedCredits = Metered.GetConsumptionCredit();
> ```

**Returns:**
double
