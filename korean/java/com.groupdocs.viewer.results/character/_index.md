---
title: "Character"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "단일 문자를 포함하는 상대적으로 배치된 사각형을 나타냅니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.viewer.results/character/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Character extends TextElement<Character>, Serializable
```

단일 문자를 포함하는 상대적으로 배치된 사각형을 나타냅니다.


Character 인터페이스는 사각형으로 표시된 문자를 접근하고 조작하기 위한 계약을 정의합니다.
GroupDocs.Viewer 구성 요소에서. 문자 자체와 같은 정보를 검색하는 메서드를 제공합니다,
위치 및 사각형의 크기.


사용 예시:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List characters = viewInfo.getPages().get(0).getLines().get(0).getWords().get(0).getCharacters();
     Character character = characters.get(0);

     // Use the character object for further operations
 }
 
````


***Note:** The default implementation of this interface is CharacterImpl.*

