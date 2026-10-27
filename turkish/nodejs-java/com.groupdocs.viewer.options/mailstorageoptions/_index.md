---
title: "MailStorageOptions"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Mail depolama Lotus Notes MBox veri dosyalarını render etmek için seçenekler sağlar."
type: docs
weight: 19
url: /tr/nodejs-java/com.groupdocs.viewer.options/mailstorageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MailStorageOptions
```

Mail depolama (Lotus Notes, MBox) veri dosyalarını renderleme seçeneklerini sağlar.

MailStorageOptions sınıfı, GroupDocs.Viewer bileşeninde Mail depolama veri dosyalarının (örneğin Lotus Notes veya MBox) render edilmesini kontrol etmek için kullanılabilecek çeşitli ayarları ve parametreleri kapsüller.

Ayrıntılar için, [documentation][].

Örnek kullanım:

```

 MailStorageOptions options = new MailStorageOptions();
 options.setAddressFilter("@gmail.com");
 options.setMaxItems(10);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setMailStorageOptions(options);

 try (Viewer viewer = new Viewer("mail.msg")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MailStorageOptions()](#MailStorageOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTextFilter()](#getTextFilter--) | Mesajları filtrelemek için kullanılan anahtar kelimeleri alır. |
| [setTextFilter(String textFilter)](#setTextFilter-java.lang.String-) | Mesajları filtrelemek için kullanılan anahtar kelimeleri ayarlar. |
| [getAddressFilter()](#getAddressFilter--) | Gönderici veya alıcıya göre mesajları filtrelemek için kullanılan e-posta adresini alır. |
| [setAddressFilter(String addressFilter)](#setAddressFilter-java.lang.String-) | Gönderici veya alıcıya göre mesajları filtrelemek için kullanılan e-posta adresini ayarlar. |
| [getMaxItems()](#getMaxItems--) | Render edilecek maksimum mesaj veya öğe sayısını alır. |
| [setMaxItems(int maxItems)](#setMaxItems-int-) | Render edilecek maksimum mesaj veya öğe sayısını ayarlar. |
### MailStorageOptions() {#MailStorageOptions--}
```
public MailStorageOptions()
```


### getTextFilter() {#getTextFilter--}
```
public String getTextFilter()
```


Mesajları filtrelemek için kullanılan anahtar kelimeleri alır.

Bu özelliği, konu veya gövde içinde belirli bir metin içeren tüm mesajları render etmek için kullanın. Kod örneği için, [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Returns:**
java.lang.String - mesajları filtrelemek için kullanılan anahtar kelimeler.
### setTextFilter(String textFilter) {#setTextFilter-java.lang.String-}
```
public void setTextFilter(String textFilter)
```


Mesajları filtrelemek için kullanılan anahtar kelimeleri ayarlar.

Bu özelliği, konu veya gövde içinde belirli bir metin içeren tüm mesajları render etmek için kullanın. Kod örneği için, [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| textFilter | java.lang.String | Mesajları filtrelemek için kullanılan anahtar kelimeler. |

### getAddressFilter() {#getAddressFilter--}
```
public String getAddressFilter()
```


Gönderici veya alıcıya göre mesajları filtrelemek için kullanılan e-posta adresini alır.

Bu özelliği, göndericinin\u2019s veya alıcının\u2019s adresinde belirli bir metin içeren tüm mesajları render etmek için kullanın. Kod örneği için, [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Returns:**
java.lang.String - mesajları filtrelemek için kullanılan e-posta adresi.
### setAddressFilter(String addressFilter) {#setAddressFilter-java.lang.String-}
```
public void setAddressFilter(String addressFilter)
```


Gönderici veya alıcıya göre mesajları filtrelemek için kullanılan e-posta adresini ayarlar.

Bu özelliği, göndericinin\u2019s veya alıcının\u2019s adresinde belirli bir metin içeren tüm mesajları render etmek için kullanın. Kod örneği için, [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| addressFilter | java.lang.String | Mesajları filtrelemek için kullanılan e-posta adresi. |

### getMaxItems() {#getMaxItems--}
```
public int getMaxItems()
```


Render edilecek maksimum mesaj veya öğe sayısını alır.

Lotus Notes veri dosyaları büyük olabilir ve tüm mesajları almak önemli zaman alabilir. Bu ayar, işlenen mesaj veya öğe sayısının maksimumunu sınırlar.

***Note:** The default value is 0, which means all messages will be rendered.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render

**Returns:**
int - işlenecek maksimum mesaj veya öğe sayısı.
### setMaxItems(int maxItems) {#setMaxItems-int-}
```
public void setMaxItems(int maxItems)
```


Render edilecek maksimum mesaj veya öğe sayısını ayarlar.

Lotus Notes veri dosyaları büyük olabilir ve tüm mesajları almak önemli zaman alabilir. Bu ayar, işlenen mesaj veya öğe sayısının maksimumunu sınırlar.

***Note:** The default value is 0, which means all messages will be rendered.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| maxItems | int | İşlenecek maksimum mesaj veya öğe sayısı. |

