---
title: Merger
second_title: Referencia de API de GroupDocs.Merger para .NET
description: Inicializa una nueva instancia deMergergroupdocs.merger/merger clase.
type: docs
weight: 10
url: /es/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

Inicializa una nueva instancia de[`Merger`](../../merger) clase.

```csharp
public Merger(Stream document)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Stream | El flujo legible. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*document* es nulo. |

### Ver también

* class [Merger](../../merger)
* espacio de nombres [GroupDocs.Merger](../../merger)
* asamblea [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

Inicializa una nueva instancia de[`Merger`](../../merger) clase.

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Stream | El flujo legible. |
| loadOptions | ILoadOptions | Las opciones de carga de documentos. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*document* es nulo. |
| ArgumentNullException | arrojado cuando*loadOptions* es nulo. |

### Ver también

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* espacio de nombres [GroupDocs.Merger](../../merger)
* asamblea [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

Inicializa una nueva instancia de[`Merger`](../../merger) clase.

```csharp
public Merger(Stream document, MergerSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Stream | El flujo legible. |
| settings | MergerSettings | La configuración de fusión. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*document* es nulo. |
| ArgumentNullException | arrojado cuando*settings* es nulo. |

### Ver también

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* espacio de nombres [GroupDocs.Merger](../../merger)
* asamblea [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

Inicializa una nueva instancia de[`Merger`](../../merger) clase.

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Stream | El flujo legible. |
| loadOptions | ILoadOptions | Las opciones de carga de documentos. |
| settings | MergerSettings | La configuración de fusión. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*document* es nulo. |
| ArgumentNullException | arrojado cuando*loadOptions* es nulo. |
| ArgumentNullException | arrojado cuando*settings* es nulo. |

### Ver también

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* espacio de nombres [GroupDocs.Merger](../../merger)
* asamblea [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

Inicializa una nueva instancia de[`Merger`](../../merger) clase.

```csharp
public Merger(Func<Stream> getFileStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| getFileStream | Func`1 | El método que devuelve un flujo legible. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*getFileStream* es nulo. |

### Ver también

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* espacio de nombres [GroupDocs.Merger](../../merger)
* asamblea [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

Inicializa una nueva instancia de[`Merger`](../../merger) clase.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| getFileStream | Func`1 | El método que devuelve un flujo legible. |
| loadOptions | ILoadOptions | Las opciones de carga de documentos. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*getFileStream* es nulo. |
| ArgumentNullException | arrojado cuando*loadOptions* es nulo. |

### Ver también

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* espacio de nombres [GroupDocs.Merger](../../merger)
* asamblea [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

Inicializa una nueva instancia de[`Merger`](../../merger) clase.

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| getFileStream | Func`1 | El método que devuelve un flujo legible. |
| settings | MergerSettings | La configuración de fusión. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*getFileStream* es nulo. |
| ArgumentNullException | arrojado cuando*settings* es nulo. |

### Ver también

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* espacio de nombres [GroupDocs.Merger](../../merger)
* asamblea [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

Inicializa una nueva instancia de[`Merger`](../../merger) clase.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| getFileStream | Func`1 | El método que devuelve un flujo legible. |
| loadOptions | ILoadOptions | Las opciones de carga de documentos. |
| settings | MergerSettings | La configuración de fusión. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*getFileStream* es nulo. |
| ArgumentNullException | arrojado cuando*loadOptions* es nulo. |
| ArgumentNullException | arrojado cuando*settings* es nulo. |

### Ver también

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* espacio de nombres [GroupDocs.Merger](../../merger)
* asamblea [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

Inicializa una nueva instancia de[`Merger`](../../merger) clase.

```csharp
public Merger(string filePath)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*filePath* es nulo o vacío. |

### Ver también

* class [Merger](../../merger)
* espacio de nombres [GroupDocs.Merger](../../merger)
* asamblea [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

Inicializa una nueva instancia de[`Merger`](../../merger) clase.

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo. |
| loadOptions | ILoadOptions | Las opciones de carga de documentos. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*filePath* es nulo o vacío. |
| ArgumentNullException | arrojado cuando*loadOptions* es nulo. |

### Ver también

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* espacio de nombres [GroupDocs.Merger](../../merger)
* asamblea [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

Inicializa una nueva instancia de[`Merger`](../../merger) clase.

```csharp
public Merger(string filePath, MergerSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo. |
| settings | MergerSettings | La configuración de fusión. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*filePath* es nulo o vacío. |
| ArgumentNullException | arrojado cuando*settings* es nulo. |

### Ver también

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* espacio de nombres [GroupDocs.Merger](../../merger)
* asamblea [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

Inicializa una nueva instancia de[`Merger`](../../merger) clase.

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo. |
| loadOptions | ILoadOptions | Las opciones de carga de documentos. |
| settings | MergerSettings | La configuración de fusión. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*filePath* es nulo o vacío. |
| ArgumentNullException | arrojado cuando*loadOptions* es nulo. |
| ArgumentNullException | arrojado cuando*settings* es nulo. |

### Ver también

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* espacio de nombres [GroupDocs.Merger](../../merger)
* asamblea [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
