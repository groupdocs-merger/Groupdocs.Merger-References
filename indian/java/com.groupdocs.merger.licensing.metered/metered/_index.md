---
title: "मेटर्ड"
second_title: "GroupDocs.Merger के लिए Java API संदर्भ"
description: "Metered लाइसेंस लागू करने के लिए विधियाँ प्रदान करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.merger.licensing.metered/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

[Metered][] लाइसेंस लागू करने के लिए विधियाँ प्रदान करता है।


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Metered()](#Metered--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Metered कुंजियों के साथ उत्पाद सक्रिय करता है। |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | प्रोसेस किए गए MB की मात्रा प्राप्त करता है। |
| [getConsumptionCredit()](#getConsumptionCredit--) | उपयोग किए गए क्रेडिट की मात्रा प्राप्त करता है |
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Metered कुंजियों के साथ उत्पाद सक्रिय करता है।

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| publicKey | java.lang.String | सार्वजनिक कुंजी। |
| privateKey | java.lang.String | निजी कुंजी। |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


प्रोसेस किए गए MB की मात्रा प्राप्त करता है।

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


उपयोग किए गए क्रेडिट की मात्रा प्राप्त करता है

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
