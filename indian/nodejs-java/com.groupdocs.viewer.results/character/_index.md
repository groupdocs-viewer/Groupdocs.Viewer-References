---
title: "अक्षर"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "एक सापेक्ष रूप से स्थित आयत का प्रतिनिधित्व करता है जिसमें एक अक्षर होता है।"
type: docs
weight: 14
url: /hi/nodejs-java/com.groupdocs.viewer.results/character/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Character extends TextElement<Character>, Serializable
```

एक सापेक्ष रूप से स्थित आयत का प्रतिनिधित्व करता है जिसमें एक अक्षर होता है।

Character इंटरफ़ेस एक अनुबंध परिभाषित करता है जो GroupDocs.Viewer घटक में एक आयत द्वारा दर्शाए गए अक्षर तक पहुँचने और उसे संशोधित करने के लिए है। यह अक्षर स्वयं, स्थिति, और आयत के आकार जैसी जानकारी प्राप्त करने के लिए विधियाँ प्रदान करता है।

उदाहरण उपयोग:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List characters = viewInfo.getPages().get(0).getLines().get(0).getWords().get(0).getCharacters();
     Character character = characters.get(0);

     // Use the character object for further operations
 }
 
```

***Note:** The default implementation of this interface is CharacterImpl.*
