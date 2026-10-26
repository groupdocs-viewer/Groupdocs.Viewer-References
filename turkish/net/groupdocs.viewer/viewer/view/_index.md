---
title: "View"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Belgenin tüm sayfalarının görünümünü oluşturur."
type: docs
weight: 90
url: /tr/net/groupdocs.viewer/viewer/view/
---

## View(ViewOptions) {#view}

Belgenin tüm sayfalarının görünümünü oluşturur.

```csharp
public void View(ViewOptions options)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| seçenekler | ViewOptions | Görünüm seçenekleri. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *options* null olduğunda fırlatılır. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Belgeyi açmak için şifre gerektiğinde atılır. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Belirtilen şifre yanlış olduğunda atılır. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Ek bulunamadığında fırlatılır. |

### Açıklamalar

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Ayrıca Bakınız

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Belgenin tüm sayfalarının görünümünü oluşturur.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| seçenekler | ViewOptions | Görünüm seçenekleri. |
| cancellationToken | CancellationToken | Mevcut görünüm sürecini iptal etmek için bir istek göndermek amacıyla iptal belirteci. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *options* null olduğunda fırlatılır. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Belgeyi açmak için şifre gerektiğinde atılır. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Belirtilen şifre yanlış olduğunda atılır. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Ek bulunamadığında fırlatılır. |

### Açıklamalar

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Ayrıca Bakınız

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Belgenin belirli sayfalarının görünümünü oluşturur.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| seçenekler | ViewOptions | Görünüm seçenekleri. |
| pageNumbers | Int32[] | Görüntülenecek sayfa numaraları. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *options* null olduğunda fırlatılır. |
| ArgumentNullException | *pageNumbers* null olduğunda atılır. |
| ArgumentException | *pageNumbers* boş olduğunda atılır. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Belgeyi açmak için şifre gerektiğinde atılır. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Belirtilen şifre yanlış olduğunda atılır. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Ek bulunamadığında fırlatılır. |

### Açıklamalar

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Ayrıca Bakınız

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Belgenin belirli sayfalarının görünümünü oluşturur.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| seçenekler | ViewOptions | Görünüm seçenekleri. |
| pageNumbers | CancellationToken | Görüntülenecek sayfa numaraları. |
| cancellationToken | Int32[] | İşlemi iptal etmek için iptal belirteci. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *options* null olduğunda fırlatılır. |
| ArgumentNullException | *pageNumbers* null olduğunda atılır. |
| ArgumentException | *pageNumbers* boş olduğunda atılır. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Belgeyi açmak için şifre gerektiğinde atılır. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Belirtilen şifre yanlış olduğunda atılır. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Ek bulunamadığında fırlatılır. |

### Açıklamalar

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Ayrıca Bakınız

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
