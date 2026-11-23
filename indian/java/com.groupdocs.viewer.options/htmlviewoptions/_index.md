---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "दस्तावेज़ों को HTML फ़ॉर्मेट में रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 16
url: /hi/java/com.groupdocs.viewer.options/htmlviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class HtmlViewOptions extends ViewOptions
```

दस्तावेज़ों को HTML फ़ॉर्मेट में रेंडर करने के विकल्प प्रदान करता है।


HtmlViewOptions क्लास अतिरिक्त सेटिंग्स और पैरामीटर को समाहित करती है।
जिसका उपयोग GroupDocs.Viewer घटक में दस्तावेज़ों को HTML फ़ॉर्मेट में रेंडर करने को नियंत्रित करने के लिए किया जा सकता है।


विवरण के लिए, देखें [topic](../https://docs.groupdocs.com/viewer/java/rendering-to-html/) और इसके उपविषय।


उदाहरण उपयोग:

````

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.setExcludeFonts(true);
 options.setFontsToExclude(Arrays.asList("font-name"));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


## Fields

| Field | विवरण |
| --- | --- |
| [CREATE_PAGE_STREAM](#CREATE-PAGE-STREAM) |  |
| [FILE_PATH_FORMAT](#FILE-PATH-FORMAT) |  |
## Methods

| Method | विवरण |
| --- | --- |
|  | [isRenderResponsive()](#isRenderResponsive--) | निर्धारित करता है कि रिस्पॉन्सिव रेंडरिंग सक्षम है या नहीं। |
|
|  | [setRenderResponsive(boolean value)](#setRenderResponsive-boolean-) | सेट करता है कि रिस्पॉन्सिव रेंडरिंग सक्षम है या नहीं। |
|
|  | [isMinify()](#isMinify--) | जाँचता है कि HTML सामग्री और HTML संसाधनों का मिनिफिकेशन सक्षम है या नहीं। |
|
|  | [setMinify(boolean value)](#setMinify-boolean-) | सेट करता है कि HTML सामग्री और HTML संसाधनों का मिनिफिकेशन सक्षम है या नहीं। |
|
|  | [isRenderToSinglePage()](#isRenderToSinglePage--) | पूरे दस्तावेज़ को एक HTML फ़ाइल में रेंडर करने को सक्षम बनाता है। |
|
|  | [setRenderToSinglePage(boolean renderSinglePage)](#setRenderToSinglePage-boolean-) | पूरे दस्तावेज़ को एक HTML फ़ाइल में रेंडर करने को सक्षम बनाता है। |
|
|  | [getImageMaxWidth()](#getImageMaxWidth--) | आउटपुट इमेज की अधिकतम चौड़ाई पिक्सेल में लौटाता है। |
|
|  | [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | आउटपुट छवि की अधिकतम चौड़ाई पिक्सेल में सेट करता है। |
|
|  | [getImageMaxHeight()](#getImageMaxHeight--) | आउटपुट इमेज की अधिकतम ऊँचाई पिक्सेल में प्राप्त करता है। |
|
|  | [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में सेट करता है। |
|
|  | [getImageWidth()](#getImageWidth--) | आउटपुट इमेज की चौड़ाई पिक्सेल में प्राप्त करता है। |
|
|  | [setImageWidth(int imageWidth)](#setImageWidth-int-) | आउटपुट छवि की चौड़ाई को पिक्सेल में सेट करता है। |
|
|  | [getImageHeight()](#getImageHeight--) | एकल इमेज को HTML में बदलते समय आउटपुट इमेज की ऊँचाई पिक्सेल में प्राप्त करता है। |
|
|  | [setImageHeight(int imageHeight)](#setImageHeight-int-) | एकल इमेज को HTML में बदलते समय आउटपुट इमेज की ऊँचाई पिक्सेल में सेट करता है। |
|
|  | [isForPrinting()](#isForPrinting--) | जाँचता है कि आउटपुट HTML को प्रिंटिंग के लिए अनुकूलित किया जाना चाहिए या नहीं। |
|
|  | [setForPrinting(boolean value)](#setForPrinting-boolean-) | सेट करता है कि आउटपुट HTML को प्रिंटिंग के लिए अनुकूलित किया जाना चाहिए या नहीं। |
|
|  | [isExcludeFonts()](#isExcludeFonts--) | निर्धारित करता है कि HTML दस्तावेज़ से फ़ॉन्ट्स को बाहर रखा जाए या नहीं। |
|
|  | [setExcludeFonts(boolean value)](#setExcludeFonts-boolean-) | HTML दस्तावेज़ से फ़ॉन्ट को बाहर रखने की सेटिंग करता है। |
|
|  | [getFontsToExclude()](#getFontsToExclude--) | HTML दस्तावेज़ से बाहर रखने के लिए फ़ॉन्ट नामों की सूची प्राप्त करता है। |
|
|  | [setFontsToExclude(List<String> value)](#setFontsToExclude-java.util.List-java.lang.String--) | HTML दस्तावेज़ से बाहर रखने के लिए फ़ॉन्ट नामों की सूची सेट करता है। |
|
|  | [isRemoveJavaScript()](#isRemoveJavaScript--) | इनपुट दस्तावेज़ों को रेंडर करते समय, जिनमें स्क्रिप्ट्स हैं, परिणामस्वरूप HTML दस्तावेज़ों में लिंक से JavaScript स्रोत कोड को हटाने की अनुमति देता है। |
|
|  | [setRemoveJavaScript(boolean value)](#setRemoveJavaScript-boolean-) | इनपुट दस्तावेज़ों को रेंडर करते समय, जिनमें स्क्रिप्ट्स हैं, परिणामस्वरूप HTML दस्तावेज़ों में लिंक से JavaScript स्रोत कोड को हटाने की अनुमति सेट करता है। |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Words या Email दस्तावेज़ की सहेजने की प्रगति का अनुमान लगाने के लिए उपयोग किए जाने वाले कॉलबैक को प्राप्त करता है। |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Words या Email दस्तावेज़ की सहेजने की प्रगति का अनुमान लगाने के लिए उपयोग किए जाने वाले कॉलबैक को सेट करता है। |
|
|  | [forEmbeddedResources(CreatePageStream createPageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-) | नए उदाहरण को प्रारंभ करता है |
HtmlViewOptions
एम्बेडेड संसाधनों के साथ HTML में रेंडर करने के लिए क्लास।
|
|  | [forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | नए उदाहरण को प्रारंभ करता है |
HtmlViewOptions
एम्बेडेड संसाधनों के साथ HTML में रेंडर करने के लिए क्लास।
|
|  | [forEmbeddedResources(PageStreamFactory pageStreamFactory)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-) | नए उदाहरण को प्रारंभ करता है |
HtmlViewOptions
एम्बेडेड संसाधनों के साथ HTML में रेंडर करने के लिए क्लास।
|
|  | [forEmbeddedResources()](#forEmbeddedResources--) | नए उदाहरण को प्रारंभ करता है |
HtmlViewOptions
class।
|
|  | [forEmbeddedResources(String filePathFormat)](#forEmbeddedResources-java.lang.String-) | नए उदाहरण को प्रारंभ करता है |
HtmlViewOptions
class।
|
|  | [forEmbeddedResources(Path filePathFormat)](#forEmbeddedResources-java.nio.file.Path-) | नए उदाहरण को प्रारंभ करता है |
HtmlViewOptions
class।
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-) | नए उदाहरण को प्रारंभ करता है |
HtmlViewOptions
बाहरी संसाधनों के साथ HTML में रेंडर करने के लिए क्लास।
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-) | नए उदाहरण को प्रारंभ करता है |
HtmlViewOptions
बाहरी संसाधनों के साथ HTML में रेंडर करने के लिए क्लास।
|
|  | [forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)](#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-) | नए उदाहरण को प्रारंभ करता है |
HtmlViewOptions
बाहरी संसाधनों के साथ HTML में रेंडर करने के लिए क्लास।
|
|  | [forExternalResources()](#forExternalResources--) | नए इंस्टेंस को इनिशियलाइज़ करता है |
HtmlViewOptions
class।
|
|  | [forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)](#forExternalResources-java.lang.String-java.lang.String-java.lang.String-) | नए उदाहरण को प्रारंभ करता है |
HtmlViewOptions
class।
|
### CREATE_PAGE_STREAM {#CREATE-PAGE-STREAM}
```
public static final String CREATE_PAGE_STREAM
```


### FILE_PATH_FORMAT {#FILE-PATH-FORMAT}
```
public static final String FILE_PATH_FORMAT
```


### isRenderResponsive() {#isRenderResponsive--}
```
public final boolean isRenderResponsive()
```


निर्धारित करता है कि रिस्पॉन्सिव रेंडरिंग सक्षम है या नहीं।
रिस्पॉन्सिव वेब पेज विभिन्न स्क्रीन आकार वाले डिवाइसों पर अच्छी तरह रेंडर होते हैं।


रिस्पॉन्सिव डिज़ाइन का उद्देश्य वेब पेजों को विभिन्न डिवाइसों पर अच्छी तरह रेंडर करना है। रिस्पॉन्सिव लेआउट के साथ रेंडर करने के लिए, इस प्रॉपर्टी को true सेट करें।
कोड उदाहरण के लिए, देखें [डॉक्यूमेंटेशन](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/)।


**Returns:**
बूलियन -  true  यदि रिस्पॉन्सिव रेंडरिंग सक्षम है,  false  अन्यथा।

### setRenderResponsive(boolean value) {#setRenderResponsive-boolean-}
```
public final void setRenderResponsive(boolean value)
```


सेट करता है कि रिस्पॉन्सिव रेंडरिंग सक्षम है या नहीं।
रिस्पॉन्सिव वेब पेज विभिन्न स्क्रीन आकार वाले डिवाइसों पर अच्छी तरह रेंडर होते हैं।


रिस्पॉन्सिव डिज़ाइन का उद्देश्य वेब पेजों को विभिन्न डिवाइसों पर अच्छी तरह रेंडर करना है। रिस्पॉन्सिव लेआउट के साथ रेंडर करने के लिए, इस प्रॉपर्टी को true सेट करें।
कोड उदाहरण के लिए, देखें [डॉक्यूमेंटेशन](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | boolean | true  रिस्पॉन्सिव रेंडरिंग को सक्षम करने के लिए,  false  इसे निष्क्रिय करने के लिए। |
|

### isMinify() {#isMinify--}
```
public final boolean isMinify()
```


जाँचता है कि HTML सामग्री और HTML संसाधनों का मिनिफिकेशन सक्षम है या नहीं।


आउटपुट कंटेंट (HTML, CSS, और SVG) का संपीड़न HTML फ़ाइल को अनुकूलित करने के तरीकों में से एक है। इसे करने के लिए, इस प्रॉपर्टी को true सेट करें।
कोड उदाहरण के लिए, देखें [डॉक्यूमेंटेशन](../https://docs.groupdocs.com/viewer/java/minify-html/)।


**Returns:**
बूलियन -  true  यदि मिनिफिकेशन सक्षम है,  false  अन्यथा।

### setMinify(boolean value) {#setMinify-boolean-}
```
public final void setMinify(boolean value)
```


सेट करता है कि HTML सामग्री और HTML संसाधनों का मिनिफिकेशन सक्षम है या नहीं।


आउटपुट कंटेंट (HTML, CSS, और SVG) का संपीड़न HTML फ़ाइल को अनुकूलित करने के तरीकों में से एक है। इसे करने के लिए, इस प्रॉपर्टी को true सेट करें।
कोड उदाहरण के लिए, देखें [डॉक्यूमेंटेशन](../https://docs.groupdocs.com/viewer/java/minify-html/)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | boolean | true  मिनिफिकेशन को सक्षम करने के लिए,  false  इसे निष्क्रिय करने के लिए। |
|

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public boolean isRenderToSinglePage()
```


पूरे दस्तावेज़ को एक HTML फ़ाइल में रेंडर करने को सक्षम बनाता है।

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer("invoice.docx")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setRenderToSinglePage(boolean renderSinglePage) {#setRenderToSinglePage-boolean-}
```
public void setRenderToSinglePage(boolean renderSinglePage)
```


पूरे दस्तावेज़ को एक HTML फ़ाइल में रेंडर करने को सक्षम बनाता है।

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer("invoice.docx")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| renderSinglePage | boolean |  |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


आउटपुट इमेज की अधिकतम चौड़ाई पिक्सेल में लौटाता है।
***Note:** This value is used when converting a single image to HTML.
विवरण और कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Returns:**
int - आउटपुट इमेज की अधिकतम चौड़ाई।

### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


आउटपुट छवि की अधिकतम चौड़ाई पिक्सेल में सेट करता है।
***Note:** This value is used when converting a single image to HTML.
विवरण और कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | imageMaxWidth | int | आउटपुट इमेज की अधिकतम चौड़ाई। |
|

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


आउटपुट इमेज की अधिकतम ऊँचाई पिक्सेल में प्राप्त करता है।
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
विवरण और कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Returns:**
int - आउटपुट इमेज की अधिकतम ऊँचाई।

### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में सेट करता है।
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
विवरण और कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | imageMaxHeight | int | आउटपुट इमेज की अधिकतम ऊँचाई। |
|

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


आउटपुट इमेज की चौड़ाई पिक्सेल में प्राप्त करता है।


***Note:** This value is applicable only when converting a single image to HTML.*
विवरण और कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Returns:**
int - आउटपुट इमेज की चौड़ाई।

### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


आउटपुट छवि की चौड़ाई को पिक्सेल में सेट करता है।


***Note:** This value is applicable only when converting a single image to HTML.*
विवरण और कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | imageWidth | int | आउटपुट इमेज की चौड़ाई। |
|

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


एकल इमेज को HTML में बदलते समय आउटपुट इमेज की ऊँचाई पिक्सेल में प्राप्त करता है।


विवरण और कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Returns:**
int - आउटपुट छवि की ऊँचाई पिक्सेल में।

### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


एकल इमेज को HTML में बदलते समय आउटपुट इमेज की ऊँचाई पिक्सेल में सेट करता है।


विवरण और कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | imageHeight | int | आउटपुट छवि की ऊँचाई पिक्सेल में। |
|

### isForPrinting() {#isForPrinting--}
```
public final boolean isForPrinting()
```


जाँचता है कि आउटपुट HTML को प्रिंटिंग के लिए अनुकूलित किया जाना चाहिए या नहीं।


इस विकल्प को सक्षम करें ताकि आउटपुट HTML पेजों को वेक्टर SVG फ़ॉर्मेट में परिवर्तित किया जा सके।
विवरण और कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/).


**Returns:**
boolean -  true  यदि आउटपुट HTML को प्रिंटिंग के लिए अनुकूलित किया जाना चाहिए,  false  अन्यथा।

### setForPrinting(boolean value) {#setForPrinting-boolean-}
```
public final void setForPrinting(boolean value)
```


सेट करता है कि आउटपुट HTML को प्रिंटिंग के लिए अनुकूलित किया जाना चाहिए या नहीं।


इस विकल्प को सक्षम करें ताकि आउटपुट HTML पेजों को वेक्टर SVG फ़ॉर्मेट में परिवर्तित किया जा सके।
विवरण और कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | boolean | true  आउटपुट HTML को प्रिंटिंग के लिए अनुकूलित करने के लिए,  false  अन्यथा। |
|

### isExcludeFonts() {#isExcludeFonts--}
```
public final boolean isExcludeFonts()
```


निर्धारित करता है कि HTML दस्तावेज़ से फ़ॉन्ट्स को बाहर रखा जाए या नहीं।


डिफ़ॉल्ट रूप से, GroupDocs.Viewer दस्तावेज़ में उपयोग किए गए फ़ॉन्ट्स को HTML में एम्बेड करता है। इसे रोकने के लिए, इस प्रॉपर्टी को true सेट करें।
विवरण और कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Returns:**
boolean -  true  यदि फ़ॉन्ट्स को बाहर रखा जाना चाहिए,  false  अन्यथा।

### setExcludeFonts(boolean value) {#setExcludeFonts-boolean-}
```
public final void setExcludeFonts(boolean value)
```


HTML दस्तावेज़ से फ़ॉन्ट को बाहर रखने की सेटिंग करता है।


डिफ़ॉल्ट रूप से, GroupDocs.Viewer दस्तावेज़ में उपयोग किए गए फ़ॉन्ट्स को HTML में एम्बेड करता है। इसे रोकने के लिए, इस प्रॉपर्टी को true सेट करें।
विवरण और कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | boolean | true  फ़ॉन्ट्स को बाहर रखने के लिए,  false  अन्यथा। |
|

### getFontsToExclude() {#getFontsToExclude--}
```
public final List<String> getFontsToExclude()
```


HTML दस्तावेज़ से बाहर रखने के लिए फ़ॉन्ट नामों की सूची प्राप्त करता है।


यह विकल्प केवल प्रस्तुतियों के लिए समर्थित है।
HTML दस्तावेज़ में फ़ॉन्ट्स को शामिल करने से आउटपुट व्यू की स्थिरता में सुधार होता है लेकिन रेंडरिंग परिणाम का आकार बढ़ जाता है।
स्थिरता और आउटपुट आकार के बीच समझौता खोजने के लिए इस विकल्प का उपयोग करें।
ऐसे फ़ॉन्ट नाम शामिल करें जो लोकप्रिय हैं और अधिकांश सिस्टम पर स्थापित हैं।


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) विकल्प अक्षम है.*
विवरण और कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Returns:**
java.util.List<java.lang.String> - HTML दस्तावेज़ से बाहर रखने के लिए फ़ॉन्ट नामों की सूची।

### setFontsToExclude(List<String> value) {#setFontsToExclude-java.util.List-java.lang.String--}
```
public final void setFontsToExclude(List<String> value)
```


HTML दस्तावेज़ से बाहर रखने के लिए फ़ॉन्ट नामों की सूची सेट करता है।


यह विकल्प केवल प्रस्तुतियों के लिए समर्थित है।
HTML दस्तावेज़ में फ़ॉन्ट्स को शामिल करने से आउटपुट व्यू की स्थिरता में सुधार होता है लेकिन रेंडरिंग परिणाम का आकार बढ़ जाता है।
स्थिरता और आउटपुट आकार के बीच समझौता खोजने के लिए इस विकल्प का उपयोग करें।
ऐसे फ़ॉन्ट नाम शामिल करें जो लोकप्रिय हैं और अधिकांश सिस्टम पर स्थापित हैं।


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) विकल्प अक्षम है.*
विवरण और कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.util.List<java.lang.String> | HTML दस्तावेज़ से बाहर रखने के लिए फ़ॉन्ट नामों की सूची। |
|

### isRemoveJavaScript() {#isRemoveJavaScript--}
```
public final boolean isRemoveJavaScript()
```


जावास्क्रिप्ट स्रोत कोड को परिणामी HTML दस्तावेज़ों में लिंक से हटाने की अनुमति देता है, जब इनपुट दस्तावेज़ों को रेंडर किया जाता है, जिनमें स्क्रिप्ट्स होते हैं। डिफ़ॉल्ट रूप से यह सक्षम है (true)।


जावास्क्रिप्ट हटाने के बारे में विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html)।


**Returns:**
boolean
### setRemoveJavaScript(boolean value) {#setRemoveJavaScript-boolean-}
```
public void setRemoveJavaScript(boolean value)
```


जावास्क्रिप्ट स्रोत कोड को परिणामी HTML दस्तावेज़ों में लिंक से हटाने की अनुमति सेट करता है, जब इनपुट दस्तावेज़ों को रेंडर किया जाता है, जिनमें स्क्रिप्ट्स होते हैं। डिफ़ॉल्ट रूप से यह सक्षम है (true)।


जावास्क्रिप्ट हटाने के बारे में विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Words या Email दस्तावेज़ की सहेजने की प्रगति का अनुमान लगाने के लिए उपयोग किए जाने वाले कॉलबैक को प्राप्त करता है।


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - दस्तावेज़ सहेजने की प्रगति का अनुमान लगाने के लिए उपयोग किया जाने वाला कॉलबैक।

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Words या Email दस्तावेज़ की सहेजने की प्रगति का अनुमान लगाने के लिए उपयोग किए जाने वाले कॉलबैक को सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | दस्तावेज़ सहेजने की प्रगति का अनुमान लगाने के लिए उपयोग किया जाने वाला कॉलबैक। |
|

### forEmbeddedResources(CreatePageStream createPageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream)
```


नए उदाहरण को प्रारंभ करता है
HtmlViewOptions
एम्बेडेड संसाधनों के साथ HTML में रेंडर करने के लिए क्लास।


***Note:** The method takes a 
CreatePageStream
पैरामीटर, जो आउटपुट पेज डेटा लिखने के लिए एक स्ट्रीम को इंस्टैंसिएट करने की विधि है।*
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | वह विधि जो आउटपुट पेज डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंसिएट करती है। |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


नए उदाहरण को प्रारंभ करता है
HtmlViewOptions
एम्बेडेड संसाधनों के साथ HTML में रेंडर करने के लिए क्लास।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | वह विधि जो आउटपुट पेज डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंसिएट करती है। |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | वह विधि जो  createPageStream  पैरामीटर को असाइन की गई विधि द्वारा बनाई गई स्ट्रीम को रिलीज़ करती है। |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(PageStreamFactory pageStreamFactory) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public static HtmlViewOptions forEmbeddedResources(PageStreamFactory pageStreamFactory)
```


नए उदाहरण को प्रारंभ करता है
HtmlViewOptions
एम्बेडेड संसाधनों के साथ HTML में रेंडर करने के लिए क्लास।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | फ़ैक्टरी जो आउटपुट पेज स्ट्रीम को बनाने और रिलीज़ करने के लिए विधियों को लागू करती है। |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources() {#forEmbeddedResources--}
```
public static HtmlViewOptions forEmbeddedResources()
```


नए उदाहरण को प्रारंभ करता है
HtmlViewOptions
class।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources)।


**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(String filePathFormat) {#forEmbeddedResources-java.lang.String-}
```
public static HtmlViewOptions forEmbeddedResources(String filePathFormat)
```


नए उदाहरण को प्रारंभ करता है
HtmlViewOptions
class।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | फ़ाइल पाथ फ़ॉर्मेट, उदाहरण के लिए, 'page_{0}.html'। |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(Path filePathFormat) {#forEmbeddedResources-java.nio.file.Path-}
```
public static HtmlViewOptions forEmbeddedResources(Path filePathFormat)
```


नए उदाहरण को प्रारंभ करता है
HtmlViewOptions
class।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | फ़ाइल पाथ फ़ॉर्मेट, उदाहरण के लिए, 'page_{0}.html'। |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```


नए उदाहरण को प्रारंभ करता है
HtmlViewOptions
बाहरी संसाधनों के साथ HTML में रेंडर करने के लिए क्लास।


***Note:** This method should be used when rendering HTML with external resources, such as CSS and JavaScript files.*
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | वह विधि जो आउटपुट पेज डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंसिएट करती है। |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | वह विधि जो  createPageStream  विधि द्वारा बनाई गई स्ट्रीम को रिलीज़ करती है। |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | वह विधि जो HTML रिसोर्स के लिए URL बनाती है। |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```


नए उदाहरण को प्रारंभ करता है
HtmlViewOptions
बाहरी संसाधनों के साथ HTML में रेंडर करने के लिए क्लास।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | वह विधि जो आउटपुट पेज डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंसिएट करती है। |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | वह विधि जो आउटपुट HTML रिसोर्स डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंसिएट करती है। |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | वह विधि जो HTML रिसोर्स के लिए URL बनाती है। |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | वह विधि जो  createPageStream  विधि द्वारा बनाई गई स्ट्रीम को रिलीज़ करती है। |
|
|  | releaseResourceStream | [ReleaseResourceStream](../../com.groupdocs.viewer.interfaces/releaseresourcestream) | वह विधि जो  createResourceStream  विधि द्वारा बनाई गई स्ट्रीम को रिलीज़ करती है। |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory) {#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-}
```
public static HtmlViewOptions forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)
```


नए उदाहरण को प्रारंभ करता है
HtmlViewOptions
बाहरी संसाधनों के साथ HTML में रेंडर करने के लिए क्लास।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | फ़ैक्टरी जो आउटपुट पेज स्ट्रीम को बनाने और रिलीज़ करने के लिए विधियों को लागू करती है। |
|
|  | resourceStreamFactory | [ResourceStreamFactory](../../com.groupdocs.viewer.interfaces/resourcestreamfactory) | फ़ैक्टरी जो रिसोर्स URL बनाने और आउटपुट HTML रिसोर्स स्ट्रीम को इंस्टैंसिएट/रिलीज़ करने के लिए विधियों को लागू करती है। |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources() {#forExternalResources--}
```
public static HtmlViewOptions forExternalResources()
```


नए इंस्टेंस को इनिशियलाइज़ करता है
HtmlViewOptions
class।


* - with "p_{0}.html" as file path format for the output HTML files;
* - with "p_{0}_{1}" as file path format for the output HTML-resource files;
* - with "p_{0}_{1}" as URL format for HTML-resources;

आउटपुट फ़ाइलें एप्लिकेशन की वर्तमान कार्य निर्देशिका में रखी जाएँगी। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources)।

<br />



**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat) {#forExternalResources-java.lang.String-java.lang.String-java.lang.String-}
```
public static HtmlViewOptions forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)
```


नए उदाहरण को प्रारंभ करता है
HtmlViewOptions
class।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | फ़ाइल पाथ फ़ॉर्मेट, उदाहरण के लिए, 'page_{0}.html'। |
|
|  | resourceFilePathFormat | java.lang.String | रिसोर्स फ़ाइल पाथ फ़ॉर्मेट, उदाहरण के लिए, 'page_{0}/resource_{1}'। |
|
|  | resourceUrlFormat | java.lang.String | रिसोर्स URL फ़ॉर्मेट, उदाहरण के लिए, 'page_{0}/resource_{1}'। |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
