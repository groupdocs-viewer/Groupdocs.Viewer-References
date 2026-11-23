---
title: "Viewer"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "दस्तावेज़ रेंडरिंग प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास को दर्शाता है।"
type: docs
weight: 12
url: /hi/nodejs-java/com.groupdocs.viewer/viewer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Viewer implements Closeable
```

दस्तावेज़ रेंडरिंग प्रक्रिया को नियंत्रित करने वाली मुख्य क्लास को दर्शाता है।

Viewer क्लास GroupDocs.Viewer घटक का उपयोग करके दस्तावेज़ रेंडर करने के लिए प्रवेश बिंदु है। यह विभिन्न स्रोतों से दस्तावेज़ लोड करने, रेंडरिंग प्रक्रिया को अनुकूलित करने, और विभिन्न फ़ॉर्मेट में रेंडर किए गए आउटपुट को प्राप्त करने के लिए मेथड और विकल्प प्रदान करता है।

उदाहरण उपयोग:

```

 try (Viewer viewer = new Viewer("source.pdf")) {
     viewer.view(new PngViewOptions("result-page{0}.png"));
 }
 
```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Viewer(InputStream fileStream)](#Viewer-java.io.InputStream-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(InputStream fileStream, boolean leaveOpen)](#Viewer-java.io.InputStream-boolean-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(InputStream fileStream, LoadOptions loadOptions)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(InputStream fileStream, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(URL url)](#Viewer-java.net.URL-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(URL url, LoadOptions loadOptions)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(URL url, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(FileReader fileReader, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(String filePath)](#Viewer-java.lang.String-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(Path filePath)](#Viewer-java.nio.file.Path-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(String filePath, LoadOptions loadOptions)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(Path filePath, LoadOptions loadOptions)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(String filePath, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(Path filePath, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [LOAD_OPTIONS](#LOAD-OPTIONS) |  |
| [SETTINGS](#SETTINGS) |  |
| [FILE_READER](#FILE-READER) |  |
| [OPTIONS](#OPTIONS) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getViewInfo(ViewInfoOptions options)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-) | व्यू और दस्तावेज़ संबंधी विशिष्ट जानकारी लौटाता है। |
| [getAttachments()](#getAttachments--) | दस्तावेज़ में सम्मिलित अटैचमेंट्स लौटाता है। |
| [saveAttachment(Attachment attachment, OutputStream destination)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-) | अटैचमेंट फ़ाइल को लक्ष्य स्ट्रीम में सहेजता है। |
| [view(ViewOptions options)](#view-com.groupdocs.viewer.options.ViewOptions-) | सभी दस्तावेज़ पृष्ठों का एक व्यू बनाता है। |
| [view(ViewOptions options, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-int...-) | विशिष्ट दस्तावेज़ पृष्ठों का एक व्यू बनाता है। |
| [getAllFonts()](#getAllFonts--) | लोड किए गए दस्तावेज़ों में उपयोग किए गए सभी फ़ॉन्ट्स लौटाता है, जिसमें दस्तावेज़ में एम्बेडेड फ़ॉन्ट्स और ऑपरेटिंग सिस्टम में स्थापित सिस्टम फ़ॉन्ट्स शामिल हैं जो दस्तावेज़ में उपयोग होते हैं। |
| [search(SearchHighlightOptions options)](#search-com.groupdocs.viewer.options.SearchHighlightOptions-) | प्रदान किए गए विकल्पों के अनुसार लोड किए गए दस्तावेज़ में टेक्स्ट खोज करता है और मिलान (यदि मिले) को हाइलाइट करता है। |
| [getFileInfo()](#getFileInfo--) | फ़ाइल के बारे में जानकारी लौटाता है, जैसे फ़ाइल प्रकार और एक फ़्लैग जो दर्शाता है कि फ़ाइल एन्क्रिप्टेड है या नहीं। |
| [close()](#close--) | फ़ाइल स्ट्रीम और प्रबंधित आंतरिक संसाधनों को रिलीज़ करता है। |
### Viewer(InputStream fileStream) {#Viewer-java.io.InputStream-}
```
public Viewer(InputStream fileStream)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

GroupDocs.Viewer द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक जानकारी: [Document formats supported by GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileStream | java.io.InputStream | एक पढ़ने योग्य स्ट्रीम लौटाने वाला मेथड। |

### Viewer(InputStream fileStream, boolean leaveOpen) {#Viewer-java.io.InputStream-boolean-}
```
public Viewer(InputStream fileStream, boolean leaveOpen)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileStream | java.io.InputStream | फ़ाइल स्ट्रीम। |
| leaveOpen | boolean | true – Viewer ऑब्जेक्ट नष्ट होने के बाद स्ट्रीम को खुला रखने के लिए; अन्यथा, false। |

### Viewer(InputStream fileStream, LoadOptions loadOptions) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileStream | java.io.InputStream | पढ़ने योग्य स्ट्रीम। |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |

### Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileStream | java.io.InputStream | फ़ाइल स्ट्रीम। |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |
| leaveOpen | boolean | true – Viewer ऑब्जेक्ट नष्ट होने के बाद स्ट्रीम को खुला रखने के लिए; अन्यथा, false। |

### Viewer(InputStream fileStream, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileStream | java.io.InputStream | फ़ाइल स्ट्रीम। |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |

### Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileStream | java.io.InputStream | फ़ाइल स्ट्रीम। |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |
| leaveOpen | boolean | true – Viewer ऑब्जेक्ट नष्ट होने के बाद स्ट्रीम को खुला रखने के लिए; अन्यथा, false। |

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileStream | java.io.InputStream | फ़ाइल स्ट्रीम। |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileStream | java.io.InputStream | फ़ाइल स्ट्रीम। |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |
| leaveOpen | boolean | true – Viewer ऑब्जेक्ट नष्ट होने के बाद स्ट्रीम को खुला रखने के लिए; अन्यथा, false। |

### Viewer(URL url) {#Viewer-java.net.URL-}
```
public Viewer(URL url)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

GroupDocs.Viewer द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक जानकारी: [Document formats supported by GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | java.net.URL | एक URL फ़ाइल के लिए जिसे Viewer में लोड किया जाना चाहिए। |

### Viewer(URL url, LoadOptions loadOptions) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(URL url, LoadOptions loadOptions)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | java.net.URL | एक URL फ़ाइल के लिए जिसे Viewer में लोड किया जाना चाहिए। |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |

### Viewer(URL url, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | java.net.URL | एक URL फ़ाइल के लिए जिसे Viewer में लोड किया जाना चाहिए। |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |

### Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | java.net.URL | एक URL फ़ाइल के लिए जिसे Viewer में लोड किया जाना चाहिए। |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |

### Viewer(FileReader fileReader, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

यह कंस्ट्रक्टर आपको एक Viewer ऑब्जेक्ट बनाने की अनुमति देता है जिससे आप एक दस्तावेज़ को [FileReader](../../com.groupdocs.viewer.interfaces/filereader) से निर्दिष्ट [ViewerSettings](../../com.groupdocs.viewer/viewersettings) के साथ देख सकते हैं।

 **Learn more**

 *  To learn about the file types supported by GroupDocs.Viewer, visit: [Document formats supported by GroupDocs.Viewer][]
 *  To explore the features of GroupDocs.Viewer for Java, refer to: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | Viewer में लोड किए जाने वाले दस्तावेज़ को सम्मिलित करने वाला [FileReader](../../com.groupdocs.viewer.interfaces/filereader)। |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer पर लागू किए जाने वाले [ViewerSettings](../../com.groupdocs.viewer/viewersettings)। |

### Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

GroupDocs.Viewer का उपयोग करके दस्तावेज़ लोड और देखने की कार्यक्षमता प्रदान करता है।

**Note:** Ensure that the file reader, load options, and settings are properly configured for accurate document processing.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | फ़ाइल रीडर। |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | लोड विकल्प। |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |

### Viewer(String filePath) {#Viewer-java.lang.String-}
```
public Viewer(String filePath)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

 **Learn more:**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइल पथ | java.lang.String | रेंडर करने वाली फ़ाइल का पथ। |

### Viewer(Path filePath) {#Viewer-java.nio.file.Path-}
```
public Viewer(Path filePath)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइल पथ | java.nio.file.Path | रेंडर करने वाली फ़ाइल का पथ। |

### Viewer(String filePath, LoadOptions loadOptions) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(String filePath, LoadOptions loadOptions)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइल पथ | java.lang.String | रेंडर करने वाली फ़ाइल का पथ। |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |

### Viewer(Path filePath, LoadOptions loadOptions) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(Path filePath, LoadOptions loadOptions)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view a document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view a document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइल पथ | java.nio.file.Path | रेंडर करने वाली फ़ाइल का पथ। |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |

### Viewer(String filePath, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइल पथ | java.lang.String | रेंडर करने वाली फ़ाइल का पथ। |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |

### Viewer(Path filePath, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइल पथ | java.nio.file.Path | रेंडर करने वाली फ़ाइल का पथ। |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |

### Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view documents with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइल पथ | java.lang.String | रेंडर करने वाली फ़ाइल का पथ। |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |

### Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view documents with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ाइल पथ | java.nio.file.Path | रेंडर करने वाली फ़ाइल का पथ। |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | दस्तावेज़ लोड विकल्प। |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer सेटिंग्स। |

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


व्यू और दस्तावेज़ संबंधी विशिष्ट जानकारी लौटाता है।

 **Learn more:**

 *  Learn more about the document - file type, page count, and other format specific properties: [How to get file information using GroupDocs.Viewer][]


[How to get file information using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Get+file+information

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | व्यू जानकारी विकल्प। |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.
### getAttachments() {#getAttachments--}
```
public final List<Attachment> getAttachments()
```


दस्तावेज़ में सम्मिलित अटैचमेंट्स लौटाता है।

 **Learn more:**

 *  Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer][]
 *  Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer][]


[How to get a list of document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Get+attachments
[How to save document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Save+attachments

**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - दस्तावेज़ में सम्मिलित अटैचमेंट्स।
### saveAttachment(Attachment attachment, OutputStream destination) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-}
```
public void saveAttachment(Attachment attachment, OutputStream destination)
```


अटैचमेंट फ़ाइल को लक्ष्य स्ट्रीम में सहेजता है।

 **Learn more:**

 *  Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer][]
 *  Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer][]


[How to get a list of document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Get+attachments
[How to save document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Save+attachments

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | अटैचमेंट। |
| गंतव्य | java.io.OutputStream | लिखने योग्य स्ट्रीम। |

### view(ViewOptions options) {#view-com.groupdocs.viewer.options.ViewOptions-}
```
public final void view(ViewOptions options)
```


सभी दस्तावेज़ पृष्ठों का एक व्यू बनाता है।

 **Learn more**

 *  Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer][]


[How to customize document viewing output using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Viewing

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | व्यू विकल्प। |

### view(ViewOptions options, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-int...-}
```
public final void view(ViewOptions options, int[] pageNumbers)
```


विशिष्ट दस्तावेज़ पृष्ठों का एक व्यू बनाता है।

 **Learn more**

 *  Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer][]


[How to customize document viewing output using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Viewing

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | व्यू विकल्प। |
| pageNumbers | int[] | देखने के लिए पृष्ठ संख्याएँ। |

### getAllFonts() {#getAllFonts--}
```
public IFontInfo[] getAllFonts()
```


लोड किए गए दस्तावेज़ों में उपयोग किए गए सभी फ़ॉन्ट्स लौटाता है, जिसमें दस्तावेज़ में एम्बेडेड फ़ॉन्ट्स और ऑपरेटिंग सिस्टम में स्थापित सिस्टम फ़ॉन्ट्स शामिल हैं जो दस्तावेज़ में उपयोग होते हैं।

विवरण के लिए, देखें [ documentation][documentation]।


[documentation]: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

**Returns:**
com.groupdocs.viewer.fonts.IFontInfo[] - इस [Viewer](../../com.groupdocs.viewer/viewer) उदाहरण में लोड किए गए दस्तावेज़ में उपयोग किए गए सभी फ़ॉन्ट्स की नॉन-नल सूची।
### search(SearchHighlightOptions options) {#search-com.groupdocs.viewer.options.SearchHighlightOptions-}
```
public void search(SearchHighlightOptions options)
```


प्रदान किए गए विकल्पों के अनुसार लोड किए गए दस्तावेज़ में टेक्स्ट खोज करता है और मिलान (यदि मिले) को हाइलाइट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| विकल्प | com.groupdocs.viewer.options.SearchHighlightOptions | खोज और हाइलाइट विकल्प, जिसमें खोजने के लिए एक टेक्स्ट वाक्यांश शामिल है। यह null नहीं हो सकता। |

### getFileInfo() {#getFileInfo--}
```
public FileInfo getFileInfo()
```


फ़ाइल के बारे में जानकारी लौटाता है, जैसे फ़ाइल प्रकार और एक फ़्लैग जो दर्शाता है कि फ़ाइल एन्क्रिप्टेड है या नहीं।

**Learn more:**

 *  Learn more about how to check if a file is encrypted: [How to check if a file is encrypted][]


[How to check if a file is encrypted]: https://docs.groupdocs.com/viewer/net/how-to-check-if-file-is-encrypted/

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - the file information.
### close() {#close--}
```
public final void close()
```


फ़ाइल स्ट्रीम और प्रबंधित आंतरिक संसाधनों को रिलीज़ करता है।

