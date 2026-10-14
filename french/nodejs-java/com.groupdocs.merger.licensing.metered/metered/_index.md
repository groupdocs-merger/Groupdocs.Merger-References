---
title: "Mesuré"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Fournit des méthodes pour appliquer la licence Metered."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.merger.licensing.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Fournit des méthodes pour appliquer la licence [Metered][].


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Metered()](#Metered--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Active le produit avec les clés Metered. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Récupère la quantité de Mo traités. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Récupère la quantité de crédits utilisés |
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Active le produit avec les clés Metered.

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
| Paramètre | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | La clé publique. |
| privateKey | java.lang.String | La clé privée. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Récupère la quantité de Mo traités.

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


Récupère la quantité de crédits utilisés

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
