---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "आउटपुट PDF फ़ाइल पर लागू करने के लिए PDF अनुकूलन विकल्प निर्दिष्ट करने हेतु इस क्लास का उपयोग करें।"
type: docs
weight: 21
url: /hi/java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

आउटपुट PDF फ़ाइल पर लागू करने के लिए PDF अनुकूलन विकल्प निर्दिष्ट करने हेतु इस क्लास का उपयोग करें।


इन अनुकूलन विकल्पों का समर्थन उन सभी इनपुट फ़ाइल फ़ॉर्मेट्स के लिए किया जाता है जो PDF में निर्यात के लिए समर्थित हैं।
विवरण और कोड नमूनों के लिए, इस [पृष्ठ](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) और इसके उपपृष्ठ देखें।


उदाहरण उपयोग:

````

 try (Viewer viewer = new Viewer("sample.docx")) {
     PdfViewOptions viewOptions = new PdfViewOptions();
     viewOptions.setPdfOptimizationOptions(new PdfOptimizationOptions());
     viewOptions.getPdfOptimizationOptions().setLinearize(true);
     viewOptions.getPdfOptimizationOptions().setRemoveAnnotations(true);
     viewOptions.getPdfOptimizationOptions().setRemoveFormFields(true);
     viewOptions.getPdfOptimizationOptions().setConvertToGrayScale(true);
     viewOptions.getPdfOptimizationOptions().setSubsetFonts(true);
     viewOptions.getPdfOptimizationOptions().setCompressImages(true);
     viewOptions.getPdfOptimizationOptions().setImageQuality(50);
     viewOptions.getPdfOptimizationOptions().setResizeImages(true);
     viewOptions.getPdfOptimizationOptions().setMaxResolution(50);
     viewOptions.getPdfOptimizationOptions().setRemovePrivateInfo(true);
     viewOptions.getPdfOptimizationOptions().setUnembedFonts(true);
     viewOptions.getPdfOptimizationOptions().setLinkDuplicateStreams(true);
     viewOptions.getPdfOptimizationOptions().setAllowReusePageContent(true);

     viewer.view(viewOptions);
 }
 
````


## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | MaxResolution विकल्प का डिफ़ॉल्ट मान 300 और ImageQuality विकल्प का डिफ़ॉल्ट मान 100 सेट करता है। |
|
## Methods

| Method | विवरण |
| --- | --- |
|  | [isLinearize()](#isLinearize--) | वेब ब्राउज़र के साथ ऑनलाइन देखने के लिए आउटपुट PDF फ़ाइल का अनुकूलन सक्षम करता है। |
|
|  | [setLinearize(boolean linearize)](#setLinearize-boolean-) | वेब ब्राउज़र के साथ ऑनलाइन ब्राउज़िंग के लिए आउटपुट PDF को अनुकूलित करना है या नहीं, सेट करता है। |
|
|  | [isRemoveAnnotations()](#isRemoveAnnotations--) | जब एनोटेशन अनावश्यक हों तो उन्हें हटाया जा सकता है। |
|
|  | [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | PDF से अनावश्यक एनोटेशन हटाने हैं या नहीं, सेट करता है। |
|
|  | [isRemoveFormFields()](#isRemoveFormFields--) | यदि PDF दस्तावेज़ में AcroForms हैं, तो हम फ़ॉर्म फ़ील्ड को फ्लैट करके फ़ाइल आकार कम करने का प्रयास कर सकते हैं। |
|
|  | [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | PDF से फ़ॉर्म फ़ील्ड हटाने हैं या नहीं, सेट करता है। |
|
|  | [isConvertToGrayScale()](#isConvertToGrayScale--) | PDF फ़ाइल टेक्स्ट, इमेज, अटैचमेंट, एनोटेशन, ग्राफ़ और अन्य ऑब्जेक्ट्स से बनी होती है। |
|
|  | [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | PDF को ग्रेस्केल में बदलना है या नहीं, सेट करता है। |
|
|  | [isSubsetFonts()](#isSubsetFonts--) | पृष्ठ पर टेक्स्ट प्रदर्शित करने के लिए उपयोग किए जाने वाले प्रत्येक फ़ॉन्ट में फ़ॉन्ट अक्षरों के लिए ग्लिफ़ का सेट होता है। |
|
|  | [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | PDF में फ़ॉन्ट को सबसेट करना है या नहीं, सेट करता है। |
|
|  | [isCompressImages()](#isCompressImages--) | यदि स्रोत PDF फ़ाइल में इमेज हैं, तो इमेज को संकुचित करने और उनकी गुणवत्ता सेट करने पर विचार करें। |
|
|  | [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | PDF में इमेज को संकुचित करना है या नहीं, सेट करता है। |
|
|  | [getImageQuality()](#getImageQuality--) | यदि स्रोत PDF फ़ाइल में इमेज हैं, तो इमेज को संकुचित करने और उनकी गुणवत्ता सेट करने पर विचार करें। |
|
|  | [setImageQuality(int imageQuality)](#setImageQuality-int-) | PDF में इमेज को संकुचित करने के लिए इमेज की गुणवत्ता सेट करता है। |
|
|  | [isResizeImages()](#isResizeImages--) | CompressImages विकल्प के साथ उपयोग करके इमेज को कम रिज़ॉल्यूशन के साथ री-साइज़ किया जा सकता है। |
|
|  | [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | PDF में छवियों को पुनः आकार देने की सेटिंग निर्धारित करता है। |
|
|  | [getMaxResolution()](#getMaxResolution--) | CompressImages विकल्प के साथ उपयोग करके इमेज को कम रिज़ॉल्यूशन के साथ री-साइज़ किया जा सकता है। |
|
|  | [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | PDF में छवियों को पुनः आकार देने के लिए अधिकतम रिज़ॉल्यूशन सेट करता है। |
|
|  | [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | छोटे आउटपुट फ़ाइल आकार के लिए Excel स्प्रेडशीट की बॉर्डर लाइनों और फ़ॉन्ट्स को अनुकूलित करें। |
|
|  | [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | PDF में स्प्रेडशीट को अनुकूलित करने की सेटिंग निर्धारित करता है। |
|
|  | [isRemovePrivateInfo()](#isRemovePrivateInfo--) | यदि true सेट किया गया हो तो निजी जानकारी (पृष्ठ भाग जानकारी) हटाएँ। |
|
|  | [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | PDF से निजी जानकारी हटाने की सेटिंग निर्धारित करता है। |
|
|  | [isUnembedFonts()](#isUnembedFonts--) | यदि दस्तावेज़ एम्बेडेड फ़ॉन्ट्स का उपयोग करता है, तो इसका मतलब है कि सभी फ़ॉन्ट डेटा दस्तावेज़ में रखा गया है। |
|
|  | [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | PDF में एम्बेडेड फ़ॉन्ट्स को अनएंबेड करने की सेटिंग निर्धारित करता है। |
|
|  | [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | कभी-कभी एक दस्तावेज़ में कई समान संसाधन स्ट्रीम्स होते हैं (उदाहरण के लिए छवियाँ)। |
|
|  | [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | PDF में डुप्लिकेट स्ट्रीम्स को लिंक करने की सेटिंग निर्धारित करता है। |
|
|  | [isAllowReusePageContent()](#isAllowReusePageContent--) | यदि यह प्रॉपर्टी true पर सेट है, तो समान पृष्ठों के लिए दस्तावेज़ को अनुकूलित करते समय पृष्ठ सामग्री को पुनः उपयोग किया जाएगा। |
|
|  | [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | PDF में पृष्ठ सामग्री को पुनः उपयोग करने की अनुमति देने की सेटिंग निर्धारित करता है। |
|
|  | [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | कभी-कभी एक दस्तावेज़ में अप्रयुक्त संसाधन स्ट्रीम्स होते हैं। |
|
|  | [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | PDF से अप्रयुक्त स्ट्रीम्स को हटाने की सेटिंग निर्धारित करता है। |
|
|  | [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | एक PDF दस्तावेज़ कभी-कभी उन PDF ऑब्जेक्ट्स को शामिल करता है जो संदर्भित नहीं होते |
दस्तावेज़ में किसी अन्य ऑब्जेक्ट से।
|
|  | [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | PDF से अप्रयुक्त ऑब्जेक्ट्स को हटाने की सेटिंग निर्धारित करता है। |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


MaxResolution विकल्प का डिफ़ॉल्ट मान 300 और ImageQuality विकल्प का डिफ़ॉल्ट मान 100 सेट करता है।


विवरण और कोड नमूनों के लिए, इस [पृष्ठ](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) और इसके उपपृष्ठ देखें।


### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


वेब ब्राउज़र के साथ ऑनलाइन देखने के लिए आउटपुट PDF फ़ाइल का अनुकूलन सक्षम करता है।


कोड उदाहरण के लिए, इस [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/) को देखें।


**Returns:**
boolean -  true  यदि आउटपुट PDF ऑनलाइन ब्राउज़िंग के लिए अनुकूलित है,  false  अन्यथा।

### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


वेब ब्राउज़र के साथ ऑनलाइन ब्राउज़िंग के लिए आउटपुट PDF को अनुकूलित करना है या नहीं, सेट करता है।


कोड उदाहरण के लिए, इस [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/) को देखें।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | linearize | boolean | true  आउटपुट PDF को ऑनलाइन ब्राउज़िंग के लिए अनुकूलित करने के लिए,  false  अन्यथा। |
|

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


एनोटेशन को तब हटाया जा सकता है जब वे अनावश्यक हों। जब वे आवश्यक हों लेकिन अतिरिक्त संपादन की आवश्यकता न हो, तो उन्हें फ्लैट किया जा सकता है। इससे फ़ाइल आकार कम होगा।


***Note:** The default value is 
false
.*
कोड उदाहरण के लिए, इस [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/) को देखें।


**Returns:**
boolean -  true  यदि एनोटेशन हटाए गए हैं,  false  अन्यथा।

### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


PDF से अनावश्यक एनोटेशन हटाने हैं या नहीं, सेट करता है।


***Note:** The default value is 
false
.*
कोड उदाहरण के लिए, इस [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/) को देखें।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | removeAnnotations | boolean | true  अनावश्यक एनोटेशन हटाने के लिए,  false  अन्यथा। |
|

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


यदि PDF दस्तावेज़ में AcroForms हैं, तो हम फ़ॉर्म फ़ील्ड को फ्लैट करके फ़ाइल आकार कम करने का प्रयास कर सकते हैं।


***Note:** The default value is 
false
.*
कोड उदाहरण के लिए, देखें यह [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/).


**Returns:**
boolean -  true  यदि फ़ॉर्म फ़ील्ड हटाए गए हैं,  false  अन्यथा।

### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


PDF से फ़ॉर्म फ़ील्ड हटाने हैं या नहीं, सेट करता है।


***Note:** The default value is 
false
.*
कोड उदाहरण के लिए, देखें यह [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | removeFormFields | boolean | true  फ़ॉर्म फ़ील्ड हटाने के लिए,  false  अन्यथा। |
|

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


PDF फ़ाइल टेक्स्ट, इमेज, अटैचमेंट, एनोटेशन, ग्राफ़ और अन्य ऑब्जेक्ट्स से बनी होती है।
आपको एक आवश्यकता मिल सकती है कि PDF को RGB कलरस्पेस से ग्रेस्केल में बदलें ताकि उन PDF फ़ाइलों को प्रिंट करते समय यह तेज़ हो।
जब फ़ाइल को ग्रेस्केल में बदला जाता है, तो दस्तावेज़ का आकार भी घट जाता है, लेकिन इस परिवर्तन के साथ दस्तावेज़ की गुणवत्ता घट सकती है।
वर्तमान में, यह सुविधा Adobe Acrobat की प्री-फ़्लाइट फ़ीचर द्वारा समर्थित है।


***Note:** The default value is 
false
.*
कोड उदाहरण के लिए, देखें यह [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/).


**Returns:**
boolean -  true  यदि PDF को ग्रेस्केल में बदला गया है,  false  अन्यथा।

### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


PDF को ग्रेस्केल में बदलना है या नहीं, सेट करता है।


***Note:** The default value is 
false
.*
कोड उदाहरण के लिए, देखें यह [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | convertToGrayScale | boolean | true  PDF को ग्रेस्केल में बदलने के लिए,  false  अन्यथा। |
|

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


पृष्ठ पर टेक्स्ट प्रदर्शित करने के लिए उपयोग किए जाने वाले प्रत्येक फ़ॉन्ट में फ़ॉन्ट अक्षरों के लिए ग्लिफ़ का सेट होता है।
PDF विनिर्देशन "फ़ॉन्ट सबसेट" का समर्थन करता है, अर्थात केवल उपयोग किए गए ग्लिफ़ वाले फ़ॉन्ट।
यह समस्या पैदा कर सकता है जब टेक्स्ट को अपडेट किया जाना चाहिए (क्योंकि संभवतः आवश्यक ग्लिफ़ फ़ॉन्ट में अनुपलब्ध हैं), लेकिन ऐसे दस्तावेज़ के लिए जो बदलने की योजना नहीं है, यह आकार घटाने की अनुमति देता है।


***Note:** The default value is 
false
.*
यदि फ़ाइल एम्बेडेड फ़ॉन्ट्स का उपयोग करती है, तो इसमें सभी फ़ॉन्ट डेटा होते हैं। GroupDocs.Viewer एम्बेडेड फ़ॉन्ट्स को सबसेट करके फ़ाइल आकार कम कर सकता है। कोड उदाहरण के लिए, देखें यह [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/).


**Returns:**
boolean -  true  यदि फ़ॉन्ट्स को सबसेट किया गया है,  false  अन्यथा।

### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


PDF में फ़ॉन्ट को सबसेट करना है या नहीं, सेट करता है।


***Note:** The default value is 
false
.*
यदि फ़ाइल एम्बेडेड फ़ॉन्ट्स का उपयोग करती है, तो इसमें सभी फ़ॉन्ट डेटा होते हैं। GroupDocs.Viewer एम्बेडेड फ़ॉन्ट्स को सबसेट करके फ़ाइल आकार कम कर सकता है। कोड उदाहरण के लिए, देखें यह [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | subsetFonts | boolean | true  फ़ॉन्ट्स को सबसेट करने के लिए,  false  अन्यथा। |
|

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


यदि स्रोत PDF फ़ाइल में इमेज हैं, तो इमेज को संकुचित करने और उनकी गुणवत्ता सेट करने पर विचार करें।
इमेज कॉम्प्रेशन सक्षम करने के लिए, इस विकल्प को true सेट करें। दस्तावेज़ में सभी इमेज फिर से संकुचित की जाएँगी।
कम्प्रेशन ImageQuality प्रॉपर्टी द्वारा परिभाषित है, जो प्रतिशत में गुणवत्ता का मान है।
100% अपरिवर्तित गुणवत्ता है। इमेज गुणवत्ता घटाने के लिए, ImageQuality प्रॉपर्टी को 100 से कम सेट करें।


***Note:** The default value is 
false
.*
इस विकल्प का उपयोग अन्य कॉम्प्रेसिंग विकल्पों को सक्षम करने के लिए करें: #setImageQuality(int).setImageQuality(int) और . कोड उदाहरण के लिए, देखें यह [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Returns:**
boolean -  true  यदि इमेजेस संकुचित हैं,  false  अन्यथा।

### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


PDF में इमेज को संकुचित करना है या नहीं, सेट करता है।


***Note:** The default value is 
false
.*
इस विकल्प का उपयोग अन्य कॉम्प्रेसिंग विकल्पों को सक्षम करने के लिए करें: #setImageQuality(int).setImageQuality(int) और . कोड उदाहरण के लिए, देखें यह [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | compressImages | boolean | true  इमेजेस को संकुचित करने के लिए,  false  अन्यथा। |
|

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


यदि स्रोत PDF फ़ाइल में छवियां हैं, तो छवियों को संपीड़ित करने और उनकी गुणवत्ता सेट करने पर विचार करें। छवि संपीड़न सक्षम करने के लिए, CompressImages विकल्प को true सेट करें। दस्तावेज़ में सभी छवियों को पुनः संपीड़ित किया जाएगा। संपीड़न ImageQuality प्रॉपर्टी द्वारा परिभाषित होता है, जो प्रतिशत में गुणवत्ता का मान है। 100% अपरिवर्तित गुणवत्ता है। छवि गुणवत्ता कम करने के लिए, CompressImages विकल्प को true और ImageQuality प्रॉपर्टी को 100 से कम सेट करें।

<br />


***Note:** The default value is 
100
.*
छवि गुणवत्ता बदलने के लिए, पहले #setCompressImages(boolean).setCompressImages(boolean) प्रॉपर्टी को true सेट करें। कोड उदाहरण के लिए, इस [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/) देखें।


**Returns:**
int - छवि गुणवत्ता (मान 1 और 100 के बीच)।

### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


PDF में इमेज को संकुचित करने के लिए इमेज की गुणवत्ता सेट करता है।


***Note:** The default value is 
100
.*
छवि गुणवत्ता बदलने के लिए, पहले #setCompressImages(boolean).setCompressImages(boolean) प्रॉपर्टी को true सेट करें। कोड उदाहरण के लिए, इस [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/) देखें।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | imageQuality | int | छवि गुणवत्ता (मान 1 और 100 के बीच)। |
|

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


CompressImages विकल्प के साथ उपयोग करके इमेज को कम रिज़ॉल्यूशन के साथ री-साइज़ किया जा सकता है।
इस मामले में, हमें CompressImage को true, ResizeImages को true और MaxResolution को उपयुक्त मान पर सेट करना चाहिए।


***Note:** The default value is 
false
.*
इस विकल्प को सक्षम करने के लिए, प्रॉपर्टी को true सेट करें। यह विकल्प प्रॉपर्टी सेट करने की अनुमति देता है। कोड उदाहरण के लिए, इस [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/) देखें।


**Returns:**
boolean -  true  यदि छवियों का आकार बदल दिया गया है,  false  अन्यथा।

### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


PDF में छवियों को पुनः आकार देने की सेटिंग निर्धारित करता है।


***Note:** The default value is 
false
.*
इस विकल्प को सक्षम करने के लिए, प्रॉपर्टी को true सेट करें। यह विकल्प प्रॉपर्टी सेट करने की अनुमति देता है। कोड उदाहरण के लिए, इस [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/) देखें।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | resizeImages | boolean | true  छवियों का आकार बदलने के लिए,  false  अन्यथा। |
|

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


CompressImages विकल्प के साथ उपयोग करके कम रिज़ॉल्यूशन वाली छवियों का आकार बदला जा सकता है। इस मामले में, हमें CompressImage को true, ResizeImages को true और MaxResolution को उपयुक्त मान पर सेट करना चाहिए।


***Note:** The default value is 
300
.*
इस विकल्प को सक्षम करने के लिए, #setCompressImages(boolean).setCompressImages(boolean) और #setMaxResolution(int).setMaxResolution(int) प्रॉपर्टीज़ को true सेट करें।
कोड उदाहरण के लिए, इस [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/) देखें।


**Returns:**
int - छवियों के लिए अधिकतम रिज़ॉल्यूशन।

### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


PDF में छवियों को पुनः आकार देने के लिए अधिकतम रिज़ॉल्यूशन सेट करता है।


***Note:** The default value is 
300
.*
इस विकल्प को सक्षम करने के लिए, #setCompressImages(boolean).setCompressImages(boolean) और #setMaxResolution(int).setMaxResolution(int) प्रॉपर्टीज़ को true सेट करें।
कोड उदाहरण के लिए, इस [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/) देखें।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | maxResolution | int | छवियों के लिए अधिकतम रिज़ॉल्यूशन। |
|

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


छोटे आउटपुट फ़ाइल आकार के लिए Excel स्प्रेडशीट की बॉर्डर लाइनों और फ़ॉन्ट्स को अनुकूलित करें।


*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*


***Note:** The default value is 
false
.*
कोड उदाहरण के लिए, इस [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/) देखें।


**Returns:**
boolean -  true  यदि स्प्रेडशीट्स को अनुकूलित किया गया है,  false  अन्यथा।

### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


PDF में स्प्रेडशीट को अनुकूलित करने की सेटिंग निर्धारित करता है।


कोड उदाहरण के लिए, इस [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/) देखें।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | optimizeSpreadsheets | boolean | true  स्प्रेडशीट्स को अनुकूलित करने के लिए,  false  अन्यथा। |
|

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


यदि true सेट किया गया हो तो निजी जानकारी (पृष्ठ भाग जानकारी) हटाएँ।


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  यदि निजी जानकारी हटाई गई है,  false  अन्यथा।

### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


PDF से निजी जानकारी हटाने की सेटिंग निर्धारित करता है।


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | removePrivateInfo | boolean | true  निजी जानकारी हटाने के लिए,  false  अन्यथा। |
|

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


यदि दस्तावेज़ एम्बेडेड फ़ॉन्ट्स का उपयोग करता है, तो इसका मतलब है कि सभी फ़ॉन्ट डेटा दस्तावेज़ में रखा गया है।
फ़ायदा यह है कि दस्तावेज़ उपयोगकर्ता की मशीन पर फ़ॉन्ट स्थापित है या नहीं, इस पर निर्भर किए बिना देखा जा सकता है। लेकिन फ़ॉन्ट एम्बेड करने से दस्तावेज़ बड़ा हो जाता है।
अनएंबेड फ़ॉन्ट्स मेथड सभी एंबेडेड फ़ॉन्ट्स को हटाता है। इससे दस्तावेज़ का आकार घटता है लेकिन यदि सही फ़ॉन्ट स्थापित नहीं है तो दस्तावेज़ पढ़ने योग्य नहीं रह सकता।


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  यदि एंबेडेड फ़ॉन्ट्स अनएंबेड किए गए हों,  false  अन्यथा।

### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


PDF में एम्बेडेड फ़ॉन्ट्स को अनएंबेड करने की सेटिंग निर्धारित करता है।


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | unembedFonts | boolean | true  एंबेडेड फ़ॉन्ट्स को अनएंबेड करने के लिए,  false  अन्यथा। |
|

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


कभी-कभी एक दस्तावेज़ में कई समान संसाधन स्ट्रीम्स होते हैं (उदाहरण के लिए छवियाँ)।
यह उदाहरण के लिए तब हो सकता है जब कोई दस्तावेज़ स्वयं के साथ जोड़ दिया जाता है।
आउटपुट दस्तावेज़ में समान रिसोर्स स्ट्रीम की दो स्वतंत्र प्रतियां होती हैं।
हम सभी रिसोर्स स्ट्रीम्स का विश्लेषण करते हैं और उनकी तुलना करते हैं। यदि स्ट्रीम्स दोहराए गए हैं तो उन्हें मिलाया जाता है, अर्थात केवल एक प्रतिलिपि बचती है, संदर्भ उचित रूप से बदल दिए जाते हैं और ऑब्जेक्ट की प्रतियां हटाई जाती हैं।
कभी-कभी इससे दस्तावेज़ का आकार घट जाता है।


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  यदि डुप्लिकेट स्ट्रीम्स लिंक किए गए हों,  false  अन्यथा।

### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


PDF में डुप्लिकेट स्ट्रीम्स को लिंक करने की सेटिंग निर्धारित करता है।


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | linkDuplicateStreams | boolean | true  डुप्लिकेट स्ट्रीम्स को लिंक करने के लिए,  false  अन्यथा। |
|

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


यदि यह प्रॉपर्टी true पर सेट है, तो समान पृष्ठों के लिए दस्तावेज़ को अनुकूलित करते समय पृष्ठ सामग्री को पुनः उपयोग किया जाएगा।


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  यदि पेज कंटेंट पुन: उपयोग किया गया हो,  false  अन्यथा।

### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


PDF में पृष्ठ सामग्री को पुनः उपयोग करने की अनुमति देने की सेटिंग निर्धारित करता है।


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | allowReusePageContent | boolean | true  पेज कंटेंट को पुन: उपयोग करने की अनुमति देने के लिए,  false  अन्यथा। |
|

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


कभी-कभी एक दस्तावेज़ में अप्रयुक्त संसाधन स्ट्रीम्स होते हैं।
ये स्ट्रीम्स “अनउपयोगी ऑब्जेक्ट्स” नहीं हैं क्योंकि इन्हें पेज के रिसोर्स डिक्शनरी से रेफ़र किया गया है।
यह उन मामलों में हो सकता है जहाँ एक इमेज पेज से हटा दी गई है लेकिन पेज रिसोर्सेज से नहीं।
इसके अलावा, यह स्थिति अक्सर तब होती है जब दस्तावेज़ से पेज निकाले जाते हैं और दस्तावेज़ पेजों में “सामान्य” रिसोर्सेज होते हैं,
अर्थात, वही Resources ऑब्जेक्ट। पेज कंटेंट्स का विश्लेषण किया जाता है यह निर्धारित करने के लिए कि क्या कोई रिसोर्स स्ट्रीम
का उपयोग किया गया है या नहीं। अनउपयोगी स्ट्रीम्स हटाए जाते हैं। कभी-कभी इससे दस्तावेज़ का आकार घट जाता है।


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  यदि अनउपयोगी स्ट्रीम्स हटाए गए हों,  false  अन्यथा।

### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


PDF से अप्रयुक्त स्ट्रीम्स को हटाने की सेटिंग निर्धारित करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | removeUnusedStreams | boolean | true  अनउपयोगी स्ट्रीम्स को हटाने के लिए,  false  अन्यथा। |
|

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


एक PDF दस्तावेज़ कभी-कभी उन PDF ऑब्जेक्ट्स को शामिल करता है जो संदर्भित नहीं होते
दस्तावेज़ में किसी अन्य ऑब्जेक्ट से। यह उदाहरण के लिए हो सकता है,
जब पेज को दस्तावेज़ पेज ट्री से हटाया जाता है लेकिन पेज ऑब्जेक्ट स्वयं नहीं हटाया जाता।
इन वस्तुओं को हटाने से दस्तावेज़ अमान्य नहीं होता बल्कि यह छोटा हो जाता है।


***Note:** The default value is 
false
.*


**Returns:**
बूलियन -  true  यदि अप्रयुक्त वस्तुएँ हटाई गई हों,  false  अन्यथा।

### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


PDF से अप्रयुक्त ऑब्जेक्ट्स को हटाने की सेटिंग निर्धारित करता है।


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | removeUnusedObjects | boolean | true  अप्रयुक्त वस्तुओं को हटाने के लिए,  false  अन्यथा। |
|

