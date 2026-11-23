---
title: "रोटेशन"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "पृष्ठ का घड़ी की दिशा में डिग्री में घुमाव शामिल है।"
type: docs
weight: 45
url: /hi/nodejs-java/com.groupdocs.viewer.options/rotation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Rotation extends Enum<Rotation>
```

पृष्ठ घुमाव को डिग्री में शामिल करता है (घड़ी की दिशा में)।

Rotation enum पृष्ठ के विभिन्न घुमाव कोणों को GroupDocs.Viewer घटक में दर्शाता है। यह पूर्वनिर्धारित घुमाव विकल्पों का एक सेट प्रदान करता है जिसका उपयोग विभिन्न दस्तावेज़ देखने या रूपांतरण परिदृश्यों में पृष्ठ को रेंडर करने के लिए घुमाव कोण निर्दिष्ट करने में किया जा सकता है।

उदाहरण उपयोग:

```

 PdfViewOptions pdfViewOptions = new PdfViewOptions();

 pdfViewOptions.rotatePage(1, Rotation.ON_90_DEGREE);
 pdfViewOptions.rotatePage(2, Rotation.ON_180_DEGREE);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [ON_90_DEGREE](#ON-90-DEGREE) | 90 डिग्री पृष्ठ घुमाव। |
| [ON_180_DEGREE](#ON-180-DEGREE) | 180 डिग्री पृष्ठ घुमाव। |
| [ON_270_DEGREE](#ON-270-DEGREE) | 270 डिग्री पृष्ठ घुमाव। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### ON_90_DEGREE {#ON-90-DEGREE}
```
public static final Rotation ON_90_DEGREE
```


90 डिग्री पृष्ठ घुमाव। यह घुमाव पृष्ठ का 90-डिग्री घड़ी की दिशा में घुमाव दर्शाता है।

### ON_180_DEGREE {#ON-180-DEGREE}
```
public static final Rotation ON_180_DEGREE
```


180 डिग्री पृष्ठ घुमाव। यह घुमाव पृष्ठ का 180-डिग्री घड़ी की दिशा में घुमाव दर्शाता है।

### ON_270_DEGREE {#ON-270-DEGREE}
```
public static final Rotation ON_270_DEGREE
```


270 डिग्री पृष्ठ घुमाव। यह घुमाव पृष्ठ का 270-डिग्री घड़ी की दिशा में घुमाव दर्शाता है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[Rotation](../../com.groupdocs.viewer.options/rotation)
