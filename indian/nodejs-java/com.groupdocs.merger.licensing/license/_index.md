---
title: "License"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "घटक को लाइसेंस करने के लिए मेथड्स प्रदान करता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.merger.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

घटक को लाइसेंस करने के लिए विधियाँ प्रदान करता है। लाइसेंसिंग के बारे में अधिक जानने के लिए [here][].


[here]: https://purchase.groupdocs.com/faqs/licensing
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [License()](#License--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | घटक को लाइसेंस करता है। |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | घटक को लाइसेंस करता है। |
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


घटक को लाइसेंस करता है।

--------------------

> ```
> The following example demonstrates how to set a license
>  passing Stream of the license file.
>  
>  using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
>  {
>      GroupDocs.Merger.License lic = new GroupDocs.Merger.License();
>      lic.SetLicense(licenseStream);
>  }
> ```

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licenseStream | java.io.InputStream | लाइसेंस स्ट्रीम। |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


घटक को लाइसेंस करता है।

--------------------

> ```
> The following example demonstrates how to set a license
>  passing a path to the license file.
>  
>  string licensePath = "GroupDocs.Merger.lic";
>  GroupDocs.Merger.License lic = new GroupDocs.Merger.License();
>  lic.SetLicense(licensePath);
> ```

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licensePath | java.lang.String | लाइसेंस पथ। |

