---
title: VisioRenderingOptions
second_title: GroupDocs.Viewer for Java API Reference
description: The Visio files processing documents view options.
type: docs
weight: 34
url: /java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

The Visio files processing documents view options.

The VisioRenderingOptions class provides options for processing and rendering Visio files in the GroupDocs.Viewer component. It encapsulates settings and parameters that can be used to control the rendering process and output format for Visio documents.

Example usage:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [VisioRenderingOptions()](#VisioRenderingOptions--) | Initializes a new instance of the  VisioRenderingOptions  class. |
## Methods

| Method | Description |
| --- | --- |
| [isRenderFiguresOnly()](#isRenderFiguresOnly--) | Render only Visio figures, excluding the diagram. |
| [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | Sets the flag to render only Visio figures, excluding the diagram. |
| [getFigureWidth()](#getFigureWidth--) | Retrieves the width of the figure. |
| [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | Sets the width of the figure. |
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


Initializes a new instance of the  VisioRenderingOptions  class.

### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


Render only Visio figures, excluding the diagram.

**Returns:**
boolean -  true  if only Visio figures should be rendered,  false  otherwise.
### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


Sets the flag to render only Visio figures, excluding the diagram.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| renderFiguresOnly | boolean |  true  to render only Visio figures,  false  to include the diagram. |

### getFigureWidth() {#getFigureWidth--}
```
public int getFigureWidth()
```


Retrieves the width of the figure. The height will be calculated automatically.

**Returns:**
int - the width of the figure.
### setFigureWidth(int figureWidth) {#setFigureWidth-int-}
```
public void setFigureWidth(int figureWidth)
```


Sets the width of the figure. The height will be calculated automatically.

***Note:** Default value is 100.*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| figureWidth | int | The width of the figure. |

