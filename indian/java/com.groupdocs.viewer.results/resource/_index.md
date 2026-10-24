---
title: "Resource"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "फ़ॉन्ट, स्टाइल, छवि या ग्राफ़िक्स जैसे HTML संसाधन का प्रतिनिधित्व करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.viewer.results/resource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Serializable
```
public class Resource implements Serializable
```

फ़ॉन्ट, स्टाइल, इमेज या ग्राफ़िक्स जैसे HTML रिसोर्स का प्रतिनिधित्व करता है।


Resource क्लास HTML रेंडरिंग में GroupDocs.Viewer घटक द्वारा उपयोग किए जाने वाले संसाधन का प्रतिनिधित्व करती है।
यह विभिन्न प्रकार के संसाधनों का प्रतिनिधित्व कर सकता है, जैसे फ़ॉन्ट, स्टाइल, छवियां या ग्राफ़िक्स, जो शामिल हैं
या रेंडरिंग प्रक्रिया के दौरान उत्पन्न HTML आउटपुट में संदर्भित होते हैं।


उदाहरण उपयोग:

````

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forExternalResources(pageNumber -> , new ReleaseResourceStream() {
     @Override
     public void invoke(int pageNumber, Resource resource, OutputStream resourceStream) {
         // Handle resource
     }
 });
 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [Resource(String fileName, boolean nested)](#Resource-java.lang.String-boolean-) | नया उदाहरण बनाता है |
Resource
class।
|
## Methods

| Method | विवरण |
| --- | --- |
|  | [getFileName()](#getFileName--) | संसाधन का फ़ाइल नाम लौटाता है। |
|
|  | [setFileName(String fileName)](#setFileName-java.lang.String-) | संसाधन का फ़ाइल नाम सेट करता है। |
|
|  | [isNested()](#isNested--) | यह लौटाता है कि संसाधन किसी अन्य संसाधन के भीतर स्थित है या नहीं, उदाहरण के लिए एक फ़ॉन्ट संसाधन जो CSS या SVG संसाधन में स्थित है। |
|
|  | [setNested(boolean nested)](#setNested-boolean-) | संसाधन के किसी अन्य संसाधन के भीतर स्थित होने की स्थिति सेट करता है। |
|
|  | [toString()](#toString--) | वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |
|
### Resource(String fileName, boolean nested) {#Resource-java.lang.String-boolean-}
```
public Resource(String fileName, boolean nested)
```


नया उदाहरण बनाता है
Resource
class।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileName | java.lang.String | संसाधन फ़ाइल नाम। |
|
|  | नेस्टेड | boolean | यह दर्शाता है कि संसाधन किसी अन्य संसाधन के भीतर स्थित है या नहीं, उदाहरण के लिए एक फ़ॉन्ट संसाधन जो CSS या SVG संसाधन में स्थित है। |
|

### getFileName() {#getFileName--}
```
public final String getFileName()
```


संसाधन का फ़ाइल नाम लौटाता है।


**Returns:**
java.lang.String - संसाधन का फ़ाइल नाम।

### setFileName(String fileName) {#setFileName-java.lang.String-}
```
public void setFileName(String fileName)
```


संसाधन का फ़ाइल नाम सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileName | java.lang.String | संसाधन के लिए नया फ़ाइल नाम। |
|

### isNested() {#isNested--}
```
public final boolean isNested()
```


यह लौटाता है कि संसाधन किसी अन्य संसाधन के भीतर स्थित है या नहीं, उदाहरण के लिए एक फ़ॉन्ट संसाधन जो CSS या SVG संसाधन में स्थित है।


**Returns:**
boolean - क्या संसाधन किसी अन्य संसाधन के भीतर स्थित है।

### setNested(boolean nested) {#setNested-boolean-}
```
public void setNested(boolean nested)
```


संसाधन के किसी अन्य संसाधन के भीतर स्थित होने की स्थिति सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | नेस्टेड | boolean | क्या संसाधन को नेस्टेड के रूप में सेट किया जाना चाहिए। |
|

### toString() {#toString--}
```
public String toString()
```


वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है।


**Returns:**
java.lang.String - वर्तमान वस्तु का स्ट्रिंग प्रतिनिधित्व।

