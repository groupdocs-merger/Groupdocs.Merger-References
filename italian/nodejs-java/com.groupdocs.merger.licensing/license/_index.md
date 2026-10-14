---
title: "License"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Fornisce metodi per licenziare il componente."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.merger.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Fornisce metodi per licenziare il componente. Scopri di più sulla licenza [qui][].


[here]: https://purchase.groupdocs.com/faqs/licensing
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [License()](#License--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Licenzia il componente. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licenzia il componente. |
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Licenzia il componente.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licenseStream | java.io.InputStream | Il flusso di licenza. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Licenzia il componente.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licensePath | java.lang.String | Il percorso della licenza. |

