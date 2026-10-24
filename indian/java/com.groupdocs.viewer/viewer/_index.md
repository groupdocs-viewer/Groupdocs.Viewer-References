---
title: "Viewer"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "दस्तावेज़ रेंडरिंग प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास का प्रतिनिधित्व करता है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.viewer/viewer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Viewer implements Closeable
```

दस्तावेज़ रेंडरिंग प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास का प्रतिनिधित्व करता है।


Viewer क्लास GroupDocs.Viewer घटक का उपयोग करके दस्तावेज़ रेंडर करने के लिए प्रवेश बिंदु है।
यह विभिन्न स्रोतों से दस्तावेज़ लोड करने, रेंडरिंग प्रक्रिया को अनुकूलित करने, और विभिन्न फ़ॉर्मेट में रेंडर किया गया आउटपुट प्राप्त करने के लिए विधियां और विकल्प प्रदान करता है।


उदाहरण उपयोग:

````

 try (Viewer viewer = new Viewer("source.pdf")) {
     viewer.view(new PngViewOptions("result-page{0}.png"));
 }
 
````


## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [Viewer(InputStream fileStream)](#Viewer-java.io.InputStream-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(InputStream fileStream, boolean leaveOpen)](#Viewer-java.io.InputStream-boolean-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(InputStream fileStream, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(URL url)](#Viewer-java.net.URL-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(URL url, LoadOptions loadOptions)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(URL url, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(FileReader fileReader, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(String filePath)](#Viewer-java.lang.String-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(Path filePath)](#Viewer-java.nio.file.Path-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(String filePath, LoadOptions loadOptions)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(Path filePath, LoadOptions loadOptions)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(String filePath, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(Path filePath, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
## Fields

| Field | विवरण |
| --- | --- |
| [LOAD_OPTIONS](#LOAD-OPTIONS) |  |
| [SETTINGS](#SETTINGS) |  |
| [FILE_READER](#FILE-READER) |  |
| [OPTIONS](#OPTIONS) |  |
## Methods

| Method | विवरण |
| --- | --- |
|  | [getViewInfo(ViewInfoOptions options)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-) | व्यू और दस्तावेज़ की विशिष्ट जानकारी लौटाता है। |
|
|  | [getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-com.groupdocs.viewer.utils.CancellationToken-) | व्यू और दस्तावेज़ की विशिष्ट जानकारी लौटाता है। |
|
|  | [getAttachments()](#getAttachments--) | दस्तावेज़ में सम्मिलित अटैचमेंट्स लौटाता है। |
|
|  | [getAttachments(CancellationToken cancellationToken)](#getAttachments-com.groupdocs.viewer.utils.CancellationToken-) | दस्तावेज़ में सम्मिलित अटैचमेंट्स लौटाता है। |
|
|  | [saveAttachment(Attachment attachment, OutputStream destination)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-) | अटैचमेंट फ़ाइल को गंतव्य स्ट्रीम में सहेजता है। |
|
|  | [saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-com.groupdocs.viewer.utils.CancellationToken-) | अटैचमेंट फ़ाइल को गंतव्य स्ट्रीम में सहेजता है। |
|
|  | [view(ViewOptions options)](#view-com.groupdocs.viewer.options.ViewOptions-) | सभी दस्तावेज़ पृष्ठों का व्यू बनाता है। |
|
|  | [view(ViewOptions options, CancellationToken cancellationToken)](#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-) | सभी दस्तावेज़ पृष्ठों का व्यू बनाता है। |
|
|  | [view(ViewOptions options, int pageNumber)](#view-com.groupdocs.viewer.options.ViewOptions-int-) | विशिष्ट दस्तावेज़ पृष्ठ का व्यू बनाता है। |
|
|  | [view(ViewOptions options, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-int...-) | विशिष्ट दस्तावेज़ पृष्ठों का व्यू बनाता है। |
|
|  | [view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-int...-) | विशिष्ट दस्तावेज़ पृष्ठों का व्यू बनाता है। |
|
|  | [getAllFonts()](#getAllFonts--) | लोड किए गए दस्तावेज़ों में उपयोग किए गए सभी फ़ॉन्ट्स लौटाता है, जिसमें दस्तावेज़ में एम्बेडेड फ़ॉन्ट्स और ऑपरेटिंग सिस्टम में स्थापित सिस्टम फ़ॉन्ट्स शामिल हैं। |
|
|  | [search(SearchHighlightOptions options)](#search-com.groupdocs.viewer.options.SearchHighlightOptions-) | प्रदान किए गए विकल्पों के अनुसार लोड किए गए दस्तावेज़ में टेक्स्ट खोज करता है और मिलने वाले मिलानों को हाइलाइट करता है (यदि पाए जाएँ)। |
|
|  | [getFileInfo()](#getFileInfo--) | फ़ाइल के बारे में जानकारी लौटाता है, जैसे फ़ाइल प्रकार और एक फ़्लैग जो दर्शाता है कि फ़ाइल एन्क्रिप्टेड है या नहीं। |
|
|  | [close()](#close--) | फ़ाइल स्ट्रीम और प्रबंधित आंतरिक संसाधनों को रिलीज़ करता है। |
|
### Viewer(InputStream fileStream) {#Viewer-java.io.InputStream-}
```
public Viewer(InputStream fileStream)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।


GroupDocs.Viewer द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक जानकारी:
[Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | वह मेथड जो एक पढ़ने योग्य स्ट्रीम लौटाता है। |
|

### Viewer(InputStream fileStream, boolean leaveOpen) {#Viewer-java.io.InputStream-boolean-}
```
public Viewer(InputStream fileStream, boolean leaveOpen)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | फ़ाइल स्ट्रीम। |
|
|  | leaveOpen | boolean | Viewer ऑब्जेक्ट डिस्पोज़ होने के बाद स्ट्रीम को खुला रखने के लिए true; अन्यथा false। |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | पढ़ने योग्य स्ट्रीम। |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | फ़ाइल स्ट्रीम। |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |
|
|  | leaveOpen | boolean | Viewer ऑब्जेक्ट डिस्पोज़ होने के बाद स्ट्रीम को खुला रखने के लिए true; अन्यथा false। |
|

### Viewer(InputStream fileStream, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | फ़ाइल स्ट्रीम। |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |
|

### Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | फ़ाइल स्ट्रीम। |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |
|
|  | leaveOpen | boolean | Viewer ऑब्जेक्ट डिस्पोज़ होने के बाद स्ट्रीम को खुला रखने के लिए true; अन्यथा false। |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | फ़ाइल स्ट्रीम। |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | फ़ाइल स्ट्रीम। |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |
|
|  | leaveOpen | boolean | Viewer ऑब्जेक्ट डिस्पोज़ होने के बाद स्ट्रीम को खुला रखने के लिए true; अन्यथा false। |
|

### Viewer(URL url) {#Viewer-java.net.URL-}
```
public Viewer(URL url)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।


GroupDocs.Viewer द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक जानकारी: [GroupDocs.Viewer द्वारा समर्थित दस्तावेज़ फ़ॉर्मेट](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | url | java.net.URL | एक URL जो फ़ाइल को दर्शाता है जिसे Viewer में लोड किया जाना चाहिए। |
|

### Viewer(URL url, LoadOptions loadOptions) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(URL url, LoadOptions loadOptions)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | url | java.net.URL | एक URL जो फ़ाइल को दर्शाता है जिसे Viewer में लोड किया जाना चाहिए। |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |
|

### Viewer(URL url, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | url | java.net.URL | एक URL जो फ़ाइल को दर्शाता है जिसे Viewer में लोड किया जाना चाहिए। |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |
|

### Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | url | java.net.URL | एक URL जो फ़ाइल को दर्शाता है जिसे Viewer में लोड किया जाना चाहिए। |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |
|

### Viewer(FileReader fileReader, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।


यह कंस्ट्रक्टर आपको एक Viewer ऑब्जेक्ट बनाने की अनुमति देता है ताकि आप एक दस्तावेज़ को एक [FileReader](../../com.groupdocs.viewer.interfaces/filereader) से निर्दिष्ट [ViewerSettings](../../com.groupdocs.viewer/viewersettings) के साथ देख सकें।
***Learn more**
* To learn about the file types supported by GroupDocs.Viewer, visit: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* To explore the features of GroupDocs.Viewer for Java, refer to: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | Viewer में लोड किए जाने वाले दस्तावेज़ को सम्मिलित करने वाला [FileReader](../../com.groupdocs.viewer.interfaces/filereader) है। |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer पर लागू किए जाने वाले [ViewerSettings](../../com.groupdocs.viewer/viewersettings) हैं। |
|

### Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।


GroupDocs.Viewer का उपयोग करके दस्तावेज़ लोड करने और देखने की कार्यक्षमता प्रदान करता है।


**Note:** Ensure that the file reader, load options, and settings are properly configured for accurate document processing.


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | फ़ाइल रीडर। |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | लोड विकल्प। |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |
|

### Viewer(String filePath) {#Viewer-java.lang.String-}
```
public Viewer(String filePath)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।
***Learn more:**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | रेंडर करने वाली फ़ाइल का पथ। |
|

### Viewer(Path filePath) {#Viewer-java.nio.file.Path-}
```
public Viewer(Path filePath)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | रेंडर करने वाली फ़ाइल का पथ। |
|

### Viewer(String filePath, LoadOptions loadOptions) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(String filePath, LoadOptions loadOptions)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | रेंडर करने वाली फ़ाइल का पथ। |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |
|

### Viewer(Path filePath, LoadOptions loadOptions) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(Path filePath, LoadOptions loadOptions)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view a document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | रेंडर करने वाली फ़ाइल का पथ। |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |
|

### Viewer(String filePath, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | रेंडर करने वाली फ़ाइल का पथ। |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |
|

### Viewer(Path filePath, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | रेंडर करने वाली फ़ाइल का पथ। |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |
|

### Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | रेंडर करने वाली फ़ाइल का पथ। |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |
|

### Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस प्रारंभ करता है।
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | रेंडर करने वाली फ़ाइल का पथ। |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |
|

### LOAD_OPTIONS {#LOAD-OPTIONS}
```
public static final String LOAD_OPTIONS
```


### SETTINGS {#SETTINGS}
```
public static final String SETTINGS
```


### FILE_READER {#FILE-READER}
```
public static final String FILE_READER
```


### OPTIONS {#OPTIONS}
```
public static final String OPTIONS
```


### getViewInfo(ViewInfoOptions options) {#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-}
```
public final ViewInfo getViewInfo(ViewInfoOptions options)
```


व्यू और दस्तावेज़ की विशिष्ट जानकारी लौटाता है।
***Learn more:**
* Learn more about the document - file type, page count, and other format specific properties: [How to get file information using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+file+information)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | व्यू जानकारी विकल्प। |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.

### getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken) {#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-com.groupdocs.viewer.utils.CancellationToken-}
```
public final ViewInfo getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```


व्यू और दस्तावेज़ की विशिष्ट जानकारी लौटाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | व्यू जानकारी विकल्प। |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | ऑपरेशन को रद्द करने के लिए कैंसलेशन टोकन। |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.

### getAttachments() {#getAttachments--}
```
public final List<Attachment> getAttachments()
```


दस्तावेज़ में सम्मिलित अटैचमेंट्स लौटाता है।
***Learn more:**
* Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+attachments)
* Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Save+attachments)*


**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - दस्तावेज़ में शामिल अटैचमेंट।

### getAttachments(CancellationToken cancellationToken) {#getAttachments-com.groupdocs.viewer.utils.CancellationToken-}
```
public final List<Attachment> getAttachments(CancellationToken cancellationToken)
```


दस्तावेज़ में सम्मिलित अटैचमेंट्स लौटाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | ऑपरेशन को रद्द करने के लिए कैंसलेशन टोकन। |
|

**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - दस्तावेज़ में शामिल अटैचमेंट।

### saveAttachment(Attachment attachment, OutputStream destination) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-}
```
public void saveAttachment(Attachment attachment, OutputStream destination)
```


अटैचमेंट फ़ाइल को गंतव्य स्ट्रीम में सहेजता है।
***Learn more:**
* Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+attachments)
* Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Save+attachments)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | अटैचमेंट। |
|
|  | गंतव्य | java.io.OutputStream | लिखने योग्य स्ट्रीम। |
|

### saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-com.groupdocs.viewer.utils.CancellationToken-}
```
public void saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken)
```


अटैचमेंट फ़ाइल को गंतव्य स्ट्रीम में सहेजता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | अटैचमेंट। |
|
|  | गंतव्य | java.io.OutputStream | लिखने योग्य स्ट्रीम। |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | ऑपरेशन को रद्द करने के लिए कैंसलेशन टोकन। |
|

### view(ViewOptions options) {#view-com.groupdocs.viewer.options.ViewOptions-}
```
public final void view(ViewOptions options)
```


सभी दस्तावेज़ पृष्ठों का व्यू बनाता है।
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | व्यू विकल्प। |
|

### view(ViewOptions options, CancellationToken cancellationToken) {#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-}
```
public final void view(ViewOptions options, CancellationToken cancellationToken)
```


सभी दस्तावेज़ पृष्ठों का व्यू बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | व्यू विकल्प। |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | रेंडरिंग प्रक्रिया को रद्द करने के लिए कैंसलेशन टोकन। |
|

### view(ViewOptions options, int pageNumber) {#view-com.groupdocs.viewer.options.ViewOptions-int-}
```
public final void view(ViewOptions options, int pageNumber)
```


विशिष्ट दस्तावेज़ पृष्ठ का व्यू बनाता है।
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | व्यू विकल्प। |
|
|  | pageNumber | int | देखने के लिए पृष्ठ संख्या। |
|

### view(ViewOptions options, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-int...-}
```
public final void view(ViewOptions options, int[] pageNumbers)
```


विशिष्ट दस्तावेज़ पृष्ठों का व्यू बनाता है।
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | व्यू विकल्प। |
|
|  | pageNumbers | int[] | देखने के लिए पृष्ठ संख्याएँ। |
|

### view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-int...-}
```
public final void view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers)
```


विशिष्ट दस्तावेज़ पृष्ठों का व्यू बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | व्यू विकल्प। |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | रेंडरिंग प्रक्रिया को रद्द करने के लिए कैंसलेशन टोकन। |
|
|  | pageNumbers | int[] | देखने के लिए पृष्ठ संख्याएँ। |
|

### getAllFonts() {#getAllFonts--}
```
public IFontInfo[] getAllFonts()
```


लोड किए गए दस्तावेज़ों में उपयोग किए गए सभी फ़ॉन्ट्स लौटाता है, जिसमें दस्तावेज़ में एम्बेडेड फ़ॉन्ट्स और ऑपरेटिंग सिस्टम में स्थापित सिस्टम फ़ॉन्ट्स शामिल हैं।

विवरण के लिए, देखें
[documentation](../https://docs.groupdocs.com/viewer/net/getting-used-fonts/).


**Returns:**
com.groupdocs.viewer.fonts.IFontInfo[] - दस्तावेज़ में उपयोग किए गए सभी फ़ॉन्ट्स की नॉन-नल सूची, जो इस [Viewer](../../com.groupdocs.viewer/viewer) इंस्टेंस में लोड किया गया है।

### search(SearchHighlightOptions options) {#search-com.groupdocs.viewer.options.SearchHighlightOptions-}
```
public void search(SearchHighlightOptions options)
```


प्रदान किए गए विकल्पों के अनुसार लोड किए गए दस्तावेज़ में टेक्स्ट खोज करता है और मिलने वाले मिलानों को हाइलाइट करता है (यदि पाए जाएँ)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | विकल्प | com.groupdocs.viewer.options.SearchHighlightOptions | खोज और हाइलाइट विकल्प, जिसमें खोजने के लिए टेक्स्ट वाक्यांश शामिल है। null नहीं हो सकता। |
|

### getFileInfo() {#getFileInfo--}
```
public FileInfo getFileInfo()
```


फ़ाइल के बारे में जानकारी लौटाता है, जैसे फ़ाइल प्रकार और एक फ़्लैग जो दर्शाता है कि फ़ाइल एन्क्रिप्टेड है या नहीं।
***Learn more:**
* Learn more about how to check if a file is encrypted: [How to check if a file is encrypted](../https://docs.groupdocs.com/viewer/net/how-to-check-if-file-is-encrypted/)*


**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - the file information.

### close() {#close--}
```
public final void close()
```


फ़ाइल स्ट्रीम और प्रबंधित आंतरिक संसाधनों को रिलीज़ करता है।


