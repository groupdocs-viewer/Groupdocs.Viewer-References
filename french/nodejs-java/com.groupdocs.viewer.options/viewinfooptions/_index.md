---
title: "ViewInfoOptions"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Fournit des options utilisées pour récupérer des informations sur la vue."
type: docs
weight: 34
url: /fr/nodejs-java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

Fournit des options utilisées pour récupérer des informations sur la vue.

La classe ViewInfoOptions encapsule des paramètres et réglages supplémentaires qui peuvent être utilisés pour récupérer des informations sur une vue dans le composant GroupDocs.Viewer.

Exemple d'utilisation :

```

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*
## Méthodes

| Méthode | Description |
| --- | --- |
| [isExtractText()](#isExtractText--) | Indique si l'extraction de texte est activée. |
| [setExtractText(boolean extractText)](#setExtractText-boolean-) | Définit le drapeau indiquant si l'extraction de texte est activée. |
| [getMaxWidth()](#getMaxWidth--) | Renvoie la largeur maximale de l'image de sortie pour le rendu en PNG/JPG. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Définit la largeur maximale d'une image de sortie (en pixels, uniquement pour le rendu en PNG/JPG). |
| [getMaxHeight()](#getMaxHeight--) | Renvoie la hauteur maximale de l'image de sortie pour le rendu en PNG/JPG. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Définit la hauteur maximale d'une image de sortie (en pixels, uniquement pour le rendu en PNG/JPG). |
| [getWidth()](#getWidth--) | La largeur de l'image de sortie (en pixels, uniquement pour le rendu en PNG/JPG). |
| [setWidth(int width)](#setWidth-int-) | La largeur de l'image de sortie (en pixels, uniquement pour le rendu en PNG/JPG). |
| [getHeight()](#getHeight--) | La hauteur de l'image de sortie (en pixels, uniquement pour le rendu en PNG/JPG). |
| [setHeight(int height)](#setHeight-int-) | La hauteur de l'image de sortie (en pixels, uniquement pour le rendu en PNG/JPG). |
| [forHtmlView()](#forHtmlView--) | Initialise une nouvelle instance de la classe  ViewInfoOptions  pour récupérer des informations sur la vue lors du rendu en HTML. |
| [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | Initialise une nouvelle instance de la classe  ViewInfoOptions  pour récupérer des informations sur la vue lors du rendu en HTML. |
| [forJpgView()](#forJpgView--) | Initialise une nouvelle instance de la classe  ViewInfoOptions  pour récupérer des informations sur la vue lors du rendu en JPG. |
| [forJpgView(boolean extractText)](#forJpgView-boolean-) | Initialise une nouvelle instance de la classe  ViewInfoOptions  pour récupérer des informations sur la vue lors du rendu en JPG. |
| [forPngView()](#forPngView--) | Initialise une nouvelle instance de la classe  ViewInfoOptions  pour récupérer des informations sur la vue lors du rendu en PNG. |
| [forPngView(boolean extractText)](#forPngView-boolean-) | Initialise une nouvelle instance de la classe  ViewInfoOptions  pour récupérer des informations sur la vue lors du rendu en PNG. |
| [forPdfView()](#forPdfView--) | Initialise une nouvelle instance de la classe ViewInfoOptions pour récupérer des informations sur la vue lors du rendu en PDF. |
| [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | Initialise une nouvelle instance de la classe  ViewInfoOptions  basée sur l'objet [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions). |
| [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | Initialise une nouvelle instance de la classe  ViewInfoOptions  basée sur l'objet [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions). |
| [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | Initialise une nouvelle instance de la classe  ViewInfoOptions  basée sur l'objet [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions). |
| [fromPdfViewOptions(PdfViewOptions options)](#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-) | Initialise une nouvelle instance de la classe [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) basée sur un objet PdfViewOptions. |
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


Indique si l'extraction de texte est activée.

Utilisez cette propriété pour obtenir le texte contenu dans un document source ainsi que ses coordonnées. Vous pouvez ensuite utiliser ces données pour ajouter un texte sélectionnable sur l'image ou pour implémenter une recherche de texte dans le rendu basé sur l'image. Pour un exemple de code, consultez la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/

**Returns:**
booléen - True si l'extraction de texte est activée, false sinon.
### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


Définit le drapeau indiquant si l'extraction de texte est activée.

Utilisez cette propriété pour obtenir le texte contenu dans un document source ainsi que ses coordonnées. Vous pouvez ensuite utiliser ces données pour ajouter un texte sélectionnable sur l'image ou pour implémenter une recherche de texte dans le rendu basé sur l'image. Pour un exemple de code, consultez la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| extractText | boolean | True pour activer l'extraction de texte, false pour la désactiver. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Renvoie la largeur maximale de l'image de sortie pour le rendu en PNG/JPG.

Utilisez cette propriété pour définir la largeur maximale de l'image de sortie (en pixels). Pour l'exemple de code, voir la [documentation][]. Si vous définissez la propriété, cette propriété est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - la largeur maximale de l'image de sortie.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Définit la largeur maximale d'une image de sortie (en pixels, uniquement pour le rendu en PNG/JPG).

Utilisez cette propriété pour définir la largeur maximale de l'image de sortie (en pixels). Pour l'exemple de code, voir la [documentation][]. Si vous définissez la propriété, cette propriété est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| maxWidth | int | La largeur maximale de l'image de sortie. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Renvoie la hauteur maximale de l'image de sortie pour le rendu en PNG/JPG.

Utilisez cette propriété pour définir la hauteur maximale de l'image de sortie (en pixels). Pour l'exemple de code, voir la [documentation][]. Si vous définissez la propriété, cette propriété est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - la hauteur maximale de l'image de sortie.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Définit la hauteur maximale d'une image de sortie (en pixels, uniquement pour le rendu en PNG/JPG).

Utilisez cette propriété pour définir la hauteur maximale de l'image de sortie (en pixels). Pour l'exemple de code, voir la [documentation][]. Si vous définissez la propriété, cette propriété est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| maxHeight | int | La hauteur maximale de l'image de sortie. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


La largeur de l'image de sortie (en pixels, uniquement pour le rendu en PNG/JPG).

Utilisez cette propriété pour définir la largeur de l'image de sortie (en pixels). Pour l'exemple de code, voir la [documentation][]. Si vous définissez cette propriété, la propriété  est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Returns:**
int - la largeur de l'image.
### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


La largeur de l'image de sortie (en pixels, uniquement pour le rendu en PNG/JPG).

Utilisez cette propriété pour définir la largeur de l'image de sortie (en pixels). Pour l'exemple de code, voir la [documentation][]. Si vous définissez cette propriété, la propriété  est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur de l'image. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


La hauteur de l'image de sortie (en pixels, uniquement pour le rendu en PNG/JPG).

Utilisez cette propriété pour définir la hauteur de l'image de sortie (en pixels). Pour l'exemple de code, voir la [documentation][]. Si vous définissez cette propriété, la propriété  est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Returns:**
int - la hauteur de l'image.
### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


La hauteur de l'image de sortie (en pixels, uniquement pour le rendu en PNG/JPG).

Utilisez cette propriété pour définir la hauteur de l'image de sortie (en pixels). Pour l'exemple de code, voir la [documentation][]. Si vous définissez cette propriété, la propriété  est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| height | int | La hauteur de l'image. |

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


Initialise une nouvelle instance de la classe  ViewInfoOptions  pour récupérer des informations sur la vue lors du rendu en HTML.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.
### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


Initialise une nouvelle instance de la classe  ViewInfoOptions  pour récupérer des informations sur la vue lors du rendu en HTML.

***Note:** By default, HTML content will be rendered on multiple pages.*

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| renderSinglePage | boolean | Permet au contenu HTML d'être rendu sur une seule page. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


Initialise une nouvelle instance de la classe  ViewInfoOptions  pour récupérer des informations sur la vue lors du rendu en JPG.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


Initialise une nouvelle instance de la classe  ViewInfoOptions  pour récupérer des informations sur la vue lors du rendu en JPG.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| extractText | boolean | Active l'extraction de texte. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


Initialise une nouvelle instance de la classe  ViewInfoOptions  pour récupérer des informations sur la vue lors du rendu en PNG.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


Initialise une nouvelle instance de la classe  ViewInfoOptions  pour récupérer des informations sur la vue lors du rendu en PNG.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| extractText | boolean | Active l'extraction de texte. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPdfView() {#forPdfView--}
```
public static ViewInfoOptions forPdfView()
```


Initialise une nouvelle instance de la classe ViewInfoOptions pour récupérer des informations sur la vue lors du rendu en PDF.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.
### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


Initialise une nouvelle instance de la classe  ViewInfoOptions  basée sur l'objet [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | Les options de vue HTML. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


Initialise une nouvelle instance de la classe  ViewInfoOptions  basée sur l'objet [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | Les options de vue PNG. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


Initialise une nouvelle instance de la classe  ViewInfoOptions  basée sur l'objet [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | Les options de vue JPG. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromPdfViewOptions(PdfViewOptions options) {#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-}
```
public static ViewInfoOptions fromPdfViewOptions(PdfViewOptions options)
```


Initialise une nouvelle instance de la classe [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) basée sur un objet PdfViewOptions.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) | Les options de vue PDF. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the ViewInfoOptions class.
