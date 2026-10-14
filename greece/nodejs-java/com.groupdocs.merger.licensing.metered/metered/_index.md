---
title: "Μετρημένο"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Παρέχει μεθόδους για την εφαρμογή της άδειας Metered."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.merger.licensing.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Παρέχει μεθόδους για την εφαρμογή της άδειας [Metered][].


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Metered()](#Metered--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ενεργοποιεί το προϊόν με κλειδιά Metered. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Ανακτά το ποσό των επεξεργασμένων MB. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Ανακτά το ποσό των χρησιμοποιημένων πιστώσεων |
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Ενεργοποιεί το προϊόν με κλειδιά Metered.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| publicKey | java.lang.String | Το δημόσιο κλειδί. |
| privateKey | java.lang.String | Το ιδιωτικό κλειδί. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Ανακτά το ποσό των επεξεργασμένων MB.

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


Ανακτά το ποσό των χρησιμοποιημένων πιστώσεων

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
