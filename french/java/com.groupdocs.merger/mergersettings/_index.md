---
title: "MergerSettings"
second_title: "L'espace de noms com.groupdocs.merger.domain.builders fournit des constructeurs."
description: "Définit les paramètres pour personnaliser le comportement."
type: docs
weight: 11
url: /fr/java/com.groupdocs.merger/mergersettings/
---
**Inheritance:**
java.lang.Object
```
public class MergerSettings
```

Définit les paramètres pour personnaliser le comportement de [Merger](../../com.groupdocs.merger/merger).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MergerSettings()](#MergerSettings--) | Initialise une nouvelle instance de la classe [MergerSettings](../../com.groupdocs.merger/mergersettings). |
| [MergerSettings(ILogger logger)](#MergerSettings-com.groupdocs.merger.logging.ILogger-) | Initialise une nouvelle instance de la classe [MergerSettings](../../com.groupdocs.merger/mergersettings). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLogger()](#getLogger--) | L'implémentation du journal utilisée pour suivre le flux de traitement du document. |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.merger.logging.ILogger-) | L'implémentation du journal utilisée pour suivre le flux de traitement du document. |
### MergerSettings() {#MergerSettings--}
```
public MergerSettings()
```


Initialise une nouvelle instance de la classe [MergerSettings](../../com.groupdocs.merger/mergersettings).

### MergerSettings(ILogger logger) {#MergerSettings-com.groupdocs.merger.logging.ILogger-}
```
public MergerSettings(ILogger logger)
```


Initialise une nouvelle instance de la classe [MergerSettings](../../com.groupdocs.merger/mergersettings).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.merger.logging/ilogger) | L'implémentation du journal. |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


L'implémentation du journal utilisée pour suivre le flux de traitement du document.

**Returns:**
[ILogger](../../com.groupdocs.merger.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.merger.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


L'implémentation du journal utilisée pour suivre le flux de traitement du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.merger.logging/ilogger) |  |

