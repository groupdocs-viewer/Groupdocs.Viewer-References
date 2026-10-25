---
title: "FolderFontSource"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "TrueType yazı tiplerini içeren bir klasörü temsil eder."
type: docs
weight: 10
url: /tr/java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

TrueType yazı tiplerini içeren bir klasörü temsil eder.


FolderFontSource sınıfı, TrueType fontları içeren bir klasör konumunu belirtmek için kullanılır.
Belirtilen klasörde depolanan fontlara belge renderleme amacıyla erişim sağlamak için GroupDocs.Viewer API'sine izin verir.


Örnek kullanım:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | Yeni bir örnek başlatır |
FolderFontSource
sınıf.
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | İki öğenin belirlenip belirlenmediğini |
FolderFontSource
nesneler aynı.
|
|  | [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | İki öğenin belirlenip belirlenmediğini |
FolderFontSource
nesneler aynı değil.
|
|  | [getFolderPath()](#getFolderPath--) | TrueType fontlarını içeren klasörün yolunu alır. |
|
|  | [getSearchOption()](#getSearchOption--) | Geçerli klasörü veya geçerli klasörü ve tüm alt klasörleri aramayı belirten arama seçeneğini alır. |
|
|  | [isRecursive()](#isRecursive--) | Fontların yinelemeli olarak aranıp aranmayacağını kontrol eder. |
|
|  | [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | Geçerli öğenin |
FolderFontSource
belirtilen ile aynı olup olmadığını
FolderFontSource
nesne.
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Geçerli öğenin |
FolderFontSource
belirtilen nesne ile aynı.
|
|  | [hashCode()](#hashCode--) | Geçerli öğenin hash kodunu döndürür. |
FolderFontSource
nesne.
|
|  | [toString()](#toString--) | Geçerli nesneyi temsil eden bir dize döndürür. |
|
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


Yeni bir örnek başlatır
FolderFontSource
sınıf.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | folderPath | java.lang.String | TrueType yazı tiplerini içeren klasörün yolu. |
|
|  | searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | Geçerli klasörü, ya da geçerli klasörü ve tüm alt klasörleri arayıp aramayacağını belirtir. |
|

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


İki öğenin belirlenip belirlenmediğini
FolderFontSource
nesneler aynı.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Sol  FolderFontSource  nesnesi. |
|
|  | right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Sağ  FolderFontSource  nesnesi. |
|

**Returns:**
boolean -  true  eğer iki  FolderFontSource  nesnesi aynıysa; aksi takdirde,  false .

### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


İki öğenin belirlenip belirlenmediğini
FolderFontSource
nesneler aynı değil.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Sol  FolderFontSource  nesnesi. |
|
|  | right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Sağ  FolderFontSource  nesnesi. |
|

**Returns:**
boolean -  true  eğer iki  FolderFontSource  nesnesi aynı değilse; aksi takdirde,  false .

### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


TrueType fontlarını içeren klasörün yolunu alır.


**Returns:**
java.lang.String - TrueType yazı tiplerini içeren klasörün yolu.

### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


Geçerli klasörü veya geçerli klasörü ve tüm alt klasörleri aramayı belirten arama seçeneğini alır.


**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.

### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


Fontların yinelemeli olarak aranıp aranmayacağını kontrol eder.


**Returns:**
boolean -  true  eğer yazı tipleri yinelemeli olarak aranacaksa,  false  aksi takdirde.

### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public boolean equals(FolderFontSource other)
```


Geçerli öğenin
FolderFontSource
belirtilen ile aynı olup olmadığını
FolderFontSource
nesne.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Geçerli  FolderFontSource  nesnesiyle karşılaştırılacak nesne. |
|

**Returns:**
boolean -  true  eğer iki  FolderFontSource  nesnesi aynıysa; aksi takdirde,  false

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Geçerli öğenin
FolderFontSource
belirtilen nesne ile aynı.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | o | java.lang.Object | Geçerli  FolderFontSource  nesnesiyle karşılaştırılacak nesne. |
|

**Returns:**
boolean -  true  eğer  obj  parametresi  FolderFontSource  tipindeyse ve geçerli  FolderFontSource  nesnesiyle aynıysa; aksi takdirde,  false

### hashCode() {#hashCode--}
```
public int hashCode()
```


Geçerli öğenin hash kodunu döndürür.
FolderFontSource
nesne.


**Returns:**
int - geçerli  FolderFontSource  nesnesi için bir karma kodu.

### toString() {#toString--}
```
public String toString()
```


Geçerli nesneyi temsil eden bir dize döndürür.


**Returns:**
java.lang.String - geçerli nesneyi temsil eden bir dize.

