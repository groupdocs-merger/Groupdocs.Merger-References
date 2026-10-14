---
title: "MergerSettings"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Definiert Einstellungen zum Anpassen des Verhaltens."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.merger/mergersettings/
---
**Inheritance:**
java.lang.Object
```
public class MergerSettings
```

Definiert Einstellungen zum Anpassen des [Merger](../../com.groupdocs.merger/merger) Verhaltens.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MergerSettings()](#MergerSettings--) | Initialisiert eine neue Instanz der Klasse [MergerSettings](../../com.groupdocs.merger/mergersettings). |
| [MergerSettings(ILogger logger)](#MergerSettings-com.groupdocs.merger.logging.ILogger-) | Initialisiert eine neue Instanz der Klasse [MergerSettings](../../com.groupdocs.merger/mergersettings). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLogger()](#getLogger--) | Die Logger-Implementierung, die zur Verfolgung des Dokumentenverarbeitungsablaufs verwendet wird. |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.merger.logging.ILogger-) | Die Logger-Implementierung, die zur Verfolgung des Dokumentenverarbeitungsablaufs verwendet wird. |
### MergerSettings() {#MergerSettings--}
```
public MergerSettings()
```


Initialisiert eine neue Instanz der Klasse [MergerSettings](../../com.groupdocs.merger/mergersettings).

### MergerSettings(ILogger logger) {#MergerSettings-com.groupdocs.merger.logging.ILogger-}
```
public MergerSettings(ILogger logger)
```


Initialisiert eine neue Instanz der Klasse [MergerSettings](../../com.groupdocs.merger/mergersettings).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.merger.logging/ilogger) | Die Logger-Implementierung. |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Die Logger-Implementierung, die zur Verfolgung des Dokumentenverarbeitungsablaufs verwendet wird.

**Returns:**
[ILogger](../../com.groupdocs.merger.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.merger.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Die Logger-Implementierung, die zur Verfolgung des Dokumentenverarbeitungsablaufs verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.merger.logging/ilogger) |  |

