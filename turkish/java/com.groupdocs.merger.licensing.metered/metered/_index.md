---
title: "Ölçümlü"
second_title: "GroupDocs.Merger için Java API Referansı"
description: "Ölçümlü lisansını uygulamak için yöntemler sağlar."
type: docs
weight: 10
url: /tr/java/com.groupdocs.merger.licensing.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Uygulamak için [Metered][] lisansı yöntemleri sağlar.


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Metered()](#Metered--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Metered anahtarlarla ürünü etkinleştirir. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | İşlenen MB miktarını alır. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Kullanılan kredi miktarını alır. |
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Metered anahtarlarla ürünü etkinleştirir.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| publicKey | java.lang.String | Açık anahtar. |
| privateKey | java.lang.String | Özel anahtar. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


İşlenen MB miktarını alır.

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


Kullanılan kredi miktarını alır.

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
