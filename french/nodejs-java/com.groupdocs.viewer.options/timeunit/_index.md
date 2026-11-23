---
title: "TimeUnit"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Unité de temps de la durée du projet."
type: docs
weight: 47
url: /fr/nodejs-java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

Unité de temps de la durée du projet.

L'énumération TimeUnit représente différentes unités de temps pour spécifier la durée d'un projet dans le composant GroupDocs.Viewer. Elle fournit un ensemble d'unités de temps prédéfinies qui peuvent être utilisées pour représenter et calculer la durée d'un projet, comme les jours, les mois, etc. Pour plus de détails, voir la [documentation][].

Exemple d'utilisation :

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
## Champs

| Champ | Description |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | L'échelle de temps inconnue. |
| [DAYS](#DAYS) | Échelle de temps en jours. |
| [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | Échelle de temps en tiers de mois. |
| [MONTHS](#MONTHS) | Échelle de temps en mois. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


L'échelle de temps inconnue. Cette unité de temps représente une échelle de temps inconnue ou non spécifiée.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


Échelle de temps en jours. Cette unité de temps représente un intervalle d'un jour.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


Échelle de temps en tiers de mois. Cette unité de temps représente un intervalle d'un tiers de mois.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


Échelle de temps en mois. Cette unité de temps représente un intervalle d'un mois.

Pour plus de détails, voir la [documentation][].


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
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit)
