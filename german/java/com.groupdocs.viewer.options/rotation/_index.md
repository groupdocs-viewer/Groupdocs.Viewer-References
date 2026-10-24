---
title: "Rotation"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Enthält die Seitendrehung in Grad im Uhrzeigersinn."
type: docs
weight: 45
url: /de/java/com.groupdocs.viewer.options/rotation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Rotation extends Enum<Rotation>
```

Enthält die Seitendrehung in Grad (im Uhrzeigersinn).


Das Rotation‑Enum repräsentiert verschiedene Drehwinkel für eine Seite in der GroupDocs.Viewer‑Komponente.
Es bietet eine Reihe vordefinierter Rotationsoptionen, die verwendet werden können, um den Rotationswinkel anzugeben
für das Rendern einer Seite in verschiedenen Dokumentanzeige‑ oder Konvertierungsszenarien.


Beispielverwendung:

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();

 pdfViewOptions.rotatePage(1, Rotation.ON_90_DEGREE);
 pdfViewOptions.rotatePage(2, Rotation.ON_180_DEGREE);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [ON_90_DEGREE](#ON-90-DEGREE) | Die 90‑Grad‑Seitendrehung. |
|
|  | [ON_180_DEGREE](#ON-180-DEGREE) | Die 180‑Grad‑Seitendrehung. |
|
|  | [ON_270_DEGREE](#ON-270-DEGREE) | Die 270‑Grad‑Seitendrehung. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### ON_90_DEGREE {#ON-90-DEGREE}
```
public static final Rotation ON_90_DEGREE
```


Die 90‑Grad‑Seitendrehung.
Diese Drehung stellt eine 90‑Grad‑Drehung der Seite im Uhrzeigersinn dar.


### ON_180_DEGREE {#ON-180-DEGREE}
```
public static final Rotation ON_180_DEGREE
```


Die 180‑Grad‑Seitendrehung.
Diese Drehung stellt eine 180‑Grad‑Drehung der Seite im Uhrzeigersinn dar.


### ON_270_DEGREE {#ON-270-DEGREE}
```
public static final Rotation ON_270_DEGREE
```


Die 270‑Grad‑Seitendrehung.
Diese Drehung stellt eine 270‑Grad‑Drehung der Seite im Uhrzeigersinn dar.


### values() {#values--}
```
public static Rotation[] values()
```




**Returns:**
com.groupdocs.viewer.options.Rotation[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Rotation valueOf(String name)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[Rotation](../../com.groupdocs.viewer.options/rotation)
