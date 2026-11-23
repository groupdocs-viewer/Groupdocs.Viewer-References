---
title: "Layout"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "एक CAD ड्राइंग में शामिल लेआउट का प्रतिनिधित्व करता है।"
type: docs
weight: 17
url: /hi/nodejs-java/com.groupdocs.viewer.results/layout/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layout extends Serializable
```

एक CAD ड्राइंग में शामिल लेआउट का प्रतिनिधित्व करता है।

Layout इंटरफ़ेस GroupDocs.Viewer घटक में CAD ड्राइंग के भीतर लेआउट तक पहुँचने और उसे संशोधित करने के अनुबंध को परिभाषित करता है। यह लेआउट नाम, आयाम, और अन्य गुणों जैसी जानकारी प्राप्त करने के लिए मेथड प्रदान करता है।

उदाहरण उपयोग:

```

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layouts = viewInfo.getLayouts();
     for (Layout layout : layouts) {
         // Use the layout object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LayoutImpl.*
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getName()](#getName--) | लेआउट का नाम प्राप्त करता है। |
| [setName(String name)](#setName-java.lang.String-) | लेआउट का नाम सेट करता है। |
| [getWidth()](#getWidth--) | लेआउट की चौड़ाई प्राप्त करता है। |
| [setWidth(double width)](#setWidth-double-) | लेआउट की चौड़ाई सेट करता है। |
| [getHeight()](#getHeight--) | लेआउट की ऊँचाई प्राप्त करता है। |
| [setHeight(double height)](#setHeight-double-) | लेआउट की ऊँचाई सेट करता है। |
| [equals(Object other)](#equals-java.lang.Object-) | जाँचता है कि यह ऑब्जेक्ट प्रदान किए गए ऑब्जेक्ट के बराबर है या नहीं। |
### getName() {#getName--}
```
public abstract String getName()
```


लेआउट का नाम प्राप्त करता है।

**Returns:**
java.lang.String - लेआउट का नाम।
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


लेआउट का नाम सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | लेआउट के लिए सेट किया जाने वाला नाम। |

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


लेआउट की चौड़ाई प्राप्त करता है।

**Returns:**
double - लेआउट की चौड़ाई।
### setWidth(double width) {#setWidth-double-}
```
public abstract void setWidth(double width)
```


लेआउट की चौड़ाई सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | double | लेआउट के लिए सेट की जाने वाली चौड़ाई। |

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


लेआउट की ऊँचाई प्राप्त करता है।

**Returns:**
double - लेआउट की ऊँचाई।
### setHeight(double height) {#setHeight-double-}
```
public abstract void setHeight(double height)
```


लेआउट की ऊँचाई सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| height | double | लेआउट के लिए सेट की जाने वाली ऊँचाई। |

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


जाँचता है कि यह ऑब्जेक्ट प्रदान किए गए ऑब्जेक्ट के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| अन्य | java.lang.Object | तुलना करने के लिए ऑब्जेक्ट। |

**Returns:**
boolean -  true  यदि वस्तुएँ समान हैं,  false  अन्यथा।
