---
title: "ImageJoinOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "이미지 병합 옵션."
type: docs
weight: 13
url: /ko/java/com.groupdocs.merger.domain.options/imagejoinoptions/
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
| [ImageJoinOptions()](#ImageJoinOptions--) | 새로운 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 클래스 인스턴스를 초기화합니다. |
| [ImageJoinOptions(FileType fileType)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-) | 새로운 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 클래스 인스턴스를 초기화합니다. |
| [ImageJoinOptions(int imageJoinMode)](#ImageJoinOptions-int-) | 새로운 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 클래스 인스턴스를 초기화합니다. |
| [ImageJoinOptions(FileType fileType, int imageJoinMode)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-) | 새로운 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getType()](#getType--) | 이미지 파일 형식입니다. |
| [getMode()](#getMode--) | 이미지 결합 모드. |
### ImageJoinOptions() {#ImageJoinOptions--}
```
public ImageJoinOptions()
```


새로운 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 클래스 인스턴스를 초기화합니다.

### ImageJoinOptions(FileType fileType) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public ImageJoinOptions(FileType fileType)
```


새로운 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 이미지 파일 형식입니다. |

### ImageJoinOptions(int imageJoinMode) {#ImageJoinOptions-int-}
```
public ImageJoinOptions(int imageJoinMode)
```


새로운 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| imageJoinMode | int | 이미지 결합 모드. |

### ImageJoinOptions(FileType fileType, int imageJoinMode) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-}
```
public ImageJoinOptions(FileType fileType, int imageJoinMode)
```


새로운 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 이미지 파일 형식입니다. |
| imageJoinMode | int | 이미지 결합 모드. |

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


이미지 결합 모드.

**Returns:**
int
