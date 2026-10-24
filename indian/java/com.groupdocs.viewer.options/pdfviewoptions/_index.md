---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "दस्तावेज़ों को PDF फ़ॉर्मेट में रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 23
url: /hi/java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

दस्तावेज़ों को PDF फ़ॉर्मेट में रेंडर करने के विकल्प प्रदान करता है।


PdfViewOptions क्लास अतिरिक्त सेटिंग्स और पैरामीटर को समाहित करती है।
जिसका उपयोग GroupDocs.Viewer घटक में दस्तावेज़ों को PDF प्रारूप में रेंडर करने को नियंत्रित करने के लिए किया जा सकता है।
विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/)।


उदाहरण उपयोग:

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | नए उदाहरण को प्रारंभ करता है |
PdfViewOptions
class।
|
|  | [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | नए उदाहरण को प्रारंभ करता है |
PdfViewOptions
class।
|
|  | [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | PdfViewOptions क्लास का नया इंस्टेंस आरंभ करता है। |
|
|  | [PdfViewOptions()](#PdfViewOptions--) | डिफ़ॉल्ट सेटिंग्स के साथ PdfViewOptions क्लास का नया इंस्टेंस आरंभ करता है। |
|
|  | [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | नए उदाहरण को प्रारंभ करता है |
PdfViewOptions
class।
|
|  | [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | नए उदाहरण को प्रारंभ करता है |
PdfViewOptions
class।
|
## Methods

| Method | विवरण |
| --- | --- |
|  | [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | विभिन्न विकल्पों के साथ अनुकूलन तकनीकों को लागू करके आउटपुट PDF फ़ाइल का आकार घटाएँ। |
|
|  | [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | विभिन्न विकल्पों के साथ अनुकूलन तकनीकों को लागू करके आउटपुट PDF फ़ाइल का आकार घटाएँ। |
|
|  | [getImageMaxWidth()](#getImageMaxWidth--) | आउटपुट छवि की अधिकतम चौड़ाई पिक्सेल में प्राप्त करता है। |
|
|  | [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | आउटपुट छवि की अधिकतम चौड़ाई पिक्सेल में सेट करता है। |
|
|  | [getImageMaxHeight()](#getImageMaxHeight--) | आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में प्राप्त करता है। |
|
|  | [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में सेट करता है। |
|
|  | [getImageWidth()](#getImageWidth--) | आउटपुट छवि की चौड़ाई पिक्सेल में प्राप्त करता है। |
|
|  | [setImageWidth(int imageWidth)](#setImageWidth-int-) | आउटपुट छवि की चौड़ाई को पिक्सेल में सेट करता है। |
|
|  | [getImageHeight()](#getImageHeight--) | आउटपुट छवि की ऊँचाई को पिक्सेल में प्राप्त करता है। |
|
|  | [setImageHeight(int imageHeight)](#setImageHeight-int-) | आउटपुट छवि की ऊँचाई को पिक्सेल में सेट करता है। |
|
|  | [getSecurity()](#getSecurity--) | आउटपुट PDF दस्तावेज़ के लिए सुरक्षा विकल्पों को प्राप्त करता है। |
|
|  | [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | आउटपुट PDF दस्तावेज़ के लिए सुरक्षा विकल्पों को सेट करता है। |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Words या Email दस्तावेज़ को सहेजने की प्रगति का अनुमान लगाने के लिए उपयोग किए जाने वाले कॉलबैक को प्राप्त करता है। |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Words या Email दस्तावेज़ को सहेजने की प्रगति का अनुमान लगाने के लिए उपयोग किए जाने वाले कॉलबैक को सेट करता है। |
|
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


नए उदाहरण को प्रारंभ करता है
PdfViewOptions
class।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


नए उदाहरण को प्रारंभ करता है
PdfViewOptions
class।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | आउटपुट फ़ाइल डेटा लिखने के लिए स्ट्रीम को इंस्टैंशिएट करने के लिए उपयोग की जाने वाली विधि। |
|
|  | releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | createFileStream विधि द्वारा बनाई गई स्ट्रीम को रिलीज़ करने के लिए उपयोग की जाने वाली विधि। |
|

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


PdfViewOptions क्लास का नया इंस्टेंस आरंभ करता है।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | आउटपुट फ़ाइल स्ट्रीम को बनाने और रिलीज़ करने के लिए विधियों को लागू करने वाला फ़ैक्टरी। |
|

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


डिफ़ॉल्ट सेटिंग्स के साथ PdfViewOptions क्लास का नया इंस्टेंस आरंभ करता है।


यह कंस्ट्रक्टर एक नया बनाता है
PdfViewOptions
ऑब्जेक्ट जिसमें आउटपुट फ़ाइल के लिए फ़ाइल पाथ फ़ॉर्मेट के रूप में "output.pdf" हो।
आउटपुट फ़ाइल एप्लिकेशन की वर्तमान कार्यशील डायरेक्टरी में रखी जाएगी।
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/)।


### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


नए उदाहरण को प्रारंभ करता है
PdfViewOptions
class।


यह कंस्ट्रक्टर एक नया बनाता है
PdfViewOptions
ऑब्जेक्ट जिसमें निर्दिष्ट
outputFilePath
पैरामीटर
आउटपुट PDF फ़ाइल के पाथ को दर्शाता है।
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | outputFilePath | java.lang.String | आउटपुट PDF फ़ाइल का पाथ। |
|

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


नए उदाहरण को प्रारंभ करता है
PdfViewOptions
class।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | outputFilePath | java.nio.file.Path | आउटपुट PDF फ़ाइल का पाथ। |
|

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


विभिन्न विकल्पों के साथ अनुकूलन तकनीकों को लागू करके आउटपुट PDF फ़ाइल का आकार घटाएँ।


यह विकल्प उन सभी इनपुट फ़ाइल फ़ॉर्मेट्स के लिए समर्थित है जो PDF में रूपांतरण के लिए समर्थित हैं: [Supported document formats](../https://docs.groupdocs.com/viewer/net/supported-document-formats/)
विवरण और कोड नमूनों के लिए, देखें यह [page](../https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) और इसके चाइल्ड।


**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.

### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


विभिन्न विकल्पों के साथ अनुकूलन तकनीकों को लागू करके आउटपुट PDF फ़ाइल का आकार घटाएँ।


यह विकल्प उन सभी इनपुट फ़ाइल फ़ॉर्मेट्स के लिए समर्थित है जो PDF में रूपांतरण के लिए समर्थित हैं: [Supported document formats](../https://docs.groupdocs.com/viewer/net/supported-document-formats/)
विवरण और कोड नमूनों के लिए, देखें यह [page](../https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) और इसके चाइल्ड।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | PdfOptimizationOptions ऑब्जेक्ट या null। |
|

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


आउटपुट छवि की अधिकतम चौड़ाई को पिक्सेल में प्राप्त करता है। यह पैरामीटर केवल एकल छवि को HTML में परिवर्तित करते समय लागू होता है।


इस प्रॉपर्टी का उपयोग अधिकतम आउटपुट छवि चौड़ाई (पिक्सेल में) सेट करने के लिए करें। GroupDocs.Viewer इस प्रॉपर्टी को एकल छवि को PDF में रेंडर करते समय लागू करता है। विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/)।
यदि आप प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी कर दी जाती है।


**Returns:**
int - आउटपुट छवि की अधिकतम चौड़ाई पिक्सेल में।

### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


एक आउटपुट छवि की अधिकतम चौड़ाई पिक्सेल में सेट करता है। यह पैरामीटर केवल एकल छवि को HTML में परिवर्तित करने पर लागू होता है।


इस प्रॉपर्टी का उपयोग अधिकतम आउटपुट छवि चौड़ाई (पिक्सेल में) सेट करने के लिए करें। GroupDocs.Viewer इस प्रॉपर्टी को एकल छवि को PDF में रेंडर करते समय लागू करता है। विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/)।
यदि आप प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी कर दी जाती है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | imageMaxWidth | int | आउटपुट छवि की अधिकतम चौड़ाई पिक्सेल में। |
|

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में प्राप्त करता है। यह पैरामीटर केवल एकल छवि को HTML में परिवर्तित करने पर लागू होता है।


इस प्रॉपर्टी का उपयोग करके अधिकतम आउटपुट छवि की ऊँचाई (पिक्सेल में) सेट करें। GroupDocs.Viewer इस प्रॉपर्टी को एकल छवि को PDF में रेंडर करते समय लागू करता है। विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
यदि आप प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी कर दी जाती है।


**Returns:**
int - आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में।

### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


एक आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में सेट करता है। यह पैरामीटर केवल एकल छवि को HTML में परिवर्तित करने पर लागू होता है।


इस प्रॉपर्टी का उपयोग करके अधिकतम आउटपुट छवि की ऊँचाई (पिक्सेल में) सेट करें। GroupDocs.Viewer इस प्रॉपर्टी को केवल एकल छवि को HTML में रेंडर करते समय लागू करता है। विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
यदि आप प्रॉपर्टी सेट करते हैं, तो यह प्रॉपर्टी अनदेखी कर दी जाती है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | imageMaxHeight | int | आउटपुट छवि की अधिकतम ऊँचाई पिक्सेल में। |
|

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


आउटपुट छवि की चौड़ाई पिक्सेल में प्राप्त करता है। यह पैरामीटर केवल एकल छवि को HTML में परिवर्तित करने पर लागू होता है।


इस प्रॉपर्टी का उपयोग करके आउटपुट छवि की चौड़ाई (पिक्सेल में) सेट करें। GroupDocs.Viewer इस प्रॉपर्टी को एकल छवि को PDF में रेंडर करते समय लागू करता है। विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
यदि आप इस प्रॉपर्टी को सेट करते हैं, तो यह प्रॉपर्टी अनदेखी कर दी जाती है।


**Returns:**
int - आउटपुट छवि की चौड़ाई पिक्सेल में।

### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


आउटपुट छवि की चौड़ाई पिक्सेल में सेट करता है। यह पैरामीटर केवल एकल छवि PDF को परिवर्तित करने पर लागू होता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | imageWidth | int | आउटपुट छवि की चौड़ाई पिक्सेल में। |
|

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


आउटपुट छवि की ऊँचाई पिक्सेल में प्राप्त करता है। यह पैरामीटर केवल एकल छवि को HTML में परिवर्तित करने पर लागू होता है।


इस प्रॉपर्टी का उपयोग करके आउटपुट छवि की ऊँचाई (पिक्सेल में) सेट करें। GroupDocs.Viewer इस प्रॉपर्टी को केवल एकल छवि को HTML में रेंडर करते समय लागू करता है। विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
यदि आप इस प्रॉपर्टी को सेट करते हैं, तो यह प्रॉपर्टी अनदेखी कर दी जाती है।


**Returns:**
int - आउटपुट छवि की ऊँचाई पिक्सेल में।

### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


आउटपुट छवि की ऊँचाई पिक्सेल में सेट करता है। यह पैरामीटर केवल एकल छवि को HTML में परिवर्तित करने पर लागू होता है।


इस प्रॉपर्टी का उपयोग करके आउटपुट छवि की ऊँचाई (पिक्सेल में) सेट करें। GroupDocs.Viewer इस प्रॉपर्टी को केवल एकल छवि को HTML में रेंडर करते समय लागू करता है। विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
यदि आप इस प्रॉपर्टी को सेट करते हैं, तो यह प्रॉपर्टी अनदेखी कर दी जाती है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | imageHeight | int | आउटपुट छवि की ऊँचाई पिक्सेल में। |
|

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


आउटपुट PDF दस्तावेज़ के लिए सुरक्षा विकल्पों को प्राप्त करता है।


विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.

### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


आउटपुट PDF दस्तावेज़ के लिए सुरक्षा विकल्पों को सेट करता है।


विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [Security](../../com.groupdocs.viewer.options/security) | आउटपुट PDF दस्तावेज़ के लिए सुरक्षा विकल्प। |
|

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Words या Email दस्तावेज़ को सहेजने की प्रगति का अनुमान लगाने के लिए उपयोग किए जाने वाले कॉलबैक को प्राप्त करता है।


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - दस्तावेज़ सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक।

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Words या Email दस्तावेज़ को सहेजने की प्रगति का अनुमान लगाने के लिए उपयोग किए जाने वाले कॉलबैक को सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | दस्तावेज़ सहेजने की प्रगति का अनुमान लगाने के लिए कॉलबैक। |
|

