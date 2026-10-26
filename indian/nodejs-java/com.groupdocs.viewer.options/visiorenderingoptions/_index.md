---
title: "VisioRenderingOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "Visio दस्तावेज़ों को रेंडर करने के विकल्प शामिल हैं।"
type: docs
weight: 36
url: /hi/nodejs-java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Visio दस्तावेज़ों को रेंडर करने के विकल्प शामिल हैं।

VisioRenderingOptions क्लास GroupDocs.Viewer घटक में Visio फ़ाइलों को प्रोसेस और रेंडर करने के विकल्प प्रदान करती है। यह सेटिंग्स और पैरामीटर्स को समाहित करती है जिन्हें Visio दस्तावेज़ों के रेंडरिंग प्रोसेस और आउटपुट फ़ॉर्मेट को नियंत्रित करने के लिए उपयोग किया जा सकता है। विवरण के लिए, देखें [documentation][].

उदाहरण उपयोग:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [VisioRenderingOptions()](#VisioRenderingOptions--) | VisioRenderingOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [isRenderFiguresOnly()](#isRenderFiguresOnly--) | डायग्राम को छोड़कर केवल Visio फ़िगर्स को रेंडर करें। |
| [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | डायग्राम को छोड़कर केवल Visio फ़िगर्स को रेंडर करने के लिए फ़्लैग सेट करता है। |
| [getFigureWidth()](#getFigureWidth--) | फ़िगर की चौड़ाई प्राप्त करता है। |
| [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | फ़िगर की चौड़ाई सेट करता है। |
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


VisioRenderingOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


डायग्राम को छोड़कर केवल Visio फ़िगर्स को रेंडर करें।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Returns:**
boolean -  true  यदि केवल Visio आकृतियों को रेंडर किया जाना चाहिए,  false  अन्यथा.
### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


डायग्राम को छोड़कर केवल Visio फ़िगर्स को रेंडर करने के लिए फ़्लैग सेट करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| renderFiguresOnly | boolean | true  केवल Visio आकृतियों को रेंडर करने के लिए,  false  आरेख को शामिल करने के लिए. |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| figureWidth | int | आकृति की चौड़ाई। |

