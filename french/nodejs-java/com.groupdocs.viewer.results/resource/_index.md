---
title: "Resource"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Représente une ressource HTML telle qu'une police, un style, une image ou un graphique."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.viewer.results/resource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Serializable
```
public class Resource implements Serializable
```

Représente une ressource HTML telle qu'une police, un style, une image ou un graphique.

La classe Resource représente une ressource utilisée dans le rendu HTML du composant GroupDocs.Viewer. Elle peut représenter différents types de ressources, telles que des polices, des styles, des images ou des graphiques, qui sont incluses ou référencées dans la sortie HTML générée lors du processus de rendu.

Exemple d'utilisation :

```

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forExternalResources(pageNumber -> , new ReleaseResourceStream() {
     @Override
     public void invoke(int pageNumber, Resource resource, OutputStream resourceStream) {
         // Handle resource
     }
 });
 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Resource(String fileName, boolean nested)](#Resource-java.lang.String-boolean-) | Crée une nouvelle instance de la classe Resource. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFileName()](#getFileName--) | Renvoie le nom de fichier de la ressource. |
| [setFileName(String fileName)](#setFileName-java.lang.String-) | Définit le nom de fichier de la ressource. |
| [isNested()](#isNested--) | Renvoie si la ressource se trouve à l'intérieur d'une autre ressource, par ex. une ressource de police qui se trouve dans une ressource CSS ou SVG. |
| [setNested(boolean nested)](#setNested-boolean-) | Définit si la ressource se trouve à l'intérieur d'une autre ressource. |
| [toString()](#toString--) | Renvoie une chaîne qui représente l'objet actuel. |
### Resource(String fileName, boolean nested) {#Resource-java.lang.String-boolean-}
```
public Resource(String fileName, boolean nested)
```


Crée une nouvelle instance de la classe Resource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Le nom de fichier de la ressource. |
| imbriqué | boolean | Indique si la ressource se trouve à l'intérieur d'une autre ressource, par ex., une ressource de police qui se trouve dans une ressource CSS ou SVG. |

### getFileName() {#getFileName--}
```
public final String getFileName()
```


Renvoie le nom de fichier de la ressource.

**Returns:**
java.lang.String - le nom de fichier de la ressource.
### setFileName(String fileName) {#setFileName-java.lang.String-}
```
public void setFileName(String fileName)
```


Définit le nom de fichier de la ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Le nouveau nom de fichier pour la ressource. |

### isNested() {#isNested--}
```
public final boolean isNested()
```


Renvoie si la ressource se trouve à l'intérieur d'une autre ressource, par ex. une ressource de police qui se trouve dans une ressource CSS ou SVG.

**Returns:**
boolean - Si la ressource se trouve à l'intérieur d'une autre ressource.
### setNested(boolean nested) {#setNested-boolean-}
```
public void setNested(boolean nested)
```


Définit si la ressource se trouve à l'intérieur d'une autre ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imbriqué | boolean | Si la ressource doit être définie comme imbriquée. |

### toString() {#toString--}
```
public String toString()
```


Renvoie une chaîne qui représente l'objet actuel.

**Returns:**
java.lang.String - la représentation sous forme de chaîne de l'objet actuel.
