---
title: "Karakter"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Mewakili persegi panjang yang diposisikan relatif yang berisi satu karakter."
type: docs
weight: 14
url: /id/nodejs-java/com.groupdocs.viewer.results/character/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Character extends TextElement<Character>, Serializable
```

Mewakili persegi panjang yang diposisikan relatif yang berisi satu karakter.

Antarmuka Character mendefinisikan kontrak untuk mengakses dan memanipulasi karakter yang direpresentasikan oleh sebuah persegi panjang dalam komponen GroupDocs.Viewer. Ini menyediakan metode untuk mengambil informasi seperti karakter itu sendiri, posisi, dan ukuran persegi panjang.

Contoh penggunaan:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List characters = viewInfo.getPages().get(0).getLines().get(0).getWords().get(0).getCharacters();
     Character character = characters.get(0);

     // Use the character object for further operations
 }
 
```

***Note:** The default implementation of this interface is CharacterImpl.*
