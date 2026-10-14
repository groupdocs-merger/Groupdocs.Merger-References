---
title: "Metered"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Proporciona métodos para aplicar la licencia Metered."
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.merger.licensing.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Proporciona métodos para aplicar la licencia [Metered][]


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Metered()](#Metered--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Activa el producto con claves Metered. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Recupera la cantidad de MB procesados. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Recupera la cantidad de créditos utilizados |
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Activa el producto con claves Metered.

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| publicKey | java.lang.String | La clave pública. |
| privateKey | java.lang.String | La clave privada. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Recupera la cantidad de MB procesados.

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


Recupera la cantidad de créditos utilizados

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
