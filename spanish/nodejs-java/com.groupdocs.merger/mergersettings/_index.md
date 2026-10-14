---
title: "MergerSettings"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Define la configuración para personalizar el comportamiento."
type: docs
weight: 11
url: /es/nodejs-java/com.groupdocs.merger/mergersettings/
---
**Inheritance:**
java.lang.Object
```
public class MergerSettings
```

Define la configuración para personalizar el comportamiento de [Merger](../../com.groupdocs.merger/merger).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MergerSettings()](#MergerSettings--) | Inicializa una nueva instancia de la clase [MergerSettings](../../com.groupdocs.merger/mergersettings). |
| [MergerSettings(ILogger logger)](#MergerSettings-com.groupdocs.merger.logging.ILogger-) | Inicializa una nueva instancia de la clase [MergerSettings](../../com.groupdocs.merger/mergersettings). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getLogger()](#getLogger--) | La implementación del registrador utilizada para rastrear el flujo de trabajo del procesamiento de documentos. |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.merger.logging.ILogger-) | La implementación del registrador utilizada para rastrear el flujo de trabajo del procesamiento de documentos. |
### MergerSettings() {#MergerSettings--}
```
public MergerSettings()
```


Inicializa una nueva instancia de la clase [MergerSettings](../../com.groupdocs.merger/mergersettings).

### MergerSettings(ILogger logger) {#MergerSettings-com.groupdocs.merger.logging.ILogger-}
```
public MergerSettings(ILogger logger)
```


Inicializa una nueva instancia de la clase [MergerSettings](../../com.groupdocs.merger/mergersettings).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.merger.logging/ilogger) | La implementación del registrador. |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


La implementación del registrador utilizada para rastrear el flujo de trabajo del procesamiento de documentos.

**Returns:**
[ILogger](../../com.groupdocs.merger.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.merger.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


La implementación del registrador utilizada para rastrear el flujo de trabajo del procesamiento de documentos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.merger.logging/ilogger) |  |

