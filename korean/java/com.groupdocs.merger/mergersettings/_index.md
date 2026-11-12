---
title: "MergerSettings"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "동작을 사용자 정의하기 위한 설정을 정의합니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.merger/mergersettings/
---
**Inheritance:**
java.lang.Object
```
public class MergerSettings
```

동작을 사용자 정의하기 위한 설정을 정의합니다 [Merger](../../com.groupdocs.merger/merger) 동작.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MergerSettings()](#MergerSettings--) | 새 인스턴스를 초기화합니다 [MergerSettings](../../com.groupdocs.merger/mergersettings) 클래스. |
| [MergerSettings(ILogger logger)](#MergerSettings-com.groupdocs.merger.logging.ILogger-) | 새 인스턴스를 초기화합니다 [MergerSettings](../../com.groupdocs.merger/mergersettings) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLogger()](#getLogger--) | 문서 처리 워크플로를 추적하는 데 사용되는 로거 구현. |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.merger.logging.ILogger-) | 문서 처리 워크플로를 추적하는 데 사용되는 로거 구현. |
### MergerSettings() {#MergerSettings--}
```
public MergerSettings()
```


새 인스턴스를 초기화합니다 [MergerSettings](../../com.groupdocs.merger/mergersettings) 클래스.

### MergerSettings(ILogger logger) {#MergerSettings-com.groupdocs.merger.logging.ILogger-}
```
public MergerSettings(ILogger logger)
```


새 인스턴스를 초기화합니다 [MergerSettings](../../com.groupdocs.merger/mergersettings) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.merger.logging/ilogger) | 로거 구현. |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


문서 처리 워크플로를 추적하는 데 사용되는 로거 구현.

**Returns:**
[ILogger](../../com.groupdocs.merger.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.merger.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


문서 처리 워크플로를 추적하는 데 사용되는 로거 구현.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.merger.logging/ilogger) |  |

