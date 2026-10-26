---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "आउटपुट PDF फ़ाइल पर लागू करने के लिए PDF अनुकूलन विकल्प निर्दिष्ट करने हेतु इस क्लास का उपयोग करें।"
type: docs
weight: 21
url: /hi/nodejs-java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

आउटपुट PDF फ़ाइल पर लागू करने के लिए PDF अनुकूलन विकल्प निर्दिष्ट करने हेतु इस क्लास का उपयोग करें।

ये अनुकूलन विकल्प उन सभी इनपुट फ़ाइल स्वरूपों के लिए समर्थित हैं जो PDF में निर्यात के लिए समर्थित हैं। विवरण और कोड नमूनों के लिए, देखें यह [page][] और इसके उप‑पृष्ठ।

उदाहरण उपयोग:

```

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
 
```


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | MaxResolution विकल्प का डिफ़ॉल्ट मान 300 और ImageQuality विकल्प का डिफ़ॉल्ट मान 100 सेट करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [isLinearize()](#isLinearize--) | वेब ब्राउज़र के साथ ऑनलाइन देखने के लिए आउटपुट PDF फ़ाइल का अनुकूलन सक्षम करता है। |
| [setLinearize(boolean linearize)](#setLinearize-boolean-) | वेब ब्राउज़र के साथ ऑनलाइन ब्राउज़िंग के लिए आउटपुट PDF को अनुकूलित करना है या नहीं, सेट करता है। |
| [isRemoveAnnotations()](#isRemoveAnnotations--) | जब एनोटेशन अनावश्यक हों तो उन्हें हटाया जा सकता है। |
| [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | PDF से अनावश्यक एनोटेशन हटाने हैं या नहीं, सेट करता है। |
| [isRemoveFormFields()](#isRemoveFormFields--) | यदि PDF दस्तावेज़ में AcroForms हैं, तो फ़ॉर्म फ़ील्ड को फ्लैटन करके फ़ाइल आकार कम करने का प्रयास किया जा सकता है। |
| [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | PDF से फ़ॉर्म फ़ील्ड हटाने हैं या नहीं, सेट करता है। |
| [isConvertToGrayScale()](#isConvertToGrayScale--) | PDF फ़ाइल टेक्स्ट, इमेज, अटैचमेंट, एनोटेशन, ग्राफ़ और अन्य ऑब्जेक्ट्स से बनी होती है। |
| [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | PDF को ग्रेस्केल में बदलना है या नहीं, सेट करता है। |
| [isSubsetFonts()](#isSubsetFonts--) | पृष्ठ पर टेक्स्ट प्रदर्शित करने के लिए उपयोग किए जाने वाले प्रत्येक फ़ॉन्ट में फ़ॉन्ट अक्षरों के लिए ग्लिफ़ का सेट होता है। |
| [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | PDF में फ़ॉन्ट को सबसेट करना है या नहीं, सेट करता है। |
| [isCompressImages()](#isCompressImages--) | यदि स्रोत PDF फ़ाइल में इमेज हैं, तो इमेज को संपीड़ित करने और उनकी गुणवत्ता सेट करने पर विचार करें। |
| [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | PDF में इमेज को संपीड़ित करना है या नहीं, सेट करता है। |
| [getImageQuality()](#getImageQuality--) | यदि स्रोत PDF फ़ाइल में इमेज हैं, तो इमेज को संपीड़ित करने और उनकी गुणवत्ता सेट करने पर विचार करें। |
| [setImageQuality(int imageQuality)](#setImageQuality-int-) | PDF में इमेज को संपीड़ित करने के लिए इमेज गुणवत्ता सेट करता है। |
| [isResizeImages()](#isResizeImages--) | इमेज को कम रिज़ॉल्यूशन के साथ रिसाइज़ करने के लिए CompressImages विकल्प के साथ उपयोग किया जा सकता है। |
| [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | PDF में इमेज को रिसाइज़ करना है या नहीं, सेट करता है। |
| [getMaxResolution()](#getMaxResolution--) | इमेज को कम रिज़ॉल्यूशन के साथ रिसाइज़ करने के लिए CompressImages विकल्प के साथ उपयोग किया जा सकता है। |
| [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | PDF में इमेज को रिसाइज़ करने के लिए अधिकतम रिज़ॉल्यूशन सेट करता है। |
| [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | छोटे आउटपुट फ़ाइल आकार के लिए Excel स्प्रेडशीट की बॉर्डर लाइनों और फ़ॉन्ट को अनुकूलित करता है। |
| [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | PDF में स्प्रेडशीट को अनुकूलित करना है या नहीं, सेट करता है। |
| [isRemovePrivateInfo()](#isRemovePrivateInfo--) | यदि सत्य पर सेट किया गया हो तो निजी जानकारी (पृष्ठ टुकड़ा जानकारी) हटाएँ। |
| [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | PDF से निजी जानकारी हटाने हैं या नहीं, सेट करता है। |
| [isUnembedFonts()](#isUnembedFonts--) | यदि दस्तावेज़ एम्बेडेड फ़ॉन्ट का उपयोग करता है, तो इसका मतलब है कि सभी फ़ॉन्ट डेटा दस्तावेज़ में रखा गया है। |
| [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | PDF में एम्बेडेड फ़ॉन्ट को अनएंबेड करना है या नहीं, सेट करता है। |
| [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | कभी-कभी एक दस्तावेज़ में कई समान रिसोर्स स्ट्रीम (जैसे इमेज) होते हैं। |
| [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | PDF में डुप्लिकेट स्ट्रीम को लिंक करना है या नहीं, सेट करता है। |
| [isAllowReusePageContent()](#isAllowReusePageContent--) | यदि यह प्रॉपर्टी सत्य पर सेट है, तो समान पृष्ठों के लिए दस्तावेज़ को अनुकूलित करते समय पृष्ठ सामग्री को पुन: उपयोग किया जाएगा। |
| [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | PDF में पृष्ठ सामग्री को पुन: उपयोग करने की अनुमति देने के लिए सेट करता है। |
| [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | कभी-कभी दस्तावेज़ में अप्रयुक्त संसाधन स्ट्रीम होते हैं। |
| [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | PDF से अप्रयुक्त स्ट्रीम को हटाने के लिए सेट करता है। |
| [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | PDF दस्तावेज़ में कभी-कभी ऐसे PDF ऑब्जेक्ट होते हैं जो दस्तावेज़ में किसी अन्य ऑब्जेक्ट से संदर्भित नहीं होते। |
| [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | PDF से अप्रयुक्त ऑब्जेक्ट को हटाने के लिए सेट करता है। |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


MaxResolution विकल्प का डिफ़ॉल्ट मान 300 और ImageQuality विकल्प का डिफ़ॉल्ट मान 100 सेट करता है।

विवरण और कोड नमूनों के लिए, इस [page][] और इसकी उपश्रेणियों को देखें।


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/

### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


वेब ब्राउज़र के साथ ऑनलाइन देखने के लिए आउटपुट PDF फ़ाइल का अनुकूलन सक्षम करता है।

कोड उदाहरण के लिए, इस [documentation][] को देखें।


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Returns:**
बूलियन -  true  यदि आउटपुट PDF ऑनलाइन ब्राउज़िंग के लिए अनुकूलित है,  false  अन्यथा।
### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


वेब ब्राउज़र के साथ ऑनलाइन ब्राउज़िंग के लिए आउटपुट PDF को अनुकूलित करना है या नहीं, सेट करता है।

कोड उदाहरण के लिए, इस [documentation][] को देखें।


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| linearize | boolean | true  आउटपुट PDF को ऑनलाइन ब्राउज़िंग के लिए अनुकूलित करने के लिए,  false  अन्यथा। |

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


जब एनोटेशन अनावश्यक हों तो उन्हें हटाया जा सकता है। जब वे आवश्यक हों लेकिन अतिरिक्त संपादन की आवश्यकता न हो, तो उन्हें फ्लैट किया जा सकता है। इससे फ़ाइल का आकार कम हो जाएगा।

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Returns:**
बूलियन -  true  यदि एनोटेशन हटाए गए हैं,  false  अन्यथा।
### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


PDF से अनावश्यक एनोटेशन हटाने हैं या नहीं, सेट करता है।

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| removeAnnotations | boolean | true  अनावश्यक एनोटेशन को हटाने के लिए,  false  अन्यथा। |

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


यदि PDF दस्तावेज़ में AcroForms हैं, तो फ़ॉर्म फ़ील्ड को फ्लैटन करके फ़ाइल आकार कम करने का प्रयास किया जा सकता है।

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Returns:**
बूलियन -  true  यदि फ़ॉर्म फ़ील्ड हटाए गए हैं,  false  अन्यथा।
### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


PDF से फ़ॉर्म फ़ील्ड हटाने हैं या नहीं, सेट करता है।

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| removeFormFields | boolean | true  फ़ॉर्म फ़ील्ड को हटाने के लिए,  false  अन्यथा। |

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


PDF फ़ाइल टेक्स्ट, इमेज, अटैचमेंट, एनोटेशन, ग्राफ़ और अन्य ऑब्जेक्ट्स से बनी होती है। आपको कभी-कभी ऐसी आवश्यकता मिल सकती है कि PDF को RGB कलरस्पेस से ग्रेस्केल में परिवर्तित किया जाए ताकि उन PDF फ़ाइलों को प्रिंट करते समय गति बढ़े। साथ ही जब फ़ाइल को ग्रेस्केल में बदल दिया जाता है, तो दस्तावेज़ का आकार भी घट जाता है, लेकिन इस परिवर्तन के साथ दस्तावेज़ की गुणवत्ता घट सकती है। वर्तमान में, यह सुविधा Adobe Acrobat की प्री‑फ़्लाइट फ़ीचर द्वारा समर्थित है।

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Returns:**
बूलियन -  true  यदि PDF को ग्रेस्केल में परिवर्तित किया गया है,  false  अन्यथा।
### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


PDF को ग्रेस्केल में बदलना है या नहीं, सेट करता है।

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| convertToGrayScale | boolean | true  PDF को ग्रेस्केल में परिवर्तित करने के लिए,  false  अन्यथा। |

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


पृष्ठ पर टेक्स्ट प्रदर्शित करने के लिए उपयोग किए जाने वाले प्रत्येक फ़ॉन्ट में फ़ॉन्ट अक्षरों के लिए ग्लिफ़ का सेट होता है। PDF विनिर्देश "फ़ॉन्ट सबसेट" का समर्थन करता है, अर्थात केवल उपयोग किए गए ग्लिफ़ वाले फ़ॉन्ट। इससे तब समस्या हो सकती है जब टेक्स्ट को अपडेट करना हो (क्योंकि आवश्यक ग्लिफ़ फ़ॉन्ट में नहीं हो सकते), लेकिन उन दस्तावेज़ों के लिए जो बदलने की योजना नहीं रखते, यह आकार घटाने की अनुमति देता है।

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Returns:**
बूलियन -  true  यदि फ़ॉन्ट सबसेट किए गए हैं,  false  अन्यथा।
### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


PDF में फ़ॉन्ट को सबसेट करना है या नहीं, सेट करता है।

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| subsetFonts | boolean | true  फ़ॉन्ट को सबसेट करने के लिए,  false  अन्यथा। |

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


यदि स्रोत PDF फ़ाइल में छवियाँ हैं, तो छवियों को संकुचित करने और उनकी गुणवत्ता सेट करने पर विचार करें। छवि संपीड़न सक्षम करने के लिए, इस विकल्प को true पर सेट करें। दस्तावेज़ में सभी छवियों को फिर से संकुचित किया जाएगा। संपीड़न ImageQuality प्रॉपर्टी द्वारा परिभाषित है, जो प्रतिशत में गुणवत्ता का मान है। 100% अपरिवर्तित गुणवत्ता है। छवि गुणवत्ता घटाने के लिए, ImageQuality प्रॉपर्टी को 100 से कम सेट करें।

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
बूलियन -  true  यदि छवियाँ संकुचित हैं,  false  अन्यथा।
### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


PDF में इमेज को संपीड़ित करना है या नहीं, सेट करता है।

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| compressImages | boolean | true  छवियों को संकुचित करने के लिए,  false  अन्यथा। |

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


यदि स्रोत PDF फ़ाइल में छवियाँ हैं, तो छवियों को संकुचित करने और उनकी गुणवत्ता सेट करने पर विचार करें। छवि संपीड़न सक्षम करने के लिए, CompressImages विकल्प को true पर सेट करें। दस्तावेज़ में सभी छवियों को फिर से संकुचित किया जाएगा। संपीड़न ImageQuality प्रॉपर्टी द्वारा परिभाषित है, जो प्रतिशत में गुणवत्ता का मान है। 100% अपरिवर्तित गुणवत्ता है। छवि गुणवत्ता घटाने के लिए, CompressImages विकल्प को true और ImageQuality प्रॉपर्टी को 100 से कम सेट करें।

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
int - छवि गुणवत्ता (मान 1 से 100 के बीच)।
### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


PDF में इमेज को संपीड़ित करने के लिए इमेज गुणवत्ता सेट करता है।

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageQuality | int | छवि गुणवत्ता (मान 1 से 100 के बीच)। |

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


CompressImages विकल्प के साथ उपयोग किया जा सकता है ताकि छवियों को कम रिज़ॉल्यूशन के साथ आकार बदल सकें। इस मामले में, हमें CompressImage को true, ResizeImages को true और MaxResolution को उपयुक्त मान पर सेट करना चाहिए।

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
बूलियन -  true  यदि छवियों का आकार बदला गया है,  false  अन्यथा।
### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


PDF में इमेज को रिसाइज़ करना है या नहीं, सेट करता है।

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| resizeImages | boolean | true  छवियों का आकार बदलने के लिए,  false  अन्यथा। |

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


CompressImages विकल्प के साथ उपयोग किया जा सकता है ताकि छवियों को कम रिज़ॉल्यूशन के साथ आकार बदल सकें। इस मामले में, हमें CompressImage को true, ResizeImages को true और MaxResolution को उपयुक्त मान पर सेट करना चाहिए।

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
int - छवियों के लिए अधिकतम रिज़ॉल्यूशन।
### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


PDF में इमेज को रिसाइज़ करने के लिए अधिकतम रिज़ॉल्यूशन सेट करता है।

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| maxResolution | int | छवियों के लिए अधिकतम रिज़ॉल्यूशन। |

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


छोटे आउटपुट फ़ाइल आकार के लिए Excel स्प्रेडशीट की बॉर्डर लाइनों और फ़ॉन्ट को अनुकूलित करता है।

*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Returns:**
बूलियन -  true  यदि स्प्रेडशीट्स को अनुकूलित किया गया है,  false  अन्यथा।
### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


PDF में स्प्रेडशीट को अनुकूलित करना है या नहीं, सेट करता है।

कोड उदाहरण के लिए, इस [documentation][] को देखें।


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| optimizeSpreadsheets | boolean | true  स्प्रेडशीट्स को अनुकूलित करने के लिए,  false  अन्यथा। |

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


यदि सत्य पर सेट किया गया हो तो निजी जानकारी (पृष्ठ टुकड़ा जानकारी) हटाएँ।

***Note:** The default value is  false .*

**Returns:**
बूलियन -  true  यदि निजी जानकारी हटाई गई है,  false  अन्यथा।
### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


PDF से निजी जानकारी हटाने हैं या नहीं, सेट करता है।

***Note:** The default value is  false .*

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| removePrivateInfo | boolean | true  निजी जानकारी हटाने के लिए,  false  अन्यथा। |

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


यदि दस्तावेज़ में एम्बेडेड फ़ॉन्ट्स का उपयोग किया गया है, तो इसका अर्थ है कि सभी फ़ॉन्ट डेटा दस्तावेज़ में रखा गया है। इसका लाभ यह है कि फ़ॉन्ट उपयोगकर्ता के मशीन पर स्थापित हो या न हो, दस्तावेज़ देखी जा सकती है। लेकिन फ़ॉन्ट्स को एम्बेड करने से दस्तावेज़ बड़ा हो जाता है। unembed fonts मेथड सभी एम्बेडेड फ़ॉन्ट्स को हटाता है। इससे दस्तावेज़ का आकार घटता है, लेकिन यदि सही फ़ॉन्ट स्थापित नहीं है तो दस्तावेज़ पढ़ने योग्य नहीं रह सकता।

***Note:** The default value is  false .*

**Returns:**
बूलियन -  true  यदि एम्बेडेड फ़ॉन्ट्स को अनएंबेड किया गया है,  false  अन्यथा।
### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


PDF में एम्बेडेड फ़ॉन्ट को अनएंबेड करना है या नहीं, सेट करता है।

***Note:** The default value is  false .*

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| unembedFonts | boolean | true  एम्बेडेड फ़ॉन्ट्स को अनएंबेड करने के लिए,  false  अन्यथा। |

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


कभी-कभी एक दस्तावेज़ में कई समान संसाधन स्ट्रीम्स होते हैं (उदाहरण के लिए छवियों)। यह तब हो सकता है जब दस्तावेज़ को स्वयं के साथ जोड़ दिया जाता है। आउटपुट दस्तावेज़ में समान संसाधन स्ट्रीम की दो स्वतंत्र प्रतियां होती हैं। हम सभी संसाधन स्ट्रीम्स का विश्लेषण करते हैं और उनकी तुलना करते हैं। यदि स्ट्रीम्स दोहराए गए हैं तो उन्हें मिलाया जाता है, अर्थात केवल एक प्रति बचती है, संदर्भों को उचित रूप से बदल दिया जाता है और वस्तु की प्रतियां हटा दी जाती हैं। कभी-कभी इससे दस्तावेज़ का आकार घट जाता है।

***Note:** The default value is  false .*

**Returns:**
बूलियन -  true  यदि दोहराए गए स्ट्रीम्स लिंक किए गए हों,  false  अन्यथा।
### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


PDF में डुप्लिकेट स्ट्रीम को लिंक करना है या नहीं, सेट करता है।

***Note:** The default value is  false .*

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| linkDuplicateStreams | boolean | true  दोहराए गए स्ट्रीम्स को लिंक करने के लिए,  false  अन्यथा। |

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


यदि यह प्रॉपर्टी सत्य पर सेट है, तो समान पृष्ठों के लिए दस्तावेज़ को अनुकूलित करते समय पृष्ठ सामग्री को पुन: उपयोग किया जाएगा।

***Note:** The default value is  false .*

**Returns:**
बूलियन -  true  यदि पृष्ठ सामग्री पुन: उपयोग की गई हो,  false  अन्यथा।
### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


PDF में पृष्ठ सामग्री को पुन: उपयोग करने की अनुमति देने के लिए सेट करता है।

***Note:** The default value is  false .*

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| allowReusePageContent | boolean | true  पृष्ठ सामग्री को पुन: उपयोग करने की अनुमति देने के लिए,  false  अन्यथा। |

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


कभी-कभी एक दस्तावेज़ में अप्रयुक्त संसाधन स्ट्रीम्स होते हैं। ये स्ट्रीम्स अप्रयुक्त ऑब्जेक्ट्स नहीं हैं क्योंकि वे पृष्ठ के संसाधन शब्दकोश से संदर्भित हैं। यह तब हो सकता है जब किसी छवि को पृष्ठ से हटा दिया गया हो लेकिन पृष्ठ संसाधनों से नहीं। साथ ही, यह स्थिति अक्सर तब उत्पन्न होती है जब दस्तावेज़ से पृष्ठ निकाले जाते हैं और दस्तावेज़ पृष्ठों में सामान्य संसाधन होते हैं, अर्थात वही Resources ऑब्जेक्ट। पृष्ठ सामग्री का विश्लेषण यह निर्धारित करने के लिए किया जाता है कि कोई संसाधन स्ट्रीम उपयोग में है या नहीं। अप्रयुक्त स्ट्रीम्स को हटा दिया जाता है। कभी-कभी इससे दस्तावेज़ का आकार घट जाता है।

***Note:** The default value is  false .*

**Returns:**
बूलियन -  true  यदि अप्रयुक्त स्ट्रीम्स हटाए गए हों,  false  अन्यथा।
### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


PDF से अप्रयुक्त स्ट्रीम को हटाने के लिए सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| removeUnusedStreams | boolean | true  अप्रयुक्त स्ट्रीम्स को हटाने के लिए,  false  अन्यथा। |

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


एक PDF दस्तावेज़ में कभी-कभी ऐसे PDF ऑब्जेक्ट्स होते हैं जो दस्तावेज़ में किसी अन्य ऑब्जेक्ट से संदर्भित नहीं होते। यह तब हो सकता है, उदाहरण के लिए, जब एक पृष्ठ को दस्तावेज़ पृष्ठ वृक्ष से हटाया जाता है लेकिन पृष्ठ ऑब्जेक्ट स्वयं नहीं हटाया जाता। इन ऑब्जेक्ट्स को हटाने से दस्तावेज़ अमान्य नहीं होता बल्कि इसका आकार घट जाता है।

***Note:** The default value is  false .*

**Returns:**
बूलियन -  true  यदि अप्रयुक्त ऑब्जेक्ट्स हटाए गए हों,  false  अन्यथा।
### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


PDF से अप्रयुक्त ऑब्जेक्ट को हटाने के लिए सेट करता है।

***Note:** The default value is  false .*

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| removeUnusedObjects | boolean | true  अप्रयुक्त ऑब्जेक्ट्स को हटाने के लिए,  false  अन्यथा। |

