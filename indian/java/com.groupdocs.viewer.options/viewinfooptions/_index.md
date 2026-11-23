---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "व्यू के बारे में जानकारी प्राप्त करने के लिए उपयोग किए जाने वाले विकल्प प्रदान करता है।"
type: docs
weight: 34
url: /hi/java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

व्यू के बारे में जानकारी प्राप्त करने के लिए उपयोग किए जाने वाले विकल्प प्रदान करता है।


ViewInfoOptions क्लास अतिरिक्त सेटिंग्स और पैरामीटर को संलग्न करती है जो
GroupDocs.Viewer घटक में एक व्यू के बारे में जानकारी प्राप्त करने के लिए उपयोग की जा सकती है।


उदाहरण उपयोग:

````

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*

## Methods

| Method | विवरण |
| --- | --- |
|  | [isExtractText()](#isExtractText--) | यह दर्शाता है कि टेक्स्ट एक्सट्रैक्शन सक्षम है या नहीं। |
|
|  | [setExtractText(boolean extractText)](#setExtractText-boolean-) | टेक्स्ट निष्कर्षण सक्षम है या नहीं यह दर्शाने वाला फ़्लैग सेट करता है। |
|
|  | [getMaxWidth()](#getMaxWidth--) | PNG/JPG में रेंडर करने के लिए आउटपुट छवि की अधिकतम चौड़ाई लौटाता है। |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | आउटपुट छवि की अधिकतम चौड़ाई सेट करता है (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)। |
|
|  | [getMaxHeight()](#getMaxHeight--) | PNG/JPG में रेंडर करने के लिए आउटपुट छवि की अधिकतम ऊँचाई लौटाता है। |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | आउटपुट छवि की अधिकतम ऊँचाई सेट करता है (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)। |
|
|  | [getWidth()](#getWidth--) | आउटपुट छवि की चौड़ाई (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)। |
|
|  | [setWidth(int width)](#setWidth-int-) | आउटपुट छवि की चौड़ाई (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)। |
|
|  | [getHeight()](#getHeight--) | आउटपुट छवि की ऊँचाई (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)। |
|
|  | [setHeight(int height)](#setHeight-int-) | आउटपुट छवि की ऊँचाई (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)। |
|
|  | [forHtmlView()](#forHtmlView--) | नए उदाहरण को प्रारंभ करता है |
ViewInfoOptions
HTML में रेंडर करने पर दृश्य की जानकारी प्राप्त करने के लिए क्लास।
|
|  | [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | नए उदाहरण को प्रारंभ करता है |
ViewInfoOptions
HTML में रेंडर करने पर दृश्य की जानकारी प्राप्त करने के लिए क्लास।
|
|  | [forJpgView()](#forJpgView--) | नए उदाहरण को प्रारंभ करता है |
ViewInfoOptions
JPG में रेंडर करने पर दृश्य की जानकारी प्राप्त करने के लिए क्लास।
|
|  | [forJpgView(boolean extractText)](#forJpgView-boolean-) | नए उदाहरण को प्रारंभ करता है |
ViewInfoOptions
JPG में रेंडर करने पर दृश्य की जानकारी प्राप्त करने के लिए क्लास।
|
|  | [forPngView()](#forPngView--) | नए उदाहरण को प्रारंभ करता है |
ViewInfoOptions
PNG में रेंडर करने पर दृश्य की जानकारी प्राप्त करने के लिए क्लास।
|
|  | [forPngView(boolean extractText)](#forPngView-boolean-) | नए उदाहरण को प्रारंभ करता है |
ViewInfoOptions
PNG में रेंडर करने पर दृश्य की जानकारी प्राप्त करने के लिए क्लास।
|
|  | [forPdfView()](#forPdfView--) | PDF में रेंडर करने पर दृश्य की जानकारी प्राप्त करने के लिए ViewInfoOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | नए उदाहरण को प्रारंभ करता है |
ViewInfoOptions
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) ऑब्जेक्ट पर आधारित क्लास।
|
|  | [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | नए उदाहरण को प्रारंभ करता है |
ViewInfoOptions
[PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) ऑब्जेक्ट पर आधारित क्लास।
|
|  | [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | नए उदाहरण को प्रारंभ करता है |
ViewInfoOptions
[JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) ऑब्जेक्ट पर आधारित क्लास।
|
|  | [fromPdfViewOptions(PdfViewOptions options)](#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-) | PdfViewOptions ऑब्जेक्ट पर आधारित [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


यह दर्शाता है कि टेक्स्ट एक्सट्रैक्शन सक्षम है या नहीं।
इस प्रॉपर्टी का उपयोग स्रोत दस्तावेज़ में मौजूद टेक्स्ट और उसके निर्देशांक प्राप्त करने के लिए करें। फिर आप इस डेटा का उपयोग छवि के ऊपर चयन योग्य टेक्स्ट जोड़ने या इमेज-आधारित रेंडरिंग में टेक्स्ट खोज लागू करने के लिए कर सकते हैं। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/)।


**Returns:**
बूलियन - यदि टेक्स्ट निष्कर्षण सक्षम है तो True, अन्यथा False।

### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


टेक्स्ट निष्कर्षण सक्षम है या नहीं यह दर्शाने वाला फ़्लैग सेट करता है।
इस प्रॉपर्टी का उपयोग स्रोत दस्तावेज़ में मौजूद टेक्स्ट और उसके निर्देशांक प्राप्त करने के लिए करें। फिर आप इस डेटा का उपयोग छवि के ऊपर चयन योग्य टेक्स्ट जोड़ने या इमेज-आधारित रेंडरिंग में टेक्स्ट खोज लागू करने के लिए कर सकते हैं। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | extractText | boolean | टेक्स्ट निष्कर्षण सक्षम करने के लिए True, अक्षम करने के लिए false। |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


PNG/JPG में रेंडर करने के लिए आउटपुट छवि की अधिकतम चौड़ाई लौटाता है।
इस प्रॉपर्टी का उपयोग अधिकतम आउटपुट छवि की चौड़ाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/)। यदि आप इस प्रॉपर्टी को सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाती है।


**Returns:**
int - आउटपुट इमेज की अधिकतम चौड़ाई।

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


आउटपुट छवि की अधिकतम चौड़ाई सेट करता है (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)।
इस प्रॉपर्टी का उपयोग अधिकतम आउटपुट छवि की चौड़ाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/)। यदि आप इस प्रॉपर्टी को सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाती है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | maxWidth | int | आउटपुट इमेज की अधिकतम चौड़ाई। |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


PNG/JPG में रेंडर करने के लिए आउटपुट छवि की अधिकतम ऊँचाई लौटाता है।
इस प्रॉपर्टी का उपयोग अधिकतम आउटपुट छवि की ऊँचाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/)। यदि आप इस प्रॉपर्टी को सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाती है।


**Returns:**
int - आउटपुट इमेज की अधिकतम ऊँचाई।

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


आउटपुट छवि की अधिकतम ऊँचाई सेट करता है (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)।
इस प्रॉपर्टी का उपयोग अधिकतम आउटपुट छवि की ऊँचाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/)। यदि आप इस प्रॉपर्टी को सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाती है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | maxHeight | int | आउटपुट इमेज की अधिकतम ऊँचाई। |
|

### getWidth() {#getWidth--}
```
public int getWidth()
```


आउटपुट छवि की चौड़ाई (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)।
इस प्रॉपर्टी का उपयोग आउटपुट छवि की चौड़ाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/)। यदि आप इस प्रॉपर्टी को सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाती है।


**Returns:**
int - छवि की चौड़ाई।

### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


आउटपुट छवि की चौड़ाई (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)।
इस प्रॉपर्टी का उपयोग आउटपुट छवि की चौड़ाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/)। यदि आप इस प्रॉपर्टी को सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाती है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | width | int | छवि की चौड़ाई। |
|

### getHeight() {#getHeight--}
```
public int getHeight()
```


आउटपुट छवि की ऊँचाई (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)।
इस प्रॉपर्टी का उपयोग आउटपुट इमेज की ऊँचाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/)। यदि आप इस प्रॉपर्टी को सेट करते हैं, तो यह प्रॉपर्टी अनदेखी कर दी जाएगी।


**Returns:**
int - इमेज की ऊँचाई।

### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


आउटपुट छवि की ऊँचाई (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)।
इस प्रॉपर्टी का उपयोग आउटपुट इमेज की ऊँचाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/)। यदि आप इस प्रॉपर्टी को सेट करते हैं, तो यह प्रॉपर्टी अनदेखी कर दी जाएगी।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | ऊँचाई | int | इमेज की ऊँचाई। |
|

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


नए उदाहरण को प्रारंभ करता है
ViewInfoOptions
HTML में रेंडर करने पर दृश्य की जानकारी प्राप्त करने के लिए क्लास।


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.

### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


नए उदाहरण को प्रारंभ करता है
ViewInfoOptions
HTML में रेंडर करने पर दृश्य की जानकारी प्राप्त करने के लिए क्लास।


***Note:** By default, HTML content will be rendered on multiple pages.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | renderSinglePage | boolean | HTML सामग्री को एक ही पृष्ठ पर रेंडर करने में सक्षम बनाता है। |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


नए उदाहरण को प्रारंभ करता है
ViewInfoOptions
JPG में रेंडर करने पर दृश्य की जानकारी प्राप्त करने के लिए क्लास।


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


नए उदाहरण को प्रारंभ करता है
ViewInfoOptions
JPG में रेंडर करने पर दृश्य की जानकारी प्राप्त करने के लिए क्लास।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | extractText | boolean | टेक्स्ट निष्कर्षण को सक्षम करता है। |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


नए उदाहरण को प्रारंभ करता है
ViewInfoOptions
PNG में रेंडर करने पर दृश्य की जानकारी प्राप्त करने के लिए क्लास।


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


नए उदाहरण को प्रारंभ करता है
ViewInfoOptions
PNG में रेंडर करने पर दृश्य की जानकारी प्राप्त करने के लिए क्लास।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | extractText | boolean | टेक्स्ट निष्कर्षण को सक्षम करता है। |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPdfView() {#forPdfView--}
```
public static ViewInfoOptions forPdfView()
```


PDF में रेंडर करने पर दृश्य की जानकारी प्राप्त करने के लिए ViewInfoOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.

### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


नए उदाहरण को प्रारंभ करता है
ViewInfoOptions
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) ऑब्जेक्ट पर आधारित क्लास।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | HTML व्यू विकल्प। |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


नए उदाहरण को प्रारंभ करता है
ViewInfoOptions
[PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) ऑब्जेक्ट पर आधारित क्लास।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | PNG व्यू विकल्प। |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


नए उदाहरण को प्रारंभ करता है
ViewInfoOptions
[JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) ऑब्जेक्ट पर आधारित क्लास।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | JPG व्यू विकल्प। |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPdfViewOptions(PdfViewOptions options) {#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-}
```
public static ViewInfoOptions fromPdfViewOptions(PdfViewOptions options)
```


PdfViewOptions ऑब्जेक्ट पर आधारित [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | options | [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) | PDF व्यू विकल्प। |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the ViewInfoOptions class.

