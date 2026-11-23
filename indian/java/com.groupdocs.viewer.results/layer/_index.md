---
title: "लेयर"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "CAD ड्राइंग में शामिल एक लेयर का प्रतिनिधित्व करता है।"
type: docs
weight: 16
url: /hi/java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

CAD ड्राइंग में शामिल एक लेयर का प्रतिनिधित्व करता है।


लेयर इंटरफ़ेस CAD ड्रॉइंग के भीतर लेयर तक पहुँचने और उसे संशोधित करने के अनुबंध को परिभाषित करता है।
GroupDocs.Viewer घटक में। यह लेयर नाम जैसी जानकारी प्राप्त करने के लिए विधियाँ प्रदान करता है,
दृश्यता, और अन्य गुण।


उदाहरण उपयोग:

````

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layers = viewInfo.getLayers();
     for (Layer layer : layers) {
         // Use the layer object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LayerImpl.*

## Methods

| Method | विवरण |
| --- | --- |
|  | [getName()](#getName--) | लेयर का नाम प्राप्त करता है। |
|
|  | [setName(String name)](#setName-java.lang.String-) | लेयर का नाम सेट करता है। |
|
|  | [isVisible()](#isVisible--) | लेयर की दृश्यता जाँचता है। |
|
|  | [setVisible(boolean isVisible)](#setVisible-boolean-) | लेयर की दृश्यता सेट करता है। |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | जाँचता है कि यह ऑब्जेक्ट प्रदान किए गए ऑब्जेक्ट के बराबर है या नहीं। |
|
### getName() {#getName--}
```
public abstract String getName()
```


लेयर का नाम प्राप्त करता है।


**Note:** Layer names are case sensitive.


**Returns:**
java.lang.String - लेयर का नाम।

### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


लेयर का नाम सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | लेयर के लिए नया नाम। |
|

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


लेयर की दृश्यता जाँचता है।


CAD ड्राइंग लेयर्स जो बंद या फ्रीज़ किए गए हैं, अदृश्य होते हैं।
अदृश्य लेयर्स को रेंडर करने के लिए, [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions#setLayers-List-) विकल्प का उपयोग करें।


**Returns:**
boolean -  true  यदि लेयर दृश्यमान है,  false  अन्यथा।

### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


लेयर की दृश्यता सेट करता है।


यदि
true
, लेयर दृश्यमान होगा; यदि
false
, यह छिपा रहेगा।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | isVisible | boolean | लेयर को दृश्यमान होना चाहिए या नहीं। |
|

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


जाँचता है कि यह ऑब्जेक्ट प्रदान किए गए ऑब्जेक्ट के बराबर है या नहीं।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | अन्य | java.lang.Object | तुलना करने के लिए वस्तु। |
|

**Returns:**
boolean -  true  यदि वस्तुएँ समान हैं,  false  अन्यथा।

