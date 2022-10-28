---
title: SplitOptions
second_title: Referencia de API de GroupDocs.Merger para .NET
description: Inicializa una nueva instancia delSplitOptionsgroupdocs.merger.domain.options/splitoptions clase.
type: docs
weight: 10
url: /es/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

Inicializa una nueva instancia del[`SplitOptions`](../../splitoptions) clase.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePathFormat | String | El formato de la ruta del archivo, por ejemplo, 'c:/split{0}.doc' o 'c:/split{0}.{1}' con una extensión ya predefinida. |
| pageNumbers | Int32[] | Número de páginas. |

### Ver también

* class [SplitOptions](../../splitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../splitoptions)
* asamblea [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

Inicializa una nueva instancia del[`SplitOptions`](../../splitoptions) clase.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePathFormat | String | El formato de la ruta del archivo, por ejemplo, 'c:/split{0}.doc' o 'c:/split{0}.{1}' con una extensión ya predefinida. |
| pageNumbers | Int32[] | Número de páginas. |
| splitMode | SplitMode | El modo de división de[`Mode`](../mode). |

### Ver también

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../splitoptions)
* asamblea [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

Inicializa una nueva instancia del[`SplitOptions`](../../splitoptions) clase.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePathFormat | String | El formato de la ruta del archivo, por ejemplo, 'c:/split{0}.doc' o 'c:/split{0}.{1}' con una extensión ya predefinida. |
| startNumber | Int32 | El número de la página de inicio. |
| endNumber | Int32 | El número de página final. |

### Ver también

* class [SplitOptions](../../splitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../splitoptions)
* asamblea [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

Inicializa una nueva instancia del[`SplitOptions`](../../splitoptions) clase.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePathFormat | String | El formato de la ruta del archivo, por ejemplo, 'c:/split{0}.doc' o 'c:/split{0}.{1}' con una extensión ya predefinida. |
| startNumber | Int32 | El número de la página de inicio. |
| endNumber | Int32 | El número de página final. |
| mode | RangeMode | El modo de rango. |

### Ver también

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../splitoptions)
* asamblea [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

Inicializa una nueva instancia del[`SplitOptions`](../../splitoptions) clase.

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | El método que instancia el flujo utilizado para escribir datos divididos de salida. |

### Ver también

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../splitoptions)
* asamblea [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

Inicializa una nueva instancia del[`SplitOptions`](../../splitoptions) clase.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | El método que instancia el flujo utilizado para escribir datos divididos de salida. |
| pageNumbers | Int32[] | Número de páginas. |

### Ver también

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../splitoptions)
* asamblea [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

Inicializa una nueva instancia del[`SplitOptions`](../../splitoptions) clase.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | El método que instancia el flujo utilizado para escribir datos divididos de salida. |
| pageNumbers | Int32[] | Número de páginas. |
| splitMode | SplitMode | El modo de división de[`Mode`](../mode). |

### Ver también

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../splitoptions)
* asamblea [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

Inicializa una nueva instancia del[`SplitOptions`](../../splitoptions) clase.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | El método que instancia el flujo utilizado para escribir datos divididos de salida. |
| startNumber | Int32 | El número de la página de inicio. |
| endNumber | Int32 | El número de página final. |

### Ver también

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../splitoptions)
* asamblea [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

Inicializa una nueva instancia del[`SplitOptions`](../../splitoptions) clase.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | El método que instancia el flujo utilizado para escribir datos divididos de salida. |
| startNumber | Int32 | El número de la página de inicio. |
| endNumber | Int32 | El número de página final. |
| mode | RangeMode | El modo de rango. |

### Ver también

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../splitoptions)
* asamblea [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

Inicializa una nueva instancia del[`SplitOptions`](../../splitoptions) clase.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | El método que instancia el flujo utilizado para escribir datos divididos de salida. |
| releaseSplitStream | ReleaseSplitStream | El método que libera el flujo creado por el método createPageStream. |

### Ver también

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../splitoptions)
* asamblea [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

Inicializa una nueva instancia del[`SplitOptions`](../../splitoptions) clase.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | El método que instancia el flujo utilizado para escribir datos divididos de salida. |
| releaseSplitStream | ReleaseSplitStream | El método que libera el flujo creado por el método createPageStream. |
| pageNumbers | Int32[] | Número de páginas. |

### Ver también

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../splitoptions)
* asamblea [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

Inicializa una nueva instancia del[`SplitOptions`](../../splitoptions) clase.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | El método que instancia el flujo utilizado para escribir datos divididos de salida. |
| releaseSplitStream | ReleaseSplitStream | El método que libera el flujo creado por el método createPageStream. |
| pageNumbers | Int32[] | Número de páginas. |
| splitMode | SplitMode | El modo de división de[`Mode`](../mode). |

### Ver también

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../splitoptions)
* asamblea [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

Inicializa una nueva instancia del[`SplitOptions`](../../splitoptions) clase.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | El método que instancia el flujo utilizado para escribir datos divididos de salida. |
| releaseSplitStream | ReleaseSplitStream | El método que libera el flujo creado por el método createPageStream. |
| startNumber | Int32 | El número de la página de inicio. |
| endNumber | Int32 | El número de página final. |

### Ver también

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../splitoptions)
* asamblea [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

Inicializa una nueva instancia del[`SplitOptions`](../../splitoptions) clase.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | El método que instancia el flujo utilizado para escribir datos divididos de salida. |
| releaseSplitStream | ReleaseSplitStream | El método que libera el flujo creado por el método createPageStream. |
| startNumber | Int32 | El número de la página de inicio. |
| endNumber | Int32 | El número de página final. |
| mode | RangeMode | El modo de rango. |

### Ver también

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* espacio de nombres [GroupDocs.Merger.Domain.Options](../../splitoptions)
* asamblea [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
