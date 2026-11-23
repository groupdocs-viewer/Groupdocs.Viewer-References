---
title: "PdfOptions"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Fournit des options pour le rendu des documents PDF."
type: docs
weight: 22
url: /fr/java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

Fournit des options pour le rendu des documents PDF.


La classe PdfOptions encapsule divers paramètres et réglages qui peuvent être utilisés
pour contrôler le rendu des documents PDF dans le composant GroupDocs.Viewer.
Pour plus de détails, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


Exemple d'utilisation :

````

 PdfOptions options = new PdfOptions();
 options.setDisableCharsGrouping(true);
 options.setRenderTextAsImage(true);
 options.setEnableFontHinting(true);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setPdfOptions(options);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | Initialise une nouvelle instance de |
PdfOptions
classe.
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isDisableCopyProtection()](#isDisableCopyProtection--) | Désactive la protection contre la copie de contenu lors du rendu en HTML. |
|
|  | [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | Désactive la protection contre la copie de contenu lors du rendu en HTML. |
|
|  | [isRenderTextAsImage()](#isRenderTextAsImage--) | Détermine si le texte provenant de la source est rendu sous forme d'image en HTML. |
|
|  | [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Définit si le texte provenant de la source est rendu sous forme d'image en HTML. |
|
|  | [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Vérifie si le regroupement de caractères est désactivé afin de maintenir une précision maximale lors du positionnement des caractères lors du rendu de la page. |
|
|  | [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Définit l'option de désactiver le regroupement de caractères, garantissant une précision maximale lors du positionnement des caractères lors du rendu de la page. |
|
|  | [isEnableLayeredRendering()](#isEnableLayeredRendering--) | Vérifie si le rendu du texte et des graphiques doit suivre l'ordre Z dans le document PDF original lors du rendu en HTML. |
|
|  | [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | Active ou désactive le rendu du texte et des graphiques selon l'ordre Z dans le document PDF original lors du rendu en HTML. |
|
|  | [isEnableFontHinting()](#isEnableFontHinting--) | Détermine si l'optimisation des polices est activée. |
|
|  | [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Active l'optimisation des polices. |
|
|  | [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Active le rendu des pages avec la même taille en pixels que la taille de la page dans le document PDF source. |
|
|  | [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Active le rendu des pages avec la même taille en pixels que la taille de la page dans le document PDF source. |
|
|  | [getImageQuality()](#getImageQuality--) | Récupère la qualité d'image de sortie pour les ressources image lors du rendu en HTML. |
|
|  | [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | Définit la qualité d'image de sortie pour les ressources image lors du rendu en HTML. |
|
|  | [isFixedLayout()](#isFixedLayout--) | Le PDF est un format fixe, de sorte que tous les éléments ont une place précise sur une page. |
|
|  | [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | Le PDF est un format fixe, de sorte que tous les éléments ont une place précise sur une page. |
|
|  | [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Activez cette option pour encapsuler chaque image du document HTML de sortie dans une balise SVG afin d'améliorer la qualité du rendu. |
|
|  | [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Activez cette option pour encapsuler chaque image du document HTML de sortie dans une balise SVG afin d'améliorer la qualité du rendu. |
|
|  | [isAnalyzeFonts()](#isAnalyzeFonts--) | Remplace les polices si nécessaire pour garantir que tous les caractères du texte puissent être affichés. |
|
|  | [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | Remplace les polices si nécessaire pour garantir que tous les caractères du texte puissent être affichés. |
|
|  | [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Désactive toutes les restrictions de licence pour toutes les polices du document XPS/OXPS actuel. |
|
|  | [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Définissez le drapeau pour désactiver toutes les restrictions de licence pour toutes les polices du document XPS/OXPS actuel. |
|
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Initialise une nouvelle instance de
PdfOptions
classe.


### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


Désactive la protection contre la copie de contenu lors du rendu en HTML.


Lors du rendu de fichiers PDF protégés contre la copie de texte et d'images vers HTML, GroupDocs.Viewer ajoute un attribut HTML « inert » à la balise BODY du HTML.
La valeur par défaut de cette option est
false
.


Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


Désactive la protection contre la copie de contenu lors du rendu en HTML.


Lors du rendu de fichiers PDF protégés contre la copie de texte et d'images vers HTML, GroupDocs.Viewer ajoute un attribut HTML « inert » à la balise BODY du HTML.
La valeur par défaut de cette option est
false
.


Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Détermine si le texte provenant de la source est rendu sous forme d'image en HTML.


Lorsque cette option est définie sur
true
, le texte est rendu sous forme d'image dans le HTML de sortie.
Activez cette option pour rendre le texte non sélectionnable ou pour corriger le rendu des caractères et faire en sorte que le HTML ressemble au PDF.
Cette option est prise en charge lors du rendu en HTML.


***Note:** The default value is 
false
.*


**Returns:**
booléen -  true  si le texte est rendu sous forme d'image en HTML,  false  sinon.

### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Définit si le texte provenant de la source est rendu sous forme d'image en HTML.


Lorsque cette option est définie sur
true
, le texte est rendu sous forme d'image dans le HTML de sortie.
Activez cette option pour rendre le texte non sélectionnable ou pour corriger le rendu des caractères et faire en sorte que le HTML ressemble au PDF.
Cette option est prise en charge lors du rendu en HTML.


***Note:** The default value is 
false
.*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | renderTextAsImage | boolean | true  pour rendre le texte sous forme d'image en HTML,  false  sinon. |
|

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Vérifie si le regroupement de caractères est désactivé afin de maintenir une précision maximale lors du positionnement des caractères lors du rendu de la page.
Lorsque cette option est activée, les caractères sont rendus sans aucun regroupement, ce qui garantit une précision maximale.


***Note:** By default, character grouping is enabled.*
Lors de la conversion de fichiers PDF, GroupDocs.Viewer regroupe les caractères individuels en mots pour améliorer les performances de rendu. Si votre document contient des hiéroglyphes ou des symboles spéciaux, vous pouvez souhaiter interdire le regroupement des caractères afin d'obtenir une mise en page plus précise. La valeur par défaut est false.
Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Returns:**
booléen -  true  si le regroupement des caractères est désactivé,  false  sinon.

### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Définit l'option de désactiver le regroupement de caractères, garantissant une précision maximale lors du positionnement des caractères lors du rendu de la page.
Lorsque cette option est activée en définissant la valeur à
true
, le regroupement des caractères est désactivé, ce qui assure une précision maximale.


***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.*
Lors de la conversion de fichiers PDF, GroupDocs.Viewer regroupe les caractères individuels en mots pour améliorer les performances de rendu. Si votre document contient des hiéroglyphes ou des symboles spéciaux, vous pouvez souhaiter interdire le regroupement des caractères afin d'obtenir une mise en page plus précise. La valeur par défaut est false.
Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | true  pour désactiver le regroupement des caractères,  false  pour l'activer. |
|

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Vérifie si le rendu du texte et des graphiques doit suivre l'ordre Z dans le document PDF original lors du rendu en HTML.
Lorsque cette option est activée en retournant
true
, le texte et les graphiques sont rendus selon leur ordre Z dans le document PDF original.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
Par défaut, GroupDocs.Veiewer rend le texte et les graphiques comme une seule couche en HTML. Cette option vous permet d'organiser les objets dans le même ordre que dans le fichier source. La valeur par défaut est false.
Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Returns:**
booléen -  true  si le rendu en couches est activé,  false  sinon.

### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


Active ou désactive le rendu du texte et des graphiques selon l'ordre Z dans le document PDF original lors du rendu en HTML.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
Par défaut, GroupDocs.Veiewer rend le texte et les graphiques comme une seule couche en HTML. Cette option vous permet d'organiser les objets dans le même ordre que dans le fichier source. La valeur par défaut est false.
Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | true  pour activer le rendu en couches,  false  pour le désactiver. |
|

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Détermine si le lissage des polices est activé. Le lissage des polices ajuste l'affichage d'une police vectorielle.
Cette option n'est prise en charge que pour les polices TrueType (TTF) lorsqu'elles sont utilisées dans le document source.


***Note:** This option is supported when rendering into PNG or JPG formats.*
Le lissage des polices ajuste la façon dont une police vectorielle est affichée. Applicable uniquement aux polices TTF utilisées dans le document source. Cette option est disponible pour le rendu aux formats PNG ou JPG. La valeur par défaut est false.
Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Returns:**
booléen -  true  si le lissage des polices est activé,  false  sinon.

### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Active le lissage des polices. Le lissage des polices ajuste l'affichage d'une police vectorielle et n'est pris en charge que pour les polices TrueType (TTF) lorsqu'elles sont utilisées dans le document source.


***Note:** This option is supported when rendering into PNG or JPG formats.*
Le lissage des polices ajuste la façon dont une police vectorielle est affichée. Applicable uniquement aux polices TTF utilisées dans le document source. Cette option est disponible pour le rendu aux formats PNG ou JPG. La valeur par défaut est false.
Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | true  pour activer le lissage des polices,  false  pour le désactiver. |
|

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Active le rendu des pages avec la même taille en pixels que la taille de la page dans le document PDF source.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
Par défaut, GroupDocs.Viewer calcule la taille des pages d'image de sortie pour une meilleure qualité de rendu. Activez cette option pour garantir que les pages de sortie ont la même taille que la taille de page du document PDF source (en pixels). La valeur par défaut est false.
Cette option est disponible pour le rendu aux formats PNG ou JPG.
Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Returns:**
booléen -  true  si l'option est activée,  false  sinon.

### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Active le rendu des pages avec la même taille en pixels que la taille de la page dans le document PDF source.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
Par défaut, GroupDocs.Viewer calcule la taille des pages d'image de sortie pour une meilleure qualité de rendu. Activez cette option pour garantir que les pages de sortie ont la même taille que la taille de page du document PDF source (en pixels). La valeur par défaut est false.
Cette option est disponible pour le rendu aux formats PNG ou JPG.
Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | renderOriginalPageSize | boolean | true  pour activer le rendu avec la taille de page d'origine,  false  sinon. |
|

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


Récupère la qualité d'image de sortie pour les ressources image lors du rendu en HTML. La valeur par défaut est Low.


Lorsque cette option est définie sur true, GroupDocs.Viewer rend le texte sous forme d'image dans la sortie HTML. Cela rend le texte non sélectionnable et améliore le rendu des caractères, garantissant une apparence similaire à un PDF en HTML. La valeur par défaut est false.
Cette option est disponible pour le rendu en HTML.
Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.

### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


Définit la qualité d'image de sortie pour les ressources image lors du rendu en HTML. La valeur par défaut est Low.


Lorsque cette option est définie sur true, GroupDocs.Viewer rend le texte sous forme d'image dans la sortie HTML. Cela rend le texte non sélectionnable et améliore le rendu des caractères, garantissant une apparence similaire à un PDF en HTML. La valeur par défaut est false.
Cette option est disponible pour le rendu en HTML.
Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | La qualité d'image de sortie pour les ressources image lors du rendu en HTML. |
|

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


Le PDF est un format fixe, de sorte que tous les éléments ont une place précise sur une page.
Pour garantir que le HTML de sortie ressemble au PDF source, les documents sont rendus en HTML avec une mise en page fixe par défaut.
Lors du rendu avec une mise en page fixe, le HTML de sortie a une taille fixe afin que les éléments restent au même endroit quel que soit la taille de la fenêtre.
Pour rendre en HTML avec une mise en page fluide, définissez cette propriété sur false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
Les documents PDF et EPUB sont initialement rendus en HTML avec une mise en page fixe afin de conserver l'apparence du document source. Cette mise en page fixe signifie que tous les éléments HTML ont des positions précises au sein d'un conteneur de taille définie. Redimensionner la fenêtre du navigateur n'affecte pas la position et la taille des éléments dans le document.
Cette option n'est disponible que lors du rendu en HTML. La valeur par défaut est true. Pour rendre avec une mise en page fluide, définissez cette propriété sur false.


Exemple d'utilisation :

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Returns:**
boolean - true si c'est une mise en page fixe

### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


Le PDF est un format fixe, de sorte que tous les éléments ont une place précise sur une page.
Pour garantir que le HTML de sortie ressemble au PDF source, les documents sont rendus en HTML avec une mise en page fixe par défaut.
Lors du rendu avec une mise en page fixe, le HTML de sortie a une taille fixe afin que les éléments restent au même endroit quel que soit la taille de la fenêtre.
Pour rendre en HTML avec une mise en page fluide, définissez cette propriété sur false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
Les documents PDF et EPUB sont initialement rendus en HTML avec une mise en page fixe afin de conserver l'apparence du document source. Cette mise en page fixe signifie que tous les éléments HTML ont des positions précises au sein d'un conteneur de taille définie. Redimensionner la fenêtre du navigateur n'affecte pas la position et la taille des éléments dans le document.
Cette option n'est disponible que lors du rendu en HTML. La valeur par défaut est true. Pour rendre avec une mise en page fluide, définissez cette propriété sur false.


Exemple d'utilisation :

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fixedLayout | boolean | true si c'est une mise en page fixe |
|

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Activez cette option pour encapsuler chaque image du document HTML de sortie dans une balise SVG afin d'améliorer la qualité du rendu.


Cette option est prise en charge lors du rendu des [formats de fichiers PDF et mise en page](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) en HTML avec des ressources intégrées et externes.


Par défaut, lors du rendu vers des fichiers PDF et de mise en page, toutes les images sont rendues en une seule image PNG. L'image PNG rendue est utilisée comme arrière-plan du document HTML de sortie.


En savoir plus :

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Returns:**
boolean -  true  si les images sont encapsulées dans SVG,  false  sinon.

### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Activez cette option pour encapsuler chaque image du document HTML de sortie dans une balise SVG afin d'améliorer la qualité du rendu.


Cette option est prise en charge lors du rendu des [formats de fichiers PDF et mise en page](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) en HTML avec des ressources intégrées et externes.


Par défaut, lors du rendu vers des fichiers PDF et de mise en page, toutes les images sont rendues en une seule image PNG. L'image PNG rendue est utilisée comme arrière-plan du document HTML de sortie.


En savoir plus :

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | wrapImagesInSvg | boolean | true  si les images doivent être encapsulées dans SVG,  false  sinon. |
|

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


Remplace les polices si nécessaire pour garantir que tous les caractères du texte puissent être affichés.


**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


Remplace les polices si nécessaire pour garantir que tous les caractères du texte puissent être affichés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | analyzeFonts | boolean | true si les polices doivent être affichées, false sinon |
|

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Désactive toutes les restrictions de licence pour toutes les polices du document XPS/OXPS actuel.


De nombreuses opérations avec la police ne peuvent pas être exécutées si ces opérations sont interdites par la licence de cette police.
Par exemple, certaines polices ne peuvent pas être incorporées dans un document PDF si les règles de licence désactivent l'incorporation de cette police.
Soyez prudent lors de l'utilisation de ce drapeau. Lorsqu'il est activé, cela signifie que la personne qui active ce drapeau assume toute la responsabilité
pour d'éventuelles violations de licence ou de loi sur eux-mêmes. Ainsi, ils le font à leurs propres risques. Il est fortement recommandé d'utiliser
ce drapeau uniquement lorsque vous êtes pleinement convaincu de ne pas enfreindre la loi sur le droit d'auteur. Par défaut, false.
Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


Exemple d'utilisation :

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


Définissez le drapeau pour désactiver toutes les restrictions de licence pour toutes les polices du document XPS/OXPS actuel.


De nombreuses opérations avec la police ne peuvent pas être exécutées si ces opérations sont interdites par la licence de cette police.
Par exemple, certaines polices ne peuvent pas être incorporées dans un document PDF si les règles de licence désactivent l'incorporation de cette police.
Soyez prudent lors de l'utilisation de ce drapeau. Lorsqu'il est activé, cela signifie que la personne qui active ce drapeau assume toute la responsabilité
pour d'éventuelles violations de licence ou de loi sur eux-mêmes. Ainsi, ils le font à leurs propres risques. Il est fortement recommandé d'utiliser
ce drapeau uniquement lorsque vous êtes pleinement convaincu de ne pas enfreindre la loi sur le droit d'auteur. Par défaut, false.
Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


Exemple d'utilisation :

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

