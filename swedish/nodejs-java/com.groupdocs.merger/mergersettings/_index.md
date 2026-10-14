---
title: "MergerSettings"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Definierar inställningar för att anpassa beteendet."
type: docs
weight: 11
url: /sv/nodejs-java/com.groupdocs.merger/mergersettings/
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
| [getLogger()](#getLogger--) | Logger-implementationen som används för att spåra dokumentbehandlingsflödet. |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.merger.logging.ILogger-) | Logger-implementationen som används för att spåra dokumentbehandlingsflödet. |
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
| logger | [ILogger](../../com.groupdocs.merger.logging/ilogger) | Logger-implementationen. |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Logger-implementationen som används för att spåra dokumentbehandlingsflödet.

**Returns:**
[ILogger](../../com.groupdocs.merger.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.merger.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Logger-implementationen som används för att spåra dokumentbehandlingsflödet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.merger.logging/ilogger) |  |

