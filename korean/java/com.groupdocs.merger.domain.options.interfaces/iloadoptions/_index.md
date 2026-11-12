---
title: "ILoadOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "문서 로드 옵션을 위한 인터페이스."
type: docs
weight: 15
url: /ko/java/com.groupdocs.merger.domain.options.interfaces/iloadoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ILoadOptions extends IOptions
```

문서 로드 옵션을 위한 인터페이스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getType()](#getType--) | 열 파일의 유형. |
| [getPassword()](#getPassword--) | 암호로 보호된 파일을 열기 위한 비밀번호. |
| [getExtension()](#getExtension--) | 열 파일의 확장자. |
| [getEncoding()](#getEncoding--) | 텍스트 기반 파일을 열 때 사용되는 인코딩이며, 예를 들어 [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) 또는 [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### getType() {#getType--}
```
public abstract FileType getType()
```


열 파일의 유형.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


암호로 보호된 파일을 열기 위한 비밀번호.

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


열 파일의 확장자.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public abstract Charset getEncoding()
```


텍스트 기반 파일을 열 때 사용되는 인코딩이며, 예를 들어 [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) 또는 [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). 기본값은 [DefaultCharset][].


[DefaultCharset]: https://docs.oracle.com/javase/7/docs/api/java/nio/charset/Charset.html#defaultCharset%28%29

**Returns:**
java.nio.charset.Charset
