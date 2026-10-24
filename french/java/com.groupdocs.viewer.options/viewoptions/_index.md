---
title: "ViewOptions"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Contient les options de rendu."
type: docs
weight: 35
url: /fr/java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

Contient les options de rendu.


La classe ViewOptions étend la classe BaseViewOptions et sert de classe de base pour les options de rendu
dans le composant GroupDocs.Viewer. Elle encapsule des paramètres et réglages communs qui peuvent être utilisés
pour rendre différents types de documents dans divers formats.


***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | Obtient le filigrane texte appliqué à chaque page. |
|
|  | [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | Définit le filigrane texte à appliquer à chaque page. |
|
|  | [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | Applique une rotation horaire à la page spécifiée. |
|
|  | [getPageRotations()](#getPageRotations--) | Récupère les rotations de page. |
|
|  | [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | Pour éviter de créer l'instance uniquement pour vérifier qu'elle est vide |
|
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


Obtient le filigrane texte appliqué à chaque page.


Dans le cas où #setWatermark(Watermark).setWatermark(Watermark) et #getPageRotations().getPageRotations() sont spécifiés,
le filigrane sera appliqué aux pages tournées.
Pour plus de détails, voir la [documentation](../https://docs.groupdocs.com/viewer/java/add-text-watermark/).


**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.

### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


Définit le filigrane texte à appliquer à chaque page.


Dans le cas où les deux
ViewOptions.Watermark
et #getPageRotations().getPageRotations() sont spécifiés,
le filigrane sera appliqué aux pages tournées.
Pour plus de détails, voir la [documentation](../https://docs.groupdocs.com/viewer/java/add-text-watermark/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Watermark](../../com.groupdocs.viewer.options/watermark) | Le filigrane texte à définir. |
|

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


Applique une rotation horaire à la page spécifiée.
Pour plus de détails, voir la [documentation](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | pageNumber | int | Le numéro de page doit être strictement supérieur à 0. |
|
|  | rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | La valeur de rotation. |
|

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


Récupère les rotations de page.


Si les deux [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions#setWatermark-Watermark-) et
getPageRotations()
sont spécifiés,
le filigrane sera appliqué aux pages tournées.
Pour plus de détails, voir la [documentation](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/).


**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> - une map contenant les numéros de page comme clés et leurs rotations correspondantes comme valeurs.

### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


Pour éviter de créer l'instance uniquement pour vérifier qu'elle est vide


**Returns:**
boolean
