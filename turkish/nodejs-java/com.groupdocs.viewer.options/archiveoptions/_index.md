---
title: "ArchiveOptions"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Arşiv dosyalarını renderleme seçeneklerini sağlar."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

Arşiv dosyalarını renderleme seçeneklerini sağlar.

ArchiveOptions sınıfı, görüntüleyici modülünde arşiv dosyalarının render edilmesini yapılandırmak için kullanılabilecek bir dizi seçeneği temsil eder. Sayfa başına öğe sayısı gibi render sürecinin çeşitli yönlerini özelleştirmenize olanak tanır.

Örnek kullanım:

```

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
```

***Note:** The  ArchiveOptions  class provides a range of customization options for rendering archive files. You can configure these options based on your specific requirements to achieve the desired output.*
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ArchiveOptions()](#ArchiveOptions--) | ArchiveOptions sınıfının varsayılan ayarlarla yeni bir örneğini oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFolder()](#getFolder--) | Render için kullanılacak arşiv içindeki klasörü alır. |
| [setFolder(String value)](#setFolder-java.lang.String-) | Arşivin içinde, renderleme için kullanılacak klasörü ayarlar. |
| [getFileName()](#getFileName--) | Başlıkta görüntülenecek dosya adını alır. |
| [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | Başlıkta görüntülenecek dosya adını ayarlar. |
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


ArchiveOptions sınıfının varsayılan ayarlarla yeni bir örneğini oluşturur.

### getFolder() {#getFolder--}
```
public final String getFolder()
```


Render için kullanılacak arşiv içindeki klasörü alır.

Varsayılan olarak, GroupDocs.Viewer arşivde bulunan tüm klasörlerin öğelerini renderlar. Belirli bir klasörden öğeleri renderlamak için bu özelliği ayarlayın. Kod örneği için, [belgelendirme][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder

**Returns:**
java.lang.String - renderlanacak klasör.
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Arşivin içinde, renderleme için kullanılacak klasörü ayarlar.

Varsayılan olarak, GroupDocs.Viewer arşivde bulunan tüm klasörlerin öğelerini renderlar. Belirli bir klasörden öğeleri renderlamak için bu özelliği ayarlayın. Kod örneği için, [belgelendirme][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String | Renderlanacak klasör. |

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


Başlıkta görüntülenecek dosya adını alır.

Varsayılan olarak, GroupDocs.Viewer arşiv dosya adını her sayfanın başlığında gösterir. Bu adı değiştirmek veya gizlemek için bu özelliği ayarlayın. Daha fazla bilgi ve kod örneği için [belgelendirme][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.
### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


Başlıkta görüntülenecek dosya adını ayarlar.

Varsayılan olarak, GroupDocs.Viewer arşiv dosya adını her sayfanın başlığında gösterir. Bu adı değiştirmek veya gizlemek için bu özelliği ayarlayın. Daha fazla bilgi ve kod örneği için [belgelendirme][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | [FileName](../../com.groupdocs.viewer.options/filename) | Görüntülenecek dosya adı. |

