---
title: "TimeUnit"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Zeiteinheit der Projektdauer."
type: docs
weight: 47
url: /de/nodejs-java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

Zeiteinheit der Projektdauer.

Das TimeUnit‑Enum repräsentiert verschiedene Zeiteinheiten zur Angabe der Projektdauer in der GroupDocs.Viewer‑Komponente. Es stellt eine Menge vordefinierter Zeiteinheiten bereit, die zur Darstellung und Berechnung der Projektdauer verwendet werden können, z. B. Tage, Monate usw. Weitere Details finden Sie in der [Dokumentation][].

Beispielhafte Verwendung:

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
## Felder

| Feld | Beschreibung |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | Die unbekannte Zeitskala. |
| [DAYS](#DAYS) | Tage‑Zeitskala. |
| [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | Drittel‑Monats‑Zeitskala. |
| [MONTHS](#MONTHS) | Monats‑Zeitskala. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


Die unbekannte Zeitskala. Diese Zeiteinheit stellt eine unbekannte oder nicht spezifizierte Zeitskala dar.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


Tage‑Zeitskala. Diese Zeiteinheit stellt ein Intervall von einem Tag dar.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


Drittel‑Monats‑Zeitskala. Diese Zeiteinheit stellt ein Intervall von einem Drittel eines Monats dar.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


Monats‑Zeitskala. Diese Zeiteinheit stellt ein Intervall von einem Monat dar.

Weitere Details finden Sie in der [Dokumentation][].


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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit)
