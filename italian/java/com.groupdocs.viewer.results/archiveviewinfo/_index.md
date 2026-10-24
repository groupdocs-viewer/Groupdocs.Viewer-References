---
title: "ArchiveViewInfo"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Rappresenta le informazioni di visualizzazione per un file archivio."
type: docs
weight: 11
url: /it/java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

Rappresenta le informazioni di visualizzazione per un file archivio.


L'interfaccia ArchiveViewInfo definisce il contratto per il recupero delle informazioni di visualizzazione specifiche per un file di archivio
nel componente GroupDocs.Viewer. Fornisce metodi per accedere a dettagli come il conteggio delle pagine, le dimensioni e le opzioni di rendering
specifici per i file di archivio.


Esempio di utilizzo:

````

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFolders()](#getFolders--) | Recupera l'elenco delle cartelle contenute nel file di archivio. |
|
|  | [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | Imposta l'elenco delle cartelle contenute nel file di archivio. |
|
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Recupera l'elenco delle cartelle contenute nel file di archivio.


**Returns:**
java.util.List<java.lang.String> - l'elenco delle cartelle.

### setFolders(List<String> folders) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> folders)
```


Imposta l'elenco delle cartelle contenute nel file di archivio.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | cartelle | java.util.List<java.lang.String> | l'elenco delle cartelle. |
|

