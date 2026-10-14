---
title: "GroupDocsMergerException"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "문서 처리 중 발생하는 오류를 나타냅니다."
type: docs
weight: 12
url: /ko/nodejs-java/com.groupdocs.merger.exceptions/groupdocsmergerexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception
```
public class GroupDocsMergerException extends Exception
```

문서 처리 중 발생하는 오류를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GroupDocsMergerException(String message)](#GroupDocsMergerException-java.lang.String-) | 새 인스턴스를 초기화합니다 [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) 클래스. |
| [GroupDocsMergerException(String message, Exception innerException)](#GroupDocsMergerException-java.lang.String-java.lang.Exception-) | 새 인스턴스를 초기화합니다 [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getException(Exception exception)](#getException-java.lang.Exception-) | 입력 예외에서 GroupDocs Merger 예외를 가져옵니다. |
### GroupDocsMergerException(String message) {#GroupDocsMergerException-java.lang.String-}
```
public GroupDocsMergerException(String message)
```


새 인스턴스를 초기화합니다 [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 메시지 | java.lang.String | 오류를 설명하는 메시지. |

### GroupDocsMergerException(String message, Exception innerException) {#GroupDocsMergerException-java.lang.String-java.lang.Exception-}
```
public GroupDocsMergerException(String message, Exception innerException)
```


새 인스턴스를 초기화합니다 [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 메시지 | java.lang.String | 오류를 설명하는 메시지. |
| innerException | java.lang.Exception | 오류의 내부 예외. |

### getException(Exception exception) {#getException-java.lang.Exception-}
```
public static Exception getException(Exception exception)
```


입력 예외에서 GroupDocs Merger 예외를 가져옵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 예외 | java.lang.Exception | 입력 예외. |

**Returns:**
java.lang.Exception -
