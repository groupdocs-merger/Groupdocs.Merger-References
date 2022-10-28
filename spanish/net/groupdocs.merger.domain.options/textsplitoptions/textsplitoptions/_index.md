---
title: TextSplitOptions
second_title: Referencia de API de GroupDocs.Merger para .NET
description: Inicializa una nueva instancia delTextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions clase.
type: docs
weight: 10
url: /es/net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

Inicializa una nueva instancia del[`TextSplitOptions`](../../textsplitoptions) clase.

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePathFormat | String | El formato de la ruta del archivo, por ejemplo, 'c:/split{0}.doc' o 'c:/split{0}.{1}' con una extensión ya definida. |
| lineNumbers | Int32[] | Números de línea para dividir texto. |

### Ver también

* class [TextSplitOptions](../../textsplitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* asamblea [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

Inicializa una nueva instancia del[`TextSplitOptions`](../../textsplitoptions) clase.

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePathFormat | String | El formato de la ruta del archivo, por ejemplo, 'c:/split{0}.doc' o 'c:/split{0}.{1}' con una extensión ya definida. |
| mode | TextSplitMode | Modo de división de texto. |
| lineNumbers | Int32[] | Números de línea para dividir texto. |

### Ver también

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* asamblea [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

Inicializa una nueva instancia del[`TextSplitOptions`](../../textsplitoptions) clase.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | El método que instancia el flujo utilizado para escribir datos divididos de salida. |
| lineNumbers | Int32[] | Números de línea para dividir texto. |

### Ver también

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* asamblea [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

Inicializa una nueva instancia del[`TextSplitOptions`](../../textsplitoptions) clase.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | El método que instancia el flujo utilizado para escribir datos divididos de salida. |
| mode | TextSplitMode | Modo de división de texto. |
| lineNumbers | Int32[] | Números de línea para dividir texto. |

### Ver también

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* asamblea [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

Inicializa una nueva instancia del[`TextSplitOptions`](../../textsplitoptions) clase.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | El método que instancia el flujo utilizado para escribir datos divididos de salida. |
| releaseSplitStream | ReleaseSplitStream | El método que libera el flujo creado por el método createPageStream. |
| lineNumbers | Int32[] | Números de línea para dividir texto. |

### Ver también

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* asamblea [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

Inicializa una nueva instancia del[`TextSplitOptions`](../../textsplitoptions) clase.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | El método que instancia el flujo utilizado para escribir datos divididos de salida. |
| releaseSplitStream | ReleaseSplitStream | El método que libera el flujo creado por el método createPageStream. |
| mode | TextSplitMode | Modo de división de texto. |
| lineNumbers | Int32[] | Números de línea para dividir texto. |

### Ver también

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* asamblea [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
