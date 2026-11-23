---
title: "Watermark"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "एक टेक्स्ट वॉटरमार्क का प्रतिनिधित्व करता है।"
type: docs
weight: 37
url: /hi/nodejs-java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

एक टेक्स्ट वॉटरमार्क का प्रतिनिधित्व करता है। विवरण के लिए, देखें [documentation][].

Watermark क्लास GroupDocs.Viewer घटक में एक टेक्स्ट वॉटरमार्क का प्रतिनिधित्व करती है। इसका उपयोग दस्तावेज़ों के रेंडर किए गए आउटपुट पर वॉटरमार्क को परिभाषित करने और लागू करने के लिए किया जाता है।

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


[documentation]: https://docs.groupdocs.com/viewer/net/add-text-watermark/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Watermark(String text)](#Watermark-java.lang.String-) | Watermark क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getText()](#getText--) | वॉटरमार्क टेक्स्ट लौटाता है। |
| [getColor()](#getColor--) | वॉटरमार्क का रंग लौटाता है। |
| [getColorAsHex()](#getColorAsHex--) | वॉटरमार्क का रंग हेक्स फ़ॉर्मेट में लौटाता है। |
| [setColor(Color value)](#setColor-java.awt.Color-) | वॉटरमार्क का रंग सेट करता है। |
| [setColor(String colorName)](#setColor-java.lang.String-) | वॉटरमार्क का रंग सेट करता है। |
| [getPosition()](#getPosition--) | वॉटरमार्क की स्थिति लौटाता है। |
| [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | वॉटरमार्क की स्थिति सेट करता है। |
| [getSize()](#getSize--) | वॉटरमार्क का आकार लौटाता है। |
| [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | वॉटरमार्क का आकार सेट करता है। |
| [getFontName()](#getFontName--) | वॉटरमार्क के लिए उपयोग किए गए फ़ॉन्ट का नाम लौटाता है। |
| [setFontName(String value)](#setFontName-java.lang.String-) | वॉटरमार्क के लिए उपयोग किए गए फ़ॉन्ट का नाम सेट करता है। |
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


Watermark क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| टेक्स्ट | java.lang.String | वॉटरमार्क टेक्स्ट। |

### getText() {#getText--}
```
public final String getText()
```


वॉटरमार्क टेक्स्ट लौटाता है। यह मेथड दस्तावेज़ पर लागू वॉटरमार्क का टेक्स्ट प्राप्त करता है।

**Returns:**
java.lang.String - वॉटरमार्क टेक्स्ट।
### getColor() {#getColor--}
```
public final Color getColor()
```


वॉटरमार्क का रंग लौटाता है। यह मेथड दस्तावेज़ पर लागू वॉटरमार्क का रंग प्राप्त करता है।

***Note:** The default value is the red color obtained from Color\#getRed().getRed().*

**Returns:**
java.awt.Color - वॉटरमार्क रंग।
### getColorAsHex() {#getColorAsHex--}
```
public final String getColorAsHex()
```


वॉटरमार्क का रंग हेक्स फ़ॉर्मेट में लौटाता है। यह मेथड दस्तावेज़ पर लागू वॉटरमार्क का रंग प्राप्त करता है।

***Note:** The default value is the red color obtained from Color\#getRed().getRed().*

**Returns:**
java.lang.String - हेक्स फ़ॉर्मेट में वॉटरमार्क रंग।
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


वॉटरमार्क का रंग सेट करता है। यह मेथड दस्तावेज़ पर लागू वॉटरमार्क का रंग सेट करता है।

***Note:** The default value is obtained from Color\#getRed().getRed().*

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.awt.Color | सेट करने के लिए वॉटरमार्क रंग। |

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


वॉटरमार्क का रंग सेट करता है। यह मेथड दस्तावेज़ पर लागू वॉटरमार्क का रंग सेट करता है।

***Note:** The default value is obtained from Color\#getRed().getRed().*

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorName | java.lang.String | सेट करने के लिए वॉटरमार्क रंग। |

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


वॉटरमार्क की स्थिति लौटाता है। यह मेथड दस्तावेज़ पर लागू वॉटरमार्क की स्थिति लौटाता है।

***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).*

**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - the watermark position.
### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


वॉटरमार्क की स्थिति सेट करता है। यह मेथड दस्तावेज़ पर लागू वॉटरमार्क की स्थिति सेट करता है।

***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).*

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Position](../../com.groupdocs.viewer.options/position) | वॉटरमार्क स्थिति। |

### getSize() {#getSize--}
```
public final Size getSize()
```


वॉटरमार्क का आकार लौटाता है। यह मेथड दस्तावेज़ पर लागू वॉटरमार्क का आकार प्राप्त करता है।

***Note:** The default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).*

**Returns:**
[Size](../../com.groupdocs.viewer.options/size) - the watermark size.
### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


वॉटरमार्क का आकार सेट करता है। यह मेथड दस्तावेज़ पर लागू किए जाने वाले वॉटरमार्क का आकार निर्धारित करता है।

***Note:** The default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).*

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Size](../../com.groupdocs.viewer.options/size) | वॉटरमार्क का आकार। |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String | वॉटरमार्क के लिए उपयोग किया गया फ़ॉन्ट नाम। |

