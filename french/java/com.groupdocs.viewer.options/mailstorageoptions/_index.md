---
title: "MailStorageOptions"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Fournit des options pour le rendu des fichiers de données Lotus Notes MBox de stockage de courrier."
type: docs
weight: 19
url: /fr/java/com.groupdocs.viewer.options/mailstorageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MailStorageOptions
```

Fournit des options pour le rendu des fichiers de données de stockage de courrier (Lotus Notes, MBox).


La classe MailStorageOptions encapsule divers paramètres et réglages qui peuvent être utilisés
pour contrôler le rendu des fichiers de données de stockage Mail (tels que Lotus Notes ou MBox) dans le composant GroupDocs.Viewer.


Pour plus de détails, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options).


Exemple d'utilisation :

````

 MailStorageOptions options = new MailStorageOptions();
 options.setAddressFilter("@gmail.com");
 options.setMaxItems(10);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setMailStorageOptions(options);

 try (Viewer viewer = new Viewer("mail.msg")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MailStorageOptions()](#MailStorageOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getTextFilter()](#getTextFilter--) | Obtient les mots‑clés utilisés pour filtrer les messages. |
|
|  | [setTextFilter(String textFilter)](#setTextFilter-java.lang.String-) | Définit les mots‑clés utilisés pour filtrer les messages. |
|
|  | [getAddressFilter()](#getAddressFilter--) | Obtient l’adresse e‑mail utilisée pour filtrer les messages par expéditeur ou destinataire. |
|
|  | [setAddressFilter(String addressFilter)](#setAddressFilter-java.lang.String-) | Définit l’adresse e‑mail utilisée pour filtrer les messages par expéditeur ou destinataire. |
|
|  | [getMaxItems()](#getMaxItems--) | Obtient le nombre maximal de messages ou d’éléments à rendre. |
|
|  | [setMaxItems(int maxItems)](#setMaxItems-int-) | Définit le nombre maximal de messages ou d’éléments à rendre. |
|
### MailStorageOptions() {#MailStorageOptions--}
```
public MailStorageOptions()
```


### getTextFilter() {#getTextFilter--}
```
public String getTextFilter()
```


Obtient les mots‑clés utilisés pour filtrer les messages.


Utilisez cette propriété pour rendre tous les messages contenant un texte spécifique dans l’objet ou le corps. Pour un exemple de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages).


**Returns:**
java.lang.String - les mots‑clés utilisés pour filtrer les messages.

### setTextFilter(String textFilter) {#setTextFilter-java.lang.String-}
```
public void setTextFilter(String textFilter)
```


Définit les mots‑clés utilisés pour filtrer les messages.


Utilisez cette propriété pour rendre tous les messages contenant un texte spécifique dans l’objet ou le corps. Pour un exemple de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | textFilter | java.lang.String | Les mots‑clés utilisés pour filtrer les messages. |
|

### getAddressFilter() {#getAddressFilter--}
```
public String getAddressFilter()
```


Obtient l’adresse e‑mail utilisée pour filtrer les messages par expéditeur ou destinataire.


Utilisez cette propriété pour rendre tous les messages contenant un texte spécifique dans l’adresse de l’expéditeur\\u2019s ou du destinataire\\u2019s. Pour un exemple de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages).


**Returns:**
java.lang.String - l’adresse e‑mail utilisée pour filtrer les messages.

### setAddressFilter(String addressFilter) {#setAddressFilter-java.lang.String-}
```
public void setAddressFilter(String addressFilter)
```


Définit l’adresse e‑mail utilisée pour filtrer les messages par expéditeur ou destinataire.


Utilisez cette propriété pour rendre tous les messages contenant un texte spécifique dans l’adresse de l’expéditeur\\u2019s ou du destinataire\\u2019s. Pour un exemple de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | addressFilter | java.lang.String | L’adresse e‑mail utilisée pour filtrer les messages. |
|

### getMaxItems() {#getMaxItems--}
```
public int getMaxItems()
```


Obtient le nombre maximal de messages ou d’éléments à rendre.


Les fichiers de données Lotus Notes peuvent être volumineux, et la récupération de tous les messages peut prendre un temps considérable.
Ce paramètre limite le nombre maximal de messages ou d’éléments qui sont rendus.


***Note:** The default value is 0, which means all messages will be rendered.*
Pour un exemple de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render).


**Returns:**
int - le nombre maximal de messages ou d’éléments à rendre.

### setMaxItems(int maxItems) {#setMaxItems-int-}
```
public void setMaxItems(int maxItems)
```


Définit le nombre maximal de messages ou d’éléments à rendre.


Les fichiers de données Lotus Notes peuvent être volumineux, et la récupération de tous les messages peut prendre un temps considérable.
Ce paramètre limite le nombre maximal de messages ou d’éléments qui sont rendus.


***Note:** The default value is 0, which means all messages will be rendered.*
Pour un exemple de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | maxItems | int | Le nombre maximal de messages ou d’éléments à rendre. |
|

