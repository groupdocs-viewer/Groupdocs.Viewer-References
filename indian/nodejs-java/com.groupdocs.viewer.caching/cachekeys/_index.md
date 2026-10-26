---
title: "CacheKeys"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "कैश एंट्री के लिए अद्वितीय पहचानकर्ता प्राप्त करने के लिए मेथड्स प्रदान करता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.viewer.caching/cachekeys/
---
**Inheritance:**
java.lang.Object
```
public class CacheKeys
```

कैश एंट्री के लिए अद्वितीय पहचानकर्ता प्राप्त करने के लिए मेथड्स प्रदान करता है।

यह क्लास आपको विभिन्न पैरामीटरों जैसे दस्तावेज़ पथ, रेंडरिंग विकल्प, और संसाधन नाम के आधार पर कैश कुंजियाँ उत्पन्न करने की अनुमति देती है। इन कैश कुंजियों का उपयोग कुशल दस्तावेज़ रेंडरिंग के लिए कैश्ड डेटा को संग्रहीत और पुनः प्राप्त करने में किया जा सकता है।

उदाहरण उपयोग:

```

 // Generate a cache key for a file
 String fileKey = CacheKeys.getFileKey("filename.pdf");

 // Generate a cache key for a page
 String pageKey = CacheKeys.getPageKey(pageNumber, FileType.HTML.getExtension());

 // Generate a cache key for a resource
 Resource resource = new Resource("styles.css", false);
 String pageKey = CacheKeys.getResourceKey(pageNumber, resource);
 
```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [PAGE_NUMBER](#PAGE-NUMBER) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getAttachmentsKey()](#getAttachmentsKey--) | कैश एंट्री के लिए अद्वितीय पहचानकर्ता लौटाता है जो [Attachment](../../com.groupdocs.viewer.results/attachment) ऑब्जेक्ट्स के संग्रह का प्रतिनिधित्व करता है। |
| [getAttachmentKey(String attachmentId)](#getAttachmentKey-java.lang.String-) | एक अटैचमेंट फ़ाइल का प्रतिनिधित्व करने वाली कैश एंट्री के लिए अद्वितीय पहचानकर्ता प्राप्त करता है। |
| [getViewInfoKey()](#getViewInfoKey--) | एक [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) ऑब्जेक्ट का प्रतिनिधित्व करने वाली कैश एंट्री के लिए अद्वितीय पहचानकर्ता प्राप्त करता है। |
| [getFileInfoKey()](#getFileInfoKey--) | एक [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) ऑब्जेक्ट का प्रतिनिधित्व करने वाली कैश एंट्री के लिए अद्वितीय पहचानकर्ता प्राप्त करता है। |
| [getFileKey(String extension)](#getFileKey-java.lang.String-) | फ़ाइल का प्रतिनिधित्व करने वाली कैश एंट्री के लिए अद्वितीय पहचानकर्ता प्राप्त करता है। |
| [getPageKey(int pageNumber, String extension)](#getPageKey-int-java.lang.String-) | पेज फ़ाइल का प्रतिनिधित्व करने वाली कैश एंट्री के लिए अद्वितीय पहचानकर्ता प्राप्त करता है। |
| [getResourceKey(int pageNumber, Resource resource)](#getResourceKey-int-com.groupdocs.viewer.results.Resource-) | एक [Resource](../../com.groupdocs.viewer.results/resource) ऑब्जेक्ट का प्रतिनिधित्व करने वाली कैश एंट्री के लिए अद्वितीय पहचानकर्ता लौटाता है। |
| [getResourceFilter(int pageNumber)](#getResourceFilter-int-) | कैश एंट्रीज़ को खोजने के लिए एक फ़िल्टर स्ट्रिंग लौटाता है जो [Resource](../../com.groupdocs.viewer.results/resource) ऑब्जेक्ट्स का प्रतिनिधित्व करती हैं। |
### PAGE_NUMBER {#PAGE-NUMBER}
```
public static final String PAGE_NUMBER
```


### getAttachmentsKey() {#getAttachmentsKey--}
```
public static String getAttachmentsKey()
```


कैश एंट्री के लिए अद्वितीय पहचानकर्ता लौटाता है जो [Attachment](../../com.groupdocs.viewer.results/attachment) ऑब्जेक्ट्स के संग्रह का प्रतिनिधित्व करता है।

**Returns:**
java.lang.String - attachments कैश एंट्री के लिए अद्वितीय पहचानकर्ता।
### getAttachmentKey(String attachmentId) {#getAttachmentKey-java.lang.String-}
```
public static String getAttachmentKey(String attachmentId)
```


एक अटैचमेंट फ़ाइल का प्रतिनिधित्व करने वाली कैश एंट्री के लिए अद्वितीय पहचानकर्ता प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| attachmentId | java.lang.String | एकल फ़ाइल के संदर्भ में अटैचमेंट का अद्वितीय पहचानकर्ता। |

**Returns:**
java.lang.String - अटैचमेंट फ़ाइल कैश एंट्री के लिए अद्वितीय पहचानकर्ता।
### getViewInfoKey() {#getViewInfoKey--}
```
public static String getViewInfoKey()
```


एक [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) ऑब्जेक्ट का प्रतिनिधित्व करने वाली कैश एंट्री के लिए अद्वितीय पहचानकर्ता प्राप्त करता है।

**Returns:**
java.lang.String - कैश एंट्री के लिए अद्वितीय पहचानकर्ता।
### getFileInfoKey() {#getFileInfoKey--}
```
public static String getFileInfoKey()
```


एक [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) ऑब्जेक्ट का प्रतिनिधित्व करने वाली कैश एंट्री के लिए अद्वितीय पहचानकर्ता प्राप्त करता है।

**Returns:**
java.lang.String - एक [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) ऑब्जेक्ट का प्रतिनिधित्व करने वाली कैश एंट्री के लिए अद्वितीय पहचानकर्ता।
### getFileKey(String extension) {#getFileKey-java.lang.String-}
```
public static String getFileKey(String extension)
```


फ़ाइल का प्रतिनिधित्व करने वाली कैश एंट्री के लिए अद्वितीय पहचानकर्ता प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| extension | java.lang.String | फ़ाइलनाम प्रत्यय (\".\" सहित) उदाहरण: \".doc\"। |

**Returns:**
java.lang.String - फ़ाइल का प्रतिनिधित्व करने वाली कैश एंट्री के लिए अद्वितीय पहचानकर्ता।
### getPageKey(int pageNumber, String extension) {#getPageKey-int-java.lang.String-}
```
public static String getPageKey(int pageNumber, String extension)
```


पेज फ़ाइल का प्रतिनिधित्व करने वाली कैश एंट्री के लिए अद्वितीय पहचानकर्ता प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageNumber | int | पेज की संख्या। |
| extension | java.lang.String | फ़ाइलनाम प्रत्यय (\".\" सहित) उदाहरण: \".doc\"। |

**Returns:**
java.lang.String - पेज फ़ाइल का प्रतिनिधित्व करने वाली कैश एंट्री के लिए अद्वितीय पहचानकर्ता।
### getResourceKey(int pageNumber, Resource resource) {#getResourceKey-int-com.groupdocs.viewer.results.Resource-}
```
public static String getResourceKey(int pageNumber, Resource resource)
```


एक [Resource](../../com.groupdocs.viewer.results/resource) ऑब्जेक्ट का प्रतिनिधित्व करने वाली कैश एंट्री के लिए अद्वितीय पहचानकर्ता लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageNumber | int | पेज की संख्या। |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) | HTML संसाधन। |

**Returns:**
java.lang.String - कैश एंट्री के लिए अद्वितीय पहचानकर्ता।
### getResourceFilter(int pageNumber) {#getResourceFilter-int-}
```
public static String getResourceFilter(int pageNumber)
```


कैश एंट्रीज़ को खोजने के लिए एक फ़िल्टर स्ट्रिंग लौटाता है जो [Resource](../../com.groupdocs.viewer.results/resource) ऑब्जेक्ट्स का प्रतिनिधित्व करती हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageNumber | int | पेज की संख्या। |

**Returns:**
java.lang.String - कैश एंट्रीज़ को खोजने के लिए फ़िल्टर स्ट्रिंग।
