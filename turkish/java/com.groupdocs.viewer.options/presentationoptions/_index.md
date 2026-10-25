---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Sunumları işlemek için seçenekler sağlar."
type: docs
weight: 26
url: /tr/java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

Sunumları işlemek için seçenekler sağlar.


Ayrıntılar için [belgelere](../https://docs.groupdocs.com/viewer/java/render-presentations/) bakın.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isRenderToPureHtml()](#isRenderToPureHtml--) | Sunum belgeleri için yeni bir HTML render modunu etkinleştirir. |
|
|  | [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Sunum belgeleri için yeni bir HTML render modunu etkinleştirir. |
|
|  | [isRenderHeaderFooterPlaceholders()](#isRenderHeaderFooterPlaceholders--) | Slaytın başlık ve altbilgisindeki yer tutucuların render edilmesini etkinleştirir. |
|
|  | [setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)](#setRenderHeaderFooterPlaceholders-boolean-) | Slaytın başlık ve altbilgisindeki yer tutucuların render edilmesini etkinleştirir. |
|
|  | [getResolution()](#getResolution--) | Sunum içindeki görüntüler için çözünürlük (yalnızca HTML/PDF render için). |
|
|  | [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | Sunum içindeki görüntüler için çözünürlük (yalnızca HTML/PDF render için). |
|
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Sunum belgeleri için yeni bir HTML render modunu etkinleştirir.


Bu modda, Sunum dosyaları SVG görüntüsü olmadan saf HTML/CSS işaretlemesine render edilir.
Varsayılan olarak, bu özellik devre dışı bırakılmıştır (false). Bu seçenek etkinleştirilmezse mevcut SVG tabanlı HTML renderlayıcı kullanılır.


**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Sunum belgeleri için yeni bir HTML render modunu etkinleştirir.


Bu modda, Sunum dosyaları SVG görüntüsü olmadan saf HTML/CSS işaretlemesine render edilir.
Varsayılan olarak, bu özellik devre dışı bırakılmıştır (false). Bu seçenek etkinleştirilmezse mevcut SVG tabanlı HTML renderlayıcı kullanılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### isRenderHeaderFooterPlaceholders() {#isRenderHeaderFooterPlaceholders--}
```
public boolean isRenderHeaderFooterPlaceholders()
```


Slaytın başlık ve altbilgisindeki yer tutucuların render edilmesini etkinleştirir. Varsayılan olarak devre dışı (false). Bu seçenek, sunumların tüm 4 render modunda geçerlidir: HTML, PDF, PNG ve JPEG. Saf HTML/CSS işaretlemesine render ederken uygulanmaz.


**Returns:**
boolean
### setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders) {#setRenderHeaderFooterPlaceholders-boolean-}
```
public void setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)
```


Slaytın başlık ve altbilgisindeki yer tutucuların render edilmesini etkinleştirir. Varsayılan olarak devre dışı (false). Bu seçenek, sunumların tüm 4 render modunda geçerlidir: HTML, PDF, PNG ve JPEG. Saf HTML/CSS işaretlemesine render ederken uygulanmaz.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderHeaderFooterPlaceholders | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Sunum içindeki görüntüler için çözünürlük (yalnızca HTML/PDF render için).


Kod örneği için [belgelere](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution) bakın.


**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


Sunum içindeki görüntüler için çözünürlük (yalnızca HTML/PDF render için).


Kod örneği için [belgelere](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

