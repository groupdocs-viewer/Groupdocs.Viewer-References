---
title: "OutlookViewInfo"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Rappresenta le informazioni di visualizzazione per un file di dati Outlook."
type: docs
weight: 22
url: /it/java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

Rappresenta le informazioni di visualizzazione per un file di dati Outlook.


L'interfaccia OutlookViewInfo definisce il contratto per accedere e manipolare le informazioni della vista
per un file Outlook Data nel componente GroupDocs.Viewer. Fornisce metodi per recuperare informazioni
come un elenco di cartelle e altre proprietà.


Esempio di utilizzo:

````

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is OutlookViewInfoImpl.*

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFolders()](#getFolders--) | Recupera l'elenco delle cartelle contenute nel file Outlook Data. |
|
|  | [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | Imposta l'elenco delle cartelle contenute nel file Outlook Data. |
|
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Recupera l'elenco delle cartelle contenute nel file Outlook Data.


**Returns:**
java.util.List<java.lang.String> - l'elenco delle cartelle.

### setFolders(List<String> list) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> list)
```


Imposta l'elenco delle cartelle contenute nel file Outlook Data.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | elenco | java.util.List<java.lang.String> | l'elenco delle cartelle. |
|

