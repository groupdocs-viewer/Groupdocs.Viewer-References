---
title: "TimeUnit"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Tijdseenheid van de projectduur."
type: docs
weight: 47
url: /nl/nodejs-java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

Tijdseenheid van de projectduur.

De TimeUnit‑enum vertegenwoordigt verschillende tijdseenheden voor het specificeren van de duur van een project in de GroupDocs.Viewer‑component. Het biedt een set vooraf gedefinieerde tijdseenheden die kunnen worden gebruikt om de duur van een project weer te geven en te berekenen, zoals dagen, maanden enzovoort. Voor details, zie de [documentation][].

Voorbeeldgebruik:

```

 HtmlViewOptions pdfViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = pdfViewOptions.getProjectManagementOptions();
 projectManagementOptions.setTimeUnit(TimeUnit.MONTHS);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit
## Velden

| Veld | Beschrijving |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | De onbekende tijdschaal. |
| [DAYS](#DAYS) | Dagen tijdschaal. |
| [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | Derden van maanden tijdschaal. |
| [MONTHS](#MONTHS) | Maanden tijdschaal. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


De onbekende tijdschaal. Deze tijdseenheid vertegenwoordigt een onbekende of niet-gespecificeerde tijdschaal.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


Dagen tijdschaal. Deze tijdseenheid vertegenwoordigt een interval van één dag.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


Derden van maanden tijdschaal. Deze tijdseenheid vertegenwoordigt een interval van een derde van de maand.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


Maanden tijdschaal. Deze tijdseenheid vertegenwoordigt een interval van één maand.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### values() {#values--}
```
public static TimeUnit[] values()
```




**Returns:**
com.groupdocs.viewer.options.TimeUnit[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TimeUnit valueOf(String name)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit)
