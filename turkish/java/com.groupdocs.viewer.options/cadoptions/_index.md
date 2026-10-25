---
title: "CadOptions"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "CAD çizimlerini işlemek için seçenekler sunar."
type: docs
weight: 13
url: /tr/java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

CAD çizimlerini işlemek için seçenekler sunar.


CadOptions sınıfı, kullanılabilecek çeşitli ayarları ve parametreleri kapsar
GroupDocs.Viewer bileşeninde CAD çizimlerinin oluşturulmasını kontrol etmek için.


Daha fazla bilgi ve kod örnekleri için, [Render CAD drawings and models as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-cad-drawings-and-models/) ve [Specify rendering options for CAD files](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/) bağlantılarına bakın.


Örnek kullanım:

````

 CadOptions options = CadOptions.forRenderingByWidth(256);
 options.setRenderLayouts(true);
 options.setBackgroundColor(Color.YELLOW);
 options.setLayers(Arrays.asList(
         CacheableFactory.getInstance().newLayer("Layer1"),
         CacheableFactory.getInstance().newLayer("Layer2")
 ));

 try (Viewer viewer = new Viewer("document.dwg")) {
     PdfViewOptions pdfViewOptions = new PdfViewOptions();
     pdfViewOptions.setCadOptions(options);
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Alanlar

| Alan | Açıklama |
| --- | --- |
| [WIDTH](#WIDTH) |  |
| [HEIGHT](#HEIGHT) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPc3File()](#getPc3File--) | Çiziciyle ilişkili PC3 (Plotter Configuration) dosyasını alır. |
|
|  | [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | Çiziciyle ilişkili PC3 (Plotter Configuration) dosyasını ayarlar. |
|
|  | [forRenderingByScaleFactor(double scaleFactor)](#forRenderingByScaleFactor-double-) | Yeni bir örnek başlatır |
CadOptions
ölçek faktörüne göre oluşturma sınıfı.
|
|  | [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | Yeni bir örnek başlatır |
CadOptions
genişliğe göre oluşturma sınıfı.
|
|  | [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | Yeni bir örnek başlatır |
CadOptions
yüksekliğe göre oluşturma sınıfı.
|
|  | [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | Yeni bir örnek başlatır |
CadOptions
genişlik ve yüksekliğe göre oluşturma sınıfı.
|
|  | [getScaleFactor()](#getScaleFactor--) | Oluşturma için ölçek faktörünü alır. |
|
|  | [getWidth()](#getWidth--) | Çıktı sonucunun genişliğini piksel cinsinden alır. |
|
|  | [getHeight()](#getHeight--) | Çıktı sonucunun yüksekliğini piksel cinsinden alır. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Görselin arka plan rengini alır. |
|
|  | [getBackgroundColorAsHex()](#getBackgroundColorAsHex--) | Görselin arka plan rengini alır. |
|
|  | [setBackgroundColor(Color backgroundColor)](#setBackgroundColor-java.awt.Color-) | Görselin arka plan rengini ayarlar. |
|
|  | [setBackgroundColor(String colorName)](#setBackgroundColor-java.lang.String-) | Görselin arka plan rengini ayarlar. |
|
|  | [getTiles()](#getTiles--) | Oluşturulacak çizim bölgelerini alır. |
|
|  | [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | Oluşturulacak çizim bölgelerini ayarlar. |
|
|  | [isRenderLayouts()](#isRenderLayouts--) | CAD belgesindeki düzenlerin oluşturulup oluşturulmayacağını gösterir. |
|
|  | [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | CAD belgesindeki düzenlerin oluşturulup oluşturulmayacağını ayarlar. |
|
|  | [getLayoutName()](#getLayoutName--) | Belirli düzenin render edilmesi için adını alır. |
|
|  | [setLayoutName(String value)](#setLayoutName-java.lang.String-) | Render edilecek belirli düzenin adını ayarlar. |
|
|  | [getLayers()](#getLayers--) | Render edilecek CAD çizim katmanlarını alır. |
|
|  | [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Render edilecek CAD çizim katmanlarını alır. |
|
|  | [isEnablePerformanceConversionMode()](#isEnablePerformanceConversionMode--) | Bu bayrağı true olarak ayarlamak, CAD ailesindeki tüm formatlar için özel bir performans odaklı dönüşüm modunu etkinleştirir. |
|
|  | [setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)](#setEnablePerformanceConversionMode-boolean-) | Bu bayrağı true olarak ayarlamak, CAD ailesindeki tüm formatlar için özel bir performans odaklı dönüşüm modunu etkinleştirir. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Bu CadOptions nesnesinin başka bir nesneye eşit olup olmadığını kontrol eder. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | {@inheritDoc} |
|
|  | [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | {@inheritDoc} |
|
### WIDTH {#WIDTH}
```
public static final String WIDTH
```


### HEIGHT {#HEIGHT}
```
public static final String HEIGHT
```


### getPc3File() {#getPc3File--}
```
public String getPc3File()
```


Çiziciyle ilişkili PC3 (Plotter Configuration) dosyasını alır.


**Returns:**
java.lang.String - PC3 dosya yolu.

### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


Çiziciyle ilişkili PC3 (Plotter Configuration) dosyasını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pc3File | java.lang.String | PC3 dosya yolu. |
|

### forRenderingByScaleFactor(double scaleFactor) {#forRenderingByScaleFactor-double-}
```
public static CadOptions forRenderingByScaleFactor(double scaleFactor)
```


Yeni bir örnek başlatır
CadOptions
ölçek faktörüne göre oluşturma sınıfı.


Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | scaleFactor | double | Render için ölçek faktörü. 1'den büyük değerler çıktı sonucunu büyütür, 0 ile 1 arasındaki değerler ise çıktıyı küçültür. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by scale factor.

### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


Yeni bir örnek başlatır
CadOptions
genişliğe göre oluşturma sınıfı.


Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | width | int | Çıktı sonucunun piksel cinsinden genişliği. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width.

### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


Yeni bir örnek başlatır
CadOptions
yüksekliğe göre oluşturma sınıfı.


Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | height | int | Çıktı sonucunun piksel cinsinden yüksekliği. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by height.

### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


Yeni bir örnek başlatır
CadOptions
genişlik ve yüksekliğe göre oluşturma sınıfı.


Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | width | int | Çıktı sonucunun piksel cinsinden genişliği. |
|
|  | height | int | Çıktı sonucunun piksel cinsinden yüksekliği. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width and height.

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Oluşturma için ölçek faktörünü alır.
1'den yüksek değerler çıktı sonucunu büyütür, 0 ile 1 arasındaki değerler ise çıktıyı küçültür.


**Returns:**
double - render için ölçek faktörü.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Çıktı sonucunun genişliğini piksel cinsinden alır.


**Returns:**
int - çıktı sonucunun genişliği.

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Çıktı sonucunun yüksekliğini piksel cinsinden alır.


**Returns:**
int - çıktı sonucunun yüksekliği.

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Görselin arka plan rengini alır.


**Returns:**
java.awt.Color - görüntünün arka plan rengi.

### getBackgroundColorAsHex() {#getBackgroundColorAsHex--}
```
public String getBackgroundColorAsHex()
```


Görselin arka plan rengini alır.


**Returns:**
java.lang.String - görüntünün 0xFFFFFF formatındaki arka plan rengi.

### setBackgroundColor(Color backgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color backgroundColor)
```


Görselin arka plan rengini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | backgroundColor | java.awt.Color | Görüntünün arka plan rengi. |
|

### setBackgroundColor(String colorName) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String colorName)
```


Görselin arka plan rengini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | colorName | java.lang.String | Görüntünün arka plan rengi adı. |
|

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


Oluşturulacak çizim bölgelerini alır.
***Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT) file types.
Bu
RenderLayouts
([isRenderLayouts()](../../com.groupdocs.viewer.options/cadapplications#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadapplications#setRenderLayouts-boolean-))
and
LayoutName
([getLayoutName()](../../com.groupdocs.viewer.options/cadapplications#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadorders#setLayoutName-String-)) seçenekler yoksayılır
döşemelerle render ederken.*


**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile> - render edilecek çizim bölgelerinin listesi.

### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


Oluşturulacak çizim bölgelerini ayarlar.
***Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT) file types.
Bu
RenderLayouts
([isRenderLayouts()](../../com.groupdocs.viewer.options/cadapplications#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadapplications#setRenderLayouts-boolean-))
and
LayoutName
([getLayoutName()](../../com.groupdocs.viewer.options/cadapplications#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadorders#setLayoutName-String-)) seçenekler yoksayılır
döşemelerle render ederken.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.viewer.options.Tile> | Render edilecek çizim bölgelerinin listesi. |
|

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


CAD belgesindeki düzenlerin oluşturulup oluşturulmayacağını gösterir.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
Varsayılan olarak, yalnızca Model render edilir.*


**Returns:**
boolean -  true  eğer düzenler render edilmeliyse,  false  aksi takdirde.

### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


CAD belgesindeki düzenlerin oluşturulup oluşturulmayacağını ayarlar.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
Varsayılan olarak, yalnızca Model render edilir.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  düzenleri render etmek için,  false  aksi takdirde. |
|

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


Belirli bir düzeni render etmek için adını alır. Düzen adı büyük/küçük harfe duyarlıdır.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
Varsayılan olarak, yalnızca Model render edilir.*


**Returns:**
java.lang.String - render edilecek belirli düzenin adı.

### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


Render edilecek belirli düzenin adını ayarlar. Düzen adı büyük/küçük harfe duyarlıdır.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
Varsayılan olarak, yalnızca Model render edilir.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | Render edilecek belirli düzenin adı. |
|

### getLayers() {#getLayers--}
```
public final List<Layer> getLayers()
```


Render edilecek CAD çizim katmanlarını alır.


**Note:** By default, all layers are rendered. Layer names are case-sensitive.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - CAD çizim katmanları.

### setLayers(List<Layer> value) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public final void setLayers(List<Layer> value)
```


Render edilecek CAD çizim katmanlarını alır.
***Note:** By default, all layers are rendered. Layer names are case-sensitive.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.viewer.results.Layer> | CAD çizim katmanları. |
|

### isEnablePerformanceConversionMode() {#isEnablePerformanceConversionMode--}
```
public boolean isEnablePerformanceConversionMode()
```


Bu bayrağın true olarak ayarlanması, CAD ailesindeki tüm formatlar için özel bir performans odaklı dönüşüm modunu etkinleştirir. Bu modda dönüşüm hızı çok daha hızlıdır, ancak ortaya çıkan belgelerin kalitesi önemli ölçüde daha kötüdür. Varsayılan olarak, devre dışı bırakılmıştır (false). Ortaya çıkan belgelerin kalitesi, performans pahasına mümkün olan en iyi seviyededir.


**Returns:**
boolean -  true  eğer performans odaklı dönüşüm modu etkinse,  false  aksi takdirde.

### setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode) {#setEnablePerformanceConversionMode-boolean-}
```
public void setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)
```


Bu bayrağın true olarak ayarlanması, CAD ailesindeki tüm formatlar için özel bir performans odaklı dönüşüm modunu etkinleştirir. Bu modda dönüşüm hızı çok daha hızlıdır, ancak ortaya çıkan belgelerin kalitesi önemli ölçüde daha kötüdür. Varsayılan olarak, devre dışı bırakılmıştır (false). Ortaya çıkan belgelerin kalitesi, performans pahasına mümkün olan en iyi seviyededir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | enablePerformanceConversionMode | boolean | true  performans odaklı dönüşüm modunu etkinleştirmek için,  false  devre dışı bırakmak için. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Bu CadOptions nesnesinin başka bir nesneye eşit olup olmadığını kontrol eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | o | java.lang.Object | Karşılaştırılacak nesne. |
|

**Returns:**
boolean -  true  nesneler eşitse,  false  aksi takdirde.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu nesne için karma kod değerini hesaplar. Karma kod, şuna dayanır
nesnenin iç durumu ve karma tabanlı veri yapılarına kullanılır
hash haritaları ve hash kümeleri gibi.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - bu nesne için karma kod değeri.

### toString() {#toString--}
```
public String toString()
```


Bu nesnenin bir dize temsili döndürür.
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Returns:**
java.lang.String - bu nesnenin bir dize temsili.

### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Bu nesnenin bir dize temsili döndürür.
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | stil | org.apache.commons.lang3.builder.ToStringStyle | Dize temsili oluşturmak için kullanılacak ToStringStyle. |
|

**Returns:**
java.lang.String - belirtilen ToStringStyle kullanılarak bu nesnenin bir dize temsili.

