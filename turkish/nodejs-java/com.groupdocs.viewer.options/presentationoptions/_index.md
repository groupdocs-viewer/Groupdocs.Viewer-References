---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Sunumları renderleme seçeneklerini sağlar."
type: docs
weight: 26
url: /tr/nodejs-java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

Sunumları renderleme seçeneklerini sağlar.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isRenderToPureHtml()](#isRenderToPureHtml--) | Presentation belgeleri için yeni bir HTML renderleme modunu etkinleştirir. |
| [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Presentation belgeleri için yeni bir HTML renderleme modunu etkinleştirir. |
| [getResolution()](#getResolution--) | Sunum içindeki görüntüler için çözünürlük (yalnızca HTML/PDF renderleme için). |
| [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | Sunum içindeki görüntüler için çözünürlük (yalnızca HTML/PDF renderleme için). |
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Presentation belgeleri için yeni bir HTML renderleme modunu etkinleştirir.

Bu modda, Presentation dosyaları SVG görüntüler olmadan saf HTML/CSS işaretlemesine renderlenir. Varsayılan olarak, bu özellik devre dışıdır (false). Bu seçenek etkinleştirilmezse mevcut SVG tabanlı HTML renderleyici kullanılır.

**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Presentation belgeleri için yeni bir HTML renderleme modunu etkinleştirir.

Bu modda, Presentation dosyaları SVG görüntüler olmadan saf HTML/CSS işaretlemesine renderlenir. Varsayılan olarak, bu özellik devre dışıdır (false). Bu seçenek etkinleştirilmezse mevcut SVG tabanlı HTML renderleyici kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Sunum içindeki görüntüler için çözünürlük (yalnızca HTML/PDF renderleme için).

Kod örneği için, [documentation][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


Sunum içindeki görüntüler için çözünürlük (yalnızca HTML/PDF renderleme için).

Kod örneği için, [documentation][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

