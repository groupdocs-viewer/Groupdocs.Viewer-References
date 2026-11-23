---
title: "Size"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "वॉटरमार्क आकार शामिल है।"
type: docs
weight: 30
url: /hi/nodejs-java/com.groupdocs.viewer.options/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

वॉटरमार्क आकार शामिल है।

Size क्लास GroupDocs.Viewer घटक में वॉटरमार्क का आकार दर्शाती है। यह वॉटरमार्क की आयाम, जैसे चौड़ाई और ऊँचाई, निर्दिष्ट करने के विकल्प प्रदान करती है।

उदाहरण उपयोग:

```

 Watermark watermark = new Watermark("Watermark");
 watermark.setPosition(Position.DIAGONAL);
 watermark.setColor(java.awt.Color.GREEN);
 watermark.setSize(Size.HALF_SIZE);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setWatermark(watermark);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Size(byte relativeSize)](#Size-byte-) | Size क्लास का एक नया उदाहरण आरंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [FULL_SIZE](#FULL-SIZE) | पृष्ठ में फिट होने वाले वॉटरमार्क टेक्स्ट का अधिकतम आकार दर्शाता है। |
| [HALF_SIZE](#HALF-SIZE) | पृष्ठ में फिट होने वाले वॉटरमार्क टेक्स्ट के अधिकतम आकार का आधा दर्शाता है। |
| [ONE_THIRD](#ONE-THIRD) | पृष्ठ में फिट होने वाले वॉटरमार्क टेक्स्ट के अधिकतम आकार का एक तिहाई दर्शाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getRelativeSize()](#getRelativeSize--) | पृष्ठ की चौड़ाई के संबंध में वॉटरमार्क टेक्स्ट आकार को प्रतिशत में लौटाता है। |
### Size(byte relativeSize) {#Size-byte-}
```
public Size(byte relativeSize)
```


Size क्लास का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| relativeSize | byte | पृष्ठ के आकार के संबंध में प्रतिशत में आकार। |

### FULL_SIZE {#FULL-SIZE}
```
public static final Size FULL_SIZE
```


पृष्ठ में फिट होने वाले वॉटरमार्क टेक्स्ट का अधिकतम आकार दर्शाता है।

### HALF_SIZE {#HALF-SIZE}
```
public static final Size HALF_SIZE
```


पृष्ठ में फिट होने वाले वॉटरमार्क टेक्स्ट के अधिकतम आकार का आधा दर्शाता है।

### ONE_THIRD {#ONE-THIRD}
```
public static final Size ONE_THIRD
```


पृष्ठ में फिट होने वाले वॉटरमार्क टेक्स्ट के अधिकतम आकार का एक तिहाई दर्शाता है।

### getRelativeSize() {#getRelativeSize--}
```
public final byte getRelativeSize()
```


पृष्ठ की चौड़ाई के संबंध में वॉटरमार्क टेक्स्ट आकार को प्रतिशत में लौटाता है।

**Returns:**
byte - वॉटरमार्क टेक्स्ट आकार प्रतिशत में।
