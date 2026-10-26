---
title: "ArchiveOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "आर्काइव फ़ाइलों को रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

आर्काइव फ़ाइलों को रेंडर करने के विकल्प प्रदान करता है।

ArchiveOptions क्लास विकल्पों का एक सेट दर्शाता है जिसका उपयोग व्यूअर मॉड्यूल में आर्काइव फ़ाइलों की रेंडरिंग को कॉन्फ़िगर करने के लिए किया जा सकता है। यह आपको रेंडरिंग प्रक्रिया के विभिन्न पहलुओं को अनुकूलित करने की अनुमति देता है, जैसे प्रत्येक पृष्ठ पर आइटमों की संख्या आदि।

उदाहरण उपयोग:

```

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
```

***Note:** The  ArchiveOptions  class provides a range of customization options for rendering archive files. You can configure these options based on your specific requirements to achieve the desired output.*
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ArchiveOptions()](#ArchiveOptions--) | डिफ़ॉल्ट सेटिंग्स के साथ ArchiveOptions क्लास का नया उदाहरण बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFolder()](#getFolder--) | आर्काइव के भीतर वह फ़ोल्डर प्राप्त करता है जिसका उपयोग रेंडरिंग के लिए किया जाएगा। |
| [setFolder(String value)](#setFolder-java.lang.String-) | आर्काइव के भीतर वह फ़ोल्डर सेट करता है जिसका उपयोग रेंडरिंग के लिए किया जाएगा। |
| [getFileName()](#getFileName--) | हेडर में प्रदर्शित होने वाले फ़ाइलनाम को प्राप्त करता है। |
| [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | हेडर में प्रदर्शित होने वाले फ़ाइलनाम को सेट करता है। |
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


डिफ़ॉल्ट सेटिंग्स के साथ ArchiveOptions क्लास का नया उदाहरण बनाता है।

### getFolder() {#getFolder--}
```
public final String getFolder()
```


आर्काइव के भीतर वह फ़ोल्डर प्राप्त करता है जिसका उपयोग रेंडरिंग के लिए किया जाएगा।

डिफ़ॉल्ट रूप से, GroupDocs.Viewer आर्काइव में मौजूद सभी फ़ोल्डरों की वस्तुओं को रेंडर करता है। किसी विशिष्ट फ़ोल्डर की वस्तुओं को रेंडर करने के लिए, इस प्रॉपर्टी को सेट करें। कोड उदाहरण के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder

**Returns:**
java.lang.String - रेंडर किया जाने वाला फ़ोल्डर।
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


आर्काइव के भीतर वह फ़ोल्डर सेट करता है जिसका उपयोग रेंडरिंग के लिए किया जाएगा।

डिफ़ॉल्ट रूप से, GroupDocs.Viewer आर्काइव में मौजूद सभी फ़ोल्डरों की वस्तुओं को रेंडर करता है। किसी विशिष्ट फ़ोल्डर की वस्तुओं को रेंडर करने के लिए, इस प्रॉपर्टी को सेट करें। कोड उदाहरण के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String | रेंडर किया जाने वाला फ़ोल्डर। |

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


हेडर में प्रदर्शित होने वाले फ़ाइलनाम को प्राप्त करता है।

डिफ़ॉल्ट रूप से, GroupDocs.Viewer प्रत्येक पृष्ठ के हेडर में आर्काइव फ़ाइल नाम दिखाता है। इस नाम को बदलने या छिपाने के लिए, इस प्रॉपर्टी को सेट करें। अधिक जानकारी और कोड उदाहरण के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.
### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


हेडर में प्रदर्शित होने वाले फ़ाइलनाम को सेट करता है।

डिफ़ॉल्ट रूप से, GroupDocs.Viewer प्रत्येक पृष्ठ के हेडर में आर्काइव फ़ाइल नाम दिखाता है। इस नाम को बदलने या छिपाने के लिए, इस प्रॉपर्टी को सेट करें। अधिक जानकारी और कोड उदाहरण के लिए, देखें [दस्तावेज़ीकरण][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileName | [FileName](../../com.groupdocs.viewer.options/filename) | प्रदर्शित किया जाने वाला फ़ाइलनाम। |

