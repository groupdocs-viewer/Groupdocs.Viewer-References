---
title: "PdfOptions"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Fournit des options pour le rendu des documents PDF."
type: docs
weight: 22
url: /fr/nodejs-java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

Fournit des options pour le rendu des documents PDF.

La classe PdfOptions encapsule divers paramètres et réglages qui peuvent être utilisés pour contrôler le rendu des documents PDF dans le composant GroupDocs.Viewer. Pour plus de détails, voir la [documentation][].

Exemple d'utilisation :

```

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
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Initialise une nouvelle instance de la classe PdfOptions. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isDisableCopyProtection()](#isDisableCopyProtection--) | Désactive la protection contre la copie de contenu lors du rendu en HTML. |
| [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | Désactive la protection contre la copie de contenu lors du rendu en HTML. |
| [isRenderTextAsImage()](#isRenderTextAsImage--) | Détermine si le texte provenant de la source est rendu sous forme d'image en HTML. |
| [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Définit si le texte provenant de la source est rendu sous forme d'image en HTML. |
| [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Vérifie si le regroupement de caractères est désactivé afin de maintenir une précision maximale lors du positionnement des caractères pendant le rendu de la page. |
| [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Définit l'option de désactiver le regroupement de caractères, garantissant une précision maximale lors du positionnement des caractères pendant le rendu de la page. |
| [isEnableLayeredRendering()](#isEnableLayeredRendering--) | Vérifie si le rendu du texte et des graphiques doit suivre l'ordre Z dans le document PDF original lors du rendu en HTML. |
| [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | Active ou désactive le rendu du texte et des graphiques selon l'ordre Z dans le document PDF original lors du rendu en HTML. |
| [isEnableFontHinting()](#isEnableFontHinting--) | Détermine si le lissage des polices est activé. |
| [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Active le lissage des polices. |
| [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Active le rendu des pages avec la même taille en pixels que la taille de la page dans le document PDF source. |
| [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Active le rendu des pages avec la même taille en pixels que la taille de la page dans le document PDF source. |
| [getImageQuality()](#getImageQuality--) | Récupère la qualité d'image de sortie pour les ressources d'image lors du rendu en HTML. |
| [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | Définit la qualité d'image de sortie pour les ressources d'image lors du rendu en HTML. |
| [isFixedLayout()](#isFixedLayout--) | Le PDF est un format fixe, de sorte que tous les éléments ont une place précise sur une page. |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | Le PDF est un format fixe, de sorte que tous les éléments ont une place précise sur une page. |
| [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Activez cette option pour encapsuler chaque image dans le document HTML de sortie dans une balise SVG afin d'améliorer la qualité de sortie. |
| [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Activez cette option pour encapsuler chaque image dans le document HTML de sortie dans une balise SVG afin d'améliorer la qualité de sortie. |
| [isFixLinkIssue()](#isFixLinkIssue--) | Essaie de corriger le problème lorsque le contenu complet d'une page HTML est un lien. |
| [setFixLinkIssue(boolean fixLinkIssue)](#setFixLinkIssue-boolean-) | Essaie de corriger le problème lorsque le contenu complet d'une page HTML est un lien. |
| [isAnalyzeFonts()](#isAnalyzeFonts--) | Remplace les polices si nécessaire pour garantir que tous les caractères du texte puissent être affichés. |
| [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | Remplace les polices si nécessaire pour garantir que tous les caractères du texte puissent être affichés. |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Désactive toutes les restrictions de licence pour toutes les polices dans le document XPS/OXPS actuel. |
| [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Définissez le drapeau pour désactiver toutes les restrictions de licence pour toutes les polices dans le document XPS/OXPS actuel. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Initialise une nouvelle instance de la classe PdfOptions.

### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


Désactive la protection contre la copie de contenu lors du rendu en HTML.

Lors du rendu de fichiers PDF protégés contre la copie de texte et d'images vers HTML, GroupDocs.Viewer ajoute un attribut HTML 'inert' à la balise BODY du HTML. La valeur par défaut de cette option est  false .

Pour un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


Désactive la protection contre la copie de contenu lors du rendu en HTML.

Lors du rendu de fichiers PDF protégés contre la copie de texte et d'images vers HTML, GroupDocs.Viewer ajoute un attribut HTML 'inert' à la balise BODY du HTML. La valeur par défaut de cette option est  false .

Pour un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Détermine si le texte provenant de la source est rendu sous forme d'image en HTML.

Lorsque cette option est définie sur  true , le texte est rendu sous forme d'image dans le HTML de sortie. Activez cette option pour rendre le texte non sélectionnable ou pour corriger le rendu des caractères et faire ressembler le HTML au PDF. Cette option est prise en charge lors du rendu en HTML.

***Note:** The default value is  false .*

**Returns:**
booléen -  true  si le texte est rendu sous forme d'image en HTML,  false  sinon.
### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Définit si le texte provenant de la source est rendu sous forme d'image en HTML.

Lorsque cette option est définie sur  true , le texte est rendu sous forme d'image dans le HTML de sortie. Activez cette option pour rendre le texte non sélectionnable ou pour corriger le rendu des caractères et faire ressembler le HTML au PDF. Cette option est prise en charge lors du rendu en HTML.

***Note:** The default value is  false .*

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| renderTextAsImage | boolean | true  pour rendre le texte sous forme d'image en HTML,  false  sinon. |

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Vérifie si le regroupement de caractères est désactivé afin de maintenir une précision maximale lors du positionnement des caractères lors du rendu de la page. Lorsque cette option est activée, les caractères sont rendus sans aucun regroupement, ce qui garantit une précision maximale.

***Note:** By default, character grouping is enabled.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Returns:**
booléen -  true  si le regroupement de caractères est désactivé,  false  sinon.
### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Définit l'option pour désactiver le regroupement de caractères, assurant une précision maximale lors du positionnement des caractères lors du rendu de la page. Lorsque cette option est activée en définissant la valeur sur  true , le regroupement de caractères est désactivé, ce qui garantit une précision maximale.

***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | true  pour désactiver le regroupement de caractères,  false  pour l'activer. |

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Vérifie si le rendu du texte et des graphiques doit suivre l'ordre Z dans le document PDF original lors du rendu en HTML. Lorsque cette option est activée en renvoyant  true , le texte et les graphiques sont rendus selon leur ordre Z dans le document PDF original.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Returns:**
booléen -  true  si le rendu en couches est activé,  false  sinon.
### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


Active ou désactive le rendu du texte et des graphiques selon l'ordre Z dans le document PDF original lors du rendu en HTML.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | true  pour activer le rendu en couches,  false  pour le désactiver. |

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Détermine si le lissage des polices est activé. Le lissage des polices ajuste l'affichage d'une police vectorielle. Cette option n'est prise en charge que pour les polices TrueType (TTF) lorsqu'elles sont utilisées dans le document source.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Returns:**
booléen -  true  si le lissage des polices est activé,  false  sinon.
### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Active le lissage des polices. Le lissage des polices ajuste l'affichage d'une police vectorielle et n'est pris en charge que pour les polices TrueType (TTF) lorsqu'elles sont utilisées dans le document source.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | true  pour activer le lissage des polices,  false  pour le désactiver. |

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Active le rendu des pages avec la même taille en pixels que la taille de la page dans le document PDF source.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Returns:**
booléen -  true  si l'option est activée,  false  sinon.
### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Active le rendu des pages avec la même taille en pixels que la taille de la page dans le document PDF source.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| renderOriginalPageSize | boolean | true  pour activer le rendu avec la taille de page originale,  false  sinon. |

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


Récupère la qualité d'image de sortie pour les ressources image lors du rendu en HTML. La valeur par défaut est Low.

Lorsque cette option est définie sur true, GroupDocs.Viewer rend le texte sous forme d'image dans la sortie HTML. Cela rend le texte non sélectionnable et améliore le rendu des caractères, assurant une apparence similaire à un PDF en HTML. La valeur par défaut est false. Cette option est disponible pour le rendu en HTML. Pour un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.
### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


Définit la qualité d'image de sortie pour les ressources image lors du rendu en HTML. La valeur par défaut est Low.

Lorsque cette option est définie sur true, GroupDocs.Viewer rend le texte sous forme d'image dans la sortie HTML. Cela rend le texte non sélectionnable et améliore le rendu des caractères, assurant une apparence similaire à un PDF en HTML. La valeur par défaut est false. Cette option est disponible pour le rendu en HTML. Pour un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | La qualité d'image de sortie pour les ressources d'image lors du rendu en HTML. |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


Le PDF est un format fixe, donc tous les éléments ont une place spécifique sur une page. Pour garantir que le HTML de sortie ressemble au PDF source, les documents sont rendus en HTML avec une mise en page fixe par défaut. Lors du rendu avec une mise en page fixe, le HTML de sortie a une taille fixe, de sorte que les éléments restent au même endroit quel que soit la taille de la fenêtre. Pour rendre le HTML avec une mise en page fluide, définissez cette propriété sur false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Exemple d'utilisation :

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Returns:**
booléen - true si c'est une mise en page fixe
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


Le PDF est un format fixe, donc tous les éléments ont une place spécifique sur une page. Pour garantir que le HTML de sortie ressemble au PDF source, les documents sont rendus en HTML avec une mise en page fixe par défaut. Lors du rendu avec une mise en page fixe, le HTML de sortie a une taille fixe, de sorte que les éléments restent au même endroit quel que soit la taille de la fenêtre. Pour rendre le HTML avec une mise en page fluide, définissez cette propriété sur false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Exemple d'utilisation :

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fixedLayout | boolean | true si c'est une mise en page fixe |

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Activez cette option pour encapsuler chaque image dans le document HTML de sortie dans une balise SVG afin d'améliorer la qualité de sortie.

Cette option est prise en charge lors du rendu des [formats PDF et de mise en page][] en HTML avec des ressources intégrées et externes.

Par défaut, lors du rendu vers des fichiers PDF et de mise en page, toutes les images sont rendues en une seule image PNG. L'image PNG rendue est utilisée comme arrière-plan du document HTML de sortie.

En savoir plus :

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Returns:**
booléen -  true  si les images sont encapsulées dans SVG,  false  sinon.
### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Activez cette option pour encapsuler chaque image dans le document HTML de sortie dans une balise SVG afin d'améliorer la qualité de sortie.

Cette option est prise en charge lors du rendu des [formats PDF et de mise en page][] en HTML avec des ressources intégrées et externes.

Par défaut, lors du rendu vers des fichiers PDF et de mise en page, toutes les images sont rendues en une seule image PNG. L'image PNG rendue est utilisée comme arrière-plan du document HTML de sortie.

En savoir plus :

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| wrapImagesInSvg | boolean | true  si les images doivent être encapsulées dans SVG,  false  sinon. |

### isFixLinkIssue() {#isFixLinkIssue--}
```
public boolean isFixLinkIssue()
```


Essaie de corriger le problème lorsque le contenu complet d'une page HTML est un lien. Fonctionne uniquement lorsque le format d'entrée est PDF et le format de sortie est HTML (avec des ressources intégrées ou externes). Désactivé par défaut (false). Activez-le uniquement si vous savez ce que vous faites et pourquoi. L'activation de cette option augmente le temps de traitement du document.

**Returns:**
boolean
### setFixLinkIssue(boolean fixLinkIssue) {#setFixLinkIssue-boolean-}
```
public void setFixLinkIssue(boolean fixLinkIssue)
```


Essaie de corriger le problème lorsque le contenu complet d'une page HTML est un lien. Fonctionne uniquement lorsque le format d'entrée est PDF et le format de sortie est HTML (avec des ressources intégrées ou externes). Désactivé par défaut (false). Activez-le uniquement si vous savez ce que vous faites et pourquoi. L'activation de cette option augmente le temps de traitement du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fixLinkIssue | boolean | true si le problème doit être corrigé, false sinon. |

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
| analyzeFonts | boolean | true si les polices doivent être affichées, false sinon. |

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Désactive toutes les restrictions de licence pour toutes les polices dans le document XPS/OXPS actuel.

De nombreuses opérations avec les polices ne peuvent pas être exécutées si ces opérations sont interdites par la licence de la police. Par exemple, certaines polices ne peuvent pas être incorporées dans un document PDF si les règles de licence désactivent l'incorporation de cette police. Soyez prudent lors de l'utilisation de ce drapeau. Lorsqu'il est activé, cela signifie que la personne qui l'active assume l'entière responsabilité de toute violation éventuelle de licence ou de loi. Elle le fait à ses propres risques. Il est fortement recommandé d'utiliser ce drapeau uniquement lorsque vous êtes pleinement convaincu de ne pas enfreindre le droit d'auteur. Désactivé par défaut. Pour un exemple de code, consultez la [documentation][].

Exemple d'utilisation :

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


Définissez le drapeau pour désactiver toutes les restrictions de licence pour toutes les polices dans le document XPS/OXPS actuel.

De nombreuses opérations avec les polices ne peuvent pas être exécutées si ces opérations sont interdites par la licence de la police. Par exemple, certaines polices ne peuvent pas être incorporées dans un document PDF si les règles de licence désactivent l'incorporation de cette police. Soyez prudent lors de l'utilisation de ce drapeau. Lorsqu'il est activé, cela signifie que la personne qui l'active assume l'entière responsabilité de toute violation éventuelle de licence ou de loi. Elle le fait à ses propres risques. Il est fortement recommandé d'utiliser ce drapeau uniquement lorsque vous êtes pleinement convaincu de ne pas enfreindre le droit d'auteur. Désactivé par défaut. Pour un exemple de code, consultez la [documentation][].

Exemple d'utilisation :

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

