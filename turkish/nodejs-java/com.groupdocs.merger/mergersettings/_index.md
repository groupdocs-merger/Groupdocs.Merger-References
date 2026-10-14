---
title: "MergerSettings"
second_title: "GroupDocs.Merger Node.js için Java API Referansı"
description: "Davranışı özelleştirmek için ayarları tanımlar."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.merger/mergersettings/
---
**Inheritance:**
java.lang.Object
```
public class MergerSettings
```

Davranışı özelleştirmek için [Merger](../../com.groupdocs.merger/merger) ayarlarını tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MergerSettings()](#MergerSettings--) | Yeni bir [MergerSettings](../../com.groupdocs.merger/mergersettings) sınıfı örneğini başlatır. |
| [MergerSettings(ILogger logger)](#MergerSettings-com.groupdocs.merger.logging.ILogger-) | Yeni bir [MergerSettings](../../com.groupdocs.merger/mergersettings) sınıfı örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLogger()](#getLogger--) | Belge işleme iş akışını izlemek için kullanılan günlük kaydedici uygulaması. |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.merger.logging.ILogger-) | Belge işleme iş akışını izlemek için kullanılan günlük kaydedici uygulaması. |
### MergerSettings() {#MergerSettings--}
```
public MergerSettings()
```


Yeni bir [MergerSettings](../../com.groupdocs.merger/mergersettings) sınıfı örneğini başlatır.

### MergerSettings(ILogger logger) {#MergerSettings-com.groupdocs.merger.logging.ILogger-}
```
public MergerSettings(ILogger logger)
```


Yeni bir [MergerSettings](../../com.groupdocs.merger/mergersettings) sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.merger.logging/ilogger) | Günlük kaydedici uygulaması. |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Belge işleme iş akışını izlemek için kullanılan günlük kaydedici uygulaması.

**Returns:**
[ILogger](../../com.groupdocs.merger.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.merger.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Belge işleme iş akışını izlemek için kullanılan günlük kaydedici uygulaması.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.merger.logging/ilogger) |  |

