---
title: "حرف"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يمثل مستطيلًا موضعًا نسبيًا يحتوي على حرف واحد."
type: docs
weight: 14
url: /ar/java/com.groupdocs.viewer.results/character/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Character extends TextElement<Character>, Serializable
```

يمثل مستطيلًا موضعًا نسبيًا يحتوي على حرف واحد.


واجهة Character تحدد العقد للوصول إلى حرف ممثل بمستطيل ومعالجته
في مكوّن GroupDocs.Viewer. توفر طرقًا لاسترجاع معلومات مثل الحرف نفسه،
الموضع، وحجم المستطيل.


مثال على الاستخدام:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List characters = viewInfo.getPages().get(0).getLines().get(0).getWords().get(0).getCharacters();
     Character character = characters.get(0);

     // Use the character object for further operations
 }
 
````


***Note:** The default implementation of this interface is CharacterImpl.*

