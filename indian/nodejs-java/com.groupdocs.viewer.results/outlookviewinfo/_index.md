---
title: "OutlookViewInfo"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "Outlook डेटा फ़ाइल के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।"
type: docs
weight: 20
url: /hi/nodejs-java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

Outlook डेटा फ़ाइल के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।

OutlookViewInfo इंटरफ़ेस GroupDocs.Viewer घटक में Outlook डेटा फ़ाइल के लिए दृश्य जानकारी तक पहुँचने और उसे संशोधित करने के अनुबंध को परिभाषित करता है। यह फ़ोल्डरों की सूची और अन्य गुणों जैसी जानकारी प्राप्त करने के लिए विधियाँ प्रदान करता है।

उदाहरण उपयोग:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is OutlookViewInfoImpl.*
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFolders()](#getFolders--) | Outlook डेटा फ़ाइल में मौजूद फ़ोल्डरों की सूची प्राप्त करता है। |
| [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | Outlook डेटा फ़ाइल में मौजूद फ़ोल्डरों की सूची सेट करता है। |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Outlook डेटा फ़ाइल में मौजूद फ़ोल्डरों की सूची प्राप्त करता है।

**Returns:**
java.util.List<java.lang.String> - फ़ोल्डरों की सूची।
### setFolders(List<String> list) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> list)
```


Outlook डेटा फ़ाइल में मौजूद फ़ोल्डरों की सूची सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| सूची | java.util.List<java.lang.String> | फ़ोल्डरों की सूची। |

