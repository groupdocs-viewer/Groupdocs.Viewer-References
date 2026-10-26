---
title: "पृष्ठ"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "एक पृष्ठ जिसे देखा जा सकता है, उसका प्रतिनिधित्व करता है।"
type: docs
weight: 21
url: /hi/nodejs-java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

एक पृष्ठ जिसे देखा जा सकता है, उसका प्रतिनिधित्व करता है।

Page इंटरफ़ेस एक अनुबंध परिभाषित करता है जो GroupDocs.Viewer घटक में देखी जा सकने वाले एकल पृष्ठ तक पहुँचने और उसे संशोधित करने के लिए है। यह पृष्ठ संख्या, आकार, और अन्य गुण जैसी जानकारी प्राप्त करने के लिए विधियाँ प्रदान करता है।

उदाहरण उपयोग:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List pages = viewInfo.getPages();
     for (Page page : pages) {
         // Use the page object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is PageImpl.*
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getName()](#getName--) | वर्कशीट या पृष्ठ का नाम प्राप्त करता है। |
| [setName(String name)](#setName-java.lang.String-) | वर्कशीट या पृष्ठ का नाम सेट करता है। |
| [getNumber()](#getNumber--) | पृष्ठ संख्या प्राप्त करता है। |
| [setNumber(int number)](#setNumber-int-) | पृष्ठ संख्या सेट करता है। |
| [isVisible()](#isVisible--) | पृष्ठ दृश्यता संकेतक प्राप्त करता है। |
| [setVisible(boolean visible)](#setVisible-boolean-) | पृष्ठ दृश्यता संकेतक सेट करता है। |
| [getWidth()](#getWidth--) | JPG या PNG के रूप में देखते समय पृष्ठ की चौड़ाई पिक्सेल में प्राप्त करता है। |
| [setWidth(int width)](#setWidth-int-) | JPG या PNG के रूप में देखते समय पृष्ठ की चौड़ाई पिक्सेल में सेट करता है। |
| [getHeight()](#getHeight--) | JPG या PNG के रूप में देखते समय पृष्ठ की ऊँचाई पिक्सेल में प्राप्त करता है। |
| [setHeight(int height)](#setHeight-int-) | JPG या PNG के रूप में देखते समय पृष्ठ की ऊँचाई पिक्सेल में सेट करता है। |
| [getLines()](#getLines--) | JPG या PNG के रूप में देखते समय, सक्षम टेक्स्ट एक्सट्रैक्शन के साथ पृष्ठ में मौजूद लाइनों को प्राप्त करता है। |
| [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | JPG या PNG के रूप में देखते समय, सक्षम टेक्स्ट एक्सट्रैक्शन के साथ पृष्ठ में मौजूद लाइनों को सेट करता है। |
### getName() {#getName--}
```
public abstract String getName()
```


वर्कशीट या पृष्ठ का नाम प्राप्त करता है।

**Returns:**
java.lang.String - वर्कशीट या पृष्ठ का नाम।
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


वर्कशीट या पृष्ठ का नाम सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | वर्कशीट या पृष्ठ के लिए सेट करने वाला नाम। |

### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


पृष्ठ संख्या प्राप्त करता है।

**Returns:**
int - पृष्ठ संख्या।
### setNumber(int number) {#setNumber-int-}
```
public abstract void setNumber(int number)
```


पृष्ठ संख्या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संख्या | int | सेट करने के लिए पृष्ठ संख्या। |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


पृष्ठ दृश्यता संकेतक प्राप्त करता है।

**Returns:**
boolean - पृष्ठ दृश्यता संकेतक।
### setVisible(boolean visible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean visible)
```


पृष्ठ दृश्यता संकेतक सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| दृश्यमान | boolean | यदि पृष्ठ दृश्यमान है तो true, अन्यथा false। |

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


JPG या PNG के रूप में देखते समय पृष्ठ की चौड़ाई पिक्सेल में प्राप्त करता है।

**Returns:**
int - पृष्ठ की चौड़ाई।
### setWidth(int width) {#setWidth-int-}
```
public abstract void setWidth(int width)
```


JPG या PNG के रूप में देखते समय पृष्ठ की चौड़ाई पिक्सेल में सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | int | पृष्ठ के लिए सेट करने वाली चौड़ाई। |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


JPG या PNG के रूप में देखते समय पृष्ठ की ऊँचाई पिक्सेल में प्राप्त करता है।

**Returns:**
int - पृष्ठ की ऊँचाई।
### setHeight(int height) {#setHeight-int-}
```
public abstract void setHeight(int height)
```


JPG या PNG के रूप में देखते समय पृष्ठ की ऊँचाई पिक्सेल में सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| height | int | पृष्ठ के लिए सेट करने वाली ऊँचाई। |

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


JPG या PNG के रूप में देखते समय, सक्षम टेक्स्ट एक्सट्रैक्शन के साथ पृष्ठ में मौजूद लाइनों को प्राप्त करता है।

**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - पृष्ठ में मौजूद पंक्तियाँ।
### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


JPG या PNG के रूप में देखते समय, सक्षम टेक्स्ट एक्सट्रैक्शन के साथ पृष्ठ में मौजूद लाइनों को सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पंक्तियाँ | java.util.List<com.groupdocs.viewer.results.Line> | पृष्ठ के लिए सेट करने वाली पंक्तियों की सूची। |

