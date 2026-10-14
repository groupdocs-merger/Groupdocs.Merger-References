---
title: "ConsoleLogger"
second_title: "GroupDocs.Merger Node.js के लिए Java API संदर्भ"
description: "कंसोल में लॉग संदेश लिखता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.merger.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.logging.ILogger](../../com.groupdocs.merger.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

कंसोल में लॉग संदेश लिखता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | कंसोल में ट्रेस संदेश लिखता है। |
| [warning(String message)](#warning-java.lang.String-) | कंसोल में चेतावनी संदेश लिखता है। |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | कंसोल में त्रुटि संदेश लिखता है। |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


कंसोल में ट्रेस संदेश लिखता है। ट्रेस लॉग संदेश एप्लिकेशन प्रवाह के बारे में सामान्यतः उपयोगी जानकारी प्रदान करते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संदेश | java.lang.String | ट्रेस संदेश। |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


कंसोल में चेतावनी संदेश लिखता है। चेतावनी लॉग संदेश एप्लिकेशन प्रवाह में अप्रत्याशित और पुनर्प्राप्ति योग्य घटनाओं के बारे में जानकारी प्रदान करते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संदेश | java.lang.String | चेतावनी संदेश। |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


कंसोल में त्रुटि संदेश लिखता है। त्रुटि लॉग संदेश एप्लिकेशन प्रवाह में अपरिवर्तनीय घटनाओं के बारे में जानकारी प्रदान करते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संदेश | java.lang.String | त्रुटि संदेश। |
| अपवाद | java.lang.Exception | अपवाद। |

