---
title: "PdfOptions"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "PDF belgelerini renderleme seçeneklerini sağlar."
type: docs
weight: 22
url: /tr/nodejs-java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

PDF belgelerini renderleme seçeneklerini sağlar.

PdfOptions sınıfı, GroupDocs.Viewer bileşeninde PDF belgelerinin render edilmesini kontrol etmek için kullanılabilecek çeşitli ayarları ve parametreleri kapsar. Ayrıntılar için [belge][].

Örnek kullanım:

```

 PdfOptions options = new PdfOptions();
 options.setDisableCharsGrouping(true);
 options.setRenderTextAsImage(true);
 options.setEnableFontHinting(true);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setPdfOptions(options);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | PdfOptions sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isDisableCopyProtection()](#isDisableCopyProtection--) | HTML'ye render edilirken içerik kopyalama korumasını kapatır. |
| [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | HTML'ye render edilirken içerik kopyalama korumasını kapatır. |
| [isRenderTextAsImage()](#isRenderTextAsImage--) | Kaynağın metninin HTML'de görüntü olarak render edilip edilmediğini belirler. |
| [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Kaynağın metninin HTML'de görüntü olarak render edilip edilmeyeceğini ayarlar. |
| [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Sayfa render edilirken karakter konumlandırması sırasında maksimum hassasiyeti korumak için karakter gruplandırmasının devre dışı bırakılıp bırakılmadığını kontrol eder. |
| [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Sayfa render edilirken karakter konumlandırması sırasında maksimum hassasiyeti sağlamak için karakter gruplandırmasını devre dışı bırakma seçeneğini ayarlar. |
| [isEnableLayeredRendering()](#isEnableLayeredRendering--) | HTML'ye render edilirken metin ve grafiklerin orijinal PDF belgesindeki z-sırasını takip edip etmeyeceğini kontrol eder. |
| [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | HTML'ye render edilirken metin ve grafiklerin orijinal PDF belgesindeki z-sırasına göre render edilmesini etkinleştirir veya devre dışı bırakır. |
| [isEnableFontHinting()](#isEnableFontHinting--) | Yazı tipi ipucu (hinting) özelliğinin etkin olup olmadığını belirler. |
| [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Yazı tipi ipucu özelliğini etkinleştirir. |
| [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Kaynak PDF belgesindeki sayfa boyutuyla aynı piksel boyutunda sayfaların render edilmesini etkinleştirir. |
| [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Kaynak PDF belgesindeki sayfa boyutuyla aynı piksel boyutunda sayfaların render edilmesini etkinleştirir. |
| [getImageQuality()](#getImageQuality--) | HTML'ye render edilirken görüntü kaynakları için çıktı görüntü kalitesini alır. |
| [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | HTML'ye render edilirken görüntü kaynakları için çıktı görüntü kalitesini ayarlar. |
| [isFixedLayout()](#isFixedLayout--) | PDF sabit bir format olduğundan tüm öğeler sayfada belirli bir konuma sahiptir. |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF sabit bir format olduğundan tüm öğeler sayfada belirli bir konuma sahiptir. |
| [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Çıktı kalitesini artırmak için çıktı HTML belgesindeki her görüntüyü SVG etiketiyle sarmak için bu seçeneği etkinleştirin. |
| [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Çıktı kalitesini artırmak için çıktı HTML belgesindeki her görüntüyü SVG etiketiyle sarmak için bu seçeneği etkinleştirin. |
| [isFixLinkIssue()](#isFixLinkIssue--) | Tüm HTML sayfa içeriği bir bağlantı olduğunda sorunu düzeltmeye çalışır. |
| [setFixLinkIssue(boolean fixLinkIssue)](#setFixLinkIssue-boolean-) | Tüm HTML sayfa içeriği bir bağlantı olduğunda sorunu düzeltmeye çalışır. |
| [isAnalyzeFonts()](#isAnalyzeFonts--) | Metindeki tüm karakterlerin görüntülenebilmesi için gerektiğinde yazı tiplerini değiştirir. |
| [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | Metindeki tüm karakterlerin görüntülenebilmesi için gerektiğinde yazı tiplerini değiştirir. |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Mevcut XPS/OXPS belgesindeki tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırak. |
| [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Mevcut XPS/OXPS belgesindeki tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırakmak üzere bayrağı ayarlayın. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


PdfOptions sınıfının yeni bir örneğini başlatır.

### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


HTML'ye render edilirken içerik kopyalama korumasını kapatır.

Metin ve görsellerin kopyalanmasına karşı koruma içeren PDF dosyalarını HTML'ye dönüştürürken, GroupDocs.Viewer HTML BODY etiketine 'inert' HTML özelliğini ekler. Bu seçeneğin varsayılan değeri false dir.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


HTML'ye render edilirken içerik kopyalama korumasını kapatır.

Metin ve görsellerin kopyalanmasına karşı koruma içeren PDF dosyalarını HTML'ye dönüştürürken, GroupDocs.Viewer HTML BODY etiketine 'inert' HTML özelliğini ekler. Bu seçeneğin varsayılan değeri false dir.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Kaynağın metninin HTML'de görüntü olarak render edilip edilmediğini belirler.

Bu seçenek true olarak ayarlandığında, metin çıktı HTML'sinde bir görüntü olarak işlenir. Metni seçilemez hâle getirmek veya karakter render'ını düzeltmek ve HTML'nin PDF gibi görünmesini sağlamak için bu seçeneği etkinleştirin. Bu seçenek HTML'ye dönüştürme sırasında desteklenir.

***Note:** The default value is  false .*

**Returns:**
boolean - true ise metin HTML'de bir görüntü olarak işlenir, false ise aksi halde.
### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Kaynağın metninin HTML'de görüntü olarak render edilip edilmeyeceğini ayarlar.

Bu seçenek true olarak ayarlandığında, metin çıktı HTML'sinde bir görüntü olarak işlenir. Metni seçilemez hâle getirmek veya karakter render'ını düzeltmek ve HTML'nin PDF gibi görünmesini sağlamak için bu seçeneği etkinleştirin. Bu seçenek HTML'ye dönüştürme sırasında desteklenir.

***Note:** The default value is  false .*

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderTextAsImage | boolean | true metni HTML'de bir görüntü olarak işlemek için, false aksi halde. |

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Sayfa işlenirken karakter konumlandırmasında maksimum hassasiyeti korumak için karakter gruplandırmasının devre dışı bırakılıp bırakılmadığını denetler. Bu seçenek etkinleştirildiğinde, karakterler herhangi bir gruplandırma olmadan işlenir ve bu da maksimum hassasiyeti sağlar.

***Note:** By default, character grouping is enabled.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Returns:**
boolean - true ise karakter gruplandırması devre dışı bırakılmıştır, false ise aksi halde.
### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Sayfa işlenirken karakter konumlandırmasında maksimum hassasiyeti sağlamak için karakter gruplandırmasını devre dışı bırakma seçeneğini ayarlar. Değer true olarak ayarlandığında bu seçenek etkinleşir ve karakter gruplandırması devre dışı bırakılır, bu da maksimum hassasiyeti temin eder.

***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | true karakter gruplandırmasını devre dışı bırakmak için, false etkinleştirmek için. |

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Metin ve grafiklerin HTML'ye dönüştürülürken orijinal PDF belgesindeki z-sırasını takip edip etmeyeceğini denetler. Bu seçenek true döndürülerek etkinleştirildiğinde, metin ve grafikler orijinal PDF belgesindeki z-sırasına göre işlenir.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Returns:**
boolean - true ise katmanlı render etkin, false ise aksi halde.
### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


HTML'ye render edilirken metin ve grafiklerin orijinal PDF belgesindeki z-sırasına göre render edilmesini etkinleştirir veya devre dışı bırakır.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | true katmanlı render'ı etkinleştirmek için, false devre dışı bırakmak için. |

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Yazı tipi ipucu (font hinting) özelliğinin etkin olup olmadığını belirler. Font hinting, bir kontur yazı tipinin görüntülenmesini ayarlar. Bu seçenek yalnızca kaynak belgede kullanılan TrueType (TTF) yazı tipleri için desteklenir.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Returns:**
boolean - true ise font hinting etkin, false ise aksi halde.
### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Font hinting'i etkinleştirir. Font hinting, bir kontur yazı tipinin görüntülenmesini ayarlar ve yalnızca kaynak belgede kullanılan TrueType (TTF) yazı tipleri için desteklenir.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | true font hinting'i etkinleştirmek için, false devre dışı bırakmak için. |

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Kaynak PDF belgesindeki sayfa boyutuyla aynı piksel boyutunda sayfaların render edilmesini etkinleştirir.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Returns:**
boolean - true ise seçenek etkin, false ise aksi halde.
### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Kaynak PDF belgesindeki sayfa boyutuyla aynı piksel boyutunda sayfaların render edilmesini etkinleştirir.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderOriginalPageSize | boolean | true orijinal sayfa boyutuyla render etmeyi etkinleştirmek için, false aksi halde. |

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


HTML'ye dönüştürürken görüntü kaynakları için çıktı görüntü kalitesini alır. Varsayılan değer Düşük'tür.

Bu seçenek true olarak ayarlandığında, GroupDocs.Viewer metni HTML çıktısında bir görüntü olarak işler. Bu, metnin seçilemez olmasını sağlar ve karakter render'ını iyileştirerek HTML'de PDF benzeri bir görünüm elde eder. Varsayılan değer false'tur. Bu seçenek HTML'ye render için mevcuttur. Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.
### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


HTML'ye dönüştürürken görüntü kaynakları için çıktı görüntü kalitesini ayarlar. Varsayılan değer Düşük'tür.

Bu seçenek true olarak ayarlandığında, GroupDocs.Viewer metni HTML çıktısında bir görüntü olarak işler. Bu, metnin seçilemez olmasını sağlar ve karakter render'ını iyileştirerek HTML'de PDF benzeri bir görünüm elde eder. Varsayılan değer false'tur. Bu seçenek HTML'ye render için mevcuttur. Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | HTML'ye render edildiğinde görüntü kaynakları için çıktı görüntü kalitesi. |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF sabit bir format olduğu için tüm öğeler sayfada belirli bir konuma sahiptir. Çıktı HTML'nin kaynak PDF ile aynı görünmesini sağlamak için belgeler varsayılan olarak sabit bir düzenle HTML'ye render edilir. Sabit düzenle render edildiğinde çıktı HTML sabit boyuta sahiptir, böylece öğeler pencere boyutundan bağımsız olarak aynı konumda kalır. Akışkan düzenle HTML'ye render etmek için bu özelliği false olarak ayarlayın.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Örnek kullanım:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Returns:**
boolean - sabit düzen ise true
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF sabit bir format olduğu için tüm öğeler sayfada belirli bir konuma sahiptir. Çıktı HTML'nin kaynak PDF ile aynı görünmesini sağlamak için belgeler varsayılan olarak sabit bir düzenle HTML'ye render edilir. Sabit düzenle render edildiğinde çıktı HTML sabit boyuta sahiptir, böylece öğeler pencere boyutundan bağımsız olarak aynı konumda kalır. Akışkan düzenle HTML'ye render etmek için bu özelliği false olarak ayarlayın.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Örnek kullanım:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fixedLayout | boolean | sabit düzen ise true |

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Çıktı kalitesini artırmak için çıktı HTML belgesindeki her görüntüyü SVG etiketiyle sarmak için bu seçeneği etkinleştirin.

Bu seçenek, [PDF and Page Layout file formats][] gömülü ve harici kaynaklarla HTML'ye render edilirken desteklenir.

Varsayılan olarak, PDF ve Page Layout dosyalarına render edildiğinde, tüm görüntüler tek bir PNG görüntüsü olarak render edilir. Oluşturulan PNG görüntüsü, çıktı HTML belgesinin arka planı olarak kullanılır.

Daha fazla bilgi:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Returns:**
boolean -  görüntüler SVG içinde sarılmışsa true, aksi takdirde false.
### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Çıktı kalitesini artırmak için çıktı HTML belgesindeki her görüntüyü SVG etiketiyle sarmak için bu seçeneği etkinleştirin.

Bu seçenek, [PDF and Page Layout file formats][] gömülü ve harici kaynaklarla HTML'ye render edilirken desteklenir.

Varsayılan olarak, PDF ve Page Layout dosyalarına render edildiğinde, tüm görüntüler tek bir PNG görüntüsü olarak render edilir. Oluşturulan PNG görüntüsü, çıktı HTML belgesinin arka planı olarak kullanılır.

Daha fazla bilgi:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| wrapImagesInSvg | boolean | görüntüler SVG içinde sarılacaksa true, aksi takdirde false. |

### isFixLinkIssue() {#isFixLinkIssue--}
```
public boolean isFixLinkIssue()
```


Tüm HTML sayfa içeriği bir bağlantı olduğunda sorunu düzeltmeye çalışır. Yalnızca giriş formatı PDF ve çıkış formatı HTML (gömülü veya harici kaynaklarla) olduğunda çalışır. Varsayılan olarak devre dışı bırakılmıştır (false). Ne yaptığınızı ve neden yaptığınızı bildiğinizde yalnızca açın. Bu seçeneği açmak belge işleme süresini artırır.

**Returns:**
boolean
### setFixLinkIssue(boolean fixLinkIssue) {#setFixLinkIssue-boolean-}
```
public void setFixLinkIssue(boolean fixLinkIssue)
```


Tüm HTML sayfa içeriği bir bağlantı olduğunda sorunu düzeltmeye çalışır. Yalnızca giriş formatı PDF ve çıkış formatı HTML (gömülü veya harici kaynaklarla) olduğunda çalışır. Varsayılan olarak devre dışı bırakılmıştır (false). Ne yaptığınızı ve neden yaptığınızı bildiğinizde yalnızca açın. Bu seçeneği açmak belge işleme süresini artırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fixLinkIssue | boolean | sorun düzeltilmeli ise true, aksi takdirde false. |

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


Metindeki tüm karakterlerin görüntülenebilmesi için gerektiğinde yazı tiplerini değiştirir.

**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


Metindeki tüm karakterlerin görüntülenebilmesi için gerektiğinde yazı tiplerini değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| analyzeFonts | boolean | yazı tipleri gösterilecekse true, aksi takdirde false. |

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Mevcut XPS/OXPS belgesindeki tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırak.

Bu yazı tipiyle ilgili birçok işlem, eğer bu işlemler yazı tipinin lisansı tarafından yasaklanmışsa gerçekleştirilemez. Örneğin, bazı yazı tipleri, lisans kuralları bu yazı tipinin gömülmesini engelliyorsa bir PDF belgesine gömülemez. Bu bayrağı kullanırken dikkatli olun. Ayarlandığında, bu bayrağı ayarlayan kişinin olası lisans/yasal ihlallerden tamamen sorumlu olduğunu kabul ettiği anlamına gelir. Yani riski kendileri üstlenir. Telif hakkı yasasını ihlal etmediğinizden tamamen emin olduğunuz durumlarda bu bayrağı kullanmanız şiddetle önerilir. Varsayılan olarak false. Kod örneği için [documentation][] sayfasına bakın.

Örnek kullanım:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


Mevcut XPS/OXPS belgesindeki tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırakmak üzere bayrağı ayarlayın.

Bu yazı tipiyle ilgili birçok işlem, eğer bu işlemler yazı tipinin lisansı tarafından yasaklanmışsa gerçekleştirilemez. Örneğin, bazı yazı tipleri, lisans kuralları bu yazı tipinin gömülmesini engelliyorsa bir PDF belgesine gömülemez. Bu bayrağı kullanırken dikkatli olun. Ayarlandığında, bu bayrağı ayarlayan kişinin olası lisans/yasal ihlallerden tamamen sorumlu olduğunu kabul ettiği anlamına gelir. Yani riski kendileri üstlenir. Telif hakkı yasasını ihlal etmediğinizden tamamen emin olduğunuz durumlarda bu bayrağı kullanmanız şiddetle önerilir. Varsayılan olarak false. Kod örneği için [documentation][] sayfasına bakın.

Örnek kullanım:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

