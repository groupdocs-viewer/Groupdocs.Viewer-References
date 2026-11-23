---
title: "Line"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Représente un rectangle positionné relativement qui contient une seule ligne."
type: docs
weight: 18
url: /fr/java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

Représente un rectangle positionné relativement qui contient une seule ligne.


L'interface Line définit le contrat pour accéder et manipuler une ligne représentée par un rectangle
dans le composant GroupDocs.Viewer. Il fournit des méthodes pour récupérer des informations telles que le texte de la ligne,
position et taille du rectangle.


Exemple d'utilisation :

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List lines = viewInfo.getPages().get(0).getLines();
     for (Line line : lines) {
         // Use the line object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LineImpl.*

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getWords()](#getWords--) | Récupère les mots contenus dans la ligne. |
|
|  | [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | Définit les mots contenus dans la ligne. |
|
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


Récupère les mots contenus dans la ligne.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - les mots contenus dans la ligne.

### setWords(List<Word> wordList) {#setWords-java.util.List-com.groupdocs.viewer.results.Word--}
```
public abstract void setWords(List<Word> wordList)
```


Définit les mots contenus dans la ligne.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | wordList | java.util.List<com.groupdocs.viewer.results.Word> | les mots contenus dans la ligne. |
|

