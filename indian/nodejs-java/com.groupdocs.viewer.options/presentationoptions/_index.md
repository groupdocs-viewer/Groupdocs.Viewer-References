---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "प्रेज़ेंटेशन को रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 26
url: /hi/nodejs-java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

प्रेज़ेंटेशन को रेंडर करने के विकल्प प्रदान करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [isRenderToPureHtml()](#isRenderToPureHtml--) | Presentation दस्तावेज़ों के लिए नया HTML रेंडरिंग मोड सक्षम करता है। |
| [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Presentation दस्तावेज़ों के लिए नया HTML रेंडरिंग मोड सक्षम करता है। |
| [getResolution()](#getResolution--) | प्रेजेंटेशन के भीतर छवियों के लिए रिज़ॉल्यूशन (केवल HTML/PDF रेंडरिंग के लिए)। |
| [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | प्रेजेंटेशन के भीतर छवियों के लिए रिज़ॉल्यूशन (केवल HTML/PDF रेंडरिंग के लिए)। |
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Presentation दस्तावेज़ों के लिए नया HTML रेंडरिंग मोड सक्षम करता है।

इस मोड में, Presentation फ़ाइलें शुद्ध HTML/CSS मार्कअप में रेंडर की जाती हैं, बिना SVG छवियों के। डिफ़ॉल्ट रूप से, यह सुविधा अक्षम (false) है। यदि यह विकल्प सक्षम नहीं है तो मौजूदा SVG-आधारित HTML रेंडरर का उपयोग किया जाता है।

**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Presentation दस्तावेज़ों के लिए नया HTML रेंडरिंग मोड सक्षम करता है।

इस मोड में, Presentation फ़ाइलें शुद्ध HTML/CSS मार्कअप में रेंडर की जाती हैं, बिना SVG छवियों के। डिफ़ॉल्ट रूप से, यह सुविधा अक्षम (false) है। यदि यह विकल्प सक्षम नहीं है तो मौजूदा SVG-आधारित HTML रेंडरर का उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


प्रेजेंटेशन के भीतर छवियों के लिए रिज़ॉल्यूशन (केवल HTML/PDF रेंडरिंग के लिए)।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


प्रेजेंटेशन के भीतर छवियों के लिए रिज़ॉल्यूशन (केवल HTML/PDF रेंडरिंग के लिए)।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

