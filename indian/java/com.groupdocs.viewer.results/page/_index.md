---
title: "पृष्ठ"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "एक एकल पृष्ठ का प्रतिनिधित्व करता है जिसे देखा जा सकता है।"
type: docs
weight: 23
url: /hi/java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

एक एकल पृष्ठ का प्रतिनिधित्व करता है जिसे देखा जा सकता है।


Page इंटरफ़ेस एकल पृष्ठ तक पहुँचने और उसे संशोधित करने के अनुबंध को परिभाषित करता है।
जो GroupDocs.Viewer घटक में देखा जा सकता है। यह प्राप्त करने के लिए विधियाँ प्रदान करता है
पृष्ठ संख्या, आकार, और अन्य गुण जैसी जानकारी।


उदाहरण उपयोग:

````

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List pages = viewInfo.getPages();
     for (Page page : pages) {
         // Use the page object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is PageImpl.*

## Methods

| Method | विवरण |
| --- | --- |
|  | [getName()](#getName--) | वर्कशीट या पृष्ठ का नाम प्राप्त करता है। |
|
|  | [setName(String name)](#setName-java.lang.String-) | वर्कशीट या पृष्ठ का नाम सेट करता है। |
|
|  | [getNumber()](#getNumber--) | पृष्ठ संख्या प्राप्त करता है। |
|
|  | [setNumber(int number)](#setNumber-int-) | पृष्ठ संख्या सेट करता है। |
|
|  | [isVisible()](#isVisible--) | पृष्ठ दृश्यता संकेतक प्राप्त करता है। |
|
|  | [setVisible(boolean visible)](#setVisible-boolean-) | पृष्ठ दृश्यता संकेतक सेट करता है। |
|
|  | [getWidth()](#getWidth--) | JPG या PNG के रूप में देखने पर पृष्ठ की चौड़ाई पिक्सेल में प्राप्त करता है। |
|
|  | [setWidth(int width)](#setWidth-int-) | JPG या PNG के रूप में देखने पर पृष्ठ की चौड़ाई पिक्सेल में सेट करता है। |
|
|  | [getHeight()](#getHeight--) | JPG या PNG के रूप में देखने पर पृष्ठ की ऊँचाई पिक्सेल में प्राप्त करता है। |
|
|  | [setHeight(int height)](#setHeight-int-) | JPG या PNG के रूप में देखने पर पृष्ठ की ऊँचाई पिक्सेल में सेट करता है। |
|
|  | [getLines()](#getLines--) | सक्रिय टेक्स्ट एक्सट्रैक्शन के साथ JPG या PNG के रूप में देखने पर पृष्ठ में मौजूद लाइनों को प्राप्त करता है। |
|
|  | [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | सक्रिय टेक्स्ट एक्सट्रैक्शन के साथ JPG या PNG के रूप में देखने पर पृष्ठ में मौजूद लाइनों को सेट करता है। |
|
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
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | वर्कशीट या पृष्ठ के लिए सेट किया जाने वाला नाम। |
|

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
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | number | int | सेट करने के लिए पृष्ठ संख्या। |
|

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
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | visible | boolean | यदि पृष्ठ दृश्यमान है तो true, अन्यथा false। |
|

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


JPG या PNG के रूप में देखने पर पृष्ठ की चौड़ाई पिक्सेल में प्राप्त करता है।


**Returns:**
int - पृष्ठ की चौड़ाई।

### setWidth(int width) {#setWidth-int-}
```
public abstract void setWidth(int width)
```


JPG या PNG के रूप में देखने पर पृष्ठ की चौड़ाई पिक्सेल में सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | width | int | पृष्ठ के लिए सेट की जाने वाली चौड़ाई। |
|

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


JPG या PNG के रूप में देखने पर पृष्ठ की ऊँचाई पिक्सेल में प्राप्त करता है।


**Returns:**
int - पृष्ठ की ऊँचाई।

### setHeight(int height) {#setHeight-int-}
```
public abstract void setHeight(int height)
```


JPG या PNG के रूप में देखने पर पृष्ठ की ऊँचाई पिक्सेल में सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | ऊँचाई | int | पृष्ठ के लिए सेट की जाने वाली ऊँचाई। |
|

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


सक्रिय टेक्स्ट एक्सट्रैक्शन के साथ JPG या PNG के रूप में देखने पर पृष्ठ में मौजूद लाइनों को प्राप्त करता है।


**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - पृष्ठ में मौजूद लाइनों।

### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


सक्रिय टेक्स्ट एक्सट्रैक्शन के साथ JPG या PNG के रूप में देखने पर पृष्ठ में मौजूद लाइनों को सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | रेखाएँ | java.util.List<com.groupdocs.viewer.results.Line> | पृष्ठ के लिए सेट की जाने वाली लाइनों की सूची। |
|

