---
title: "ViewOptions"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "İşleme seçeneklerini içerir."
type: docs
weight: 35
url: /tr/java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

İşleme seçeneklerini içerir.


ViewOptions sınıfı, BaseViewOptions sınıfını genişletir ve render seçenekleri için temel sınıf olarak hizmet eder
GroupDocs.Viewer bileşeninde. Kullanılabilecek ortak ayarları ve parametreleri kapsar
çeşitli belge türlerini farklı formatlara dönüştürmek için.


***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | Her sayfaya uygulanan metin filigranını alır. |
|
|  | [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | Her sayfaya uygulanacak metin filigranını ayarlar. |
|
|  | [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | Belirtilen sayfaya saat yönünde bir döndürme uygular. |
|
|  | [getPageRotations()](#getPageRotations--) | Sayfa döndürmelerini alır. |
|
|  | [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | Örneği sadece boş olup olmadığını kontrol etmek için oluşturmaktan kaçınmak amacıyla |
|
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


Her sayfaya uygulanan metin filigranını alır.


Hem #setWatermark(Watermark).setWatermark(Watermark) hem de #getPageRotations().getPageRotations() belirtilmişse,
filigran döndürülmüş sayfalara uygulanacaktır.
Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/add-text-watermark/) bakın.


**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.

### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


Her sayfaya uygulanacak metin filigranını ayarlar.


Her iki durumda da
ViewOptions.Watermark
ve #getPageRotations().getPageRotations() belirtilmişse,
filigran döndürülmüş sayfalara uygulanacaktır.
Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/add-text-watermark/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Watermark](../../com.groupdocs.viewer.options/watermark) | Ayarlanacak metin filigranı. |
|

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


Belirtilen sayfaya saat yönünde bir döndürme uygular.
Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pageNumber | int | Sayfa numarası, 0'dan büyük olmalıdır. |
|
|  | rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | Döndürme değeri. |
|

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


Sayfa döndürmelerini alır.


Hem [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions#setWatermark-Watermark-) hem de
getPageRotations()
belirtilmişse,
filigran döndürülmüş sayfalara uygulanacaktır.
Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/) bakın.


**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> - sayfa numaralarını anahtar olarak ve karşılık gelen döndürmeleri değer olarak içeren bir harita.

### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


Örneği sadece boş olup olmadığını kontrol etmek için oluşturmaktan kaçınmak amacıyla


**Returns:**
boolean
