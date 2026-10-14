---
title: "ImageJoinOptions"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "이미지 병합 옵션."
type: docs
weight: 13
url: /ko/nodejs-java/com.groupdocs.merger.domain.options/imagejoinoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/iimagejoinoptions)
```
public class ImageJoinOptions implements IImageJoinOptions
```

이미지 병합 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ImageJoinOptions()](#ImageJoinOptions--) | 새 인스턴스를 초기화합니다 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 클래스. |
| [ImageJoinOptions(FileType fileType)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-) | 새 인스턴스를 초기화합니다 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 클래스. |
| [ImageJoinOptions(int imageJoinMode)](#ImageJoinOptions-int-) | 새 인스턴스를 초기화합니다 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 클래스. |
| [ImageJoinOptions(FileType fileType, int imageJoinMode)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-) | 새 인스턴스를 초기화합니다 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getType()](#getType--) | 이미지 파일 형식입니다. |
| [getMode()](#getMode--) | 이미지 결합 모드입니다. |
### ImageJoinOptions() {#ImageJoinOptions--}
```
public ImageJoinOptions()
```


새 인스턴스를 초기화합니다 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 클래스.

### ImageJoinOptions(FileType fileType) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public ImageJoinOptions(FileType fileType)
```


새 인스턴스를 초기화합니다 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 이미지 파일 형식입니다. |

### ImageJoinOptions(int imageJoinMode) {#ImageJoinOptions-int-}
```
public ImageJoinOptions(int imageJoinMode)
```


새 인스턴스를 초기화합니다 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageJoinMode | int | 이미지 결합 모드입니다. |

### ImageJoinOptions(FileType fileType, int imageJoinMode) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-}
```
public ImageJoinOptions(FileType fileType, int imageJoinMode)
```


새 인스턴스를 초기화합니다 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 이미지 파일 형식입니다. |
| imageJoinMode | int | 이미지 결합 모드입니다. |

### getType() {#getType--}
```
public final FileType getType()
```


이미지 파일 형식입니다.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getMode() {#getMode--}
```
public final int getMode()
```


이미지 결합 모드입니다.

**Returns:**
int
