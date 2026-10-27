---
title: "OutlookOptions"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Outlook veri dosyalarını renderleme seçeneklerini sağlar."
type: docs
weight: 20
url: /tr/nodejs-java/com.groupdocs.viewer.options/outlookoptions/
---
**Inheritance:**
java.lang.Object
```
public class OutlookOptions
```

Outlook veri dosyalarını renderleme seçeneklerini sağlar.

OutlookOptions sınıfı, GroupDocs.Viewer bileşeninde Outlook veri dosyalarının (örneğin PST veya OST dosyaları) renderlenmesini kontrol etmek için kullanılabilecek çeşitli ayarları ve parametreleri kapsar.

Ayrıntılar için, [documentation][].

Örnek kullanım:

```

 OutlookOptions options = new OutlookOptions();
 options.setAddressFilter("@gmail.com");
 options.setFolder("folderName");

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setOutlookOptions(options);

 try (Viewer viewer = new Viewer("mail.pst")) {
   viewer.view(htmlViewOptions);
   // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OutlookOptions()](#OutlookOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFolder()](#getFolder--) | Renderlenecek klasörün adını alır. |
| [setFolder(String value)](#setFolder-java.lang.String-) | Renderlenecek klasörün adını ayarlar. |
| [getTextFilter()](#getTextFilter--) | Mesajları filtrelemek için kullanılan anahtar kelimeleri alır. |
| [setTextFilter(String value)](#setTextFilter-java.lang.String-) | Mesajları filtrelemek için kullanılan anahtar kelimeleri alır. |
| [getAddressFilter()](#getAddressFilter--) | Gönderici veya alıcıya göre mesajları filtrelemek için kullanılan e-posta adresini alır. |
| [setAddressFilter(String value)](#setAddressFilter-java.lang.String-) | Gönderici veya alıcıya göre mesajları filtrelemek için kullanılan e-posta adresini ayarlar. |
| [getMaxItemsInFolder()](#getMaxItemsInFolder--) | Bir klasörden renderlenebilecek maksimum mesaj veya öğe sayısını alır. |
| [setMaxItemsInFolder(int value)](#setMaxItemsInFolder-int-) | Bir klasörden renderlenebilecek maksimum mesaj veya öğe sayısını ayarlar. |
### OutlookOptions() {#OutlookOptions--}
```
public OutlookOptions()
```


### getFolder() {#getFolder--}
```
public final String getFolder()
```


Renderlenecek klasörün adını alır. Renderlenecek klasörün adı (ör. Gelen Kutusu, Gönderilmiş Öğeler veya Silinmiş Öğeler).

When Outlook veri dosyası işlenirken, GroupDocs.Viewer dosyada bulunan tüm klasörlerden (iç içe klasörler dahil) mesajları render eder. Bu özelliği belirli bir klasörden öğeleri render etmek için kullanın. Kod örneği için bu [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder

**Returns:**
java.lang.String - render edilecek klasörün adı.
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Render edilecek klasörün adını ayarlar. Render edilecek klasörün adı (ör. Inbox, Sent Item veya Deleted Items).

When Outlook veri dosyası işlenirken, GroupDocs.Viewer dosyada bulunan tüm klasörlerden (iç içe klasörler dahil) mesajları render eder. Bu özelliği belirli bir klasörden öğeleri render etmek için kullanın. Kod örneği için bu [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String | Render edilecek klasörün adı. |

### getTextFilter() {#getTextFilter--}
```
public final String getTextFilter()
```


Mesajları filtrelemek için kullanılan anahtar kelimeleri alır.

Bu özelliği, konu veya gövde içinde belirli bir metin içeren tüm mesajları render etmek için kullanın. Kod örneği için, [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Returns:**
java.lang.String - anahtar kelimeler.
### setTextFilter(String value) {#setTextFilter-java.lang.String-}
```
public final void setTextFilter(String value)
```


Mesajları filtrelemek için kullanılan anahtar kelimeleri alır.

Bu özelliği, konu veya gövde içinde belirli bir metin içeren tüm mesajları render etmek için kullanın. Kod örneği için, [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String | Anahtar kelimeler. |

### getAddressFilter() {#getAddressFilter--}
```
public final String getAddressFilter()
```


Gönderici veya alıcıya göre mesajları filtrelemek için kullanılan e-posta adresini alır.

Bu özelliği, gönderici\ufffds veya alıcı\ufffds adresinde belirli bir metin içeren tüm mesajları render etmek için kullanın. Kod örneği için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Returns:**
java.lang.String - mesajları filtrelemek için kullanılan e-posta adresi.
### setAddressFilter(String value) {#setAddressFilter-java.lang.String-}
```
public final void setAddressFilter(String value)
```


Gönderici veya alıcıya göre mesajları filtrelemek için kullanılan e-posta adresini ayarlar.

Bu özelliği, gönderici\ufffds veya alıcı\ufffds adresinde belirli bir metin içeren tüm mesajları render etmek için kullanın. Kod örneği için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String | Mesajları filtrelemek için kullanılan e-posta adresi. |

### getMaxItemsInFolder() {#getMaxItemsInFolder--}
```
public final int getMaxItemsInFolder()
```


Bir klasörden renderlenebilecek maksimum mesaj veya öğe sayısını alır.

Outlook veri dosyaları büyük olabilir ve tüm mesajları almak önemli zaman alabilir. Bu ayar, render edilen mesajların veya öğelerin (ör. kişiler ve görevler) maksimum sayısını sınırlar. Varsayılan değer 50'dir. Tüm mesajları render etmek için değeri 0 olarak ayarlayın. Kod örneği için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render

**Returns:**
int - bir klasörden render edilebilecek maksimum mesaj veya öğe sayısı.
### setMaxItemsInFolder(int value) {#setMaxItemsInFolder-int-}
```
public final void setMaxItemsInFolder(int value)
```


Bir klasörden renderlenebilecek maksimum mesaj veya öğe sayısını ayarlar.

Outlook veri dosyaları büyük olabilir ve tüm mesajları almak önemli zaman alabilir. Bu ayar, render edilen mesajların veya öğelerin (ör. kişiler ve görevler) maksimum sayısını sınırlar. Varsayılan değer 50'dir. Tüm mesajları render etmek için değeri 0 olarak ayarlayın. Kod örneği için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int | Bir klasörden render edilebilecek maksimum mesaj veya öğe sayısı. |

