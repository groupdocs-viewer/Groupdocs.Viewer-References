---
title: "Position"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "वॉटरमार्क की स्थिति निर्धारित करता है।"
type: docs
weight: 43
url: /hi/nodejs-java/com.groupdocs.viewer.options/position/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Position extends Enum<Position>
```

वॉटरमार्क की स्थिति निर्धारित करता है।

Position enum वॉटरमार्क के लिए विभिन्न स्थितियों का प्रतिनिधित्व करता है जो GroupDocs.Viewer घटक में उपयोग होती हैं। यह पूर्वनिर्धारित स्थितियों का एक सेट प्रदान करता है जिसे दस्तावेज़ या छवि पर वॉटरमार्क की स्थिति निर्दिष्ट करने के लिए रेंडरिंग प्रक्रिया के दौरान उपयोग किया जा सकता है।

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
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [DIAGONAL](#DIAGONAL) | विकर्ण स्थिति। |
| [TOP_LEFT](#TOP-LEFT) | ऊपरी बाएँ स्थिति। |
| [TOP_CENTER](#TOP-CENTER) | ऊपरी मध्य स्थिति। |
| [TOP_RIGHT](#TOP-RIGHT) | ऊपरी दाएँ स्थिति। |
| [BOTTOM_LEFT](#BOTTOM-LEFT) | निचला बाएँ स्थिति। |
| [BOTTOM_CENTER](#BOTTOM-CENTER) | निचला मध्य स्थिति। |
| [BOTTOM_RIGHT](#BOTTOM-RIGHT) | निचला दाएँ स्थिति। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### DIAGONAL {#DIAGONAL}
```
public static final Position DIAGONAL
```


विकर्ण स्थिति। यह स्थिति एक विकर्ण संरेखण या प्लेसमेंट का प्रतिनिधित्व करती है।

### TOP_LEFT {#TOP-LEFT}
```
public static final Position TOP_LEFT
```


ऊपरी बाएँ स्थिति। यह स्थिति ऊपरी बाएँ कोने के संरेखण या प्लेसमेंट का प्रतिनिधित्व करती है।

### TOP_CENTER {#TOP-CENTER}
```
public static final Position TOP_CENTER
```


ऊपरी मध्य स्थिति। यह स्थिति ऊपरी मध्य संरेखण या प्लेसमेंट का प्रतिनिधित्व करती है।

### TOP_RIGHT {#TOP-RIGHT}
```
public static final Position TOP_RIGHT
```


ऊपरी दाएँ स्थिति। यह स्थिति ऊपरी दाएँ कोने के संरेखण या प्लेसमेंट का प्रतिनिधित्व करती है।

### BOTTOM_LEFT {#BOTTOM-LEFT}
```
public static final Position BOTTOM_LEFT
```


निचला बाएँ स्थिति। यह स्थिति निचले बाएँ कोने के संरेखण या प्लेसमेंट का प्रतिनिधित्व करती है।

### BOTTOM_CENTER {#BOTTOM-CENTER}
```
public static final Position BOTTOM_CENTER
```


निचला मध्य स्थिति। यह स्थिति निचले मध्य संरेखण या प्लेसमेंट का प्रतिनिधित्व करती है।

### BOTTOM_RIGHT {#BOTTOM-RIGHT}
```
public static final Position BOTTOM_RIGHT
```


निचला दाएँ स्थिति। यह स्थिति निचले दाएँ कोने के संरेखण या प्लेसमेंट का प्रतिनिधित्व करती है।

### values() {#values--}
```
public static Position[] values()
```




**Returns:**
com.groupdocs.viewer.options.Position[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Position valueOf(String name)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.viewer.options/position)
