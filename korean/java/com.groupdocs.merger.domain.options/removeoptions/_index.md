---
title: "RemoveOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "페이지 제거를 위한 옵션을 제공합니다."
type: docs
weight: 33
url: /ko/java/com.groupdocs.merger.domain.options/removeoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRemoveOptions](../../com.groupdocs.merger.domain.options.interfaces/iremoveoptions)
```
public class RemoveOptions extends PageOptions implements IRemoveOptions
```

페이지 제거를 위한 옵션을 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [RemoveOptions()](#RemoveOptions--) | 새로운 [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) 클래스 인스턴스를 초기화합니다. |
| [RemoveOptions(int[] pageNumbers)](#RemoveOptions-int---) | 새로운 [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) 클래스 인스턴스를 초기화합니다. |
| [RemoveOptions(int startNumber, int endNumber)](#RemoveOptions-int-int-) | 새로운 [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) 클래스 인스턴스를 초기화합니다. |
| [RemoveOptions(int startNumber, int endNumber, int mode)](#RemoveOptions-int-int-int-) | 새로운 [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) 클래스 인스턴스를 초기화합니다. |
### RemoveOptions() {#RemoveOptions--}
```
public RemoveOptions()
```


새로운 [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) 클래스 인스턴스를 초기화합니다.

### RemoveOptions(int[] pageNumbers) {#RemoveOptions-int---}
```
public RemoveOptions(int[] pageNumbers)
```


새로운 [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pageNumbers | int[] | 페이지 번호. |

### RemoveOptions(int startNumber, int endNumber) {#RemoveOptions-int-int-}
```
public RemoveOptions(int startNumber, int endNumber)
```


새로운 [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startNumber | int | 시작 페이지 번호. |
| endNumber | int | 끝 페이지 번호. |

### RemoveOptions(int startNumber, int endNumber, int mode) {#RemoveOptions-int-int-int-}
```
public RemoveOptions(int startNumber, int endNumber, int mode)
```


새로운 [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startNumber | int | 시작 페이지 번호. |
| endNumber | int | 끝 페이지 번호. |
| mode | int | 범위 모드. |

