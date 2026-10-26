---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "दस्तावेज़ों को PNG फ़ॉर्मेट में रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 25
url: /hi/nodejs-java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

दस्तावेज़ों को PNG फ़ॉर्मेट में रेंडर करने के विकल्प प्रदान करता है।

PngViewOptions क्लास अतिरिक्त सेटिंग्स और पैरामीटर को संलग्न करती है जिन्हें GroupDocs.Viewer घटक में दस्तावेज़ों को PNG फ़ॉर्मेट में रेंडर करने को नियंत्रित करने के लिए उपयोग किया जा सकता है।

उदाहरण उपयोग:

```

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```

***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.* For details, see this [page][] and its children.


[page]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | PngViewOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | PngViewOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | PngViewOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [PngViewOptions()](#PngViewOptions--) | PngViewOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | PngViewOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | PngViewOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | आउटपुट छवि की अधिकतम चौड़ाई पिक्सेल में लौटाता है। |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | आउटपुट छवि की अधिकतम चौड़ाई पिक्सेल में सेट करता है। |
| [getMaxHeight()](#getMaxHeight--) | आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में लौटाता है। |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में सेट करता है। |
| [isExtractText()](#isExtractText--) | निर्धारित करता है कि टेक्स्ट एक्सट्रैक्शन सक्षम है या नहीं। |
| [setExtractText(boolean value)](#setExtractText-boolean-) | टेक्स्ट एक्सट्रैक्शन को सक्षम या अक्षम करता है। |
| [getWidth()](#getWidth--) | आउटपुट छवि की चौड़ाई पिक्सेल में लौटाता है। |
| [setWidth(int value)](#setWidth-int-) | आउटपुट छवि की चौड़ाई पिक्सेल में सेट करता है। |
| [getHeight()](#getHeight--) | आउटपुट छवि की ऊँचाई पिक्सेल में लौटाता है। |
| [setHeight(int value)](#setHeight-int-) | आउटपुट छवि की ऊँचाई पिक्सेल में सेट करता है। |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | दस्तावेज़ को सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक प्राप्त करता है। |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | दस्तावेज़ को सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक सेट करता है। |
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


PngViewOptions क्लास का नया इंस्टेंस प्रारंभ करता है।

कोड उदाहरण के लिए, देखें [दस्तावेज़][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | वह मेथड जो आउटपुट पेज डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंशिएट करता है। |

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


PngViewOptions क्लास का नया इंस्टेंस प्रारंभ करता है।

कोड उदाहरण के लिए, देखें [दस्तावेज़][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | वह मेथड जो आउटपुट पेज डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंशिएट करता है। |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | वह मेथड जो createPageStream पैरामीटर को असाइन किए गए मेथड द्वारा निर्मित स्ट्रीम को रिलीज़ करता है। |

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


PngViewOptions क्लास का नया इंस्टेंस प्रारंभ करता है।

कोड उदाहरण के लिए, देखें [दस्तावेज़][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | आउटपुट पेज स्ट्रीम को बनाने और रिलीज़ करने के लिए मेथड्स को लागू करने वाला फ़ैक्टरी। |

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


PngViewOptions क्लास का नया इंस्टेंस प्रारंभ करता है।

यह कंस्ट्रक्टर PngViewOptions का नया इंस्टेंस "p\_\{0\}.png" को आउटपुट फ़ाइलों के लिए फ़ाइल पाथ फ़ॉर्मेट के रूप में इनिशियलाइज़ करता है। आउटपुट फ़ाइलें एप्लिकेशन की वर्तमान कार्य निर्देशिका में रखी जाएँगी। कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


PngViewOptions क्लास का नया इंस्टेंस प्रारंभ करता है।

उदाहरण के लिए, यदि फ़ाइल पाथ फ़ॉर्मेट 'page\_\{0\}.png' है, तो आउटपुट फ़ाइलें पेज नंबर के आधार पर 'page\_1.png', 'page\_2.png' आदि नाम से रखी जाएँगी।

***Note:** It is important to note that the output files will be placed into the current working directory of the application.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | java.lang.String | फ़ाइल पाथ फ़ॉर्मेट, उदाहरण के लिए, 'page\_\{0\}.png'। |

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


PngViewOptions क्लास का नया इंस्टेंस प्रारंभ करता है।

उदाहरण के लिए, यदि फ़ाइल पाथ फ़ॉर्मेट 'page\_\{0\}.png' है, तो आउटपुट फ़ाइलें पेज नंबर के आधार पर 'page\_1.png', 'page\_2.png' आदि नाम से रखी जाएँगी। कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | फ़ाइल पाथ फ़ॉर्मेट, उदाहरण के लिए, 'page\_\{0\}.png'। |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


आउटपुट छवि की अधिकतम चौड़ाई पिक्सेल में लौटाता है।

इस प्रॉपर्टी का उपयोग अधिकतम आउटपुट इमेज चौड़ाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप  प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाएगी।


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - आउटपुट इमेज की अधिकतम चौड़ाई।
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


आउटपुट छवि की अधिकतम चौड़ाई पिक्सेल में सेट करता है।

इस प्रॉपर्टी का उपयोग अधिकतम आउटपुट इमेज चौड़ाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप  प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाएगी।


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| maxWidth | int | आउटपुट इमेज की अधिकतम चौड़ाई। |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में लौटाता है।

इस प्रॉपर्टी का उपयोग अधिकतम आउटपुट इमेज ऊँचाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप  प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाएगी।


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - आउटपुट इमेज की अधिकतम ऊँचाई।
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में सेट करता है।

इस प्रॉपर्टी का उपयोग अधिकतम आउटपुट इमेज ऊँचाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप  प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाएगी।


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| maxHeight | int | आउटपुट इमेज की अधिकतम ऊँचाई। |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


निर्धारित करता है कि टेक्स्ट एक्सट्रैक्शन सक्षम है या नहीं।

यह विकल्प तब उपयोगी हो सकता है जब आप इमेज के ऊपर एक चयन योग्य टेक्स्ट लेयर जोड़ना चाहते हैं। इस प्रॉपर्टी का उपयोग स्रोत दस्तावेज़ में मौजूद टेक्स्ट और उसके निर्देशांक प्राप्त करने के लिए करें। फिर आप इस डेटा का उपयोग इमेज के ऊपर चयन योग्य टेक्स्ट जोड़ने या इमेज-आधारित रेंडरिंग में टेक्स्ट खोज लागू करने के लिए कर सकते हैं। कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Returns:**
boolean - यदि टेक्स्ट एक्सट्रैक्शन सक्षम है तो true, अन्यथा false।
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


टेक्स्ट एक्सट्रैक्शन को सक्षम या अक्षम करता है।

यह विकल्प तब उपयोगी हो सकता है जब आप इमेज के ऊपर एक चयन योग्य टेक्स्ट लेयर जोड़ना चाहते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean | टेक्स्ट एक्सट्रैक्शन सक्षम करने के लिए true, इसे अक्षम करने के लिए false। |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


आउटपुट छवि की चौड़ाई पिक्सेल में लौटाता है।

इस प्रॉपर्टी का उपयोग आउटपुट इमेज की चौड़ाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप इस प्रॉपर्टी को सेट करते हैं, तो  प्रॉपर्टी अनदेखी की जाएगी।


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - आउटपुट छवि की चौड़ाई।
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


आउटपुट छवि की चौड़ाई पिक्सेल में सेट करता है।

इस प्रॉपर्टी का उपयोग आउटपुट इमेज की चौड़ाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप इस प्रॉपर्टी को सेट करते हैं, तो  प्रॉपर्टी अनदेखी की जाएगी।


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int | आउटपुट छवि की चौड़ाई। |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


आउटपुट छवि की ऊँचाई पिक्सेल में लौटाता है।

इस प्रॉपर्टी का उपयोग आउटपुट इमेज की ऊँचाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप इस प्रॉपर्टी को सेट करते हैं, तो  प्रॉपर्टी अनदेखी की जाएगी।


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - आउटपुट इमेज की ऊँचाई।
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


आउटपुट छवि की ऊँचाई पिक्सेल में सेट करता है।

इस प्रॉपर्टी का उपयोग आउटपुट इमेज की ऊँचाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप इस प्रॉपर्टी को सेट करते हैं, तो  प्रॉपर्टी अनदेखी की जाएगी।


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int | आउटपुट इमेज की ऊँचाई। |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


दस्तावेज़ को सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक प्राप्त करता है।

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - दस्तावेज़ सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक।
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


दस्तावेज़ को सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | दस्तावेज़ सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक। |

