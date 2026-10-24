---
title: "PngViewOptions"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Fournit des options pour le rendu des documents au format PNG."
type: docs
weight: 25
url: /fr/java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

Fournit des options pour le rendu des documents au format PNG.


La classe PngViewOptions encapsule des paramètres et réglages supplémentaires qui peuvent être utilisés
pour contrôler le rendu des documents au format PNG dans le composant GroupDocs.Viewer.


Exemple d'utilisation :

````

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.*
Pour plus de détails, consultez cette [page](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/) et ses sous‑pages.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initialise une nouvelle instance de |
PngViewOptions
classe.
|
|  | [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initialise une nouvelle instance de |
PngViewOptions
classe.
|
|  | [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initialise une nouvelle instance de |
PngViewOptions
classe.
|
|  | [PngViewOptions()](#PngViewOptions--) | Initialise une nouvelle instance de |
PngViewOptions
classe.
|
|  | [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | Initialise une nouvelle instance de |
PngViewOptions
classe.
|
|  | [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | Initialise une nouvelle instance de |
PngViewOptions
classe.
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getMaxWidth()](#getMaxWidth--) | Renvoie la largeur maximale d'une image de sortie en pixels. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Définit la largeur maximale d'une image de sortie en pixels. |
|
|  | [getMaxHeight()](#getMaxHeight--) | Renvoie la hauteur maximale d'une image de sortie en pixels. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Définit la hauteur maximale d'une image de sortie en pixels. |
|
|  | [isExtractText()](#isExtractText--) | Détermine si l'extraction de texte est activée. |
|
|  | [setExtractText(boolean value)](#setExtractText-boolean-) | Active ou désactive l'extraction de texte. |
|
|  | [getWidth()](#getWidth--) | Renvoie la largeur de l'image de sortie en pixels. |
|
|  | [setWidth(int value)](#setWidth-int-) | Définit la largeur de l'image de sortie en pixels. |
|
|  | [getHeight()](#getHeight--) | Renvoie la hauteur de l'image de sortie en pixels. |
|
|  | [setHeight(int value)](#setHeight-int-) | Définit la hauteur de l'image de sortie en pixels. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Récupère le rappel (callback) pour estimer la progression de l'enregistrement d'un document. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Définit le rappel (callback) pour estimer la progression de l'enregistrement d'un document. |
|
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


Initialise une nouvelle instance de
PngViewOptions
classe.


Pour l'exemple de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | La méthode qui instancie le flux utilisé pour écrire les données de la page de sortie. |
|

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initialise une nouvelle instance de
PngViewOptions
classe.


Pour l'exemple de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | La méthode qui instancie le flux utilisé pour écrire les données de la page de sortie. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | La méthode qui libère le flux créé par la méthode assignée au paramètre createPageStream. |
|

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


Initialise une nouvelle instance de
PngViewOptions
classe.


Pour l'exemple de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | La fabrique qui implémente les méthodes de création et de libération du flux de page de sortie. |
|

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


Initialise une nouvelle instance de
PngViewOptions
classe.


Ce constructeur initialise une nouvelle instance de
PngViewOptions

avec "p_{0}.png" comme format de chemin de fichier pour les fichiers de sortie.
Les fichiers de sortie seront placés dans le répertoire de travail actuel de l'application.
Pour l'exemple de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


Initialise une nouvelle instance de
PngViewOptions
classe.


Par exemple, si le format de chemin de fichier est 'page_{0}.png', les fichiers de sortie seront
nommés 'page_1.png', 'page_2.png', etc., en fonction du numéro de page.


***Note:** It is important to note that the output files will be placed into the current working directory of the application.*
Pour l'exemple de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Le format de chemin de fichier, par ex., 'page_{0}.png'. |
|

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


Initialise une nouvelle instance de
PngViewOptions
classe.


Par exemple, si le format de chemin de fichier est 'page_{0}.png', les fichiers de sortie seront
nommés 'page_1.png', 'page_2.png', etc., en fonction du numéro de page.
Pour l'exemple de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | Le format de chemin de fichier, par ex., 'page_{0}.png'. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Renvoie la largeur maximale d'une image de sortie en pixels.


Utilisez cette propriété pour définir la largeur maximale de l'image de sortie (en pixels). Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Si vous définissez la propriété, cette propriété est ignorée.


**Returns:**
int - la largeur maximale de l'image de sortie.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Définit la largeur maximale d'une image de sortie en pixels.


Utilisez cette propriété pour définir la largeur maximale de l'image de sortie (en pixels). Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Si vous définissez la propriété, cette propriété est ignorée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | maxWidth | int | La largeur maximale de l'image de sortie. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Renvoie la hauteur maximale d'une image de sortie en pixels.


Utilisez cette propriété pour définir la hauteur maximale de l'image de sortie (en pixels). Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Si vous définissez la propriété, cette propriété est ignorée.


**Returns:**
int - la hauteur maximale de l'image de sortie.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Définit la hauteur maximale d'une image de sortie en pixels.


Utilisez cette propriété pour définir la hauteur maximale de l'image de sortie (en pixels). Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Si vous définissez la propriété, cette propriété est ignorée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | maxHeight | int | La hauteur maximale de l'image de sortie. |
|

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Détermine si l'extraction de texte est activée.


Cette option peut être utile lorsque vous souhaitez ajouter une couche de texte sélectionnable sur l'image.
Utilisez cette propriété pour obtenir le texte contenu dans un document source ainsi que ses coordonnées. Vous pouvez ensuite utiliser ces données pour ajouter un texte sélectionnable sur l'image ou implémenter une recherche de texte dans le rendu basé sur l'image.
Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/).


**Returns:**
boolean -  true  si l'extraction de texte est activée,  false  sinon.

### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Active ou désactive l'extraction de texte.


Cette option peut être utile lorsque vous souhaitez ajouter une couche de texte sélectionnable sur l'image.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | true  pour activer l'extraction de texte,  false  pour la désactiver. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Renvoie la largeur de l'image de sortie en pixels.


Utilisez cette propriété pour définir la largeur de l'image de sortie (en pixels). Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Si vous définissez cette propriété, la propriété est ignorée.


**Returns:**
int - la largeur de l'image de sortie.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Définit la largeur de l'image de sortie en pixels.


Utilisez cette propriété pour définir la largeur de l'image de sortie (en pixels). Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Si vous définissez cette propriété, la propriété est ignorée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La largeur de l'image de sortie. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Renvoie la hauteur de l'image de sortie en pixels.


Utilisez cette propriété pour définir la hauteur de l'image de sortie (en pixels). Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Si vous définissez cette propriété, la propriété est ignorée.


**Returns:**
int - la hauteur de l'image de sortie.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Définit la hauteur de l'image de sortie en pixels.


Utilisez cette propriété pour définir la hauteur de l'image de sortie (en pixels). Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Si vous définissez cette propriété, la propriété est ignorée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La hauteur de l'image de sortie. |
|

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Récupère le rappel (callback) pour estimer la progression de l'enregistrement d'un document.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - le rappel pour estimer la progression de l'enregistrement du document.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Définit le rappel (callback) pour estimer la progression de l'enregistrement d'un document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Le rappel pour estimer la progression de l'enregistrement du document. |
|

