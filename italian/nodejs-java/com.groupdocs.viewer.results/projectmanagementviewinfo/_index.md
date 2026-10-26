---
title: "ProjectManagementViewInfo"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Rappresenta le informazioni di visualizzazione per un documento MS Project."
type: docs
weight: 23
url: /it/nodejs-java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

Rappresenta le informazioni di visualizzazione per un documento MS Project.

L'interfaccia ProjectManagementViewInfo definisce il contratto per accedere e manipolare le informazioni di visualizzazione di un documento MS Project nel componente GroupDocs.Viewer. Fornisce metodi per recuperare informazioni come le date di inizio e fine, e altre proprietà.

Esempio di utilizzo:

```

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getStartDate()](#getStartDate--) | Recupera la data e l'ora di inizio del progetto. |
| [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | Imposta la data e l'ora di inizio del progetto. |
| [getEndDate()](#getEndDate--) | Recupera la data e l'ora di completamento del progetto. |
| [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | Imposta la data e l'ora di fine del progetto. |
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


Recupera la data e l'ora di inizio del progetto.

**Returns:**
java.util.Date - la data e l'ora di inizio del progetto.
### setStartDate(Date startDate) {#setStartDate-java.util.Date-}
```
public abstract void setStartDate(Date startDate)
```


Imposta la data e l'ora di inizio del progetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startDate | java.util.Date | la nuova data e ora di inizio da impostare. |

### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


Recupera la data e l'ora di completamento del progetto.

**Returns:**
java.util.Date - la data e l'ora di fine del progetto.
### setEndDate(Date endDate) {#setEndDate-java.util.Date-}
```
public abstract void setEndDate(Date endDate)
```


Imposta la data e l'ora di fine del progetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| endDate | java.util.Date | la nuova data e ora di fine da impostare. |

