---
title: "FileNotFoundException"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "यह अपवाद तब फेंका जाता है जब फ़ाइल या निर्देशिका नहीं मिलती।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.viewer.exception/filenotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class FileNotFoundException extends GroupDocsViewerException
```

यह अपवाद तब फेंका जाता है जब कोई फ़ाइल या निर्देशिका नहीं मिलती। यह दर्शाता है कि निर्दिष्ट फ़ाइल या निर्देशिका मौजूद नहीं है या उसे एक्सेस नहीं किया जा सकता।

## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [FileNotFoundException(String message)](#FileNotFoundException-java.lang.String-) | निर्दिष्ट संदेश के साथ FileNotFoundException वर्ग का एक उदाहरण बनाता है। |
|
|  | [FileNotFoundException(Path path)](#FileNotFoundException-java.nio.file.Path-) | निर्दिष्ट फ़ाइल पथ के साथ FileNotFoundException वर्ग का नया उदाहरण प्रारंभ करता है। |
|
|  | [FileNotFoundException(String messageTemplate, Object[] params)](#FileNotFoundException-java.lang.String-java.lang.Object...-) | निर्दिष्ट त्रुटि संदेश के साथ FileNotFoundException वर्ग का नया उदाहरण बनाता है। |
|
|  | [FileNotFoundException(Throwable cause)](#FileNotFoundException-java.lang.Throwable-) | FileNotFoundException वर्ग का नया उदाहरण बनाता है। |
|
|  | [FileNotFoundException(String message, Throwable throwable)](#FileNotFoundException-java.lang.String-java.lang.Throwable-) | निर्दिष्ट त्रुटि संदेश के साथ FileNotFoundException वर्ग का नया उदाहरण प्रारंभ करता है। |
|
### FileNotFoundException(String message) {#FileNotFoundException-java.lang.String-}
```
public FileNotFoundException(String message)
```


निर्दिष्ट संदेश के साथ FileNotFoundException वर्ग का एक उदाहरण बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | संदेश | java.lang.String | त्रुटि का वर्णन करने वाला संदेश। |
|

### FileNotFoundException(Path path) {#FileNotFoundException-java.nio.file.Path-}
```
public FileNotFoundException(Path path)
```


निर्दिष्ट फ़ाइल पथ के साथ FileNotFoundException वर्ग का नया उदाहरण प्रारंभ करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | पाथ | java.nio.file.Path | फ़ाइल का पथ जो मौजूद नहीं है। |
|

### FileNotFoundException(String messageTemplate, Object[] params) {#FileNotFoundException-java.lang.String-java.lang.Object...-}
```
public FileNotFoundException(String messageTemplate, Object[] params)
```


निर्दिष्ट त्रुटि संदेश के साथ FileNotFoundException वर्ग का नया उदाहरण बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | messageTemplate | java.lang.String | त्रुटि का वर्णन करने वाला संदेश। |
|
|  | params | java.lang.Object[] | वे पैरामीटर जो त्रुटि संदेश में सेट किए जाएंगे। |
|

### FileNotFoundException(Throwable cause) {#FileNotFoundException-java.lang.Throwable-}
```
public FileNotFoundException(Throwable cause)
```


FileNotFoundException वर्ग का नया उदाहरण बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | कारण | java.lang.Throwable | अपवाद का कारण। |
|

### FileNotFoundException(String message, Throwable throwable) {#FileNotFoundException-java.lang.String-java.lang.Throwable-}
```
public FileNotFoundException(String message, Throwable throwable)
```


निर्दिष्ट त्रुटि संदेश के साथ FileNotFoundException वर्ग का नया उदाहरण प्रारंभ करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | संदेश | java.lang.String | त्रुटि का वर्णन करने वाला संदेश। |
|
|  | throwable | java.lang.Throwable | वह throwable जो अपवाद का कारण बना। |
|

