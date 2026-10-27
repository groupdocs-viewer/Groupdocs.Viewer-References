---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Bu sınıfı, çıktı PDF dosyasına uygulanacak PDF optimizasyon seçeneklerini belirtmek için kullanın."
type: docs
weight: 21
url: /tr/nodejs-java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

Bu sınıfı, çıktı PDF dosyasına uygulanacak PDF optimizasyon seçeneklerini belirtmek için kullanın.

Bu optimizasyon seçenekleri, PDF'ye dışa aktarma için desteklenen tüm giriş dosya formatları için desteklenir. Ayrıntılar ve kod örnekleri için bu [page][] ve alt sayfalarına bakın.

Örnek kullanım:

```

 try (Viewer viewer = new Viewer("sample.docx")) {
     PdfViewOptions viewOptions = new PdfViewOptions();
     viewOptions.setPdfOptimizationOptions(new PdfOptimizationOptions());
     viewOptions.getPdfOptimizationOptions().setLinearize(true);
     viewOptions.getPdfOptimizationOptions().setRemoveAnnotations(true);
     viewOptions.getPdfOptimizationOptions().setRemoveFormFields(true);
     viewOptions.getPdfOptimizationOptions().setConvertToGrayScale(true);
     viewOptions.getPdfOptimizationOptions().setSubsetFonts(true);
     viewOptions.getPdfOptimizationOptions().setCompressImages(true);
     viewOptions.getPdfOptimizationOptions().setImageQuality(50);
     viewOptions.getPdfOptimizationOptions().setResizeImages(true);
     viewOptions.getPdfOptimizationOptions().setMaxResolution(50);
     viewOptions.getPdfOptimizationOptions().setRemovePrivateInfo(true);
     viewOptions.getPdfOptimizationOptions().setUnembedFonts(true);
     viewOptions.getPdfOptimizationOptions().setLinkDuplicateStreams(true);
     viewOptions.getPdfOptimizationOptions().setAllowReusePageContent(true);

     viewer.view(viewOptions);
 }
 
```


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | MaxResolution seçeneği için varsayılan değeri 300 ve ImageQuality seçeneği için 100 olarak ayarlar. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isLinearize()](#isLinearize--) | Çıktı PDF dosyasının çevrimiçi bir web tarayıcısı ile görüntülenmesi için optimizasyonunu etkinleştirir. |
| [setLinearize(boolean linearize)](#setLinearize-boolean-) | Çıktı PDF'nin çevrimiçi tarama için optimize edilip edilmeyeceğini ayarlar. |
| [isRemoveAnnotations()](#isRemoveAnnotations--) | Ek açıklamalar gereksiz olduğunda silinebilir. |
| [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | PDF'den gereksiz ek açıklamaların kaldırılıp kaldırılmayacağını ayarlar. |
| [isRemoveFormFields()](#isRemoveFormFields--) | PDF belgesi AcroForm'lar içeriyorsa, form alanlarını düzleştirerek dosya boyutunu azaltmayı deneyebiliriz. |
| [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | PDF'den form alanlarının kaldırılıp kaldırılmayacağını ayarlar. |
| [isConvertToGrayScale()](#isConvertToGrayScale--) | PDF dosyası Metin, Görüntü, Ek, Ek açıklamalar, Grafikler ve diğer nesnelerden oluşur. |
| [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | PDF'nin gri tonlamaya dönüştürülüp dönüştürülmeyeceğini ayarlar. |
| [isSubsetFonts()](#isSubsetFonts--) | Sayfada metni görüntülemek için kullanılan her yazı tipi, yazı tipi karakterleri için bir glif kümesi içerir. |
| [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | PDF'deki yazı tiplerinin alt küme oluşturulup oluşturulmayacağını ayarlar. |
| [isCompressImages()](#isCompressImages--) | Kaynak PDF dosyası görüntüler içeriyorsa, görüntüleri sıkıştırmayı ve kalitelerini ayarlamayı düşünün. |
| [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | PDF'deki görüntülerin sıkıştırılıp sıkıştırılmayacağını ayarlar. |
| [getImageQuality()](#getImageQuality--) | Kaynak PDF dosyası görüntüler içeriyorsa, görüntüleri sıkıştırmayı ve kalitelerini ayarlamayı düşünün. |
| [setImageQuality(int imageQuality)](#setImageQuality-int-) | PDF'deki görüntüleri sıkıştırmak için görüntü kalitesini ayarlar. |
| [isResizeImages()](#isResizeImages--) | Görüntüleri daha düşük çözünürlükte yeniden boyutlandırmak için CompressImages seçeneğiyle birlikte kullanılabilir. |
| [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | PDF'deki görüntülerin yeniden boyutlandırılıp boyutlandırılmayacağını ayarlar. |
| [getMaxResolution()](#getMaxResolution--) | Görüntüleri daha düşük çözünürlükte yeniden boyutlandırmak için CompressImages seçeneğiyle birlikte kullanılabilir. |
| [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | PDF'deki görüntüleri yeniden boyutlandırmak için maksimum çözünürlüğü ayarlar. |
| [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Daha küçük çıktı dosyası boyutu için Excel çalışma sayfalarının kenar çizgilerini ve yazı tiplerini optimize eder. |
| [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | PDF'deki çalışma sayfalarının optimize edilip edilmeyeceğini ayarlar. |
| [isRemovePrivateInfo()](#isRemovePrivateInfo--) | Doğru olarak ayarlanırsa özel bilgileri (sayfa parça bilgisi) kaldırır. |
| [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | PDF'den özel bilgilerin kaldırılıp kaldırılmayacağını ayarlar. |
| [isUnembedFonts()](#isUnembedFonts--) | Belge gömülü yazı tipleri kullanıyorsa, tüm yazı tipi verilerinin belgeye yerleştirildiği anlamına gelir. |
| [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | PDF'deki gömülü yazı tiplerinin gömülmesinin kaldırılıp kaldırılmayacağını ayarlar. |
| [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | Bazen bir belge, birkaç aynı kaynak akışı (örneğin görüntüler) içerir. |
| [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | PDF'deki yinelenen akışların bağlanıp bağlanmayacağını ayarlar. |
| [isAllowReusePageContent()](#isAllowReusePageContent--) | Bu özellik doğru olarak ayarlanırsa, aynı sayfalar için belgeyi optimize ederken sayfa içeriği yeniden kullanılacaktır. |
| [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | PDF içinde sayfa içeriğinin yeniden kullanılmasına izin verilip verilmeyeceğini ayarlar. |
| [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | Bazen bir belge kullanılmayan kaynak akışları içerir. |
| [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | PDF'den kullanılmayan akışların kaldırılıp kaldırılmayacağını ayarlar. |
| [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | Bir PDF belgesi bazen, belgede başka hiçbir nesne tarafından referans edilmeyen PDF nesnelerini içerir. |
| [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | PDF'den kullanılmayan nesnelerin kaldırılıp kaldırılmayacağını ayarlar. |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


MaxResolution seçeneği için varsayılan değeri 300 ve ImageQuality seçeneği için 100 olarak ayarlar.

Ayrıntılar ve kod örnekleri için, bu [page][] ve alt öğelerine bakın.


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/

### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


Çıktı PDF dosyasının çevrimiçi bir web tarayıcısı ile görüntülenmesi için optimizasyonunu etkinleştirir.

Kod örneği için, bu [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Returns:**
boolean -  true  eğer çıktı PDF'i çevrimiçi gezinme için optimize edilmişse,  false  aksi takdirde.
### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


Çıktı PDF'nin çevrimiçi tarama için optimize edilip edilmeyeceğini ayarlar.

Kod örneği için, bu [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| linearize | boolean | true  çıktı PDF'i çevrimiçi gezinme için optimize etmek için,  false  aksi takdirde. |

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


Ek açıklamalar gereksiz olduğunda silinebilir. Gerektiğinde ancak ek düzenleme gerektirmiyorsa düzleştirilebilir. Bu dosya boyutunu azaltacaktır.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Returns:**
boolean -  true  eğer ek açıklamalar kaldırıldıysa,  false  aksi takdirde.
### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


PDF'den gereksiz ek açıklamaların kaldırılıp kaldırılmayacağını ayarlar.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| removeAnnotations | boolean | true  gereksiz ek açıklamaları kaldırmak için,  false  aksi takdirde. |

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


PDF belgesi AcroForm'lar içeriyorsa, form alanlarını düzleştirerek dosya boyutunu azaltmayı deneyebiliriz.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Returns:**
boolean -  true  eğer form alanları kaldırıldıysa,  false  aksi takdirde.
### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


PDF'den form alanlarının kaldırılıp kaldırılmayacağını ayarlar.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| removeFormFields | boolean | true  form alanlarını kaldırmak için,  false  aksi takdirde. |

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


PDF dosyası Metin, Görüntü, Ek, Ek açıklamalar, Grafikler ve diğer nesnelerden oluşur. PDF'yi RGB renk uzayından gri tonlamaya dönüştürme ihtiyacıyla karşılaşabilirsiniz; bu, PDF dosyalarını yazdırırken daha hızlı olmasını sağlar. Ayrıca dosya gri tonlamaya dönüştürüldüğünde belgenin boyutu da azalır, ancak bu değişiklikle belgenin kalitesi düşebilir. Şu anda bu özellik, Adobe Acrobat'ın Pre-Flight özelliği tarafından desteklenmektedir.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Returns:**
boolean -  true  eğer PDF gri tonlamaya dönüştürüldüyse,  false  aksi takdirde.
### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


PDF'nin gri tonlamaya dönüştürülüp dönüştürülmeyeceğini ayarlar.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| convertToGrayScale | boolean | true  PDF'i gri tonlamaya dönüştürmek için,  false  aksi takdirde. |

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


Sayfada metni görüntülemek için kullanılan her yazı tipi, karakterler için bir dizi glif içerir. PDF spesifikasyonu "yazı tipi alt kümesi"ni destekler; yani yalnızca kullanılan glifleri içeren bir yazı tipi. Bu, metin güncellenmesi gerektiğinde (gerekli glifler yazı tipinde bulunmadığından) sorunlara yol açabilir, ancak değişmesi planlanmayan belgeler için boyutu azaltmaya olanak tanır.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Returns:**
boolean -  true  eğer yazı tipleri alt küme haline getirildiyse,  false  aksi takdirde.
### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


PDF'deki yazı tiplerinin alt küme oluşturulup oluşturulmayacağını ayarlar.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subsetFonts | boolean | true  yazı tiplerini alt küme haline getirmek için,  false  aksi takdirde. |

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


Kaynak PDF dosyası görüntüler içeriyorsa, görüntüleri sıkıştırmayı ve kalitelerini ayarlamayı düşünün. Görüntü sıkıştırmasını etkinleştirmek için bu seçeneği true olarak ayarlayın. Bir belgedeki tüm görüntüler yeniden sıkıştırılacaktır. Sıkıştırma, kalite yüzdesi değeri olan ImageQuality özelliği ile tanımlanır. %100 değişmemiş kalite demektir. Görüntü kalitesini düşürmek için ImageQuality özelliğini 100'den az bir değere ayarlayın.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
boolean -  true  eğer görüntüler sıkıştırıldıysa,  false  aksi takdirde.
### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


PDF'deki görüntülerin sıkıştırılıp sıkıştırılmayacağını ayarlar.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| compressImages | boolean | true  görüntüleri sıkıştırmak için,  false  aksi takdirde. |

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


Kaynak PDF dosyası görüntüler içeriyorsa, görüntüleri sıkıştırmayı ve kalitelerini ayarlamayı düşünün. Görüntü sıkıştırmasını etkinleştirmek için CompressImages seçeneğini true olarak ayarlayın. Bir belgedeki tüm görüntüler yeniden sıkıştırılacaktır. Sıkıştırma, yüzde olarak kalite değeri olan ImageQuality özelliği ile tanımlanır. %100 değişmemiş kalite demektir. Görüntü kalitesini düşürmek için CompressImages seçeneğini true ve ImageQuality özelliğini 100'den az bir değere ayarlayın.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
int - görüntü kalitesi (1 ile 100 arasında değer).
### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


PDF'deki görüntüleri sıkıştırmak için görüntü kalitesini ayarlar.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageQuality | int | görüntü kalitesi (1 ile 100 arasında değer). |

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


CompressImages seçeneği ile birlikte, görüntüleri daha düşük çözünürlükte yeniden boyutlandırmak için kullanılabilir. Bu durumda, CompressImage'i true, ResizeImages'i true ve MaxResolution'ı uygun değere ayarlamalıyız.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
boolean -  true  eğer görüntüler yeniden boyutlandırıldıysa,  false  aksi takdirde.
### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


PDF'deki görüntülerin yeniden boyutlandırılıp boyutlandırılmayacağını ayarlar.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resizeImages | boolean | true  görüntüleri yeniden boyutlandırmak için,  false  aksi takdirde. |

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


CompressImages seçeneği ile birlikte, görüntüleri daha düşük çözünürlükte yeniden boyutlandırmak için kullanılabilir. Bu durumda, CompressImage'i true, ResizeImages'i true ve MaxResolution'ı uygun değere ayarlamalıyız.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
int - görüntüler için maksimum çözünürlük.
### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


PDF'deki görüntüleri yeniden boyutlandırmak için maksimum çözünürlüğü ayarlar.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| maxResolution | int | görüntüler için maksimum çözünürlük. |

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Daha küçük çıktı dosyası boyutu için Excel çalışma sayfalarının kenar çizgilerini ve yazı tiplerini optimize eder.

*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Returns:**
boolean -  true  eğer elektronik tablolar optimize edildiyse,  false  aksi takdirde.
### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


PDF'deki çalışma sayfalarının optimize edilip edilmeyeceğini ayarlar.

Kod örneği için, bu [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| optimizeSpreadsheets | boolean | true  elektronik tabloları optimize etmek için,  false  aksi takdirde. |

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


Doğru olarak ayarlanırsa özel bilgileri (sayfa parça bilgisi) kaldırır.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  eğer özel bilgiler kaldırıldıysa,  false  aksi takdirde.
### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


PDF'den özel bilgilerin kaldırılıp kaldırılmayacağını ayarlar.

***Note:** The default value is  false .*

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| removePrivateInfo | boolean | true  özel bilgileri kaldırmak için,  false  aksi takdirde. |

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


Belge gömülü yazı tipleri kullanıyorsa, tüm yazı tipi verileri belgeye yerleştirilir. Avantajı, belgenin kullanıcı\u2019s makinesinde yazı tipi yüklü olsun ya da olmasın görüntülenebilmesidir. Ancak gömülü yazı tipleri belgeyi büyütür. unembed fonts yöntemi tüm gömülü yazı tiplerini kaldırır. Bu, belge boyutunu azaltır ancak doğru yazı tipi yüklü değilse belge okunamaz hale gelebilir.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  eğer gömülü yazı tipleri kaldırıldıysa,  false  aksi takdirde.
### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


PDF'deki gömülü yazı tiplerinin gömülmesinin kaldırılıp kaldırılmayacağını ayarlar.

***Note:** The default value is  false .*

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| unembedFonts | boolean | true  gömülü yazı tiplerini kaldırmak için,  false  aksi takdirde. |

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


Bazen bir belge, birkaç aynı kaynak akışı (örneğin görüntüler) içerir. Bu, örneğin bir belge kendisiyle birleştirildiğinde meydana gelebilir. Çıktı belgesi aynı kaynak akışının iki bağımsız kopyasını içerir. Tüm kaynak akışlarını analiz eder ve karşılaştırırız. Akışlar yinelendiğinde birleştirilir, yani yalnızca bir kopya kalır, referanslar uygun şekilde değiştirilir ve nesnenin kopyaları kaldırılır. Bazen bu belge boyutunu azaltır.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  eğer yinelenen akışlar bağlanmışsa,  false  aksi takdirde.
### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


PDF'deki yinelenen akışların bağlanıp bağlanmayacağını ayarlar.

***Note:** The default value is  false .*

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| linkDuplicateStreams | boolean | true  yinelenen akışları bağlamak için,  false  aksi takdirde. |

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


Bu özellik doğru olarak ayarlanırsa, aynı sayfalar için belgeyi optimize ederken sayfa içeriği yeniden kullanılacaktır.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  eğer sayfa içeriği yeniden kullanılıyorsa,  false  aksi takdirde.
### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


PDF içinde sayfa içeriğinin yeniden kullanılmasına izin verilip verilmeyeceğini ayarlar.

***Note:** The default value is  false .*

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| allowReusePageContent | boolean | true  sayfa içeriğinin yeniden kullanılmasına izin vermek için,  false  aksi takdirde. |

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


Bazen bir belge kullanılmayan kaynak akışları içerir. Bu akışlar, bir sayfanın kaynak sözlüğünden referans alındıkları için \u201cunused objects\u201d (kullanılmayan nesneler) değildir. Bu, bir görüntünün sayfadan kaldırılıp sayfa kaynaklarından kaldırılmadığı durumlarda meydana gelebilir. Ayrıca, sayfalar belgeden çıkarıldığında ve belge sayfalarının \u201ccommon\u201d (ortak) kaynakları, yani aynı Resources nesnesi olduğunda bu durum sıkça görülür. Sayfa içerikleri, bir kaynak akışının kullanılıp kullanılmadığını belirlemek için analiz edilir. Kullanılmayan akışlar kaldırılır. Bazen bu belge boyutunu azaltır.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  eğer kullanılmayan akışlar kaldırıldıysa,  false  aksi takdirde.
### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


PDF'den kullanılmayan akışların kaldırılıp kaldırılmayacağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| removeUnusedStreams | boolean | true  kullanılmayan akışları kaldırmak için,  false  aksi takdirde. |

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


Bir PDF belgesi bazen, belgede başka hiçbir nesneden referans alınmayan PDF nesnelerini içerir. Bu, örneğin bir sayfa belge sayfa ağacından kaldırıldığında ancak sayfa nesnesi kendisi isn\u2019t kaldırılmadığında meydana gelebilir. Bu nesnelerin kaldırılması belgeyi geçersiz kılmaz, ancak belgeyi küçültür.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  eğer kullanılmayan nesneler kaldırıldıysa,  false  aksi takdirde.
### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


PDF'den kullanılmayan nesnelerin kaldırılıp kaldırılmayacağını ayarlar.

***Note:** The default value is  false .*

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| removeUnusedObjects | boolean | true  kullanılmayan nesneleri kaldırmak için,  false  aksi takdirde. |

