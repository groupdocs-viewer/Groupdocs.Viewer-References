---
title: Resource
second_title: GroupDocs.Viewer for Java API Reference
description: Represents HTML resource such as font style image or graphics.
type: docs
weight: 10
url: /java/com.groupdocs.viewer.results/resource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Serializable
```
public class Resource implements Serializable
```

Represents HTML resource such as font, style, image or graphics.
## Constructors

| Constructor | Description |
| --- | --- |
| [Resource(String fileName, boolean nested)](#Resource-java.lang.String-boolean-) | Creates new instance of [Resource](../../com.groupdocs.viewer.results/resource) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFileName()](#getFileName--) | The resource file name. |
| [isNested()](#isNested--) | Indicates whether resource resides inside another resource, e.g. font resource that resides in CSS or SVG resource. |
| [toString()](#toString--) | Returns a string that represents the current object. |
### Resource(String fileName, boolean nested) {#Resource-java.lang.String-boolean-}
```
public Resource(String fileName, boolean nested)
```


Creates new instance of [Resource](../../com.groupdocs.viewer.results/resource) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Resource file name. |
| nested | boolean | Indicates whether resource resides inside another resource, e.g. font resource that resides in CSS or SVG resource. |

### getFileName() {#getFileName--}
```
public final String getFileName()
```


The resource file name.

**Returns:**
java.lang.String - The resource file name.
### isNested() {#isNested--}
```
public final boolean isNested()
```


Indicates whether resource resides inside another resource, e.g. font resource that resides in CSS or SVG resource.

**Returns:**
boolean - whether resource resides inside another resource, e.g. font resource that resides in CSS or SVG resource.
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
