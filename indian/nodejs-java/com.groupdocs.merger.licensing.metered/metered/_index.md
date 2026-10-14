---
title: "मापित"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "Metered लाइसेंस लागू करने के लिए विधियाँ प्रदान करता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.merger.licensing.metered/metered/
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
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Metered कुंजियों के साथ उत्पाद सक्रिय करता है। |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | प्रोसेस किए गए MBs की मात्रा प्राप्त करता है। |
| [getConsumptionCredit()](#getConsumptionCredit--) | उपयोग किए गए क्रेडिट्स की मात्रा प्राप्त करता है |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| publicKey | java.lang.String | सार्वजनिक कुंजी। |
| privateKey | java.lang.String | निजी कुंजी। |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


प्रोसेस किए गए MBs की मात्रा प्राप्त करता है।

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


उपयोग किए गए क्रेडिट्स की मात्रा प्राप्त करता है

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
