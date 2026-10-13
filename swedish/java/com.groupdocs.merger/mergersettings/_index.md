---
title: "MergerSettings"
second_title: "GroupDocs.Merger för Java API-referens"
description: "Definierar inställningar för att anpassa beteendet."
type: docs
weight: 11
url: /sv/java/com.groupdocs.merger/mergersettings/
---
**Inheritance:**
java.lang.Object
```
public class MergerSettings
```

Definierar inställningar för att anpassa [Merger](../../com.groupdocs.merger/merger) beteendet.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MergerSettings()](#MergerSettings--) | Initierar en ny instans av klassen [MergerSettings](../../com.groupdocs.merger/mergersettings). |
| [MergerSettings(ILogger logger)](#MergerSettings-com.groupdocs.merger.logging.ILogger-) | Initierar en ny instans av klassen [MergerSettings](../../com.groupdocs.merger/mergersettings). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLogger()](#getLogger--) | Loggimplementeringen som används för att spåra arbetsflödet för dokumentbehandling. |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.merger.logging.ILogger-) | Loggimplementeringen som används för att spåra arbetsflödet för dokumentbehandling. |
### MergerSettings() {#MergerSettings--}
```
public MergerSettings()
```


Initierar en ny instans av klassen [MergerSettings](../../com.groupdocs.merger/mergersettings).

### MergerSettings(ILogger logger) {#MergerSettings-com.groupdocs.merger.logging.ILogger-}
```
public MergerSettings(ILogger logger)
```


Initierar en ny instans av klassen [MergerSettings](../../com.groupdocs.merger/mergersettings).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.merger.logging/ilogger) | Loggimplementeringen. |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Loggimplementeringen som används för att spåra arbetsflödet för dokumentbehandling.

**Returns:**
[ILogger](../../com.groupdocs.merger.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.merger.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Loggimplementeringen som används för att spåra arbetsflödet för dokumentbehandling.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.merger.logging/ilogger) |  |

