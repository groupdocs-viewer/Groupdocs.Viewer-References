---
title: "CadViewInfo"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "एक CAD ड्राइंग के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।"
type: docs
weight: 13
url: /hi/nodejs-java/com.groupdocs.viewer.results/cadviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface CadViewInfo extends ViewInfo
```

एक CAD ड्राइंग के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।

CadViewInfo इंटरफ़ेस GroupDocs.Viewer घटक में CAD ड्राइंग के लिए विशिष्ट दृश्य जानकारी प्राप्त करने के अनुबंध को परिभाषित करता है। यह CAD ड्रॉइंग की लेयर्स तक पहुँचने के लिए विधियाँ प्रदान करता है।

उदाहरण उपयोग:

```

 try (Viewer viewer = new Viewer("document.plt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is CadViewInfoImpl.*
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getLayers()](#getLayers--) | CAD ड्राइंग में लेयर्स की सूची प्राप्त करता है। |
| [setLayers(List<Layer> layers)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | CAD ड्राइंग में लेयर्स की सूची सेट करता है। |
| [getLayouts()](#getLayouts--) | CAD ड्राइंग में शामिल लेआउट्स की सूची प्राप्त करता है। |
| [setLayouts(List<Layout> layouts)](#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--) | CAD ड्राइंग में शामिल लेआउट्स की सूची सेट करता है। |
### getLayers() {#getLayers--}
```
public abstract List<Layer> getLayers()
```


CAD ड्राइंग में लेयर्स की सूची प्राप्त करता है।

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - CAD ड्राइंग में लेयर्स।
### setLayers(List<Layer> layers) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public abstract void setLayers(List<Layer> layers)
```


CAD ड्राइंग में लेयर्स की सूची सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| परतें | java.util.List<com.groupdocs.viewer.results.Layer> | CAD ड्राइंग के लिए सेट करने वाली लेयर्स। |

### getLayouts() {#getLayouts--}
```
public abstract List<Layout> getLayouts()
```


CAD ड्राइंग में शामिल लेआउट्स की सूची प्राप्त करता है।

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layout> - CAD ड्राइंग में लेआउट्स।
### setLayouts(List<Layout> layouts) {#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--}
```
public abstract void setLayouts(List<Layout> layouts)
```


CAD ड्राइंग में शामिल लेआउट्स की सूची सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| लेआउट्स | java.util.List<com.groupdocs.viewer.results.Layout> | CAD ड्राइंग के लिए सेट करने वाले लेआउट्स। |

