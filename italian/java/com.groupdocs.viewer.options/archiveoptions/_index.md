---
title: "ArchiveOptions"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Fornisce opzioni per il rendering dei file di archivio."
type: docs
weight: 10
url: /it/java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

Fornisce opzioni per il rendering dei file di archivio.


Il
ArchiveOptions
La classe rappresenta un insieme di opzioni che possono essere utilizzate per configurare il rendering dei file di archivio nel modulo visualizzatore.
Consente di personalizzare vari aspetti del processo di rendering, come il numero di elementi per pagina e così via.


Esempio di utilizzo:

````

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
````


***Note:** The 
ArchiveOptions
La classe fornisce una gamma di opzioni di personalizzazione per il rendering dei file di archivio.
Puoi configurare queste opzioni in base alle tue esigenze specifiche per ottenere l'output desiderato.*

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [ArchiveOptions()](#ArchiveOptions--) | Crea una nuova istanza della classe ArchiveOptions con le impostazioni predefinite. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFolder()](#getFolder--) | Ottiene la cartella all'interno dell'archivio che verrà utilizzata per il rendering. |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | Imposta la cartella all'interno dell'archivio che verrà utilizzata per il rendering. |
|
|  | [getFileName()](#getFileName--) | Ottiene il nome file da visualizzare nell'intestazione. |
|
|  | [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | Imposta il nome file da visualizzare nell'intestazione. |
|
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


Crea una nuova istanza della classe ArchiveOptions con le impostazioni predefinite.


### getFolder() {#getFolder--}
```
public final String getFolder()
```


Ottiene la cartella all'interno dell'archivio che verrà utilizzata per il rendering.


Per impostazione predefinita, GroupDocs.Viewer renderizza gli elementi da tutte le cartelle contenute nell'archivio. Per renderizzare gli elementi da una cartella specifica, imposta questa proprietà.
Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder).


**Returns:**
java.lang.String - la cartella da renderizzare.

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Imposta la cartella all'interno dell'archivio che verrà utilizzata per il rendering.


Per impostazione predefinita, GroupDocs.Viewer renderizza gli elementi da tutte le cartelle contenute nell'archivio. Per renderizzare gli elementi da una cartella specifica, imposta questa proprietà.
Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | La cartella da renderizzare. |
|

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


Ottiene il nome file da visualizzare nell'intestazione.


Per impostazione predefinita, GroupDocs.Viewer visualizza il nome del file di archivio nell'intestazione di ogni pagina. Per modificare o nascondere questo nome, impostare questa proprietà.
Per ulteriori informazioni e un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name).


**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.

### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


Imposta il nome file da visualizzare nell'intestazione.


Per impostazione predefinita, GroupDocs.Viewer visualizza il nome del file di archivio nell'intestazione di ogni pagina. Per modificare o nascondere questo nome, impostare questa proprietà.
Per ulteriori informazioni e un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileName | [FileName](../../com.groupdocs.viewer.options/filename) | Il nome file da visualizzare. |
|

