---
title: "ViewOptions"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Renderleme seçeneklerini içerir."
type: docs
weight: 35
url: /tr/nodejs-java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

Renderleme seçeneklerini içerir.

ViewOptions sınıfı, BaseViewOptions sınıfını genişletir ve GroupDocs.Viewer bileşenindeki render seçenekleri için temel sınıf olarak hizmet verir. Çeşitli belge türlerini farklı formatlara render etmek için kullanılabilecek ortak ayarları ve parametreleri kapsar.

***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getWatermark()](#getWatermark--) | Her sayfaya uygulanan metin filigranını alır. |
| [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | Her sayfaya uygulanacak metin filigranını ayarlar. |
| [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | Belirtilen sayfaya saat yönünde bir dönüş uygular. |
| [getPageRotations()](#getPageRotations--) | Sayfa dönüşlerini alır. |
| [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | Örneği sadece boş olup olmadığını kontrol etmek için oluşturmaktan kaçınmak amacıyla |
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


Her sayfaya uygulanan metin filigranını alır.

Hem \#setWatermark(Watermark).setWatermark(Watermark) hem de \#getPageRotations().getPageRotations() belirtilmişse, filigran döndürülmüş sayfalara uygulanır. Ayrıntılar için [documentation][] belgesine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.
### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


Her sayfaya uygulanacak metin filigranını ayarlar.

Hem  ViewOptions.Watermark  hem de \#getPageRotations().getPageRotations() belirtilmişse, filigran döndürülmüş sayfalara uygulanır. Ayrıntılar için [documentation][] belgesine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Watermark](../../com.groupdocs.viewer.options/watermark) | Ayarlanacak metin filigranı. |

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


Belirtilen sayfaya saat yönünde bir dönüş uygular.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber | int | Sayfa numarası, 0'dan kesinlikle büyük olmalıdır. |
| rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | Dönüş değeri. |

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


Sayfa dönüşlerini alır.

Eğer hem [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions\#setWatermark-Watermark-) hem de getPageRotations() belirtilmişse, filigran döndürülmüş sayfalara uygulanacaktır. Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> - sayfa numaralarını anahtar ve karşılık gelen dönüşlerini değer olarak içeren bir harita.
### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


Örneği sadece boş olup olmadığını kontrol etmek için oluşturmaktan kaçınmak amacıyla

**Returns:**
boolean
