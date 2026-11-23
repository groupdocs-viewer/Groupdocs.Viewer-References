---
title: "PdfViewOptions"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Fournit des options pour le rendu des documents au format PDF."
type: docs
weight: 23
url: /fr/nodejs-java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

Fournit des options pour le rendu des documents au format PDF.

La classe PdfViewOptions encapsule des paramètres et des réglages supplémentaires qui peuvent être utilisés pour contrôler le rendu des documents au format PDF dans le composant GroupDocs.Viewer. Pour plus de détails, voir la [documentation][].

Exemple d'utilisation :

```

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | Initialise une nouvelle instance de la classe  PdfViewOptions . |
| [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | Initialise une nouvelle instance de la classe  PdfViewOptions . |
| [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | Initialise une nouvelle instance de la classe  PdfViewOptions . |
| [PdfViewOptions()](#PdfViewOptions--) | Initialise une nouvelle instance de la classe  PdfViewOptions  avec les paramètres par défaut. |
| [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | Initialise une nouvelle instance de la classe  PdfViewOptions . |
| [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | Initialise une nouvelle instance de la classe  PdfViewOptions . |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | Réduisez la taille du fichier PDF de sortie en appliquant des techniques d'optimisation avec différentes options. |
| [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | Réduisez la taille du fichier PDF de sortie en appliquant des techniques d'optimisation avec différentes options. |
| [getImageMaxWidth()](#getImageMaxWidth--) | Récupère la largeur maximale d'une image de sortie en pixels. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Définit la largeur maximale d'une image de sortie en pixels. |
| [getImageMaxHeight()](#getImageMaxHeight--) | Récupère la hauteur maximale d'une image de sortie en pixels. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Définit la hauteur maximale d'une image de sortie en pixels. |
| [getImageWidth()](#getImageWidth--) | Récupère la largeur de l'image de sortie en pixels. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | Définit la largeur de l'image de sortie en pixels. |
| [getImageHeight()](#getImageHeight--) | Récupère la hauteur de l'image de sortie en pixels. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | Définit la hauteur de l'image de sortie en pixels. |
| [getSecurity()](#getSecurity--) | Récupère les options de sécurité du document PDF de sortie. |
| [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | Définit les options de sécurité du document PDF de sortie. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Récupère le callback utilisé pour estimer la progression de l'enregistrement d'un document Words ou Email. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Définit le callback utilisé pour estimer la progression de l'enregistrement d'un document Words ou Email. |
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


Initialise une nouvelle instance de la classe  PdfViewOptions .

Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


Initialise une nouvelle instance de la classe  PdfViewOptions .

Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | La méthode utilisée pour instancier le flux d'écriture des données du fichier de sortie. |
| releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | La méthode utilisée pour libérer le flux créé par la méthode  createFileStream  . |

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


Initialise une nouvelle instance de la classe  PdfViewOptions .

Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | La fabrique qui implémente les méthodes de création et de libération du flux de fichier de sortie. |

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


Initialise une nouvelle instance de la classe  PdfViewOptions  avec les paramètres par défaut.

Ce constructeur crée un nouvel objet  PdfViewOptions  avec "output.pdf" comme format de chemin de fichier pour le fichier de sortie. Le fichier de sortie sera placé dans le répertoire de travail actuel de l'application. Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


Initialise une nouvelle instance de la classe  PdfViewOptions .

Ce constructeur crée un nouvel objet  PdfViewOptions  avec le paramètre  outputFilePath  spécifié représentant le chemin du fichier PDF de sortie. Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| outputFilePath | java.lang.String | Le chemin du fichier PDF de sortie. |

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


Initialise une nouvelle instance de la classe  PdfViewOptions .

Pour l'exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| outputFilePath | java.nio.file.Path | Le chemin du fichier PDF de sortie. |

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


Réduisez la taille du fichier PDF de sortie en appliquant des techniques d'optimisation avec différentes options.

Cette option est prise en charge pour tous les formats de fichiers d'entrée qui sont pris en charge pour la conversion en PDF : [Supported document formats][] Pour plus de détails et des exemples de code, voir cette [page][] et ses sous‑pages.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.
### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


Réduisez la taille du fichier PDF de sortie en appliquant des techniques d'optimisation avec différentes options.

Cette option est prise en charge pour tous les formats de fichiers d'entrée qui sont pris en charge pour la conversion en PDF : [Supported document formats][] Pour plus de détails et des exemples de code, voir cette [page][] et ses sous‑pages.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | Objet PdfOptimizationOptions ou null. |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Récupère la largeur maximale d'une image de sortie en pixels. Ce paramètre s'applique uniquement lors de la conversion d'une image unique en HTML.

Utilisez cette propriété pour définir la largeur maximale de l'image de sortie (en pixels). GroupDocs.Viewer applique cette propriété lors du rendu d'une image unique en PDF. Pour plus de détails, voir la [documentation][]. Si vous définissez la  propriété, cette propriété est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - la largeur maximale de l'image de sortie en pixels.
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Définit la largeur maximale d'une image de sortie en pixels. Ce paramètre s'applique uniquement lors de la conversion d'une image unique en HTML.

Utilisez cette propriété pour définir la largeur maximale de l'image de sortie (en pixels). GroupDocs.Viewer applique cette propriété lors du rendu d'une image unique en PDF. Pour plus de détails, voir la [documentation][]. Si vous définissez la  propriété, cette propriété est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageMaxWidth | int | La largeur maximale de l'image de sortie en pixels. |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Récupère la hauteur maximale d'une image de sortie en pixels. Ce paramètre s'applique uniquement lors de la conversion d'une image unique en HTML.

Utilisez cette propriété pour définir la hauteur maximale de l'image de sortie (en pixels). GroupDocs.Viewer applique cette propriété lors du rendu d'une image unique en PDF. Pour plus de détails, voir la [documentation][]. Si vous définissez la  propriété, cette propriété est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - la hauteur maximale de l'image de sortie en pixels.
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Définit la hauteur maximale d'une image de sortie en pixels. Ce paramètre s'applique uniquement lors de la conversion d'une seule image en HTML.

Utilisez cette propriété pour définir la hauteur maximale de l'image de sortie (en pixels). GroupDocs.Viewer applique cette propriété uniquement lors du rendu d'une seule image en HTML. Pour plus de détails, consultez la [documentation][]. Si vous définissez la  propriété, cette propriété est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageMaxHeight | int | La hauteur maximale de l'image de sortie en pixels. |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Récupère la largeur de l'image de sortie en pixels. Ce paramètre s'applique uniquement lors de la conversion d'une seule image en HTML.

Utilisez cette propriété pour définir la largeur de l'image de sortie (en pixels). GroupDocs.Viewer applique cette propriété lors du rendu d'une seule image en PDF. Pour plus de détails, consultez la [documentation][]. Si vous définissez cette propriété, la  propriété est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - la largeur de l'image de sortie en pixels.
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Définit la largeur de l'image de sortie en pixels. Ce paramètre s'applique uniquement lors de la conversion d'un PDF contenant une seule image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageWidth | int | La largeur de l'image de sortie en pixels. |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Récupère la hauteur de l'image de sortie en pixels. Ce paramètre s'applique uniquement lors de la conversion d'une seule image en HTML.

Utilisez cette propriété pour définir la hauteur de l'image de sortie (en pixels). GroupDocs.Viewer applique cette propriété uniquement lors du rendu d'une seule image en HTML. Pour plus de détails, consultez la [documentation][]. Si vous définissez cette propriété, la  propriété est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - la hauteur de l'image de sortie en pixels.
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Définit la hauteur de l'image de sortie en pixels. Ce paramètre s'applique uniquement lors de la conversion d'une seule image en HTML.

Utilisez cette propriété pour définir la hauteur de l'image de sortie (en pixels). GroupDocs.Viewer applique cette propriété uniquement lors du rendu d'une seule image en HTML. Pour plus de détails, consultez la [documentation][]. Si vous définissez cette propriété, la  propriété est ignorée.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageHeight | int | La hauteur de l'image de sortie en pixels. |

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


Récupère les options de sécurité du document PDF de sortie.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.
### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


Définit les options de sécurité du document PDF de sortie.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Security](../../com.groupdocs.viewer.options/security) | Les options de sécurité du document PDF de sortie. |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Récupère le callback utilisé pour estimer la progression de l'enregistrement d'un document Words ou Email.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - le rappel pour estimer la progression de l'enregistrement du document.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Définit le callback utilisé pour estimer la progression de l'enregistrement d'un document Words ou Email.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Le rappel pour estimer la progression de l'enregistrement du document. |

