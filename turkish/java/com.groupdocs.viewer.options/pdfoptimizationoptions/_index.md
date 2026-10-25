---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Bu sınıfı, çıktı PDF dosyasına uygulanacak PDF optimizasyon seçeneklerini belirtmek için kullanın."
type: docs
weight: 21
url: /tr/java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

Bu sınıfı, çıktı PDF dosyasına uygulanacak PDF optimizasyon seçeneklerini belirtmek için kullanın.


Bu optimizasyon seçenekleri, PDF'ye dışa aktarma için desteklenen tüm giriş dosya biçimleri için desteklenir.
Ayrıntılar ve kod örnekleri için, bu [sayfaya](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) ve alt sayfalara bakın.


Örnek kullanım:

````

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
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | MaxResolution seçeneğinin varsayılan değerini 300 ve ImageQuality seçeneğinin varsayılan değerini 100 olarak ayarlar. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isLinearize()](#isLinearize--) | Çıktı PDF dosyasının bir web tarayıcısında çevrimiçi görüntülenmesi için optimizasyonu etkinleştirir. |
|
|  | [setLinearize(boolean linearize)](#setLinearize-boolean-) | Çıktı PDF'nin bir web tarayıcısında çevrimiçi gezinme için optimize edilip edilmeyeceğini ayarlar. |
|
|  | [isRemoveAnnotations()](#isRemoveAnnotations--) | Ek açıklamalar gereksiz olduğunda silinebilir. |
|
|  | [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | PDF'den gereksiz ek açıklamaların kaldırılıp kaldırılmayacağını ayarlar. |
|
|  | [isRemoveFormFields()](#isRemoveFormFields--) | PDF belgesi AcroForm'lar içeriyorsa, form alanlarını düzleştirerek dosya boyutunu azaltmayı deneyebiliriz. |
|
|  | [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | PDF'den form alanlarının kaldırılıp kaldırılmayacağını ayarlar. |
|
|  | [isConvertToGrayScale()](#isConvertToGrayScale--) | PDF dosyası Metin, Görüntü, Ek, Ek açıklamalar, Grafikler ve diğer nesnelerden oluşur. |
|
|  | [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | PDF'nin gri tonlamaya dönüştürülüp dönüştürülmeyeceğini ayarlar. |
|
|  | [isSubsetFonts()](#isSubsetFonts--) | Sayfada metni görüntülemek için kullanılan her yazı tipi, yazı tipi karakterleri için bir glif kümesi içerir. |
|
|  | [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | PDF'deki yazı tiplerinin alt küme oluşturulup oluşturulmayacağını ayarlar. |
|
|  | [isCompressImages()](#isCompressImages--) | Kaynak PDF dosyası görüntüler içeriyorsa, görüntüleri sıkıştırmayı ve kalitelerini ayarlamayı düşünün. |
|
|  | [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | PDF'deki görüntülerin sıkıştırılıp sıkıştırılmayacağını ayarlar. |
|
|  | [getImageQuality()](#getImageQuality--) | Kaynak PDF dosyası görüntüler içeriyorsa, görüntüleri sıkıştırmayı ve kalitelerini ayarlamayı düşünün. |
|
|  | [setImageQuality(int imageQuality)](#setImageQuality-int-) | PDF'deki görüntüleri sıkıştırmak için görüntü kalitesini ayarlar. |
|
|  | [isResizeImages()](#isResizeImages--) | Görüntüleri daha düşük çözünürlükte yeniden boyutlandırmak için CompressImages seçeneğiyle birlikte kullanılabilir. |
|
|  | [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | PDF'deki görüntülerin yeniden boyutlandırılıp boyutlandırılmayacağını ayarlar. |
|
|  | [getMaxResolution()](#getMaxResolution--) | Görüntüleri daha düşük çözünürlükte yeniden boyutlandırmak için CompressImages seçeneğiyle birlikte kullanılabilir. |
|
|  | [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | PDF'deki görüntülerin yeniden boyutlandırılması için maksimum çözünürlüğü ayarlar. |
|
|  | [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Daha küçük çıktı dosyası boyutu için Excel çalışma sayfalarının kenar çizgilerini ve yazı tiplerini optimize eder. |
|
|  | [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | PDF'deki çalışma sayfalarının optimize edilip edilmeyeceğini ayarlar. |
|
|  | [isRemovePrivateInfo()](#isRemovePrivateInfo--) | Doğru olarak ayarlanırsa özel bilgileri (sayfa parça bilgisi) kaldırır. |
|
|  | [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | PDF'den özel bilgilerin kaldırılıp kaldırılmayacağını ayarlar. |
|
|  | [isUnembedFonts()](#isUnembedFonts--) | Belge gömülü yazı tipleri kullanıyorsa, tüm yazı tipi verilerinin belgeye yerleştirildiği anlamına gelir. |
|
|  | [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | PDF'deki gömülü yazı tiplerinin gömülmesini kaldırıp kaldırmayacağını ayarlar. |
|
|  | [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | Bazen bir belge, birkaç aynı kaynak akışı (örneğin görüntüler) içerir. |
|
|  | [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | PDF'deki yinelenen akışların bağlanıp bağlanmayacağını ayarlar. |
|
|  | [isAllowReusePageContent()](#isAllowReusePageContent--) | Bu özellik true olarak ayarlanırsa, belge aynı sayfalar için optimize edilirken sayfa içeriği yeniden kullanılacaktır. |
|
|  | [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | PDF'de sayfa içeriğinin yeniden kullanılmasına izin verilip verilmeyeceğini ayarlar. |
|
|  | [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | Bazen bir belge kullanılmayan kaynak akışları içerir. |
|
|  | [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | PDF'den kullanılmayan akışların kaldırılıp kaldırılmayacağını ayarlar. |
|
|  | [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | Bir PDF belgesi bazen başvurulmamış PDF nesnelerini içerir |
belgedeki herhangi bir başka nesneden.
|
|  | [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | PDF'den kullanılmayan nesnelerin kaldırılıp kaldırılmayacağını ayarlar. |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


MaxResolution seçeneğinin varsayılan değerini 300 ve ImageQuality seçeneğinin varsayılan değerini 100 olarak ayarlar.


Ayrıntılar ve kod örnekleri için, bu [sayfaya](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) ve alt sayfalara bakın.


### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


Çıktı PDF dosyasının bir web tarayıcısında çevrimiçi görüntülenmesi için optimizasyonu etkinleştirir.


Kod örneği için, bu [belgelere](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/) bakın.


**Returns:**
boolean -  true  eğer çıktı PDF'i çevrimiçi görüntüleme için optimize edilmişse,  false  aksi takdirde.

### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


Çıktı PDF'nin bir web tarayıcısında çevrimiçi gezinme için optimize edilip edilmeyeceğini ayarlar.


Kod örneği için, bu [belgelere](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | linearize | boolean | true  çıktı PDF'i çevrimiçi görüntüleme için optimize etmek için,  false  aksi takdirde. |
|

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


Ek açıklamalar gereksiz olduğunda silinebilir. Gerektiğinde ancak ek düzenleme gerektirmiyorsa düzleştirilebilir. Bu dosya boyutunu azaltacaktır.


***Note:** The default value is 
false
.*
Kod örneği için, bu [belgelere](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/) bakın.


**Returns:**
boolean -  true  eğer ek açıklamalar kaldırıldıysa,  false  aksi takdirde.

### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


PDF'den gereksiz ek açıklamaların kaldırılıp kaldırılmayacağını ayarlar.


***Note:** The default value is 
false
.*
Kod örneği için, bu [belgelere](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | removeAnnotations | boolean | true  gereksiz ek açıklamaları kaldırmak için,  false  aksi takdirde. |
|

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


PDF belgesi AcroForm'lar içeriyorsa, form alanlarını düzleştirerek dosya boyutunu azaltmayı deneyebiliriz.


***Note:** The default value is 
false
.*
Kod örneği için, bu [belgelere](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/) bakın.


**Returns:**
boolean -  true  eğer form alanları kaldırıldıysa,  false  aksi takdirde.

### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


PDF'den form alanlarının kaldırılıp kaldırılmayacağını ayarlar.


***Note:** The default value is 
false
.*
Kod örneği için, bu [belgelere](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | removeFormFields | boolean | true  form alanlarını kaldırmak için,  false  aksi takdirde. |
|

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


PDF dosyası Metin, Görüntü, Ek, Ek açıklamalar, Grafikler ve diğer nesnelerden oluşur.
PDF'yi RGB renk uzayından gri tonlamaya dönüştürme ihtiyacıyla karşılaşabilirsiniz; bu, PDF dosyalarını yazdırırken daha hızlı olmasını sağlar.
Ayrıca dosya gri tonlamaya dönüştürüldüğünde, belgenin boyutu da azalır ancak bu değişiklikle belgenin kalitesi düşebilir.
Şu anda, bu özellik Adobe Acrobat'ın Pre-Flight özelliği tarafından desteklenmektedir.


***Note:** The default value is 
false
.*
Kod örneği için, bu [belgeye](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/) bakın.


**Returns:**
boolean -  true  eğer PDF gri tonlamaya dönüştürülmüşse,  false  aksi takdirde.

### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


PDF'nin gri tonlamaya dönüştürülüp dönüştürülmeyeceğini ayarlar.


***Note:** The default value is 
false
.*
Kod örneği için, bu [belgeye](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | convertToGrayScale | boolean | true  PDF'yi gri tonlamaya dönüştürmek için,  false  aksi takdirde. |
|

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


Sayfada metni görüntülemek için kullanılan her yazı tipi, yazı tipi karakterleri için bir glif kümesi içerir.
PDF spesifikasyonu "font alt kümesi"ni destekler, yani yalnızca kullanılan glifleri içeren font.
Bu, metin güncellenmesi gerektiğinde (muhtemelen gerekli glifler fontta bulunmadığından) sorunlara yol açabilir, ancak değişmesi planlanmayan belgeler için boyutu azaltmaya olanak tanır.


***Note:** The default value is 
false
.*
Dosya gömülü fontlar kullanıyorsa, tüm font verilerini içerir. GroupDocs.Viewer, dosya boyutunu azaltmak için gömülü fontların alt kümesini oluşturabilir. Kod örneği için, bu [belgeye](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/) bakın.


**Returns:**
boolean -  true  eğer fontlar alt kümeye alındıysa,  false  aksi takdirde.

### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


PDF'deki yazı tiplerinin alt küme oluşturulup oluşturulmayacağını ayarlar.


***Note:** The default value is 
false
.*
Dosya gömülü fontlar kullanıyorsa, tüm font verilerini içerir. GroupDocs.Viewer, dosya boyutunu azaltmak için gömülü fontların alt kümesini oluşturabilir. Kod örneği için, bu [belgeye](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | subsetFonts | boolean | true  fontları alt kümeye almak için,  false  aksi takdirde. |
|

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


Kaynak PDF dosyası görüntüler içeriyorsa, görüntüleri sıkıştırmayı ve kalitelerini ayarlamayı düşünün.
Görüntü sıkıştırmasını etkinleştirmek için bu seçeneği true olarak ayarlayın. Bir belgedeki tüm görüntüler yeniden sıkıştırılacaktır.
Sıkıştırma, kalite değerini yüzde olarak belirten ImageQuality özelliği tarafından tanımlanır.
%100 değişmemiş kalite anlamına gelir. Görüntü kalitesini düşürmek için ImageQuality özelliğini 100'ün altına ayarlayın.


***Note:** The default value is 
false
.*
Bu seçeneği, diğer sıkıştırma seçeneklerine izin vermek için kullanın: #setImageQuality(int).setImageQuality(int) ve . Kod örneği için, bu [belgeye](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/) bakın.


**Returns:**
boolean -  true  eğer görüntüler sıkıştırıldıysa,  false  aksi takdirde.

### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


PDF'deki görüntülerin sıkıştırılıp sıkıştırılmayacağını ayarlar.


***Note:** The default value is 
false
.*
Bu seçeneği, diğer sıkıştırma seçeneklerine izin vermek için kullanın: #setImageQuality(int).setImageQuality(int) ve . Kod örneği için, bu [belgeye](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | compressImages | boolean | true  görüntüleri sıkıştırmak için,  false  aksi takdirde. |
|

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


Kaynak PDF dosyası görüntüler içeriyorsa, görüntüleri sıkıştırmayı ve kalitelerini ayarlamayı düşünün. Görüntü sıkıştırmasını etkinleştirmek için CompressImages seçeneğini true olarak ayarlayın. Bir belgedeki tüm görüntüler yeniden sıkıştırılacaktır. Sıkıştırma, kalite değerini yüzde olarak belirten ImageQuality özelliği tarafından tanımlanır. %100 değişmemiş kalite demektir. Görüntü kalitesini düşürmek için CompressImages seçeneğini true ve ImageQuality özelliğini 100'ün altına ayarlayın.

<br />


***Note:** The default value is 
100
.*
Görüntü kalitesini değiştirmek için, önce #setCompressImages(boolean).setCompressImages(boolean) özelliğini true olarak ayarlayın. Kod örneği için, bu [belgeye](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/) bakın.


**Returns:**
int - görüntü kalitesi (1 ile 100 arasında bir değer).

### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


PDF'deki görüntüleri sıkıştırmak için görüntü kalitesini ayarlar.


***Note:** The default value is 
100
.*
Görüntü kalitesini değiştirmek için, önce #setCompressImages(boolean).setCompressImages(boolean) özelliğini true olarak ayarlayın. Kod örneği için, bu [belgeye](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | imageQuality | int | görüntü kalitesi (1 ile 100 arasında bir değer). |
|

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


Görüntüleri daha düşük çözünürlükte yeniden boyutlandırmak için CompressImages seçeneğiyle birlikte kullanılabilir.
Bu durumda, CompressImage'ı true, ResizeImages'ı true ve MaxResolution'ı uygun değere ayarlamalıyız.


***Note:** The default value is 
false
.*
Bu seçeneği etkinleştirmek için özelliği true olarak ayarlayın. Bu seçenek, özelliğin ayarlanmasına izin verir. Kod örneği için, bu [belgeleme](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/) bağlantısına bakın.


**Returns:**
boolean -  true  eğer görüntüler yeniden boyutlandırıldıysa,  false  aksi takdirde.

### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


PDF'deki görüntülerin yeniden boyutlandırılıp boyutlandırılmayacağını ayarlar.


***Note:** The default value is 
false
.*
Bu seçeneği etkinleştirmek için özelliği true olarak ayarlayın. Bu seçenek, özelliğin ayarlanmasına izin verir. Kod örneği için, bu [belgeleme](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/) bağlantısına bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | resizeImages | boolean | true  görüntüleri yeniden boyutlandırmak için,  false  aksi takdirde. |
|

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


CompressImages seçeneğiyle birlikte, görüntüleri daha düşük bir çözünürlükte yeniden boyutlandırmak için kullanılabilir. Bu durumda, CompressImage'i true, ResizeImages'i true ve MaxResolution'ı uygun değere ayarlamalıyız.


***Note:** The default value is 
300
.*
Bu seçeneği etkinleştirmek için, #setCompressImages(boolean).setCompressImages(boolean) ve #setMaxResolution(int).setMaxResolution(int) özelliklerini true olarak ayarlayın.
Kod örneği için, bu [belgeleme](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/) bağlantısına bakın.


**Returns:**
int - görüntüler için maksimum çözünürlük.

### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


PDF'deki görüntülerin yeniden boyutlandırılması için maksimum çözünürlüğü ayarlar.


***Note:** The default value is 
300
.*
Bu seçeneği etkinleştirmek için, #setCompressImages(boolean).setCompressImages(boolean) ve #setMaxResolution(int).setMaxResolution(int) özelliklerini true olarak ayarlayın.
Kod örneği için, bu [belgeleme](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/) bağlantısına bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | maxResolution | int | görüntüler için maksimum çözünürlük. |
|

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Daha küçük çıktı dosyası boyutu için Excel çalışma sayfalarının kenar çizgilerini ve yazı tiplerini optimize eder.


*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*


***Note:** The default value is 
false
.*
Kod örneği için, bu [belgeleme](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/) bağlantısına bakın.


**Returns:**
boolean -  true  eğer elektronik tablolar optimize edildiyse,  false  aksi takdirde.

### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


PDF'deki çalışma sayfalarının optimize edilip edilmeyeceğini ayarlar.


Kod örneği için, bu [belgeleme](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/) bağlantısına bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | optimizeSpreadsheets | boolean | true  elektronik tabloları optimize etmek için,  false  aksi takdirde. |
|

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


Doğru olarak ayarlanırsa özel bilgileri (sayfa parça bilgisi) kaldırır.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  eğer özel bilgiler kaldırıldıysa,  false  aksi takdirde.

### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


PDF'den özel bilgilerin kaldırılıp kaldırılmayacağını ayarlar.


***Note:** The default value is 
false
.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | removePrivateInfo | boolean | true  özel bilgileri kaldırmak için,  false  aksi takdirde. |
|

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


Belge gömülü yazı tipleri kullanıyorsa, tüm yazı tipi verilerinin belgeye yerleştirildiği anlamına gelir.
Avantajı, belgenin kullanıcının\\u2019s makinesinde yazı tipi yüklü olsun ya da olmasın görüntülenebilir olmasıdır. Ancak yazı tiplerini gömmek belgeyi daha büyük yapar.
Gömülü yazı tiplerini kaldırma yöntemi tüm gömülü yazı tiplerini siler. Bu, belge boyutunu azaltır ancak doğru yazı tipi yüklü değilse belge okunamaz hale gelebilir.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  eğer gömülü yazı tipleri kaldırıldıysa,  false  aksi takdirde.

### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


PDF'deki gömülü yazı tiplerinin gömülmesini kaldırıp kaldırmayacağını ayarlar.


***Note:** The default value is 
false
.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | unembedFonts | boolean | true  gömülü yazı tiplerini kaldırmak için,  false  aksi takdirde. |
|

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


Bazen bir belge, birkaç aynı kaynak akışı (örneğin görüntüler) içerir.
Bu, örneğin bir belge kendisiyle birleştirildiğinde meydana gelebilir.
Çıktı belgesi aynı kaynak akışının iki bağımsız kopyasını içerir.
Tüm kaynak akışlarını analiz eder ve karşılaştırırız. Akışlar yinelendiğinde birleştirilir, yani yalnızca bir kopya kalır, referanslar uygun şekilde değiştirilir ve nesnenin kopyaları kaldırılır.
Bazen bu belge boyutunu azaltır.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  eğer yinelenen akışlar bağlanmışsa,  false  aksi takdirde.

### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


PDF'deki yinelenen akışların bağlanıp bağlanmayacağını ayarlar.


***Note:** The default value is 
false
.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | linkDuplicateStreams | boolean | true  yinelenen akışları bağlamak için,  false  aksi takdirde. |
|

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


Bu özellik true olarak ayarlanırsa, belge aynı sayfalar için optimize edilirken sayfa içeriği yeniden kullanılacaktır.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  eğer sayfa içeriği yeniden kullanılıyorsa,  false  aksi takdirde.

### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


PDF'de sayfa içeriğinin yeniden kullanılmasına izin verilip verilmeyeceğini ayarlar.


***Note:** The default value is 
false
.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | allowReusePageContent | boolean | true  sayfa içeriğinin yeniden kullanılmasına izin vermek için,  false  aksi takdirde. |
|

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


Bazen bir belge kullanılmayan kaynak akışları içerir.
Bu akışlar \\u201cunused objects\\u201d değildir çünkü bir sayfanın kaynak sözlüğünden referans alınmaktadır.
Bu, bir görüntünün sayfadan kaldırıldığı ancak sayfa kaynaklarından kaldırılmadığı durumlarda meydana gelebilir.
Ayrıca, bu durum belge sayfaları çıkarıldığında ve belge sayfalarının \\u201ccommon\\u201d kaynakları olduğunda sıkça ortaya çıkar,
yani aynı Resources nesnesi. Sayfa içerikleri, bir kaynak akışının olup olmadığını belirlemek için analiz edilir
kullanılıp kullanılmadığını belirlemek için. Kullanılmayan akışlar kaldırılır. Bazen bu belge boyutunu azaltır.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  eğer kullanılmayan akışlar kaldırılmışsa,  false  aksi takdirde.

### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


PDF'den kullanılmayan akışların kaldırılıp kaldırılmayacağını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | removeUnusedStreams | boolean | true  kullanılmayan akışları kaldırmak için,  false  aksi takdirde. |
|

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


Bir PDF belgesi bazen başvurulmamış PDF nesnelerini içerir
belgedeki herhangi bir başka nesneden. Bu, örneğin,
bir sayfa belge sayfa ağacından kaldırıldığında ancak sayfa nesnesi kendisi isn\\u2019t kaldırılmadığında.
Bu nesneleri kaldırmak belgeyi geçersiz kılmaz, aksine küçültür.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  eğer kullanılmayan nesneler kaldırılmışsa,  false  aksi takdirde.

### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


PDF'den kullanılmayan nesnelerin kaldırılıp kaldırılmayacağını ayarlar.


***Note:** The default value is 
false
.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | removeUnusedObjects | boolean | true  kullanılmayan nesneleri kaldırmak için,  false  aksi takdirde. |
|

