---
title: "TimeUnit"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Unità di tempo della durata del progetto."
type: docs
weight: 47
url: /it/java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

Unità di tempo della durata del progetto.


L'enumerazione TimeUnit rappresenta diverse unità di tempo per specificare la durata di un progetto nel componente GroupDocs.Viewer.
Fornisce un insieme di unità di tempo predefinite che possono essere usate per rappresentare e calcolare la durata di un progetto,
come giorni, mesi e così via.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


Esempio di utilizzo:

````

 HtmlViewOptions pdfViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = pdfViewOptions.getProjectManagementOptions();
 projectManagementOptions.setTimeUnit(TimeUnit.MONTHS);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Campi

| Campo | Descrizione |
| --- | --- |
|  | [UNSPECIFIED](#UNSPECIFIED) | La scala temporale sconosciuta. |
|
|  | [DAYS](#DAYS) | Scala temporale dei giorni. |
|
|  | [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | Scala temporale di terzi di mesi. |
|
|  | [MONTHS](#MONTHS) | Scala temporale di mesi. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


La scala temporale sconosciuta.
Questa unità di tempo rappresenta una scala temporale sconosciuta o non specificata.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


Scala temporale dei giorni.
Questa unità di tempo rappresenta un intervallo di un giorno.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


Scala temporale di terzi di mesi.
Questa unità di tempo rappresenta un intervallo di un terzo di mese.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


Scala temporale di mesi.
Questa unità di tempo rappresenta un intervallo di un mese.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit)
