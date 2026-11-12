---
title: "Metered"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "Metered 라이선스를 적용하기 위한 메서드를 제공합니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.merger.licensing.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

[Metered][] 라이선스를 적용하기 위한 메서드를 제공합니다.


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Metered()](#Metered--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Metered 키를 사용하여 제품을 활성화합니다. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 처리된 MB 양을 가져옵니다. |
| [getConsumptionCredit()](#getConsumptionCredit--) | 사용된 크레딧 양을 가져옵니다. |
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Metered 키를 사용하여 제품을 활성화합니다.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| publicKey | java.lang.String | 공개 키. |
| privateKey | java.lang.String | 개인 키. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


처리된 MB 양을 가져옵니다.

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
java.math.BigDecimal
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


사용된 크레딧 양을 가져옵니다.

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
java.math.BigDecimal
