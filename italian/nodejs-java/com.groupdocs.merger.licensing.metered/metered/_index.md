---
title: "Metered"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Fornisce metodi per applicare la licenza Metered."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.merger.licensing.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Fornisce metodi per applicare la licenza [Metered][].


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Metered()](#Metered--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Attiva il prodotto con chiavi Metered. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Recupera la quantità di MB elaborati. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Recupera la quantità di crediti utilizzati |
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Attiva il prodotto con chiavi Metered.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| publicKey | java.lang.String | La chiave pubblica. |
| privateKey | java.lang.String | La chiave privata. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Recupera la quantità di MB elaborati.

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


Recupera la quantità di crediti utilizzati

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
