---
title: "लेयर"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "एक CAD ड्राइंग में शामिल लेयर का प्रतिनिधित्व करता है।"
type: docs
weight: 16
url: /hi/nodejs-java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

एक CAD ड्राइंग में शामिल लेयर का प्रतिनिधित्व करता है।

Layer इंटरफ़ेस GroupDocs.Viewer घटक में CAD ड्राइंग के भीतर एक लेयर तक पहुँचने और उसे संशोधित करने के अनुबंध को परिभाषित करता है। यह लेयर नाम, दृश्यता, और अन्य गुणों जैसी जानकारी प्राप्त करने के लिए विधियाँ प्रदान करता है।

उदाहरण उपयोग:

```

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layers = viewInfo.getLayers();
     for (Layer layer : layers) {
         // Use the layer object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LayerImpl.*
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getName()](#getName--) | लेयर का नाम प्राप्त करता है। |
| [setName(String name)](#setName-java.lang.String-) | लेयर का नाम सेट करता है। |
| [isVisible()](#isVisible--) | लेयर की दृश्यता जाँचता है। |
| [setVisible(boolean isVisible)](#setVisible-boolean-) | लेयर की दृश्यता सेट करता है। |
| [equals(Object other)](#equals-java.lang.Object-) | जाँचता है कि यह ऑब्जेक्ट प्रदान किए गए ऑब्जेक्ट के बराबर है या नहीं। |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | लेयर के लिए नया नाम। |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


लेयर की दृश्यता जाँचता है।

जो CAD ड्राइंग लेयर बंद या फ्रीज़ की गई हैं, वे अदृश्य होती हैं। अदृश्य लेयरों को रेंडर करने के लिए, [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions\\#setLayers-List-) विकल्प का उपयोग करें।

**Returns:**
boolean - यदि लेयर दृश्यमान है तो true, अन्यथा false।
### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


लेयर की दृश्यता सेट करता है।

यदि true है, तो लेयर दृश्यमान होगी; यदि false है, तो वह छिपी होगी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | लेयर को दृश्यमान होना चाहिए या नहीं। |

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
