---
title: "PresentationOptions"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Fournit des options pour le rendu des présentations."
type: docs
weight: 26
url: /fr/java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

Fournit des options pour le rendu des présentations.


Pour plus de détails, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isRenderToPureHtml()](#isRenderToPureHtml--) | Active un nouveau mode de rendu HTML pour les documents Presentation. |
|
|  | [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Active un nouveau mode de rendu HTML pour les documents Presentation. |
|
|  | [isRenderHeaderFooterPlaceholders()](#isRenderHeaderFooterPlaceholders--) | Active le rendu des espaces réservés dans l'en-tête et le pied de page d'une diapositive. |
|
|  | [setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)](#setRenderHeaderFooterPlaceholders-boolean-) | Active le rendu des espaces réservés dans l'en-tête et le pied de page d'une diapositive. |
|
|  | [getResolution()](#getResolution--) | Résolution des images à l'intérieur de la présentation (uniquement pour le rendu HTML/PDF). |
|
|  | [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | Résolution des images à l'intérieur de la présentation (uniquement pour le rendu HTML/PDF). |
|
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Active un nouveau mode de rendu HTML pour les documents Presentation.


Dans ce mode, les fichiers Presentation sont rendus en balisage HTML/CSS pur, sans images SVG.
Par défaut, cette fonctionnalité est désactivée (false). Le rendu HTML existant basé sur SVG est utilisé si cette option n'est pas activée.


**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Active un nouveau mode de rendu HTML pour les documents Presentation.


Dans ce mode, les fichiers Presentation sont rendus en balisage HTML/CSS pur, sans images SVG.
Par défaut, cette fonctionnalité est désactivée (false). Le rendu HTML existant basé sur SVG est utilisé si cette option n'est pas activée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### isRenderHeaderFooterPlaceholders() {#isRenderHeaderFooterPlaceholders--}
```
public boolean isRenderHeaderFooterPlaceholders()
```


Active le rendu des espaces réservés dans l'en-tête et le pied de page d'une diapositive. Désactivé par défaut (false). Cette option s'applique à tous les 4 modes de rendu des présentations : HTML, PDF, PNG et JPEG. N'est pas applicable lors du rendu de la présentation en balisage HTML/CSS pur en utilisant .


**Returns:**
boolean
### setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders) {#setRenderHeaderFooterPlaceholders-boolean-}
```
public void setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)
```


Active le rendu des espaces réservés dans l'en-tête et le pied de page d'une diapositive. Désactivé par défaut (false). Cette option s'applique à tous les 4 modes de rendu des présentations : HTML, PDF, PNG et JPEG. N'est pas applicable lors du rendu de la présentation en balisage HTML/CSS pur en utilisant .


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| renderHeaderFooterPlaceholders | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Résolution des images à l'intérieur de la présentation (uniquement pour le rendu HTML/PDF).


Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution).


**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


Résolution des images à l'intérieur de la présentation (uniquement pour le rendu HTML/PDF).


Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

