---
title: "PathUtils"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "La classe PathUtils fournit des méthodes utilitaires pour travailler avec les chemins de fichiers."
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

La classe PathUtils fournit des méthodes utilitaires pour travailler avec les chemins de fichiers.

La classe PathUtils contient des méthodes statiques qui vous permettent d'effectuer diverses opérations sur les chemins de fichiers dans le composant GroupDocs.Viewer.

Exemple d'utilisation :

```

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
```
## Méthodes

| Méthode | Description |
| --- | --- |
| [combine(String[] params)](#combine-java.lang.String...-) | Combine les parties de chemins en utilisant le séparateur. |
| [getFileName(String path)](#getFileName-java.lang.String-) | Obtient le nom de fichier. |
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


Combine les parties de chemins en utilisant le séparateur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| paramètres | java.lang.String[] | les parties du chemin |

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
| chemin | java.lang.String | le chemin |

**Returns:**
java.lang.String - le nom de fichier
