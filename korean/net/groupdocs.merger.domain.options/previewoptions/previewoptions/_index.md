---
title: PreviewOptions
second_title: .NET API 참조용 GroupDocs.Merger
description: 의 새 인스턴스를 초기화합니다.PreviewOptionsgroupdocs.merger.domain.options/previewoptions 클래스.
type: docs
weight: 10
url: /ko/net/groupdocs.merger.domain.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream, PreviewMode) {#constructor_4}

의 새 인스턴스를 초기화합니다.[`PreviewOptions`](../../previewoptions) 클래스.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| previewMode | PreviewMode | 의 미리보기 모드[`Mode`](../mode) |

### 또한보십시오

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../previewoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int[]) {#constructor_7}

의 새 인스턴스를 초기화합니다.[`PreviewOptions`](../../previewoptions) 클래스.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int[] pageNumbers)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| previewMode | PreviewMode | 의 미리보기 모드[`Mode`](../mode) |
| pageNumbers | Int32[] | 페이지 번호. |

### 또한보십시오

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../previewoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int) {#constructor_5}

의 새 인스턴스를 초기화합니다.[`PreviewOptions`](../../previewoptions) 클래스.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| previewMode | PreviewMode | 의 미리보기 모드[`Mode`](../mode) |
| startNumber | Int32 | 시작 페이지 번호입니다. |
| endNumber | Int32 | 끝 페이지 번호입니다. |

### 또한보십시오

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../previewoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int, RangeMode) {#constructor_6}

의 새 인스턴스를 초기화합니다.[`PreviewOptions`](../../previewoptions) 클래스.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber, RangeMode mode)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| previewMode | PreviewMode | 의 미리보기 모드[`Mode`](../mode) |
| startNumber | Int32 | 시작 페이지 번호입니다. |
| endNumber | Int32 | 끝 페이지 번호입니다. |
| mode | RangeMode | 범위 모드입니다. |

### 또한보십시오

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../previewoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode) {#constructor}

의 새 인스턴스를 초기화합니다.[`PreviewOptions`](../../previewoptions) 클래스.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| releasePageStream | ReleasePageStream | createPageStream 메소드로 생성된 스트림을 해제하는 메소드. |
| previewMode | PreviewMode | 의 미리보기 모드[`Mode`](../mode) |

### 또한보십시오

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../previewoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int[]) {#constructor_3}

의 새 인스턴스를 초기화합니다.[`PreviewOptions`](../../previewoptions) 클래스.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int[] pageNumbers)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| releasePageStream | ReleasePageStream | createPageStream 메소드로 생성된 스트림을 해제하는 메소드. |
| previewMode | PreviewMode | 의 미리보기 모드[`Mode`](../mode) |
| pageNumbers | Int32[] | 페이지 번호. |

### 또한보십시오

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../previewoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int) {#constructor_1}

의 새 인스턴스를 초기화합니다.[`PreviewOptions`](../../previewoptions) 클래스.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| releasePageStream | ReleasePageStream | createPageStream 메소드로 생성된 스트림을 해제하는 메소드. |
| previewMode | PreviewMode | 의 미리보기 모드[`Mode`](../mode) |
| startNumber | Int32 | 시작 페이지 번호입니다. |
| endNumber | Int32 | 끝 페이지 번호입니다. |

### 또한보십시오

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../previewoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int, RangeMode) {#constructor_2}

의 새 인스턴스를 초기화합니다.[`PreviewOptions`](../../previewoptions) 클래스.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber, RangeMode mode)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| releasePageStream | ReleasePageStream | createPageStream 메소드로 생성된 스트림을 해제하는 메소드. |
| previewMode | PreviewMode | 의 미리보기 모드[`Mode`](../mode) |
| startNumber | Int32 | 시작 페이지 번호입니다. |
| endNumber | Int32 | 끝 페이지 번호입니다. |
| mode | RangeMode | 범위 모드입니다. |

### 또한보십시오

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../previewoptions)
* 집회 [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
