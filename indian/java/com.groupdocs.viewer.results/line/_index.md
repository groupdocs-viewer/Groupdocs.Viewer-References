---
title: "Line"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "एक सापेक्ष रूप से स्थित आयत का प्रतिनिधित्व करता है जिसमें एक एकल पंक्ति होती है।"
type: docs
weight: 18
url: /hi/java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

एक सापेक्ष रूप से स्थित आयत का प्रतिनिधित्व करता है जिसमें एक एकल पंक्ति होती है।


Line इंटरफ़ेस आयत द्वारा प्रतिनिधित्व की गई रेखा तक पहुँचने और उसे संशोधित करने के अनुबंध को परिभाषित करता है।
GroupDocs.Viewer घटक में। यह पंक्ति के पाठ जैसी जानकारी प्राप्त करने के लिए विधियाँ प्रदान करता है,
स्थिति, और आयत का आकार।


उदाहरण उपयोग:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List lines = viewInfo.getPages().get(0).getLines();
     for (Line line : lines) {
         // Use the line object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LineImpl.*

## Methods

| Method | विवरण |
| --- | --- |
|  | [getWords()](#getWords--) | पंक्ति में मौजूद शब्दों को प्राप्त करता है। |
|
|  | [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | पंक्ति में मौजूद शब्दों को सेट करता है। |
|
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


पंक्ति में मौजूद शब्दों को प्राप्त करता है।


**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - पंक्ति में मौजूद शब्द।

### setWords(List<Word> wordList) {#setWords-java.util.List-com.groupdocs.viewer.results.Word--}
```
public abstract void setWords(List<Word> wordList)
```


पंक्ति में मौजूद शब्दों को सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | wordList | java.util.List<com.groupdocs.viewer.results.Word> | पंक्ति में मौजूद शब्द। |
|

