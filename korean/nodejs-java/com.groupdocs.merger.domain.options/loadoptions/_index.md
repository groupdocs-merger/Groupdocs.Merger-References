---
title: "LoadOptions"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "문서 로드를 위한 옵션을 제공합니다."
type: docs
weight: 16
url: /ko/nodejs-java/com.groupdocs.merger.domain.options/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

문서 로드를 위한 옵션을 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-) | 새 인스턴스를 초기화합니다 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 클래스. |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | 새 인스턴스를 초기화합니다 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 클래스. |
| [LoadOptions(String password, Charset encoding)](#LoadOptions-java.lang.String-java.nio.charset.Charset-) | 새 인스턴스를 초기화합니다 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 클래스. |
| [LoadOptions(FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-) | 새 인스턴스를 초기화합니다 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 클래스. |
| [LoadOptions(FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | 새 인스턴스를 초기화합니다 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 클래스. |
| [LoadOptions(String extension, FileType fileType, String password, Charset encoding)](#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | 새 인스턴스를 초기화합니다 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 클래스. |
| [LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | 새 인스턴스를 초기화합니다 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 클래스. |
| [LoadOptions(FileType iniFileType, FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-) | 새 인스턴스를 초기화합니다 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 클래스. |
| [LoadOptions(FileType iniFileType, FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | 새 인스턴스를 초기화합니다 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getType()](#getType--) | 로드할 파일의 유형. |
| [getExtension()](#getExtension--) | 초기화할 파일의 확장자. |
| [getPassword()](#getPassword--) | 비밀번호로 보호된 파일을 열기 위한 비밀번호입니다. |
| [getEncoding()](#getEncoding--) | 텍스트 기반 파일을 열 때 사용되는 인코딩이며, [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) 또는 [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT)와 같은 파일에 적용됩니다. |
### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType fileType)
```


새 인스턴스를 초기화합니다 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 로드할 파일의 유형. |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


새 인스턴스를 초기화합니다 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 비밀번호 | java.lang.String | 비밀번호로 보호된 파일을 열기 위한 비밀번호입니다. |

### LoadOptions(String password, Charset encoding) {#LoadOptions-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String password, Charset encoding)
```


새 인스턴스를 초기화합니다 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 비밀번호 | java.lang.String | 비밀번호로 보호된 파일을 열기 위한 비밀번호입니다. |
| encoding | java.nio.charset.Charset | 텍스트 기반 파일을 열 때 사용되는 인코딩이며, [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) 또는 [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT)와 같은 파일에 적용됩니다. |

### LoadOptions(FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType fileType, String password)
```


새 인스턴스를 초기화합니다 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 로드할 파일의 유형. |
| 비밀번호 | java.lang.String | 비밀번호로 보호된 파일을 열기 위한 비밀번호입니다. |

### LoadOptions(FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType fileType, String password, Charset encoding)
```


새 인스턴스를 초기화합니다 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 로드할 파일의 유형. |
| 비밀번호 | java.lang.String | 비밀번호로 보호된 파일을 열기 위한 비밀번호입니다. |
| encoding | java.nio.charset.Charset | 텍스트 기반 파일을 열 때 사용되는 인코딩이며, [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) 또는 [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT)와 같은 파일에 적용됩니다. |

### LoadOptions(String extension, FileType fileType, String password, Charset encoding) {#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String extension, FileType fileType, String password, Charset encoding)
```


새 인스턴스를 초기화합니다 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 확장자 | java.lang.String | 로드할 파일의 확장자. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 로드할 파일의 유형. |
| 비밀번호 | java.lang.String | 비밀번호로 보호된 파일을 열기 위한 비밀번호입니다. |
| encoding | java.nio.charset.Charset | 텍스트 기반 파일을 열 때 사용되는 인코딩이며, [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) 또는 [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT)와 같은 파일에 적용됩니다. |

### LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)
```


새 인스턴스를 초기화합니다 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 초기화할 파일의 유형. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 로드할 파일의 유형. |
| 비밀번호 | java.lang.String | 비밀번호로 보호된 파일을 열기 위한 비밀번호입니다. |
| encoding | java.nio.charset.Charset | 텍스트 기반 파일을 열 때 사용되는 인코딩이며, [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) 또는 [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT)와 같은 파일에 적용됩니다. |

### LoadOptions(FileType iniFileType, FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password)
```


새 인스턴스를 초기화합니다 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 초기화할 파일의 유형. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 로드할 파일의 유형. |
| 비밀번호 | java.lang.String | 비밀번호로 보호된 파일을 열기 위한 비밀번호입니다. |

### LoadOptions(FileType iniFileType, FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType iniFileType, FileType fileType)
```


새 인스턴스를 초기화합니다 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 클래스.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 초기화할 파일의 유형. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 로드할 파일의 유형. |

### getType() {#getType--}
```
public final FileType getType()
```


로드할 파일의 유형.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getExtension() {#getExtension--}
```
public final String getExtension()
```


초기화할 파일의 확장자.

**Returns:**
java.lang.String
### getPassword() {#getPassword--}
```
public final String getPassword()
```


비밀번호로 보호된 파일을 열기 위한 비밀번호입니다.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


텍스트 기반 파일([FileType.CSV](../../com.groupdocs.merger.domain/filetype\\#CSV) 또는 [FileType.TXT](../../com.groupdocs.merger.domain/filetype\\#TXT))을 열 때 사용되는 인코딩입니다. 기본값은 System.Text.Encoding.Default (java.nio.charset.Charset)입니다.

**Returns:**
java.nio.charset.Charset
