---
title: Word
second_title: GroupDocs.Viewer for Java API Reference
description: Represents a relatively positioned rectangle that contains a single word.
type: docs
weight: 26
url: /java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

Represents a relatively positioned rectangle that contains a single word.

The Word interface represents a word within a relatively positioned rectangle in the GroupDocs.Viewer component. It extends the TextElement interface and provides additional methods to access and manipulate the word content.

Example usage:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List words = viewInfo.getPages().get(0).getLines().get(0).getWords();
     for (Word word : words) {
         // Use the word object for further operations
     }
 }
 
```

Note: The default implementation of this interface is WordImpl.
## Methods

| Method | Description |
| --- | --- |
| [getCharacters()](#getCharacters--) | Retrieves the characters contained by the word. |
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


Retrieves the characters contained by the word.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - the list of characters.
