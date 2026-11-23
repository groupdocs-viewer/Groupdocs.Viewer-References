---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "वर्ड प्रोसेसिंग दस्तावेज़ों को रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 38
url: /hi/java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

वर्ड प्रोसेसिंग दस्तावेज़ों को रेंडर करने के विकल्प प्रदान करता है।


WordProcessingOptions क्लास वर्ड प्रोसेसिंग दस्तावेज़ों के रेंडरिंग के लिए विकल्प प्रदान करती है।
GroupDocs.Viewer कंपोनेंट में। यह सेटिंग्स और पैरामीटर को समाहित करती है जिन्हें उपयोग किया जा सकता है
वर्ड प्रोसेसिंग फ़ाइलों के रेंडरिंग प्रक्रिया और आउटपुट फ़ॉर्मेट को नियंत्रित करने के लिए।
विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/)।


उदाहरण उपयोग:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [WordProcessingOptions()](#WordProcessingOptions--) | नए उदाहरण को प्रारंभ करता है |
WordProcessingOptions
class।
|
## Methods

| Method | विवरण |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | HTM और HTML फ़ाइलों के रेंडरिंग के लिए पेज आकार प्राप्त करता है। |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | HTM और HTML फ़ाइलों के रेंडरिंग के लिए पेज आकार सेट करता है। |
|
|  | [isRenderTrackedChanges()](#isRenderTrackedChanges--) | निर्देशित करता है कि ट्रैक्ड परिवर्तन (संशोधन) रेंडरिंग सक्षम है या नहीं। |
|
|  | [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | ट्रैक्ड परिवर्तन (संशोधन) रेंडरिंग को सक्षम करने का सेट करता है। |
|
|  | [getLeftMargin()](#getLeftMargin--) | HTML रेंडरिंग के लिए बाएँ पेज मार्जिन प्राप्त करता है। |
|
|  | [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | HTML रेंडरिंग के लिए बाएँ पेज मार्जिन सेट करता है। |
|
|  | [getRightMargin()](#getRightMargin--) | HTML रेंडरिंग के लिए दाएँ पेज मार्जिन प्राप्त करता है। |
|
|  | [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | HTML रेंडरिंग के लिए दाएँ पृष्ठ मार्जिन सेट करता है। |
|
|  | [getTopMargin()](#getTopMargin--) | HTML रेंडरिंग के लिए शीर्ष पृष्ठ मार्जिन प्राप्त करता है। |
|
|  | [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | HTML रेंडरिंग के लिए शीर्ष पृष्ठ मार्जिन सेट करता है। |
|
|  | [getBottomMargin()](#getBottomMargin--) | निचला पृष्ठ मार्जिन (केवल HTML रेंडरिंग के लिए) |
|
|  | [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | HTML रेंडरिंग के लिए निचला पृष्ठ मार्जिन सेट करता है। |
|
|  | [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | यह विकल्प अरबी, हिब्रू, भारतीय लिपियों, लैटिन-आधारित या सायरिलिक-आधारित लिपियों को रेंडर करते समय केरनिंग और अन्य OpenType सुविधाओं को सक्षम करता है। |
|
|  | [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | यह विकल्प अरबी, हिब्रू, भारतीय लिपियों, लैटिन-आधारित या सायरिलिक-आधारित लिपियों को रेंडर करते समय केरनिंग और अन्य OpenType सुविधाओं को सक्षम करता है। |
|
|  | [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | यह दर्शाता है कि HTML या PDF में रेंडर करते समय सामग्री तालिका नेविगेशन को अक्षम किया जाना चाहिए या नहीं। |
|
|  | [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | HTML या PDF में रेंडर करते समय सामग्री तालिका नेविगेशन को अक्षम किया जाना चाहिए या नहीं, सेट करता है। |
|
|  | [isUpdateFields()](#isUpdateFields--) | इनपुट WordProcessing दस्तावेज़ को HTML, PDF, PNG, या JPEG आउटपुट फ़ॉर्मेट में सहेजने से पहले कुछ प्रकार के फ़ील्ड को अपडेट किया जाना चाहिए या नहीं, यह निर्धारित करने वाला मान प्राप्त करता है। |
|
|  | [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | इनपुट WordProcessing दस्तावेज़ को HTML, PDF, PNG, या JPEG आउटपुट फ़ॉर्मेट में सहेजने से पहले कुछ प्रकार के फ़ील्ड को अपडेट किया जाना चाहिए या नहीं, यह निर्धारित करने वाला मान सेट करता है। |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | जेनरेटेड छवियों के लिए डॉट्स प्रति इंच में क्षैतिज रिज़ॉल्यूशन प्राप्त करता है। |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | जनरेट किए गए इमेज की क्षैतिज रेज़ोल्यूशन को डॉट्स प्रति इंच में सेट करता है। |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | जेनरेटेड छवियों के लिए डॉट्स प्रति इंच में लंबवत रिज़ॉल्यूशन प्राप्त करता है। |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | जनरेट किए गए इमेज की लंबवत रेज़ोल्यूशन को डॉट्स प्रति इंच में सेट करता है। |
|
|  | [getPageNumberLocation()](#getPageNumberLocation--) | लोड किए गए WordProcessing दस्तावेज़ के लिए पृष्ठ क्रमांक को जबरन लागू करने की अनुमति देता है। |
|
|  | [setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)](#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-) | लोड किए गए WordProcessing दस्तावेज़ के लिए पृष्ठ क्रमांक को जबरन लागू करने की अनुमति देता है। |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | जाँचें कि विकल्प बदले गए हैं या नहीं। |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


नए उदाहरण को प्रारंभ करता है
WordProcessingOptions
class।
Word processing दस्तावेज़ों को रेंडर करने के विकल्प शामिल हैं। विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes)।


### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


HTM और HTML फ़ाइलों के रेंडरिंग के लिए पेज आकार प्राप्त करता है।


डिफ़ॉल्ट पृष्ठ आकार का उपयोग करते समय, कुछ सामग्री पृष्ठ फ्रेम में फिट नहीं हो सकती है।
सामग्री को फिट करने के लिए, आप बड़े पृष्ठ आकार, जैसे A3, को [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3) का उपयोग करके सेट कर सकते हैं।


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.

### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


HTM और HTML फ़ाइलों के रेंडरिंग के लिए पेज आकार सेट करता है।


डिफ़ॉल्ट पृष्ठ आकार का उपयोग करते समय, कुछ सामग्री पृष्ठ फ्रेम में फिट नहीं हो सकती है।
सामग्री को फिट करने के लिए, आप बड़े पृष्ठ आकार, जैसे A3, को [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3) का उपयोग करके सेट कर सकते हैं।


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | आउटपुट पृष्ठ का आकार। |
|

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


निर्देशित करता है कि ट्रैक्ड परिवर्तन (संशोधन) रेंडरिंग सक्षम है या नहीं।
विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes)।


**Returns:**
boolean -  true  यदि ट्रैक्ड परिवर्तन रेंडरिंग सक्षम है,  false  अन्यथा।

### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


ट्रैक्ड परिवर्तन (संशोधन) रेंडरिंग को सक्षम करने का सेट करता है।
विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | boolean | true  ट्रैक्ड परिवर्तन रेंडरिंग को सक्षम करने के लिए,  false  इसे अक्षम करने के लिए। |
|

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


HTML रेंडरिंग के लिए बाएँ पेज मार्जिन प्राप्त करता है।
विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins)।


**Returns:**
java.lang.Double - बाएँ पृष्ठ मार्जिन मान।

### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


HTML रेंडरिंग के लिए बाएँ पेज मार्जिन सेट करता है।
विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | leftMargin | java.lang.Double | सेट करने के लिए बाएँ पृष्ठ मार्जिन मान। |
|

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


HTML रेंडरिंग के लिए दाएँ पेज मार्जिन प्राप्त करता है।
विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins)।


**Returns:**
java.lang.Double - दाएँ पृष्ठ मार्जिन मान।

### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


HTML रेंडरिंग के लिए दाएँ पृष्ठ मार्जिन सेट करता है।
विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | rightMargin | java.lang.Double | सेट करने के लिए दाएँ पृष्ठ मार्जिन मान। |
|

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


HTML रेंडरिंग के लिए शीर्ष पृष्ठ मार्जिन प्राप्त करता है।
विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins)।


**Returns:**
java.lang.Double - शीर्ष पृष्ठ मार्जिन।

### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


HTML रेंडरिंग के लिए शीर्ष पृष्ठ मार्जिन सेट करता है।
विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | topMargin | java.lang.Double | सेट करने के लिए शीर्ष पृष्ठ मार्जिन। |
|

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


निचला पृष्ठ मार्जिन (केवल HTML रेंडरिंग के लिए)
विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins)।


**Returns:**
java.lang.Double - निचला पृष्ठ मार्जिन।

### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


HTML रेंडरिंग के लिए निचला पृष्ठ मार्जिन सेट करता है।
विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | bottomMargin | java.lang.Double | सेट करने के लिए निचला पृष्ठ मार्जिन। |
|

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


यह विकल्प अरबी, हिब्रू, भारतीय लिपियों, लैटिन-आधारित या सायरिलिक-आधारित लिपियों को रेंडर करते समय केरनिंग और अन्य OpenType सुविधाओं को सक्षम करता है।


**Returns:**
boolean - True यदि OpenType सुविधाएँ सक्षम हैं, अन्यथा false।

### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


यह विकल्प अरबी, हिब्रू, भारतीय लिपियों, लैटिन-आधारित या सायरिलिक-आधारित लिपियों को रेंडर करते समय केरनिंग और अन्य OpenType सुविधाओं को सक्षम करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | enableOpenTypeFeatures | boolean | OpenType सुविधाएँ सक्षम करने के लिए True, अन्यथा false। |
|

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


यह दर्शाता है कि HTML या PDF में रेंडर करते समय तालिका‑सामग्री नेविगेशन को अक्षम किया जाना चाहिए या नहीं। जब यह विकल्प true पर सेट किया जाता है, तो HTML रेंडरिंग के लिए तालिका‑सामग्री से सापेक्ष लिंक को span टैग से बदल दिया जाएगा, जिससे कार्यक्षमता हट जाएगी लेकिन दृश्य रूप बना रहेगा। PDF रेंडरिंग के लिए तालिका‑सामग्री को लिंक के बिना साधारण टेक्स्ट के रूप में रेंडर किया जाएगा।


**Returns:**
boolean - True यदि तालिका‑सामग्री नेविगेशन अक्षम है; अन्यथा false।

### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


HTML या PDF में रेंडर करते समय तालिका‑सामग्री नेविगेशन को अक्षम किया जाना चाहिए या नहीं, यह निर्धारित करता है। जब यह विकल्प true पर सेट किया जाता है, तो HTML रेंडरिंग के लिए तालिका‑सामग्री से सापेक्ष लिंक को span टैग से बदल दिया जाएगा, जिससे कार्यक्षमता हट जाएगी लेकिन दृश्य रूप बना रहेगा। PDF रेंडरिंग के लिए तालिका‑सामग्री को लिंक के बिना साधारण टेक्स्ट के रूप में रेंडर किया जाएगा।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | unlinkTableOfContents | boolean | यह दर्शाता है कि तालिका‑सामग्री नेविगेशन को अक्षम किया जाना चाहिए या नहीं। |
|

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


एक मान प्राप्त करता है जो निर्धारित करता है कि क्या कुछ प्रकार के फ़ील्ड को इनपुट WordProcessing दस्तावेज़ को HTML, PDF, PNG, या JPEG आउटपुट फ़ॉर्मेट में सहेजने से पहले अपडेट किया जाना चाहिए। इस प्रॉपर्टी का डिफ़ॉल्ट मान true \\u2014 फ़ील्ड सहेजने से पहले अपडेट किए जाएंगे।


विवरण के लिए, देखें [दस्तावेज़](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving)।


**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


एक मान सेट करता है जो निर्धारित करता है कि क्या कुछ प्रकार के फ़ील्ड को इनपुट WordProcessing दस्तावेज़ को HTML, PDF, PNG, या JPEG आउटपुट फ़ॉर्मेट में सहेजने से पहले अपडेट किया जाना चाहिए। इस प्रॉपर्टी का डिफ़ॉल्ट मान true \\u2014 फ़ील्ड सहेजने से पहले अपडेट किए जाएंगे।


विवरण के लिए, देखें [दस्तावेज़](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| updateFields | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


उत्पन्न छवियों के लिए क्षैतिज रिज़ॉल्यूशन डॉट्स पर इंच में प्राप्त करता है। यह विकल्प केवल WordProcessing दस्तावेज़ों को PNG या JPEG फ़ॉर्मेट में रेंडर करते समय उपयोग किया जाता है।


डिफ़ॉल्ट मान 96 DPI है। न्यूनतम संभव मान - 72 DPI, अधिकतम संभव मान - 600 DPI।
यदि उपयोगकर्ता द्वारा निर्दिष्ट मान इन सीमाओं से बाहर है, तो न्यूनतम या अधिकतम संभव मान लागू किया जाएगा।


**Returns:**
int - DPI में क्षैतिज रिज़ॉल्यूशन।

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


उत्पन्न छवियों के लिए क्षैतिज रिज़ॉल्यूशन डॉट्स पर इंच में सेट करता है। यह विकल्प केवल WordProcessing दस्तावेज़ों को PNG या JPEG फ़ॉर्मेट में रेंडर करते समय उपयोग किया जाता है।


डिफ़ॉल्ट मान 96 DPI है। न्यूनतम संभव मान - 72 DPI, अधिकतम संभव मान - 600 DPI।
यदि उपयोगकर्ता द्वारा निर्दिष्ट मान इन सीमाओं से बाहर है, तो न्यूनतम या अधिकतम संभव मान लागू किया जाएगा।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | horizontalResolution | int | DPI में क्षैतिज रिज़ॉल्यूशन। |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


उत्पन्न छवियों के लिए ऊर्ध्वाधर रिज़ॉल्यूशन डॉट्स पर इंच में प्राप्त करता है। यह विकल्प केवल WordProcessing दस्तावेज़ों को PNG या JPEG फ़ॉर्मेट में रेंडर करते समय उपयोग किया जाता है।


डिफ़ॉल्ट मान 96 DPI है। न्यूनतम संभव मान - 72 DPI, अधिकतम संभव मान - 600 DPI।
यदि उपयोगकर्ता द्वारा निर्दिष्ट मान इन सीमाओं से बाहर है, तो न्यूनतम या अधिकतम संभव मान लागू किया जाएगा।


**Returns:**
int - DPI में लंबवत रिज़ॉल्यूशन।

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


उत्पन्न छवियों के लिए ऊर्ध्वाधर रिज़ॉल्यूशन डॉट्स पर इंच में सेट करता है। यह विकल्प केवल WordProcessing दस्तावेज़ों को PNG या JPEG फ़ॉर्मेट में रेंडर करते समय उपयोग किया जाता है।


डिफ़ॉल्ट मान 96 DPI है। न्यूनतम संभव मान - 72 DPI, अधिकतम संभव मान - 600 DPI।
यदि उपयोगकर्ता द्वारा निर्दिष्ट मान इन सीमाओं से बाहर है, तो न्यूनतम या अधिकतम संभव मान लागू किया जाएगा।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | verticalResolution | int | DPI में लंबवत रिज़ॉल्यूशन। |
|

### getPageNumberLocation() {#getPageNumberLocation--}
```
public WordsPageNumberLocation getPageNumberLocation()
```


लोड किए गए WordProcessing दस्तावेज़ पर पृष्ठ क्रमांक लागू करने के लिए बाध्य करने की अनुमति देता है। डिफ़ॉल्ट रूप से यह [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 दस्तावेज़ अपरिवर्तित रहता है।


**Returns:**
[WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) - the page number location.

### setPageNumberLocation(WordsPageNumberLocation pageNumberLocation) {#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-}
```
public void setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)
```


लोड किए गए WordProcessing दस्तावेज़ पर पृष्ठ क्रमांक लागू करने के लिए बाध्य करने की अनुमति देता है। डिफ़ॉल्ट रूप से यह [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 दस्तावेज़ अपरिवर्तित रहता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | pageNumberLocation | [WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) | पृष्ठ क्रमांक स्थान। |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


जाँचें कि विकल्प बदले गए हैं या नहीं।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | o | java.lang.Object | समानता के लिए तुलना करने वाला ऑब्जेक्ट। |
|

**Returns:**
बूलियन -  true  यदि विकल्प निर्दिष्ट वस्तु के बराबर हों,  false  अन्यथा।

### hashCode() {#hashCode--}
```
public int hashCode()
```


इस वस्तु के लिए हैश कोड मान की गणना करता है। हैश कोड आधारित है
वस्तु की आंतरिक स्थिति पर और हैश-आधारित डेटा संरचनाओं में उपयोग किया जाता है
जैसे हैश मैप और हैश सेट।
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - इस वस्तु के लिए हैश कोड मान।

