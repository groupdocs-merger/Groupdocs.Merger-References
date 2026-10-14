---
title: "Licence"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Fournit des méthodes pour licencier le composant."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.merger.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Fournit des méthodes pour licencier le composant. En savoir plus sur la licence [ici][].


[here]: https://purchase.groupdocs.com/faqs/licensing
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [License()](#License--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Licence le composant. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licence le composant. |
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Licence le composant.

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
| Paramètre | Type | Description |
| --- | --- | --- |
| licenseStream | java.io.InputStream | Le flux de licence. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Licence le composant.

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
| Paramètre | Type | Description |
| --- | --- | --- |
| licensePath | java.lang.String | Le chemin de licence. |

