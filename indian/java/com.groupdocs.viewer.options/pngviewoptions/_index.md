---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "दस्तावेज़ों को PNG फ़ॉर्मेट में रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 25
url: /hi/java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

दस्तावेज़ों को PNG फ़ॉर्मेट में रेंडर करने के विकल्प प्रदान करता है।


PngViewOptions क्लास अतिरिक्त सेटिंग्स और पैरामीटर को समाहित करता है जिन्हें उपयोग किया जा सकता है
GroupDocs.Viewer घटक में दस्तावेज़ों को PNG फ़ॉर्मेट में रेंडर करने को नियंत्रित करने के लिए।


उदाहरण उपयोग:

````

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.*
विवरण के लिए, इस [page](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/) को देखें और इसके उपपृष्ठों को।

## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | नए उदाहरण को प्रारंभ करता है |
PngViewOptions
class।
|
|  | [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | नए उदाहरण को प्रारंभ करता है |
PngViewOptions
class।
|
|  | [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | नए उदाहरण को प्रारंभ करता है |
PngViewOptions
class।
|
|  | [PngViewOptions()](#PngViewOptions--) | नए इंस्टेंस को इनिशियलाइज़ करता है |
PngViewOptions
class।
|
|  | [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | नए उदाहरण को प्रारंभ करता है |
PngViewOptions
class।
|
|  | [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | नए उदाहरण को प्रारंभ करता है |
PngViewOptions
class।
|
## Methods

| Method | विवरण |
| --- | --- |
|  | [getMaxWidth()](#getMaxWidth--) | आउटपुट इमेज की अधिकतम चौड़ाई पिक्सेल में लौटाता है। |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | आउटपुट छवि की अधिकतम चौड़ाई पिक्सेल में सेट करता है। |
|
|  | [getMaxHeight()](#getMaxHeight--) | आउटपुट छवि की अधिकतम ऊँचाई को पिक्सेल में लौटाता है। |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में सेट करता है। |
|
|  | [isExtractText()](#isExtractText--) | निर्धारित करता है कि टेक्स्ट निष्कर्षण सक्षम है या नहीं। |
|
|  | [setExtractText(boolean value)](#setExtractText-boolean-) | टेक्स्ट निष्कर्षण को सक्षम या अक्षम करता है। |
|
|  | [getWidth()](#getWidth--) | आउटपुट छवि की चौड़ाई को पिक्सेल में लौटाता है। |
|
|  | [setWidth(int value)](#setWidth-int-) | आउटपुट छवि की चौड़ाई को पिक्सेल में सेट करता है। |
|
|  | [getHeight()](#getHeight--) | आउटपुट छवि की ऊँचाई को पिक्सेल में लौटाता है। |
|
|  | [setHeight(int value)](#setHeight-int-) | आउटपुट छवि की ऊँचाई को पिक्सेल में सेट करता है। |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | दस्तावेज़ के सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक प्राप्त करता है। |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | दस्तावेज़ के सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक सेट करता है। |
|
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


नए उदाहरण को प्रारंभ करता है
PngViewOptions
class।


कोड उदाहरण के लिए, इस [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png) को देखें।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | वह मेथड जो आउटपुट पेज डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंशिएट करता है। |
|

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


नए उदाहरण को प्रारंभ करता है
PngViewOptions
class।


कोड उदाहरण के लिए, इस [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png) को देखें।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | वह मेथड जो आउटपुट पेज डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंशिएट करता है। |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | वह मेथड जो createPageStream पैरामीटर को असाइन किए गए मेथड द्वारा निर्मित स्ट्रीम को रिलीज़ करता है। |
|

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


नए उदाहरण को प्रारंभ करता है
PngViewOptions
class।


कोड उदाहरण के लिए, इस [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png) को देखें।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | फ़ैक्टरी जो आउटपुट पेज स्ट्रीम को बनाने और रिलीज़ करने के लिए विधियों को लागू करती है। |
|

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


नए इंस्टेंस को इनिशियलाइज़ करता है
PngViewOptions
class।


यह कन्स्ट्रक्टर नया इंस्टेंस इनिशियलाइज़ करता है।
PngViewOptions

"p_{0}.png" को आउटपुट फ़ाइलों के लिए फ़ाइल पथ स्वरूप के रूप में उपयोग करें।
आउटपुट फ़ाइलें एप्लिकेशन की वर्तमान कार्य निर्देशिका में रखी जाएँगी।
कोड उदाहरण के लिए, इस [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png) को देखें।


### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


नए उदाहरण को प्रारंभ करता है
PngViewOptions
class।


उदाहरण के लिए, यदि फ़ाइल पथ स्वरूप 'page_{0}.png' है, तो आउटपुट फ़ाइलें होंगी
'page_1.png', 'page_2.png' आदि के रूप में नामित होंगी, पृष्ठ संख्या के आधार पर।


***Note:** It is important to note that the output files will be placed into the current working directory of the application.*
कोड उदाहरण के लिए, इस [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png) को देखें।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | फ़ाइल पथ स्वरूप, उदाहरण के लिए, 'page_{0}.png'। |
|

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


नए उदाहरण को प्रारंभ करता है
PngViewOptions
class।


उदाहरण के लिए, यदि फ़ाइल पथ स्वरूप 'page_{0}.png' है, तो आउटपुट फ़ाइलें होंगी
'page_1.png', 'page_2.png' आदि के रूप में नामित होंगी, पृष्ठ संख्या के आधार पर।
कोड उदाहरण के लिए, इस [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png) को देखें।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | फ़ाइल पथ स्वरूप, उदाहरण के लिए, 'page_{0}.png'। |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


आउटपुट इमेज की अधिकतम चौड़ाई पिक्सेल में लौटाता है।


इस प्रॉपर्टी का उपयोग करके आउटपुट इमेज की अधिकतम चौड़ाई (पिक्सेल में) सेट करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/)।
यदि आप प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी कर दी जाती है।


**Returns:**
int - आउटपुट इमेज की अधिकतम चौड़ाई।

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


आउटपुट छवि की अधिकतम चौड़ाई पिक्सेल में सेट करता है।


इस प्रॉपर्टी का उपयोग करके आउटपुट इमेज की अधिकतम चौड़ाई (पिक्सेल में) सेट करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/)।
यदि आप प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी कर दी जाती है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | maxWidth | int | आउटपुट इमेज की अधिकतम चौड़ाई। |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


आउटपुट छवि की अधिकतम ऊँचाई को पिक्सेल में लौटाता है।


इस प्रॉपर्टी का उपयोग करके आउटपुट इमेज की अधिकतम ऊँचाई (पिक्सेल में) सेट करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/)।
यदि आप प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी कर दी जाती है।


**Returns:**
int - आउटपुट इमेज की अधिकतम ऊँचाई।

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में सेट करता है।


इस प्रॉपर्टी का उपयोग करके आउटपुट इमेज की अधिकतम ऊँचाई (पिक्सेल में) सेट करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/)।
यदि आप प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी कर दी जाती है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | maxHeight | int | आउटपुट इमेज की अधिकतम ऊँचाई। |
|

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


निर्धारित करता है कि टेक्स्ट निष्कर्षण सक्षम है या नहीं।


यह विकल्प उपयोगी हो सकता है जब आप इमेज के ऊपर चयन योग्य टेक्स्ट लेयर जोड़ना चाहते हैं।
इस प्रॉपर्टी का उपयोग करके स्रोत दस्तावेज़ में मौजूद टेक्स्ट और उसके निर्देशांक प्राप्त करें। फिर आप इस डेटा का उपयोग करके इमेज के ऊपर चयन योग्य टेक्स्ट जोड़ सकते हैं या इमेज-आधारित रेंडरिंग में टेक्स्ट खोज लागू कर सकते हैं।
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/)।


**Returns:**
boolean -  true  यदि टेक्स्ट निष्कर्षण सक्षम है,  false  अन्यथा।

### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


टेक्स्ट निष्कर्षण को सक्षम या अक्षम करता है।


यह विकल्प उपयोगी हो सकता है जब आप इमेज के ऊपर चयन योग्य टेक्स्ट लेयर जोड़ना चाहते हैं।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | boolean | true  टेक्स्ट निष्कर्षण को सक्षम करने के लिए,  false  इसे निष्क्रिय करने के लिए। |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


आउटपुट छवि की चौड़ाई को पिक्सेल में लौटाता है।


इस प्रॉपर्टी का उपयोग करके आउटपुट इमेज की चौड़ाई (पिक्सेल में) सेट करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/)।
यदि आप इस प्रॉपर्टी को सेट करते हैं, तो यह प्रॉपर्टी अनदेखी कर दी जाती है।


**Returns:**
int - आउटपुट इमेज की चौड़ाई।

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


आउटपुट छवि की चौड़ाई को पिक्सेल में सेट करता है।


इस प्रॉपर्टी का उपयोग करके आउटपुट इमेज की चौड़ाई (पिक्सेल में) सेट करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/)।
यदि आप इस प्रॉपर्टी को सेट करते हैं, तो यह प्रॉपर्टी अनदेखी कर दी जाती है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | int | आउटपुट इमेज की चौड़ाई। |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


आउटपुट छवि की ऊँचाई को पिक्सेल में लौटाता है।


इस प्रॉपर्टी का उपयोग करके आउटपुट इमेज की ऊँचाई (पिक्सेल में) सेट करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/)।
यदि आप इस प्रॉपर्टी को सेट करते हैं, तो यह प्रॉपर्टी अनदेखी कर दी जाती है।


**Returns:**
int - आउटपुट इमेज की ऊँचाई।

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


आउटपुट छवि की ऊँचाई को पिक्सेल में सेट करता है।


इस प्रॉपर्टी का उपयोग करके आउटपुट इमेज की ऊँचाई (पिक्सेल में) सेट करें। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/)।
यदि आप इस प्रॉपर्टी को सेट करते हैं, तो यह प्रॉपर्टी अनदेखी कर दी जाती है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | int | आउटपुट इमेज की ऊँचाई। |
|

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


दस्तावेज़ के सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक प्राप्त करता है।


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - दस्तावेज़ सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक।

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


दस्तावेज़ के सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | दस्तावेज़ सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक। |
|

