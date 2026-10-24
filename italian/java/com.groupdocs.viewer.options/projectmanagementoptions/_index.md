---
title: "ProjectManagementOptions"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Fornisce opzioni per il rendering dei file di gestione progetti."
type: docs
weight: 27
url: /it/java/com.groupdocs.viewer.options/projectmanagementoptions/
---
**Inheritance:**
java.lang.Object
```
public class ProjectManagementOptions
```

Fornisce opzioni per il rendering dei file di gestione progetti.


La classe ProjectManagementOptions incapsula varie impostazioni e parametri che possono essere utilizzati
per controllare il rendering dei file di project management (come Microsoft Project o simili)
nel componente GroupDocs.Viewer.
Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


Esempio di utilizzo:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 ProjectManagementOptions projectManagementOptions = pngViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);
 projectManagementOptions.setStartDate(new Date(2021, 11, 23));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [ProjectManagementOptions()](#ProjectManagementOptions--) | Inizializza una nuova istanza di |
ProjectManagementOptions
classe.
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Recupera la dimensione della pagina di output. |
|
|  | [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Imposta la dimensione della pagina di output. |
|
|  | [getTimeUnit()](#getTimeUnit--) | Recupera l'unità di tempo. |
|
|  | [setTimeUnit(TimeUnit value)](#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-) | Recupera l'unità di tempo. |
|
|  | [getStartDate()](#getStartDate--) | Recupera la data di inizio della vista Gantt Chart da includere nell'output. |
|
|  | [setStartDate(Date value)](#setStartDate-java.util.Date-) | Imposta la data di inizio della vista Gantt Chart da includere nell'output. |
|
|  | [getEndDate()](#getEndDate--) | Recupera la data di fine della vista Gantt Chart da includere nell'output. |
|
|  | [setEndDate(Date value)](#setEndDate-java.util.Date-) | Imposta la data di fine della vista Gantt Chart da includere nell'output. |
|
### ProjectManagementOptions() {#ProjectManagementOptions--}
```
public ProjectManagementOptions()
```


Inizializza una nuova istanza di
ProjectManagementOptions
classe.


### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Recupera la dimensione della pagina di output.


Per l'esempio di codice, vedere la [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size).


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the output page size.

### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Imposta la dimensione della pagina di output.


Per l'esempio di codice, vedere la [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | La dimensione della pagina di output. |
|

### getTimeUnit() {#getTimeUnit--}
```
public final TimeUnit getTimeUnit()
```


Recupera l'unità di tempo.


Per l'esempio di codice, vedere la [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit) - the time unit.

### setTimeUnit(TimeUnit value) {#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-}
```
public final void setTimeUnit(TimeUnit value)
```


Recupera l'unità di tempo.


Per l'esempio di codice, vedere la [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [TimeUnit](../../com.groupdocs.viewer.options/timeunit) | L'unità di tempo. |
|

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Recupera la data di inizio della vista Gantt Chart da includere nell'output.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Per l'esempio di codice, vedere la [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Returns:**
java.util.Date - la data di inizio della vista Gantt Chart.

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Imposta la data di inizio della vista Gantt Chart da includere nell'output.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Per l'esempio di codice, vedere la [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.util.Date | La data di inizio della vista Gantt Chart. |
|

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Recupera la data di fine della vista Gantt Chart da includere nell'output.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Per l'esempio di codice, vedere la [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Returns:**
java.util.Date - la data di fine della vista Gantt Chart.

### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Imposta la data di fine della vista Gantt Chart da includere nell'output.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Per l'esempio di codice, vedere la [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.util.Date | La data di fine della vista Gantt Chart. |
|

