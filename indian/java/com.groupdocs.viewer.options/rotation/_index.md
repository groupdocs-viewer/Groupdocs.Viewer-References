---
title: "Rotation"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "पृष्ठ घूर्णन को घड़ी की दिशा में डिग्री में शामिल करता है।"
type: docs
weight: 45
url: /hi/java/com.groupdocs.viewer.options/rotation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Rotation extends Enum<Rotation>
```

पृष्ठ घूर्णन को डिग्री में शामिल करता है (घड़ी की दिशा में)।


Rotation enum GroupDocs.Viewer घटक में पृष्ठ के विभिन्न घूर्णन कोणों का प्रतिनिधित्व करता है।
यह पूर्वनिर्धारित घूर्णन विकल्पों का एक सेट प्रदान करता है जिसे घूर्णन कोण निर्दिष्ट करने के लिए उपयोग किया जा सकता है।
विभिन्न दस्तावेज़ देखना या रूपांतरण परिदृश्यों में पृष्ठ को रेंडर करने के लिए।


उदाहरण उपयोग:

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();

 pdfViewOptions.rotatePage(1, Rotation.ON_90_DEGREE);
 pdfViewOptions.rotatePage(2, Rotation.ON_180_DEGREE);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Fields

| Field | विवरण |
| --- | --- |
|  | [ON_90_DEGREE](#ON-90-DEGREE) | 90 डिग्री पृष्ठ घूर्णन। |
|
|  | [ON_180_DEGREE](#ON-180-DEGREE) | 180 डिग्री पृष्ठ घूर्णन। |
|
|  | [ON_270_DEGREE](#ON-270-DEGREE) | 270 डिग्री पृष्ठ घूर्णन। |
|
## Methods

| Method | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### ON_90_DEGREE {#ON-90-DEGREE}
```
public static final Rotation ON_90_DEGREE
```


90 डिग्री पृष्ठ घूर्णन।
यह घूर्णन पृष्ठ का 90-डिग्री घड़ी की दिशा में घूर्णन दर्शाता है।


### ON_180_DEGREE {#ON-180-DEGREE}
```
public static final Rotation ON_180_DEGREE
```


180 डिग्री पृष्ठ घूर्णन।
यह घूर्णन पृष्ठ का 180-डिग्री घड़ी की दिशा में घूर्णन दर्शाता है।


### ON_270_DEGREE {#ON-270-DEGREE}
```
public static final Rotation ON_270_DEGREE
```


270 डिग्री पृष्ठ घूर्णन।
यह घूर्णन पृष्ठ का 270-डिग्री घड़ी की दिशा में घूर्णन दर्शाता है।


### values() {#values--}
```
public static Rotation[] values()
```




**Returns:**
com.groupdocs.viewer.options.Rotation[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Rotation valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[Rotation](../../com.groupdocs.viewer.options/rotation)
