---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "दस्तावेज़ों को JPG फ़ॉर्मेट में रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 17
url: /hi/nodejs-java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

दस्तावेज़ों को JPG फ़ॉर्मेट में रेंडर करने के विकल्प प्रदान करता है।

JpgViewOptions क्लास अतिरिक्त सेटिंग्स और पैरामीटर को समाहित करता है जिन्हें GroupDocs.Viewer घटक में दस्तावेज़ों को JPG फ़ॉर्मेट में रेंडर करने को नियंत्रित करने के लिए उपयोग किया जा सकता है।

उदाहरण उपयोग:

```

 JpgViewOptions options = new JpgViewOptions();
 options.setMaxWidth(1920);
 options.setMaxHeight(1080);
 options.setQuality((byte) 96);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```

***Note:** The JpgViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output JPG images.*
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | JpgViewOptions क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | JpgViewOptions क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | JpgViewOptions क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [JpgViewOptions()](#JpgViewOptions--) | आउटपुट फ़ाइलों के लिए फ़ाइल पाथ फ़ॉर्मेट "p\_\{0\}.jpg" के साथ JpgViewOptions का एक नया इंस्टेंस प्रारंभ करता है। |
| [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | JpgViewOptions क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [JpgViewOptions(Path filePathFormat)](#JpgViewOptions-java.nio.file.Path-) | JpgViewOptions क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | आउटपुट इमेज की अधिकतम चौड़ाई पिक्सेल में प्राप्त करता है। |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | आउटपुट छवि की अधिकतम चौड़ाई पिक्सेल में सेट करता है। |
| [getMaxHeight()](#getMaxHeight--) | आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में प्राप्त करता है। |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में सेट करता है। |
| [getQuality()](#getQuality--) | आउटपुट इमेज की गुणवत्ता प्राप्त करता है। |
| [setQuality(byte value)](#setQuality-byte-) | आउटपुट इमेज की गुणवत्ता सेट करता है। |
| [isExtractText()](#isExtractText--) | टेक्स्ट निष्कर्षण को सक्षम करता है। |
| [setExtractText(boolean value)](#setExtractText-boolean-) | टेक्स्ट एक्सट्रैक्शन को सक्षम या अक्षम करता है। |
| [getWidth()](#getWidth--) | आउटपुट छवि की चौड़ाई पिक्सेल में प्राप्त करता है। |
| [setWidth(int value)](#setWidth-int-) | आउटपुट छवि की चौड़ाई पिक्सेल में सेट करता है। |
| [getHeight()](#getHeight--) | आउटपुट इमेज की ऊँचाई पिक्सेल में प्राप्त करता है। |
| [setHeight(int value)](#setHeight-int-) | आउटपुट छवि की ऊँचाई पिक्सेल में सेट करता है। |
| [getPageStreamFactory()](#getPageStreamFactory--) | फ़ैक्टरी प्राप्त करता है जो आउटपुट पेज स्ट्रीम बनाने और रिलीज़ करने के लिए मेथड्स को लागू करती है। |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Words या Email दस्तावेज़ की सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक प्राप्त करता है। |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Words या Email दस्तावेज़ की सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक सेट करता है। |
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


JpgViewOptions क्लास का एक नया इंस्टेंस प्रारंभ करता है।

कोड उदाहरण के लिए, देखें [दस्तावेज़][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | वह मेथड जो आउटपुट पेज डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंशिएट करता है। |

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


JpgViewOptions क्लास का एक नया इंस्टेंस प्रारंभ करता है।

कोड उदाहरण के लिए, देखें [दस्तावेज़][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | वह मेथड जो आउटपुट पेज डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंशिएट करता है। |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | वह मेथड जो उस स्ट्रीम को रिलीज़ करता है जो createPageStream पैरामीटर को पास किए गए डेलीगेट को असाइन किए गए मेथड द्वारा बनाई गई थी। |

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


JpgViewOptions क्लास का एक नया इंस्टेंस प्रारंभ करता है।

कोड उदाहरण के लिए, देखें [दस्तावेज़][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | आउटपुट पेज स्ट्रीम को बनाने और रिलीज़ करने के लिए मेथड्स को लागू करने वाला फ़ैक्टरी। |

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


आउटपुट फ़ाइलों के लिए फ़ाइल पाथ फ़ॉर्मेट "p\_\{0\}.jpg" के साथ JpgViewOptions का एक नया इंस्टेंस प्रारंभ करता है। आउटपुट फ़ाइलें एप्लिकेशन की वर्तमान कार्य निर्देशिका में रखी जाएँगी।

कोड उदाहरण के लिए, देखें [दस्तावेज़][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


JpgViewOptions क्लास का एक नया इंस्टेंस प्रारंभ करता है।

कोड उदाहरण के लिए, देखें [दस्तावेज़][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | java.lang.String | फ़ाइल पाथ फ़ॉर्मेट, उदाहरण के लिए, 'page\_\{0\}.jpg'। |

### JpgViewOptions(Path filePathFormat) {#JpgViewOptions-java.nio.file.Path-}
```
public JpgViewOptions(Path filePathFormat)
```


JpgViewOptions क्लास का एक नया इंस्टेंस प्रारंभ करता है।

कोड उदाहरण के लिए, देखें [दस्तावेज़][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | फ़ाइल पाथ फ़ॉर्मेट, उदाहरण के लिए, 'page\_\{0\}.jpg'। |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


आउटपुट इमेज की अधिकतम चौड़ाई पिक्सेल में प्राप्त करता है।

इस प्रॉपर्टी का उपयोग अधिकतम आउटपुट इमेज चौड़ाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप \#setWidth(int).setWidth(int) प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाएगी।


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - आउटपुट छवि की अधिकतम चौड़ाई।
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


आउटपुट छवि की अधिकतम चौड़ाई पिक्सेल में सेट करता है।

इस प्रॉपर्टी का उपयोग अधिकतम आउटपुट इमेज चौड़ाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप \#setWidth(int).setWidth(int) प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाएगी।


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| maxWidth | int | आउटपुट छवि की अधिकतम चौड़ाई। |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में प्राप्त करता है।

इस गुण का उपयोग अधिकतम आउटपुट छवि की ऊँचाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप \#setHeight(int).setHeight(int) गुण सेट करते हैं, तो यह गुण अनदेखा किया जाता है।


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - आउटपुट छवि की अधिकतम ऊँचाई।
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में सेट करता है।

इस गुण का उपयोग अधिकतम आउटपुट छवि की ऊँचाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप \#setHeight(int).setHeight(int) गुण सेट करते हैं, तो यह गुण अनदेखा किया जाता है।


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| maxHeight | int | आउटपुट छवि की अधिकतम ऊँचाई। |

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


आउटपुट इमेज की गुणवत्ता प्राप्त करता है।

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Returns:**
byte - आउटपुट छवि की गुणवत्ता।
### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


आउटपुट इमेज की गुणवत्ता सेट करता है।

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte | आउटपुट छवि की गुणवत्ता। |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


टेक्स्ट निष्कर्षण को सक्षम करता है।

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Returns:**
boolean - यदि टेक्स्ट एक्सट्रैक्शन सक्षम है तो true, अन्यथा false।
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


टेक्स्ट एक्सट्रैक्शन को सक्षम या अक्षम करता है।

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean | टेक्स्ट एक्सट्रैक्शन सक्षम करने के लिए true, इसे अक्षम करने के लिए false। |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


आउटपुट छवि की चौड़ाई पिक्सेल में प्राप्त करता है।

इस गुण का उपयोग आउटपुट छवि की चौड़ाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप इस गुण को सेट करते हैं, तो \#setMaxWidth(int).setMaxWidth(int) गुण अनदेखा किया जाता है।


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - आउटपुट छवि की चौड़ाई।
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


आउटपुट छवि की चौड़ाई पिक्सेल में सेट करता है।

इस गुण का उपयोग आउटपुट छवि की चौड़ाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप इस गुण को सेट करते हैं, तो \#setMaxWidth(int).setMaxWidth(int) गुण अनदेखा किया जाता है।


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int | आउटपुट छवि की चौड़ाई। |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


आउटपुट इमेज की ऊँचाई पिक्सेल में प्राप्त करता है।

इस गुण का उपयोग आउटपुट छवि की ऊँचाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप इस गुण को सेट करते हैं, तो \#setMaxHeight(int).setMaxHeight(int) गुण अनदेखा किया जाता है।


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - आउटपुट इमेज की ऊँचाई।
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


आउटपुट छवि की ऊँचाई पिक्सेल में सेट करता है।

इस गुण का उपयोग आउटपुट छवि की ऊँचाई (पिक्सेल में) सेट करने के लिए करें। कोड उदाहरण के लिए, देखें [documentation][]. यदि आप इस गुण को सेट करते हैं, तो \#setMaxHeight(int).setMaxHeight(int) गुण अनदेखा किया जाता है।


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int | आउटपुट इमेज की ऊँचाई। |

### getPageStreamFactory() {#getPageStreamFactory--}
```
public final PageStreamFactory getPageStreamFactory()
```


फ़ैक्टरी प्राप्त करता है जो आउटपुट पेज स्ट्रीम बनाने और रिलीज़ करने के लिए मेथड्स को लागू करती है।

**Returns:**
[PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) - the factory for the output page stream.
### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Words या Email दस्तावेज़ की सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक प्राप्त करता है।

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - दस्तावेज़ सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक।
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Words या Email दस्तावेज़ की सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | दस्तावेज़ सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक। |

