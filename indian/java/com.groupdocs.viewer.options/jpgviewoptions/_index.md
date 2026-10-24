---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "दस्तावेज़ों को JPG फ़ॉर्मेट में रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 17
url: /hi/java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

दस्तावेज़ों को JPG फ़ॉर्मेट में रेंडर करने के विकल्प प्रदान करता है।


JpgViewOptions क्लास अतिरिक्त सेटिंग्स और पैरामीटर को समाहित करती है जिन्हें दस्तावेज़ों की रेंडरिंग को नियंत्रित करने के लिए उपयोग किया जा सकता है।
GroupDocs.Viewer घटक में JPG प्रारूप में।


उदाहरण उपयोग:

````

 JpgViewOptions options = new JpgViewOptions();
 options.setMaxWidth(1920);
 options.setMaxHeight(1080);
 options.setQuality((byte) 96);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


***Note:** The JpgViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output JPG images.*

## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | नए उदाहरण को प्रारंभ करता है |
JpgViewOptions
class।
|
|  | [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | नए उदाहरण को प्रारंभ करता है |
JpgViewOptions
class।
|
|  | [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | नए उदाहरण को प्रारंभ करता है |
JpgViewOptions
class।
|
|  | [JpgViewOptions()](#JpgViewOptions--) | का नया इंस्टेंस प्रारंभ करता है |
JpgViewOptions
आउटपुट फ़ाइलों के लिए फ़ाइल पथ प्रारूप के रूप में "p_{0}.jpg" का उपयोग करके।
|
|  | [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | नए उदाहरण को प्रारंभ करता है |
JpgViewOptions
class।
|
|  | [JpgViewOptions(Path filePathFormat)](#JpgViewOptions-java.nio.file.Path-) | नए उदाहरण को प्रारंभ करता है |
JpgViewOptions
class।
|
## Methods

| Method | विवरण |
| --- | --- |
|  | [getMaxWidth()](#getMaxWidth--) | आउटपुट छवि की अधिकतम चौड़ाई पिक्सेल में प्राप्त करता है। |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | आउटपुट छवि की अधिकतम चौड़ाई पिक्सेल में सेट करता है। |
|
|  | [getMaxHeight()](#getMaxHeight--) | आउटपुट इमेज की अधिकतम ऊँचाई पिक्सेल में प्राप्त करता है। |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में सेट करता है। |
|
|  | [getQuality()](#getQuality--) | आउटपुट छवि की गुणवत्ता प्राप्त करता है। |
|
|  | [setQuality(byte value)](#setQuality-byte-) | आउटपुट छवि की गुणवत्ता सेट करता है। |
|
|  | [isExtractText()](#isExtractText--) | टेक्स्ट निष्कर्षण को सक्षम करता है। |
|
|  | [setExtractText(boolean value)](#setExtractText-boolean-) | टेक्स्ट निष्कर्षण को सक्षम या अक्षम करता है। |
|
|  | [getWidth()](#getWidth--) | आउटपुट इमेज की चौड़ाई पिक्सेल में प्राप्त करता है। |
|
|  | [setWidth(int value)](#setWidth-int-) | आउटपुट छवि की चौड़ाई को पिक्सेल में सेट करता है। |
|
|  | [getHeight()](#getHeight--) | आउटपुट छवि की ऊँचाई पिक्सेल में प्राप्त करता है। |
|
|  | [setHeight(int value)](#setHeight-int-) | आउटपुट छवि की ऊँचाई को पिक्सेल में सेट करता है। |
|
|  | [getPageStreamFactory()](#getPageStreamFactory--) | आउटपुट पेज स्ट्रीम बनाने और रिलीज़ करने के लिए विधियों को लागू करने वाले फ़ैक्टरी को प्राप्त करता है। |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Words या Email दस्तावेज़ के सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक प्राप्त करता है। |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Words या Email दस्तावेज़ के सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक सेट करता है। |
|
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


नए उदाहरण को प्रारंभ करता है
JpgViewOptions
class।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | वह मेथड जो आउटपुट पेज डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंशिएट करता है। |
|

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


नए उदाहरण को प्रारंभ करता है
JpgViewOptions
class।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | वह मेथड जो आउटपुट पेज डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंशिएट करता है। |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | वह विधि जो उस स्ट्रीम को रिलीज़ करती है जो उस विधि द्वारा बनाई गई है जो createPageStream पैरामीटर को पास किए गए डेलीगेट को असाइन की गई है। |
|

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


नए उदाहरण को प्रारंभ करता है
JpgViewOptions
class।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | फ़ैक्टरी जो आउटपुट पेज स्ट्रीम को बनाने और रिलीज़ करने के लिए विधियों को लागू करती है। |
|

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


का नया इंस्टेंस प्रारंभ करता है
JpgViewOptions
आउटपुट फ़ाइलों के लिए फ़ाइल पथ प्रारूप के रूप में "p_{0}.jpg" का उपयोग करके।
आउटपुट फ़ाइलें एप्लिकेशन की वर्तमान कार्य निर्देशिका में रखी जाएँगी।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg)।


### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


नए उदाहरण को प्रारंभ करता है
JpgViewOptions
class।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | फ़ाइल पथ प्रारूप, उदाहरण के लिए, 'page_{0}.jpg'। |
|

### JpgViewOptions(Path filePathFormat) {#JpgViewOptions-java.nio.file.Path-}
```
public JpgViewOptions(Path filePathFormat)
```


नए उदाहरण को प्रारंभ करता है
JpgViewOptions
class।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | फ़ाइल पथ प्रारूप, उदाहरण के लिए, 'page_{0}.jpg'। |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


आउटपुट छवि की अधिकतम चौड़ाई पिक्सेल में प्राप्त करता है।


इस प्रॉपर्टी का उपयोग करके आउटपुट इमेज की अधिकतम चौड़ाई (पिक्सेल में) सेट करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/)।
यदि आप #setWidth(int).setWidth(int) प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाएगी।


**Returns:**
int - आउटपुट इमेज की अधिकतम चौड़ाई।

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


आउटपुट छवि की अधिकतम चौड़ाई पिक्सेल में सेट करता है।


इस प्रॉपर्टी का उपयोग करके आउटपुट इमेज की अधिकतम चौड़ाई (पिक्सेल में) सेट करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/)।
यदि आप #setWidth(int).setWidth(int) प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाएगी।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | maxWidth | int | आउटपुट इमेज की अधिकतम चौड़ाई। |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


आउटपुट इमेज की अधिकतम ऊँचाई पिक्सेल में प्राप्त करता है।


इस प्रॉपर्टी का उपयोग करके आउटपुट इमेज की अधिकतम ऊँचाई (पिक्सेल में) सेट करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/)।
यदि आप #setHeight(int).setHeight(int) प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाएगी।


**Returns:**
int - आउटपुट इमेज की अधिकतम ऊँचाई।

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में सेट करता है।


इस प्रॉपर्टी का उपयोग करके आउटपुट इमेज की अधिकतम ऊँचाई (पिक्सेल में) सेट करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/)।
यदि आप #setHeight(int).setHeight(int) प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी की जाएगी।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | maxHeight | int | आउटपुट इमेज की अधिकतम ऊँचाई। |
|

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


आउटपुट छवि की गुणवत्ता प्राप्त करता है।


***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.*
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/)।


**Returns:**
byte - आउटपुट छवि की गुणवत्ता।

### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


आउटपुट छवि की गुणवत्ता सेट करता है।


***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.*
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | byte | आउटपुट छवि की गुणवत्ता। |
|

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


टेक्स्ट निष्कर्षण को सक्षम करता है।


***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.*
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/)।


**Returns:**
boolean -  true  यदि टेक्स्ट निष्कर्षण सक्षम है,  false  अन्यथा।

### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


टेक्स्ट निष्कर्षण को सक्षम या अक्षम करता है।


***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.*
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | boolean | true  टेक्स्ट निष्कर्षण को सक्षम करने के लिए,  false  इसे निष्क्रिय करने के लिए। |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


आउटपुट इमेज की चौड़ाई पिक्सेल में प्राप्त करता है।


इस प्रॉपर्टी का उपयोग करके आउटपुट इमेज की चौड़ाई (पिक्सेल में) सेट करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/)।
यदि आप इस प्रॉपर्टी को सेट करते हैं, तो #setMaxWidth(int).setMaxWidth(int) प्रॉपर्टी अनदेखी की जाएगी।


**Returns:**
int - आउटपुट इमेज की चौड़ाई।

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


आउटपुट छवि की चौड़ाई को पिक्सेल में सेट करता है।


इस प्रॉपर्टी का उपयोग करके आउटपुट इमेज की चौड़ाई (पिक्सेल में) सेट करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/)।
यदि आप इस प्रॉपर्टी को सेट करते हैं, तो #setMaxWidth(int).setMaxWidth(int) प्रॉपर्टी अनदेखी की जाएगी।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | int | आउटपुट इमेज की चौड़ाई। |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


आउटपुट छवि की ऊँचाई पिक्सेल में प्राप्त करता है।


इस प्रॉपर्टी का उपयोग करके आउटपुट इमेज की ऊँचाई (पिक्सेल में) सेट करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/)।
यदि आप इस प्रॉपर्टी को सेट करते हैं, तो #setMaxHeight(int).setMaxHeight(int) प्रॉपर्टी अनदेखी की जाएगी।


**Returns:**
int - आउटपुट इमेज की ऊँचाई।

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


आउटपुट छवि की ऊँचाई को पिक्सेल में सेट करता है।


इस प्रॉपर्टी का उपयोग करके आउटपुट इमेज की ऊँचाई (पिक्सेल में) सेट करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/)।
यदि आप इस प्रॉपर्टी को सेट करते हैं, तो #setMaxHeight(int).setMaxHeight(int) प्रॉपर्टी अनदेखी की जाएगी।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | int | आउटपुट इमेज की ऊँचाई। |
|

### getPageStreamFactory() {#getPageStreamFactory--}
```
public final PageStreamFactory getPageStreamFactory()
```


आउटपुट पेज स्ट्रीम बनाने और रिलीज़ करने के लिए विधियों को लागू करने वाले फ़ैक्टरी को प्राप्त करता है।


**Returns:**
[PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) - the factory for the output page stream.

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Words या Email दस्तावेज़ के सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक प्राप्त करता है।


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - दस्तावेज़ सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक।

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Words या Email दस्तावेज़ के सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | दस्तावेज़ सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक। |
|

