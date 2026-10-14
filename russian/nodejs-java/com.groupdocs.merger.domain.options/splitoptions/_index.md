---
title: "SplitOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Предоставляет параметры для разбиения страниц документа."
type: docs
weight: 36
url: /ru/nodejs-java/com.groupdocs.merger.domain.options/splitoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions)
```
public class SplitOptions extends PageOptions implements ISplitOptions
```

Предоставляет параметры для разбиения страниц документа.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SplitOptions(int[] pageNumbers, int splitMode)](#SplitOptions-int---int-) | Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(int splitMode, int startNumber, int endNumber)](#SplitOptions-int-int-int-) | Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-int-int-int-int-) | Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int[] pageNumbers)](#SplitOptions-java.lang.String-int---) | Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)](#SplitOptions-java.lang.String-int---int-) | Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-) | Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-int-) | Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)](#SplitOptions-java.lang.String-int-int-java.lang.Integer-) | Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-java.lang.String-int-int-int-int-) | Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-) | Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-) | Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-) | Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-) | Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-) | Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-) | Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getMode()](#getMode--) | Получает режим разбиения страниц. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Проверяет параметры разбиения. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Получает полный путь к файлу разделённого документа по индексу с заранее определённым расширением. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory для создания или освобождения потока предварительного просмотра выходной страницы. |
### SplitOptions(int[] pageNumbers, int splitMode) {#SplitOptions-int---int-}
```
public SplitOptions(int[] pageNumbers, int splitMode)
```


Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumbers | int[] | Номера страниц. |
| splitMode | int | Режим разделения Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(int splitMode, int startNumber, int endNumber) {#SplitOptions-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber)
```


Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| splitMode | int | Режим разделения Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |

### SplitOptions(int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-int-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber, int mode)
```


Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| splitMode | int | Режим разделения Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |
| mode | int | Режим диапазона. |

### SplitOptions(String filePathFormat, int[] pageNumbers) {#SplitOptions-java.lang.String-int---}
```
public SplitOptions(String filePathFormat, int[] pageNumbers)
```


Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePathFormat | java.lang.String | Формат пути к файлу, например 'c:/split\{0\}.doc' или 'c:/split\{0\}.\{1\}' с уже заранее определённым расширением. |
| pageNumbers | int[] | Номера страниц. |

### SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode) {#SplitOptions-java.lang.String-int---int-}
```
public SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)
```


Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePathFormat | java.lang.String | Формат пути к файлу, например 'c:/split\{0\}.doc' или 'c:/split\{0\}.\{1\}' с уже заранее определённым расширением. |
| pageNumbers | int[] | Номера страниц. |
| splitMode | int | Режим разделения Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(String filePathFormat, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber)
```


Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePathFormat | java.lang.String | Формат пути к файлу, например 'c:/split\{0\}.doc' или 'c:/split\{0\}.\{1\}' с уже заранее определённым расширением. |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)
```


Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePathFormat | java.lang.String | Формат пути к файлу, например 'c:/split\{0\}.doc' или 'c:/split\{0\}.\{1\}' с уже заранее определённым расширением. |
| splitMode | int | Режим разделения Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |

### SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode) {#SplitOptions-java.lang.String-int-int-java.lang.Integer-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)
```


Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePathFormat | java.lang.String | Формат пути к файлу, например 'c:/split\{0\}.doc' или 'c:/split\{0\}.\{1\}' с уже заранее определённым расширением. |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |
| mode | java.lang.Integer | Режим диапазона. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-java.lang.String-int-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)
```


Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePathFormat | java.lang.String | Формат пути к файлу, например 'c:/split\{0\}.doc' или 'c:/split\{0\}.\{1\}' с уже заранее определённым расширением. |
| splitMode | int | Режим разделения Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |
| mode | int | Режим диапазона. |

### SplitOptions(SplitStreamFactory splitStreamFactory) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory)
```


Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Метод, который создает поток, используемый для записи разделенных выходных данных. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)
```


Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Метод, который создает поток, используемый для записи разделенных выходных данных. |
| pageNumbers | int[] | Номера страниц. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)
```


Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Метод, который создает поток, используемый для записи разделенных выходных данных. |
| pageNumbers | int[] | Номера страниц. |
| splitMode | int | Режим разделения Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)
```


Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Метод, который создает поток, используемый для записи разделенных выходных данных. |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)
```


Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Метод, который создает поток, используемый для записи разделенных выходных данных. |
| splitMode | int | Режим разделения Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)
```


Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Метод, который создает поток, используемый для записи разделенных выходных данных. |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |
| mode | java.lang.Integer | Режим диапазона. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)
```


Создаёт новый экземпляр класса [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Метод, который создает поток, используемый для записи разделенных выходных данных. |
| splitMode | int | Режим разделения Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |
| mode | int | Режим диапазона. |

### getMode() {#getMode--}
```
public final int getMode()
```


Получает режим разбиения страниц.

**Returns:**
int
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


Получает полный путь к файлу разделённого документа по индексу с заранее определённым расширением.

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
