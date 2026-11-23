---
title: "KnownColors"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: 
type: docs
weight: 10
url: /de/java/com.groupdocs.viewer.drawing.rgb24color/knowncolors/
---
**Inheritance:**
java.lang.Object
```
public class KnownColors
```
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [tryFindColor(String keyword, Rgb24Color[] output)](#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---) | Versucht, eine Farbe anhand ihres String-Namens zu finden. |
|
|  | [tryFindName(Rgb24Color color, String[] name)](#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---) | Versucht, einen Farbnamen anhand seines RGB-Werts zu finden. |
|
### tryFindColor(String keyword, Rgb24Color[] output) {#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---}
```
public static boolean tryFindColor(String keyword, Rgb24Color[] output)
```


Versucht, eine Farbe anhand ihres String-Namens zu finden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | keyword | java.lang.String | Ein Farbname. |
|
|  | output | [Rgb24Color\[\]](../../com.groupdocs.viewer.drawing/rgb24color) | Der Ergebnisbehälter für die gefundene Farbe oder CssLevel1.Black bei einem Fehler. |
|

**Returns:**
boolean - Wahr, wenn die Farbe erfolgreich nach Namen gefunden wurde, sonst falsch.

### tryFindName(Rgb24Color color, String[] name) {#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---}
```
public static boolean tryFindName(Rgb24Color color, String[] name)
```


Versucht, einen Farbnamen anhand seines RGB-Werts zu finden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | color | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) | Eine Farbinstanz. |
|
|  | Name | java.lang.String[] | Der Ergebnisbehälter für den gefundenen Farbnamen oder null bei einem Fehlschlag. |
|

**Returns:**
boolean - Wahr, wenn der Name für die gegebene Farbe erfolgreich gefunden wurde, sonst falsch.

