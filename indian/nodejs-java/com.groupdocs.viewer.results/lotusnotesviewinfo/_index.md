---
title: "LotusNotesViewInfo"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "Lotus Notes डेटाबेस स्टोरेज के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।"
type: docs
weight: 19
url: /hi/nodejs-java/com.groupdocs.viewer.results/lotusnotesviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface LotusNotesViewInfo extends ViewInfo
```

Lotus Notes डेटाबेस स्टोरेज के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।

LotusNotesViewInfo इंटरफ़ेस GroupDocs.Viewer घटक में Lotus Notes डेटाबेस स्टोरेज के लिए दृश्य जानकारी तक पहुँचने और उसे संशोधित करने के अनुबंध को परिभाषित करता है। यह नोट्स की गिनती और अन्य गुणों जैसी जानकारी प्राप्त करने के लिए विधियाँ प्रदान करता है।

उदाहरण उपयोग:

```

 try (Viewer viewer = new Viewer("document.nsf")) {
     final LotusNotesViewInfo viewInfo = (LotusNotesViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is LotusNotesViewInfoImpl.*
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getNotesCount()](#getNotesCount--) | स्टोरेज में नोट्स की गिनती प्राप्त करता है। |
| [setNotesCount(int count)](#setNotesCount-int-) | स्टोरेज में नोट्स की गिनती सेट करता है। |
### getNotesCount() {#getNotesCount--}
```
public abstract int getNotesCount()
```


स्टोरेज में नोट्स की गिनती प्राप्त करता है।

**Returns:**
int - स्टोरेज में नोट्स की गिनती।
### setNotesCount(int count) {#setNotesCount-int-}
```
public abstract void setNotesCount(int count)
```


स्टोरेज में नोट्स की गिनती सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| गिनती | int | स्टोरेज में नोट्स की गिनती। |

