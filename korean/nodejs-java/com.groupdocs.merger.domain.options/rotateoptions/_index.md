---
title: "RotateOptions"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "페이지 회전을 위한 옵션을 제공합니다."
type: docs
weight: 33
url: /ko/nodejs-java/com.groupdocs.merger.domain.options/rotateoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions)
```
public class RotateOptions extends PageOptions implements IRotateOptions
```

페이지 회전을 위한 옵션을 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [RotateOptions(int rotateMode)](#RotateOptions-int-) | 새 인스턴스를 초기화합니다 [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) 클래스. |
| [RotateOptions(int rotateMode, int[] pageNumbers)](#RotateOptions-int-int---) | 새 인스턴스를 초기화합니다 [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) 클래스. |
| [RotateOptions(int rotateMode, int startNumber, int endNumber)](#RotateOptions-int-int-int-) | 새 인스턴스를 초기화합니다 [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) 클래스. |
| [RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)](#RotateOptions-int-int-int-int-) | 새 인스턴스를 초기화합니다 [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getMode()](#getMode--) | 회전 모드(90, 180 또는 270도)를 가져옵니다. |
### RotateOptions(int rotateMode) {#RotateOptions-int-}
```
public RotateOptions(int rotateMode)
```


새 인스턴스를 초기화합니다 [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rotateMode | int | 회전 모드 (\\#getMode.getMode/\\#setMode(int).setMode(int)) |

### RotateOptions(int rotateMode, int[] pageNumbers) {#RotateOptions-int-int---}
```
public RotateOptions(int rotateMode, int[] pageNumbers)
```


새 인스턴스를 초기화합니다 [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rotateMode | int | 회전 모드 (\\#getMode.getMode/\\#setMode(int).setMode(int)) |
| pageNumbers | int[] | 페이지 번호. |

### RotateOptions(int rotateMode, int startNumber, int endNumber) {#RotateOptions-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber)
```


새 인스턴스를 초기화합니다 [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rotateMode | int | 회전 모드 (\\#getMode.getMode/\\#setMode(int).setMode(int)) |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |

### RotateOptions(int rotateMode, int startNumber, int endNumber, int mode) {#RotateOptions-int-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)
```


새 인스턴스를 초기화합니다 [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rotateMode | int | 회전 모드 (\\#getMode.getMode/\\#setMode(int).setMode(int)) |
| startNumber | int | 시작 페이지 번호입니다. |
| endNumber | int | 끝 페이지 번호입니다. |
| mode | int | 범위 모드입니다. |

### getMode() {#getMode--}
```
public final int getMode()
```


회전 모드(90, 180 또는 270도)를 가져옵니다.

**Returns:**
int
