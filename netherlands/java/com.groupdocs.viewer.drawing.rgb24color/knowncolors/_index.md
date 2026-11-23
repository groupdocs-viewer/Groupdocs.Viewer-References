---
title: "KnownColors"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: 
type: docs
weight: 10
url: /nl/java/com.groupdocs.viewer.drawing.rgb24color/knowncolors/
---
**Inheritance:**
java.lang.Object
```
public class KnownColors
```
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [tryFindColor(String keyword, Rgb24Color[] output)](#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---) | Probeert een kleur te vinden op basis van de tekenreeksnaam. |
|
|  | [tryFindName(Rgb24Color color, String[] name)](#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---) | Probeert een kleurnaam te vinden op basis van de RGB-waarde. |
|
### tryFindColor(String keyword, Rgb24Color[] output) {#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---}
```
public static boolean tryFindColor(String keyword, Rgb24Color[] output)
```


Probeert een kleur te vinden op basis van de tekenreeksnaam.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | trefwoord | java.lang.String | Een kleurnaam. |
|
|  | output | [Rgb24Color\[\]](../../com.groupdocs.viewer.drawing/rgb24color) | De resultaatscontainer voor de gevonden kleur, of CssLevel1.Black bij falen. |
|

**Returns:**
boolean - True als de kleur succesvol werd gevonden op naam, false anders.

### tryFindName(Rgb24Color color, String[] name) {#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---}
```
public static boolean tryFindName(Rgb24Color color, String[] name)
```


Probeert een kleurnaam te vinden op basis van de RGB-waarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | color | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) | Een kleurinstantie. |
|
|  | name | java.lang.String[] | De resultaatscontainer voor de gevonden kleurnaam, of null bij falen. |
|

**Returns:**
boolean - True als de naam succesvol werd gevonden voor de gegeven kleur, false anders.

