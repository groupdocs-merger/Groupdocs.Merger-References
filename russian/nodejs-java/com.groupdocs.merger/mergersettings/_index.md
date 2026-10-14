---
title: "MergerSettings"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Определяет настройки для настройки поведения."
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.merger/mergersettings/
---
**Inheritance:**
java.lang.Object
```
public class MergerSettings
```

Определяет настройки для настройки поведения [Merger](../../com.groupdocs.merger/merger).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MergerSettings()](#MergerSettings--) | Инициализирует новый экземпляр класса [MergerSettings](../../com.groupdocs.merger/mergersettings). |
| [MergerSettings(ILogger logger)](#MergerSettings-com.groupdocs.merger.logging.ILogger-) | Инициализирует новый экземпляр класса [MergerSettings](../../com.groupdocs.merger/mergersettings). |
## Методы

| Метод | Описание |
| --- | --- |
| [getLogger()](#getLogger--) | Реализация логгера, используемая для отслеживания рабочего процесса обработки документов. |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.merger.logging.ILogger-) | Реализация логгера, используемая для отслеживания рабочего процесса обработки документов. |
### MergerSettings() {#MergerSettings--}
```
public MergerSettings()
```


Инициализирует новый экземпляр класса [MergerSettings](../../com.groupdocs.merger/mergersettings).

### MergerSettings(ILogger logger) {#MergerSettings-com.groupdocs.merger.logging.ILogger-}
```
public MergerSettings(ILogger logger)
```


Инициализирует новый экземпляр класса [MergerSettings](../../com.groupdocs.merger/mergersettings).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.merger.logging/ilogger) | Реализация логгера. |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Реализация логгера, используемая для отслеживания рабочего процесса обработки документов.

**Returns:**
[ILogger](../../com.groupdocs.merger.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.merger.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Реализация логгера, используемая для отслеживания рабочего процесса обработки документов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.merger.logging/ilogger) |  |

