---
title: "VisioRenderingOptions"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Visio belgelerini işlemek için seçenekleri içerir."
type: docs
weight: 36
url: /tr/java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Visio belgelerini işlemek için seçenekleri içerir.


VisioRenderingOptions sınıfı, Visio dosyalarını işleme ve renderleme seçenekleri sağlar
GroupDocs.Viewer bileşeninde. Kullanılabilecek ayarları ve parametreleri kapsar
Visio belgeleri için renderleme sürecini ve çıktı formatını kontrol etmek için.
Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-visio-documents/) bakın.


Örnek kullanım:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [VisioRenderingOptions()](#VisioRenderingOptions--) | Yeni bir örnek başlatır |
VisioRenderingOptions
sınıf.
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isRenderFiguresOnly()](#isRenderFiguresOnly--) | Şemayı hariç tutarak yalnızca Visio şekillerini renderle. |
|
|  | [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | Şemayı hariç tutarak yalnızca Visio şekillerini renderlemek için bayrağı ayarlar. |
|
|  | [getFigureWidth()](#getFigureWidth--) | Şeklin genişliğini alır. |
|
|  | [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | Şeklin genişliğini ayarlar. |
|
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


Yeni bir örnek başlatır
VisioRenderingOptions
sınıf.


### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


Şemayı hariç tutarak yalnızca Visio şekillerini renderle.
Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes) bakın.


**Returns:**
boolean -  true  yalnızca Visio şekilleri renderlenecekse,  false  aksi takdirde.

### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


Şemayı hariç tutarak yalnızca Visio şekillerini renderlemek için bayrağı ayarlar.
Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | renderFiguresOnly | boolean | true  yalnızca Visio şekillerini renderlemek için,  false  şemayı dahil etmek için. |
|

### getFigureWidth() {#getFigureWidth--}
```
public int getFigureWidth()
```


Şeklin genişliğini alır. Yükseklik otomatik olarak hesaplanacaktır.


**Returns:**
int - şeklin genişliği.

### setFigureWidth(int figureWidth) {#setFigureWidth-int-}
```
public void setFigureWidth(int figureWidth)
```


Şeklin genişliğini ayarlar. Yükseklik otomatik olarak hesaplanacaktır.


***Note:** Default value is 100.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | figureWidth | int | Şeklin genişliği. |
|

