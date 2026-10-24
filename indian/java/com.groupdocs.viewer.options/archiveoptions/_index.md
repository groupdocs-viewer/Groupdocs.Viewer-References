---
title: "ArchiveOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "अभिलेख फ़ाइलों को रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

अभिलेख फ़ाइलों को रेंडर करने के विकल्प प्रदान करता है।


यह
ArchiveOptions
क्लास उन विकल्पों का सेट दर्शाता है जिसका उपयोग व्यूअर मॉड्यूल में आर्काइव फ़ाइलों के रेंडरिंग को कॉन्फ़िगर करने के लिए किया जा सकता है।
यह आपको रेंडरिंग प्रक्रिया के विभिन्न पहलुओं को अनुकूलित करने की अनुमति देता है, जैसे प्रत्येक पृष्ठ पर आइटमों की संख्या आदि।


उदाहरण उपयोग:

````

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
````


***Note:** The 
ArchiveOptions
क्लास आर्काइव फ़ाइलों के रेंडरिंग के लिए विभिन्न अनुकूलन विकल्प प्रदान करती है।
आप अपनी विशिष्ट आवश्यकताओं के आधार पर इन विकल्पों को कॉन्फ़िगर करके वांछित आउटपुट प्राप्त कर सकते हैं।*

## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [ArchiveOptions()](#ArchiveOptions--) | डिफ़ॉल्ट सेटिंग्स के साथ ArchiveOptions क्लास का एक नया इंस्टेंस बनाता है। |
|
## Methods

| Method | विवरण |
| --- | --- |
|  | [getFolder()](#getFolder--) | आर्काइव के भीतर वह फ़ोल्डर प्राप्त करता है जिसका उपयोग रेंडरिंग के लिए किया जाएगा। |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | आर्काइव के भीतर वह फ़ोल्डर सेट करता है जिसका उपयोग रेंडरिंग के लिए किया जाएगा। |
|
|  | [getFileName()](#getFileName--) | हेडर में प्रदर्शित होने वाले फ़ाइलनाम को प्राप्त करता है। |
|
|  | [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | हेडर में प्रदर्शित होने वाले फ़ाइलनाम को सेट करता है। |
|
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


डिफ़ॉल्ट सेटिंग्स के साथ ArchiveOptions क्लास का एक नया इंस्टेंस बनाता है।


### getFolder() {#getFolder--}
```
public final String getFolder()
```


आर्काइव के भीतर वह फ़ोल्डर प्राप्त करता है जिसका उपयोग रेंडरिंग के लिए किया जाएगा।


डिफ़ॉल्ट रूप से, GroupDocs.Viewer आर्काइव में मौजूद सभी फ़ोल्डरों से आइटम रेंडर करता है। किसी विशिष्ट फ़ोल्डर से आइटम रेंडर करने के लिए, इस प्रॉपर्टी को सेट करें।
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder)।


**Returns:**
java.lang.String - रेंडर किया जाने वाला फ़ोल्डर।

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


आर्काइव के भीतर वह फ़ोल्डर सेट करता है जिसका उपयोग रेंडरिंग के लिए किया जाएगा।


डिफ़ॉल्ट रूप से, GroupDocs.Viewer आर्काइव में मौजूद सभी फ़ोल्डरों से आइटम रेंडर करता है। किसी विशिष्ट फ़ोल्डर से आइटम रेंडर करने के लिए, इस प्रॉपर्टी को सेट करें।
कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | रेंडर किया जाने वाला फ़ोल्डर। |
|

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


हेडर में प्रदर्शित होने वाले फ़ाइलनाम को प्राप्त करता है।


डिफ़ॉल्ट रूप से, GroupDocs.Viewer प्रत्येक पृष्ठ के हेडर में आर्काइव फ़ाइल का नाम दिखाता है। इस नाम को बदलने या छिपाने के लिए, इस प्रॉपर्टी को सेट करें।
अधिक जानकारी और कोड उदाहरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name)।


**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.

### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


हेडर में प्रदर्शित होने वाले फ़ाइलनाम को सेट करता है।


डिफ़ॉल्ट रूप से, GroupDocs.Viewer प्रत्येक पृष्ठ के हेडर में आर्काइव फ़ाइल का नाम दिखाता है। इस नाम को बदलने या छिपाने के लिए, इस प्रॉपर्टी को सेट करें।
अधिक जानकारी और कोड उदाहरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileName | [FileName](../../com.groupdocs.viewer.options/filename) | दिखाने के लिए फ़ाइलनाम। |
|

