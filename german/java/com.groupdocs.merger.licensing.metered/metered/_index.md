---
title: "Metered"
second_title: "GroupDocs.Merger für Java API-Referenz"
description: "Stellt Methoden zum Anwenden der Metered-Lizenz bereit."
type: docs
weight: 10
url: /de/java/com.groupdocs.merger.licensing.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Stellt Methoden zum Anwenden der [Metered][] Lizenz bereit.


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Metered()](#Metered--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Aktiviert das Produkt mit Metered-Schlüsseln. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Ruft die Menge der verarbeiteten MBs ab. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Ruft die Menge der verwendeten Credits ab. |
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Aktiviert das Produkt mit Metered-Schlüsseln.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| publicKey | java.lang.String | Der öffentliche Schlüssel. |
| privateKey | java.lang.String | Der private Schlüssel. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Ruft die Menge der verarbeiteten MBs ab.

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


Ruft die Menge der verwendeten Credits ab.

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
