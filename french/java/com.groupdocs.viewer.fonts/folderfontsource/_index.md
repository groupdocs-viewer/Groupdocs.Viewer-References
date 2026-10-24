---
title: "FolderFontSource"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Représente un dossier contenant des polices TrueType."
type: docs
weight: 10
url: /fr/java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

Représente un dossier contenant des polices TrueType.


La classe FolderFontSource est utilisée pour spécifier un emplacement de dossier contenant des polices TrueType.
Elle permet à l'API GroupDocs.Viewer d'accéder aux polices stockées dans le dossier spécifié à des fins de rendu de documents.


Exemple d'utilisation :

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | Initialise une nouvelle instance de |
FolderFontSource
classe.
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Détermine si deux |
FolderFontSource
objets sont identiques.
|
|  | [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Détermine si deux |
FolderFontSource
objets ne sont pas identiques.
|
|  | [getFolderPath()](#getFolderPath--) | Obtient le chemin du dossier contenant les polices TrueType. |
|
|  | [getSearchOption()](#getSearchOption--) | Obtient l'option de recherche qui spécifie s'il faut rechercher dans le dossier actuel, ou dans le dossier actuel et tous ses sous-dossiers. |
|
|  | [isRecursive()](#isRecursive--) | Vérifie si les polices seraient recherchées de manière récursive. |
|
|  | [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | Détermine si l'élément actuel |
FolderFontSource
est le même que le spécifié
FolderFontSource
objet.
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Détermine si l'élément actuel |
FolderFontSource
est le même que l'objet spécifié.
|
|  | [hashCode()](#hashCode--) | Renvoie le code de hachage pour l'élément actuel |
FolderFontSource
objet.
|
|  | [toString()](#toString--) | Renvoie une chaîne qui représente l'objet actuel. |
|
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


Initialise une nouvelle instance de
FolderFontSource
classe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | folderPath | java.lang.String | Chemin du dossier contenant les polices TrueType. |
|
|  | searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | Spécifie s'il faut rechercher dans le dossier actuel, ou dans le dossier actuel et tous les sous-dossiers. |
|

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


Détermine si deux
FolderFontSource
objets sont identiques.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | L'objet  FolderFontSource  de gauche. |
|
|  | right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | L'objet  FolderFontSource  de droite. |
|

**Returns:**
booléen -  true  si les deux objets  FolderFontSource  sont identiques ; sinon,  false .

### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


Détermine si deux
FolderFontSource
objets ne sont pas identiques.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | L'objet  FolderFontSource  de gauche. |
|
|  | right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | L'objet  FolderFontSource  de droite. |
|

**Returns:**
booléen -  true  si les deux objets  FolderFontSource  ne sont pas identiques ; sinon,  false .

### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


Obtient le chemin du dossier contenant les polices TrueType.


**Returns:**
java.lang.String - le chemin du dossier contenant les polices TrueType.

### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


Obtient l'option de recherche qui spécifie s'il faut rechercher dans le dossier actuel, ou dans le dossier actuel et tous ses sous-dossiers.


**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.

### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


Vérifie si les polices seraient recherchées de manière récursive.


**Returns:**
booléen -  true  si les polices sont recherchées de façon récursive,  false  sinon.

### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public boolean equals(FolderFontSource other)
```


Détermine si l'élément actuel
FolderFontSource
est le même que le spécifié
FolderFontSource
objet.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | L'objet à comparer avec l'objet  FolderFontSource  actuel. |
|

**Returns:**
booléen -  true  si les deux objets  FolderFontSource  sont identiques ; sinon,  false

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Détermine si l'élément actuel
FolderFontSource
est le même que l'objet spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | o | java.lang.Object | L'objet à comparer avec l'objet  FolderFontSource  actuel. |
|

**Returns:**
booléen -  true  si le paramètre  obj  est de type  FolderFontSource  et est identique à l'objet  FolderFontSource  actuel ; sinon,  false

### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage pour l'élément actuel
FolderFontSource
objet.


**Returns:**
int - un code de hachage pour l'objet  FolderFontSource  actuel.

### toString() {#toString--}
```
public String toString()
```


Renvoie une chaîne qui représente l'objet actuel.


**Returns:**
java.lang.String - une chaîne qui représente l'objet actuel.

