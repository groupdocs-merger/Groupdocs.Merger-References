---
title: "GroupDocsMergerException"
second_title: "GroupDocs.Merger के लिए Java API संदर्भ"
description: "दस्तावेज़ प्रसंस्करण के दौरान उत्पन्न होने वाली त्रुटियों का प्रतिनिधित्व करता है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.merger.exceptions/groupdocsmergerexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception
```
public class GroupDocsMergerException extends Exception
```

दस्तावेज़ प्रसंस्करण के दौरान उत्पन्न होने वाली त्रुटियों का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [GroupDocsMergerException(String message)](#GroupDocsMergerException-java.lang.String-) | नए उदाहरण को प्रारंभ करता है [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) वर्ग का। |
| [GroupDocsMergerException(String message, Exception innerException)](#GroupDocsMergerException-java.lang.String-java.lang.Exception-) | नए उदाहरण को प्रारंभ करता है [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) वर्ग का। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getException(Exception exception)](#getException-java.lang.Exception-) | इनपुट अपवाद से GroupDocs Merger अपवाद प्राप्त करें। |
### GroupDocsMergerException(String message) {#GroupDocsMergerException-java.lang.String-}
```
public GroupDocsMergerException(String message)
```


नए उदाहरण को प्रारंभ करता है [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) वर्ग का।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| संदेश | java.lang.String | त्रुटि का वर्णन करने वाला संदेश। |

### GroupDocsMergerException(String message, Exception innerException) {#GroupDocsMergerException-java.lang.String-java.lang.Exception-}
```
public GroupDocsMergerException(String message, Exception innerException)
```


नए उदाहरण को प्रारंभ करता है [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) वर्ग का।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| संदेश | java.lang.String | त्रुटि का वर्णन करने वाला संदेश। |
| innerException | java.lang.Exception | त्रुटि की आंतरिक अपवाद। |

### getException(Exception exception) {#getException-java.lang.Exception-}
```
public static Exception getException(Exception exception)
```


इनपुट अपवाद से GroupDocs Merger अपवाद प्राप्त करें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| अपवाद | java.lang.Exception | इनपुट अपवाद। |

**Returns:**
java.lang.Exception -
