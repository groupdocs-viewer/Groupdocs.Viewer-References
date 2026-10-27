---
title: "Sayfa"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Görüntülenebilen tek bir sayfayı temsil eder."
type: docs
weight: 21
url: /tr/nodejs-java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

Görüntülenebilen tek bir sayfayı temsil eder.

Page arayüzü, GroupDocs.Viewer bileşeninde görüntülenebilen tek bir sayfaya erişim ve manipülasyon sağlamak için sözleşmeyi tanımlar. Sayfa numarası, boyutu ve diğer özellikler gibi bilgileri almayı sağlayan yöntemler sunar.

Örnek kullanım:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List pages = viewInfo.getPages();
     for (Page page : pages) {
         // Use the page object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is PageImpl.*
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getName()](#getName--) | Çalışma sayfasının veya sayfanın adını alır. |
| [setName(String name)](#setName-java.lang.String-) | Çalışma sayfasının veya sayfanın adını ayarlar. |
| [getNumber()](#getNumber--) | Sayfa numarasını alır. |
| [setNumber(int number)](#setNumber-int-) | Sayfa numarasını ayarlar. |
| [isVisible()](#isVisible--) | Sayfanın görünürlük göstergesini alır. |
| [setVisible(boolean visible)](#setVisible-boolean-) | Sayfanın görünürlük göstergesini ayarlar. |
| [getWidth()](#getWidth--) | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden genişliğini alır. |
| [setWidth(int width)](#setWidth-int-) | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden genişliğini ayarlar. |
| [getHeight()](#getHeight--) | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden yüksekliğini alır. |
| [setHeight(int height)](#setHeight-int-) | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden yüksekliğini ayarlar. |
| [getLines()](#getLines--) | Metin Çıkarma etkinleştirildiğinde JPG veya PNG olarak görüntülendiğinde sayfada bulunan satırları alır. |
| [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | Metin Çıkarma etkinleştirildiğinde JPG veya PNG olarak görüntülendiğinde sayfada bulunan satırları ayarlar. |
### getName() {#getName--}
```
public abstract String getName()
```


Çalışma sayfasının veya sayfanın adını alır.

**Returns:**
java.lang.String - çalışma sayfasının veya sayfanın adı.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Çalışma sayfasının veya sayfanın adını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | çalışma sayfası veya sayfa için ayarlanacak ad. |

### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


Sayfa numarasını alır.

**Returns:**
int - sayfa numarası.
### setNumber(int number) {#setNumber-int-}
```
public abstract void setNumber(int number)
```


Sayfa numarasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayı | int | ayarlanacak sayfa numarası. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Sayfanın görünürlük göstergesini alır.

**Returns:**
boolean - sayfa görünürlük göstergesi.
### setVisible(boolean visible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean visible)
```


Sayfanın görünürlük göstergesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görünür | boolean | sayfa görünürse true, aksi takdirde false. |

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden genişliğini alır.

**Returns:**
int - sayfanın genişliği.
### setWidth(int width) {#setWidth-int-}
```
public abstract void setWidth(int width)
```


JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden genişliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | int | sayfa için ayarlanacak genişlik. |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden yüksekliğini alır.

**Returns:**
int - sayfanın yüksekliği.
### setHeight(int height) {#setHeight-int-}
```
public abstract void setHeight(int height)
```


JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden yüksekliğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| height | int | sayfa için ayarlanacak yükseklik. |

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


Metin Çıkarma etkinleştirildiğinde JPG veya PNG olarak görüntülendiğinde sayfada bulunan satırları alır.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - sayfada bulunan satırlar.
### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


Metin Çıkarma etkinleştirildiğinde JPG veya PNG olarak görüntülendiğinde sayfada bulunan satırları ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| satırlar | java.util.List<com.groupdocs.viewer.results.Line> | sayfa için ayarlanacak satırların listesi. |

