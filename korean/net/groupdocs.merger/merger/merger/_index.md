---
title: Merger
second_title: .NET API 참조용 GroupDocs.Merger
description: 의 새 인스턴스를 초기화합니다.Mergergroupdocs.merger/merger 클래스.
type: docs
weight: 10
url: /ko/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

의 새 인스턴스를 초기화합니다.[`Merger`](../../merger) 클래스.

```csharp
public Merger(Stream document)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Stream | 읽을 수 있는 스트림입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*document* null입니다. |

### 또한보십시오

* class [Merger](../../merger)
* 네임스페이스 [GroupDocs.Merger](../../merger)
* 집회 [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

의 새 인스턴스를 초기화합니다.[`Merger`](../../merger) 클래스.

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Stream | 읽을 수 있는 스트림입니다. |
| loadOptions | ILoadOptions | 문서 로드 옵션. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*document* null입니다. |
| ArgumentNullException | 언제 던져*loadOptions* null입니다. |

### 또한보십시오

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* 네임스페이스 [GroupDocs.Merger](../../merger)
* 집회 [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

의 새 인스턴스를 초기화합니다.[`Merger`](../../merger) 클래스.

```csharp
public Merger(Stream document, MergerSettings settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Stream | 읽을 수 있는 스트림입니다. |
| settings | MergerSettings | 합병 설정. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*document* null입니다. |
| ArgumentNullException | 언제 던져*settings* null입니다. |

### 또한보십시오

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* 네임스페이스 [GroupDocs.Merger](../../merger)
* 집회 [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

의 새 인스턴스를 초기화합니다.[`Merger`](../../merger) 클래스.

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Stream | 읽을 수 있는 스트림입니다. |
| loadOptions | ILoadOptions | 문서 로드 옵션. |
| settings | MergerSettings | 합병 설정. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*document* null입니다. |
| ArgumentNullException | 언제 던져*loadOptions* null입니다. |
| ArgumentNullException | 언제 던져*settings* null입니다. |

### 또한보십시오

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* 네임스페이스 [GroupDocs.Merger](../../merger)
* 집회 [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

의 새 인스턴스를 초기화합니다.[`Merger`](../../merger) 클래스.

```csharp
public Merger(Func<Stream> getFileStream)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| getFileStream | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*getFileStream* null입니다. |

### 또한보십시오

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* 네임스페이스 [GroupDocs.Merger](../../merger)
* 집회 [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

의 새 인스턴스를 초기화합니다.[`Merger`](../../merger) 클래스.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| getFileStream | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드입니다. |
| loadOptions | ILoadOptions | 문서 로드 옵션. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*getFileStream* null입니다. |
| ArgumentNullException | 언제 던져*loadOptions* null입니다. |

### 또한보십시오

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* 네임스페이스 [GroupDocs.Merger](../../merger)
* 집회 [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

의 새 인스턴스를 초기화합니다.[`Merger`](../../merger) 클래스.

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| getFileStream | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드입니다. |
| settings | MergerSettings | 합병 설정. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*getFileStream* null입니다. |
| ArgumentNullException | 언제 던져*settings* null입니다. |

### 또한보십시오

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* 네임스페이스 [GroupDocs.Merger](../../merger)
* 집회 [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

의 새 인스턴스를 초기화합니다.[`Merger`](../../merger) 클래스.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| getFileStream | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드입니다. |
| loadOptions | ILoadOptions | 문서 로드 옵션. |
| settings | MergerSettings | 합병 설정. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*getFileStream* null입니다. |
| ArgumentNullException | 언제 던져*loadOptions* null입니다. |
| ArgumentNullException | 언제 던져*settings* null입니다. |

### 또한보십시오

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* 네임스페이스 [GroupDocs.Merger](../../merger)
* 집회 [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

의 새 인스턴스를 초기화합니다.[`Merger`](../../merger) 클래스.

```csharp
public Merger(string filePath)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 파일 경로입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*filePath* null이거나 비어 있습니다. |

### 또한보십시오

* class [Merger](../../merger)
* 네임스페이스 [GroupDocs.Merger](../../merger)
* 집회 [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

의 새 인스턴스를 초기화합니다.[`Merger`](../../merger) 클래스.

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 파일 경로입니다. |
| loadOptions | ILoadOptions | 문서 로드 옵션. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*filePath* null이거나 비어 있습니다. |
| ArgumentNullException | 언제 던져*loadOptions* null입니다. |

### 또한보십시오

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* 네임스페이스 [GroupDocs.Merger](../../merger)
* 집회 [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

의 새 인스턴스를 초기화합니다.[`Merger`](../../merger) 클래스.

```csharp
public Merger(string filePath, MergerSettings settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 파일 경로입니다. |
| settings | MergerSettings | 합병 설정. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*filePath* null이거나 비어 있습니다. |
| ArgumentNullException | 언제 던져*settings* null입니다. |

### 또한보십시오

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* 네임스페이스 [GroupDocs.Merger](../../merger)
* 집회 [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

의 새 인스턴스를 초기화합니다.[`Merger`](../../merger) 클래스.

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 파일 경로입니다. |
| loadOptions | ILoadOptions | 문서 로드 옵션. |
| settings | MergerSettings | 합병 설정. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*filePath* null이거나 비어 있습니다. |
| ArgumentNullException | 언제 던져*loadOptions* null입니다. |
| ArgumentNullException | 언제 던져*settings* null입니다. |

### 또한보십시오

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* 네임스페이스 [GroupDocs.Merger](../../merger)
* 집회 [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
