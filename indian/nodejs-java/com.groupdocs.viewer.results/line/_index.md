---
title: "लाइन"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "एक सापेक्ष रूप से स्थित आयत का प्रतिनिधित्व करता है जिसमें एक पंक्ति होती है।"
type: docs
weight: 18
url: /hi/nodejs-java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

एक सापेक्ष रूप से स्थित आयत का प्रतिनिधित्व करता है जिसमें एक पंक्ति होती है।

Line इंटरफ़ेस वह अनुबंध परिभाषित करता है जो GroupDocs.Viewer घटक में आयत द्वारा प्रदर्शित एक लाइन तक पहुँचने और उसे संशोधित करने के लिए है। यह लाइन टेक्स्ट, स्थिति, और आयत के आकार जैसी जानकारी प्राप्त करने के लिए मेथड्स प्रदान करता है।

उदाहरण उपयोग:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List lines = viewInfo.getPages().get(0).getLines();
     for (Line line : lines) {
         // Use the line object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LineImpl.*
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getWords()](#getWords--) | लाइन में मौजूद शब्दों को प्राप्त करता है। |
| [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | लाइन में मौजूद शब्दों को सेट करता है। |
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


लाइन में मौजूद शब्दों को प्राप्त करता है।

**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - लाइन में मौजूद शब्द।
### setWords(List<Word> wordList) {#setWords-java.util.List-com.groupdocs.viewer.results.Word--}
```
public abstract void setWords(List<Word> wordList)
```


लाइन में मौजूद शब्दों को सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| wordList | java.util.List<com.groupdocs.viewer.results.Word> | लाइन में मौजूद शब्द। |

