---
title: "ArchiveViewInfo"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "एक आर्काइव फ़ाइल के लिए व्यू जानकारी का प्रतिनिधित्व करता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

एक आर्काइव फ़ाइल के लिए व्यू जानकारी का प्रतिनिधित्व करता है।


ArchiveViewInfo इंटरफ़ेस एक अभिलेख फ़ाइल के विशिष्ट दृश्य जानकारी प्राप्त करने के अनुबंध को परिभाषित करता है।
GroupDocs.Viewer घटक में। यह पृष्ठ गणना, आयाम, और रेंडरिंग विकल्प जैसी विवरणों तक पहुँचने के लिए विधियाँ प्रदान करता है।
अभिलेख फ़ाइलों के लिए विशिष्ट।


उदाहरण उपयोग:

````

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*

## Methods

| Method | विवरण |
| --- | --- |
|  | [getFolders()](#getFolders--) | अभिलेख फ़ाइल में सम्मिलित फ़ोल्डरों की सूची प्राप्त करता है। |
|
|  | [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | अभिलेख फ़ाइल में सम्मिलित फ़ोल्डरों की सूची सेट करता है। |
|
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


अभिलेख फ़ाइल में सम्मिलित फ़ोल्डरों की सूची प्राप्त करता है।


**Returns:**
java.util.List<java.lang.String> - फ़ोल्डर की सूची।

### setFolders(List<String> folders) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> folders)
```


अभिलेख फ़ाइल में सम्मिलित फ़ोल्डरों की सूची सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | folders | java.util.List<java.lang.String> | फ़ोल्डर की सूची। |
|

