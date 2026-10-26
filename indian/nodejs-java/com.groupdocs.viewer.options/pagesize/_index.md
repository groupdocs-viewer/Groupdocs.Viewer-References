---
title: "PageSize"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "पृष्ठ का आकार।"
type: docs
weight: 42
url: /hi/nodejs-java/com.groupdocs.viewer.options/pagesize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PageSize extends Enum<PageSize>
```

पृष्ठ का आकार।

PageSize enum GroupDocs.Viewer घटक में विभिन्न पेज आकारों का प्रतिनिधित्व करता है। यह पूर्वनिर्धारित पेज आकारों का एक सेट प्रदान करता है जिसे विभिन्न दस्तावेज़ रेंडरिंग परिदृश्यों में पेज के आयाम निर्दिष्ट करने के लिए उपयोग किया जा सकता है।

उदाहरण उपयोग:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = htmlViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | डिफ़ॉल्ट, अनिर्दिष्ट पेज आकार। |
| [LETTER](#LETTER) | Letter पृष्ठ का आकार पॉइंट्स में 792 x 612 है। |
| [LEDGER](#LEDGER) | A0 पृष्ठ का आकार पॉइंट्स में 3371 x 2384 है। |
| [A0](#A0) | A1 पृष्ठ का आकार पॉइंट्स में 2384 x 1685 है। |
| [A1](#A1) | A2 पृष्ठ का आकार पॉइंट्स में 1684 x 1190 है। |
| [A2](#A2) | A3 पृष्ठ का आकार पॉइंट्स में 1190 x 842 है। |
| [A3](#A3) | A3 पृष्ठ का आकार पॉइंट्स में 1190 x 842 है। |
| [A4](#A4) | A4 पृष्ठ का आकार पॉइंट्स में 842 x 595 है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final PageSize UNSPECIFIED
```


डिफ़ॉल्ट, अनिर्दिष्ट पृष्ठ आकार। यह आकार तब उपयोग किया जाता है जब कोई विशिष्ट पृष्ठ आकार निर्दिष्ट नहीं किया जाता।

### LETTER {#LETTER}
```
public static final PageSize LETTER
```


Letter पृष्ठ का आकार पॉइंट्स में 792 x 612 है। यह पृष्ठ आकार उत्तरी अमेरिका में पत्रों और दस्तावेज़ों के लिए सामान्यतः उपयोग किया जाता है।

### LEDGER {#LEDGER}
```
public static final PageSize LEDGER
```


A0 पृष्ठ का आकार पॉइंट्स में 3371 x 2384 है। यह बड़ा पृष्ठ आकार ISO 216 अंतरराष्ट्रीय मानक का हिस्सा है।

### A0 {#A0}
```
public static final PageSize A0
```


A1 पृष्ठ का आकार पॉइंट्स में 2384 x 1685 है। यह पृष्ठ आकार ISO 216 अंतरराष्ट्रीय मानक का हिस्सा है।

### A1 {#A1}
```
public static final PageSize A1
```


A2 पृष्ठ का आकार पॉइंट्स में 1684 x 1190 है। यह पृष्ठ आकार ISO 216 अंतरराष्ट्रीय मानक का हिस्सा है।

### A2 {#A2}
```
public static final PageSize A2
```


A3 पृष्ठ का आकार पॉइंट्स में 1190 x 842 है। यह पृष्ठ आकार ISO 216 अंतरराष्ट्रीय मानक का हिस्सा है।

### A3 {#A3}
```
public static final PageSize A3
```


A3 पृष्ठ का आकार पॉइंट्स में 1190 x 842 है। यह पृष्ठ आकार ISO 216 अंतरराष्ट्रीय मानक का हिस्सा है।

### A4 {#A4}
```
public static final PageSize A4
```


A4 पृष्ठ का आकार पॉइंट्स में 842 x 595 है। यह पृष्ठ आकार ISO 216 अंतरराष्ट्रीय मानक का हिस्सा है।

### values() {#values--}
```
public static PageSize[] values()
```




**Returns:**
com.groupdocs.viewer.options.PageSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PageSize valueOf(String name)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize)
