---
title: "Viewer"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Viewergroupdocs.viewer/viewer sınıfının yeni bir örneğini başlatır."
type: docs
weight: 10
url: /tr/net/groupdocs.viewer/viewer/viewer/
---

## Viewer(Func&lt;Stream&gt;) {#constructor}

[`Viewer`](../../viewer) sınıfının yeni bir örneğini başlatır.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| getFileStream | Func`1 | Okunabilir akışı döndüren yöntem. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *getFileStream* null olduğunda atılır. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ayrıca Bakınız

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

[`Viewer`](../../viewer) sınıfının yeni bir örneğini başlatır.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| getFileStream | Func`1 | Okunabilir akışı döndüren yöntem. |
| getLoadOptions | Func`1 | Belge yükleme seçeneklerini döndüren yöntemler. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *getFileStream* null olduğunda atılır. |
| ArgumentNullException | *getLoadOptions* null olduğunda atılır. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ayrıca Bakınız

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

[`Viewer`](../../viewer) sınıfının yeni bir örneğini başlatır.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| getFileStream | Func`1 | Okunabilir akışı döndüren yöntem. |
| settings | ViewerSettings | Viewer ayarları. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *getFileStream* null olduğunda atılır. |
| ArgumentNullException | *settings* null olduğunda atılır. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ayrıca Bakınız

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

[`Viewer`](../../viewer) sınıfının yeni bir örneğini başlatır.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| getFileStream | Func`1 | Okunabilir akışı döndüren yöntem. |
| getLoadOptions | Func`1 | Belge yükleme seçeneklerini döndüren yöntemler. |
| settings | ViewerSettings | Viewer ayarları. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *getFileStream* null olduğunda atılır. |
| ArgumentNullException | *getLoadOptions* null olduğunda atılır. |
| ArgumentNullException | *settings* null olduğunda atılır. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ayrıca Bakınız

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

[`Viewer`](../../viewer) sınıfının yeni bir örneğini başlatır.

```csharp
public Viewer(Stream stream)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| akış | Akış | Dosya akışı. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *stream* null olduğunda atılır. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ayrıca Bakınız

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

[`Viewer`](../../viewer) sınıfının yeni bir örneğini başlatır.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| akış | Akış | Dosya akışı. |
| leaveOpen | Boolean | Viewer nesnesi yok edildiğinde akışı açık bırakmak için true; aksi takdirde false. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *stream* null olduğunda atılır. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ayrıca Bakınız

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

[`Viewer`](../../viewer) sınıfının yeni bir örneğini başlatır.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| akış | Akış | Dosya akışı. |
| loadOptions | LoadOptions | Belge yükleme seçenekleri. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *stream* null olduğunda atılır. |
| ArgumentNullException | *loadOptions* null olduğunda atılır. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ayrıca Bakınız

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

[`Viewer`](../../viewer) sınıfının yeni bir örneğini başlatır.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| akış | Akış | Dosya akışı. |
| loadOptions | LoadOptions | Belge yükleme seçenekleri. |
| leaveOpen | Boolean | Viewer nesnesi yok edildiğinde akışı açık bırakmak için true; aksi takdirde false. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *stream* null olduğunda atılır. |
| ArgumentNullException | *loadOptions* null olduğunda atılır. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ayrıca Bakınız

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

[`Viewer`](../../viewer) sınıfının yeni bir örneğini başlatır.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| akış | Akış | Dosya akışı. |
| settings | ViewerSettings | Viewer ayarları. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *stream* null olduğunda atılır. |
| ArgumentNullException | *settings* null olduğunda atılır. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ayrıca Bakınız

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

[`Viewer`](../../viewer) sınıfının yeni bir örneğini başlatır.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| akış | Akış | Dosya akışı. |
| settings | ViewerSettings | Viewer ayarları. |
| leaveOpen | Boolean | Viewer nesnesi yok edildiğinde akışı açık bırakmak için true; aksi takdirde false. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *stream* null olduğunda atılır. |
| ArgumentNullException | *settings* null olduğunda atılır. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ayrıca Bakınız

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

[`Viewer`](../../viewer) sınıfının yeni bir örneğini başlatır.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| akış | Akış | Dosya akışı. |
| loadOptions | LoadOptions | Belge yükleme seçenekleri. |
| settings | ViewerSettings | Viewer ayarları. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *stream* null olduğunda atılır. |
| ArgumentNullException | *loadOptions* null olduğunda atılır. |
| ArgumentNullException | *settings* null olduğunda atılır. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ayrıca Bakınız

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

[`Viewer`](../../viewer) sınıfının yeni bir örneğini başlatır.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| akış | Akış | Dosya akışı. |
| loadOptions | LoadOptions | Belge yükleme seçenekleri. |
| settings | ViewerSettings | Viewer ayarları. |
| leaveOpen | Boolean | Viewer nesnesi yok edildiğinde akışı açık bırakmak için true; aksi takdirde false. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *stream* null olduğunda atılır. |
| ArgumentNullException | *loadOptions* null olduğunda atılır. |
| ArgumentNullException | *settings* null olduğunda atılır. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ayrıca Bakınız

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

[`Viewer`](../../viewer) sınıfının yeni bir örneğini başlatır.

```csharp
public Viewer(string filePath)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| filePath | String | Render edilecek dosyanın yolu. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *filePath* null veya boş olduğunda atılır. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ayrıca Bakınız

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

[`Viewer`](../../viewer) sınıfının yeni bir örneğini başlatır.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| filePath | String | Render edilecek dosyanın yolu. |
| settings | ViewerSettings | Viewer ayarları. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *filePath* null veya boş olduğunda atılır. |
| ArgumentNullException | *settings* null olduğunda atılır. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ayrıca Bakınız

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

[`Viewer`](../../viewer) sınıfının yeni bir örneğini başlatır.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| filePath | String | Render edilecek dosyanın yolu. |
| loadOptions | LoadOptions | Dosyayı açmak için kullanılan seçenekler. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *filePath* null veya boş olduğunda atılır. |
| ArgumentNullException | *loadOptions* null olduğunda atılır. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ayrıca Bakınız

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

[`Viewer`](../../viewer) sınıfının yeni bir örneğini başlatır.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| filePath | String | Render edilecek dosyanın yolu. |
| loadOptions | LoadOptions | Dosyayı açmak için kullanılan seçenekler. |
| settings | ViewerSettings | Viewer ayarları. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *filePath* null veya boş olduğunda atılır. |
| ArgumentNullException | *loadOptions* null olduğunda atılır. |
| ArgumentNullException | *settings* null olduğunda atılır. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ayrıca Bakınız

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
