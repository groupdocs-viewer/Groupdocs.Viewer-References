---
title: "ArchiveViewInfo"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "एक आर्काइव फ़ाइल के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।"
type: docs
weight: 11
url: /hi/nodejs-java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

एक आर्काइव फ़ाइल के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।

ArchiveViewInfo इंटरफ़ेस एक अनुबंध परिभाषित करता है जो GroupDocs.Viewer घटक में एक अभिलेख फ़ाइल के लिए विशिष्ट दृश्य जानकारी प्राप्त करने के लिए है। यह पृष्ठ गिनती, आयाम, और अभिलेख फ़ाइलों के लिए विशिष्ट रेंडरिंग विकल्प जैसी विवरणों तक पहुँचने के लिए विधियाँ प्रदान करता है।

उदाहरण उपयोग:

```

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFolders()](#getFolders--) | अभिलेख फ़ाइल में मौजूद फ़ोल्डरों की सूची प्राप्त करता है। |
| [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | अभिलेख फ़ाइल में मौजूद फ़ोल्डरों की सूची सेट करता है। |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


अभिलेख फ़ाइल में मौजूद फ़ोल्डरों की सूची प्राप्त करता है।

**Returns:**
java.util.List<java.lang.String> - फ़ोल्डरों की सूची।
### setFolders(List<String> folders) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> folders)
```


अभिलेख फ़ाइल में मौजूद फ़ोल्डरों की सूची सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ोल्डर | java.util.List<java.lang.String> | फ़ोल्डरों की सूची। |

