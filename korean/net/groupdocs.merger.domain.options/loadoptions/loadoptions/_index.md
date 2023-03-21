---
title: LoadOptions
second_title: .NET API 참조용 GroupDocs.Merger
description: 의 새 인스턴스를 초기화합니다.LoadOptionsgroupdocs.merger.domain.options/loadoptions 클래스.
type: docs
weight: 10
url: /ko/net/groupdocs.merger.domain.options/loadoptions/loadoptions/
---
## LoadOptions(FileType) {#constructor}

의 새 인스턴스를 초기화합니다.[`LoadOptions`](../../loadoptions) 클래스.

```csharp
public LoadOptions(FileType fileType)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | FileType | 로드할 파일의 유형입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*fileType* null입니다. |

### 또한보십시오

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## LoadOptions(string) {#constructor_6}

의 새 인스턴스를 초기화합니다.[`LoadOptions`](../../loadoptions) 클래스.

```csharp
public LoadOptions(string password)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| password | String | 암호로 보호된 파일을 열기 위한 암호입니다. |

### 또한보십시오

* class [LoadOptions](../../loadoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## LoadOptions(string, Encoding) {#constructor_8}

의 새 인스턴스를 초기화합니다.[`LoadOptions`](../../loadoptions) 클래스.

```csharp
public LoadOptions(string password, Encoding encoding)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| password | String | 암호로 보호된 파일을 열기 위한 암호입니다. |
| encoding | Encoding | 다음과 같은 텍스트 기반 파일을 열 때 사용되는 인코딩[`CSV`](../../../groupdocs.merger.domain/filetype/csv) 또는[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*encoding* null입니다. |

### 또한보십시오

* class [LoadOptions](../../loadoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string) {#constructor_4}

의 새 인스턴스를 초기화합니다.[`LoadOptions`](../../loadoptions) 클래스.

```csharp
public LoadOptions(FileType fileType, string password)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | FileType | 로드할 파일의 유형입니다. |
| password | String | 암호로 보호된 파일을 열기 위한 암호입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*fileType* null입니다. |

### 또한보십시오

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string, Encoding) {#constructor_5}

의 새 인스턴스를 초기화합니다.[`LoadOptions`](../../loadoptions) 클래스.

```csharp
public LoadOptions(FileType fileType, string password, Encoding encoding)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | FileType | 로드할 파일의 유형입니다. |
| password | String | 암호로 보호된 파일을 열기 위한 암호입니다. |
| encoding | Encoding | 다음과 같은 텍스트 기반 파일을 열 때 사용되는 인코딩[`CSV`](../../../groupdocs.merger.domain/filetype/csv) 또는[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*fileType* null입니다. |
| ArgumentNullException | 언제 던져*encoding* null입니다. |

### 또한보십시오

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## LoadOptions(string, FileType, string, Encoding) {#constructor_7}

의 새 인스턴스를 초기화합니다.[`LoadOptions`](../../loadoptions) 클래스.

```csharp
public LoadOptions(string extension, FileType fileType, string password, Encoding encoding)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| extension | String | 로드할 파일의 확장자입니다. |
| fileType | FileType | 로드할 파일의 유형입니다. |
| password | String | 암호로 보호된 파일을 열기 위한 암호입니다. |
| encoding | Encoding | 다음과 같은 텍스트 기반 파일을 열 때 사용되는 인코딩[`CSV`](../../../groupdocs.merger.domain/filetype/csv) 또는[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*fileType* null입니다. |
| ArgumentNullException | 언제 던져*encoding* null입니다. |

### 또한보십시오

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string, Encoding) {#constructor_3}

의 새 인스턴스를 초기화합니다.[`LoadOptions`](../../loadoptions) 클래스.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password, Encoding encoding)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| iniFileType | FileType | 초기화할 파일의 유형입니다. |
| fileType | FileType | 로드할 파일의 유형입니다. |
| password | String | 암호로 보호된 파일을 열기 위한 암호입니다. |
| encoding | Encoding | 다음과 같은 텍스트 기반 파일을 열 때 사용되는 인코딩[`CSV`](../../../groupdocs.merger.domain/filetype/csv) 또는[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*iniFileType* null입니다. |
| ArgumentNullException | 언제 던져*fileType* null입니다. |
| ArgumentNullException | 언제 던져*encoding* null입니다. |

### 또한보십시오

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string) {#constructor_2}

의 새 인스턴스를 초기화합니다.[`LoadOptions`](../../loadoptions) 클래스.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| iniFileType | FileType | 초기화할 파일의 유형입니다. |
| fileType | FileType | 로드할 파일의 유형입니다. |
| password | String | 암호로 보호된 파일을 열기 위한 암호입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*iniFileType* null입니다. |
| ArgumentNullException | 언제 던져*fileType* null입니다. |

### 또한보십시오

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 집회 [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType) {#constructor_1}

의 새 인스턴스를 초기화합니다.[`LoadOptions`](../../loadoptions) 클래스.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| iniFileType | FileType | 초기화할 파일의 유형입니다. |
| fileType | FileType | 로드할 파일의 유형입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*iniFileType* null입니다. |
| ArgumentNullException | 언제 던져*fileType* null입니다. |

### 또한보십시오

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 집회 [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
