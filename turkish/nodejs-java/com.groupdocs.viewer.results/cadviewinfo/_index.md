---
title: "CadViewInfo"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Bir CAD çizimi için görünüm bilgilerini temsil eder."
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.viewer.results/cadviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface CadViewInfo extends ViewInfo
```

Bir CAD çizimi için görünüm bilgilerini temsil eder.

CadViewInfo arabirimi, GroupDocs.Viewer bileşeninde bir CAD çizimine özgü görünüm bilgilerini almak için sözleşmeyi tanımlar. CAD çizim katmanlarına erişim sağlayan yöntemler sunar.

Örnek kullanım:

```

 try (Viewer viewer = new Viewer("document.plt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is CadViewInfoImpl.*
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLayers()](#getLayers--) | CAD çizimindeki katmanların listesini alır. |
| [setLayers(List<Layer> layers)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | CAD çizimindeki katmanların listesini ayarlar. |
| [getLayouts()](#getLayouts--) | CAD çiziminde bulunan yerleşimlerin listesini alır. |
| [setLayouts(List<Layout> layouts)](#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--) | CAD çiziminde bulunan yerleşimlerin listesini ayarlar. |
### getLayers() {#getLayers--}
```
public abstract List<Layer> getLayers()
```


CAD çizimindeki katmanların listesini alır.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - CAD çizimindeki katmanlar.
### setLayers(List<Layer> layers) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public abstract void setLayers(List<Layer> layers)
```


CAD çizimindeki katmanların listesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| katmanlar | java.util.List<com.groupdocs.viewer.results.Layer> | CAD çizimi için ayarlanacak katmanlar. |

### getLayouts() {#getLayouts--}
```
public abstract List<Layout> getLayouts()
```


CAD çiziminde bulunan yerleşimlerin listesini alır.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layout> - CAD çizimindeki yerleşimler.
### setLayouts(List<Layout> layouts) {#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--}
```
public abstract void setLayouts(List<Layout> layouts)
```


CAD çiziminde bulunan yerleşimlerin listesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| düzenler | java.util.List<com.groupdocs.viewer.results.Layout> | CAD çizimi için ayarlanacak yerleşimler. |

