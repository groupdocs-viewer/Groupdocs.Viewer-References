---
title: "Word"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Représente un rectangle positionné relativement qui contient un seul mot."
type: docs
weight: 28
url: /fr/java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

Représente un rectangle positionné relativement qui contient un seul mot.


L'interface Word représente un mot à l'intérieur d'un rectangle relativement positionné dans le composant GroupDocs.Viewer.
Elle étend l'interface TextElement et fournit des méthodes supplémentaires pour accéder et manipuler le contenu du mot.


Exemple d'utilisation :

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List words = viewInfo.getPages().get(0).getLines().get(0).getWords();
     for (Word word : words) {
         // Use the word object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is WordImpl.*

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getCharacters()](#getCharacters--) | Récupère les caractères contenus dans le mot. |
|
|  | [setCharacters(List<Character> characters)](#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--) | Définit les caractères contenus dans le mot. |
|
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


Récupère les caractères contenus dans le mot.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - la liste des caractères.

### setCharacters(List<Character> characters) {#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--}
```
public abstract void setCharacters(List<Character> characters)
```


Définit les caractères contenus dans le mot.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | caractères | java.util.List<com.groupdocs.viewer.results.Character> | la liste des caractères à définir. |
|

