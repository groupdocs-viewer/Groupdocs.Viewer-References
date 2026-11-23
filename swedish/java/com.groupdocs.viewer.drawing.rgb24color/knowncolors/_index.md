---
title: "KnownColors"
second_title: "GroupDocs.Viewer för Java API-referens"
description: 
type: docs
weight: 10
url: /sv/java/com.groupdocs.viewer.drawing.rgb24color/knowncolors/
---
**Inheritance:**
java.lang.Object
```
public class KnownColors
```
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [tryFindColor(String keyword, Rgb24Color[] output)](#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---) | Försöker hitta en färg efter dess strängnamn. |
|
|  | [tryFindName(Rgb24Color color, String[] name)](#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---) | Försöker hitta ett färgnamn efter dess RGB‑värde. |
|
### tryFindColor(String keyword, Rgb24Color[] output) {#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---}
```
public static boolean tryFindColor(String keyword, Rgb24Color[] output)
```


Försöker hitta en färg efter dess strängnamn.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | nyckelord | java.lang.String | Ett färgnamn. |
|
|  | output | [Rgb24Color\[\]](../../com.groupdocs.viewer.drawing/rgb24color) | Resultatbehållaren för den hittade färgen, eller CssLevel1.Black vid fel. |
|

**Returns:**
boolean – True om färgen hittades framgångsrikt efter namn, false annars.

### tryFindName(Rgb24Color color, String[] name) {#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---}
```
public static boolean tryFindName(Rgb24Color color, String[] name)
```


Försöker hitta ett färgnamn efter dess RGB‑värde.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | color | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) | En färginstans. |
|
|  | namn | java.lang.String[] | Resultatbehållaren för det hittade färgnamnet, eller null vid fel. |
|

**Returns:**
boolean – True om namnet hittades framgångsrikt för den angivna färgen, false annars.

