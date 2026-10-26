---
title: "VisioRenderingOptions"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Contient des options pour le rendu des documents Visio."
type: docs
weight: 36
url: /fr/nodejs-java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Contient des options pour le rendu des documents Visio.

La classe VisioRenderingOptions fournit des options pour le traitement et le rendu des fichiers Visio dans le composant GroupDocs.Viewer. Elle encapsule des paramètres et des réglages pouvant être utilisés pour contrôler le processus de rendu et le format de sortie des documents Visio. Pour plus de détails, consultez la [documentation][].

Exemple d'utilisation :

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [VisioRenderingOptions()](#VisioRenderingOptions--) | Initialise une nouvelle instance de la classe  VisioRenderingOptions . |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isRenderFiguresOnly()](#isRenderFiguresOnly--) | Rendre uniquement les figures Visio, en excluant le diagramme. |
| [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | Définit le drapeau pour rendre uniquement les figures Visio, en excluant le diagramme. |
| [getFigureWidth()](#getFigureWidth--) | Récupère la largeur de la figure. |
| [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | Définit la largeur de la figure. |
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


Initialise une nouvelle instance de la classe  VisioRenderingOptions .

### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


Rendre uniquement les figures Visio, en excluant le diagramme.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Returns:**
boolean -  true  si seules les figures Visio doivent être rendues,  false  sinon.
### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


Définit le drapeau pour rendre uniquement les figures Visio, en excluant le diagramme.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| renderFiguresOnly | boolean | true  pour rendre uniquement les figures Visio,  false  pour inclure le diagramme. |

### getFigureWidth() {#getFigureWidth--}
```
public int getFigureWidth()
```


Récupère la largeur de la figure. La hauteur sera calculée automatiquement.

**Returns:**
int - la largeur de la figure.
### setFigureWidth(int figureWidth) {#setFigureWidth-int-}
```
public void setFigureWidth(int figureWidth)
```


Définit la largeur de la figure. La hauteur sera calculée automatiquement.

***Note:** Default value is 100.*

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| figureWidth | int | La largeur de la figure. |

