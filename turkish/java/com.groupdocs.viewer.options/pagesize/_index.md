---
title: "PageSize"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Sayfanın boyutu."
type: docs
weight: 42
url: /tr/java/com.groupdocs.viewer.options/pagesize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PageSize extends Enum<PageSize>
```

Sayfanın boyutu.


PageSize enum'ı, GroupDocs.Viewer bileşeninde farklı sayfa boyutlarını temsil eder.
Önceden tanımlanmış sayfa boyutlarından oluşan bir küme sağlar ve bu boyutlar ölçüleri belirtmek için kullanılabilir.
bir sayfanın çeşitli belge renderleme senaryolarında.


Örnek kullanım:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = htmlViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [UNSPECIFIED](#UNSPECIFIED) | Varsayılan, belirtilmemiş sayfa boyutu. |
|
|  | [LETTER](#LETTER) | Letter sayfasının puan cinsinden boyutu 792 x 612'dir. |
|
|  | [LEDGER](#LEDGER) | A0 sayfasının puan cinsinden boyutu 3371 x 2384'tür. |
|
|  | [A0](#A0) | A1 sayfasının puan cinsinden boyutu 2384 x 1685'tir. |
|
|  | [A1](#A1) | A2 sayfasının puan cinsinden boyutu 1684 x 1190'tir. |
|
|  | [A2](#A2) | A3 sayfasının puan cinsinden boyutu 1190 x 842'dir. |
|
|  | [A3](#A3) | A3 sayfasının puan cinsinden boyutu 1190 x 842'dir. |
|
|  | [A4](#A4) | A4 sayfasının puan cinsinden boyutu 842 x 595'tir. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final PageSize UNSPECIFIED
```


Varsayılan, belirtilmemiş sayfa boyutu.
Bu boyut, belirli bir sayfa boyutu belirtilmediğinde kullanılır.


### LETTER {#LETTER}
```
public static final PageSize LETTER
```


Letter sayfasının puan cinsinden boyutu 792 x 612'dir.
Bu sayfa boyutu, Kuzey Amerika'da mektuplar ve belgeler için yaygın olarak kullanılır.


### LEDGER {#LEDGER}
```
public static final PageSize LEDGER
```


A0 sayfasının puan cinsinden boyutu 3371 x 2384'tür.
Bu büyük sayfa boyutu, ISO 216 uluslararası standardının bir parçasıdır.


### A0 {#A0}
```
public static final PageSize A0
```


A1 sayfasının puan cinsinden boyutu 2384 x 1685'tir.
Bu sayfa boyutu, ISO 216 uluslararası standardının bir parçasıdır.


### A1 {#A1}
```
public static final PageSize A1
```


A2 sayfasının puan cinsinden boyutu 1684 x 1190'tir.
Bu sayfa boyutu, ISO 216 uluslararası standardının bir parçasıdır.


### A2 {#A2}
```
public static final PageSize A2
```


A3 sayfasının puan cinsinden boyutu 1190 x 842'dir.
Bu sayfa boyutu, ISO 216 uluslararası standardının bir parçasıdır.


### A3 {#A3}
```
public static final PageSize A3
```


A3 sayfasının puan cinsinden boyutu 1190 x 842'dir.
Bu sayfa boyutu, ISO 216 uluslararası standardının bir parçasıdır.


### A4 {#A4}
```
public static final PageSize A4
```


A4 sayfasının puan cinsinden boyutu 842 x 595'tir.
Bu sayfa boyutu, ISO 216 uluslararası standardının bir parçasıdır.


### values() {#values--}
```
public static PageSize[] values()
```




**Returns:**
com.groupdocs.viewer.options.PageSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PageSize valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize)
