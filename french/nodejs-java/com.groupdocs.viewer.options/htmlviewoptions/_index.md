---
title: "HtmlViewOptions"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Fournit des options pour le rendu des documents au format HTML."
type: docs
weight: 16
url: /fr/nodejs-java/com.groupdocs.viewer.options/htmlviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class HtmlViewOptions extends ViewOptions
```

Fournit des options pour le rendu des documents au format HTML.

La classe HtmlViewOptions encapsule des paramètres et réglages supplémentaires pouvant être utilisés pour contrôler le rendu des documents au format HTML dans le composant GroupDocs.Viewer.

Pour plus de détails, consultez le [topic][] et ses enfants.

Exemple d'utilisation :

```

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.setExcludeFonts(true);
 options.setFontsToExclude(Arrays.asList("font-name"));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```


[topic]: https://docs.groupdocs.com/viewer/java/rendering-to-html/
## Champs

| Champ | Description |
| --- | --- |
| [CREATE_PAGE_STREAM](#CREATE-PAGE-STREAM) |  |
| [FILE_PATH_FORMAT](#FILE-PATH-FORMAT) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isRenderResponsive()](#isRenderResponsive--) | Détermine si le rendu réactif est activé. |
| [setRenderResponsive(boolean value)](#setRenderResponsive-boolean-) | Définit si le rendu réactif est activé. |
| [isMinify()](#isMinify--) | Vérifie si la minification du contenu HTML et des ressources HTML est activée. |
| [setMinify(boolean value)](#setMinify-boolean-) | Définit si la minification du contenu HTML et des ressources HTML est activée. |
| [isRenderToSinglePage()](#isRenderToSinglePage--) | Active le rendu d'un document complet en un seul fichier HTML. |
| [setRenderToSinglePage(boolean renderSinglePage)](#setRenderToSinglePage-boolean-) | Active le rendu d'un document complet en un seul fichier HTML. |
| [getImageMaxWidth()](#getImageMaxWidth--) | Renvoie la largeur maximale d'une image de sortie en pixels. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Définit la largeur maximale d'une image de sortie en pixels. |
| [getImageMaxHeight()](#getImageMaxHeight--) | Obtient la hauteur maximale d'une image de sortie en pixels. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Définit la hauteur maximale d'une image de sortie en pixels. |
| [getImageWidth()](#getImageWidth--) | Obtient la largeur de l'image de sortie en pixels. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | Définit la largeur de l'image de sortie en pixels. |
| [getImageHeight()](#getImageHeight--) | Obtient la hauteur de l'image de sortie en pixels lors de la conversion d'une image unique en HTML. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | Définit la hauteur de l'image de sortie en pixels lors de la conversion d'une image unique en HTML. |
| [isForPrinting()](#isForPrinting--) | Vérifie si le HTML de sortie doit être optimisé pour l'impression. |
| [setForPrinting(boolean value)](#setForPrinting-boolean-) | Définit si le HTML de sortie doit être optimisé pour l'impression. |
| [isExcludeFonts()](#isExcludeFonts--) | Détermine s'il faut exclure les polices du document HTML. |
| [setExcludeFonts(boolean value)](#setExcludeFonts-boolean-) | Définit s'il faut exclure les polices du document HTML. |
| [getFontsToExclude()](#getFontsToExclude--) | Récupère la liste des noms de polices à exclure du document HTML. |
| [setFontsToExclude(List<String> value)](#setFontsToExclude-java.util.List-java.lang.String--) | Définit la liste des noms de polices à exclure du document HTML. |
| [isRemoveJavaScript()](#isRemoveJavaScript--) | Permet de supprimer le code source JavaScript des liens dans les documents HTML résultants, lors du rendu de documents d'entrée contenant des scripts. |
| [setRemoveJavaScript(boolean value)](#setRemoveJavaScript-boolean-) | Définit l'autorisation de supprimer le code source JavaScript des liens dans les documents HTML résultants, lors du rendu de documents d'entrée contenant des scripts. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Récupère le rappel utilisé pour estimer la progression de l'enregistrement d'un document Words ou Email. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Définit le rappel utilisé pour estimer la progression de l'enregistrement d'un document Words ou Email. |
| [forEmbeddedResources(CreatePageStream createPageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initialise une nouvelle instance de la classe  HtmlViewOptions  pour le rendu en HTML avec des ressources intégrées. |
| [forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initialise une nouvelle instance de la classe  HtmlViewOptions  pour le rendu en HTML avec des ressources intégrées. |
| [forEmbeddedResources(PageStreamFactory pageStreamFactory)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initialise une nouvelle instance de la classe  HtmlViewOptions  pour le rendu en HTML avec des ressources intégrées. |
| [forEmbeddedResources()](#forEmbeddedResources--) | Initialise une nouvelle instance de la classe  HtmlViewOptions . |
| [forEmbeddedResources(String filePathFormat)](#forEmbeddedResources-java.lang.String-) | Initialise une nouvelle instance de la classe  HtmlViewOptions . |
| [forEmbeddedResources(Path filePathFormat)](#forEmbeddedResources-java.nio.file.Path-) | Initialise une nouvelle instance de la classe  HtmlViewOptions . |
| [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-) | Initialise une nouvelle instance de la classe  HtmlViewOptions  pour le rendu en HTML avec des ressources externes. |
| [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-) | Initialise une nouvelle instance de la classe  HtmlViewOptions  pour le rendu en HTML avec des ressources externes. |
| [forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)](#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-) | Initialise une nouvelle instance de la classe  HtmlViewOptions  pour le rendu en HTML avec des ressources externes. |
| [forExternalResources()](#forExternalResources--) | Initialise une nouvelle instance de la classe  HtmlViewOptions . |
| [forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)](#forExternalResources-java.lang.String-java.lang.String-java.lang.String-) | Initialise une nouvelle instance de la classe  HtmlViewOptions . |
### CREATE_PAGE_STREAM {#CREATE-PAGE-STREAM}
```
public static final String CREATE_PAGE_STREAM
```


### FILE_PATH_FORMAT {#FILE-PATH-FORMAT}
```
public static final String FILE_PATH_FORMAT
```


### isRenderResponsive() {#isRenderResponsive--}
```
public final boolean isRenderResponsive()
```


Détermine si le rendu réactif est activé. Les pages web réactives s'affichent correctement sur des appareils avec différentes tailles d'écran.

Le design réactif vise à faire en sorte que les pages web s'affichent correctement sur une variété d'appareils. Pour rendre avec une mise en page réactive, définissez cette propriété sur true. Pour un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/

**Returns:**
booléen -  true  si le rendu réactif est activé,  false  sinon.
### setRenderResponsive(boolean value) {#setRenderResponsive-boolean-}
```
public final void setRenderResponsive(boolean value)
```


Définit si le rendu réactif est activé. Les pages web réactives s'affichent correctement sur des appareils avec différentes tailles d'écran.

Le design réactif vise à faire en sorte que les pages web s'affichent correctement sur une variété d'appareils. Pour rendre avec une mise en page réactive, définissez cette propriété sur true. Pour un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | true  pour activer le rendu réactif,  false  pour le désactiver. |

### isMinify() {#isMinify--}
```
public final boolean isMinify()
```


Vérifie si la minification du contenu HTML et des ressources HTML est activée.

La compression du contenu de sortie (HTML, CSS et SVG) est l'une des façons d'optimiser le fichier HTML. Pour ce faire, définissez cette propriété sur true. Pour un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/minify-html/

**Returns:**
booléen -  true  si la minification est activée,  false  sinon.
### setMinify(boolean value) {#setMinify-boolean-}
```
public final void setMinify(boolean value)
```


Définit si la minification du contenu HTML et des ressources HTML est activée.

La compression du contenu de sortie (HTML, CSS et SVG) est l'une des façons d'optimiser le fichier HTML. Pour ce faire, définissez cette propriété sur true. Pour un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/minify-html/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | true  pour activer la minification,  false  pour désactiver. |

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public boolean isRenderToSinglePage()
```


Active le rendu d'un document complet en un seul fichier HTML.

**See the following topics for more information:**

 *  [Render archives as HTML, PDF, and image files][Render archives as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render web documents as PDF, PNG, and JPEG files][Render web documents as PDF_ PNG_ and JPEG files]

**Example:**

```
try (final Viewer viewer = new Viewer("invoice.docx")) {
   HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
   viewOptions.setRenderToSinglePage(true);

   viewer.view(viewOptions);
 }
```


[Render archives as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file
[Render web documents as PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources

**Returns:**
boolean
### setRenderToSinglePage(boolean renderSinglePage) {#setRenderToSinglePage-boolean-}
```
public void setRenderToSinglePage(boolean renderSinglePage)
```


Active le rendu d'un document complet en un seul fichier HTML.

**See the following topics for more information:**

 *  [Render archives as HTML, PDF, and image files][Render archives as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render web documents as PDF, PNG, and JPEG files][Render web documents as PDF_ PNG_ and JPEG files]

**Example:**

```
try (final Viewer viewer = new Viewer("invoice.docx")) {
   HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
   viewOptions.setRenderToSinglePage(true);

   viewer.view(viewOptions);
 }
```


[Render archives as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file
[Render web documents as PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| renderSinglePage | boolean |  |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Renvoie la largeur maximale d'une image de sortie en pixels.

**Note:** This value is used when converting a single image to HTML. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - la largeur maximale d'une image de sortie.
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Définit la largeur maximale d'une image de sortie en pixels.

**Note:** This value is used when converting a single image to HTML. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageMaxWidth | int | La largeur maximale d'une image de sortie. |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Obtient la hauteur maximale d'une image de sortie en pixels.

**Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - la hauteur maximale d'une image de sortie.
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Définit la hauteur maximale d'une image de sortie en pixels.

**Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageMaxHeight | int | La hauteur maximale d'une image de sortie. |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Obtient la largeur de l'image de sortie en pixels.

***Note:** This value is applicable only when converting a single image to HTML.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - la largeur de l'image de sortie.
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Définit la largeur de l'image de sortie en pixels.

***Note:** This value is applicable only when converting a single image to HTML.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageWidth | int | La largeur de l'image de sortie. |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Obtient la hauteur de l'image de sortie en pixels lors de la conversion d'une image unique en HTML.

Pour plus de détails et un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - la hauteur de l'image de sortie en pixels.
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Définit la hauteur de l'image de sortie en pixels lors de la conversion d'une image unique en HTML.

Pour plus de détails et un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageHeight | int | La hauteur de l'image de sortie en pixels. |

### isForPrinting() {#isForPrinting--}
```
public final boolean isForPrinting()
```


Vérifie si le HTML de sortie doit être optimisé pour l'impression.

Activez cette option pour convertir les pages HTML de sortie au format SVG vectoriel. Pour plus de détails et un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/

**Returns:**
booléen -  true  si le HTML de sortie doit être optimisé pour l'impression,  false  sinon.
### setForPrinting(boolean value) {#setForPrinting-boolean-}
```
public final void setForPrinting(boolean value)
```


Définit si le HTML de sortie doit être optimisé pour l'impression.

Activez cette option pour convertir les pages HTML de sortie au format SVG vectoriel. Pour plus de détails et un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | true  pour optimiser le HTML de sortie pour l'impression,  false  sinon. |

### isExcludeFonts() {#isExcludeFonts--}
```
public final boolean isExcludeFonts()
```


Détermine s'il faut exclure les polices du document HTML.

Par défaut, GroupDocs.Viewer intègre les polices utilisées dans le document dans le HTML. Pour l'empêcher, définissez cette propriété sur true. Pour plus de détails et un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Returns:**
booléen -  true  si les polices doivent être exclues,  false  sinon.
### setExcludeFonts(boolean value) {#setExcludeFonts-boolean-}
```
public final void setExcludeFonts(boolean value)
```


Définit s'il faut exclure les polices du document HTML.

Par défaut, GroupDocs.Viewer intègre les polices utilisées dans le document dans le HTML. Pour l'empêcher, définissez cette propriété sur true. Pour plus de détails et un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | true  pour exclure les polices,  false  sinon. |

### getFontsToExclude() {#getFontsToExclude--}
```
public final List<String> getFontsToExclude()
```


Récupère la liste des noms de polices à exclure du document HTML.

Cette option n'est prise en charge que pour les présentations. Inclure les polices dans le document HTML améliore la stabilité de la vue de sortie mais augmente la taille du résultat rendu. Utilisez cette option pour trouver un compromis entre stabilité et taille de sortie. Incluez les noms de polices qui sont populaires et installés sur la plupart des systèmes.

***Note:** Please note that this property is active only when the  ExcludeFonts  (\#isExcludeFonts().isExcludeFonts()/\#setExcludeFonts(boolean).setExcludeFonts(boolean)) option is disabled.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Returns:**
java.util.List<java.lang.String> - la liste des noms de polices à exclure du document HTML.
### setFontsToExclude(List<String> value) {#setFontsToExclude-java.util.List-java.lang.String--}
```
public final void setFontsToExclude(List<String> value)
```


Définit la liste des noms de polices à exclure du document HTML.

Cette option n'est prise en charge que pour les présentations. Inclure les polices dans le document HTML améliore la stabilité de la vue de sortie mais augmente la taille du résultat rendu. Utilisez cette option pour trouver un compromis entre stabilité et taille de sortie. Incluez les noms de polices qui sont populaires et installés sur la plupart des systèmes.

***Note:** Please note that this property is active only when the  ExcludeFonts  (\#isExcludeFonts().isExcludeFonts()/\#setExcludeFonts(boolean).setExcludeFonts(boolean)) option is disabled.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.List<java.lang.String> | La liste des noms de polices à exclure du document HTML. |

### isRemoveJavaScript() {#isRemoveJavaScript--}
```
public final boolean isRemoveJavaScript()
```


Permet de supprimer le code source JavaScript des liens dans les documents HTML résultants, lors du rendu de documents d'entrée contenant des scripts. Activé par défaut (true).

Pour plus de détails sur la suppression de JavaScript, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html

**Returns:**
boolean
### setRemoveJavaScript(boolean value) {#setRemoveJavaScript-boolean-}
```
public void setRemoveJavaScript(boolean value)
```


Définit l'autorisation de supprimer le code source JavaScript des liens dans les documents HTML résultants, lors du rendu de documents d'entrée contenant des scripts. Activé par défaut (true).

Pour plus de détails sur la suppression de JavaScript, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Récupère le rappel utilisé pour estimer la progression de l'enregistrement d'un document Words ou Email.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - le rappel utilisé pour estimer la progression de l'enregistrement du document.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Définit le rappel utilisé pour estimer la progression de l'enregistrement d'un document Words ou Email.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Le rappel utilisé pour estimer la progression de l'enregistrement du document. |

### forEmbeddedResources(CreatePageStream createPageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream)
```


Initialise une nouvelle instance de la classe  HtmlViewOptions  pour le rendu en HTML avec des ressources intégrées.

***Note:** The method takes a  CreatePageStream  parameter, which is a method used to instantiate a stream for writing output page data.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | La méthode qui instancie un flux utilisé pour écrire les données de la page de sortie. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initialise une nouvelle instance de la classe  HtmlViewOptions  pour le rendu en HTML avec des ressources intégrées.

Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | La méthode qui instancie un flux utilisé pour écrire les données de la page de sortie. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | La méthode qui libère le flux créé par la méthode assignée au paramètre  createPageStream  . |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources(PageStreamFactory pageStreamFactory) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public static HtmlViewOptions forEmbeddedResources(PageStreamFactory pageStreamFactory)
```


Initialise une nouvelle instance de la classe  HtmlViewOptions  pour le rendu en HTML avec des ressources intégrées.

Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | La fabrique qui implémente les méthodes de création et de libération du flux de page de sortie. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources() {#forEmbeddedResources--}
```
public static HtmlViewOptions forEmbeddedResources()
```


Initialise une nouvelle instance de la classe  HtmlViewOptions .

Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forEmbeddedResources(String filePathFormat) {#forEmbeddedResources-java.lang.String-}
```
public static HtmlViewOptions forEmbeddedResources(String filePathFormat)
```


Initialise une nouvelle instance de la classe  HtmlViewOptions .

Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | Le format du chemin de fichier, par ex., 'page\_\{0\}.html'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forEmbeddedResources(Path filePathFormat) {#forEmbeddedResources-java.nio.file.Path-}
```
public static HtmlViewOptions forEmbeddedResources(Path filePathFormat)
```


Initialise une nouvelle instance de la classe  HtmlViewOptions .

Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | Le format du chemin de fichier, par ex., 'page\_\{0\}.html'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```


Initialise une nouvelle instance de la classe  HtmlViewOptions  pour le rendu en HTML avec des ressources externes.

***Note:** This method should be used when rendering HTML with external resources, such as CSS and JavaScript files.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | La méthode qui instancie le flux utilisé pour écrire les données de la page de sortie. |
| createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | La méthode qui libère le flux créé par la méthode  createPageStream  . |
| createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | La méthode qui crée l'URL de la ressource HTML. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```


Initialise une nouvelle instance de la classe  HtmlViewOptions  pour le rendu en HTML avec des ressources externes.

Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | La méthode qui instancie le flux utilisé pour écrire les données de la page de sortie. |
| createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | La méthode qui instancie le flux utilisé pour écrire les données de la ressource HTML de sortie. |
| createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | La méthode qui crée l'URL de la ressource HTML. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | La méthode qui libère le flux créé par la méthode  createPageStream  . |
| releaseResourceStream | [ReleaseResourceStream](../../com.groupdocs.viewer.interfaces/releaseresourcestream) | La méthode qui libère le flux créé par la méthode  createResourceStream  . |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory) {#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-}
```
public static HtmlViewOptions forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)
```


Initialise une nouvelle instance de la classe  HtmlViewOptions  pour le rendu en HTML avec des ressources externes.

Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | La fabrique qui implémente les méthodes de création et de libération du flux de page de sortie. |
| resourceStreamFactory | [ResourceStreamFactory](../../com.groupdocs.viewer.interfaces/resourcestreamfactory) | La fabrique qui implémente les méthodes de création d'URL de ressources et d'instanciation/libération du flux de ressource HTML de sortie. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources() {#forExternalResources--}
```
public static HtmlViewOptions forExternalResources()
```


Initialise une nouvelle instance de la classe  HtmlViewOptions .

 *  \- with "p\_\{0\}.html" as file path format for the output HTML files;
 *  \- with "p\_\{0\}\_\{1\}" as file path format for the output HTML-resource files;
 *  \- with "p\_\{0\}\_\{1\}" as URL format for HTML-resources;

Les fichiers de sortie seront placés dans le répertoire de travail actuel de l'application. Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat) {#forExternalResources-java.lang.String-java.lang.String-java.lang.String-}
```
public static HtmlViewOptions forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)
```


Initialise une nouvelle instance de la classe  HtmlViewOptions .

Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | Le format du chemin de fichier, par ex., 'page\_\{0\}.html'. |
| resourceFilePathFormat | java.lang.String | Le format du chemin de fichier de ressource, par ex., 'page\_\{0\}/resource\_\{1\}'. |
| resourceUrlFormat | java.lang.String | Le format de l'URL de ressource, par ex., 'page\_\{0\}/resource\_\{1\}'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
