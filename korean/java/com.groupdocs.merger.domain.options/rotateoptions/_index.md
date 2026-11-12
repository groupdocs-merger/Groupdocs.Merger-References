---
title: "RotateOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "페이지 회전을 위한 옵션을 제공합니다."
type: docs
weight: 35
url: /ko/java/com.groupdocs.merger.domain.options/rotateoptions/
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rotateMode | int | Mode의 회전 모드 (\#getMode.getMode/\#setMode(int).setMode(int)) |

### RotateOptions(int rotateMode, int[] pageNumbers) {#RotateOptions-int-int---}
```
public RotateOptions(int rotateMode, int[] pageNumbers)
```


새 인스턴스를 초기화합니다 [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rotateMode | int | Mode의 회전 모드 (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | 페이지 번호. |

### RotateOptions(int rotateMode, int startNumber, int endNumber) {#RotateOptions-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber)
```


새 인스턴스를 초기화합니다 [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rotateMode | int | Mode의 회전 모드 (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | 시작 페이지 번호. |
| endNumber | int | 끝 페이지 번호. |

### RotateOptions(int rotateMode, int startNumber, int endNumber, int mode) {#RotateOptions-int-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)
```


새 인스턴스를 초기화합니다 [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rotateMode | int | Mode의 회전 모드 (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | 시작 페이지 번호. |
| endNumber | int | 끝 페이지 번호. |
| mode | int | 범위 모드. |

### getMode() {#getMode--}
```
public final int getMode()
```


회전 모드(90, 180 또는 270도)를 가져옵니다.

**Returns:**
int
