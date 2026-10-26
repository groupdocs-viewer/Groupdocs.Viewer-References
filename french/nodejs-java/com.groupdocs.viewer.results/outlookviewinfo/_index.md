---
title: "OutlookViewInfo"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Représente les informations de vue pour un fichier de données Outlook."
type: docs
weight: 20
url: /fr/nodejs-java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

Représente les informations de vue pour un fichier de données Outlook.

L'interface OutlookViewInfo définit le contrat pour accéder et manipuler les informations de vue d'un fichier de données Outlook dans le composant GroupDocs.Viewer. Elle fournit des méthodes pour récupérer des informations telles qu'une liste de dossiers et d'autres propriétés.

Exemple d'utilisation :

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is OutlookViewInfoImpl.*
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFolders()](#getFolders--) | Récupère la liste des dossiers contenus dans le fichier de données Outlook. |
| [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | Définit la liste des dossiers contenus dans le fichier de données Outlook. |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Récupère la liste des dossiers contenus dans le fichier de données Outlook.

**Returns:**
java.util.List<java.lang.String> - la liste des dossiers.
### setFolders(List<String> list) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> list)
```


Définit la liste des dossiers contenus dans le fichier de données Outlook.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| liste | java.util.List<java.lang.String> | la liste des dossiers. |

