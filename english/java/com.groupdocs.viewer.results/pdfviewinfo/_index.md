---
title: PdfViewInfo
second_title: GroupDocs.Viewer for Java API Reference
description: Represents view information for a PDF document.
type: docs
weight: 22
url: /java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

Represents view information for a PDF document.

The PdfViewInfo interface defines the contract for accessing and manipulating view information for a PDF document in the GroupDocs.Viewer component. It provides methods to retrieve information such as allowing printing, and other properties.

Example usage:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is PdfViewInfoImpl.*
## Methods

| Method | Description |
| --- | --- |
| [isPrintingAllowed()](#isPrintingAllowed--) | Checks if printing of the document is allowed. |
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


Checks if printing of the document is allowed.

**Returns:**
boolean -  true  if printing is allowed,  false  otherwise.
