---
title: "LotusNotesViewInfo"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Rappresenta le informazioni di visualizzazione per l'archiviazione di un database Lotus Notes."
type: docs
weight: 19
url: /it/nodejs-java/com.groupdocs.viewer.results/lotusnotesviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface LotusNotesViewInfo extends ViewInfo
```

Rappresenta le informazioni di visualizzazione per l'archiviazione di un database Lotus Notes.

L'interfaccia LotusNotesViewInfo definisce il contratto per accedere e manipolare le informazioni di visualizzazione per l'archiviazione di database Lotus Notes nel componente GroupDocs.Viewer. Fornisce metodi per recuperare informazioni come il conteggio delle note e altre proprietà.

Esempio di utilizzo:

```

 try (Viewer viewer = new Viewer("document.nsf")) {
     final LotusNotesViewInfo viewInfo = (LotusNotesViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is LotusNotesViewInfoImpl.*
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getNotesCount()](#getNotesCount--) | Recupera il conteggio delle note nell'archivio. |
| [setNotesCount(int count)](#setNotesCount-int-) | Imposta il conteggio delle note nell'archivio. |
### getNotesCount() {#getNotesCount--}
```
public abstract int getNotesCount()
```


Recupera il conteggio delle note nell'archivio.

**Returns:**
int - il conteggio delle note nell'archivio.
### setNotesCount(int count) {#setNotesCount-int-}
```
public abstract void setNotesCount(int count)
```


Imposta il conteggio delle note nell'archivio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| conteggio | int | il conteggio delle note nell'archivio. |

