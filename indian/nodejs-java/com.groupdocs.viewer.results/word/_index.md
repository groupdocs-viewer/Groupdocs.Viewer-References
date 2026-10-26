---
title: "Word"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "एक सापेक्ष रूप से स्थित आयत का प्रतिनिधित्व करता है जिसमें एक शब्द होता है।"
type: docs
weight: 26
url: /hi/nodejs-java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

एक सापेक्ष रूप से स्थित आयत का प्रतिनिधित्व करता है जिसमें एक शब्द होता है।

Word इंटरफ़ेस GroupDocs.Viewer घटक में एक सापेक्ष रूप से स्थित आयत के भीतर शब्द का प्रतिनिधित्व करता है। यह TextElement इंटरफ़ेस को विस्तारित करता है और शब्द सामग्री तक पहुँचने और उसे संशोधित करने के लिए अतिरिक्त विधियाँ प्रदान करता है।

उदाहरण उपयोग:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List words = viewInfo.getPages().get(0).getLines().get(0).getWords();
     for (Word word : words) {
         // Use the word object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is WordImpl.*
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getCharacters()](#getCharacters--) | शब्द में मौजूद अक्षरों को प्राप्त करता है। |
| [setCharacters(List<Character> characters)](#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--) | शब्द में मौजूद अक्षरों को सेट करता है। |
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


शब्द में मौजूद अक्षरों को प्राप्त करता है।

**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - अक्षरों की सूची।
### setCharacters(List<Character> characters) {#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--}
```
public abstract void setCharacters(List<Character> characters)
```


शब्द में मौजूद अक्षरों को सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| अक्षर | java.util.List<com.groupdocs.viewer.results.Character> | सेट करने के लिए अक्षरों की सूची। |

