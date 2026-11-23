---
title: "PdfOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "PDF दस्तावेज़ों को रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 22
url: /hi/java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

PDF दस्तावेज़ों को रेंडर करने के विकल्प प्रदान करता है।


PdfOptions क्लास विभिन्न सेटिंग्स और पैरामीटर को समाहित करती है जिन्हें उपयोग किया जा सकता है
GroupDocs.Viewer घटक में PDF दस्तावेज़ों के रेंडरिंग को नियंत्रित करने के लिए।
विवरण के लिए, देखें [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


उदाहरण उपयोग:

````

 PdfOptions options = new PdfOptions();
 options.setDisableCharsGrouping(true);
 options.setRenderTextAsImage(true);
 options.setEnableFontHinting(true);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setPdfOptions(options);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | का नया इंस्टेंस प्रारंभ करता है |
PdfOptions
class।
|
## Methods

| Method | विवरण |
| --- | --- |
|  | [isDisableCopyProtection()](#isDisableCopyProtection--) | HTML में रेंडरिंग के समय कंटेंट कॉपी प्रोटेक्शन को बंद करता है। |
|
|  | [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | HTML में रेंडरिंग के समय कंटेंट कॉपी प्रोटेक्शन को बंद करता है। |
|
|  | [isRenderTextAsImage()](#isRenderTextAsImage--) | निर्धारित करता है कि स्रोत से टेक्स्ट HTML में छवि के रूप में रेंडर किया जाता है या नहीं। |
|
|  | [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | सेट करता है कि स्रोत से टेक्स्ट HTML में छवि के रूप में रेंडर किया जाए या नहीं। |
|
|  | [isDisableCharsGrouping()](#isDisableCharsGrouping--) | पेज रेंडरिंग के दौरान कैरेक्टर पोजिशनिंग में अधिकतम सटीकता बनाए रखने के लिए जांचता है कि कैरेक्टर ग्रुपिंग निष्क्रिय है या नहीं। |
|
|  | [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | पेज रेंडरिंग के दौरान कैरेक्टर पोजिशनिंग में अधिकतम सटीकता सुनिश्चित करने के लिए कैरेक्टर ग्रुपिंग को निष्क्रिय करने का विकल्प सेट करता है। |
|
|  | [isEnableLayeredRendering()](#isEnableLayeredRendering--) | HTML में रेंडरिंग के समय यह जांचता है कि टेक्स्ट और ग्राफिक्स का रेंडरिंग मूल PDF दस्तावेज़ में z-ऑर्डर का पालन करना चाहिए या नहीं। |
|
|  | [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | HTML में रेंडर करते समय मूल PDF दस्तावेज़ में z‑order के अनुसार पाठ और ग्राफ़िक्स के रेंडरिंग को सक्षम या अक्षम करता है। |
|
|  | [isEnableFontHinting()](#isEnableFontHinting--) | निर्धारित करता है कि फ़ॉन्ट हिंटिंग सक्षम है या नहीं। |
|
|  | [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | फ़ॉन्ट हिंटिंग को सक्षम करता है। |
|
|  | [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | स्रोत PDF दस्तावेज़ में पृष्ठ आकार के समान पिक्सेल आकार के साथ पृष्ठों के रेंडरिंग को सक्षम करता है। |
|
|  | [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | स्रोत PDF दस्तावेज़ में पृष्ठ आकार के समान पिक्सेल आकार के साथ पृष्ठों के रेंडरिंग को सक्षम करता है। |
|
|  | [getImageQuality()](#getImageQuality--) | HTML में रेंडर करते समय इमेज संसाधनों के लिए आउटपुट इमेज क्वालिटी प्राप्त करता है। |
|
|  | [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | HTML में रेंडर करते समय इमेज संसाधनों के लिए आउटपुट इमेज क्वालिटी सेट करता है। |
|
|  | [isFixedLayout()](#isFixedLayout--) | PDF एक स्थिर फ़ॉर्मेट है, इसलिए सभी तत्वों का पृष्ठ पर एक विशिष्ट स्थान होता है। |
|
|  | [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF एक स्थिर फ़ॉर्मेट है, इसलिए सभी तत्वों का पृष्ठ पर एक विशिष्ट स्थान होता है। |
|
|  | [isWrapImagesInSvg()](#isWrapImagesInSvg--) | आउटपुट गुणवत्ता सुधारने के लिए प्रत्येक इमेज को आउटपुट HTML दस्तावेज़ में SVG टैग में लपेटने के लिए इस विकल्प को सक्षम करें। |
|
|  | [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | आउटपुट गुणवत्ता सुधारने के लिए प्रत्येक इमेज को आउटपुट HTML दस्तावेज़ में SVG टैग में लपेटने के लिए इस विकल्प को सक्षम करें। |
|
|  | [isAnalyzeFonts()](#isAnalyzeFonts--) | पाठ में सभी अक्षरों को प्रदर्शित करने के लिए आवश्यकतानुसार फ़ॉन्ट्स को बदलता है। |
|
|  | [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | पाठ में सभी अक्षरों को प्रदर्शित करने के लिए आवश्यकतानुसार फ़ॉन्ट्स को बदलता है। |
|
|  | [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | वर्तमान XPS/OXPS दस्तावेज़ में सभी फ़ॉन्ट्स के लिए किसी भी लाइसेंस प्रतिबंध को अक्षम करें। |
|
|  | [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | वर्तमान XPS/OXPS दस्तावेज़ में सभी फ़ॉन्ट्स के लिए लाइसेंस प्रतिबंध को अक्षम करने के लिए फ़्लैग सेट करें। |
|
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


का नया इंस्टेंस प्रारंभ करता है
PdfOptions
class।


### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


HTML में रेंडरिंग के समय कंटेंट कॉपी प्रोटेक्शन को बंद करता है।


जब PDF फ़ाइलों को टेक्स्ट और इमेज को HTML में कॉपी करने से बचाने वाले प्रोटेक्शन के साथ रेंडर किया जाता है, तो GroupDocs.Viewer HTML BODY टैग में एक 'inert' HTML एट्रिब्यूट जोड़ता है।
इस विकल्प का डिफ़ॉल्ट मान है
false
.


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection)।


**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


HTML में रेंडरिंग के समय कंटेंट कॉपी प्रोटेक्शन को बंद करता है।


जब PDF फ़ाइलों को टेक्स्ट और इमेज को HTML में कॉपी करने से बचाने वाले प्रोटेक्शन के साथ रेंडर किया जाता है, तो GroupDocs.Viewer HTML BODY टैग में एक 'inert' HTML एट्रिब्यूट जोड़ता है।
इस विकल्प का डिफ़ॉल्ट मान है
false
.


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


निर्धारित करता है कि स्रोत से टेक्स्ट HTML में छवि के रूप में रेंडर किया जाता है या नहीं।


जब इस विकल्प को सेट किया जाता है
true
, तो टेक्स्ट आउटपुट HTML में एक इमेज के रूप में रेंडर किया जाता है।
टेक्स्ट को चयन योग्य न बनाने या अक्षर रेंडरिंग को ठीक करने और HTML को PDF जैसा दिखाने के लिए इस विकल्प को सक्षम करें।
HTML में रेंडर करते समय यह विकल्प समर्थित है।


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  यदि टेक्स्ट HTML में इमेज के रूप में रेंडर किया जाता है,  false  अन्यथा।

### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


सेट करता है कि स्रोत से टेक्स्ट HTML में छवि के रूप में रेंडर किया जाए या नहीं।


जब इस विकल्प को सेट किया जाता है
true
, तो टेक्स्ट आउटपुट HTML में एक इमेज के रूप में रेंडर किया जाता है।
टेक्स्ट को चयन योग्य न बनाने या अक्षर रेंडरिंग को ठीक करने और HTML को PDF जैसा दिखाने के लिए इस विकल्प को सक्षम करें।
HTML में रेंडर करते समय यह विकल्प समर्थित है।


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | renderTextAsImage | boolean | true  को HTML में टेक्स्ट को इमेज के रूप में रेंडर करने के लिए,  false  अन्यथा। |
|

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


पेज रेंडरिंग के दौरान कैरेक्टर पोजिशनिंग में अधिकतम सटीकता बनाए रखने के लिए जांचता है कि कैरेक्टर ग्रुपिंग निष्क्रिय है या नहीं।
जब यह विकल्प सक्षम किया जाता है, तो अक्षरों को बिना किसी समूहबद्धता के रेंडर किया जाता है, जो अधिकतम सटीकता सुनिश्चित करता है।


***Note:** By default, character grouping is enabled.*
PDF फ़ाइलों को परिवर्तित करते समय, GroupDocs.Viewer व्यक्तिगत अक्षरों को शब्दों में समूहित करता है ताकि रेंडरिंग प्रदर्शन बेहतर हो। यदि आपके दस्तावेज़ में चित्रलिपि या विशेष प्रतीक शामिल हैं, तो अधिक सटीक लेआउट सुनिश्चित करने के लिए आप अक्षर समूहबद्धता को प्रतिबंधित करना चाह सकते हैं। डिफ़ॉल्ट मान false है।
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping)।


**Returns:**
boolean -  true  यदि अक्षर समूहबद्धता अक्षम है,  false  अन्यथा।

### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


पेज रेंडरिंग के दौरान कैरेक्टर पोजिशनिंग में अधिकतम सटीकता सुनिश्चित करने के लिए कैरेक्टर ग्रुपिंग को निष्क्रिय करने का विकल्प सेट करता है।
जब इस विकल्प को मान सेट करके सक्षम किया जाता है
true
, अक्षर समूहबद्धता अक्षम हो जाती है, जो अधिकतम सटीकता सुनिश्चित करती है।


***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.*
PDF फ़ाइलों को परिवर्तित करते समय, GroupDocs.Viewer व्यक्तिगत अक्षरों को शब्दों में समूहित करता है ताकि रेंडरिंग प्रदर्शन बेहतर हो। यदि आपके दस्तावेज़ में चित्रलिपि या विशेष प्रतीक शामिल हैं, तो अधिक सटीक लेआउट सुनिश्चित करने के लिए आप अक्षर समूहबद्धता को प्रतिबंधित करना चाह सकते हैं। डिफ़ॉल्ट मान false है।
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | boolean | true  अक्षर समूहबद्धता को अक्षम करने के लिए,  false  इसे सक्षम करने के लिए। |
|

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


HTML में रेंडरिंग के समय यह जांचता है कि टेक्स्ट और ग्राफिक्स का रेंडरिंग मूल PDF दस्तावेज़ में z-ऑर्डर का पालन करना चाहिए या नहीं।
जब इस विकल्प को लौटाकर सक्षम किया जाता है
true
, टेक्स्ट और ग्राफ़िक्स मूल PDF दस्तावेज़ में उनके z-क्रम के अनुसार रेंडर होते हैं।


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
डिफ़ॉल्ट रूप से, GroupDocs.Veiewer टेक्स्ट और ग्राफ़िक्स को HTML में एकल लेयर के रूप में रेंडर करता है। यह विकल्प आपको वस्तुओं को स्रोत फ़ाइल के समान क्रम में व्यवस्थित करने देता है। डिफ़ॉल्ट मान false है।
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering)।


**Returns:**
boolean -  true  यदि लेयरड रेंडरिंग सक्षम है,  false  अन्यथा।

### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


HTML में रेंडर करते समय मूल PDF दस्तावेज़ में z‑order के अनुसार पाठ और ग्राफ़िक्स के रेंडरिंग को सक्षम या अक्षम करता है।


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
डिफ़ॉल्ट रूप से, GroupDocs.Veiewer टेक्स्ट और ग्राफ़िक्स को HTML में एकल लेयर के रूप में रेंडर करता है। यह विकल्प आपको वस्तुओं को स्रोत फ़ाइल के समान क्रम में व्यवस्थित करने देता है। डिफ़ॉल्ट मान false है।
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | boolean | true  लेयरड रेंडरिंग को सक्षम करने के लिए,  false  इसे अक्षम करने के लिए। |
|

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


निर्धारित करता है कि फ़ॉन्ट हिंटिंग सक्षम है या नहीं। फ़ॉन्ट हिंटिंग आउटलाइन फ़ॉन्ट के प्रदर्शन को समायोजित करती है।
यह विकल्प केवल TrueType (TTF) फ़ॉन्ट्स के लिए समर्थित है जब स्रोत दस्तावेज़ में उपयोग किया जाता है।


***Note:** This option is supported when rendering into PNG or JPG formats.*
फ़ॉन्ट हिंटिंग आउटलाइन फ़ॉन्ट के प्रदर्शित होने के तरीके को समायोजित करती है। यह केवल स्रोत दस्तावेज़ में उपयोग किए गए TTF फ़ॉन्ट्स पर लागू होती है। यह विकल्प PNG या JPG फ़ॉर्मेट में रेंडरिंग के लिए उपलब्ध है। डिफ़ॉल्ट मान false है।
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting)।


**Returns:**
boolean -  true  यदि फ़ॉन्ट हिंटिंग सक्षम है,  false  अन्यथा।

### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


फ़ॉन्ट हिंटिंग को सक्षम करता है। फ़ॉन्ट हिंटिंग आउटलाइन फ़ॉन्ट के प्रदर्शन को समायोजित करती है और केवल TrueType (TTF) फ़ॉन्ट्स के लिए समर्थित है जब स्रोत दस्तावेज़ में उपयोग किया जाता है।


***Note:** This option is supported when rendering into PNG or JPG formats.*
फ़ॉन्ट हिंटिंग आउटलाइन फ़ॉन्ट के प्रदर्शित होने के तरीके को समायोजित करती है। यह केवल स्रोत दस्तावेज़ में उपयोग किए गए TTF फ़ॉन्ट्स पर लागू होती है। यह विकल्प PNG या JPG फ़ॉर्मेट में रेंडरिंग के लिए उपलब्ध है। डिफ़ॉल्ट मान false है।
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | boolean | true  फ़ॉन्ट हिंटिंग को सक्षम करने के लिए,  false  इसे अक्षम करने के लिए। |
|

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


स्रोत PDF दस्तावेज़ में पृष्ठ आकार के समान पिक्सेल आकार के साथ पृष्ठों के रेंडरिंग को सक्षम करता है।


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
डिफ़ॉल्ट रूप से, GroupDocs.Viewer बेहतर रेंडरिंग गुणवत्ता के लिए आउटपुट इमेज पेज आकार की गणना करता है। इस विकल्प को सक्षम करें ताकि आउटपुट पेजों का आकार स्रोत PDF दस्तावेज़ के पेज आकार (पिक्सेल में) के समान हो। डिफ़ॉल्ट मान false है।
यह विकल्प PNG या JPG फ़ॉर्मेट में रेंडरिंग के लिए उपलब्ध है।
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages)।


**Returns:**
boolean -  true  यदि विकल्प सक्षम है,  false  अन्यथा।

### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


स्रोत PDF दस्तावेज़ में पृष्ठ आकार के समान पिक्सेल आकार के साथ पृष्ठों के रेंडरिंग को सक्षम करता है।


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
डिफ़ॉल्ट रूप से, GroupDocs.Viewer बेहतर रेंडरिंग गुणवत्ता के लिए आउटपुट इमेज पेज आकार की गणना करता है। इस विकल्प को सक्षम करें ताकि आउटपुट पेजों का आकार स्रोत PDF दस्तावेज़ के पेज आकार (पिक्सेल में) के समान हो। डिफ़ॉल्ट मान false है।
यह विकल्प PNG या JPG फ़ॉर्मेट में रेंडरिंग के लिए उपलब्ध है।
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | renderOriginalPageSize | boolean | true  मूल पृष्ठ आकार के साथ रेंडरिंग सक्षम करने के लिए,  false  अन्यथा। |
|

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


HTML में रेंडरिंग करते समय इमेज संसाधनों के लिए आउटपुट इमेज गुणवत्ता प्राप्त करता है। डिफ़ॉल्ट मान Low है।


जब यह विकल्प true पर सेट किया जाता है, तो GroupDocs.Viewer HTML आउटपुट में टेक्स्ट को इमेज के रूप में रेंडर करता है। इससे टेक्स्ट चयन योग्य नहीं रहता और कैरेक्टर रेंडरिंग में सुधार होता है, जिससे HTML में PDF जैसा रूप मिलता है। डिफ़ॉल्ट मान false है।
यह विकल्प HTML में रेंडरिंग के लिए उपलब्ध है।
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image)।


**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.

### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


HTML में रेंडरिंग करते समय इमेज संसाधनों के लिए आउटपुट इमेज गुणवत्ता सेट करता है। डिफ़ॉल्ट मान Low है।


जब यह विकल्प true पर सेट किया जाता है, तो GroupDocs.Viewer HTML आउटपुट में टेक्स्ट को इमेज के रूप में रेंडर करता है। इससे टेक्स्ट चयन योग्य नहीं रहता और कैरेक्टर रेंडरिंग में सुधार होता है, जिससे HTML में PDF जैसा रूप मिलता है। डिफ़ॉल्ट मान false है।
यह विकल्प HTML में रेंडरिंग के लिए उपलब्ध है।
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | HTML में रेंडरिंग करते समय इमेज संसाधनों के लिए आउटपुट इमेज गुणवत्ता। |
|

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF एक स्थिर फ़ॉर्मेट है, इसलिए सभी तत्वों का पृष्ठ पर एक विशिष्ट स्थान होता है।
यह सुनिश्चित करने के लिए कि आउटपुट HTML स्रोत PDF जैसा ही दिखे, दस्तावेज़ डिफ़ॉल्ट रूप से फिक्स्ड लेआउट के साथ HTML में रेंडर किए जाते हैं।
फिक्स्ड लेआउट के साथ रेंडरिंग करने पर आउटपुट HTML का आकार स्थिर रहता है, इसलिए तत्व विंडो के आकार की परवाह किए बिना उसी स्थान पर रहते हैं।
फ्लुइड लेआउट के साथ HTML में रेंडर करने के लिए इस प्रॉपर्टी को false सेट करें।


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
PDF और EPUB दस्तावेज़ प्रारंभ में स्रोत दस्तावेज़ की उपस्थिति बनाए रखने के लिए फिक्स्ड लेआउट के साथ HTML में रेंडर किए जाते हैं। यह फिक्स्ड लेआउट का अर्थ है कि सभी HTML तत्व एक निर्धारित आकार वाले कंटेनर के भीतर सटीक स्थितियों में होते हैं। ब्राउज़र विंडो का आकार बदलने से दस्तावेज़ में तत्वों की स्थिति और आकार प्रभावित नहीं होते।
यह विकल्प केवल HTML में रेंडरिंग के समय उपलब्ध है। डिफ़ॉल्ट मान true है। फ्लुइड लेआउट के साथ रेंडर करने के लिए, इस प्रॉपर्टी को false सेट करें।


उदाहरण उपयोग:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Returns:**
boolean - यदि यह फिक्स्ड लेआउट है तो true

### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF एक स्थिर फ़ॉर्मेट है, इसलिए सभी तत्वों का पृष्ठ पर एक विशिष्ट स्थान होता है।
यह सुनिश्चित करने के लिए कि आउटपुट HTML स्रोत PDF जैसा ही दिखे, दस्तावेज़ डिफ़ॉल्ट रूप से फिक्स्ड लेआउट के साथ HTML में रेंडर किए जाते हैं।
फिक्स्ड लेआउट के साथ रेंडरिंग करने पर आउटपुट HTML का आकार स्थिर रहता है, इसलिए तत्व विंडो के आकार की परवाह किए बिना उसी स्थान पर रहते हैं।
फ्लुइड लेआउट के साथ HTML में रेंडर करने के लिए इस प्रॉपर्टी को false सेट करें।


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
PDF और EPUB दस्तावेज़ प्रारंभ में स्रोत दस्तावेज़ की उपस्थिति बनाए रखने के लिए फिक्स्ड लेआउट के साथ HTML में रेंडर किए जाते हैं। यह फिक्स्ड लेआउट का अर्थ है कि सभी HTML तत्व एक निर्धारित आकार वाले कंटेनर के भीतर सटीक स्थितियों में होते हैं। ब्राउज़र विंडो का आकार बदलने से दस्तावेज़ में तत्वों की स्थिति और आकार प्रभावित नहीं होते।
यह विकल्प केवल HTML में रेंडरिंग के समय उपलब्ध है। डिफ़ॉल्ट मान true है। फ्लुइड लेआउट के साथ रेंडर करने के लिए, इस प्रॉपर्टी को false सेट करें।


उदाहरण उपयोग:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fixedLayout | boolean | यदि यह फिक्स्ड लेआउट है तो true |
|

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


आउटपुट गुणवत्ता सुधारने के लिए प्रत्येक इमेज को आउटपुट HTML दस्तावेज़ में SVG टैग में लपेटने के लिए इस विकल्प को सक्षम करें।


यह विकल्प तब समर्थित है जब [PDF and Page Layout file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) को एम्बेडेड और एक्सटर्नल रिसोर्सेज़ के साथ HTML में रेंडर किया जाता है।


डिफ़ॉल्ट रूप से, जब PDF और Page Layout फ़ाइलों में रेंडर किया जाता है, सभी इमेज एक ही PNG इमेज के रूप में रेंडर होते हैं। रेंडर किया गया PNG इमेज आउटपुट HTML दस्तावेज़ के बैकग्राउंड के रूप में उपयोग किया जाता है।


और अधिक जानें:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Returns:**
boolean - यदि इमेजेस SVG में रैप की गई हैं तो true, अन्यथा false।

### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


आउटपुट गुणवत्ता सुधारने के लिए प्रत्येक इमेज को आउटपुट HTML दस्तावेज़ में SVG टैग में लपेटने के लिए इस विकल्प को सक्षम करें।


यह विकल्प तब समर्थित है जब [PDF and Page Layout file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) को एम्बेडेड और एक्सटर्नल रिसोर्सेज़ के साथ HTML में रेंडर किया जाता है।


डिफ़ॉल्ट रूप से, जब PDF और Page Layout फ़ाइलों में रेंडर किया जाता है, सभी इमेज एक ही PNG इमेज के रूप में रेंडर होते हैं। रेंडर किया गया PNG इमेज आउटपुट HTML दस्तावेज़ के बैकग्राउंड के रूप में उपयोग किया जाता है।


और अधिक जानें:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | wrapImagesInSvg | boolean | true  यदि इमेजेस को SVG में रैप किया जाना चाहिए,  false  अन्यथा। |
|

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


पाठ में सभी अक्षरों को प्रदर्शित करने के लिए आवश्यकतानुसार फ़ॉन्ट्स को बदलता है।


**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


पाठ में सभी अक्षरों को प्रदर्शित करने के लिए आवश्यकतानुसार फ़ॉन्ट्स को बदलता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | analyzeFonts | boolean | true यदि फ़ॉन्ट्स प्रदर्शित किए जाने चाहिए, false अन्यथा। |
|

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


वर्तमान XPS/OXPS दस्तावेज़ में सभी फ़ॉन्ट्स के लिए किसी भी लाइसेंस प्रतिबंध को अक्षम करें।


फ़ॉन्ट के साथ कई ऑपरेशन्स को निष्पादित नहीं किया जा सकता यदि ये ऑपरेशन्स इस फ़ॉन्ट के लाइसेंस द्वारा प्रतिबंधित हों।
उदाहरण के लिए, कुछ फ़ॉन्ट को PDF दस्तावेज़ में एम्बेड नहीं किया जा सकता यदि लाइसेंस नियम इस फ़ॉन्ट के लिए एम्बेडिंग को अक्षम करते हैं।
इस फ़्लैग का उपयोग करते समय सावधान रहें। जब यह सेट किया जाता है, तो इसका मतलब है कि जो व्यक्ति इस फ़्लैग को सेट करता है वह सभी जिम्मेदारी लेता है
संभव लाइसेंस/कानून उल्लंघनों के लिए स्वयं पर। इसलिए वे इसे अपने जोखिम पर लेते हैं। इसे उपयोग करने की दृढ़ता से सिफ़ारिश की जाती है
यह फ़्लैग केवल तब उपयोग करें जब आप पूरी तरह आश्वस्त हों कि आप कॉपीराइट कानून का उल्लंघन नहीं कर रहे हैं। डिफ़ॉल्ट रूप से यह false है।
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files)।


उदाहरण उपयोग:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


वर्तमान XPS/OXPS दस्तावेज़ में सभी फ़ॉन्ट्स के लिए लाइसेंस प्रतिबंध को अक्षम करने के लिए फ़्लैग सेट करें।


फ़ॉन्ट के साथ कई ऑपरेशन्स को निष्पादित नहीं किया जा सकता यदि ये ऑपरेशन्स इस फ़ॉन्ट के लाइसेंस द्वारा प्रतिबंधित हों।
उदाहरण के लिए, कुछ फ़ॉन्ट को PDF दस्तावेज़ में एम्बेड नहीं किया जा सकता यदि लाइसेंस नियम इस फ़ॉन्ट के लिए एम्बेडिंग को अक्षम करते हैं।
इस फ़्लैग का उपयोग करते समय सावधान रहें। जब यह सेट किया जाता है, तो इसका मतलब है कि जो व्यक्ति इस फ़्लैग को सेट करता है वह सभी जिम्मेदारी लेता है
संभव लाइसेंस/कानून उल्लंघनों के लिए स्वयं पर। इसलिए वे इसे अपने जोखिम पर लेते हैं। इसे उपयोग करने की दृढ़ता से सिफ़ारिश की जाती है
यह फ़्लैग केवल तब उपयोग करें जब आप पूरी तरह आश्वस्त हों कि आप कॉपीराइट कानून का उल्लंघन नहीं कर रहे हैं। डिफ़ॉल्ट रूप से यह false है।
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files)।


उदाहरण उपयोग:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

