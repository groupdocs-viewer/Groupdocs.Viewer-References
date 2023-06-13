---
title: Line
second_title: GroupDocs.Viewer for Java API Reference
description: Represents a relatively positioned rectangle that contains a single line.
type: docs
weight: 18
url: /java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

Represents a relatively positioned rectangle that contains a single line.

The Line interface defines the contract for accessing and manipulating a line represented by a rectangle in the GroupDocs.Viewer component. It provides methods to retrieve information such as the line text, position, and size of the rectangle.

Example usage:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List lines = viewInfo.getPages().get(0).getLines();
     for (Line line : lines) {
         // Use the line object for further operations
     }
 }
 
```

Note: The default implementation of this interface is LineImpl.
## Methods

| Method | Description |
| --- | --- |
| [getWords()](#getWords--) | Retrieves the words contained in the line. |
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


Retrieves the words contained in the line.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - the words contained in the line.
