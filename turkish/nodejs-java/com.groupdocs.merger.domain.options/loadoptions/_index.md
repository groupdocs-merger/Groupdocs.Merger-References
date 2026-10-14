---
title: "LoadOptions"
second_title: "GroupDocs.Merger Node.js için Java API Referansı"
description: "Belge yükleme için seçenekler sağlar."
type: docs
weight: 16
url: /tr/nodejs-java/com.groupdocs.merger.domain.options/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Belge yükleme için seçenekler sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-) | Yeni bir [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) sınıfının örneğini başlatır. |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Yeni bir [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) sınıfının örneğini başlatır. |
| [LoadOptions(String password, Charset encoding)](#LoadOptions-java.lang.String-java.nio.charset.Charset-) | Yeni bir [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) sınıfının örneğini başlatır. |
| [LoadOptions(FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-) | Yeni bir [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) sınıfının örneğini başlatır. |
| [LoadOptions(FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Yeni bir [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) sınıfının örneğini başlatır. |
| [LoadOptions(String extension, FileType fileType, String password, Charset encoding)](#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Yeni bir [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) sınıfının örneğini başlatır. |
| [LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Yeni bir [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) sınıfının örneğini başlatır. |
| [LoadOptions(FileType iniFileType, FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-) | Yeni bir [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) sınıfının örneğini başlatır. |
| [LoadOptions(FileType iniFileType, FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Yeni bir [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Yüklenecek dosyanın türü. |
| [getExtension()](#getExtension--) | Başlatılacak dosyanın uzantısı. |
| [getPassword()](#getPassword--) | Şifre korumalı dosyayı açmak için şifre. |
| [getEncoding()](#getEncoding--) | Metin tabanlı dosyalar açılırken kullanılan kodlama, örneğin [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) veya [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType fileType)
```


Yeni bir [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Yüklenecek dosyanın türü. |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Yeni bir [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parola | java.lang.String | Şifre korumalı dosyayı açmak için şifre. |

### LoadOptions(String password, Charset encoding) {#LoadOptions-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String password, Charset encoding)
```


Yeni bir [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parola | java.lang.String | Şifre korumalı dosyayı açmak için şifre. |
| encoding | java.nio.charset.Charset | Metin tabanlı dosyalar açılırken kullanılan kodlama, örneğin [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) veya [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType fileType, String password)
```


Yeni bir [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Yüklenecek dosyanın türü. |
| parola | java.lang.String | Şifre korumalı dosyayı açmak için şifre. |

### LoadOptions(FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType fileType, String password, Charset encoding)
```


Yeni bir [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Yüklenecek dosyanın türü. |
| parola | java.lang.String | Şifre korumalı dosyayı açmak için şifre. |
| encoding | java.nio.charset.Charset | Metin tabanlı dosyalar açılırken kullanılan kodlama, örneğin [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) veya [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(String extension, FileType fileType, String password, Charset encoding) {#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String extension, FileType fileType, String password, Charset encoding)
```


Yeni bir [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uzantı | java.lang.String | Yüklenecek dosyanın uzantısı. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Yüklenecek dosyanın türü. |
| parola | java.lang.String | Şifre korumalı dosyayı açmak için şifre. |
| encoding | java.nio.charset.Charset | Metin tabanlı dosyalar açılırken kullanılan kodlama, örneğin [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) veya [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)
```


Yeni bir [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Başlatılacak dosyanın türü. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Yüklenecek dosyanın türü. |
| parola | java.lang.String | Şifre korumalı dosyayı açmak için şifre. |
| encoding | java.nio.charset.Charset | Metin tabanlı dosyalar açılırken kullanılan kodlama, örneğin [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) veya [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password)
```


Yeni bir [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Başlatılacak dosyanın türü. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Yüklenecek dosyanın türü. |
| parola | java.lang.String | Şifre korumalı dosyayı açmak için şifre. |

### LoadOptions(FileType iniFileType, FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType iniFileType, FileType fileType)
```


Yeni bir [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Başlatılacak dosyanın türü. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Yüklenecek dosyanın türü. |

### getType() {#getType--}
```
public final FileType getType()
```


Yüklenecek dosyanın türü.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Başlatılacak dosyanın uzantısı.

**Returns:**
java.lang.String
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Şifre korumalı dosyayı açmak için şifre.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Metin tabanlı dosyaları, örn. [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) veya [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT), açarken kullanılan kodlama. Varsayılan değer System.Text.Encoding.Default (java.nio.charset.Charset).

**Returns:**
java.nio.charset.Charset
