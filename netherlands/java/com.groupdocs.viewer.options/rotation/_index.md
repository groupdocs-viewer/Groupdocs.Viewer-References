---
title: "Rotation"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Bevat paginrotatie in graden met de klok mee."
type: docs
weight: 45
url: /nl/java/com.groupdocs.viewer.options/rotation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Rotation extends Enum<Rotation>
```

Bevat paginadraaien in graden (met de klok mee).


De Rotation-enum vertegenwoordigt verschillende rotatiehoeken voor een pagina in de GroupDocs.Viewer-component.
Het biedt een reeks vooraf gedefinieerde rotatie-opties die kunnen worden gebruikt om de rotatiehoek op te geven
voor het renderen van een pagina in verschillende documentweergave- of conversiescenario's.


Voorbeeldgebruik:

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();

 pdfViewOptions.rotatePage(1, Rotation.ON_90_DEGREE);
 pdfViewOptions.rotatePage(2, Rotation.ON_180_DEGREE);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [ON_90_DEGREE](#ON-90-DEGREE) | De 90-graden paginrotatie. |
|
|  | [ON_180_DEGREE](#ON-180-DEGREE) | De 180-graden paginrotatie. |
|
|  | [ON_270_DEGREE](#ON-270-DEGREE) | De 270-graden paginrotatie. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### ON_90_DEGREE {#ON-90-DEGREE}
```
public static final Rotation ON_90_DEGREE
```


De 90-graden paginrotatie.
Deze rotatie vertegenwoordigt een 90-graden rotatie met de klok mee van de pagina.


### ON_180_DEGREE {#ON-180-DEGREE}
```
public static final Rotation ON_180_DEGREE
```


De 180-graden paginrotatie.
Deze rotatie vertegenwoordigt een 180-graden rotatie met de klok mee van de pagina.


### ON_270_DEGREE {#ON-270-DEGREE}
```
public static final Rotation ON_270_DEGREE
```


De 270-graden paginrotatie.
Deze rotatie vertegenwoordigt een 270-graden rotatie met de klok mee van de pagina.


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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Rotation](../../com.groupdocs.viewer.options/rotation)
