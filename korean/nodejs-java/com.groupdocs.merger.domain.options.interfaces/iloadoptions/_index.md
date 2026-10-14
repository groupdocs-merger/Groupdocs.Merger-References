---
title: "ILoadOptions"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "문서 로드 옵션을 위한 인터페이스."
type: docs
weight: 15
url: /ko/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iloadoptions/
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
| [getType()](#getType--) | 열 파일의 유형입니다. |
| [getPassword()](#getPassword--) | 비밀번호로 보호된 파일을 열기 위한 비밀번호입니다. |
| [getExtension()](#getExtension--) | 열 파일의 확장자입니다. |
| [getEncoding()](#getEncoding--) | 텍스트 기반 파일을 열 때 사용되는 인코딩이며, [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) 또는 [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT)와 같은 파일에 적용됩니다. |
### getType() {#getType--}
```
public abstract FileType getType()
```


열 파일의 유형입니다.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


비밀번호로 보호된 파일을 열기 위한 비밀번호입니다.

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


열 파일의 확장자입니다.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public abstract Charset getEncoding()
```


텍스트 기반 파일을 열 때 사용되는 인코딩이며, [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) 또는 [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT)와 같은 파일에 적용됩니다. 기본값은 [DefaultCharset][]입니다.


[DefaultCharset]: https://docs.oracle.com/javase/7/docs/api/java/nio/charset/Charset.html#defaultCharset%28%29

**Returns:**
java.nio.charset.Charset
