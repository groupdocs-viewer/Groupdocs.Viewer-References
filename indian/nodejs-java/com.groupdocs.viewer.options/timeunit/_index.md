---
title: "TimeUnit"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "प्रोजेक्ट अवधि की समय इकाई।"
type: docs
weight: 47
url: /hi/nodejs-java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

प्रोजेक्ट अवधि की समय इकाई।

TimeUnit enum प्रोजेक्ट की अवधि निर्दिष्ट करने के लिए विभिन्न समय इकाइयों का प्रतिनिधित्व करता है जो GroupDocs.Viewer घटक में उपयोग होती हैं। यह पूर्वनिर्धारित समय इकाइयों का एक सेट प्रदान करता है जिसे प्रोजेक्ट की अवधि को दर्शाने और गणना करने के लिए उपयोग किया जा सकता है, जैसे दिन, महीने आदि। विवरण के लिए, देखें [documentation][].

उदाहरण उपयोग:

```

 HtmlViewOptions pdfViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = pdfViewOptions.getProjectManagementOptions();
 projectManagementOptions.setTimeUnit(TimeUnit.MONTHS);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | अज्ञात समय स्केल। |
| [DAYS](#DAYS) | दिनों का समय स्केल। |
| [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | महीनों के तिहाई का समय स्केल। |
| [MONTHS](#MONTHS) | महीनों का समय स्केल। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


अज्ञात समय स्केल। यह समय इकाई एक अज्ञात या अनिर्दिष्ट समय स्केल का प्रतिनिधित्व करती है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


दिनों का समय स्केल। यह समय इकाई एक-दिन अंतराल का प्रतिनिधित्व करती है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


महीनों के तिहाई का समय स्केल। यह समय इकाई महीने के एक-तिहाई अंतराल का प्रतिनिधित्व करती है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


महीनों का समय स्केल। यह समय इकाई एक-महीने का अंतराल दर्शाती है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### values() {#values--}
```
public static TimeUnit[] values()
```




**Returns:**
com.groupdocs.viewer.options.TimeUnit[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TimeUnit valueOf(String name)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit)
