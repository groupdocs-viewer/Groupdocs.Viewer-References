---
title: "Katman"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Bir CAD çizimi içinde bulunan bir katmanı temsil eder."
type: docs
weight: 16
url: /tr/java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

Bir CAD çizimi içinde bulunan bir katmanı temsil eder.


Katman arayüzü, bir CAD çizimindeki katmana erişmek ve onu manipüle etmek için sözleşmeyi tanımlar
GroupDocs.Viewer bileşeninde. Katman adı gibi bilgileri almak için yöntemler sağlar,
görünürlük ve diğer özellikler.


Örnek kullanım:

````

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layers = viewInfo.getLayers();
     for (Layer layer : layers) {
         // Use the layer object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LayerImpl.*

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getName()](#getName--) | Katmanın adını alır. |
|
|  | [setName(String name)](#setName-java.lang.String-) | Katmanın adını ayarlar. |
|
|  | [isVisible()](#isVisible--) | Katmanın görünürlüğünü kontrol eder. |
|
|  | [setVisible(boolean isVisible)](#setVisible-boolean-) | Katmanın görünürlüğünü ayarlar. |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Bu nesnenin sağlanan nesneye eşit olup olmadığını kontrol eder. |
|
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
|  | ad | java.lang.String | Katman için yeni ad. |
|

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Katmanın görünürlüğünü kontrol eder.


Kapalı veya dondurulmuş CAD çizim katmanları görünmez.
Görünmez katmanları işlemek için, [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions#setLayers-List-) seçeneğini kullanın.


**Returns:**
boolean -  true  katman görünürse,  false  aksi takdirde.

### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


Katmanın görünürlüğünü ayarlar.


Eğer
true
, katman görünür olacaktır; eğer
false
, gizli olacaktır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | isVisible | boolean | Katmanın görünür olup olmaması. |
|

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Bu nesnenin sağlanan nesneye eşit olup olmadığını kontrol eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | diğer | java.lang.Object | Karşılaştırılacak nesne. |
|

**Returns:**
boolean -  true  nesneler eşitse,  false  aksi takdirde.

