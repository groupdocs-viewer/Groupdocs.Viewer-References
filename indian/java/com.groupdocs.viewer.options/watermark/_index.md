---
title: "Watermark"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "टेक्स्ट वॉटरमार्क का प्रतिनिधित्व करता है।"
type: docs
weight: 37
url: /hi/java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

एक टेक्स्ट वॉटरमार्क को दर्शाता है। विवरण के लिए, देखें [दस्तावेज़](../https://docs.groupdocs.com/viewer/net/add-text-watermark/).


Watermark क्लास GroupDocs.Viewer घटक में एक टेक्स्ट वॉटरमार्क को दर्शाता है।
यह दस्तावेज़ों के रेंडर किए गए आउटपुट पर वॉटरमार्क को परिभाषित करने और लागू करने के लिए उपयोग किया जाता है।


उदाहरण उपयोग:

````

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
 
````


## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [Watermark(String text)](#Watermark-java.lang.String-) | नए उदाहरण को प्रारंभ करता है |
Watermark
class।
|
## Methods

| Method | विवरण |
| --- | --- |
|  | [getText()](#getText--) | वॉटरमार्क टेक्स्ट लौटाता है। |
|
|  | [getColor()](#getColor--) | वॉटरमार्क रंग लौटाता है। |
|
|  | [getColorAsHex()](#getColorAsHex--) | वॉटरमार्क रंग को हेक्स फ़ॉर्मेट में लौटाता है। |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | वॉटरमार्क रंग सेट करता है। |
|
|  | [setColor(String colorName)](#setColor-java.lang.String-) | वॉटरमार्क रंग सेट करता है। |
|
|  | [getPosition()](#getPosition--) | वॉटरमार्क स्थिति लौटाता है। |
|
|  | [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | वॉटरमार्क स्थिति सेट करता है। |
|
|  | [getSize()](#getSize--) | वॉटरमार्क आकार लौटाता है। |
|
|  | [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | वॉटरमार्क का आकार सेट करता है। |
|
|  | [getFontName()](#getFontName--) | वॉटरमार्क के लिए उपयोग किए गए फ़ॉन्ट का नाम लौटाता है। |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | वॉटरमार्क के लिए उपयोग किए गए फ़ॉन्ट का नाम सेट करता है। |
|
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


नए उदाहरण को प्रारंभ करता है
Watermark
class।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | टेक्स्ट | java.lang.String | वॉटरमार्क टेक्स्ट। |
|

### getText() {#getText--}
```
public final String getText()
```


वॉटरमार्क टेक्स्ट लौटाता है।
यह मेथड दस्तावेज़ पर लागू वॉटरमार्क का टेक्स्ट प्राप्त करता है।


**Returns:**
java.lang.String - वॉटरमार्क टेक्स्ट।

### getColor() {#getColor--}
```
public final Color getColor()
```


वॉटरमार्क रंग लौटाता है।
यह मेथड दस्तावेज़ पर लागू वॉटरमार्क का रंग प्राप्त करता है।


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.awt.Color - वॉटरमार्क रंग।

### getColorAsHex() {#getColorAsHex--}
```
public final String getColorAsHex()
```


वॉटरमार्क रंग को हेक्स फ़ॉर्मेट में लौटाता है।
यह मेथड दस्तावेज़ पर लागू वॉटरमार्क का रंग प्राप्त करता है।


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.lang.String - हेक्स फॉर्मेट में वॉटरमार्क रंग।

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


वॉटरमार्क रंग सेट करता है।
यह मेथड दस्तावेज़ पर लागू वॉटरमार्क का रंग सेट करता है।


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.awt.Color | सेट करने के लिए वॉटरमार्क रंग। |
|

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


वॉटरमार्क रंग सेट करता है।
यह मेथड दस्तावेज़ पर लागू वॉटरमार्क का रंग सेट करता है।


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | colorName | java.lang.String | सेट करने के लिए वॉटरमार्क रंग। |
|

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


वॉटरमार्क स्थिति लौटाता है।
यह मेथड दस्तावेज़ पर लागू वॉटरमार्क की स्थिति लौटाता है।


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - the watermark position.

### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


वॉटरमार्क स्थिति सेट करता है।
यह मेथड दस्तावेज़ पर लागू वॉटरमार्क की स्थिति सेट करता है।


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [Position](../../com.groupdocs.viewer.options/position) | वॉटरमार्क स्थिति। |
|

### getSize() {#getSize--}
```
public final Size getSize()
```


वॉटरमार्क आकार लौटाता है।
यह मेथड दस्तावेज़ पर लागू वॉटरमार्क का आकार प्राप्त करता है।


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Returns:**
[Size](../../com.groupdocs.viewer.options/size) - the watermark size.

### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


वॉटरमार्क का आकार सेट करता है।
यह मेथड दस्तावेज़ पर लागू वॉटरमार्क का आकार सेट करता है।


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.viewer.options/size) | वॉटरमार्क आकार। |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


वॉटरमार्क के लिए उपयोग किए गए फ़ॉन्ट का नाम लौटाता है।


**Returns:**
java.lang.String - वॉटरमार्क के लिए उपयोग किया गया फ़ॉन्ट नाम।

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


वॉटरमार्क के लिए उपयोग किए गए फ़ॉन्ट का नाम सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | वॉटरमार्क के लिए उपयोग किया गया फ़ॉन्ट नाम। |
|

