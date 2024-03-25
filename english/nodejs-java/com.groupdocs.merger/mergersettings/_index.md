---
title: MergerSettings
second_title: GroupDocs.Merger for Node.js via Java API Reference
description: Defines settings for customizing  behaviour.
type: docs
weight: 11
url: /nodejs-java/com.groupdocs.merger/mergersettings/
---
**Inheritance:**
java.lang.Object
```
public class MergerSettings
```

Defines settings for customizing [Merger](../../com.groupdocs.merger/merger) behaviour.
## Constructors

| Constructor | Description |
| --- | --- |
| [MergerSettings()](#MergerSettings--) | Initializes new instance of [MergerSettings](../../com.groupdocs.merger/mergersettings) class. |
| [MergerSettings(ILogger logger)](#MergerSettings-com.groupdocs.merger.logging.ILogger-) | Initializes new instance of [MergerSettings](../../com.groupdocs.merger/mergersettings) class. |
## Methods

| Method | Description |
| --- | --- |
| [getLogger()](#getLogger--) | The logger implementation used for tracking document processing workflow. |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.merger.logging.ILogger-) | The logger implementation used for tracking document processing workflow. |
### MergerSettings() {#MergerSettings--}
```
public MergerSettings()
```


Initializes new instance of [MergerSettings](../../com.groupdocs.merger/mergersettings) class.

### MergerSettings(ILogger logger) {#MergerSettings-com.groupdocs.merger.logging.ILogger-}
```
public MergerSettings(ILogger logger)
```


Initializes new instance of [MergerSettings](../../com.groupdocs.merger/mergersettings) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.merger.logging/ilogger) | The logger implementation. |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


The logger implementation used for tracking document processing workflow.

**Returns:**
[ILogger](../../com.groupdocs.merger.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.merger.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


The logger implementation used for tracking document processing workflow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.merger.logging/ilogger) |  |

