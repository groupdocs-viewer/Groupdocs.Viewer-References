---
title: "LoadOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "फ़ाइल खोलने के लिए उपयोग किए जाने वाले विकल्प प्रदान करता है।"
type: docs
weight: 18
url: /hi/nodejs-java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

फ़ाइल खोलने के लिए उपयोग किए जाने वाले विकल्प प्रदान करता है।

LoadOptions क्लास विभिन्न सेटिंग्स और पैरामीटर को समाहित करती है जिन्हें यह निर्दिष्ट करने के लिए उपयोग किया जा सकता है कि फ़ाइल को GroupDocs.Viewer घटक में कैसे खोला और लोड किया जाना चाहिए। विवरण के लिए, देखें यह [पृष्ठ][] और इसके उपवर्ग।

उदाहरण उपयोग:

```

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
```


[page]: https://docs.groupdocs.com/viewer/java/loading/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | LoadOptions क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | LoadOptions क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [isTryRepair()](#isTryRepair--) | सक्रिय होने पर, GroupDocs.Viewer PDF दस्तावेज़ों में संरचनात्मक भ्रष्टाचार को ठीक करने का प्रयास करता है। |
| [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | सक्रिय होने पर, GroupDocs.Viewer PDF दस्तावेज़ों में संरचनात्मक भ्रष्टाचार को ठीक करने का प्रयास करता है। |
| [getFileType()](#getFileType--) | खोलने वाली फ़ाइल का प्रकार प्राप्त करता है। |
| [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | खोलने वाली फ़ाइल का प्रकार सेट करता है। |
| [getPassword()](#getPassword--) | एन्क्रिप्टेड फ़ाइल खोलने के लिए पासवर्ड प्राप्त करता है। |
| [setPassword(String value)](#setPassword-java.lang.String-) | एन्क्रिप्टेड फ़ाइल खोलने के लिए पासवर्ड सेट करता है। |
| [getCharset()](#getCharset--) | टेक्स्ट-आधारित फ़ाइलों या ईमेल संदेशों को खोलते समय उपयोग किया जाने वाला कैरेक्टर सेट, जैसे कि [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), और [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG)। |
| [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | टेक्स्ट-आधारित फ़ाइलों या ईमेल संदेशों को खोलते समय उपयोग किया जाने वाला कैरेक्टर सेट, जैसे कि [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), और [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG)। |
| [isDetectCharset()](#isDetectCharset--) | यह विकल्प [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV), और [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) फ़ाइलों के कैरेक्टर सेट डिटेक्शन को सक्षम करता है। |
| [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | यह विकल्प [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV), और [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) फ़ाइलों के कैरेक्टर सेट डिटेक्शन को सक्षम करता है। |
| [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | बाहरी संसाधनों को लोड करने के लिए टाइमआउट प्राप्त करता है। |
| [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | ग्राफ़िक्स जैसी बाहरी संसाधनों को लोड करने के लिए टाइमआउट सेट करता है। |
| [getUrlConnectTimeout()](#getUrlConnectTimeout--) | java.net.URL का उपयोग करके दस्तावेज़ लोड करने हेतु एक [Viewer](../../com.groupdocs.viewer/viewer) बनाने के लिए कनेक्शन टाइमआउट प्राप्त करता है। |
| [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | java.net.URL का उपयोग करके दस्तावेज़ लोड करने हेतु एक [Viewer](../../com.groupdocs.viewer/viewer) बनाने के लिए कनेक्शन टाइमआउट सेट करता है। |
| [getUrlReadTimeout()](#getUrlReadTimeout--) | java.net.URL का उपयोग करके दस्तावेज़ लोड करने हेतु एक [Viewer](../../com.groupdocs.viewer/viewer) बनाने के लिए रीड टाइमआउट प्राप्त करता है। |
| [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | java.net.URL का उपयोग करके दस्तावेज़ लोड करने हेतु एक [Viewer](../../com.groupdocs.viewer/viewer) बनाने के लिए रीड टाइमआउट सेट करता है। |
| [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | आर्काइव निकालने की प्रक्रिया को नियंत्रित करने के लिए सुरक्षा विकल्प प्राप्त करता है। |
| [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | आर्काइव निकालने की प्रक्रिया को नियंत्रित करने के लिए सुरक्षा विकल्प सेट करता है। |
| [isSkipExternalResources()](#isSkipExternalResources--) | जब इसे true पर सेट किया जाता है, तो सभी बाहरी संसाधन जैसे छवियां लोड नहीं होंगी, सिवाय \#getWhitelistedResources().getWhitelistedResources() के। |
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | जब इसे true पर सेट किया जाता है, तो सभी बाहरी संसाधन जैसे छवियां लोड नहीं होंगी, सिवाय \#getWhitelistedResources().getWhitelistedResources() के। |
| [getWhitelistedResources()](#getWhitelistedResources--) | जब \#isSkipExternalResources().isSkipExternalResources() को `true` पर सेट किया जाता है, तो लोड किए जाने वाले बाहरी संसाधनों से संबंधित URL अंशों की सूची। |
| [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | जब \#isSkipExternalResources().isSkipExternalResources() को `true` पर सेट किया जाता है, तो लोड किए जाने वाले बाहरी संसाधनों से संबंधित URL अंशों की सूची सेट करता है। |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


LoadOptions क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


LoadOptions क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | खोलने के लिए फ़ाइल का प्रकार। |

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


जब सक्षम किया जाता है, तो GroupDocs.Viewer PDF दस्तावेज़ों में संरचनात्मक भ्रष्टाचार को ठीक करने का प्रयास करता है। डिफ़ॉल्ट मान false है।

यह सुविधा PDF दस्तावेज़ में निम्नलिखित समस्याओं को संबोधित करती है:

 *  Broken references within the document (incorrect object offsets in the Cross-reference list).
 *  Missing critical elements like root object, page object, or page content.
 *  Circular references (Form X-object referencing itself).

**Returns:**
boolean
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


जब सक्षम किया जाता है, तो GroupDocs.Viewer PDF दस्तावेज़ों में संरचनात्मक भ्रष्टाचार को ठीक करने का प्रयास करता है। डिफ़ॉल्ट मान false है।

यह सुविधा PDF दस्तावेज़ में निम्नलिखित समस्याओं को संबोधित करती है:

 *  Broken references within the document (incorrect object offsets in the Cross-reference list).
 *  Missing critical elements like root object, page object, or page content.
 *  Circular references (Form X-object referencing itself).

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tryRepair | boolean |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


खोलने वाली फ़ाइल का प्रकार प्राप्त करता है।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.
### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


खोलने वाली फ़ाइल का प्रकार सेट करता है।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल प्रकार। |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


एन्क्रिप्टेड फ़ाइल खोलने के लिए पासवर्ड प्राप्त करता है।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/load-password-protected-document/

**Returns:**
java.lang.String - फ़ाइल खोलने के लिए पासवर्ड।
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


एन्क्रिप्टेड फ़ाइल खोलने के लिए पासवर्ड सेट करता है।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/load-password-protected-document/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String | फ़ाइल खोलने के लिए पासवर्ड। |

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


टेक्स्ट-आधारित फ़ाइलों या ईमेल संदेशों को खोलते समय उपयोग किया जाने वाला कैरेक्टर सेट, जैसे कि [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), और [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG)।

डिफ़ॉल्ट मान java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8 है। कोड उदाहरण के लिए, देखें [documentation][].

**Learn more**

 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render email messages as HTML, PDF, PNG, and JPEG files][Render email messages as HTML_ PDF_ PNG_ and JPEG files]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setCharset(StandardCharsets.US_ASCII); // Set the charset

 try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files
[Render email messages as HTML_ PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Returns:**
java.nio.charset.Charset
### setCharset(Charset value) {#setCharset-java.nio.charset.Charset-}
```
public final void setCharset(Charset value)
```


टेक्स्ट-आधारित फ़ाइलों या ईमेल संदेशों को खोलते समय उपयोग किया जाने वाला कैरेक्टर सेट, जैसे कि [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), और [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG)।

डिफ़ॉल्ट मान java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8 है। कोड उदाहरण के लिए, देखें [documentation][].

**Learn more**

 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render email messages as HTML, PDF, PNG, and JPEG files][Render email messages as HTML_ PDF_ PNG_ and JPEG files]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setCharset(StandardCharsets.US_ASCII); // Set the charset

 try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files
[Render email messages as HTML_ PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


यह विकल्प [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV), और [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) फ़ाइलों के कैरेक्टर सेट का पता लगाने को सक्षम करता है। यदि कैरेक्टर सेट का पता नहीं चल पाता है तो डिफ़ॉल्ट रूप से [getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--) उपयोग किया जाता है।

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

यदि एन्कोडिंग का पता नहीं चल पाता है, तो डिफ़ॉल्ट उपयोग किया जाता है। कोड उदाहरण के लिए, देखें [documentation][].

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setDetectCharset(true); // Enable encoding detection

 try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/

**Returns:**
boolean
### setDetectCharset(boolean detectCharset) {#setDetectCharset-boolean-}
```
public void setDetectCharset(boolean detectCharset)
```


यह विकल्प [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV), और [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) फ़ाइलों के कैरेक्टर सेट का पता लगाने को सक्षम करता है। यदि कैरेक्टर सेट का पता नहीं चल पाता है तो डिफ़ॉल्ट रूप से [getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--) उपयोग किया जाता है।

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

यदि एन्कोडिंग का पता नहीं चल पाता है, तो डिफ़ॉल्ट उपयोग किया जाता है। कोड उदाहरण के लिए, देखें [documentation][].

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setDetectCharset(true); // Enable encoding detection

 try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| detectCharset | boolean |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


बाहरी संसाधनों को लोड करने के लिए टाइमआउट प्राप्त करता है।

**Note:** The default value is 10 seconds.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

डिफ़ॉल्ट मान 30 सेकंड है। कोड उदाहरण के लिए, देखें [documentation][].

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setResourceLoadingTimeout(5000); // Set resource loading timeout to 5 seconds

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents

**Returns:**
int
### setResourceLoadingTimeout(int resourceLoadingTimeout) {#setResourceLoadingTimeout-int-}
```
public void setResourceLoadingTimeout(int resourceLoadingTimeout)
```


ग्राफ़िक्स जैसी बाहरी संसाधनों को लोड करने के लिए टाइमआउट सेट करता है।

***Note:** The default value is 30 seconds.*

यह विकल्प बाहरी संसाधन वाले वर्ड प्रोसेसिंग दस्तावेज़ों के लिए समर्थित है। डिफ़ॉल्ट मान 30 सेकंड है। कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| resourceLoadingTimeout | int | लोडिंग टाइमआउट, मिलीसेकंड। |

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


java.net.URL का उपयोग करके दस्तावेज़ लोड करने हेतु एक [Viewer](../../com.groupdocs.viewer/viewer) बनाने के लिए कनेक्शन टाइमआउट प्राप्त करता है।

***Note:** The default value is 5 seconds.*

**Returns:**
int - कनेक्शन टाइमआउट।
### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


java.net.URL का उपयोग करके दस्तावेज़ लोड करने हेतु एक [Viewer](../../com.groupdocs.viewer/viewer) बनाने के लिए कनेक्शन टाइमआउट सेट करता है।

***Note:** The default value is 5 seconds.*

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| urlConnectTimeout | int | कनेक्शन टाइमआउट। |

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


java.net.URL का उपयोग करके दस्तावेज़ लोड करने हेतु एक [Viewer](../../com.groupdocs.viewer/viewer) बनाने के लिए रीड टाइमआउट प्राप्त करता है।

***Note:** The default value is 30 seconds.*

**Returns:**
int - पढ़ने का टाइमआउट।
### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


java.net.URL का उपयोग करके दस्तावेज़ लोड करने हेतु एक [Viewer](../../com.groupdocs.viewer/viewer) बनाने के लिए रीड टाइमआउट सेट करता है।

***Note:** The default value is 30 seconds.*

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| urlReadTimeout | int | रीड टाइमआउट। |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | आर्काइव निकालने की प्रक्रिया को कॉन्फ़िगर करने के लिए विकल्प ऑब्जेक्ट। |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


जब इसे true पर सेट किया जाता है, तो सभी बाहरी संसाधन जैसे छवियां लोड नहीं होंगी, सिवाय \#getWhitelistedResources().getWhitelistedResources() के।

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```


जब इसे true पर सेट किया जाता है, तो सभी बाहरी संसाधन जैसे छवियां लोड नहीं होंगी, सिवाय \#getWhitelistedResources().getWhitelistedResources() के।

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| skipExternalResources | boolean | बाहरी संसाधनों के लोडिंग को सक्षम या अक्षम करने के लिए फ़्लैग। |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


जब \#isSkipExternalResources().isSkipExternalResources() को `true` पर सेट किया जाता है, तो लोड किए जाने वाले बाहरी संसाधनों से संबंधित URL अंशों की सूची।

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources
 loadOptions.getWhitelistedResources().add("avatars.githubusercontent.com"); // Enable loading of external resources that have 'avatars.githubusercontent.com' fragment in resource URL.
 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whitelistedResources) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whitelistedResources)
```


जब \#isSkipExternalResources().isSkipExternalResources() को `true` पर सेट किया जाता है, तो लोड किए जाने वाले बाहरी संसाधनों से संबंधित URL अंशों की सूची सेट करता है।

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources
 loadOptions.setWhitelistedResources(Arrays.asList("avatars.githubusercontent.com")); // Enable loading of external resources that have 'avatars.githubusercontent.com' fragment in resource URL.
 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| whitelistedResources | java.util.List<java.lang.String> | बाहरी संसाधनों से संबंधित URL फ्रैगमेंट की सूची जिन्हें लोड किया जाना चाहिए। |

