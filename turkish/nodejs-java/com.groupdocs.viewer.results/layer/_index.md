---
title: "Katman"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Bir CAD çizimi içinde bulunan bir katmanı temsil eder."
type: docs
weight: 16
url: /tr/nodejs-java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

Bir CAD çizimi içinde bulunan bir katmanı temsil eder.

Layer arayüzü, GroupDocs.Viewer bileşenindeki bir CAD çizimindeki katmana erişim ve manipülasyon için sözleşmeyi tanımlar. Katman adı, görünürlük ve diğer özellikler gibi bilgileri almayı sağlayan yöntemler sunar.

Örnek kullanım:

```

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layers = viewInfo.getLayers();
     for (Layer layer : layers) {
         // Use the layer object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LayerImpl.*
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getName()](#getName--) | Katmanın adını alır. |
| [setName(String name)](#setName-java.lang.String-) | Katmanın adını ayarlar. |
| [isVisible()](#isVisible--) | Katmanın görünürlüğünü kontrol eder. |
| [setVisible(boolean isVisible)](#setVisible-boolean-) | Katmanın görünürlüğünü ayarlar. |
| [equals(Object other)](#equals-java.lang.Object-) | Bu nesnenin sağlanan nesneye eşit olup olmadığını kontrol eder. |
### getName() {#getName--}
```
public abstract String getName()
```


Katmanın adını alır.

**Note:** Layer names are case sensitive.

**Returns:**
java.lang.String - katmanın adı.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Katmanın adını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Katman için yeni ad. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Katmanın görünürlüğünü kontrol eder.

Kapalı veya dondurulmuş CAD çizim katmanları görünmezdir. Görünmez katmanları renderlemek için [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions\#setLayers-List-) seçeneğini kullanın.

**Returns:**
boolean -  katman görünürse true,  aksi takdirde false.
### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


Katmanın görünürlüğünü ayarlar.

Eğer  true , katman görünür; eğer  false , gizli olacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isVisible | boolean | Katmanın görünür olup olmayacağı. |

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Bu nesnenin sağlanan nesneye eşit olup olmadığını kontrol eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| diğer | java.lang.Object | Karşılaştırılacak nesne. |

**Returns:**
boolean -  true  nesneler eşitse,  false  aksi takdirde.
