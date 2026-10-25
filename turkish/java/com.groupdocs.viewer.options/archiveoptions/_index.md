---
title: "ArchiveOptions"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Arşiv dosyalarını işlemek için seçenekler sunar."
type: docs
weight: 10
url: /tr/java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

Arşiv dosyalarını işlemek için seçenekler sunar.


Bu
ArchiveOptions
class, görüntüleyici modülünde arşiv dosyalarının işlenmesini yapılandırmak için kullanılabilecek bir dizi seçeneği temsil eder.
İşleme sürecinin çeşitli yönlerini, örneğin her sayfadaki öğe sayısı gibi, özelleştirmenizi sağlar.


Örnek kullanım:

````

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
````


***Note:** The 
ArchiveOptions
class, arşiv dosyalarının işlenmesi için bir dizi özelleştirme seçeneği sunar.
Bu seçenekleri, belirli gereksinimlerinize göre yapılandırarak istediğiniz çıktıyı elde edebilirsiniz.*

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [ArchiveOptions()](#ArchiveOptions--) | ArchiveOptions sınıfının varsayılan ayarlarla yeni bir örneğini oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFolder()](#getFolder--) | İşleme için kullanılacak arşivin içindeki klasörü alır. |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | İşleme için kullanılacak arşivin içindeki klasörü ayarlar. |
|
|  | [getFileName()](#getFileName--) | Üstbilgide gösterilecek dosya adını alır. |
|
|  | [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | Üstbilgide gösterilecek dosya adını ayarlar. |
|
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


ArchiveOptions sınıfının varsayılan ayarlarla yeni bir örneğini oluşturur.


### getFolder() {#getFolder--}
```
public final String getFolder()
```


İşleme için kullanılacak arşivin içindeki klasörü alır.


Varsayılan olarak, GroupDocs.Viewer arşivde bulunan tüm klasörlerden öğeleri işler. Belirli bir klasörden öğeleri işlemek için bu özelliği ayarlayın.
Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder) adresine bakın.


**Returns:**
java.lang.String - işlenecek klasör.

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


İşleme için kullanılacak arşivin içindeki klasörü ayarlar.


Varsayılan olarak, GroupDocs.Viewer arşivde bulunan tüm klasörlerden öğeleri işler. Belirli bir klasörden öğeleri işlemek için bu özelliği ayarlayın.
Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder) adresine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | İşlenecek klasör. |
|

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


Üstbilgide gösterilecek dosya adını alır.


Varsayılan olarak, GroupDocs.Viewer arşiv dosya adını her sayfanın üstbilgisinde gösterir. Bu adı değiştirmek veya gizlemek için bu özelliği ayarlayın.
Daha fazla bilgi ve kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name) adresine bakın.


**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.

### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


Üstbilgide gösterilecek dosya adını ayarlar.


Varsayılan olarak, GroupDocs.Viewer arşiv dosya adını her sayfanın üstbilgisinde gösterir. Bu adı değiştirmek veya gizlemek için bu özelliği ayarlayın.
Daha fazla bilgi ve kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name) adresine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileName | [FileName](../../com.groupdocs.viewer.options/filename) | Gösterilecek dosya adı. |
|

