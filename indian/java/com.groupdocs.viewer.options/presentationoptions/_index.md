---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "प्रेज़ेंटेशन को रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 26
url: /hi/java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

प्रेज़ेंटेशन को रेंडर करने के विकल्प प्रदान करता है।


विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/).

## Constructors

| Constructor | विवरण |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Methods

| Method | विवरण |
| --- | --- |
|  | [isRenderToPureHtml()](#isRenderToPureHtml--) | Presentation दस्तावेज़ों के लिए एक नया HTML रेंडरिंग मोड सक्षम करता है। |
|
|  | [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Presentation दस्तावेज़ों के लिए एक नया HTML रेंडरिंग मोड सक्षम करता है। |
|
|  | [isRenderHeaderFooterPlaceholders()](#isRenderHeaderFooterPlaceholders--) | स्लाइड के हेडर और फुटर में प्लेसहोल्डर रेंडरिंग को सक्षम करता है। |
|
|  | [setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)](#setRenderHeaderFooterPlaceholders-boolean-) | स्लाइड के हेडर और फुटर में प्लेसहोल्डर रेंडरिंग को सक्षम करता है। |
|
|  | [getResolution()](#getResolution--) | प्रेजेंटेशन के भीतर इमेजों के लिए रिज़ॉल्यूशन (केवल HTML/PDF रेंडरिंग के लिए)। |
|
|  | [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | प्रेजेंटेशन के भीतर इमेजों के लिए रिज़ॉल्यूशन (केवल HTML/PDF रेंडरिंग के लिए)। |
|
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Presentation दस्तावेज़ों के लिए एक नया HTML रेंडरिंग मोड सक्षम करता है।


इस मोड में, Presentation फ़ाइलें शुद्ध HTML/CSS मार्कअप में रेंडर की जाती हैं, बिना SVG इमेजों के।
डिफ़ॉल्ट रूप से, यह फीचर अक्षम है (false)। यदि यह विकल्प सक्षम नहीं है तो मौजूदा SVG-आधारित HTML रेंडरर उपयोग किया जाता है।


**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Presentation दस्तावेज़ों के लिए एक नया HTML रेंडरिंग मोड सक्षम करता है।


इस मोड में, Presentation फ़ाइलें शुद्ध HTML/CSS मार्कअप में रेंडर की जाती हैं, बिना SVG इमेजों के।
डिफ़ॉल्ट रूप से, यह फीचर अक्षम है (false)। यदि यह विकल्प सक्षम नहीं है तो मौजूदा SVG-आधारित HTML रेंडरर उपयोग किया जाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### isRenderHeaderFooterPlaceholders() {#isRenderHeaderFooterPlaceholders--}
```
public boolean isRenderHeaderFooterPlaceholders()
```


स्लाइड के हेडर और फुटर में प्लेसहोल्डर रेंडरिंग को सक्षम करता है। डिफ़ॉल्ट रूप से अक्षम (false)। यह विकल्प प्रस्तुतियों के सभी 4 रेंडरिंग मोड्स पर लागू होता है: HTML, PDF, PNG, और JPEG। शुद्ध HTML/CSS मार्कअप में प्रस्तुति रेंडर करने पर लागू नहीं होता।


**Returns:**
boolean
### setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders) {#setRenderHeaderFooterPlaceholders-boolean-}
```
public void setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)
```


स्लाइड के हेडर और फुटर में प्लेसहोल्डर रेंडरिंग को सक्षम करता है। डिफ़ॉल्ट रूप से अक्षम (false)। यह विकल्प प्रस्तुतियों के सभी 4 रेंडरिंग मोड्स पर लागू होता है: HTML, PDF, PNG, और JPEG। शुद्ध HTML/CSS मार्कअप में प्रस्तुति रेंडर करने पर लागू नहीं होता।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| renderHeaderFooterPlaceholders | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


प्रेजेंटेशन के भीतर इमेजों के लिए रिज़ॉल्यूशन (केवल HTML/PDF रेंडरिंग के लिए)।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution)।


**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


प्रेजेंटेशन के भीतर इमेजों के लिए रिज़ॉल्यूशन (केवल HTML/PDF रेंडरिंग के लिए)।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

