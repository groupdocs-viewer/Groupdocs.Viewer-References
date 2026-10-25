---
title: "Düzen"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Bir CAD çizimi içinde bulunan bir yerleşimi temsil eder."
type: docs
weight: 17
url: /tr/java/com.groupdocs.viewer.results/layout/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layout extends Serializable
```

Bir CAD çizimi içinde bulunan bir yerleşimi temsil eder.


Düzen arabirimi, bir CAD çizimindeki düzeni erişmek ve değiştirmek için sözleşmeyi tanımlar.
GroupDocs.Viewer bileşeninde. Düzen adı gibi bilgileri almak için yöntemler sağlar,
boyutlar ve diğer özellikler.


Örnek kullanım:

````

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layouts = viewInfo.getLayouts();
     for (Layout layout : layouts) {
         // Use the layout object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LayoutImpl.*

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getName()](#getName--) | Düzenin adını alır. |
|
|  | [setName(String name)](#setName-java.lang.String-) | Düzenin adını ayarlar. |
|
|  | [getWidth()](#getWidth--) | Düzenin genişliğini alır. |
|
|  | [setWidth(double width)](#setWidth-double-) | Düzenin genişliğini ayarlar. |
|
|  | [getHeight()](#getHeight--) | Düzenin yüksekliğini alır. |
|
|  | [setHeight(double height)](#setHeight-double-) | Düzenin yüksekliğini ayarlar. |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Bu nesnenin sağlanan nesneye eşit olup olmadığını kontrol eder. |
|
### getName() {#getName--}
```
public abstract String getName()
```


Düzenin adını alır.


**Returns:**
java.lang.String - düzenin adı.

### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Düzenin adını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | Düzen için ayarlanacak ad. |
|

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Düzenin genişliğini alır.


**Returns:**
double - düzenin genişliği.

### setWidth(double width) {#setWidth-double-}
```
public abstract void setWidth(double width)
```


Düzenin genişliğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | width | double | Düzen için ayarlanacak genişlik. |
|

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Düzenin yüksekliğini alır.


**Returns:**
double - düzenin yüksekliği.

### setHeight(double height) {#setHeight-double-}
```
public abstract void setHeight(double height)
```


Düzenin yüksekliğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | height | double | Düzen için ayarlanacak yükseklik. |
|

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Bu nesnenin sağlanan nesneye eşit olup olmadığını kontrol eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | diğer | java.lang.Object | Karşılaştırılacak nesne. |
|

**Returns:**
boolean -  true  nesneler eşitse,  false  aksi takdirde.

