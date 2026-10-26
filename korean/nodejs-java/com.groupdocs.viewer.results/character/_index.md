---
title: "문자"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "단일 문자를 포함하는 상대적으로 위치된 사각형을 나타냅니다."
type: docs
weight: 14
url: /ko/nodejs-java/com.groupdocs.viewer.results/character/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Character extends TextElement<Character>, Serializable
```

단일 문자를 포함하는 상대적으로 위치된 사각형을 나타냅니다.

Character 인터페이스는 GroupDocs.Viewer 구성 요소에서 사각형으로 표시되는 문자를 접근하고 조작하기 위한 계약을 정의합니다. 문자 자체, 위치 및 사각형 크기와 같은 정보를 검색하는 메서드를 제공합니다.

예시 사용법:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List characters = viewInfo.getPages().get(0).getLines().get(0).getWords().get(0).getCharacters();
     Character character = characters.get(0);

     // Use the character object for further operations
 }
 
```

***Note:** The default implementation of this interface is CharacterImpl.*
