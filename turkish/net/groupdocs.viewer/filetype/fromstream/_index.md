---
title: "FromStream"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Dosya imzasını okuyarak dosya türünü algılar."
type: docs
weight: 2000
url: /tr/net/groupdocs.viewer/filetype/fromstream/
---

## FromStream(Stream) {#fromstream}

Dosya imzasını okuyarak dosya türünü algılar.

```csharp
public static FileType FromStream(Stream stream)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| akış | Akış | Dosya akışı. |

### Ayrıca Bakınız

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, string) {#fromstream_2}

Dosya imzasını okuyarak dosya türünü algılar.

```csharp
public static FileType FromStream(Stream stream, string password)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| akış | Akış | Dosya akışı. |
| parola | String | Dosyayı açmak için parola. |

### Ayrıca Bakınız

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, ILogger) {#fromstream_1}

Dosya imzasını okuyarak dosya türünü algılar.

```csharp
public static FileType FromStream(Stream stream, ILogger logger)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| akış | Akış | Dosya akışı. |
| logger | ILogger | Günlükleyici. |

### Dönüş Değeri

Dosya türü başarıyla tespit edildiğinde dosya türünü döndürür, aksi takdirde varsayılan [`Unknown`](../unknown) dosya türünü döndürür.

### Ayrıca Bakınız

* interface [ILogger](../../../groupdocs.viewer.logging/ilogger)
* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, string, ILogger) {#fromstream_3}

Dosya imzasını okuyarak dosya türünü algılar.

```csharp
public static FileType FromStream(Stream stream, string password, ILogger logger)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| akış | Akış | Dosya akışı. |
| parola | String | Dosyayı açmak için parola. |
| logger | ILogger | Günlükleyici. |

### Dönüş Değeri

Dosya türü başarıyla tespit edildiğinde dosya türünü döndürür, aksi takdirde varsayılan [`Unknown`](../unknown) dosya türünü döndürür.

### Ayrıca Bakınız

* interface [ILogger](../../../groupdocs.viewer.logging/ilogger)
* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
