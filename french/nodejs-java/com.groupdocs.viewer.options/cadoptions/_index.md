---
title: "CadOptions"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Fournit des options pour le rendu des dessins CAO."
type: docs
weight: 13
url: /fr/nodejs-java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

Fournit des options pour le rendu des dessins CAO.

La classe CadOptions encapsule divers paramètres et réglages qui peuvent être utilisés pour contrôler le rendu des dessins CAD dans le composant GroupDocs.Viewer.

Pour plus d'informations et des exemples de code, consultez le [Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] et le [Specify rendering options for CAD files][].

Exemple d'utilisation :

```

 CadOptions options = CadOptions.forRenderingByWidth(256);
 options.setRenderLayouts(true);
 options.setBackgroundColor(Color.YELLOW);
 options.setLayers(Arrays.asList(
         CacheableFactory.getInstance().newLayer("Layer1"),
         CacheableFactory.getInstance().newLayer("Layer2")
 ));

 try (Viewer viewer = new Viewer("document.dwg")) {
     PdfViewOptions pdfViewOptions = new PdfViewOptions();
     pdfViewOptions.setCadOptions(options);
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/
## Champs

| Champ | Description |
| --- | --- |
| [WIDTH](#WIDTH) |  |
| [HEIGHT](#HEIGHT) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPc3File()](#getPc3File--) | Récupère le fichier PC3 (Configuration du traceur) associé au traceur. |
| [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | Définit le fichier PC3 (Configuration du traceur) associé au traceur. |
| [forRenderingByScaleFactor(double scaleFactor)](#forRenderingByScaleFactor-double-) | Initialise une nouvelle instance de la classe  CadOptions  pour le rendu par facteur d'échelle. |
| [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | Initialise une nouvelle instance de la classe  CadOptions  pour le rendu par largeur. |
| [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | Initialise une nouvelle instance de la classe  CadOptions  pour le rendu par hauteur. |
| [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | Initialise une nouvelle instance de la classe CadOptions pour le rendu par largeur et hauteur. |
| [getScaleFactor()](#getScaleFactor--) | Obtient le facteur d'échelle pour le rendu. |
| [getWidth()](#getWidth--) | Obtient la largeur du résultat de sortie en pixels. |
| [getHeight()](#getHeight--) | Obtient la hauteur du résultat de sortie en pixels. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtient la couleur d'arrière-plan de l'image. |
| [getBackgroundColorAsHex()](#getBackgroundColorAsHex--) | Obtient la couleur d'arrière-plan de l'image. |
| [setBackgroundColor(Color backgroundColor)](#setBackgroundColor-java.awt.Color-) | Définit la couleur d'arrière-plan de l'image. |
| [setBackgroundColor(String colorName)](#setBackgroundColor-java.lang.String-) | Définit la couleur d'arrière-plan de l'image. |
| [getTiles()](#getTiles--) | Obtient les régions de dessin à rendre. |
| [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | Définit les régions de dessin à rendre. |
| [isRenderLayouts()](#isRenderLayouts--) | Indique si les mises en page du document CAD doivent être rendues. |
| [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | Définit si les mises en page du document CAD doivent être rendues. |
| [getLayoutName()](#getLayoutName--) | Obtient le nom de la mise en page spécifique à rendre. |
| [setLayoutName(String value)](#setLayoutName-java.lang.String-) | Définit le nom de la mise en page spécifique à rendre. |
| [getLayers()](#getLayers--) | Obtient les calques de dessin CAD à rendre. |
| [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Obtient les calques de dessin CAD à rendre. |
| [isEnablePerformanceConversionMode()](#isEnablePerformanceConversionMode--) | Mettre ce drapeau à true active un mode de conversion spécial orienté performance pour tous les formats de la famille CAD. |
| [setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)](#setEnablePerformanceConversionMode-boolean-) | Mettre ce drapeau à true active un mode de conversion spécial orienté performance pour tous les formats de la famille CAD. |
| [equals(Object o)](#equals-java.lang.Object-) | Vérifie si cet objet CadOptions est égal à un autre objet. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | \{@inheritDoc\} |
| [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | \{@inheritDoc\} |
### WIDTH {#WIDTH}
```
public static final String WIDTH
```


### HEIGHT {#HEIGHT}
```
public static final String HEIGHT
```


### getPc3File() {#getPc3File--}
```
public String getPc3File()
```


Récupère le fichier PC3 (Configuration du traceur) associé au traceur.

**Returns:**
java.lang.String - le chemin du fichier PC3.
### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


Définit le fichier PC3 (Configuration du traceur) associé au traceur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pc3File | java.lang.String | Le chemin du fichier PC3. |

### forRenderingByScaleFactor(double scaleFactor) {#forRenderingByScaleFactor-double-}
```
public static CadOptions forRenderingByScaleFactor(double scaleFactor)
```


Initialise une nouvelle instance de la classe  CadOptions  pour le rendu par facteur d'échelle.

Pour un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scaleFactor | double | Le facteur d'échelle pour le rendu. Les valeurs supérieures à 1 agrandiront le résultat de sortie, tandis que les valeurs comprises entre 0 et 1 le réduiront. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by scale factor.
### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


Initialise une nouvelle instance de la classe  CadOptions  pour le rendu par largeur.

Pour un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur du résultat de sortie en pixels. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width.
### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


Initialise une nouvelle instance de la classe  CadOptions  pour le rendu par hauteur.

Pour un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| height | int | La hauteur du résultat de sortie en pixels. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by height.
### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


Initialise une nouvelle instance de la classe CadOptions pour le rendu par largeur et hauteur.

Pour un exemple de code, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur du résultat de sortie en pixels. |
| height | int | La hauteur du résultat de sortie en pixels. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width and height.
### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Obtient le facteur d'échelle pour le rendu. Les valeurs supérieures à 1 agrandiront le résultat de sortie, tandis que les valeurs comprises entre 0 et 1 le réduiront.

**Returns:**
double - le facteur d'échelle pour le rendu.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtient la largeur du résultat de sortie en pixels.

**Returns:**
int - la largeur du résultat de sortie.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtient la hauteur du résultat de sortie en pixels.

**Returns:**
int - la hauteur du résultat de sortie.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtient la couleur d'arrière-plan de l'image.

**Returns:**
java.awt.Color - la couleur d'arrière-plan de l'image.
### getBackgroundColorAsHex() {#getBackgroundColorAsHex--}
```
public String getBackgroundColorAsHex()
```


Obtient la couleur d'arrière-plan de l'image.

**Returns:**
java.lang.String - la couleur d'arrière-plan de l'image au format 0xFFFFFF.
### setBackgroundColor(Color backgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color backgroundColor)
```


Définit la couleur d'arrière-plan de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| backgroundColor | java.awt.Color | La couleur d'arrière-plan de l'image. |

### setBackgroundColor(String colorName) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String colorName)
```


Définit la couleur d'arrière-plan de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorName | java.lang.String | Le nom de la couleur d'arrière-plan de l'image. |

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


Obtient les régions de dessin à rendre.

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile> - la liste des régions de dessin à rendre.
### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


Définit les régions de dessin à rendre.

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.options.Tile> | La liste des régions de dessin à rendre. |

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


Indique si les mises en page du document CAD doivent être rendues.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
boolean -  true  si les mises en page doivent être rendues,  false  sinon.
### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


Définit si les mises en page du document CAD doivent être rendues.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | true  pour rendre les mises en page,  false  sinon. |

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


Obtient le nom de la mise en page spécifique à rendre. Le nom de la mise en page est sensible à la casse.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
java.lang.String - le nom de la mise en page spécifique à rendre.
### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


Définit le nom de la mise en page spécifique à rendre. Le nom de la mise en page est sensible à la casse.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Le nom de la mise en page spécifique à rendre. |

### getLayers() {#getLayers--}
```
public final List<Layer> getLayers()
```


Obtient les calques de dessin CAD à rendre.

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - les calques de dessin CAD.
### setLayers(List<Layer> value) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public final void setLayers(List<Layer> value)
```


Obtient les calques de dessin CAD à rendre.

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.results.Layer> | Les calques de dessin CAD. |

### isEnablePerformanceConversionMode() {#isEnablePerformanceConversionMode--}
```
public boolean isEnablePerformanceConversionMode()
```


Activer ce drapeau à true active un mode de conversion spécial orienté performance pour tous les formats de la famille CAD. Dans ce mode, la vitesse de conversion est beaucoup plus rapide, mais la qualité des documents résultants est nettement pire. Par défaut, il est désactivé (false). La qualité des documents résultants est la meilleure possible au détriment des performances.

**Returns:**
boolean -  true  si le mode de conversion orienté performance est activé,  false  sinon.
### setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode) {#setEnablePerformanceConversionMode-boolean-}
```
public void setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)
```


Activer ce drapeau à true active un mode de conversion spécial orienté performance pour tous les formats de la famille CAD. Dans ce mode, la vitesse de conversion est beaucoup plus rapide, mais la qualité des documents résultants est nettement pire. Par défaut, il est désactivé (false). La qualité des documents résultants est la meilleure possible au détriment des performances.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| enablePerformanceConversionMode | boolean | true  pour activer le mode de conversion orienté performance,  false  pour le désactiver. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Vérifie si cet objet CadOptions est égal à un autre objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | L'objet à comparer. |

**Returns:**
boolean -  true  si les objets sont égaux,  false  sinon.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Calcule la valeur du code de hachage pour cet objet. Le code de hachage est basé sur l'état interne de l'objet et est utilisé dans les structures de données basées sur le hachage telles que les tables de hachage et les ensembles de hachage.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - la valeur du code de hachage pour cet objet.
### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne de cet objet.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Returns:**
java.lang.String - une représentation sous forme de chaîne de cet objet.
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Renvoie une représentation sous forme de chaîne de cet objet.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| style | org.apache.commons.lang3.builder.ToStringStyle | Le ToStringStyle à utiliser pour générer la représentation sous forme de chaîne. |

**Returns:**
java.lang.String - une représentation sous forme de chaîne de cet objet en utilisant le ToStringStyle spécifié.
