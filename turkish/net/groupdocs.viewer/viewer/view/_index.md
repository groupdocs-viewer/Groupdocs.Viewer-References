---
title: View
second_title: .NET API Başvurusu için GroupDocs.Viewer
description: Tüm belge sayfalarının görünümünü oluşturur.
type: docs
weight: 70
url: /tr/net/groupdocs.viewer/viewer/view/
---
## View(ViewOptions) {#view}

Tüm belge sayfalarının görünümünü oluşturur.

```csharp
public void View(ViewOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| options | ViewOptions | Görünüm seçenekleri. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*options* boş. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Belgeyi açmak için parola gerektiğinde atılır. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Belirtilen şifre yanlış olduğunda atılır. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Eklenti bulunamadığında atılır. |

### Notlar

**Daha fazla bilgi edin**

* Bu kılavuzu izleyerek farklı görüntüleme seçenekleri hakkında daha fazla bilgi edinin: [GroupDocs.Viewer kullanılarak belge görüntüleme çıktısı nasıl özelleştirilir](https://docs.groupdocs.com/display/viewernet/Viewing)

### Ayrıca bakınız

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Tüm belge sayfalarının görünümünü oluşturur.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| options | ViewOptions | Görünüm seçenekleri. |
| cancellationToken | CancellationToken | Geçerli görüntüleme sürecini iptal etmek için bir istek göndermek için iptal belirteci. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*options* boş. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Belgeyi açmak için parola gerektiğinde atılır. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Belirtilen şifre yanlış olduğunda atılır. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Eklenti bulunamadığında atılır. |

### Notlar

**Daha fazla bilgi edin**

* Bu kılavuzu izleyerek farklı görüntüleme seçenekleri hakkında daha fazla bilgi edinin: [GroupDocs.Viewer kullanılarak belge görüntüleme çıktısı nasıl özelleştirilir](https://docs.groupdocs.com/display/viewernet/Viewing)

### Ayrıca bakınız

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Belirli belge sayfalarının görünümünü oluşturur.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| options | ViewOptions | Görünüm seçenekleri. |
| pageNumbers | Int32[] | Görüntülenecek sayfa numaraları. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*options* boş. |
| ArgumentNullException | Ne zaman atıldı*pageNumbers* boş. |
| ArgumentException | Ne zaman atıldı*pageNumbers* boş. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Belgeyi açmak için parola gerektiğinde atılır. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Belirtilen şifre yanlış olduğunda atılır. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Eklenti bulunamadığında atılır. |

### Notlar

**Daha fazla bilgi edin**

* Bu kılavuzu izleyerek farklı görüntüleme seçenekleri hakkında daha fazla bilgi edinin: [GroupDocs.Viewer kullanılarak belge görüntüleme çıktısı nasıl özelleştirilir](https://docs.groupdocs.com/display/viewernet/Viewing)

### Ayrıca bakınız

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Belirli belge sayfalarının görünümünü oluşturur.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| options | ViewOptions | Görünüm seçenekleri. |
| pageNumbers | CancellationToken | Görüntülenecek sayfa numaraları. |
| cancellationToken | Int32[] | İşlemi iptal etmek için iptal belirteci. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*options* boş. |
| ArgumentNullException | Ne zaman atıldı*pageNumbers* boş. |
| ArgumentException | Ne zaman atıldı*pageNumbers* boş. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Belgeyi açmak için parola gerektiğinde atılır. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Belirtilen şifre yanlış olduğunda atılır. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Eklenti bulunamadığında atılır. |

### Notlar

**Daha fazla bilgi edin**

* Bu kılavuzu izleyerek farklı görüntüleme seçenekleri hakkında daha fazla bilgi edinin: [GroupDocs.Viewer kullanılarak belge görüntüleme çıktısı nasıl özelleştirilir](https://docs.groupdocs.com/display/viewernet/Viewing)

### Ayrıca bakınız

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* ad alanı [GroupDocs.Viewer](../../viewer)
* toplantı [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
