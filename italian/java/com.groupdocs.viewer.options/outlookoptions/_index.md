---
title: "OutlookOptions"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Fornisce opzioni per il rendering dei file di dati di Outlook."
type: docs
weight: 20
url: /it/java/com.groupdocs.viewer.options/outlookoptions/
---
**Inheritance:**
java.lang.Object
```
public class OutlookOptions
```

Fornisce opzioni per il rendering dei file di dati di Outlook.


La classe OutlookOptions incapsula varie impostazioni e parametri che possono essere utilizzati
per controllare il rendering dei file di dati Outlook (come file PST o OST) nel componente GroupDocs.Viewer.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options).


Esempio di utilizzo:

````

 OutlookOptions options = new OutlookOptions();
 options.setAddressFilter("@gmail.com");
 options.setFolder("folderName");

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setOutlookOptions(options);

 try (Viewer viewer = new Viewer("mail.pst")) {
   viewer.view(htmlViewOptions);
   // Use the viewer object for further operations
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OutlookOptions()](#OutlookOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFolder()](#getFolder--) | Ottiene il nome della cartella da renderizzare. |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | Imposta il nome della cartella da renderizzare. |
|
|  | [getTextFilter()](#getTextFilter--) | Ottiene le parole chiave utilizzate per filtrare i messaggi. |
|
|  | [setTextFilter(String value)](#setTextFilter-java.lang.String-) | Ottiene le parole chiave utilizzate per filtrare i messaggi. |
|
|  | [getAddressFilter()](#getAddressFilter--) | Ottiene l'indirizzo email utilizzato per filtrare i messaggi per mittente o destinatario. |
|
|  | [setAddressFilter(String value)](#setAddressFilter-java.lang.String-) | Imposta l'indirizzo email utilizzato per filtrare i messaggi per mittente o destinatario. |
|
|  | [getMaxItemsInFolder()](#getMaxItemsInFolder--) | Ottiene il numero massimo di messaggi o elementi che possono essere renderizzati da una cartella. |
|
|  | [setMaxItemsInFolder(int value)](#setMaxItemsInFolder-int-) | Imposta il numero massimo di messaggi o elementi che possono essere renderizzati da una cartella. |
|
### OutlookOptions() {#OutlookOptions--}
```
public OutlookOptions()
```


### getFolder() {#getFolder--}
```
public final String getFolder()
```


Ottiene il nome della cartella da renderizzare.
Il nome della cartella (ad es., Posta in arrivo, Elementi inviati o Elementi eliminati) da renderizzare.


Durante il rendering di un file dati Outlook, GroupDocs.Viewer renderizza i messaggi da tutte le cartelle contenute nel file (incluse le cartelle nidificate). Utilizza questa proprietà per renderizzare gli elementi da una cartella specifica.
Per un esempio di codice, consulta questa [documentazione](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder).


**Returns:**
java.lang.String - il nome della cartella da renderizzare.

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Imposta il nome della cartella da renderizzare.
Il nome della cartella (ad es., Posta in arrivo, Elementi inviati o Elementi eliminati) da renderizzare.


Durante il rendering di un file dati Outlook, GroupDocs.Viewer renderizza i messaggi da tutte le cartelle contenute nel file (incluse le cartelle nidificate). Utilizza questa proprietà per renderizzare gli elementi da una cartella specifica.
Per un esempio di codice, consulta questa [documentazione](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il nome della cartella da renderizzare. |
|

### getTextFilter() {#getTextFilter--}
```
public final String getTextFilter()
```


Ottiene le parole chiave utilizzate per filtrare i messaggi.


Utilizza questa proprietà per renderizzare tutti i messaggi che contengono testo specifico nell'oggetto o nel corpo. Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Returns:**
java.lang.String - le parole chiave.

### setTextFilter(String value) {#setTextFilter-java.lang.String-}
```
public final void setTextFilter(String value)
```


Ottiene le parole chiave utilizzate per filtrare i messaggi.


Utilizza questa proprietà per renderizzare tutti i messaggi che contengono testo specifico nell'oggetto o nel corpo. Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Le parole chiave. |
|

### getAddressFilter() {#getAddressFilter--}
```
public final String getAddressFilter()
```


Ottiene l'indirizzo email utilizzato per filtrare i messaggi per mittente o destinatario.


Utilizza questa proprietà per renderizzare tutti i messaggi che contengono testo specifico nell'indirizzo del mittente\\ufffds o del destinatario\\ufffds. Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Returns:**
java.lang.String - l'indirizzo email usato per filtrare i messaggi.

### setAddressFilter(String value) {#setAddressFilter-java.lang.String-}
```
public final void setAddressFilter(String value)
```


Imposta l'indirizzo email utilizzato per filtrare i messaggi per mittente o destinatario.


Utilizza questa proprietà per renderizzare tutti i messaggi che contengono testo specifico nell'indirizzo del mittente\\ufffds o del destinatario\\ufffds. Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | L'indirizzo email usato per filtrare i messaggi. |
|

### getMaxItemsInFolder() {#getMaxItemsInFolder--}
```
public final int getMaxItemsInFolder()
```


Ottiene il numero massimo di messaggi o elementi che possono essere renderizzati da una cartella.


I file dati Outlook possono essere di grandi dimensioni e il recupero di tutti i messaggi può richiedere molto tempo.
Questa impostazione limita il numero massimo di messaggi o elementi (come contatti e attività) che vengono renderizzati.
Il valore predefinito è 50. Imposta il valore a 0 per renderizzare tutti i messaggi.
Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render).


**Returns:**
int - il numero massimo di messaggi o elementi che possono essere renderizzati da una cartella.

### setMaxItemsInFolder(int value) {#setMaxItemsInFolder-int-}
```
public final void setMaxItemsInFolder(int value)
```


Imposta il numero massimo di messaggi o elementi che possono essere renderizzati da una cartella.


I file dati Outlook possono essere di grandi dimensioni e il recupero di tutti i messaggi può richiedere molto tempo.
Questa impostazione limita il numero massimo di messaggi o elementi (come contatti e attività) che vengono renderizzati.
Il valore predefinito è 50. Imposta il valore a 0 per renderizzare tutti i messaggi.
Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | Il numero massimo di messaggi o elementi che possono essere renderizzati da una cartella. |
|

