---
title: "PdfOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "PDF दस्तावेज़ों को रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 22
url: /hi/nodejs-java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

PDF दस्तावेज़ों को रेंडर करने के विकल्प प्रदान करता है।

PdfOptions क्लास विभिन्न सेटिंग्स और पैरामीटर को समाहित करता है जिन्हें GroupDocs.Viewer घटक में PDF दस्तावेज़ों की रेंडरिंग को नियंत्रित करने के लिए उपयोग किया जा सकता है। विवरण के लिए, देखें [documentation][].

उदाहरण उपयोग:

```

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
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | PdfOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [isDisableCopyProtection()](#isDisableCopyProtection--) | HTML में रेंडर करते समय कंटेंट कॉपी प्रोटेक्शन को बंद करता है। |
| [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | HTML में रेंडर करते समय कंटेंट कॉपी प्रोटेक्शन को बंद करता है। |
| [isRenderTextAsImage()](#isRenderTextAsImage--) | निर्धारित करता है कि स्रोत से टेक्स्ट HTML में इमेज के रूप में रेंडर किया जाता है या नहीं। |
| [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | स्रोत से टेक्स्ट को HTML में इमेज के रूप में रेंडर करने का सेट करता है। |
| [isDisableCharsGrouping()](#isDisableCharsGrouping--) | पेज रेंडर करते समय कैरेक्टर पोजिशनिंग में अधिकतम सटीकता बनाए रखने के लिए कैरेक्टर ग्रुपिंग निष्क्रिय है या नहीं जांचता है। |
| [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | पेज रेंडर करते समय कैरेक्टर पोजिशनिंग में अधिकतम सटीकता सुनिश्चित करने के लिए कैरेक्टर ग्रुपिंग को निष्क्रिय करने का विकल्प सेट करता है। |
| [isEnableLayeredRendering()](#isEnableLayeredRendering--) | HTML में रेंडर करते समय टेक्स्ट और ग्राफिक्स की रेंडरिंग मूल PDF दस्तावेज़ के z-order का पालन करे या नहीं जांचता है। |
| [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | HTML में रेंडर करते समय मूल PDF दस्तावेज़ के z-order के अनुसार टेक्स्ट और ग्राफिक्स की रेंडरिंग को सक्षम या निष्क्रिय करता है। |
| [isEnableFontHinting()](#isEnableFontHinting--) | निर्धारित करता है कि फ़ॉन्ट हिंटिंग सक्षम है या नहीं। |
| [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | फ़ॉन्ट हिंटिंग को सक्षम करता है। |
| [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | स्रोत PDF दस्तावेज़ में पेज आकार के समान पिक्सेल आकार के साथ पेजों की रेंडरिंग को सक्षम करता है। |
| [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | स्रोत PDF दस्तावेज़ में पेज आकार के समान पिक्सेल आकार के साथ पेजों की रेंडरिंग को सक्षम करता है। |
| [getImageQuality()](#getImageQuality--) | HTML में रेंडर करते समय इमेज रिसोर्सेज़ के लिए आउटपुट इमेज क्वालिटी प्राप्त करता है। |
| [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | HTML में रेंडर करते समय इमेज रिसोर्सेज़ के लिए आउटपुट इमेज क्वालिटी सेट करता है। |
| [isFixedLayout()](#isFixedLayout--) | PDF एक स्थिर फॉर्मेट है इसलिए सभी तत्वों का पेज पर एक विशिष्ट स्थान होता है। |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF एक स्थिर फॉर्मेट है इसलिए सभी तत्वों का पेज पर एक विशिष्ट स्थान होता है। |
| [isWrapImagesInSvg()](#isWrapImagesInSvg--) | आउटपुट क्वालिटी सुधारने के लिए प्रत्येक इमेज को आउटपुट HTML दस्तावेज़ में SVG टैग में लपेटने के लिए इस विकल्प को सक्षम करें। |
| [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | आउटपुट क्वालिटी सुधारने के लिए प्रत्येक इमेज को आउटपुट HTML दस्तावेज़ में SVG टैग में लपेटने के लिए इस विकल्प को सक्षम करें। |
| [isFixLinkIssue()](#isFixLinkIssue--) | जब पूरी HTML पेज सामग्री एक लिंक हो तो समस्या को ठीक करने का प्रयास करता है। |
| [setFixLinkIssue(boolean fixLinkIssue)](#setFixLinkIssue-boolean-) | जब पूरी HTML पेज सामग्री एक लिंक हो तो समस्या को ठीक करने का प्रयास करता है। |
| [isAnalyzeFonts()](#isAnalyzeFonts--) | टेक्स्ट में सभी कैरेक्टर प्रदर्शित हो सकें, इसके लिए आवश्यकतानुसार फ़ॉन्ट बदलता है। |
| [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | टेक्स्ट में सभी कैरेक्टर प्रदर्शित हो सकें, इसके लिए आवश्यकतानुसार फ़ॉन्ट बदलता है। |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | वर्तमान XPS/OXPS दस्तावेज़ में सभी फ़ॉन्ट्स के लिए किसी भी लाइसेंस प्रतिबंध को निष्क्रिय करें। |
| [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | वर्तमान XPS/OXPS दस्तावेज़ में सभी फ़ॉन्ट्स के लिए किसी भी लाइसेंस प्रतिबंध को निष्क्रिय करने के लिए फ़्लैग सेट करें। |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


PdfOptions क्लास का नया इंस्टेंस प्रारंभ करता है।

### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


HTML में रेंडर करते समय कंटेंट कॉपी प्रोटेक्शन को बंद करता है।

जब PDF फ़ाइलों को HTML में रेंडर किया जाता है और टेक्स्ट व छवियों की कॉपीिंग से सुरक्षा होती है, तो GroupDocs.Viewer HTML BODY टैग में एक 'inert' HTML एट्रिब्यूट जोड़ता है। इस विकल्प का डिफ़ॉल्ट मान false है।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


HTML में रेंडर करते समय कंटेंट कॉपी प्रोटेक्शन को बंद करता है।

जब PDF फ़ाइलों को HTML में रेंडर किया जाता है और टेक्स्ट व छवियों की कॉपीिंग से सुरक्षा होती है, तो GroupDocs.Viewer HTML BODY टैग में एक 'inert' HTML एट्रिब्यूट जोड़ता है। इस विकल्प का डिफ़ॉल्ट मान false है।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


निर्धारित करता है कि स्रोत से टेक्स्ट HTML में इमेज के रूप में रेंडर किया जाता है या नहीं।

जब इस विकल्प को true पर सेट किया जाता है, तो टेक्स्ट आउटपुट HTML में एक छवि के रूप में रेंडर होता है। इस विकल्प को सक्षम करने से टेक्स्ट चयन योग्य नहीं रहेगा या कैरेक्टर रेंडरिंग को ठीक किया जा सकता है और HTML को PDF जैसा दिखाया जा सकता है। यह विकल्प HTML में रेंडर करने पर समर्थित है।

***Note:** The default value is  false .*

**Returns:**
बूलियन - true यदि टेक्स्ट HTML में छवि के रूप में रेंडर हो, false अन्यथा।
### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


स्रोत से टेक्स्ट को HTML में इमेज के रूप में रेंडर करने का सेट करता है।

जब इस विकल्प को true पर सेट किया जाता है, तो टेक्स्ट आउटपुट HTML में एक छवि के रूप में रेंडर होता है। इस विकल्प को सक्षम करने से टेक्स्ट चयन योग्य नहीं रहेगा या कैरेक्टर रेंडरिंग को ठीक किया जा सकता है और HTML को PDF जैसा दिखाया जा सकता है। यह विकल्प HTML में रेंडर करने पर समर्थित है।

***Note:** The default value is  false .*

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| renderTextAsImage | boolean | true HTML में टेक्स्ट को छवि के रूप में रेंडर करने के लिए, false अन्यथा। |

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


पृष्ठ रेंडर करते समय कैरेक्टर पोजिशनिंग के दौरान अधिकतम सटीकता बनाए रखने के लिए जांचता है कि कैरेक्टर ग्रुपिंग निष्क्रिय है या नहीं। जब यह विकल्प सक्षम होता है, तो कैरेक्टर्स बिना किसी ग्रुपिंग के रेंडर होते हैं, जिससे अधिकतम सटीकता सुनिश्चित होती है।

***Note:** By default, character grouping is enabled.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Returns:**
बूलियन - true यदि कैरेक्टर ग्रुपिंग निष्क्रिय है, false अन्यथा।
### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


पृष्ठ रेंडर करते समय कैरेक्टर पोजिशनिंग के दौरान अधिकतम सटीकता सुनिश्चित करने के लिए कैरेक्टर ग्रुपिंग को निष्क्रिय करने का विकल्प सेट करता है। जब इस विकल्प को true पर सेट किया जाता है, तो कैरेक्टर ग्रुपिंग निष्क्रिय हो जाती है, जिससे अधिकतम सटीकता सुनिश्चित होती है।

***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean | true कैरेक्टर ग्रुपिंग को निष्क्रिय करने के लिए, false इसे सक्षम करने के लिए। |

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


जांचता है कि HTML में रेंडर करते समय टेक्स्ट और ग्राफ़िक्स को मूल PDF दस्तावेज़ के z-order का पालन करना चाहिए या नहीं। जब यह विकल्प true लौटाकर सक्षम किया जाता है, तो टेक्स्ट और ग्राफ़िक्स मूल PDF दस्तावेज़ के z-order के अनुसार रेंडर होते हैं।

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Returns:**
बूलियन - true यदि लेयर्ड रेंडरिंग सक्षम है, false अन्यथा।
### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


HTML में रेंडर करते समय मूल PDF दस्तावेज़ के z-order के अनुसार टेक्स्ट और ग्राफिक्स की रेंडरिंग को सक्षम या निष्क्रिय करता है।

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean | true लेयर्ड रेंडरिंग को सक्षम करने के लिए, false इसे निष्क्रिय करने के लिए। |

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


निर्धारित करता है कि फ़ॉन्ट हिन्टिंग सक्षम है या नहीं। फ़ॉन्ट हिन्टिंग आउटलाइन फ़ॉन्ट के प्रदर्शन को समायोजित करती है। यह विकल्प केवल TrueType (TTF) फ़ॉन्ट्स के लिए समर्थित है जब स्रोत दस्तावेज़ में उपयोग किया जाता है।

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Returns:**
बूलियन - true यदि फ़ॉन्ट हिन्टिंग सक्षम है, false अन्यथा।
### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


फ़ॉन्ट हिन्टिंग को सक्षम करता है। फ़ॉन्ट हिन्टिंग आउटलाइन फ़ॉन्ट के प्रदर्शन को समायोजित करती है और केवल TrueType (TTF) फ़ॉन्ट्स के लिए समर्थित है जब स्रोत दस्तावेज़ में उपयोग किया जाता है।

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean | true फ़ॉन्ट हिन्टिंग को सक्षम करने के लिए, false इसे निष्क्रिय करने के लिए। |

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


स्रोत PDF दस्तावेज़ में पेज आकार के समान पिक्सेल आकार के साथ पेजों की रेंडरिंग को सक्षम करता है।

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Returns:**
बूलियन - true यदि विकल्प सक्षम है, false अन्यथा।
### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


स्रोत PDF दस्तावेज़ में पेज आकार के समान पिक्सेल आकार के साथ पेजों की रेंडरिंग को सक्षम करता है।

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| renderOriginalPageSize | boolean | true मूल पृष्ठ आकार के साथ रेंडरिंग को सक्षम करने के लिए, false अन्यथा। |

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


HTML में रेंडर करते समय इमेज संसाधनों के आउटपुट इमेज क्वालिटी को प्राप्त करता है। डिफ़ॉल्ट मान Low है।

जब इस विकल्प को true पर सेट किया जाता है, तो GroupDocs.Viewer HTML आउटपुट में टेक्स्ट को एक छवि के रूप में रेंडर करता है। इससे टेक्स्ट चयन योग्य नहीं रहता और कैरेक्टर रेंडरिंग में सुधार होता है, जिससे HTML में PDF जैसा रूप मिलता है। डिफ़ॉल्ट मान false है। यह विकल्प HTML में रेंडर करने के लिए उपलब्ध है। कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.
### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


HTML में रेंडर करते समय इमेज संसाधनों के आउटपुट इमेज क्वालिटी को सेट करता है। डिफ़ॉल्ट मान Low है।

जब इस विकल्प को true पर सेट किया जाता है, तो GroupDocs.Viewer HTML आउटपुट में टेक्स्ट को एक छवि के रूप में रेंडर करता है। इससे टेक्स्ट चयन योग्य नहीं रहता और कैरेक्टर रेंडरिंग में सुधार होता है, जिससे HTML में PDF जैसा रूप मिलता है। डिफ़ॉल्ट मान false है। यह विकल्प HTML में रेंडर करने के लिए उपलब्ध है। कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | HTML में रेंडर करते समय इमेज संसाधनों के लिए आउटपुट इमेज गुणवत्ता। |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF एक स्थिर फ़ॉर्मेट है इसलिए सभी तत्वों का पृष्ठ पर एक विशिष्ट स्थान होता है। यह सुनिश्चित करने के लिए कि आउटपुट HTML स्रोत PDF जैसा ही दिखे, दस्तावेज़ डिफ़ॉल्ट रूप से स्थिर लेआउट के साथ HTML में रेंडर किए जाते हैं। स्थिर लेआउट के साथ रेंडर करने पर आउटपुट HTML का आकार निश्चित रहता है जिससे तत्व विंडो के आकार की परवाह किए बिना उसी स्थान पर रहते हैं। फ्लुइड लेआउट के साथ HTML रेंडर करने के लिए इस प्रॉपर्टी को false सेट करें।

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

उदाहरण उपयोग:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Returns:**
बूलियन - यदि यह स्थिर लेआउट है तो true
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF एक स्थिर फ़ॉर्मेट है इसलिए सभी तत्वों का पृष्ठ पर एक विशिष्ट स्थान होता है। यह सुनिश्चित करने के लिए कि आउटपुट HTML स्रोत PDF जैसा ही दिखे, दस्तावेज़ डिफ़ॉल्ट रूप से स्थिर लेआउट के साथ HTML में रेंडर किए जाते हैं। स्थिर लेआउट के साथ रेंडर करने पर आउटपुट HTML का आकार निश्चित रहता है जिससे तत्व विंडो के आकार की परवाह किए बिना उसी स्थान पर रहते हैं। फ्लुइड लेआउट के साथ HTML रेंडर करने के लिए इस प्रॉपर्टी को false सेट करें।

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

उदाहरण उपयोग:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fixedLayout | boolean | यदि यह स्थिर लेआउट है तो true |

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


आउटपुट क्वालिटी सुधारने के लिए प्रत्येक इमेज को आउटपुट HTML दस्तावेज़ में SVG टैग में लपेटने के लिए इस विकल्प को सक्षम करें।

यह विकल्प तब समर्थित है जब [PDF and Page Layout file formats][] को एम्बेडेड और एक्सटर्नल रिसोर्सेज़ के साथ HTML में रेंडर किया जाता है।

डिफ़ॉल्ट रूप से, जब PDF और पेज लेआउट फ़ाइलों में रेंडर किया जाता है, सभी इमेजेज़ को एक ही PNG इमेज के रूप में रेंडर किया जाता है। रेंडर किया गया PNG इमेज आउटपुट HTML दस्तावेज़ की बैकग्राउंड के रूप में उपयोग किया जाता है।

और अधिक जानें:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Returns:**
बूलियन - यदि इमेजेज़ SVG में रैप किए गए हैं तो true, अन्यथा false।
### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


आउटपुट क्वालिटी सुधारने के लिए प्रत्येक इमेज को आउटपुट HTML दस्तावेज़ में SVG टैग में लपेटने के लिए इस विकल्प को सक्षम करें।

यह विकल्प तब समर्थित है जब [PDF and Page Layout file formats][] को एम्बेडेड और एक्सटर्नल रिसोर्सेज़ के साथ HTML में रेंडर किया जाता है।

डिफ़ॉल्ट रूप से, जब PDF और पेज लेआउट फ़ाइलों में रेंडर किया जाता है, सभी इमेजेज़ को एक ही PNG इमेज के रूप में रेंडर किया जाता है। रेंडर किया गया PNG इमेज आउटपुट HTML दस्तावेज़ की बैकग्राउंड के रूप में उपयोग किया जाता है।

और अधिक जानें:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| wrapImagesInSvg | boolean | यदि इमेजेज़ को SVG में रैप किया जाना चाहिए तो true, अन्यथा false। |

### isFixLinkIssue() {#isFixLinkIssue--}
```
public boolean isFixLinkIssue()
```


जब पूरी HTML पेज सामग्री एक लिंक हो तो इस समस्या को ठीक करने का प्रयास करता है। यह केवल तब काम करता है जब इनपुट फ़ॉर्मेट PDF हो और आउटपुट फ़ॉर्मेट HTML (एम्बेडेड या एक्सटर्नल रिसोर्सेज़ के साथ) हो। डिफ़ॉल्ट रूप से यह निष्क्रिय है (false)। इसे केवल तभी चालू करें जब आप जानते हों कि आप क्या और क्यों कर रहे हैं। इस विकल्प को चालू करने से दस्तावेज़ प्रोसेसिंग समय बढ़ जाता है।

**Returns:**
boolean
### setFixLinkIssue(boolean fixLinkIssue) {#setFixLinkIssue-boolean-}
```
public void setFixLinkIssue(boolean fixLinkIssue)
```


जब पूरी HTML पेज सामग्री एक लिंक हो तो इस समस्या को ठीक करने का प्रयास करता है। यह केवल तब काम करता है जब इनपुट फ़ॉर्मेट PDF हो और आउटपुट फ़ॉर्मेट HTML (एम्बेडेड या एक्सटर्नल रिसोर्सेज़ के साथ) हो। डिफ़ॉल्ट रूप से यह निष्क्रिय है (false)। इसे केवल तभी चालू करें जब आप जानते हों कि आप क्या और क्यों कर रहे हैं। इस विकल्प को चालू करने से दस्तावेज़ प्रोसेसिंग समय बढ़ जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fixLinkIssue | boolean | यदि समस्या को ठीक किया जाना चाहिए तो true, अन्यथा false। |

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


टेक्स्ट में सभी कैरेक्टर प्रदर्शित हो सकें, इसके लिए आवश्यकतानुसार फ़ॉन्ट बदलता है।

**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


टेक्स्ट में सभी कैरेक्टर प्रदर्शित हो सकें, इसके लिए आवश्यकतानुसार फ़ॉन्ट बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| analyzeFonts | boolean | यदि फ़ॉन्ट्स दिखाए जाने चाहिए तो true, अन्यथा false। |

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


वर्तमान XPS/OXPS दस्तावेज़ में सभी फ़ॉन्ट्स के लिए किसी भी लाइसेंस प्रतिबंध को निष्क्रिय करें।

फ़ॉन्ट के साथ कई ऑपरेशन्स को तब निष्पादित नहीं किया जा सकता जब ये ऑपरेशन्स उस फ़ॉन्ट के लाइसेंस द्वारा प्रतिबंधित हों। उदाहरण के लिए, कुछ फ़ॉन्ट को PDF दस्तावेज़ में एम्बेड नहीं किया जा सकता यदि लाइसेंस नियम इस फ़ॉन्ट के लिए एम्बेडिंग को अक्षम करते हैं। इस फ़्लैग का उपयोग करते समय सावधान रहें। जब इसे सेट किया जाता है, तो इसका अर्थ है कि इस फ़्लैग को सेट करने वाला व्यक्ति संभावित लाइसेंस/कानूनी उल्लंघनों की पूरी ज़िम्मेदारी स्वयं लेता है। इसलिए यह उनका अपना जोखिम है। यह अत्यधिक अनुशंसा की जाती है कि आप इस फ़्लैग का उपयोग केवल तभी करें जब आप पूरी तरह आश्वस्त हों कि आप कॉपीराइट कानून का उल्लंघन नहीं कर रहे हैं। डिफ़ॉल्ट रूप से false है। कोड उदाहरण के लिए, देखें [documentation][].

उदाहरण उपयोग:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


वर्तमान XPS/OXPS दस्तावेज़ में सभी फ़ॉन्ट्स के लिए किसी भी लाइसेंस प्रतिबंध को निष्क्रिय करने के लिए फ़्लैग सेट करें।

फ़ॉन्ट के साथ कई ऑपरेशन्स को तब निष्पादित नहीं किया जा सकता जब ये ऑपरेशन्स उस फ़ॉन्ट के लाइसेंस द्वारा प्रतिबंधित हों। उदाहरण के लिए, कुछ फ़ॉन्ट को PDF दस्तावेज़ में एम्बेड नहीं किया जा सकता यदि लाइसेंस नियम इस फ़ॉन्ट के लिए एम्बेडिंग को अक्षम करते हैं। इस फ़्लैग का उपयोग करते समय सावधान रहें। जब इसे सेट किया जाता है, तो इसका अर्थ है कि इस फ़्लैग को सेट करने वाला व्यक्ति संभावित लाइसेंस/कानूनी उल्लंघनों की पूरी ज़िम्मेदारी स्वयं लेता है। इसलिए यह उनका अपना जोखिम है। यह अत्यधिक अनुशंसा की जाती है कि आप इस फ़्लैग का उपयोग केवल तभी करें जब आप पूरी तरह आश्वस्त हों कि आप कॉपीराइट कानून का उल्लंघन नहीं कर रहे हैं। डिफ़ॉल्ट रूप से false है। कोड उदाहरण के लिए, देखें [documentation][].

उदाहरण उपयोग:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

