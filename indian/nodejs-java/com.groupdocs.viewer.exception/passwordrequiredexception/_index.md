---
title: "PasswordRequiredException"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "जब दस्तावेज़ लोड करने के लिए पासवर्ड आवश्यक होता है, तो यह अपवाद फेंका जाता है।"
type: docs
weight: 15
url: /hi/nodejs-java/com.groupdocs.viewer.exception/passwordrequiredexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class PasswordRequiredException extends GroupDocsViewerException
```

जब दस्तावेज़ को लोड करने के लिए पासवर्ड आवश्यक होता है तो यह अपवाद फेंका जाता है। यह अपवाद आमतौर पर तब होता है जब किसी एन्क्रिप्टेड या पासवर्ड-प्रोटेक्टेड दस्तावेज़ को वैध पासवर्ड प्रदान किए बिना लोड या खोलने का प्रयास किया जाता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PasswordRequiredException()](#PasswordRequiredException--) | PasswordRequiredException क्लास का नया उदाहरण प्रारंभ करता है। |
| [PasswordRequiredException(String message)](#PasswordRequiredException-java.lang.String-) | PasswordRequiredException क्लास का नया उदाहरण एक कस्टम अपवाद संदेश के साथ प्रारंभ करता है। |
| [PasswordRequiredException(String message, Throwable throwable)](#PasswordRequiredException-java.lang.String-java.lang.Throwable-) | PasswordRequiredException क्लास का नया उदाहरण निर्दिष्ट त्रुटि संदेश के साथ प्रारंभ करता है। |
### PasswordRequiredException() {#PasswordRequiredException--}
```
public PasswordRequiredException()
```


PasswordRequiredException क्लास का नया उदाहरण प्रारंभ करता है।

### PasswordRequiredException(String message) {#PasswordRequiredException-java.lang.String-}
```
public PasswordRequiredException(String message)
```


PasswordRequiredException क्लास का नया उदाहरण एक कस्टम अपवाद संदेश के साथ प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संदेश | java.lang.String |  |

### PasswordRequiredException(String message, Throwable throwable) {#PasswordRequiredException-java.lang.String-java.lang.Throwable-}
```
public PasswordRequiredException(String message, Throwable throwable)
```


PasswordRequiredException क्लास का नया उदाहरण निर्दिष्ट त्रुटि संदेश के साथ प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संदेश | java.lang.String | संदेश। |
| throwable | java.lang.Throwable | यह throwable। |

