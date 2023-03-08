---
title: Viewer
second_title: .NET API Başvurusu için GroupDocs.Viewer
description: Yeni örneğini başlatırViewergroupdocs.viewer/viewer sınıf.
type: docs
weight: 10
url: /tr/net/groupdocs.viewer/viewer/viewer/
---
## Viewer(Func&lt;Stream&gt;) {#constructor}

Yeni örneğini başlatır[`Viewer`](../../viewer) sınıf.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| getFileStream | Func`1 | Okunabilir akış döndüren yöntem. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*getFileStream* boş. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Viewer tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET özellikleri hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ayrıca bakınız

* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

Yeni örneğini başlatır[`Viewer`](../../viewer) sınıf.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| getFileStream | Func`1 | Okunabilir akış döndüren yöntem. |
| getLoadOptions | Func`1 | Belge yükleme seçeneklerini döndüren yöntemler. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*getFileStream* boş. |
| ArgumentNullException | Ne zaman atıldı*getLoadOptions* boş. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Viewer tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET özellikleri hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* GroupDocs.Viewer for .NET: ile şifrelenmiş belgeleri yükleme ve üçüncü taraf depolardaki dosyaları görüntüleme hakkında daha fazla bilgi[GroupDocs.Viewer ile belge nasıl yüklenir ve görüntülenir?](https://docs.groupdocs.com/display/viewernet/Loading)

### Ayrıca bakınız

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

Yeni örneğini başlatır[`Viewer`](../../viewer) sınıf.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| getFileStream | Func`1 | Okunabilir akış döndüren yöntem. |
| settings | ViewerSettings | Görüntüleyici ayarları. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*getFileStream* boş. |
| ArgumentNullException | Ne zaman atıldı*settings* boş. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Viewer tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET özellikleri hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ayrıca bakınız

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

Yeni örneğini başlatır[`Viewer`](../../viewer) sınıf.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| getFileStream | Func`1 | Okunabilir akış döndüren yöntem. |
| getLoadOptions | Func`1 | Belge yükleme seçeneklerini döndüren yöntemler. |
| settings | ViewerSettings | Görüntüleyici ayarları. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*getFileStream* boş. |
| ArgumentNullException | Ne zaman atıldı*getLoadOptions* boş. |
| ArgumentNullException | Ne zaman atıldı*settings* boş. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Viewer tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET özellikleri hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* GroupDocs.Viewer for .NET: ile şifrelenmiş belgeleri yükleme ve üçüncü taraf depolardaki dosyaları görüntüleme hakkında daha fazla bilgi[GroupDocs.Viewer ile belge nasıl yüklenir ve görüntülenir?](https://docs.groupdocs.com/display/viewernet/Loading)

### Ayrıca bakınız

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

Yeni örneğini başlatır[`Viewer`](../../viewer) sınıf.

```csharp
public Viewer(Stream stream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Dosya akışı. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*stream* boş. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Viewer tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET özellikleri hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ayrıca bakınız

* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

Yeni örneğini başlatır[`Viewer`](../../viewer) sınıf.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Dosya akışı. |
| leaveOpen | Boolean | doğru Viewer nesnesi atıldıktan sonra akışı açık bırakmak; aksi takdirde,YANLIŞ. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*stream* boş. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Viewer tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET özellikleri hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ayrıca bakınız

* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

Yeni örneğini başlatır[`Viewer`](../../viewer) sınıf.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Dosya akışı. |
| loadOptions | LoadOptions | Belge yükleme seçenekleri. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*stream* boş. |
| ArgumentNullException | Ne zaman atıldı*loadOptions* boş. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Viewer tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET özellikleri hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* GroupDocs.Viewer for .NET: ile şifrelenmiş belgeleri yükleme ve üçüncü taraf depolardaki dosyaları görüntüleme hakkında daha fazla bilgi[GroupDocs.Viewer ile belge nasıl yüklenir ve görüntülenir?](https://docs.groupdocs.com/display/viewernet/Loading)

### Ayrıca bakınız

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

Yeni örneğini başlatır[`Viewer`](../../viewer) sınıf.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Dosya akışı. |
| loadOptions | LoadOptions | Belge yükleme seçenekleri. |
| leaveOpen | Boolean | doğru Viewer nesnesi atıldıktan sonra akışı açık bırakmak; aksi takdirde,YANLIŞ. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*stream* boş. |
| ArgumentNullException | Ne zaman atıldı*loadOptions* boş. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Viewer tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET özellikleri hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* GroupDocs.Viewer for .NET: ile şifrelenmiş belgeleri yükleme ve üçüncü taraf depolardaki dosyaları görüntüleme hakkında daha fazla bilgi[GroupDocs.Viewer ile belge nasıl yüklenir ve görüntülenir?](https://docs.groupdocs.com/display/viewernet/Loading)

### Ayrıca bakınız

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

Yeni örneğini başlatır[`Viewer`](../../viewer) sınıf.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Dosya akışı. |
| settings | ViewerSettings | Görüntüleyici ayarları. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*stream* boş. |
| ArgumentNullException | Ne zaman atıldı*settings* boş. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Viewer tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET özellikleri hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ayrıca bakınız

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

Yeni örneğini başlatır[`Viewer`](../../viewer) sınıf.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Dosya akışı. |
| settings | ViewerSettings | Görüntüleyici ayarları. |
| leaveOpen | Boolean | doğru Viewer nesnesi atıldıktan sonra akışı açık bırakmak; aksi takdirde,YANLIŞ. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*stream* boş. |
| ArgumentNullException | Ne zaman atıldı*settings* boş. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Viewer tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET özellikleri hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ayrıca bakınız

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

Yeni örneğini başlatır[`Viewer`](../../viewer) sınıf.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Dosya akışı. |
| loadOptions | LoadOptions | Belge yükleme seçenekleri. |
| settings | ViewerSettings | Görüntüleyici ayarları. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*stream* boş. |
| ArgumentNullException | Ne zaman atıldı*loadOptions* boş. |
| ArgumentNullException | Ne zaman atıldı*settings* boş. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Viewer tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET özellikleri hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* GroupDocs.Viewer for .NET: ile şifrelenmiş belgeleri yükleme ve üçüncü taraf depolardaki dosyaları görüntüleme hakkında daha fazla bilgi[GroupDocs.Viewer ile belge nasıl yüklenir ve görüntülenir?](https://docs.groupdocs.com/display/viewernet/Loading)

### Ayrıca bakınız

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

Yeni örneğini başlatır[`Viewer`](../../viewer) sınıf.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Dosya akışı. |
| loadOptions | LoadOptions | Belge yükleme seçenekleri. |
| settings | ViewerSettings | Görüntüleyici ayarları. |
| leaveOpen | Boolean | doğru Viewer nesnesi atıldıktan sonra akışı açık bırakmak; aksi takdirde,YANLIŞ. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*stream* boş. |
| ArgumentNullException | Ne zaman atıldı*loadOptions* boş. |
| ArgumentNullException | Ne zaman atıldı*settings* boş. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Viewer tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET özellikleri hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* GroupDocs.Viewer for .NET: ile şifrelenmiş belgeleri yükleme ve üçüncü taraf depolardaki dosyaları görüntüleme hakkında daha fazla bilgi[GroupDocs.Viewer ile belge nasıl yüklenir ve görüntülenir?](https://docs.groupdocs.com/display/viewernet/Loading)

### Ayrıca bakınız

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

Yeni örneğini başlatır[`Viewer`](../../viewer) sınıf.

```csharp
public Viewer(string filePath)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Oluşturulacak dosyanın yolu. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | Ne zaman atıldı*filePath* null veya boş. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Viewer tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET özellikleri hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ayrıca bakınız

* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

Yeni örneğini başlatır[`Viewer`](../../viewer) sınıf.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Oluşturulacak dosyanın yolu. |
| settings | ViewerSettings | Görüntüleyici ayarları. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | Ne zaman atıldı*filePath* null veya boş. |
| ArgumentNullException | Ne zaman atıldı*settings* boş. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Viewer tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET özellikleri hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ayrıca bakınız

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

Yeni örneğini başlatır[`Viewer`](../../viewer) sınıf.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Oluşturulacak dosyanın yolu. |
| loadOptions | LoadOptions | Dosyayı açmak için kullanılan seçenekler. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | Ne zaman atıldı*filePath* null veya boş. |
| ArgumentNullException | Ne zaman atıldı*loadOptions* boş. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Viewer tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET özellikleri hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* GroupDocs.Viewer for .NET: ile şifrelenmiş belgeleri yükleme ve üçüncü taraf depolardaki dosyaları görüntüleme hakkında daha fazla bilgi[GroupDocs.Viewer ile belge nasıl yüklenir ve görüntülenir?](https://docs.groupdocs.com/display/viewernet/Loading)

### Ayrıca bakınız

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

Yeni örneğini başlatır[`Viewer`](../../viewer) sınıf.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Oluşturulacak dosyanın yolu. |
| loadOptions | LoadOptions | Dosyayı açmak için kullanılan seçenekler. |
| settings | ViewerSettings | Görüntüleyici ayarları. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | Ne zaman atıldı*filePath* null veya boş. |
| ArgumentNullException | Ne zaman atıldı*loadOptions* boş. |
| ArgumentNullException | Ne zaman atıldı*settings* boş. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Viewer tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET özellikleri hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* GroupDocs.Viewer for .NET: ile şifrelenmiş belgeleri yükleme ve üçüncü taraf depolardaki dosyaları görüntüleme hakkında daha fazla bilgi[GroupDocs.Viewer ile belge nasıl yüklenir ve görüntülenir?](https://docs.groupdocs.com/display/viewernet/Loading)

### Ayrıca bakınız

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
