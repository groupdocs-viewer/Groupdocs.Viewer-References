---
title: "PdfOptimizationOptions"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Utilisez cette classe pour spécifier les options d'optimisation PDF à appliquer au fichier PDF de sortie."
type: docs
weight: 21
url: /fr/java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

Utilisez cette classe pour spécifier les options d'optimisation PDF à appliquer au fichier PDF de sortie.


Ces options d'optimisation sont prises en charge pour tous les formats de fichiers d'entrée qui sont pris en charge pour l'exportation vers PDF.
Pour plus de détails et des exemples de code, consultez cette [page](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) et ses sous‑pages.


Exemple d'utilisation :

````

 try (Viewer viewer = new Viewer("sample.docx")) {
     PdfViewOptions viewOptions = new PdfViewOptions();
     viewOptions.setPdfOptimizationOptions(new PdfOptimizationOptions());
     viewOptions.getPdfOptimizationOptions().setLinearize(true);
     viewOptions.getPdfOptimizationOptions().setRemoveAnnotations(true);
     viewOptions.getPdfOptimizationOptions().setRemoveFormFields(true);
     viewOptions.getPdfOptimizationOptions().setConvertToGrayScale(true);
     viewOptions.getPdfOptimizationOptions().setSubsetFonts(true);
     viewOptions.getPdfOptimizationOptions().setCompressImages(true);
     viewOptions.getPdfOptimizationOptions().setImageQuality(50);
     viewOptions.getPdfOptimizationOptions().setResizeImages(true);
     viewOptions.getPdfOptimizationOptions().setMaxResolution(50);
     viewOptions.getPdfOptimizationOptions().setRemovePrivateInfo(true);
     viewOptions.getPdfOptimizationOptions().setUnembedFonts(true);
     viewOptions.getPdfOptimizationOptions().setLinkDuplicateStreams(true);
     viewOptions.getPdfOptimizationOptions().setAllowReusePageContent(true);

     viewer.view(viewOptions);
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Définit les valeurs par défaut de l'option MaxResolution à 300 et de l'option ImageQuality à 100. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isLinearize()](#isLinearize--) | Active l'optimisation du fichier PDF de sortie pour la visualisation en ligne avec un navigateur web. |
|
|  | [setLinearize(boolean linearize)](#setLinearize-boolean-) | Définit si le PDF de sortie doit être optimisé pour la navigation en ligne avec un navigateur web. |
|
|  | [isRemoveAnnotations()](#isRemoveAnnotations--) | Les annotations peuvent être supprimées lorsqu'elles sont inutiles. |
|
|  | [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | Définit si les annotations inutiles doivent être supprimées du PDF. |
|
|  | [isRemoveFormFields()](#isRemoveFormFields--) | Si le document PDF contient des AcroForms, nous pouvons essayer de réduire la taille du fichier en aplatissant les champs de formulaire. |
|
|  | [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | Définit si les champs de formulaire doivent être supprimés du PDF. |
|
|  | [isConvertToGrayScale()](#isConvertToGrayScale--) | Le fichier PDF est composé de texte, d'images, de pièces jointes, d'annotations, de graphiques et d'autres objets. |
|
|  | [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | Définit si le PDF doit être converti en niveaux de gris. |
|
|  | [isSubsetFonts()](#isSubsetFonts--) | Chaque police utilisée pour afficher le texte sur la page contient un ensemble de glyphes pour les caractères de la police. |
|
|  | [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | Définit si les polices du PDF doivent être sous‑ensemble. |
|
|  | [isCompressImages()](#isCompressImages--) | Si le fichier PDF source contient des images, envisagez de compresser les images et de définir leur qualité. |
|
|  | [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | Définit si les images du PDF doivent être compressées. |
|
|  | [getImageQuality()](#getImageQuality--) | Si le fichier PDF source contient des images, envisagez de compresser les images et de définir leur qualité. |
|
|  | [setImageQuality(int imageQuality)](#setImageQuality-int-) | Définit la qualité d'image pour la compression des images dans le PDF. |
|
|  | [isResizeImages()](#isResizeImages--) | Peut être utilisé avec l'option CompressImages pour redimensionner les images à une résolution plus basse. |
|
|  | [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | Définit s'il faut redimensionner les images dans le PDF. |
|
|  | [getMaxResolution()](#getMaxResolution--) | Peut être utilisé avec l'option CompressImages pour redimensionner les images à une résolution plus basse. |
|
|  | [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | Définit la résolution maximale pour le redimensionnement des images dans le PDF. |
|
|  | [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Optimise les bordures et les polices des feuilles de calcul Excel pour réduire la taille du fichier de sortie. |
|
|  | [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | Définit s'il faut optimiser les feuilles de calcul dans le PDF. |
|
|  | [isRemovePrivateInfo()](#isRemovePrivateInfo--) | Supprime les informations privées (informations de pièce de page) si la valeur est vraie. |
|
|  | [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | Définit s'il faut supprimer les informations privées du PDF. |
|
|  | [isUnembedFonts()](#isUnembedFonts--) | Si le document utilise des polices incorporées, cela signifie que toutes les données de police sont placées dans le document. |
|
|  | [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | Définit s'il faut désincorporer les polices incorporées dans le PDF. |
|
|  | [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | Parfois, un document contient plusieurs flux de ressources identiques (par exemple des images). |
|
|  | [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | Définit s'il faut lier les flux dupliqués dans le PDF. |
|
|  | [isAllowReusePageContent()](#isAllowReusePageContent--) | Si cette propriété est définie sur vrai, le contenu de la page sera réutilisé lors de l'optimisation du document pour des pages identiques. |
|
|  | [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | Définit s'il faut autoriser la réutilisation du contenu des pages dans le PDF. |
|
|  | [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | Parfois, un document contient des flux de ressources inutilisés. |
|
|  | [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | Définit s'il faut supprimer les flux inutilisés du PDF. |
|
|  | [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | Un document PDF contient parfois des objets PDF qui ne sont pas référencés |
par aucun autre objet du document.
|
|  | [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | Définit s'il faut supprimer les objets inutilisés du PDF. |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Définit les valeurs par défaut de l'option MaxResolution à 300 et de l'option ImageQuality à 100.


Pour plus de détails et des exemples de code, consultez cette [page](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) et ses sous‑pages.


### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


Active l'optimisation du fichier PDF de sortie pour la visualisation en ligne avec un navigateur web.


Pour un exemple de code, voir cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/).


**Returns:**
booléen -  vrai  si le PDF de sortie est optimisé pour la navigation en ligne,  faux  sinon.

### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


Définit si le PDF de sortie doit être optimisé pour la navigation en ligne avec un navigateur web.


Pour un exemple de code, voir cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | linéariser | boolean | vrai  pour optimiser le PDF de sortie pour la navigation en ligne,  faux  sinon. |
|

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


Les annotations peuvent être supprimées lorsqu'elles sont inutiles. Lorsqu'elles sont nécessaires mais ne nécessitent pas d'édition supplémentaire, elles peuvent être aplaties. Cela réduira la taille du fichier.


***Note:** The default value is 
false
.*
Pour un exemple de code, voir cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/).


**Returns:**
booléen -  vrai  si les annotations sont supprimées,  faux  sinon.

### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


Définit si les annotations inutiles doivent être supprimées du PDF.


***Note:** The default value is 
false
.*
Pour un exemple de code, voir cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | removeAnnotations | boolean | true  pour supprimer les annotations inutiles,  false  sinon. |
|

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


Si le document PDF contient des AcroForms, nous pouvons essayer de réduire la taille du fichier en aplatissant les champs de formulaire.


***Note:** The default value is 
false
.*
Pour un exemple de code, voir cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/).


**Returns:**
booléen -  true  si les champs de formulaire sont supprimés,  false  sinon.

### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


Définit si les champs de formulaire doivent être supprimés du PDF.


***Note:** The default value is 
false
.*
Pour un exemple de code, voir cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | removeFormFields | boolean | true  pour supprimer les champs de formulaire,  false  sinon. |
|

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


Le fichier PDF est composé de texte, d'images, de pièces jointes, d'annotations, de graphiques et d'autres objets.
Il se peut que vous ayez besoin de convertir un PDF de l'espace colorimétrique RVB en niveaux de gris afin qu'il soit plus rapide à imprimer.
De plus, lorsque le fichier est converti en niveaux de gris, la taille du document est également réduite, mais cette modification peut entraîner une perte de qualité du document.
Actuellement, cette fonctionnalité est prise en charge par la fonction Pre‑Flight d'Adobe Acrobat.


***Note:** The default value is 
false
.*
Pour un exemple de code, voir cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/).


**Returns:**
booléen -  true  si le PDF est converti en niveaux de gris,  false  sinon.

### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


Définit si le PDF doit être converti en niveaux de gris.


***Note:** The default value is 
false
.*
Pour un exemple de code, voir cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | convertToGrayScale | boolean | true  pour convertir le PDF en niveaux de gris,  false  sinon. |
|

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


Chaque police utilisée pour afficher le texte sur la page contient un ensemble de glyphes pour les caractères de la police.
La spécification PDF prend en charge le "font subset", c’est‑à‑dire une police contenant uniquement les glyphes utilisés.
Cela peut poser des problèmes lors de la mise à jour du texte (car les glyphes nécessaires sont probablement absents de la police), mais pour un document qui n’est pas destiné à être modifié, cela permet de réduire la taille.


***Note:** The default value is 
false
.*
Si le fichier utilise des polices incorporées, il contient toutes les données de la police. GroupDocs.Viewer peut sous‑ensembliser les polices incorporées afin de réduire la taille du fichier. Pour un exemple de code, voir cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/).


**Returns:**
booléen -  true  si les polices sont sous‑ensemblisées,  false  sinon.

### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


Définit si les polices du PDF doivent être sous‑ensemble.


***Note:** The default value is 
false
.*
Si le fichier utilise des polices incorporées, il contient toutes les données de la police. GroupDocs.Viewer peut sous‑ensembliser les polices incorporées afin de réduire la taille du fichier. Pour un exemple de code, voir cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | subsetFonts | boolean | true  pour sous‑ensembliser les polices,  false  sinon. |
|

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


Si le fichier PDF source contient des images, envisagez de compresser les images et de définir leur qualité.
Pour activer la compression d’image, définissez cette option sur true. Toutes les images d’un document seront recompressées.
La compression est définie par la propriété ImageQuality, qui représente la valeur de la qualité en pourcentage.
100 % correspond à une qualité inchangée. Pour diminuer la qualité de l’image, définissez la propriété ImageQuality à une valeur inférieure à 100.


***Note:** The default value is 
false
.*
Utilisez cette option pour autoriser d’autres options de compression : #setImageQuality(int).setImageQuality(int) et . Pour un exemple de code, voir cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Returns:**
booléen -  true  si les images sont compressées,  false  sinon.

### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


Définit si les images du PDF doivent être compressées.


***Note:** The default value is 
false
.*
Utilisez cette option pour autoriser d’autres options de compression : #setImageQuality(int).setImageQuality(int) et . Pour un exemple de code, voir cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | compressImages | boolean | true  pour compresser les images,  false  sinon. |
|

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


Si le fichier PDF source contient des images, envisagez de compresser les images et de définir leur qualité. Pour activer la compression d'images, réglez l'option CompressImages sur true. Toutes les images d'un document seront recompressées. La compression est définie par la propriété ImageQuality, qui correspond à la valeur de la qualité en pourcentage. 100 % correspond à une qualité inchangée. Pour diminuer la qualité de l'image, réglez l'option CompressImages sur true et la propriété ImageQuality à moins de 100.

<br />


***Note:** The default value is 
100
.*
Pour modifier la qualité de l'image, définissez d'abord la propriété #setCompressImages(boolean).setCompressImages(boolean) sur true. Pour un exemple de code, consultez cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Returns:**
int - la qualité de l'image (valeur entre 1 et 100).

### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


Définit la qualité d'image pour la compression des images dans le PDF.


***Note:** The default value is 
100
.*
Pour modifier la qualité de l'image, définissez d'abord la propriété #setCompressImages(boolean).setCompressImages(boolean) sur true. Pour un exemple de code, consultez cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | imageQuality | int | la qualité de l'image (valeur entre 1 et 100). |
|

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


Peut être utilisé avec l'option CompressImages pour redimensionner les images à une résolution plus basse.
Dans ce cas, nous devons définir CompressImage sur true, ResizeImages sur true et MaxResolution à la valeur appropriée.


***Note:** The default value is 
false
.*
Pour autoriser cette option, réglez la propriété sur true. Cette option permet de définir la propriété. Pour un exemple de code, consultez cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Returns:**
boolean -  true  si les images sont redimensionnées,  false  sinon.

### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


Définit s'il faut redimensionner les images dans le PDF.


***Note:** The default value is 
false
.*
Pour autoriser cette option, réglez la propriété sur true. Cette option permet de définir la propriété. Pour un exemple de code, consultez cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | resizeImages | boolean | true  pour redimensionner les images,  false  sinon. |
|

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


Peut être utilisé avec l'option CompressImages pour redimensionner les images à une résolution inférieure. Dans ce cas, nous devons définir CompressImage sur true, ResizeImages sur true et MaxResolution à la valeur appropriée.


***Note:** The default value is 
300
.*
Pour autoriser cette option, réglez les propriétés #setCompressImages(boolean).setCompressImages(boolean) et #setMaxResolution(int).setMaxResolution(int) sur true.
Pour un exemple de code, consultez cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Returns:**
int - la résolution maximale pour les images.

### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


Définit la résolution maximale pour le redimensionnement des images dans le PDF.


***Note:** The default value is 
300
.*
Pour autoriser cette option, réglez les propriétés #setCompressImages(boolean).setCompressImages(boolean) et #setMaxResolution(int).setMaxResolution(int) sur true.
Pour un exemple de code, consultez cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | maxResolution | int | la résolution maximale pour les images. |
|

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Optimise les bordures et les polices des feuilles de calcul Excel pour réduire la taille du fichier de sortie.


*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*


***Note:** The default value is 
false
.*
Pour un exemple de code, consultez cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/).


**Returns:**
boolean -  true  si les feuilles de calcul sont optimisées,  false  sinon.

### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


Définit s'il faut optimiser les feuilles de calcul dans le PDF.


Pour un exemple de code, consultez cette [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | optimizeSpreadsheets | boolean | true  pour optimiser les feuilles de calcul,  false  sinon. |
|

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


Supprime les informations privées (informations de pièce de page) si la valeur est vraie.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  si les informations privées sont supprimées,  false  sinon.

### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


Définit s'il faut supprimer les informations privées du PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | removePrivateInfo | boolean | true  pour supprimer les informations privées,  false  sinon. |
|

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


Si le document utilise des polices incorporées, cela signifie que toutes les données de police sont placées dans le document.
L'avantage est que le document est visible quel que soit le fait que la police soit installée sur la machine de l'utilisateur ou non. Mais l'intégration des polices augmente la taille du document.
La méthode de désintégration des polices supprime toutes les polices intégrées. Cela réduit la taille du document mais le document peut devenir illisible si la police correcte n'est pas installée.


***Note:** The default value is 
false
.*


**Returns:**
booléen -  true  si les polices intégrées sont désintégrées,  false  sinon.

### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


Définit s'il faut désincorporer les polices incorporées dans le PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | unembedFonts | boolean | true  pour désintégrer les polices intégrées,  false  sinon. |
|

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


Parfois, un document contient plusieurs flux de ressources identiques (par exemple des images).
Cela peut se produire, par exemple, lorsqu'un document est concaténé avec lui-même.
Le document de sortie contient deux copies indépendantes du même flux de ressources.
Nous analysons tous les flux de ressources et les comparons. Si les flux sont dupliqués, ils sont fusionnés, c’est‑à‑dire qu’il ne reste qu’une seule copie, les références sont modifiées en conséquence et les copies de l’objet sont supprimées.
Parfois, cela réduit la taille du document.


***Note:** The default value is 
false
.*


**Returns:**
booléen -  true  si les flux dupliqués sont liés,  false  sinon.

### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


Définit s'il faut lier les flux dupliqués dans le PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | linkDuplicateStreams | boolean | true  pour lier les flux dupliqués,  false  sinon. |
|

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


Si cette propriété est définie sur vrai, le contenu de la page sera réutilisé lors de l'optimisation du document pour des pages identiques.


***Note:** The default value is 
false
.*


**Returns:**
booléen -  true  si le contenu de la page est réutilisé,  false  sinon.

### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


Définit s'il faut autoriser la réutilisation du contenu des pages dans le PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | allowReusePageContent | boolean | true  pour autoriser la réutilisation du contenu de la page,  false  sinon. |
|

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


Parfois, un document contient des flux de ressources inutilisés.
Ces flux ne sont pas \\u201cobjets inutilisés\\u201d car ils sont référencés depuis le dictionnaire de ressources d’une page.
Cela peut se produire dans les cas où une image a été supprimée de la page mais pas des ressources de la page.
De plus, cette situation se produit souvent lorsque des pages sont extraites du document et que les pages du document ont des ressources \\u201ccommunes\\u201d,
c’est‑à‑dire le même objet Resources. Le contenu des pages est analysé afin de déterminer si un flux de ressources
est utilisé ou non. Les flux inutilisés sont supprimés. Parfois, cela réduit la taille du document.


***Note:** The default value is 
false
.*


**Returns:**
booléen -  true  si les flux inutilisés sont supprimés,  false  sinon.

### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


Définit s'il faut supprimer les flux inutilisés du PDF.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | removeUnusedStreams | boolean | true  pour supprimer les flux inutilisés,  false  sinon. |
|

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


Un document PDF contient parfois des objets PDF qui ne sont pas référencés
à partir de tout autre objet du document. Cela peut se produire, par exemple,
lorsqu'une page est supprimée de l'arborescence des pages du document mais que l'objet page lui‑même n'est pas supprimé.
Supprimer ces objets ne rend pas le document invalide mais le réduit plutôt.


***Note:** The default value is 
false
.*


**Returns:**
booléen -  true  si les objets inutilisés sont supprimés,  false  sinon.

### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


Définit s'il faut supprimer les objets inutilisés du PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | removeUnusedObjects | boolean | true  pour supprimer les objets inutilisés,  false  sinon. |
|

