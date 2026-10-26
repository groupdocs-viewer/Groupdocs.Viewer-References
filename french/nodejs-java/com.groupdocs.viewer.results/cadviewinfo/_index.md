---
title: "CadViewInfo"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Représente les informations de vue pour un dessin CAO."
type: docs
weight: 13
url: /fr/nodejs-java/com.groupdocs.viewer.results/cadviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface CadViewInfo extends ViewInfo
```

Représente les informations de vue pour un dessin CAO.

L'interface CadViewInfo définit le contrat pour récupérer les informations de vue spécifiques à un dessin CAO dans le composant GroupDocs.Viewer. Elle fournit des méthodes pour accéder aux calques des dessins CAO.

Exemple d'utilisation :

```

 try (Viewer viewer = new Viewer("document.plt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is CadViewInfoImpl.*
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLayers()](#getLayers--) | Récupère la liste des calques du dessin CAO. |
| [setLayers(List<Layer> layers)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Définit la liste des calques du dessin CAO. |
| [getLayouts()](#getLayouts--) | Récupère la liste des mises en page contenues dans le dessin CAO. |
| [setLayouts(List<Layout> layouts)](#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--) | Définit la liste des mises en page contenues dans le dessin CAO. |
### getLayers() {#getLayers--}
```
public abstract List<Layer> getLayers()
```


Récupère la liste des calques du dessin CAO.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - les calques du dessin CAO.
### setLayers(List<Layer> layers) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public abstract void setLayers(List<Layer> layers)
```


Définit la liste des calques du dessin CAO.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| layers | java.util.List<com.groupdocs.viewer.results.Layer> | les calques à définir pour le dessin CAO. |

### getLayouts() {#getLayouts--}
```
public abstract List<Layout> getLayouts()
```


Récupère la liste des mises en page contenues dans le dessin CAO.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layout> - les mises en page du dessin CAO.
### setLayouts(List<Layout> layouts) {#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--}
```
public abstract void setLayouts(List<Layout> layouts)
```


Définit la liste des mises en page contenues dans le dessin CAO.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| layouts | java.util.List<com.groupdocs.viewer.results.Layout> | les mises en page à définir pour le dessin CAO. |

