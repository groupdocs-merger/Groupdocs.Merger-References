---
title: SplitOptions
second_title: .NET API 참조용 GroupDocs.Merger
description: 의 새 인스턴스를 초기화합니다.SplitOptionsgroupdocs.merger.domain.options/splitoptions 클래스.
type: docs
weight: 10
url: /ko/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

의 새 인스턴스를 초기화합니다.[`SplitOptions`](../../splitoptions) 클래스.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePathFormat | String | 이미 사전 정의된 확장자가 있는 파일 경로 형식(예: 'c:/split{0}.doc' 또는 'c:/split{0}.{1}'). |
| pageNumbers | Int32[] | 페이지 번호. |

### 또한보십시오

* class [SplitOptions](../../splitoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

의 새 인스턴스를 초기화합니다.[`SplitOptions`](../../splitoptions) 클래스.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePathFormat | String | 이미 사전 정의된 확장자가 있는 파일 경로 형식(예: 'c:/split{0}.doc' 또는 'c:/split{0}.{1}'). |
| pageNumbers | Int32[] | 페이지 번호. |
| splitMode | SplitMode | 의 분할 모드[`Mode`](../mode). |

### 또한보십시오

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

의 새 인스턴스를 초기화합니다.[`SplitOptions`](../../splitoptions) 클래스.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePathFormat | String | 이미 사전 정의된 확장자가 있는 파일 경로 형식(예: 'c:/split{0}.doc' 또는 'c:/split{0}.{1}'). |
| startNumber | Int32 | 시작 페이지 번호입니다. |
| endNumber | Int32 | 끝 페이지 번호입니다. |

### 또한보십시오

* class [SplitOptions](../../splitoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

의 새 인스턴스를 초기화합니다.[`SplitOptions`](../../splitoptions) 클래스.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePathFormat | String | 이미 사전 정의된 확장자가 있는 파일 경로 형식(예: 'c:/split{0}.doc' 또는 'c:/split{0}.{1}'). |
| startNumber | Int32 | 시작 페이지 번호입니다. |
| endNumber | Int32 | 끝 페이지 번호입니다. |
| mode | RangeMode | 범위 모드입니다. |

### 또한보십시오

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

의 새 인스턴스를 초기화합니다.[`SplitOptions`](../../splitoptions) 클래스.

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |

### 또한보십시오

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

의 새 인스턴스를 초기화합니다.[`SplitOptions`](../../splitoptions) 클래스.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| pageNumbers | Int32[] | 페이지 번호. |

### 또한보십시오

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

의 새 인스턴스를 초기화합니다.[`SplitOptions`](../../splitoptions) 클래스.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| pageNumbers | Int32[] | 페이지 번호. |
| splitMode | SplitMode | 의 분할 모드[`Mode`](../mode). |

### 또한보십시오

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

의 새 인스턴스를 초기화합니다.[`SplitOptions`](../../splitoptions) 클래스.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| startNumber | Int32 | 시작 페이지 번호입니다. |
| endNumber | Int32 | 끝 페이지 번호입니다. |

### 또한보십시오

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

의 새 인스턴스를 초기화합니다.[`SplitOptions`](../../splitoptions) 클래스.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| startNumber | Int32 | 시작 페이지 번호입니다. |
| endNumber | Int32 | 끝 페이지 번호입니다. |
| mode | RangeMode | 범위 모드입니다. |

### 또한보십시오

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

의 새 인스턴스를 초기화합니다.[`SplitOptions`](../../splitoptions) 클래스.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| releaseSplitStream | ReleaseSplitStream | createPageStream 메소드로 생성된 스트림을 해제하는 메소드. |

### 또한보십시오

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

의 새 인스턴스를 초기화합니다.[`SplitOptions`](../../splitoptions) 클래스.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| releaseSplitStream | ReleaseSplitStream | createPageStream 메소드로 생성된 스트림을 해제하는 메소드. |
| pageNumbers | Int32[] | 페이지 번호. |

### 또한보십시오

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

의 새 인스턴스를 초기화합니다.[`SplitOptions`](../../splitoptions) 클래스.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| releaseSplitStream | ReleaseSplitStream | createPageStream 메소드로 생성된 스트림을 해제하는 메소드. |
| pageNumbers | Int32[] | 페이지 번호. |
| splitMode | SplitMode | 의 분할 모드[`Mode`](../mode). |

### 또한보십시오

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

의 새 인스턴스를 초기화합니다.[`SplitOptions`](../../splitoptions) 클래스.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| releaseSplitStream | ReleaseSplitStream | createPageStream 메소드로 생성된 스트림을 해제하는 메소드. |
| startNumber | Int32 | 시작 페이지 번호입니다. |
| endNumber | Int32 | 끝 페이지 번호입니다. |

### 또한보십시오

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

의 새 인스턴스를 초기화합니다.[`SplitOptions`](../../splitoptions) 클래스.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 출력 분할 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| releaseSplitStream | ReleaseSplitStream | createPageStream 메소드로 생성된 스트림을 해제하는 메소드. |
| startNumber | Int32 | 시작 페이지 번호입니다. |
| endNumber | Int32 | 끝 페이지 번호입니다. |
| mode | RangeMode | 범위 모드입니다. |

### 또한보십시오

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 집회 [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
