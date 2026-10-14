---
title: "OrientationOptions"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "페이지 방향을 위한 옵션을 제공합니다."
type: docs
weight: 23
url: /ko/nodejs-java/com.groupdocs.merger.domain.options/orientationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions)
```
public class OrientationOptions extends PageOptions implements IOrientationOptions
```

페이지 방향을 위한 옵션을 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OrientationOptions(int orientationMode)](#OrientationOptions-int-) | 새 인스턴스를 초기화합니다 [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) 클래스. |
| [OrientationOptions(int orientationMode, int[] pageNumbers)](#OrientationOptions-int-int---) | 새 인스턴스를 초기화합니다 [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) 클래스. |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber)](#OrientationOptions-int-int-int-) | 새 인스턴스를 초기화합니다 [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) 클래스. |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)](#OrientationOptions-int-int-int-int-) | 새 인스턴스를 초기화합니다 [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getMode()](#getMode--) | 페이지 방향에 대한 모드를 가져옵니다. |
### OrientationOptions(int orientationMode) {#OrientationOptions-int-}
```
public OrientationOptions(int orientationMode)
```


새 인스턴스를 초기화합니다 [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) 의 방향 모드입니다. |

### OrientationOptions(int orientationMode, int[] pageNumbers) {#OrientationOptions-int-int---}
```
public OrientationOptions(int orientationMode, int[] pageNumbers)
```


새 인스턴스를 초기화합니다 [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) 의 방향 모드입니다. |
| pageNumbers | int[] | 페이지 번호. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber) {#OrientationOptions-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber)
```


새 인스턴스를 초기화합니다 [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) 의 방향 모드입니다. |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode) {#OrientationOptions-int-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)
```


새 인스턴스를 초기화합니다 [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) 의 방향 모드입니다. |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |
| mode | int | 범위 모드입니다. |

### getMode() {#getMode--}
```
public final int getMode()
```


페이지 방향에 대한 모드를 가져옵니다.

**Returns:**
int
