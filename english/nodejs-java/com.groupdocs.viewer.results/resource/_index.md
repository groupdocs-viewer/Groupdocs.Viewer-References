---
title: Resource
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Represents HTML resource such as font style image or graphics.
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.viewer.results/resource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Serializable
```
public class Resource implements Serializable
```

Represents HTML resource such as font, style, image or graphics.

The Resource class represents a resource used in HTML rendering in the GroupDocs.Viewer component. It can represent various types of resources, such as fonts, styles, images, or graphics, that are included or referenced in the generated HTML output during the rendering process.

Example usage:

```

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forExternalResources(pageNumber -> , new ReleaseResourceStream() {
     @Override
     public void invoke(int pageNumber, Resource resource, OutputStream resourceStream) {
         // Handle resource
     }
 });
 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Resource(String fileName, boolean nested)](#Resource-java.lang.String-boolean-) | Creates a new instance of the  Resource  class. |
## Methods

| Method | Description |
| --- | --- |
| [getFileName()](#getFileName--) | Returns the file name of the resource. |
| [isNested()](#isNested--) | Returns whether the resource resides inside another resource, e.g. a font resource that resides in a CSS or SVG resource. |
| [toString()](#toString--) | Returns a string that represents the current object. |
### Resource(String fileName, boolean nested) {#Resource-java.lang.String-boolean-}
```
public Resource(String fileName, boolean nested)
```


Creates a new instance of the  Resource  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The resource file name. |
| nested | boolean | Indicates whether the resource resides inside another resource, e.g., a font resource that resides in a CSS or SVG resource. |

### getFileName() {#getFileName--}
```
public final String getFileName()
```


Returns the file name of the resource.

**Returns:**
java.lang.String - the file name of the resource.
### isNested() {#isNested--}
```
public final boolean isNested()
```


Returns whether the resource resides inside another resource, e.g. a font resource that resides in a CSS or SVG resource.

**Returns:**
boolean - Whether the resource resides inside another resource.
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - the string representation of the current object.
