---
title: "VisioRenderingOptions"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Visio belgelerini renderleme seçeneklerini içerir."
type: docs
weight: 36
url: /tr/nodejs-java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Visio belgelerini renderleme seçeneklerini içerir.

VisioRenderingOptions sınıfı, GroupDocs.Viewer bileşeninde Visio dosyalarını işlemek ve render etmek için seçenekler sunar. Visio belgelerinin render sürecini ve çıktı formatını kontrol etmek için kullanılabilecek ayarları ve parametreleri kapsar. Ayrıntılar için [documentation][] sayfasına bakın.

Örnek kullanım:

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
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [VisioRenderingOptions()](#VisioRenderingOptions--) | VisioRenderingOptions sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isRenderFiguresOnly()](#isRenderFiguresOnly--) | Şemayı hariç tutarak yalnızca Visio figürlerini render eder. |
| [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | Şemayı hariç tutarak yalnızca Visio figürlerini render etmek için bayrağı ayarlar. |
| [getFigureWidth()](#getFigureWidth--) | Figürün genişliğini alır. |
| [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | Figürün genişliğini ayarlar. |
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


VisioRenderingOptions sınıfının yeni bir örneğini başlatır.

### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


Şemayı hariç tutarak yalnızca Visio figürlerini render eder.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Returns:**
boolean -  true  yalnızca Visio şekilleri render edilmesi gerekiyorsa,  false  aksi takdirde.
### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


Şemayı hariç tutarak yalnızca Visio figürlerini render etmek için bayrağı ayarlar.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderFiguresOnly | boolean | true  yalnızca Visio şekillerini render etmek için,  false  diyagramı dahil etmek için. |

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
| figureWidth | int | Şeklin genişliği. |

