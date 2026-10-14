---
title: "JoinOptions"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "문서 병합을 위한 옵션을 제공합니다."
type: docs
weight: 15
url: /ko/nodejs-java/com.groupdocs.merger.domain.options/joinoptions/
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
| [JoinOptions()](#JoinOptions--) | 새 인스턴스를 초기화합니다 [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) 클래스. |
| [JoinOptions(FileType fileType)](#JoinOptions-com.groupdocs.merger.domain.FileType-) | 새 인스턴스를 초기화합니다 [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getType()](#getType--) | 병합할 파일의 유형. |
### JoinOptions() {#JoinOptions--}
```
public JoinOptions()
```


새 인스턴스를 초기화합니다 [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) 클래스.

### JoinOptions(FileType fileType) {#JoinOptions-com.groupdocs.merger.domain.FileType-}
```
public JoinOptions(FileType fileType)
```


새 인스턴스를 초기화합니다 [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 병합할 파일의 유형. |

### getType() {#getType--}
```
public final FileType getType()
```


병합할 파일의 유형.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
