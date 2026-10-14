---
title: "ExtractOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Proporciona opciones para extraer las páginas del documento."
type: docs
weight: 11
url: /es/nodejs-java/com.groupdocs.merger.domain.options/extractoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IExtractOptions](../../com.groupdocs.merger.domain.options.interfaces/iextractoptions)
```
public class ExtractOptions extends PageOptions implements IExtractOptions
```

Proporciona opciones para extraer las páginas del documento.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ExtractOptions()](#ExtractOptions--) | Inicializa una nueva instancia de la clase [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions). |
| [ExtractOptions(int[] pageNumbers)](#ExtractOptions-int---) | Inicializa una nueva instancia de la clase [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions). |
| [ExtractOptions(int startNumber, int endNumber)](#ExtractOptions-int-int-) | Inicializa una nueva instancia de la clase [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions). |
| [ExtractOptions(int startNumber, int endNumber, int mode)](#ExtractOptions-int-int-int-) | Inicializa una nueva instancia de la clase [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions). |
### ExtractOptions() {#ExtractOptions--}
```
public ExtractOptions()
```


Inicializa una nueva instancia de la clase [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions).

### ExtractOptions(int[] pageNumbers) {#ExtractOptions-int---}
```
public ExtractOptions(int[] pageNumbers)
```


Inicializa una nueva instancia de la clase [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumbers | int[] | Números de página. |

### ExtractOptions(int startNumber, int endNumber) {#ExtractOptions-int-int-}
```
public ExtractOptions(int startNumber, int endNumber)
```


Inicializa una nueva instancia de la clase [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |

### ExtractOptions(int startNumber, int endNumber, int mode) {#ExtractOptions-int-int-int-}
```
public ExtractOptions(int startNumber, int endNumber, int mode)
```


Inicializa una nueva instancia de la clase [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |
| mode | int | El modo de rango. |

