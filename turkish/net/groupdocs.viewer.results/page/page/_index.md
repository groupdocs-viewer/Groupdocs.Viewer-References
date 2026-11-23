---
title: "Page"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Pagegroupdocs.viewer.results/page sınıfının yeni bir örneğini başlatır."
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.results/page/page/
---

## Page() {#constructor}

[`Page`](../../page) sınıfının yeni bir örneğini başlatır.

```csharp
public Page()
```

### Ayrıca Bakınız

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool) {#constructor_1}

[`Page`](../../page) sınıfının yeni bir örneğini başlatır.

```csharp
public Page(int number, bool visible)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| sayı | Int32 | Sayfa numarası. |
| görünür | Boolean | Sayfa görünürlük göstergesi. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *number* sıfırdan küçük veya eşit olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_4}

[`Page`](../../page) sınıfının yeni bir örneğini başlatır.

```csharp
public Page(int number, string name, bool visible)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| sayı | Int32 | Sayfa numarası. |
| ad | String | Çalışma sayfası veya sayfa adı. |
| görünür | Boolean | Sayfa görünürlük göstergesi. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *number* sıfırdan küçük veya eşit olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_2}

[`Page`](../../page) sınıfının yeni bir örneğini başlatır.

```csharp
public Page(int number, bool visible, int width, int height)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| sayı | Int32 | Sayfa numarası. |
| görünür | Boolean | Sayfa görünürlük göstergesi. |
| width | Int32 | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden genişliği. |
| height | Int32 | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden yüksekliği. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *number* sıfırdan küçük veya eşit olduğunda fırlatılır. |
| ArgumentException | *width* sıfırdan küçük veya eşit olduğunda fırlatılır. |
| ArgumentException | *height* sıfırdan küçük veya eşit olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_5}

[`Page`](../../page) sınıfının yeni bir örneğini başlatır.

```csharp
public Page(int number, string name, bool visible, int width, int height)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| sayı | Int32 | Sayfa numarası. |
| ad | String | Çalışma sayfası veya sayfa adı. |
| görünür | Boolean | Sayfa görünürlük göstergesi. |
| width | Int32 | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden genişliği. |
| height | Int32 | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden yüksekliği. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *number* sıfırdan küçük veya eşit olduğunda fırlatılır. |
| ArgumentException | *width* sıfırdan küçük veya eşit olduğunda fırlatılır. |
| ArgumentException | *height* sıfırdan küçük veya eşit olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, List&lt;Line&gt;) {#constructor_3}

[`Page`](../../page) sınıfının yeni bir örneğini başlatır.

```csharp
public Page(int number, bool visible, int width, int height, List<Line> lines)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| sayı | Int32 | Sayfa numarası. |
| görünür | Boolean | Sayfa görünürlük göstergesi. |
| width | Int32 | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden genişliği. |
| height | Int32 | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden yüksekliği. |
| satırlar | List`1 | Metin Çıkarma etkinleştirildiğinde JPG veya PNG olarak görüntülendiğinde sayfadaki satırlar. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *number* sıfırdan küçük veya eşit olduğunda fırlatılır. |
| ArgumentException | *width* sıfırdan küçük veya eşit olduğunda fırlatılır. |
| ArgumentException | *height* sıfırdan küçük veya eşit olduğunda fırlatılır. |
| ArgumentNullException | *lines* null olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, List&lt;Line&gt;) {#constructor_6}

[`Page`](../../page) sınıfının yeni bir örneğini başlatır.

```csharp
public Page(int number, string name, bool visible, int width, int height, List<Line> lines)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| sayı | Int32 | Sayfa numarası. |
| ad | String | Çalışma sayfası veya sayfa adı. |
| görünür | Boolean | Sayfa görünürlük göstergesi. |
| width | Int32 | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden genişliği. |
| height | Int32 | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden yüksekliği. |
| satırlar | List`1 | Metin Çıkarma etkinleştirildiğinde JPG veya PNG olarak görüntülendiğinde sayfadaki satırlar. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *number* sıfırdan küçük veya eşit olduğunda fırlatılır. |
| ArgumentException | *width* sıfırdan küçük veya eşit olduğunda fırlatılır. |
| ArgumentException | *height* sıfırdan küçük veya eşit olduğunda fırlatılır. |
| ArgumentNullException | *lines* null olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
