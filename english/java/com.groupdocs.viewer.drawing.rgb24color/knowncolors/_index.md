---
title: KnownColors
second_title: GroupDocs.Viewer for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.groupdocs.viewer.drawing.rgb24color/knowncolors/
---
**Inheritance:**
java.lang.Object
```
public class KnownColors
```
## Methods

| Method | Description |
| --- | --- |
| [tryFindColor(String keyword, Rgb24Color[] output)](#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---) | Tries to find a color by its string name. |
| [tryFindName(Rgb24Color color, String[] name)](#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---) | Tries to find a color name by its RGB value. |
### tryFindColor(String keyword, Rgb24Color[] output) {#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---}
```
public static boolean tryFindColor(String keyword, Rgb24Color[] output)
```


Tries to find a color by its string name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| keyword | java.lang.String | A color name. |
| output | [Rgb24Color\[\]](../../com.groupdocs.viewer.drawing/rgb24color) | The result container for the found color, or CssLevel1.Black on failure. |

**Returns:**
boolean - True if the color was successfully found by name, false otherwise.
### tryFindName(Rgb24Color color, String[] name) {#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---}
```
public static boolean tryFindName(Rgb24Color color, String[] name)
```


Tries to find a color name by its RGB value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) | A color instance. |
| name | java.lang.String[] | The result container for the found color name, or null on failure. |

**Returns:**
boolean - True if the name was successfully found for the given color, false otherwise.
