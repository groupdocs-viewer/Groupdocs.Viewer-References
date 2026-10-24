---
title: "PathUtils"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "La classe PathUtils fournit des méthodes utilitaires pour travailler avec les chemins de fichiers."
type: docs
weight: 13
url: /fr/java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

La classe PathUtils fournit des méthodes utilitaires pour travailler avec les chemins de fichiers.


La classe PathUtils contient des méthodes statiques qui vous permettent d'effectuer diverses opérations
sur les chemins de fichiers dans le composant GroupDocs.Viewer.


Exemple d'utilisation :

````

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
````


## Méthodes

| Méthode | Description |
| --- | --- |
|  | [combine(String[] params)](#combine-java.lang.String...-) | Combinez les parties de chemins en utilisant le séparateur. |
|
|  | [getFileName(String path)](#getFileName-java.lang.String-) | Obtient le nom de fichier. |
|
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


Combinez les parties de chemins en utilisant le séparateur.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | paramètres | java.lang.String[] | les parties des chemins |
|

**Returns:**
java.lang.String - le chemin résultant

### getFileName(String path) {#getFileName-java.lang.String-}
```
public static String getFileName(String path)
```


Obtient le nom de fichier.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | chemin | java.lang.String | le chemin |
|

**Returns:**
java.lang.String - le nom de fichier

