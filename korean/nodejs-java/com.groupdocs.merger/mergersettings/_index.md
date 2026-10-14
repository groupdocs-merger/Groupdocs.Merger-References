---
title: "MergerSettings"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "동작을 사용자 정의하기 위한 설정을 정의합니다."
type: docs
weight: 11
url: /ko/nodejs-java/com.groupdocs.merger/mergersettings/
---
**Inheritance:**
java.lang.Object
```
public class MergerSettings
```

[Merger](../../com.groupdocs.merger/merger) 동작을 사용자 정의하기 위한 설정을 정의합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MergerSettings()](#MergerSettings--) | [MergerSettings](../../com.groupdocs.merger/mergersettings) 클래스의 새 인스턴스를 초기화합니다. |
| [MergerSettings(ILogger logger)](#MergerSettings-com.groupdocs.merger.logging.ILogger-) | [MergerSettings](../../com.groupdocs.merger/mergersettings) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLogger()](#getLogger--) | 문서 처리 워크플로를 추적하는 데 사용되는 로거 구현입니다. |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.merger.logging.ILogger-) | 문서 처리 워크플로를 추적하는 데 사용되는 로거 구현입니다. |
### MergerSettings() {#MergerSettings--}
```
public MergerSettings()
```


[MergerSettings](../../com.groupdocs.merger/mergersettings) 클래스의 새 인스턴스를 초기화합니다.

### MergerSettings(ILogger logger) {#MergerSettings-com.groupdocs.merger.logging.ILogger-}
```
public MergerSettings(ILogger logger)
```


[MergerSettings](../../com.groupdocs.merger/mergersettings) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.merger.logging/ilogger) | 로거 구현입니다. |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


문서 처리 워크플로를 추적하는 데 사용되는 로거 구현입니다.

**Returns:**
[ILogger](../../com.groupdocs.merger.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.merger.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


문서 처리 워크플로를 추적하는 데 사용되는 로거 구현입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.merger.logging/ilogger) |  |

