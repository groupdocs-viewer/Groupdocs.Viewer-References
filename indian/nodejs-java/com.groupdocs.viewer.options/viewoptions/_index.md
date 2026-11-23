---
title: "ViewOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "रेंडरिंग विकल्प शामिल हैं।"
type: docs
weight: 35
url: /hi/nodejs-java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

रेंडरिंग विकल्प शामिल हैं।

ViewOptions वर्ग BaseViewOptions वर्ग का विस्तार करता है और GroupDocs.Viewer घटक में रेंडरिंग विकल्पों के लिए एक बेस वर्ग के रूप में कार्य करता है। यह विभिन्न प्रकार के दस्तावेज़ों को विभिन्न स्वरूपों में रेंडर करने के लिए उपयोग किए जा सकने वाले सामान्य सेटिंग्स और पैरामीटरों को सम्मिलित करता है।

***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getWatermark()](#getWatermark--) | प्रत्येक पृष्ठ पर लागू पाठ वॉटरमार्क प्राप्त करता है। |
| [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | प्रत्येक पृष्ठ पर लागू होने वाले पाठ वॉटरमार्क को सेट करता है। |
| [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | निर्दिष्ट पृष्ठ पर घड़ी की दिशा में घुमाव लागू करता है। |
| [getPageRotations()](#getPageRotations--) | पृष्ठ घुमावों को प्राप्त करता है। |
| [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | इंस्टेंस को केवल यह जांचने के लिए बनाने से बचाने हेतु कि वह खाली है |
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


प्रत्येक पृष्ठ पर लागू पाठ वॉटरमार्क प्राप्त करता है।

यदि दोनों \\#setWatermark(Watermark).setWatermark(Watermark) और \\#getPageRotations().getPageRotations() निर्दिष्ट किए गए हों, तो वॉटरमार्क घुमाए गए पृष्ठों पर लागू किया जाएगा। विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.
### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


प्रत्येक पृष्ठ पर लागू होने वाले पाठ वॉटरमार्क को सेट करता है।

यदि दोनों  ViewOptions.Watermark  और \\#getPageRotations().getPageRotations() निर्दिष्ट किए गए हों, तो वॉटरमार्क घुमाए गए पृष्ठों पर लागू किया जाएगा। विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Watermark](../../com.groupdocs.viewer.options/watermark) | सेट करने के लिए पाठ वॉटरमार्क। |

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


निर्दिष्ट पृष्ठ पर घड़ी की दिशा में घुमाव लागू करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageNumber | int | पृष्ठ संख्या, 0 से सख्ती से अधिक होनी चाहिए। |
| rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | घुमाव मान। |

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


पृष्ठ घुमावों को प्राप्त करता है।

यदि दोनों [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions\#setWatermark-Watermark-) और getPageRotations() निर्दिष्ट किए गए हैं, तो वॉटरमार्क घुमाए गए पृष्ठों पर लागू किया जाएगा। विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> - एक मानचित्र जिसमें पृष्ठ संख्याएँ कुंजी के रूप में और उनके संबंधित घुमाव मान मानों के रूप में होते हैं।
### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


इंस्टेंस को केवल यह जांचने के लिए बनाने से बचाने हेतु कि वह खाली है

**Returns:**
boolean
