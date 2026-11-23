---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "व्यू के बारे में जानकारी प्राप्त करने के लिए उपयोग किए जाने वाले विकल्प प्रदान करता है।"
type: docs
weight: 34
url: /hi/nodejs-java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

व्यू के बारे में जानकारी प्राप्त करने के लिए उपयोग किए जाने वाले विकल्प प्रदान करता है।

ViewInfoOptions क्लास अतिरिक्त सेटिंग्स और पैरामीटर को समाहित करती है जिन्हें GroupDocs.Viewer घटक में एक व्यू के बारे में जानकारी प्राप्त करने के लिए उपयोग किया जा सकता है।

उदाहरण उपयोग:

```

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [isExtractText()](#isExtractText--) | बताता है कि टेक्स्ट एक्सट्रैक्शन सक्षम है या नहीं। |
| [setExtractText(boolean extractText)](#setExtractText-boolean-) | फ़्लैग सेट करता है जो बताता है कि टेक्स्ट एक्सट्रैक्शन सक्षम है या नहीं। |
| [getMaxWidth()](#getMaxWidth--) | PNG/JPG में रेंडर करने के लिए आउटपुट इमेज की अधिकतम चौड़ाई लौटाता है। |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | आउटपुट इमेज की अधिकतम चौड़ाई सेट करता है (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)। |
| [getMaxHeight()](#getMaxHeight--) | PNG/JPG में रेंडर करने के लिए आउटपुट इमेज की अधिकतम ऊँचाई लौटाता है। |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | आउटपुट इमेज की अधिकतम ऊँचाई सेट करता है (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)। |
| [getWidth()](#getWidth--) | आउटपुट इमेज की चौड़ाई (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)। |
| [setWidth(int width)](#setWidth-int-) | आउटपुट इमेज की चौड़ाई (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)। |
| [getHeight()](#getHeight--) | आउटपुट इमेज की ऊँचाई (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)। |
| [setHeight(int height)](#setHeight-int-) | आउटपुट इमेज की ऊँचाई (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)। |
| [forHtmlView()](#forHtmlView--) | HTML में रेंडर करते समय व्यू के बारे में जानकारी प्राप्त करने के लिए ViewInfoOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | HTML में रेंडर करते समय व्यू के बारे में जानकारी प्राप्त करने के लिए ViewInfoOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [forJpgView()](#forJpgView--) | JPG में रेंडर करते समय व्यू के बारे में जानकारी प्राप्त करने के लिए ViewInfoOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [forJpgView(boolean extractText)](#forJpgView-boolean-) | JPG में रेंडर करते समय व्यू के बारे में जानकारी प्राप्त करने के लिए ViewInfoOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [forPngView()](#forPngView--) | PNG में रेंडर करते समय व्यू के बारे में जानकारी प्राप्त करने के लिए ViewInfoOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [forPngView(boolean extractText)](#forPngView-boolean-) | PNG में रेंडर करते समय व्यू के बारे में जानकारी प्राप्त करने के लिए ViewInfoOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [forPdfView()](#forPdfView--) | PDF में रेंडरिंग करते समय दृश्य के बारे में जानकारी प्राप्त करने के लिए ViewInfoOptions क्लास का नया उदाहरण प्रारंभ करता है। |
| [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) ऑब्जेक्ट के आधार पर ViewInfoOptions क्लास का नया उदाहरण प्रारंभ करता है। |
| [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) ऑब्जेक्ट के आधार पर ViewInfoOptions क्लास का नया उदाहरण प्रारंभ करता है। |
| [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) ऑब्जेक्ट के आधार पर ViewInfoOptions क्लास का नया उदाहरण प्रारंभ करता है। |
| [fromPdfViewOptions(PdfViewOptions options)](#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-) | PdfViewOptions ऑब्जेक्ट के आधार पर [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) क्लास का नया उदाहरण प्रारंभ करता है। |
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


बताता है कि टेक्स्ट एक्सट्रैक्शन सक्षम है या नहीं।

इस प्रॉपर्टी का उपयोग स्रोत दस्तावेज़ में मौजूद टेक्स्ट और उसके निर्देशांक प्राप्त करने के लिए करें। फिर आप इस डेटा का उपयोग छवि पर चयन योग्य टेक्स्ट जोड़ने या इमेज-आधारित रेंडरिंग में टेक्स्ट खोज लागू करने के लिए कर सकते हैं। कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/

**Returns:**
boolean - यदि टेक्स्ट निष्कर्षण सक्षम है तो True, अन्यथा false।
### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


फ़्लैग सेट करता है जो बताता है कि टेक्स्ट एक्सट्रैक्शन सक्षम है या नहीं।

इस प्रॉपर्टी का उपयोग स्रोत दस्तावेज़ में मौजूद टेक्स्ट और उसके निर्देशांक प्राप्त करने के लिए करें। फिर आप इस डेटा का उपयोग छवि पर चयन योग्य टेक्स्ट जोड़ने या इमेज-आधारित रेंडरिंग में टेक्स्ट खोज लागू करने के लिए कर सकते हैं। कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| extractText | boolean | टेक्स्ट निष्कर्षण सक्षम करने के लिए True, अक्षम करने के लिए false। |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


PNG/JPG में रेंडर करने के लिए आउटपुट इमेज की अधिकतम चौड़ाई लौटाता है।

इस प्रॉपर्टी का उपयोग अधिकतम आउटपुट इमेज चौड़ाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप  प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाएगी।


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - आउटपुट इमेज की अधिकतम चौड़ाई।
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


आउटपुट इमेज की अधिकतम चौड़ाई सेट करता है (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)।

इस प्रॉपर्टी का उपयोग अधिकतम आउटपुट इमेज चौड़ाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप  प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाएगी।


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| maxWidth | int | आउटपुट इमेज की अधिकतम चौड़ाई। |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


PNG/JPG में रेंडर करने के लिए आउटपुट इमेज की अधिकतम ऊँचाई लौटाता है।

इस प्रॉपर्टी का उपयोग अधिकतम आउटपुट इमेज ऊँचाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप  प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाएगी।


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - आउटपुट इमेज की अधिकतम ऊँचाई।
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


आउटपुट इमेज की अधिकतम ऊँचाई सेट करता है (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)।

इस प्रॉपर्टी का उपयोग अधिकतम आउटपुट इमेज ऊँचाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप  प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाएगी।


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| maxHeight | int | आउटपुट इमेज की अधिकतम ऊँचाई। |

### getWidth() {#getWidth--}
```
public int getWidth()
```


आउटपुट इमेज की चौड़ाई (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)।

इस प्रॉपर्टी का उपयोग आउटपुट इमेज की चौड़ाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप इस प्रॉपर्टी को सेट करते हैं, तो  प्रॉपर्टी अनदेखी की जाएगी।


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Returns:**
int - छवि की चौड़ाई।
### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


आउटपुट इमेज की चौड़ाई (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)।

इस प्रॉपर्टी का उपयोग आउटपुट इमेज की चौड़ाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप इस प्रॉपर्टी को सेट करते हैं, तो  प्रॉपर्टी अनदेखी की जाएगी।


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | int | छवि की चौड़ाई। |

### getHeight() {#getHeight--}
```
public int getHeight()
```


आउटपुट इमेज की ऊँचाई (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)।

इस प्रॉपर्टी का उपयोग आउटपुट इमेज की ऊँचाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप इस प्रॉपर्टी को सेट करते हैं, तो  प्रॉपर्टी अनदेखी की जाएगी।


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Returns:**
int - छवि की ऊँचाई।
### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


आउटपुट इमेज की ऊँचाई (पिक्सेल में, केवल PNG/JPG में रेंडर करने के लिए)।

इस प्रॉपर्टी का उपयोग आउटपुट इमेज की ऊँचाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप इस प्रॉपर्टी को सेट करते हैं, तो  प्रॉपर्टी अनदेखी की जाएगी।


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| height | int | छवि की ऊँचाई। |

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


HTML में रेंडर करते समय व्यू के बारे में जानकारी प्राप्त करने के लिए ViewInfoOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.
### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


HTML में रेंडर करते समय व्यू के बारे में जानकारी प्राप्त करने के लिए ViewInfoOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

***Note:** By default, HTML content will be rendered on multiple pages.*

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| renderSinglePage | boolean | HTML सामग्री को एक पृष्ठ पर रेंडर करने में सक्षम बनाता है। |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


JPG में रेंडर करते समय व्यू के बारे में जानकारी प्राप्त करने के लिए ViewInfoOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


JPG में रेंडर करते समय व्यू के बारे में जानकारी प्राप्त करने के लिए ViewInfoOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| extractText | boolean | टेक्स्ट निष्कर्षण को सक्षम करता है। |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


PNG में रेंडर करते समय व्यू के बारे में जानकारी प्राप्त करने के लिए ViewInfoOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


PNG में रेंडर करते समय व्यू के बारे में जानकारी प्राप्त करने के लिए ViewInfoOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| extractText | boolean | टेक्स्ट निष्कर्षण को सक्षम करता है। |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPdfView() {#forPdfView--}
```
public static ViewInfoOptions forPdfView()
```


PDF में रेंडरिंग करते समय दृश्य के बारे में जानकारी प्राप्त करने के लिए ViewInfoOptions क्लास का नया उदाहरण प्रारंभ करता है।

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.
### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) ऑब्जेक्ट के आधार पर ViewInfoOptions क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | HTML व्यू विकल्प। |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


[PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) ऑब्जेक्ट के आधार पर ViewInfoOptions क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | PNG व्यू विकल्प। |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


[JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) ऑब्जेक्ट के आधार पर ViewInfoOptions क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | JPG व्यू विकल्प। |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromPdfViewOptions(PdfViewOptions options) {#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-}
```
public static ViewInfoOptions fromPdfViewOptions(PdfViewOptions options)
```


PdfViewOptions ऑब्जेक्ट के आधार पर [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) | PDF व्यू विकल्प। |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the ViewInfoOptions class.
