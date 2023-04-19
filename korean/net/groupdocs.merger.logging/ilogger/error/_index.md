---
title: Error
second_title: .NET API 참조용 GroupDocs.Merger
description: 오류 로그 메시지를 작성합니다. 오류 로그 메시지는 애플리케이션 흐름에서 복구할 수 없는 이벤트에 대한 정보를 제공합니다.
type: docs
weight: 10
url: /ko/net/groupdocs.merger.logging/ilogger/error/
---
## ILogger.Error method

오류 로그 메시지를 작성합니다. 오류 로그 메시지는 애플리케이션 흐름에서 복구할 수 없는 이벤트에 대한 정보를 제공합니다.

```csharp
public void Error(string message, Exception exception)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| message | String | 오류 메시지입니다. |
| exception | Exception | 예외. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*message* null입니다. |
| ArgumentNullException | 언제 던져*exception* null입니다. |

### 또한보십시오

* interface [ILogger](../../ilogger)
* 네임스페이스 [GroupDocs.Merger.Logging](../../ilogger)
* 집회 [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->