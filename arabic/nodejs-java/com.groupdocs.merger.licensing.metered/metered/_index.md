---
title: "مقاس"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "يوفر طرقًا لتطبيق ترخيص Metered."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.merger.licensing.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

يوفر طرقًا لتطبيق ترخيص [Metered][].


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Metered()](#Metered--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | يفعل المنتج باستخدام مفاتيح Metered. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | يسترجع مقدار الـ MBs المعالجة. |
| [getConsumptionCredit()](#getConsumptionCredit--) | يسترجع مقدار الاعتمادات المستخدمة |
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


يفعل المنتج باستخدام مفاتيح Metered.

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| publicKey | java.lang.String | المفتاح العام. |
| privateKey | java.lang.String | المفتاح الخاص. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


يسترجع مقدار الـ MBs المعالجة.

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


يسترجع مقدار الاعتمادات المستخدمة

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
