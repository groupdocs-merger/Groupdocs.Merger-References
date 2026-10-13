---
title: "JoinOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "문서 병합을 위한 옵션을 제공합니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.merger.domain.options/joinoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ijoinoptions)
```
public class JoinOptions implements IJoinOptions
```

문서 병합을 위한 옵션을 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [JoinOptions()](#JoinOptions--) | 새로운 [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) 클래스 인스턴스를 초기화합니다. |
| [JoinOptions(FileType fileType)](#JoinOptions-com.groupdocs.merger.domain.FileType-) | 새로운 [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getType()](#getType--) | 결합할 파일 유형입니다. |
### JoinOptions() {#JoinOptions--}
```
public JoinOptions()
```


새로운 [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) 클래스 인스턴스를 초기화합니다.

### JoinOptions(FileType fileType) {#JoinOptions-com.groupdocs.merger.domain.FileType-}
```
public JoinOptions(FileType fileType)
```


새로운 [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 결합할 파일 유형입니다. |

### getType() {#getType--}
```
public final FileType getType()
```


결합할 파일 유형입니다.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
