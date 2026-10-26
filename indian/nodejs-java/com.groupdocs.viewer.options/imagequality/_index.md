---
title: "ImageQuality"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "PDF दस्तावेज़ों द्वारा शामिल आउटपुट HTML में इमेज की गुणवत्ता।"
type: docs
weight: 41
url: /hi/nodejs-java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

PDF दस्तावेज़ों द्वारा शामिल आउटपुट HTML में इमेज की गुणवत्ता।

ImageQuality enum PDF दस्तावेज़ों में GroupDocs.Viewer घटक द्वारा उत्पन्न आउटपुट HTML में छवियों की गुणवत्ता को दर्शाता है। यह विभिन्न स्तरों की छवि गुणवत्ता प्रदान करता है जिसका उपयोग उत्पन्न HTML आउटपुट में छवियों के रेंडरिंग और संपीड़न को नियंत्रित करने के लिए किया जा सकता है।

उदाहरण उपयोग:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [LOW](#LOW) | स्वीकार्य गुणवत्ता और सर्वोत्तम प्रदर्शन। |
| [MEDIUM](#MEDIUM) | बेहतर गुणवत्ता और धीमा प्रदर्शन। |
| [HIGH](#HIGH) | सर्वोत्तम गुणवत्ता लेकिन धीमा प्रदर्शन। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


स्वीकार्य गुणवत्ता और सर्वोत्तम प्रदर्शन। यह सेटिंग रेंडरिंग गति को छवि गुणवत्ता पर प्राथमिकता देती है।

### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


बेहतर गुणवत्ता और धीमा प्रदर्शन। यह सेटिंग छवि गुणवत्ता और रेंडरिंग गति के बीच संतुलन प्रदान करती है।

### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


सर्वोत्तम गुणवत्ता लेकिन धीमा प्रदर्शन। यह सेटिंग रेंडरिंग गति पर छवि गुणवत्ता को प्राथमिकता देती है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality)
