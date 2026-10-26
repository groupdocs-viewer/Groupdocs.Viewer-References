---
title: "ProjectManagementOptions"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Fournit des options pour le rendu des fichiers de gestion de projet."
type: docs
weight: 27
url: /fr/nodejs-java/com.groupdocs.viewer.options/projectmanagementoptions/
---
**Inheritance:**
java.lang.Object
```
public class ProjectManagementOptions
```

Fournit des options pour le rendu des fichiers de gestion de projet.

La classe ProjectManagementOptions encapsule divers paramètres et réglages qui peuvent être utilisés pour contrôler le rendu des fichiers de gestion de projet (tels que Microsoft Project ou similaires) dans le composant GroupDocs.Viewer. Pour plus de détails, consultez la [documentation][].

Exemple d'utilisation :

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 ProjectManagementOptions projectManagementOptions = pngViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);
 projectManagementOptions.setStartDate(new Date(2021, 11, 23));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ProjectManagementOptions()](#ProjectManagementOptions--) | Initialise une nouvelle instance de la classe  ProjectManagementOptions  . |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPageSize()](#getPageSize--) | Récupère la taille de page de sortie. |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Définit la taille de page de sortie. |
| [getTimeUnit()](#getTimeUnit--) | Récupère l'unité de temps. |
| [setTimeUnit(TimeUnit value)](#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-) | Récupère l'unité de temps. |
| [getStartDate()](#getStartDate--) | Récupère la date de début de la vue Gantt Chart à inclure dans la sortie. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Définit la date de début de la vue Gantt Chart à inclure dans la sortie. |
| [getEndDate()](#getEndDate--) | Récupère la date de fin de la vue Gantt Chart à inclure dans la sortie. |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Définit la date de fin de la vue Gantt Chart à inclure dans la sortie. |
### ProjectManagementOptions() {#ProjectManagementOptions--}
```
public ProjectManagementOptions()
```


Initialise une nouvelle instance de la classe  ProjectManagementOptions  .

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Récupère la taille de page de sortie.

Pour un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the output page size.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Définit la taille de page de sortie.

Pour un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | La taille de page de sortie. |

### getTimeUnit() {#getTimeUnit--}
```
public final TimeUnit getTimeUnit()
```


Récupère l'unité de temps.

Pour un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit) - the time unit.
### setTimeUnit(TimeUnit value) {#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-}
```
public final void setTimeUnit(TimeUnit value)
```


Récupère l'unité de temps.

Pour un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TimeUnit](../../com.groupdocs.viewer.options/timeunit) | L'unité de temps. |

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Récupère la date de début de la vue Gantt Chart à inclure dans la sortie.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date - la date de début de la vue Gantt Chart.
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Définit la date de début de la vue Gantt Chart à inclure dans la sortie.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Date | La date de début de la vue Gantt Chart. |

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Récupère la date de fin de la vue Gantt Chart à inclure dans la sortie.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date - la date de fin de la vue Gantt Chart.
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Définit la date de fin de la vue Gantt Chart à inclure dans la sortie.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Date | La date de fin de la vue Gantt Chart. |

