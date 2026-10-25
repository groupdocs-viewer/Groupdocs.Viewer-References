---
title: "Character"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Tek bir karakter içeren göreceli konumlandırılmış bir dikdörtgeni temsil eder."
type: docs
weight: 14
url: /tr/java/com.groupdocs.viewer.results/character/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Character extends TextElement<Character>, Serializable
```

Tek bir karakter içeren göreceli konumlandırılmış bir dikdörtgeni temsil eder.


Character arabirimi, bir dikdörtgenle temsil edilen karaktere erişim ve manipülasyon sağlamak için sözleşmeyi tanımlar
GroupDocs.Viewer bileşeninde. Karakterin kendisi gibi bilgileri almak için yöntemler sunar,
konum ve dikdörtgenin boyutu.


Örnek kullanım:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List characters = viewInfo.getPages().get(0).getLines().get(0).getWords().get(0).getCharacters();
     Character character = characters.get(0);

     // Use the character object for further operations
 }
 
````


***Note:** The default implementation of this interface is CharacterImpl.*

