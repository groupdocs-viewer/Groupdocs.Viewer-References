---
title: "LoadOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "फ़ाइल खोलने के लिए उपयोग किए जाने वाले विकल्प प्रदान करता है।"
type: docs
weight: 18
url: /hi/java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

फ़ाइल खोलने के लिए उपयोग किए जाने वाले विकल्प प्रदान करता है।


LoadOptions क्लास विभिन्न सेटिंग्स और पैरामीटरों को समाहित करती है जिन्हें उपयोग किया जा सकता है
यह निर्दिष्ट करने के लिए कि फ़ाइल को GroupDocs.Viewer घटक में कैसे खोला और लोड किया जाना चाहिए।
विवरण के लिए, देखें यह [पृष्ठ](../https://docs.groupdocs.com/viewer/java/loading/) और इसके उपपृष्ठ।


उदाहरण उपयोग:

````

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
````


## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | नए उदाहरण को प्रारंभ करता है |
LoadOptions
class।
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | नए उदाहरण को प्रारंभ करता है |
LoadOptions
class।
|
## Fields

| Field | विवरण |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## Methods

| Method | विवरण |
| --- | --- |
|  | [isTryRepair()](#isTryRepair--) | सक्षम होने पर, GroupDocs.Viewer PDF दस्तावेज़ों में संरचनात्मक भ्रष्टाचार को ठीक करने का प्रयास करता है। |
|
|  | [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | सक्षम होने पर, GroupDocs.Viewer PDF दस्तावेज़ों में संरचनात्मक भ्रष्टाचार को ठीक करने का प्रयास करता है। |
|
|  | [getFileType()](#getFileType--) | खोलने के लिए फ़ाइल का प्रकार प्राप्त करता है। |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | खोलने के लिए फ़ाइल का प्रकार सेट करता है। |
|
|  | [getPassword()](#getPassword--) | एन्क्रिप्टेड फ़ाइल खोलने के लिए पासवर्ड प्राप्त करता है। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | एन्क्रिप्टेड फ़ाइल खोलने के लिए पासवर्ड सेट करता है। |
|
|  | [getCharset()](#getCharset--) | टेक्स्ट-आधारित फ़ाइलें या ईमेल संदेश खोलते समय उपयोग किया जाने वाला कैरेक्टर सेट जैसे |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
और [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | टेक्स्ट-आधारित फ़ाइलें या ईमेल संदेश खोलते समय उपयोग किया जाने वाला कैरेक्टर सेट जैसे |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
और [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [isDetectCharset()](#isDetectCharset--) | यह विकल्प [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV), और [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) फ़ाइलों के कैरेक्टर सेट का पता लगाने को सक्षम करता है। |
|
|  | [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | यह विकल्प [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV), और [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) फ़ाइलों के कैरेक्टर सेट का पता लगाने को सक्षम करता है। |
|
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | बाहरी संसाधनों को लोड करने के लिए टाइमआउट प्राप्त करता है। |
|
|  | [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | बाहरी संसाधनों को लोड करने के लिए टाइमआउट सेट करता है, जैसे ग्राफ़िक्स। |
|
|  | [getUrlConnectTimeout()](#getUrlConnectTimeout--) | दस्तावेज़ लोड करने के लिए java.net.URL का उपयोग करके एक [Viewer](../../com.groupdocs.viewer/viewer) बनाने के लिए कनेक्शन टाइमआउट प्राप्त करता है। |
|
|  | [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | दस्तावेज़ लोड करने के लिए java.net.URL का उपयोग करके एक [Viewer](../../com.groupdocs.viewer/viewer) बनाने के लिए कनेक्शन टाइमआउट सेट करता है। |
|
|  | [getUrlReadTimeout()](#getUrlReadTimeout--) | दस्तावेज़ लोड करने के लिए java.net.URL का उपयोग करके एक [Viewer](../../com.groupdocs.viewer/viewer) बनाने के लिए रीड टाइमआउट प्राप्त करता है। |
|
|  | [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | दस्तावेज़ लोड करने के लिए java.net.URL का उपयोग करके एक [Viewer](../../com.groupdocs.viewer/viewer) बनाने के लिए रीड टाइमआउट सेट करता है। |
|
|  | [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | आर्काइव निकालने की प्रक्रिया को नियंत्रित करने के लिए सुरक्षा विकल्प प्राप्त करता है। |
|
|  | [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | आर्काइव निकालने की प्रक्रिया को नियंत्रित करने के लिए सुरक्षा विकल्प सेट करता है। |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | जब true पर सेट किया जाता है, तो सभी बाहरी संसाधन जैसे छवियां लोड नहीं होंगी, सिवाय #getWhitelistedResources().getWhitelistedResources() के। |
|
|  | [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | जब true पर सेट किया जाता है, तो सभी बाहरी संसाधन जैसे छवियां लोड नहीं होंगी, सिवाय #getWhitelistedResources().getWhitelistedResources() के। |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | URL फ्रैगमेंट की सूची जो बाहरी संसाधनों से संबंधित है और जिन्हें #isSkipExternalResources().isSkipExternalResources() को `true` पर सेट करने पर लोड किया जाना चाहिए। |
|
|  | [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | बाहरी संसाधनों से संबंधित URL अंशों की सूची सेट करता है, जिन्हें #isSkipExternalResources().isSkipExternalResources() को `true` पर सेट करने पर लोड किया जाना चाहिए। |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


नए उदाहरण को प्रारंभ करता है
LoadOptions
class।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/)।


### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


नए उदाहरण को प्रारंभ करता है
LoadOptions
class।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | खोलने के लिए फ़ाइल का प्रकार। |
|

### DEFAULT_URL_CONNECT_TIMEOUT {#DEFAULT-URL-CONNECT-TIMEOUT}
```
public static final int DEFAULT_URL_CONNECT_TIMEOUT
```


### DEFAULT_URL_READ_TIMEOUT {#DEFAULT-URL-READ-TIMEOUT}
```
public static final int DEFAULT_URL_READ_TIMEOUT
```


### _tryRepair {#-tryRepair}
```
public boolean _tryRepair
```


### isTryRepair() {#isTryRepair--}
```
public boolean isTryRepair()
```


सक्षम होने पर, GroupDocs.Viewer PDF दस्तावेज़ों में संरचनात्मक भ्रष्टाचार को ठीक करने का प्रयास करता है। डिफ़ॉल्ट मान false है।


यह सुविधा PDF दस्तावेज़ में निम्नलिखित समस्याओं को संबोधित करती है:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Returns:**
boolean
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


सक्षम होने पर, GroupDocs.Viewer PDF दस्तावेज़ों में संरचनात्मक भ्रष्टाचार को ठीक करने का प्रयास करता है। डिफ़ॉल्ट मान false है।


यह सुविधा PDF दस्तावेज़ में निम्नलिखित समस्याओं को संबोधित करती है:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| tryRepair | boolean |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


खोलने के लिए फ़ाइल का प्रकार प्राप्त करता है।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/)।


**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.

### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


खोलने के लिए फ़ाइल का प्रकार सेट करता है।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल प्रकार। |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


एन्क्रिप्टेड फ़ाइल खोलने के लिए पासवर्ड प्राप्त करता है।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/)।


**Returns:**
java.lang.String - फ़ाइल खोलने के लिए पासवर्ड।

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


एन्क्रिप्टेड फ़ाइल खोलने के लिए पासवर्ड सेट करता है।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | फ़ाइल खोलने के लिए पासवर्ड। |
|

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


टेक्स्ट-आधारित फ़ाइलें या ईमेल संदेश खोलते समय उपयोग किया जाने वाला कैरेक्टर सेट जैसे
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
और [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
डिफ़ॉल्ट मान java.nio.charset.StandardCharsets#UTF_8.UTF_8 है। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/)।

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // कैरेक्ट सेट करें

try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
java.nio.charset.Charset
### setCharset(Charset value) {#setCharset-java.nio.charset.Charset-}
```
public final void setCharset(Charset value)
```


टेक्स्ट-आधारित फ़ाइलें या ईमेल संदेश खोलते समय उपयोग किया जाने वाला कैरेक्टर सेट जैसे
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
और [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
डिफ़ॉल्ट मान java.nio.charset.StandardCharsets#UTF_8.UTF_8 है। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/)।

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // कैरेक्ट सेट करें

try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


यह विकल्प [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV), और [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) फ़ाइलों के कैरेक्ट डिटेक्शन को सक्षम करता है। यदि कैरेक्ट का पता नहीं चल पाता है तो डिफ़ॉल्ट [getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--) का उपयोग किया जाता है।

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


यदि एन्कोडिंग का पता नहीं चल पाता है, तो डिफ़ॉल्ट उपयोग किया जाता है। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/)।

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // एन्कोडिंग डिटेक्शन सक्षम करें

try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setDetectCharset(boolean detectCharset) {#setDetectCharset-boolean-}
```
public void setDetectCharset(boolean detectCharset)
```


यह विकल्प [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV), और [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) फ़ाइलों के कैरेक्ट डिटेक्शन को सक्षम करता है। यदि कैरेक्ट का पता नहीं चल पाता है तो डिफ़ॉल्ट [getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--) का उपयोग किया जाता है।

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


यदि एन्कोडिंग का पता नहीं चल पाता है, तो डिफ़ॉल्ट उपयोग किया जाता है। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/)।

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // एन्कोडिंग डिटेक्शन सक्षम करें

try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| detectCharset | boolean |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


बाहरी संसाधनों को लोड करने के लिए टाइमआउट प्राप्त करता है।


**Note:** The default value is 10 seconds.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)


डिफ़ॉल्ट मान 30 सेकंड है। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents)।

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setResourceLoadingTimeout(5000); // संसाधन लोडिंग टाइमआउट को 5 सेकंड पर सेट करें

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
int
### setResourceLoadingTimeout(int resourceLoadingTimeout) {#setResourceLoadingTimeout-int-}
```
public void setResourceLoadingTimeout(int resourceLoadingTimeout)
```


बाहरी संसाधनों को लोड करने के लिए टाइमआउट सेट करता है, जैसे ग्राफ़िक्स।


***Note:** The default value is 30 seconds.*


यह विकल्प उन वर्ड प्रोसेसिंग दस्तावेज़ों के लिए समर्थित है जिनमें बाहरी संसाधन होते हैं।
डिफ़ॉल्ट मान 30 सेकंड है। कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | resourceLoadingTimeout | int | लोडिंग टाइमआउट, मिलीसेकंड। |
|

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


दस्तावेज़ लोड करने के लिए java.net.URL का उपयोग करके एक [Viewer](../../com.groupdocs.viewer/viewer) बनाने के लिए कनेक्शन टाइमआउट प्राप्त करता है।


***Note:** The default value is 5 seconds.*


**Returns:**
int - कनेक्शन टाइमआउट।

### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


दस्तावेज़ लोड करने के लिए java.net.URL का उपयोग करके एक [Viewer](../../com.groupdocs.viewer/viewer) बनाने के लिए कनेक्शन टाइमआउट सेट करता है।


***Note:** The default value is 5 seconds.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | urlConnectTimeout | int | कनेक्शन टाइमआउट। |
|

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


दस्तावेज़ लोड करने के लिए java.net.URL का उपयोग करके एक [Viewer](../../com.groupdocs.viewer/viewer) बनाने के लिए रीड टाइमआउट प्राप्त करता है।


***Note:** The default value is 30 seconds.*


**Returns:**
int - रीड टाइमआउट।

### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


दस्तावेज़ लोड करने के लिए java.net.URL का उपयोग करके एक [Viewer](../../com.groupdocs.viewer/viewer) बनाने के लिए रीड टाइमआउट सेट करता है।


***Note:** The default value is 30 seconds.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | urlReadTimeout | int | रीड टाइमआउट। |
|

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


आर्काइव निकालने की प्रक्रिया को नियंत्रित करने के लिए सुरक्षा विकल्प प्राप्त करता है।


***Note:** Not each archive type supports all options.*


**Returns:**
com.groupdocs.viewer.options.ArchiveSecurityOptions - आर्काइव निकालने की प्रक्रिया को कॉन्फ़िगर करने के लिए विकल्प ऑब्जेक्ट।

### setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions) {#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-}
```
public void setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)
```


आर्काइव निकालने की प्रक्रिया को नियंत्रित करने के लिए सुरक्षा विकल्प सेट करता है।


***Note:** Not each archive type supports all options.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | आर्काइव निकालने की प्रक्रिया को कॉन्फ़िगर करने के लिए विकल्प ऑब्जेक्ट। |
|

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


जब true पर सेट किया जाता है, तो सभी बाहरी संसाधन जैसे छवियां लोड नहीं होंगी, सिवाय #getWhitelistedResources().getWhitelistedResources() के।

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // बाहरी संसाधनों का लोडिंग छोड़ें

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```


जब true पर सेट किया जाता है, तो सभी बाहरी संसाधन जैसे छवियां लोड नहीं होंगी, सिवाय #getWhitelistedResources().getWhitelistedResources() के।

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // बाहरी संसाधनों का लोडिंग छोड़ें

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | skipExternalResources | boolean | बाहरी संसाधनों के लोडिंग को सक्षम या अक्षम करने के लिए फ़्लैग। |
|

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


URL फ्रैगमेंट की सूची जो बाहरी संसाधनों से संबंधित है और जिन्हें #isSkipExternalResources().isSkipExternalResources() को `true` पर सेट करने पर लोड किया जाना चाहिए।

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // बाहरी संसाधनों का लोडिंग छोड़ें
loadOptions.getWhitelistedResources().add("avatars.githubusercontent.com"); // संसाधन URL में 'avatars.githubusercontent.com' फ्रैगमेंट वाले बाहरी संसाधनों का लोडिंग सक्षम करें
try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whitelistedResources) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whitelistedResources)
```


बाहरी संसाधनों से संबंधित URL अंशों की सूची सेट करता है, जिन्हें #isSkipExternalResources().isSkipExternalResources() को `true` पर सेट करने पर लोड किया जाना चाहिए।

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // बाहरी संसाधनों का लोडिंग छोड़ें
loadOptions.setWhitelistedResources(Arrays.asList("avatars.githubusercontent.com")); // संसाधन URL में 'avatars.githubusercontent.com' फ्रैगमेंट वाले बाहरी संसाधनों का लोडिंग सक्षम करें
try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | whitelistedResources | java.util.List<java.lang.String> | बाहरी संसाधनों के लोड होने वाले URL फ्रैगमेंट की सूची। |
|

