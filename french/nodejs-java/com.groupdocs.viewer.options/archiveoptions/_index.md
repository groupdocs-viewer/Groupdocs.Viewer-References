---
title: "ArchiveOptions"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Fournit des options pour le rendu des fichiers d'archive."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

Fournit des options pour le rendu des fichiers d'archive.

La classe  ArchiveOptions  représente un ensemble d'options pouvant être utilisées pour configurer le rendu des fichiers d'archive dans le module viewer. Elle vous permet de personnaliser divers aspects du processus de rendu, tels que le nombre d'éléments par page, etc.

Exemple d'utilisation :

```

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
```

***Note:** The  ArchiveOptions  class provides a range of customization options for rendering archive files. You can configure these options based on your specific requirements to achieve the desired output.*
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ArchiveOptions()](#ArchiveOptions--) | Crée une nouvelle instance de la classe ArchiveOptions avec les paramètres par défaut. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFolder()](#getFolder--) | Obtient le dossier à l'intérieur de l'archive qui sera utilisé pour le rendu. |
| [setFolder(String value)](#setFolder-java.lang.String-) | Définit le dossier à l'intérieur de l'archive qui sera utilisé pour le rendu. |
| [getFileName()](#getFileName--) | Obtient le nom de fichier à afficher dans l'en-tête. |
| [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | Définit le nom de fichier à afficher dans l'en-tête. |
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


Crée une nouvelle instance de la classe ArchiveOptions avec les paramètres par défaut.

### getFolder() {#getFolder--}
```
public final String getFolder()
```


Obtient le dossier à l'intérieur de l'archive qui sera utilisé pour le rendu.

Par défaut, GroupDocs.Viewer rend les éléments de tous les dossiers contenus dans l'archive. Pour rendre les éléments d'un dossier spécifique, définissez cette propriété. Pour un exemple de code, consultez la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder

**Returns:**
java.lang.String - le dossier à rendre.
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Définit le dossier à l'intérieur de l'archive qui sera utilisé pour le rendu.

Par défaut, GroupDocs.Viewer rend les éléments de tous les dossiers contenus dans l'archive. Pour rendre les éléments d'un dossier spécifique, définissez cette propriété. Pour un exemple de code, consultez la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Le dossier à rendre. |

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


Obtient le nom de fichier à afficher dans l'en-tête.

Par défaut, GroupDocs.Viewer affiche le nom du fichier d'archive dans l'en-tête de chaque page. Pour modifier ou masquer ce nom, définissez cette propriété. Pour plus d'informations et un exemple de code, consultez la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.
### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


Définit le nom de fichier à afficher dans l'en-tête.

Par défaut, GroupDocs.Viewer affiche le nom du fichier d'archive dans l'en-tête de chaque page. Pour modifier ou masquer ce nom, définissez cette propriété. Pour plus d'informations et un exemple de code, consultez la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | [FileName](../../com.groupdocs.viewer.options/filename) | Le nom de fichier à afficher. |

