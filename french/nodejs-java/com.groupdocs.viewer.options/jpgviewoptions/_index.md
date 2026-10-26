---
title: "JpgViewOptions"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Fournit des options pour le rendu des documents au format JPG."
type: docs
weight: 17
url: /fr/nodejs-java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

Fournit des options pour le rendu des documents au format JPG.

La classe JpgViewOptions encapsule des paramètres et réglages supplémentaires qui peuvent être utilisés pour contrôler le rendu des documents au format JPG dans le composant GroupDocs.Viewer.

Exemple d'utilisation :

```

 JpgViewOptions options = new JpgViewOptions();
 options.setMaxWidth(1920);
 options.setMaxHeight(1080);
 options.setQuality((byte) 96);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```

***Note:** The JpgViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output JPG images.*
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initialise une nouvelle instance de la classe  JpgViewOptions . |
| [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initialise une nouvelle instance de la classe  JpgViewOptions . |
| [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initialise une nouvelle instance de la classe  JpgViewOptions . |
| [JpgViewOptions()](#JpgViewOptions--) | Initialise une nouvelle instance de  JpgViewOptions  avec "p\_\{0\}.jpg" comme format de chemin de fichier pour les fichiers de sortie. |
| [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | Initialise une nouvelle instance de la classe  JpgViewOptions . |
| [JpgViewOptions(Path filePathFormat)](#JpgViewOptions-java.nio.file.Path-) | Initialise une nouvelle instance de la classe  JpgViewOptions . |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | Obtient la largeur maximale d'une image de sortie en pixels. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Définit la largeur maximale d'une image de sortie en pixels. |
| [getMaxHeight()](#getMaxHeight--) | Obtient la hauteur maximale d'une image de sortie en pixels. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Définit la hauteur maximale d'une image de sortie en pixels. |
| [getQuality()](#getQuality--) | Obtient la qualité de l'image de sortie. |
| [setQuality(byte value)](#setQuality-byte-) | Définit la qualité de l'image de sortie. |
| [isExtractText()](#isExtractText--) | Active l'extraction de texte. |
| [setExtractText(boolean value)](#setExtractText-boolean-) | Active ou désactive l'extraction de texte. |
| [getWidth()](#getWidth--) | Obtient la largeur de l'image de sortie en pixels. |
| [setWidth(int value)](#setWidth-int-) | Définit la largeur de l'image de sortie en pixels. |
| [getHeight()](#getHeight--) | Obtient la hauteur de l'image de sortie en pixels. |
| [setHeight(int value)](#setHeight-int-) | Définit la hauteur de l'image de sortie en pixels. |
| [getPageStreamFactory()](#getPageStreamFactory--) | Obtient la fabrique qui implémente les méthodes de création et de libération du flux de page de sortie. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Obtient le rappel pour estimer la progression de l'enregistrement d'un document Words ou Email. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Définit le rappel pour estimer la progression de l'enregistrement d'un document Words ou Email. |
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


Initialise une nouvelle instance de la classe  JpgViewOptions .

Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | La méthode qui crée le flux utilisé pour écrire les données de page de sortie. |

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initialise une nouvelle instance de la classe  JpgViewOptions .

Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | La méthode qui crée le flux utilisé pour écrire les données de page de sortie. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | La méthode qui libère le flux créé par la méthode assignée au délégué passé au paramètre  createPageStream . |

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


Initialise une nouvelle instance de la classe  JpgViewOptions .

Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | La fabrique qui implémente les méthodes de création et de libération du flux de page de sortie. |

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


Initialise une nouvelle instance de  JpgViewOptions  avec "p\_\{0\}.jpg" comme format de chemin de fichier pour les fichiers de sortie. Les fichiers de sortie seront placés dans le répertoire de travail actuel de l'application.

Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


Initialise une nouvelle instance de la classe  JpgViewOptions .

Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | Le format de chemin de fichier, par ex., 'page\_\{0\}.jpg'. |

### JpgViewOptions(Path filePathFormat) {#JpgViewOptions-java.nio.file.Path-}
```
public JpgViewOptions(Path filePathFormat)
```


Initialise une nouvelle instance de la classe  JpgViewOptions .

Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | Le format de chemin de fichier, par ex., 'page\_\{0\}.jpg'. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Obtient la largeur maximale d'une image de sortie en pixels.

Utilisez cette propriété pour définir la largeur maximale de l'image de sortie (en pixels). Pour un exemple de code, voir la [documentation][]. Si vous définissez la propriété \#setWidth(int).setWidth(int), cette propriété est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - la largeur maximale d'une image de sortie.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Définit la largeur maximale d'une image de sortie en pixels.

Utilisez cette propriété pour définir la largeur maximale de l'image de sortie (en pixels). Pour un exemple de code, voir la [documentation][]. Si vous définissez la propriété \#setWidth(int).setWidth(int), cette propriété est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| maxWidth | int | La largeur maximale d'une image de sortie. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Obtient la hauteur maximale d'une image de sortie en pixels.

Utilisez cette propriété pour définir la hauteur maximale de l'image de sortie (en pixels). Pour un exemple de code, consultez la [documentation][]. Si vous définissez la propriété \\#setHeight(int).setHeight(int), cette propriété est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - la hauteur maximale d'une image de sortie.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Définit la hauteur maximale d'une image de sortie en pixels.

Utilisez cette propriété pour définir la hauteur maximale de l'image de sortie (en pixels). Pour un exemple de code, consultez la [documentation][]. Si vous définissez la propriété \\#setHeight(int).setHeight(int), cette propriété est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| maxHeight | int | La hauteur maximale d'une image de sortie. |

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


Obtient la qualité de l'image de sortie.

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Returns:**
byte - la qualité de l'image de sortie.
### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


Définit la qualité de l'image de sortie.

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte | La qualité de l'image de sortie. |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Active l'extraction de texte.

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Returns:**
booléen -  true  si l'extraction de texte est activée,  false  sinon.
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Active ou désactive l'extraction de texte.

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | true  pour activer l'extraction de texte,  false  pour la désactiver. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtient la largeur de l'image de sortie en pixels.

Utilisez cette propriété pour définir la largeur de l'image de sortie (en pixels). Pour un exemple de code, consultez la [documentation][]. Si vous définissez cette propriété, la propriété \\#setMaxWidth(int).setMaxWidth(int) est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - la largeur de l'image de sortie.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Définit la largeur de l'image de sortie en pixels.

Utilisez cette propriété pour définir la largeur de l'image de sortie (en pixels). Pour un exemple de code, consultez la [documentation][]. Si vous définissez cette propriété, la propriété \\#setMaxWidth(int).setMaxWidth(int) est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | La largeur de l'image de sortie. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtient la hauteur de l'image de sortie en pixels.

Utilisez cette propriété pour définir la hauteur de l'image de sortie (en pixels). Pour un exemple de code, consultez la [documentation][]. Si vous définissez cette propriété, la propriété \\#setMaxHeight(int).setMaxHeight(int) est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - la hauteur de l'image de sortie.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Définit la hauteur de l'image de sortie en pixels.

Utilisez cette propriété pour définir la hauteur de l'image de sortie (en pixels). Pour un exemple de code, consultez la [documentation][]. Si vous définissez cette propriété, la propriété \\#setMaxHeight(int).setMaxHeight(int) est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int | La hauteur de l'image de sortie. |

### getPageStreamFactory() {#getPageStreamFactory--}
```
public final PageStreamFactory getPageStreamFactory()
```


Obtient la fabrique qui implémente les méthodes de création et de libération du flux de page de sortie.

**Returns:**
[PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) - the factory for the output page stream.
### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Obtient le rappel pour estimer la progression de l'enregistrement d'un document Words ou Email.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - le rappel pour estimer la progression de l'enregistrement du document.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Définit le rappel pour estimer la progression de l'enregistrement d'un document Words ou Email.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Le rappel pour estimer la progression de l'enregistrement du document. |

