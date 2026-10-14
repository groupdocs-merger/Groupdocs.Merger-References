---
title: "MergerSettings"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है।"
type: docs
weight: 11
url: /hi/nodejs-java/com.groupdocs.merger/mergersettings/
---
**Inheritance:**
java.lang.Object
```
public class MergerSettings
```

कस्टमाइज़ करने के लिए [Merger](../../com.groupdocs.merger/merger) के व्यवहार की सेटिंग्स को परिभाषित करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MergerSettings()](#MergerSettings--) | नए उदाहरण को इनिशियलाइज़ करता है [MergerSettings](../../com.groupdocs.merger/mergersettings) क्लास का। |
| [MergerSettings(ILogger logger)](#MergerSettings-com.groupdocs.merger.logging.ILogger-) | नए उदाहरण को इनिशियलाइज़ करता है [MergerSettings](../../com.groupdocs.merger/mergersettings) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLogger()](#getLogger--) | दस्तावेज़ प्रोसेसिंग वर्कफ़्लो को ट्रैक करने के लिए उपयोग किया गया लॉगर इम्प्लीमेंटेशन। |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.merger.logging.ILogger-) | दस्तावेज़ प्रोसेसिंग वर्कफ़्लो को ट्रैक करने के लिए उपयोग किया गया लॉगर इम्प्लीमेंटेशन। |
### MergerSettings() {#MergerSettings--}
```
public MergerSettings()
```


नए उदाहरण को इनिशियलाइज़ करता है [MergerSettings](../../com.groupdocs.merger/mergersettings) क्लास का।

### MergerSettings(ILogger logger) {#MergerSettings-com.groupdocs.merger.logging.ILogger-}
```
public MergerSettings(ILogger logger)
```


नए उदाहरण को इनिशियलाइज़ करता है [MergerSettings](../../com.groupdocs.merger/mergersettings) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.merger.logging/ilogger) | लॉगर इम्प्लीमेंटेशन। |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


दस्तावेज़ प्रोसेसिंग वर्कफ़्लो को ट्रैक करने के लिए उपयोग किया गया लॉगर इम्प्लीमेंटेशन।

**Returns:**
[ILogger](../../com.groupdocs.merger.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.merger.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


दस्तावेज़ प्रोसेसिंग वर्कफ़्लो को ट्रैक करने के लिए उपयोग किया गया लॉगर इम्प्लीमेंटेशन।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.merger.logging/ilogger) |  |

