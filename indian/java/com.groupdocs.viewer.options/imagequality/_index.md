---
title: "ImageQuality"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "PDF दस्तावेज़ों में निहित आउटपुट HTML में छवियों की गुणवत्ता।"
type: docs
weight: 41
url: /hi/java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

PDF दस्तावेज़ों में निहित आउटपुट HTML में छवियों की गुणवत्ता।


ImageQuality एन्‍युम आउटपुट HTML में PDF दस्तावेज़ों द्वारा सम्मिलित छवियों की गुणवत्ता को दर्शाता है।
GroupDocs.Viewer घटक में। यह उपयोग किए जा सकने वाले छवि गुणवत्ता के विभिन्न स्तर प्रदान करता है।
जेनरेटेड HTML आउटपुट में छवियों की रेंडरिंग और संपीड़न को नियंत्रित करने के लिए।


उदाहरण उपयोग:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Fields

| Field | विवरण |
| --- | --- |
|  | [LOW](#LOW) | स्वीकार्य गुणवत्ता और सर्वोत्तम प्रदर्शन। |
|
|  | [MEDIUM](#MEDIUM) | बेहतर गुणवत्ता और धीमी प्रदर्शन। |
|
|  | [HIGH](#HIGH) | सर्वोत्तम गुणवत्ता लेकिन धीमा प्रदर्शन। |
|
## Methods

| Method | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


स्वीकार्य गुणवत्ता और सर्वोत्तम प्रदर्शन।
यह सेटिंग रेंडरिंग गति को इमेज क्वालिटी पर प्राथमिकता देती है।


### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


बेहतर गुणवत्ता और धीमी प्रदर्शन।
यह सेटिंग इमेज क्वालिटी और रेंडरिंग गति के बीच संतुलन प्रदान करती है।


### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


सर्वोत्तम गुणवत्ता लेकिन धीमा प्रदर्शन।
यह सेटिंग रेंडरिंग गति पर इमेज क्वालिटी को प्राथमिकता देती है।


### values() {#values--}
```
public static ImageQuality[] values()
```




**Returns:**
com.groupdocs.viewer.options.ImageQuality[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ImageQuality valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality)
