---
title: "OutlookOptions"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Fournit des options pour le rendu des fichiers de données Outlook."
type: docs
weight: 20
url: /fr/java/com.groupdocs.viewer.options/outlookoptions/
---
**Inheritance:**
java.lang.Object
```
public class OutlookOptions
```

Fournit des options pour le rendu des fichiers de données Outlook.


La classe OutlookOptions encapsule divers paramètres et réglages qui peuvent être utilisés
pour contrôler le rendu des fichiers de données Outlook (tels que les fichiers PST ou OST) dans le composant GroupDocs.Viewer.


Pour plus de détails, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options).


Exemple d'utilisation :

````

 OutlookOptions options = new OutlookOptions();
 options.setAddressFilter("@gmail.com");
 options.setFolder("folderName");

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setOutlookOptions(options);

 try (Viewer viewer = new Viewer("mail.pst")) {
   viewer.view(htmlViewOptions);
   // Use the viewer object for further operations
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OutlookOptions()](#OutlookOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFolder()](#getFolder--) | Obtient le nom du dossier à rendre. |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | Définit le nom du dossier à rendre. |
|
|  | [getTextFilter()](#getTextFilter--) | Obtient les mots‑clés utilisés pour filtrer les messages. |
|
|  | [setTextFilter(String value)](#setTextFilter-java.lang.String-) | Obtient les mots‑clés utilisés pour filtrer les messages. |
|
|  | [getAddressFilter()](#getAddressFilter--) | Obtient l’adresse e‑mail utilisée pour filtrer les messages par expéditeur ou destinataire. |
|
|  | [setAddressFilter(String value)](#setAddressFilter-java.lang.String-) | Définit l’adresse e‑mail utilisée pour filtrer les messages par expéditeur ou destinataire. |
|
|  | [getMaxItemsInFolder()](#getMaxItemsInFolder--) | Obtient le nombre maximal de messages ou d'éléments pouvant être rendus à partir d'un dossier. |
|
|  | [setMaxItemsInFolder(int value)](#setMaxItemsInFolder-int-) | Définit le nombre maximal de messages ou d'éléments pouvant être rendus à partir d'un dossier. |
|
### OutlookOptions() {#OutlookOptions--}
```
public OutlookOptions()
```


### getFolder() {#getFolder--}
```
public final String getFolder()
```


Obtient le nom du dossier à rendre.
Le nom du dossier (par ex., Boîte de réception, Éléments envoyés ou Éléments supprimés) à rendre.


Lors du rendu d'un fichier de données Outlook, GroupDocs.Viewer rend les messages de tous les dossiers contenus dans le fichier (y compris les dossiers imbriqués). Utilisez cette propriété pour rendre les éléments d'un dossier spécifique.
Pour un exemple de code, voir cette [documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder).


**Returns:**
java.lang.String - le nom du dossier à rendre.

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Définit le nom du dossier à rendre.
Le nom du dossier (par ex., Boîte de réception, Éléments envoyés ou Éléments supprimés) à rendre.


Lors du rendu d'un fichier de données Outlook, GroupDocs.Viewer rend les messages de tous les dossiers contenus dans le fichier (y compris les dossiers imbriqués). Utilisez cette propriété pour rendre les éléments d'un dossier spécifique.
Pour un exemple de code, voir cette [documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le nom du dossier à rendre. |
|

### getTextFilter() {#getTextFilter--}
```
public final String getTextFilter()
```


Obtient les mots‑clés utilisés pour filtrer les messages.


Utilisez cette propriété pour rendre tous les messages contenant un texte spécifique dans l'objet ou le corps. Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Returns:**
java.lang.String - les mots-clés.

### setTextFilter(String value) {#setTextFilter-java.lang.String-}
```
public final void setTextFilter(String value)
```


Obtient les mots‑clés utilisés pour filtrer les messages.


Utilisez cette propriété pour rendre tous les messages contenant un texte spécifique dans l'objet ou le corps. Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Les mots-clés. |
|

### getAddressFilter() {#getAddressFilter--}
```
public final String getAddressFilter()
```


Obtient l’adresse e‑mail utilisée pour filtrer les messages par expéditeur ou destinataire.


Utilisez cette propriété pour rendre tous les messages contenant un texte spécifique dans l'adresse de l'expéditeur\ufffds ou du destinataire\ufffds. Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Returns:**
java.lang.String - l'adresse e-mail utilisée pour filtrer les messages.

### setAddressFilter(String value) {#setAddressFilter-java.lang.String-}
```
public final void setAddressFilter(String value)
```


Définit l’adresse e‑mail utilisée pour filtrer les messages par expéditeur ou destinataire.


Utilisez cette propriété pour rendre tous les messages contenant un texte spécifique dans l'adresse de l'expéditeur\ufffds ou du destinataire\ufffds. Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | L'adresse e-mail utilisée pour filtrer les messages. |
|

### getMaxItemsInFolder() {#getMaxItemsInFolder--}
```
public final int getMaxItemsInFolder()
```


Obtient le nombre maximal de messages ou d'éléments pouvant être rendus à partir d'un dossier.


Les fichiers de données Outlook peuvent être volumineux et la récupération de tous les messages peut prendre un temps considérable.
Ce paramètre limite le nombre maximal de messages ou d'éléments (tels que contacts et tâches) qui sont rendus.
La valeur par défaut est 50. Définissez la valeur à 0 pour rendre tous les messages.
Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render).


**Returns:**
int - le nombre maximal de messages ou d'éléments pouvant être rendus à partir d'un dossier.

### setMaxItemsInFolder(int value) {#setMaxItemsInFolder-int-}
```
public final void setMaxItemsInFolder(int value)
```


Définit le nombre maximal de messages ou d'éléments pouvant être rendus à partir d'un dossier.


Les fichiers de données Outlook peuvent être volumineux et la récupération de tous les messages peut prendre un temps considérable.
Ce paramètre limite le nombre maximal de messages ou d'éléments (tels que contacts et tâches) qui sont rendus.
La valeur par défaut est 50. Définissez la valeur à 0 pour rendre tous les messages.
Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | Le nombre maximal de messages ou d'éléments pouvant être rendus à partir d'un dossier. |
|

