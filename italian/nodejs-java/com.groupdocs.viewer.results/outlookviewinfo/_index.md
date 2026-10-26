---
title: "OutlookViewInfo"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Rappresenta le informazioni di visualizzazione per un file di dati Outlook."
type: docs
weight: 20
url: /it/nodejs-java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

Rappresenta le informazioni di visualizzazione per un file di dati Outlook.

L'interfaccia OutlookViewInfo definisce il contratto per accedere e manipolare le informazioni di visualizzazione per un file di dati Outlook nel componente GroupDocs.Viewer. Fornisce metodi per recuperare informazioni come un elenco di cartelle e altre proprietà.

Esempio di utilizzo:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is OutlookViewInfoImpl.*
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFolders()](#getFolders--) | Recupera l'elenco delle cartelle contenute nel file di dati Outlook. |
| [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | Imposta l'elenco delle cartelle contenute nel file di dati Outlook. |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Recupera l'elenco delle cartelle contenute nel file di dati Outlook.

**Returns:**
java.util.List<java.lang.String> - l'elenco delle cartelle.
### setFolders(List<String> list) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> list)
```


Imposta l'elenco delle cartelle contenute nel file di dati Outlook.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| elenco | java.util.List<java.lang.String> | l'elenco delle cartelle. |

