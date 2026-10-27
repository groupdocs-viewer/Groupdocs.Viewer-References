---
title: "FolderFontSource"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "TrueType yazı tiplerini içeren bir klasörü temsil eder."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

TrueType yazı tiplerini içeren bir klasörü temsil eder.

FolderFontSource sınıfı, TrueType yazı tiplerini içeren bir klasör konumunu belirtmek için kullanılır. Belirtilen klasörde depolanan yazı tiplerine belge renderleme amaçları için GroupDocs.Viewer API'sinin erişmesine olanak tanır.

Örnek kullanım:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | Yeni bir  FolderFontSource  sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | İki  FolderFontSource  nesnenin aynı olup olmadığını belirler. |
| [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | İki  FolderFontSource  nesnenin aynı olmama durumunu belirler. |
| [getFolderPath()](#getFolderPath--) | TrueType yazı tiplerini içeren klasörün yolunu alır. |
| [getSearchOption()](#getSearchOption--) | Geçerli klasörü ya da geçerli klasörü ve tüm alt klasörleri aramayı belirten arama seçeneğini alır. |
| [isRecursive()](#isRecursive--) | Yazı tiplerinin özyinelemeli olarak aranıp aranmayacağını kontrol eder. |
| [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | Geçerli  FolderFontSource  nesnesinin belirtilen  FolderFontSource  nesnesiyle aynı olup olmadığını belirler. |
| [equals(Object o)](#equals-java.lang.Object-) | Geçerli  FolderFontSource  nesnesinin belirtilen nesneyle aynı olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Geçerli  FolderFontSource  nesnesi için hash kodunu döndürür. |
| [toString()](#toString--) | Geçerli nesneyi temsil eden bir dize döndürür. |
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


Yeni bir  FolderFontSource  sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| folderPath | java.lang.String | TrueType yazı tiplerini içeren klasörün yolu. |
| searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | Geçerli klasörü ya da geçerli klasörü ve tüm alt klasörleri aramayı belirler. |

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


İki  FolderFontSource  nesnenin aynı olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Sol  FolderFontSource  nesnesi. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Sağ  FolderFontSource  nesnesi. |

**Returns:**
boolean -  true  eğer iki  FolderFontSource  nesnesi aynıysa; aksi takdirde,  false .
### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


İki  FolderFontSource  nesnenin aynı olmama durumunu belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Sol  FolderFontSource  nesnesi. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Sağ  FolderFontSource  nesnesi. |

**Returns:**
boolean -  true  eğer iki  FolderFontSource  nesnesi aynı değilse; aksi takdirde,  false .
### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


TrueType yazı tiplerini içeren klasörün yolunu alır.

**Returns:**
java.lang.String - TrueType yazı tiplerini içeren klasörün yolu.
### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


Geçerli klasörü ya da geçerli klasörü ve tüm alt klasörleri aramayı belirten arama seçeneğini alır.

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.
### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


Yazı tiplerinin özyinelemeli olarak aranıp aranmayacağını kontrol eder.

**Returns:**
boolean -  true  eğer yazı tipleri özyinelemeli olarak aranıyorsa,  false  aksi takdirde.
### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public boolean equals(FolderFontSource other)
```


Geçerli  FolderFontSource  nesnesinin belirtilen  FolderFontSource  nesnesiyle aynı olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Geçerli  FolderFontSource  nesnesiyle karşılaştırılacak nesne. |

**Returns:**
boolean -  true  eğer iki  FolderFontSource  nesnesi aynıysa; aksi takdirde,  false
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Geçerli  FolderFontSource  nesnesinin belirtilen nesneyle aynı olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| o | java.lang.Object | Geçerli  FolderFontSource  nesnesiyle karşılaştırılacak nesne. |

**Returns:**
boolean -  true  eğer  obj  parametresi  FolderFontSource  tipindeyse ve geçerli  FolderFontSource  nesnesiyle aynıysa; aksi takdirde,  false
### hashCode() {#hashCode--}
```
public int hashCode()
```


Geçerli  FolderFontSource  nesnesi için hash kodunu döndürür.

**Returns:**
int - geçerli  FolderFontSource  nesnesi için bir hash kodu.
### toString() {#toString--}
```
public String toString()
```


Geçerli nesneyi temsil eden bir dize döndürür.

**Returns:**
java.lang.String - geçerli nesneyi temsil eden bir dize.
