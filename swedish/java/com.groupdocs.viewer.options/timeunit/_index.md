---
title: "TimeUnit"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Tidsenhet för projektets varaktighet."
type: docs
weight: 47
url: /sv/java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

Tidsenhet för projektets varaktighet.


TimeUnit‑enumet representerar olika tidsenheter för att ange varaktigheten av ett projekt i GroupDocs.Viewer‑komponenten.
Det tillhandahåller en uppsättning fördefinierade tidsenheter som kan användas för att representera och beräkna varaktigheten av ett projekt,
såsom dagar, månader och så vidare.
För detaljer, se [dokumentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


Exempel på användning:

````

 HtmlViewOptions pdfViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = pdfViewOptions.getProjectManagementOptions();
 projectManagementOptions.setTimeUnit(TimeUnit.MONTHS);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [UNSPECIFIED](#UNSPECIFIED) | Den okända tidsskalan. |
|
|  | [DAYS](#DAYS) | Dagars tidsenhet. |
|
|  | [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | Tredjedelar av månaders tidslinje. |
|
|  | [MONTHS](#MONTHS) | Månaders tidslinje. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


Den okända tidsskalan.
Denna tidsenhet representerar en okänd eller ospecificerad tidslinje.
För detaljer, se [dokumentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


Dagars tidsenhet.
Denna tidsenhet representerar ett en-dagsintervall.
För detaljer, se [dokumentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


Tredjedelar av månaders tidslinje.
Denna tidsenhet representerar ett intervall på en tredjedel av en månad.
För detaljer, se [dokumentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


Månaders tidslinje.
Denna tidsenhet representerar ett en-månadsintervall.
För detaljer, se [dokumentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit)
