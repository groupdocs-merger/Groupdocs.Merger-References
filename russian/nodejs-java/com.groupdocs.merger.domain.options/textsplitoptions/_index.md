---
title: "TextSplitOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Предоставляет параметры для разбиения текста документа."
type: docs
weight: 39
url: /ru/nodejs-java/com.groupdocs.merger.domain.options/textsplitoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions)
```
public class TextSplitOptions implements ITextSplitOptions
```

Предоставляет параметры для разбиения текста документа.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextSplitOptions(int[] lineNumbers)](#TextSplitOptions-int---) | Инициализирует новый экземпляр класса [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(int mode, int[] lineNumbers)](#TextSplitOptions-int-int---) | Инициализирует новый экземпляр класса [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(String filePathFormat, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int---) | Инициализирует новый экземпляр класса [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int-int---) | Инициализирует новый экземпляр класса [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Инициализирует новый экземпляр класса [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---) | Инициализирует новый экземпляр класса [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getMode()](#getMode--) | Режим разбиения текста. |
| [getLineNumbers()](#getLineNumbers--) | Номера строк для разбиения текста. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Проверяет параметры разбиения. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Получает полный путь к файлу разделённого документа по индексу с заданным расширением. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory для создания или освобождения потока предварительного просмотра выходной страницы. |
### TextSplitOptions(int[] lineNumbers) {#TextSplitOptions-int---}
```
public TextSplitOptions(int[] lineNumbers)
```


Инициализирует новый экземпляр класса [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lineNumbers | int[] | Номера строк для разбиения текста. |

### TextSplitOptions(int mode, int[] lineNumbers) {#TextSplitOptions-int-int---}
```
public TextSplitOptions(int mode, int[] lineNumbers)
```


Инициализирует новый экземпляр класса [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mode | int | Режим разбиения текста. |
| lineNumbers | int[] | Номера строк для разбиения текста. |

### TextSplitOptions(String filePathFormat, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int---}
```
public TextSplitOptions(String filePathFormat, int[] lineNumbers)
```


Инициализирует новый экземпляр класса [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePathFormat | java.lang.String | Формат пути к файлу, например 'c:/split\{0\}.doc' или 'c:/split\{0\}.\{1\}' с уже заданным расширением. |
| lineNumbers | int[] | Номера строк для разбиения текста. |

### TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int-int---}
```
public TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)
```


Инициализирует новый экземпляр класса [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePathFormat | java.lang.String | Формат пути к файлу, например 'c:/split\{0\}.doc' или 'c:/split\{0\}.\{1\}' с уже заданным расширением. |
| mode | int | Режим разбиения текста. |
| lineNumbers | int[] | Номера строк для разбиения текста. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)
```


Инициализирует новый экземпляр класса [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Метод, который создает поток, используемый для записи разделенных выходных данных. |
| lineNumbers | int[] | Номера строк для разбиения текста. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)
```


Инициализирует новый экземпляр класса [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Метод, который создает поток, используемый для записи разделенных выходных данных. |
| mode | int | Режим разбиения текста. |
| lineNumbers | int[] | Номера строк для разбиения текста. |

### getMode() {#getMode--}
```
public final int getMode()
```


Режим разбиения текста.

**Returns:**
int
### getLineNumbers() {#getLineNumbers--}
```
public final int[] getLineNumbers()
```


Номера строк для разбиения текста.

**Returns:**
int[]
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Проверяет параметры разбиения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла класса [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


Получает полный путь к файлу разделённого документа по индексу с заданным расширением.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int | Индекс разделённого документа. |
| расширение | java.lang.String | Расширение файла. |

**Returns:**
java.lang.String - Полный путь к файлу.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


SplitStreamFactory для создания или освобождения потока предварительного просмотра выходной страницы.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
