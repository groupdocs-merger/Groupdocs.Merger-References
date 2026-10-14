---
title: "License"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Proporciona métodos para licenciar el componente."
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.merger.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Proporciona métodos para licenciar el componente. Obtén más información sobre licencias [aquí][].


[here]: https://purchase.groupdocs.com/faqs/licensing
## Constructores

| Constructor | Descripción |
| --- | --- |
| [License()](#License--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Licencia el componente. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licencia el componente. |
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Licencia el componente.

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| licenseStream | java.io.InputStream | El flujo de licencia. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Licencia el componente.

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| licensePath | java.lang.String | La ruta de licencia. |

