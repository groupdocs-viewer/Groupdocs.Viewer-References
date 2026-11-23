---
title: "FileName"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Représente le nom d'un fichier dans une archive."
type: docs
weight: 15
url: /fr/java/com.groupdocs.viewer.options/filename/
---
**Inheritance:**
java.lang.Object
```
public class FileName
```

Représente le nom d'un fichier dans une archive.


La classe FileName encapsule le nom d'un fichier sans aucune information de chemin ou de répertoire.
Elle fournit des méthodes pour manipuler et récupérer des informations sur le nom du fichier.


Exemple d'utilisation :

````

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.getArchiveOptions().setFileName(new FileName("my-file-name"));

 final LoadOptions loadOptions = new LoadOptions(FileType.ZIP);
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     viewer.view(options);
     // Use the viewer object for archive document rendering
 }
 
````


***Note:** The FileName class is used to work with file names and does not handle file operations or manipulation.*

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [FileName(String fileName)](#FileName-java.lang.String-) | Initialise une nouvelle instance de |
FileName
classe.
|
## Champs

| Champ | Description |
| --- | --- |
|  | [EMPTY](#EMPTY) | Représente un nom de fichier vide. |
|
|  | [SOURCE](#SOURCE) | Représente le nom du fichier source. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getText()](#getText--) |  |
|  | [toString()](#toString--) | Renvoie une représentation sous forme de chaîne de l'objet actuel. |
|
### FileName(String fileName) {#FileName-java.lang.String-}
```
public FileName(String fileName)
```


Initialise une nouvelle instance de
FileName
classe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileName | java.lang.String | Le nom du fichier. |
|

### EMPTY {#EMPTY}
```
public static final FileName EMPTY
```


Représente un nom de fichier vide.


### SOURCE {#SOURCE}
```
public static final FileName SOURCE
```


Représente le nom du fichier source.


### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne de l'objet actuel.


**Returns:**
java.lang.String - une représentation sous forme de chaîne de l'objet actuel.

