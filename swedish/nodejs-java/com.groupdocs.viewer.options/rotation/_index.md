---
title: "Rotation"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Innehåller sidrotation i grader medurs."
type: docs
weight: 45
url: /sv/nodejs-java/com.groupdocs.viewer.options/rotation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Rotation extends Enum<Rotation>
```

Innehåller sidrotation i grader (medurs).

Rotation‑enumet representerar olika rotationsvinklar för en sida i GroupDocs.Viewer‑komponenten. Det tillhandahåller en uppsättning fördefinierade rotationsalternativ som kan användas för att ange rotationsvinkeln vid rendering av en sida i olika dokumentvisnings‑ eller konverteringsscenarier.

Exempel på användning:

```

 PdfViewOptions pdfViewOptions = new PdfViewOptions();

 pdfViewOptions.rotatePage(1, Rotation.ON_90_DEGREE);
 pdfViewOptions.rotatePage(2, Rotation.ON_180_DEGREE);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ON_90_DEGREE](#ON-90-DEGREE) | Den 90‑graders sidrotationen. |
| [ON_180_DEGREE](#ON-180-DEGREE) | Den 180‑graders sidrotationen. |
| [ON_270_DEGREE](#ON-270-DEGREE) | Den 270‑graders sidrotationen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### ON_90_DEGREE {#ON-90-DEGREE}
```
public static final Rotation ON_90_DEGREE
```


Den 90‑graders sidrotationen. Denna rotation representerar en 90‑graders medursrotation av sidan.

### ON_180_DEGREE {#ON-180-DEGREE}
```
public static final Rotation ON_180_DEGREE
```


Den 180‑graders sidrotationen. Denna rotation representerar en 180‑graders medursrotation av sidan.

### ON_270_DEGREE {#ON-270-DEGREE}
```
public static final Rotation ON_270_DEGREE
```


Den 270‑graders sidrotationen. Denna rotation representerar en 270‑graders medursrotation av sidan.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[Rotation](../../com.groupdocs.viewer.options/rotation)
