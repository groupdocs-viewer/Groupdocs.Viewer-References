---
title: "ProjectManagementViewInfo"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Représente les informations de vue d'un document MS Project."
type: docs
weight: 25
url: /fr/java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

Représente les informations de vue d'un document MS Project.


L'interface ProjectManagementViewInfo définit le contrat pour accéder et manipuler les informations de vue
pour un document MS Project dans le composant GroupDocs.Viewer. Elle fournit des méthodes pour récupérer des informations
telles que les dates de début et de fin, ainsi que d'autres propriétés.


Exemple d'utilisation :

````

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getStartDate()](#getStartDate--) | Récupère la date et l'heure de début du projet. |
|
|  | [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | Définit la date et l'heure de début du projet. |
|
|  | [getEndDate()](#getEndDate--) | Récupère la date et l'heure prévues pour l'achèvement du projet. |
|
|  | [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | Définit la date et l'heure de fin du projet. |
|
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


Récupère la date et l'heure de début du projet.


**Returns:**
java.util.Date - la date et l'heure de début du projet.

### setStartDate(Date startDate) {#setStartDate-java.util.Date-}
```
public abstract void setStartDate(Date startDate)
```


Définit la date et l'heure de début du projet.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | startDate | java.util.Date | la nouvelle date et heure de début à définir. |
|

### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


Récupère la date et l'heure prévues pour l'achèvement du projet.


**Returns:**
java.util.Date - la date et l'heure de fin du projet.

### setEndDate(Date endDate) {#setEndDate-java.util.Date-}
```
public abstract void setEndDate(Date endDate)
```


Définit la date et l'heure de fin du projet.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | endDate | java.util.Date | la nouvelle date et heure de fin à définir. |
|

