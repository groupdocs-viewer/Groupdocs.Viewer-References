---
title: "BaseViewOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "बेस रेंडरिंग विकल्पों को शामिल करता है।"
type: docs
weight: 12
url: /hi/nodejs-java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

बेस रेंडरिंग विकल्पों को शामिल करता है।

The  BaseViewOptions  क्लास GroupDocs.Viewer में रेंडरिंग विकल्पों के लिए आधार के रूप में कार्य करती है। यह आपको विशिष्ट दस्तावेज़ फ़ॉर्मेट को रेंडर करते समय आउटपुट HTML, PDF, PNG, और JPEG फ़ाइलों के रेंडरिंग व्यवहार को अनुकूलित करने की अनुमति देती है।

***Note:** For internal usage.*
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [BaseViewOptions()](#BaseViewOptions--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getTextOptions()](#getTextOptions--) | टेक्स्ट फ़ाइलों को पृष्ठों में विभाजित करने के विकल्प प्राप्त करता है। |
| [setTextOptions(TextOptions textOptions)](#setTextOptions-com.groupdocs.viewer.options.TextOptions-) | टेक्स्ट फ़ाइलों को पृष्ठों में विभाजित करने के विकल्प सेट करता है। |
| [isRenderComments()](#isRenderComments--) | टिप्पणियों के रेंडरिंग को सक्षम करता है। |
| [setRenderComments(boolean value)](#setRenderComments-boolean-) | टिप्पणियों के रेंडरिंग को सक्षम करता है। |
| [isRemoveComments()](#isRemoveComments--) | सही सेट होने पर टिप्पणी रेंडरिंग को अक्षम करता है। |
| [setRemoveComments(boolean value)](#setRemoveComments-boolean-) | सही सेट होने पर टिप्पणी रेंडरिंग को अक्षम करता है। |
| [isRenderNotes()](#isRenderNotes--) | नोट्स के रेंडरिंग को सक्षम करता है। |
| [setRenderNotes(boolean value)](#setRenderNotes-boolean-) | नोट्स के रेंडरिंग को सक्षम करता है। |
| [isRenderHiddenPages()](#isRenderHiddenPages--) | छिपे पृष्ठों के रेंडरिंग को सक्षम करता है। |
| [setRenderHiddenPages(boolean value)](#setRenderHiddenPages-boolean-) | छिपे पृष्ठों के रेंडरिंग को सक्षम करता है। |
| [getDefaultFontName()](#getDefaultFontName--) | डॉक्यूमेंट में उपयोग किए गए किसी विशेष फ़ॉन्ट को न मिलने पर उपयोग किया जाने वाला डिफ़ॉल्ट फ़ॉन्ट। |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | डॉक्यूमेंट में उपयोग किए गए किसी विशेष फ़ॉन्ट को न मिलने पर उपयोग किया जाने वाला डिफ़ॉल्ट फ़ॉन्ट। |
| [getArchiveOptions()](#getArchiveOptions--) | आर्काइव फ़ाइलों के दृश्य विकल्प प्राप्त करता है। |
| [setArchiveOptions(ArchiveOptions value)](#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-) | आर्काइव फ़ाइलों के दृश्य विकल्प सेट करता है। |
| [getCadOptions()](#getCadOptions--) | CAD ड्राइंग के दृश्य विकल्प प्राप्त करता है। |
| [setCadOptions(CadOptions value)](#setCadOptions-com.groupdocs.viewer.options.CadOptions-) | CAD ड्राइंग के दृश्य विकल्प सेट करता है। |
| [isCadOptionsInitialized_Internal()](#isCadOptionsInitialized-Internal--) |  |
| [getEmailOptions()](#getEmailOptions--) | ईमेल संदेशों के दृश्य विकल्प प्राप्त करता है। |
| [setEmailOptions(EmailOptions value)](#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-) | ईमेल संदेशों के दृश्य विकल्प सेट करता है। |
| [getOutlookOptions()](#getOutlookOptions--) | MS Outlook डेटा फ़ाइलों के दृश्य विकल्प प्राप्त करता है। |
| [setOutlookOptions(OutlookOptions value)](#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-) | MS Outlook डेटा फ़ाइलों के दृश्य विकल्प सेट करता है। |
| [getPdfOptions()](#getPdfOptions--) | PDF दस्तावेज़ों के दृश्य विकल्प प्राप्त करता है। |
| [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-) | PDF दस्तावेज़ों के दृश्य विकल्प प्राप्त करता है। |
| [getMailStorageOptions()](#getMailStorageOptions--) | Lotus Notes स्टोरेज डेटा फ़ाइलों के दृश्य विकल्प प्राप्त करता है। |
| [setMailStorageOptions(MailStorageOptions mailStorageOptions)](#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-) | Lotus Notes स्टोरेज डेटा फ़ाइलों के दृश्य विकल्प सेट करता है। |
| [getProjectManagementOptions()](#getProjectManagementOptions--) | प्रोजेक्ट मैनेजमेंट फ़ाइलों के दृश्य विकल्प प्राप्त करता है। |
| [setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)](#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-) | प्रोजेक्ट मैनेजमेंट फ़ाइलों के दृश्य विकल्प सेट करता है। |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | स्प्रेडशीट फ़ाइलों के दृश्य विकल्प प्राप्त करता है। |
| [setSpreadsheetOptions(SpreadsheetOptions value)](#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-) | स्प्रेडशीट फ़ाइलों के दृश्य विकल्प सेट करता है। |
| [getWordProcessingOptions()](#getWordProcessingOptions--) | वर्ड प्रोसेसिंग फ़ाइलों के दृश्य विकल्प। |
| [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | वर्ड प्रोसेसिंग फ़ाइलों के दृश्य विकल्प। |
| [getVisioRenderingOptions()](#getVisioRenderingOptions--) | दस्तावेज़ देखने के समय Visio फ़ाइलों को प्रोसेस करने के लिए रेंडरिंग विकल्प प्राप्त करता है। |
| [setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)](#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-) | दस्तावेज़ देखने के समय Visio फ़ाइलों को प्रोसेस करने के लिए रेंडरिंग विकल्प सेट करता है। |
| [getPresentationOptions()](#getPresentationOptions--) | प्रेजेंटेशन दस्तावेज़ों को प्रोसेस करने के लिए दृश्य विकल्प प्राप्त करता है। |
| [setPresentationOptions(PresentationOptions presentationOptions)](#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-) | प्रेजेंटेशन दस्तावेज़ों को प्रोसेस करने के लिए दृश्य विकल्प सेट करता है। |
| [getWebDocumentOptions()](#getWebDocumentOptions--) | वेब दस्तावेज़ों को रेंडर करते समय आउटपुट HTML/PDF/PNG/JPEG की उपस्थिति को अनुकूलित करने वाले रेंडरिंग विकल्प प्राप्त करता है। |
| [setWebDocumentOptions(WebDocumentOptions webDocumentOptions)](#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-) | वेब दस्तावेज़ों को रेंडर करते समय आउटपुट HTML/PDF/PNG/JPEG की उपस्थिति को अनुकूलित करने वाले रेंडरिंग विकल्प सेट करता है। |
### BaseViewOptions() {#BaseViewOptions--}
```
public BaseViewOptions()
```


### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


टेक्स्ट फ़ाइलों को पृष्ठों में विभाजित करने के विकल्प प्राप्त करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/

**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions) - the text file splitting options.
### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


टेक्स्ट फ़ाइलों को पृष्ठों में विभाजित करने के विकल्प सेट करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) | टेक्स्ट फ़ाइल विभाजन विकल्प। |

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


टिप्पणियों के रेंडरिंग को सक्षम करता है।

डिफ़ॉल्ट रूप से, GroupDocs.Viewer टिप्पणियों को रेंडर नहीं करता है। इसे करने के लिए, इस प्रॉपर्टी को true सेट करें। कोड उदाहरण के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments

**Returns:**
बूलियन -  true  यदि टिप्पणियों को रेंडर किया जाना चाहिए,  false  अन्यथा।
### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


टिप्पणियों के रेंडरिंग को सक्षम करता है।

डिफ़ॉल्ट रूप से, GroupDocs.Viewer टिप्पणियों को रेंडर नहीं करता है। इसे करने के लिए, इस प्रॉपर्टी को true सेट करें। कोड उदाहरण के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean | true  यदि टिप्पणियों को रेंडर किया जाना चाहिए,  false  अन्यथा। |

### isRemoveComments() {#isRemoveComments--}
```
public final boolean isRemoveComments()
```


जब true सेट किया जाता है तो टिप्पणियों को रेंडर करना अक्षम करता है। डिफ़ॉल्ट रूप से false है \u2014 सभी टिप्पणियां प्रदर्शित होती हैं।

PDF और WordProcessing जैसे कुछ दस्तावेज़ फ़ॉर्मेट में टिप्पणियां हो सकती हैं। डिफ़ॉल्ट रूप से GroupDocs.Viewer उन्हें रेंडर करता है। इस विकल्प को true सेट करने पर टिप्पणियों को परिणामी दस्तावेज़ से बाहर रखा जा सकता है। यह विकल्प पुरानी 'RenderComments' प्रॉपर्टी को बदलता है।

**Returns:**
बूलियन -  true  यदि टिप्पणियों को रेंडर किया जाना चाहिए,  false  अन्यथा।
### setRemoveComments(boolean value) {#setRemoveComments-boolean-}
```
public final void setRemoveComments(boolean value)
```


जब true सेट किया जाता है तो टिप्पणियों को रेंडर करना अक्षम करता है। डिफ़ॉल्ट रूप से false है \u2014 सभी टिप्पणियां प्रदर्शित होती हैं।

PDF और WordProcessing जैसे कुछ दस्तावेज़ फ़ॉर्मेट में टिप्पणियां हो सकती हैं। डिफ़ॉल्ट रूप से GroupDocs.Viewer उन्हें रेंडर करता है। इस विकल्प को true सेट करने पर टिप्पणियों को परिणामी दस्तावेज़ से बाहर रखा जा सकता है। यह विकल्प पुरानी 'RenderComments' प्रॉपर्टी को बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean | true  यदि टिप्पणियों को रेंडर किया जाना चाहिए,  false  अन्यथा। |

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


नोट्स के रेंडरिंग को सक्षम करता है।

प्रेजेंटेशन या Microsoft प्रोजेक्ट फ़ाइलों जैसी कुछ फ़ाइलों में नोट्स हो सकते हैं। डिफ़ॉल्ट रूप से, GroupDocs.Viewer नोट्स को रेंडर नहीं करता है। इसे करने के लिए, इस प्रॉपर्टी को true सेट करें। कोड उदाहरण के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-speaker-notes

**Returns:**
बूलियन -  true  यदि नोट्स को रेंडर किया जाना चाहिए,  false  अन्यथा।
### setRenderNotes(boolean value) {#setRenderNotes-boolean-}
```
public final void setRenderNotes(boolean value)
```


नोट्स के रेंडरिंग को सक्षम करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean | true  यदि नोट्स को रेंडर किया जाना चाहिए,  false  अन्यथा। |

### isRenderHiddenPages() {#isRenderHiddenPages--}
```
public final boolean isRenderHiddenPages()
```


छिपे पृष्ठों के रेंडरिंग को सक्षम करता है।

प्रेजेंटेशन या स्प्रेडशीट जैसी कुछ फ़ाइलों में छिपे पृष्ठ हो सकते हैं। डिफ़ॉल्ट रूप से, GroupDocs.Viewer इन पृष्ठों को रेंडर नहीं करता है। इसे करने के लिए, इस प्रॉपर्टी को true सेट करें। कोड उदाहरण के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides

**Returns:**
बूलियन - यदि छिपे पृष्ठों को रेंडर किया जाना चाहिए तो true, अन्यथा false।
### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


छिपे पृष्ठों के रेंडरिंग को सक्षम करता है।

प्रेजेंटेशन या स्प्रेडशीट जैसी कुछ फ़ाइलों में छिपे पृष्ठ हो सकते हैं। डिफ़ॉल्ट रूप से, GroupDocs.Viewer इन पृष्ठों को रेंडर नहीं करता है। इसे करने के लिए, इस प्रॉपर्टी को true सेट करें। कोड उदाहरण के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean | यदि छिपे पृष्ठों को रेंडर किया जाना चाहिए तो true, अन्यथा false। |

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


डॉक्यूमेंट में उपयोग किए गए किसी विशेष फ़ॉन्ट को न मिलने पर उपयोग किया जाने वाला डिफ़ॉल्ट फ़ॉन्ट।

इस प्रॉपर्टी का उपयोग करके दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट सेट करें। GroupDocs.Viewer रेंडरिंग के दौरान इस फ़ॉन्ट का उपयोग करता है, न कि किसी भी न स्थापित फ़ॉन्ट का। कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/replace-missing-font/

**Returns:**
java.lang.String - डिफ़ॉल्ट फ़ॉन्ट का नाम।
### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


डॉक्यूमेंट में उपयोग किए गए किसी विशेष फ़ॉन्ट को न मिलने पर उपयोग किया जाने वाला डिफ़ॉल्ट फ़ॉन्ट।

इस प्रॉपर्टी का उपयोग करके दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट सेट करें। GroupDocs.Viewer रेंडरिंग के दौरान इस फ़ॉन्ट का उपयोग करता है, न कि किसी भी न स्थापित फ़ॉन्ट का। कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/replace-missing-font/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String | डिफ़ॉल्ट फ़ॉन्ट का नाम। |

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


आर्काइव फ़ाइलों के दृश्य विकल्प प्राप्त करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/

**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - the archive files view options.
### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


आर्काइव फ़ाइलों के दृश्य विकल्प सेट करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) | आर्काइव फ़ाइलों के दृश्य विकल्प। |

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


CAD ड्राइंग के दृश्य विकल्प प्राप्त करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] और [Specify rendering options for CAD files][].


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - the CAD drawing view options.
### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


CAD ड्राइंग के दृश्य विकल्प सेट करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] और [Specify rendering options for CAD files][].


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [CadOptions](../../com.groupdocs.viewer.options/cadoptions) | CAD ड्राइंग दृश्य विकल्प। |

### isCadOptionsInitialized_Internal() {#isCadOptionsInitialized-Internal--}
```
public boolean isCadOptionsInitialized_Internal()
```




**Returns:**
boolean
### getEmailOptions() {#getEmailOptions--}
```
public final EmailOptions getEmailOptions()
```


ईमेल संदेशों के दृश्य विकल्प प्राप्त करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions) - Email messages view options.
### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


ईमेल संदेशों के दृश्य विकल्प सेट करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) | ईमेल संदेशों के दृश्य विकल्प। |

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


MS Outlook डेटा फ़ाइलों के दृश्य विकल्प प्राप्त करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/

**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) - MS Outlook data files view options.
### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


MS Outlook डेटा फ़ाइलों के दृश्य विकल्प सेट करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) | सेट करने के लिए MS Outlook डेटा फ़ाइलों के दृश्य विकल्प। |

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


PDF दस्तावेज़ों के दृश्य विकल्प प्राप्त करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/

**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - the PDF documents view options.
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


PDF दस्तावेज़ों के दृश्य विकल्प प्राप्त करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) | PDF दस्तावेज़ों के दृश्य विकल्प। |

### getMailStorageOptions() {#getMailStorageOptions--}
```
public MailStorageOptions getMailStorageOptions()
```


Lotus Notes स्टोरेज डेटा फ़ाइलों के दृश्य विकल्प प्राप्त करता है।

**Returns:**
[MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) - the Lotus Notes storage data files view options.
### setMailStorageOptions(MailStorageOptions mailStorageOptions) {#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-}
```
public void setMailStorageOptions(MailStorageOptions mailStorageOptions)
```


Lotus Notes स्टोरेज डेटा फ़ाइलों के दृश्य विकल्प सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mailStorageOptions | [MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) | Lotus Notes स्टोरेज डेटा फ़ाइलों के दृश्य विकल्प। |

### getProjectManagementOptions() {#getProjectManagementOptions--}
```
public final ProjectManagementOptions getProjectManagementOptions()
```


प्रोजेक्ट मैनेजमेंट फ़ाइलों के दृश्य विकल्प प्राप्त करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/

**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) - the project management files view options.
### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


प्रोजेक्ट मैनेजमेंट फ़ाइलों के दृश्य विकल्प सेट करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) | सेट करने के लिए प्रोजेक्ट मैनेजमेंट फ़ाइलों के दृश्य विकल्प। |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


स्प्रेडशीट फ़ाइलों के दृश्य विकल्प प्राप्त करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files], [Split a worksheet into pages][], और [Specify spreadsheet rendering options][].


[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Split a worksheet into pages]: https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/
[Specify spreadsheet rendering options]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - the spreadsheet files view options.
### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


स्प्रेडशीट फ़ाइलों के दृश्य विकल्प सेट करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files], [Split a worksheet into pages][], और [Specify spreadsheet rendering options][].


[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Split a worksheet into pages]: https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/
[Specify spreadsheet rendering options]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) | स्प्रेडशीट फ़ाइलों के दृश्य विकल्प। |

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


वर्ड प्रोसेसिंग फ़ाइलों के दृश्य विकल्प।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/

**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - the Word processing options for rendering Word documents.
### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


वर्ड प्रोसेसिंग फ़ाइलों के दृश्य विकल्प।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) | Word दस्तावेज़ों को रेंडर करने के लिए Word प्रोसेसिंग विकल्प। |

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


दस्तावेज़ देखने के समय Visio फ़ाइलों को प्रोसेस करने के लिए रेंडरिंग विकल्प प्राप्त करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/

**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) - the Visio rendering options for processing Visio files.
### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


दस्तावेज़ देखने के समय Visio फ़ाइलों को प्रोसेस करने के लिए रेंडरिंग विकल्प सेट करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | Visio फ़ाइलों को प्रोसेस करने के लिए Visio रेंडरिंग विकल्प। |

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


प्रेजेंटेशन दस्तावेज़ों को प्रोसेस करने के लिए दृश्य विकल्प प्राप्त करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/

**Returns:**
com.groupdocs.viewer.options.PresentationOptions - प्रस्तुति दस्तावेज़ों को प्रोसेस करने के लिए प्रस्तुति दृश्य विकल्प।
### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


प्रेजेंटेशन दस्तावेज़ों को प्रोसेस करने के लिए दृश्य विकल्प सेट करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presentationOptions | com.groupdocs.viewer.options.PresentationOptions | प्रस्तुति दस्तावेज़ों को प्रोसेस करने के लिए प्रस्तुति दृश्य विकल्प। |

### getWebDocumentOptions() {#getWebDocumentOptions--}
```
public WebDocumentOptions getWebDocumentOptions()
```


वेब दस्तावेज़ों को रेंडर करते समय आउटपुट HTML/PDF/PNG/JPEG की उपस्थिति को अनुकूलित करने वाले रेंडरिंग विकल्प प्राप्त करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-web-documents/

**Returns:**
com.groupdocs.viewer.options.WebDocumentOptions - रेंडरिंग विकल्पों को कस्टमाइज़ करने के लिए WebDocumentOptions ऑब्जेक्ट।
### setWebDocumentOptions(WebDocumentOptions webDocumentOptions) {#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-}
```
public void setWebDocumentOptions(WebDocumentOptions webDocumentOptions)
```


वेब दस्तावेज़ों को रेंडर करते समय आउटपुट HTML/PDF/PNG/JPEG की उपस्थिति को अनुकूलित करने वाले रेंडरिंग विकल्प सेट करता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-web-documents/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| webDocumentOptions | com.groupdocs.viewer.options.WebDocumentOptions | रेंडरिंग विकल्पों को कस्टमाइज़ करने के लिए WebDocumentOptions ऑब्जेक्ट। |

