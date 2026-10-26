---
title: "LotusNotesViewInfo"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Représente les informations de vue pour le stockage de base de données Lotus Notes."
type: docs
weight: 19
url: /fr/nodejs-java/com.groupdocs.viewer.results/lotusnotesviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface LotusNotesViewInfo extends ViewInfo
```

Représente les informations de vue pour le stockage de base de données Lotus Notes.

L'interface LotusNotesViewInfo définit le contrat pour accéder et manipuler les informations de vue du stockage de base de données Lotus Notes dans le composant GroupDocs.Viewer. Elle fournit des méthodes pour récupérer des informations telles que le nombre de notes et d'autres propriétés.

Exemple d'utilisation :

```

 try (Viewer viewer = new Viewer("document.nsf")) {
     final LotusNotesViewInfo viewInfo = (LotusNotesViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is LotusNotesViewInfoImpl.*
## Méthodes

| Méthode | Description |
| --- | --- |
| [getNotesCount()](#getNotesCount--) | Récupère le nombre de notes dans le stockage. |
| [setNotesCount(int count)](#setNotesCount-int-) | Définit le nombre de notes dans le stockage. |
### getNotesCount() {#getNotesCount--}
```
public abstract int getNotesCount()
```


Récupère le nombre de notes dans le stockage.

**Returns:**
int - le nombre de notes dans le stockage.
### setNotesCount(int count) {#setNotesCount-int-}
```
public abstract void setNotesCount(int count)
```


Définit le nombre de notes dans le stockage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| count | int | le nombre de notes dans le stockage. |

