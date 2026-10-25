---
title: "Metered"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "GroupDocs.Viewer bileşenine ölçülü lisans uygulamak için yöntemler sağlar."
type: docs
weight: 11
url: /tr/java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

GroupDocs.Viewer bileşenine ölçülü lisans uygulamak için yöntemler sağlar.


Ölçümlü lisanslama, geleneksel sunucu başına veya geliştirici başına lisans yerine işlenen belge sayfalarının sayısına göre GroupDocs.Viewer kullanımını dinamik olarak izleme ve kontrol etmenizi sağlar.
Bu esnek lisans modeli, belge işleme gereksinimlerinin zaman içinde değiştiği senaryolar için veya yalnızca kullandığınız kadar ödeme yapmak istediğiniz durumlar için uygundur.


Örnek kullanım:

````

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Metered()](#Metered--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | İşlenen megabayt (MB) miktarını alır. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Harcanan kredi sayısını alır. |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ürünü Ölçümlü anahtarlarla etkinleştirir. |
|
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


İşlenen megabayt (MB) miktarını alır.


Bu yöntem, bileşen tarafından işlenen toplam MB miktarını döndürür.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
````



**Returns:**
double - işlenen MB miktarı.

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Harcanan kredi sayısını alır.


Bu yöntem, bileşen tarafından tüketilen toplam kredi sayısını döndürür.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
````



**Returns:**
double - tüketilen kredi sayısı.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Ürünü Ölçümlü anahtarlarla etkinleştirir.


Aşağıdaki örnek, ölçülen anahtarlarla ürünün nasıl etkinleştirileceğini gösterir.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | publicKey | java.lang.String | Genel anahtar. |
|
|  | privateKey | java.lang.String | Özel anahtar. |
|

