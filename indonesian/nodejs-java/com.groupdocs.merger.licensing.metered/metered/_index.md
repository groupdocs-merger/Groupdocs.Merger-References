---
title: "Metered"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Menyediakan metode untuk menerapkan lisensi Metered."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.merger.licensing.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Menyediakan metode untuk menerapkan lisensi [Metered][].


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [Metered()](#Metered--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Mengaktifkan produk dengan kunci Metered. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Mengambil jumlah MB yang diproses. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Mengambil jumlah kredit yang digunakan |
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Mengaktifkan produk dengan kunci Metered.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| publicKey | java.lang.String | Kunci publik. |
| privateKey | java.lang.String | Kunci pribadi. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Mengambil jumlah MB yang diproses.

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


Mengambil jumlah kredit yang digunakan

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
