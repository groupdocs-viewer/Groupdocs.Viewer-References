---
title: "ArchiveViewInfo"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Représente les informations de vue pour un fichier d'archive."
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

Représente les informations de vue pour un fichier d'archive.

L'interface ArchiveViewInfo définit le contrat pour récupérer les informations de vue spécifiques à un fichier d'archive dans le composant GroupDocs.Viewer. Elle fournit des méthodes pour accéder aux détails tels que le nombre de pages, les dimensions et les options de rendu spécifiques aux fichiers d'archive.

Exemple d'utilisation :

```

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFolders()](#getFolders--) | Récupère la liste des dossiers contenus dans le fichier d'archive. |
| [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | Définit la liste des dossiers contenus dans le fichier d'archive. |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Récupère la liste des dossiers contenus dans le fichier d'archive.

**Returns:**
java.util.List<java.lang.String> - la liste des dossiers.
### setFolders(List<String> folders) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> folders)
```


Définit la liste des dossiers contenus dans le fichier d'archive.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dossiers | java.util.List<java.lang.String> | la liste des dossiers. |

