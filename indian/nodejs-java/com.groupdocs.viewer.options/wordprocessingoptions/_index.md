---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "वर्ड प्रोसेसिंग दस्तावेज़ों को रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 38
url: /hi/nodejs-java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

वर्ड प्रोसेसिंग दस्तावेज़ों को रेंडर करने के विकल्प प्रदान करता है।

WordProcessingOptions क्लास GroupDocs.Viewer घटक में वर्ड प्रोसेसिंग दस्तावेज़ों को रेंडर करने के विकल्प प्रदान करती है। यह सेटिंग्स और पैरामीटर को समाहित करती है जिन्हें वर्ड प्रोसेसिंग फ़ाइलों की रेंडरिंग प्रक्रिया और आउटपुट फ़ॉर्मेट को नियंत्रित करने के लिए उपयोग किया जा सकता है। विवरण के लिए, देखें [documentation][].

उदाहरण उपयोग:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [WordProcessingOptions()](#WordProcessingOptions--) | WordProcessingOptions क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getPageSize()](#getPageSize--) | HTM और HTML फ़ाइलों के रेंडरिंग के लिए पेज आकार प्राप्त करता है। |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | HTM और HTML फ़ाइलों के रेंडरिंग के लिए पेज आकार सेट करता है। |
| [isRenderTrackedChanges()](#isRenderTrackedChanges--) | बताता है कि ट्रैक्ड परिवर्तन (रिवीजन) रेंडरिंग सक्षम है या नहीं। |
| [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | ट्रैक्ड परिवर्तन (रिवीजन) रेंडरिंग को सक्षम करने के लिए सेट करता है। |
| [getLeftMargin()](#getLeftMargin--) | HTML रेंडरिंग के लिए बायाँ पेज मार्जिन प्राप्त करता है। |
| [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | HTML रेंडरिंग के लिए बायाँ पेज मार्जिन सेट करता है। |
| [getRightMargin()](#getRightMargin--) | HTML रेंडरिंग के लिए दायाँ पेज मार्जिन प्राप्त करता है। |
| [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | HTML रेंडरिंग के लिए दायाँ पेज मार्जिन सेट करता है। |
| [getTopMargin()](#getTopMargin--) | HTML रेंडरिंग के लिए ऊपर का पेज मार्जिन प्राप्त करता है। |
| [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | HTML रेंडरिंग के लिए शीर्ष पृष्ठ मार्जिन सेट करता है। |
| [getBottomMargin()](#getBottomMargin--) | निचला पृष्ठ मार्जिन (केवल HTML रेंडरिंग के लिए) |
| [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | HTML रेंडरिंग के लिए निचला पृष्ठ मार्जिन सेट करता है। |
| [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | यह विकल्प अरबी, हिब्रू, भारतीय लिपियों, लैटिन-आधारित या सायरिलिक-आधारित लिपियों को रेंडर करते समय करनिंग और अन्य OpenType सुविधाओं को सक्षम करता है। |
| [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | यह विकल्प अरबी, हिब्रू, भारतीय लिपियों, लैटिन-आधारित या सायरिलिक-आधारित लिपियों को रेंडर करते समय करनिंग और अन्य OpenType सुविधाओं को सक्षम करता है। |
| [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | यह दर्शाता है कि HTML या PDF में रेंडर करते समय सामग्री तालिका नेविगेशन को अक्षम किया जाना चाहिए या नहीं। |
| [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | HTML या PDF में रेंडर करते समय सामग्री तालिका नेविगेशन को अक्षम किया जाना चाहिए या नहीं, इसे सेट करता है। |
| [isUpdateFields()](#isUpdateFields--) | एक मान प्राप्त करता है जो निर्धारित करता है कि इनपुट WordProcessing दस्तावेज़ को HTML, PDF, PNG, या JPEG आउटपुट फ़ॉर्मेट में सहेजने से पहले कुछ प्रकार के फ़ील्ड को अपडेट किया जाना चाहिए या नहीं। |
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | एक मान सेट करता है जो निर्धारित करता है कि इनपुट WordProcessing दस्तावेज़ को HTML, PDF, PNG, या JPEG आउटपुट फ़ॉर्मेट में सहेजने से पहले कुछ प्रकार के फ़ील्ड को अपडेट किया जाना चाहिए या नहीं। |
| [equals(Object o)](#equals-java.lang.Object-) | जाँचें कि विकल्प बदले गए हैं या नहीं। |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


WordProcessingOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। इसमें शब्द प्रसंस्करण दस्तावेज़ों को रेंडर करने के विकल्प शामिल हैं। विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


HTM और HTML फ़ाइलों के रेंडरिंग के लिए पेज आकार प्राप्त करता है।

डिफ़ॉल्ट पृष्ठ आकार का उपयोग करने पर कुछ सामग्री पृष्ठ फ्रेम में फिट नहीं हो सकती है। सामग्री को फिट करने के लिए, आप बड़े पृष्ठ आकार, जैसे A3, को [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3) का उपयोग करके सेट कर सकते हैं।

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


HTM और HTML फ़ाइलों के रेंडरिंग के लिए पेज आकार सेट करता है।

डिफ़ॉल्ट पृष्ठ आकार का उपयोग करने पर कुछ सामग्री पृष्ठ फ्रेम में फिट नहीं हो सकती है। सामग्री को फिट करने के लिए, आप बड़े पृष्ठ आकार, जैसे A3, को [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3) का उपयोग करके सेट कर सकते हैं।

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | आउटपुट पृष्ठ का आकार। |

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


बताता है कि ट्रैक्ड परिवर्तन (रिवीजन) रेंडरिंग सक्षम है या नहीं।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Returns:**
boolean -  true  यदि ट्रैक किए गए परिवर्तन रेंडरिंग सक्षम है,  false  अन्यथा।
### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


ट्रैक्ड परिवर्तन (रिवीजन) रेंडरिंग को सक्षम करने के लिए सेट करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean | true  ट्रैक किए गए परिवर्तन रेंडरिंग को सक्षम करने के लिए,  false  इसे अक्षम करने के लिए। |

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


HTML रेंडरिंग के लिए बायाँ पेज मार्जिन प्राप्त करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - बाएँ पृष्ठ मार्जिन का मान।
### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


HTML रेंडरिंग के लिए बायाँ पेज मार्जिन सेट करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| leftMargin | java.lang.Double | सेट करने के लिए बाएँ पृष्ठ मार्जिन का मान। |

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


HTML रेंडरिंग के लिए दायाँ पेज मार्जिन प्राप्त करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - दाएँ पृष्ठ मार्जिन का मान।
### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


HTML रेंडरिंग के लिए दायाँ पेज मार्जिन सेट करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rightMargin | java.lang.Double | सेट करने के लिए दाएँ पृष्ठ मार्जिन का मान। |

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


HTML रेंडरिंग के लिए ऊपर का पेज मार्जिन प्राप्त करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - शीर्ष पृष्ठ मार्जिन।
### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


HTML रेंडरिंग के लिए शीर्ष पृष्ठ मार्जिन सेट करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| topMargin | java.lang.Double | सेट करने के लिए शीर्ष पृष्ठ मार्जिन। |

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


निचला पृष्ठ मार्जिन (केवल HTML रेंडरिंग के लिए)

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - निचला पृष्ठ मार्जिन।
### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


HTML रेंडरिंग के लिए निचला पृष्ठ मार्जिन सेट करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bottomMargin | java.lang.Double | सेट करने के लिए निचला पृष्ठ मार्जिन। |

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


यह विकल्प अरबी, हिब्रू, भारतीय लिपियों, लैटिन-आधारित या सायरिलिक-आधारित लिपियों को रेंडर करते समय करनिंग और अन्य OpenType सुविधाओं को सक्षम करता है।

**Returns:**
boolean - True यदि OpenType सुविधाएँ सक्षम हैं, false अन्यथा।
### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


यह विकल्प अरबी, हिब्रू, भारतीय लिपियों, लैटिन-आधारित या सायरिलिक-आधारित लिपियों को रेंडर करते समय करनिंग और अन्य OpenType सुविधाओं को सक्षम करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| enableOpenTypeFeatures | boolean | सही (True) OpenType सुविधाएँ सक्षम करने के लिए, अन्यथा गलत (false)। |

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


इंगित करता है कि HTML या PDF में रेंडर करते समय सामग्री‑सूची नेविगेशन को निष्क्रिय किया जाना चाहिए या नहीं। जब यह विकल्प true पर सेट किया जाता है, तो HTML रेंडरिंग के लिए, सामग्री‑सूची से सापेक्ष लिंक को span टैग से बदल दिया जाएगा, जिससे कार्यक्षमता हट जाती है लेकिन दृश्य रूप बना रहता है। PDF रेंडरिंग के लिए, सामग्री‑सूची को लिंक के बिना साधारण पाठ के रूप में रेंडर किया जाएगा।

**Returns:**
बूलियन - यदि सामग्री‑सूची नेविगेशन निष्क्रिय है तो True, अन्यथा false।
### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


सेट करता है कि HTML या PDF में रेंडर करते समय सामग्री‑सूची नेविगेशन को निष्क्रिय किया जाना चाहिए या नहीं। जब यह विकल्प true पर सेट किया जाता है, तो HTML रेंडरिंग के लिए, सामग्री‑सूची से सापेक्ष लिंक को span टैग से बदल दिया जाएगा, जिससे कार्यक्षमता हट जाती है लेकिन दृश्य रूप बना रहता है। PDF रेंडरिंग के लिए, सामग्री‑सूची को लिंक के बिना साधारण पाठ के रूप में रेंडर किया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| unlinkTableOfContents | boolean | इंगित करता है कि सामग्री‑सूची नेविगेशन को निष्क्रिय किया जाना चाहिए या नहीं। |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


इनपुट WordProcessing दस्तावेज़ को HTML, PDF, PNG, या JPEG आउटपुट फ़ॉर्मेट में सहेजने से पहले कुछ प्रकार के फ़ील्ड्स को अपडेट किया जाना चाहिए या नहीं, यह निर्धारित करने वाला मान प्राप्त करता है। इस प्रॉपर्टी का डिफ़ॉल्ट मान true \\u2014 फ़ील्ड्स सहेजने से पहले अपडेट किए जाएंगे।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


इनपुट WordProcessing दस्तावेज़ को HTML, PDF, PNG, या JPEG आउटपुट फ़ॉर्मेट में सहेजने से पहले कुछ प्रकार के फ़ील्ड्स को अपडेट किया जाना चाहिए या नहीं, यह निर्धारित करने वाला मान सेट करता है। इस प्रॉपर्टी का डिफ़ॉल्ट मान true \\u2014 फ़ील्ड्स सहेजने से पहले अपडेट किए जाएंगे।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| updateFields | boolean |  |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


जाँचें कि विकल्प बदले गए हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| o | java.lang.Object | समानता की तुलना के लिए ऑब्जेक्ट। |

**Returns:**
बूलियन - यदि विकल्प निर्दिष्ट ऑब्जेक्ट के बराबर हैं तो true, अन्यथा false।
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस वस्तु के लिए हैश कोड मान की गणना करता है। हैश कोड वस्तु की आंतरिक स्थिति पर आधारित होता है और हैश-आधारित डेटा संरचनाओं जैसे हैश मैप और हैश सेट में उपयोग किया जाता है।

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - इस वस्तु के लिए हैश कोड मान।
