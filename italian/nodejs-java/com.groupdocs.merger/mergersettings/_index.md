---
title: "MergerSettings"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Definisce le impostazioni per personalizzare il comportamento."
type: docs
weight: 11
url: /it/nodejs-java/com.groupdocs.merger/mergersettings/
---
**Inheritance:**
java.lang.Object
```
public class MergerSettings
```

Definisce le impostazioni per personalizzare il comportamento di [Merger](../../com.groupdocs.merger/merger).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MergerSettings()](#MergerSettings--) | Inizializza una nuova istanza della classe [MergerSettings](../../com.groupdocs.merger/mergersettings). |
| [MergerSettings(ILogger logger)](#MergerSettings-com.groupdocs.merger.logging.ILogger-) | Inizializza una nuova istanza della classe [MergerSettings](../../com.groupdocs.merger/mergersettings). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLogger()](#getLogger--) | L'implementazione del logger utilizzata per tracciare il flusso di lavoro dell'elaborazione dei documenti. |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.merger.logging.ILogger-) | L'implementazione del logger utilizzata per tracciare il flusso di lavoro dell'elaborazione dei documenti. |
### MergerSettings() {#MergerSettings--}
```
public MergerSettings()
```


Inizializza una nuova istanza della classe [MergerSettings](../../com.groupdocs.merger/mergersettings).

### MergerSettings(ILogger logger) {#MergerSettings-com.groupdocs.merger.logging.ILogger-}
```
public MergerSettings(ILogger logger)
```


Inizializza una nuova istanza della classe [MergerSettings](../../com.groupdocs.merger/mergersettings).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.merger.logging/ilogger) | L'implementazione del logger. |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


L'implementazione del logger utilizzata per tracciare il flusso di lavoro dell'elaborazione dei documenti.

**Returns:**
[ILogger](../../com.groupdocs.merger.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.merger.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


L'implementazione del logger utilizzata per tracciare il flusso di lavoro dell'elaborazione dei documenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.merger.logging/ilogger) |  |

