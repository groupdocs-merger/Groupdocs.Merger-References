---
title: "计量"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "提供用于应用 Metered 许可证的方法。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.merger.licensing.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

提供用于应用 [Metered][] 许可证。


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Metered()](#Metered--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | 使用 Metered 密钥激活产品。 |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 检索已处理的 MB 数量。 |
| [getConsumptionCredit()](#getConsumptionCredit--) | 检索已使用的积分数量 |
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


使用 Metered 密钥激活产品。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| publicKey | java.lang.String | 公共密钥。 |
| privateKey | java.lang.String | 私有密钥。 |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


检索已处理的 MB 数量。

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


检索已使用的积分数量

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
