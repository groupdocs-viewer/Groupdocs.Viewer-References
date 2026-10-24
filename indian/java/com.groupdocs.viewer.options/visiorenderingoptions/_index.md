---
title: "VisioRenderingOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "Visio दस्तावेज़ों को रेंडर करने के विकल्प शामिल हैं।"
type: docs
weight: 36
url: /hi/java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Visio दस्तावेज़ों को रेंडर करने के विकल्प शामिल हैं।


VisioRenderingOptions क्लास Visio फ़ाइलों को प्रोसेस और रेंडर करने के विकल्प प्रदान करती है
GroupDocs.Viewer कंपोनेंट में। यह सेटिंग्स और पैरामीटर को समाहित करती है जिन्हें उपयोग किया जा सकता है
Visio दस्तावेज़ों के रेंडरिंग प्रक्रिया और आउटपुट फ़ॉर्मेट को नियंत्रित करने के लिए।
विस्तार के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-visio-documents/)।


उदाहरण उपयोग:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [VisioRenderingOptions()](#VisioRenderingOptions--) | नए उदाहरण को प्रारंभ करता है |
VisioRenderingOptions
class।
|
## Methods

| Method | विवरण |
| --- | --- |
|  | [isRenderFiguresOnly()](#isRenderFiguresOnly--) | केवल Visio आकृतियों को रेंडर करें, डायग्राम को छोड़कर। |
|
|  | [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | फ़्लैग सेट करता है ताकि केवल Visio आकृतियों को रेंडर किया जाए, डायग्राम को छोड़कर। |
|
|  | [getFigureWidth()](#getFigureWidth--) | आकृति की चौड़ाई प्राप्त करता है। |
|
|  | [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | आकृति की चौड़ाई सेट करता है। |
|
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


नए उदाहरण को प्रारंभ करता है
VisioRenderingOptions
class।


### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


केवल Visio आकृतियों को रेंडर करें, डायग्राम को छोड़कर।
विस्तार के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes)।


**Returns:**
boolean -  true  यदि केवल Visio आकृतियों को रेंडर किया जाना चाहिए,  false  अन्यथा।

### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


फ़्लैग सेट करता है ताकि केवल Visio आकृतियों को रेंडर किया जाए, डायग्राम को छोड़कर।
विस्तार के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | renderFiguresOnly | boolean | true  केवल Visio आकृतियों को रेंडर करने के लिए,  false  डायग्राम को शामिल करने के लिए। |
|

### getFigureWidth() {#getFigureWidth--}
```
public int getFigureWidth()
```


आकृति की चौड़ाई प्राप्त करता है। ऊँचाई स्वचालित रूप से गणना की जाएगी।


**Returns:**
int - आकृति की चौड़ाई।

### setFigureWidth(int figureWidth) {#setFigureWidth-int-}
```
public void setFigureWidth(int figureWidth)
```


आकृति की चौड़ाई सेट करता है। ऊँचाई स्वचालित रूप से गणना की जाएगी।


***Note:** Default value is 100.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | figureWidth | int | आकृति की चौड़ाई। |
|

