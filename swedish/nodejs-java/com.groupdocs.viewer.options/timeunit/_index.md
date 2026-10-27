---
title: "TimeUnit"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Tidsenhet för projektets varaktighet."
type: docs
weight: 47
url: /sv/nodejs-java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

Tidsenhet för projektets varaktighet.

Enumet TimeUnit representerar olika tidsenheter för att ange varaktigheten av ett projekt i GroupDocs.Viewer‑komponenten. Det tillhandahåller en uppsättning fördefinierade tidsenheter som kan användas för att representera och beräkna projektets varaktighet, såsom dagar, månader och så vidare. För detaljer, se [dokumentation][].

Exempel på användning:

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
## Fält

| Fält | Beskrivning |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | Den okända tidsenheten. |
| [DAYS](#DAYS) | Tidsenhet dagar. |
| [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | Tidsenhet tredjedelar av månader. |
| [MONTHS](#MONTHS) | Tidsenhet månader. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


Den okända tidsenheten. Denna tidsenhet representerar en okänd eller ospecificerad tidsenhet.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


Tidsenhet dagar. Denna tidsenhet representerar ett en-dagsintervall.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


Tidsenhet tredjedelar av månader. Denna tidsenhet representerar ett en-tredjedel av månaden‑intervall.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


Tidsenhet månader. Denna tidsenhet representerar ett en-månadsintervall.

För mer information, se [documentation][].


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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit)
