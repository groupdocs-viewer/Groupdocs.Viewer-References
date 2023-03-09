---
title: Page
second_title: .NET API Başvurusu için GroupDocs.Viewer
description: Yeni örneğini başlatırPagegroupdocs.viewer.results/page sınıf.
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.results/page/page/
---
## Page() {#constructor}

Yeni örneğini başlatır[`Page`](../../page) sınıf.

```csharp
public Page()
```

### Ayrıca bakınız

* class [Page](../../page)
* ad alanı [GroupDocs.Viewer.Results](../../page)
* toplantı [GroupDocs.Viewer](../../../)

---

## Page(int, bool) {#constructor_1}

Yeni örneğini başlatır[`Page`](../../page) sınıf.

```csharp
public Page(int number, bool visible)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| number | Int32 | Sayfa numarası. |
| visible | Boolean | Sayfa görünürlüğü göstergesi. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | Ne zaman atıldı*number* sıfırdan küçük veya eşittir. |

### Ayrıca bakınız

* class [Page](../../page)
* ad alanı [GroupDocs.Viewer.Results](../../page)
* toplantı [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_4}

Yeni örneğini başlatır[`Page`](../../page) sınıf.

```csharp
public Page(int number, string name, bool visible)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| number | Int32 | Sayfa numarası. |
| name | String | Çalışma sayfası veya sayfa adı. |
| visible | Boolean | Sayfa görünürlüğü göstergesi. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | Ne zaman atıldı*number* sıfırdan küçük veya eşittir. |

### Ayrıca bakınız

* class [Page](../../page)
* ad alanı [GroupDocs.Viewer.Results](../../page)
* toplantı [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_2}

Yeni örneğini başlatır[`Page`](../../page) sınıf.

```csharp
public Page(int number, bool visible, int width, int height)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| number | Int32 | Sayfa numarası. |
| visible | Boolean | Sayfa görünürlüğü göstergesi. |
| width | Int32 | JPG veya PNG olarak görüntülerken sayfanın piksel cinsinden genişliği. |
| height | Int32 | JPG veya PNG olarak görüntülerken sayfanın piksel cinsinden yüksekliği. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | Ne zaman atıldı*number* sıfırdan küçük veya eşittir. |
| ArgumentException | Ne zaman atıldı*width* sıfırdan küçük veya eşittir. |
| ArgumentException | Ne zaman atıldı*height* sıfırdan küçük veya eşittir. |

### Ayrıca bakınız

* class [Page](../../page)
* ad alanı [GroupDocs.Viewer.Results](../../page)
* toplantı [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_5}

Yeni örneğini başlatır[`Page`](../../page) sınıf.

```csharp
public Page(int number, string name, bool visible, int width, int height)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| number | Int32 | Sayfa numarası. |
| name | String | Çalışma sayfası veya sayfa adı. |
| visible | Boolean | Sayfa görünürlüğü göstergesi. |
| width | Int32 | JPG veya PNG olarak görüntülerken sayfanın piksel cinsinden genişliği. |
| height | Int32 | JPG veya PNG olarak görüntülerken sayfanın piksel cinsinden yüksekliği. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | Ne zaman atıldı*number* sıfırdan küçük veya eşittir. |
| ArgumentException | Ne zaman atıldı*width* sıfırdan küçük veya eşittir. |
| ArgumentException | Ne zaman atıldı*height* sıfırdan küçük veya eşittir. |

### Ayrıca bakınız

* class [Page](../../page)
* ad alanı [GroupDocs.Viewer.Results](../../page)
* toplantı [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, List&lt;Line&gt;) {#constructor_3}

Yeni örneğini başlatır[`Page`](../../page) sınıf.

```csharp
public Page(int number, bool visible, int width, int height, List<Line> lines)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| number | Int32 | Sayfa numarası. |
| visible | Boolean | Sayfa görünürlüğü göstergesi. |
| width | Int32 | JPG veya PNG olarak görüntülerken sayfanın piksel cinsinden genişliği. |
| height | Int32 | JPG veya PNG olarak görüntülerken sayfanın piksel cinsinden yüksekliği. |
| lines | List`1 | Metin Çıkarma etkinken JPG veya PNG olarak görüntülerken sayfanın içerdiği satırlar. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | Ne zaman atıldı*number* sıfırdan küçük veya eşittir. |
| ArgumentException | Ne zaman atıldı*width* sıfırdan küçük veya eşittir. |
| ArgumentException | Ne zaman atıldı*height* sıfırdan küçük veya eşittir. |
| ArgumentNullException | Ne zaman atıldı*lines* boş. |

### Ayrıca bakınız

* class [Line](../../line)
* class [Page](../../page)
* ad alanı [GroupDocs.Viewer.Results](../../page)
* toplantı [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, List&lt;Line&gt;) {#constructor_6}

Yeni örneğini başlatır[`Page`](../../page) sınıf.

```csharp
public Page(int number, string name, bool visible, int width, int height, List<Line> lines)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| number | Int32 | Sayfa numarası. |
| name | String | Çalışma sayfası veya sayfa adı. |
| visible | Boolean | Sayfa görünürlüğü göstergesi. |
| width | Int32 | JPG veya PNG olarak görüntülerken sayfanın piksel cinsinden genişliği. |
| height | Int32 | JPG veya PNG olarak görüntülerken sayfanın piksel cinsinden yüksekliği. |
| lines | List`1 | Metin Çıkarma etkinken JPG veya PNG olarak görüntülerken sayfanın içerdiği satırlar. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | Ne zaman atıldı*number* sıfırdan küçük veya eşittir. |
| ArgumentException | Ne zaman atıldı*width* sıfırdan küçük veya eşittir. |
| ArgumentException | Ne zaman atıldı*height* sıfırdan küçük veya eşittir. |
| ArgumentNullException | Ne zaman atıldı*lines* boş. |

### Ayrıca bakınız

* class [Line](../../line)
* class [Page](../../page)
* ad alanı [GroupDocs.Viewer.Results](../../page)
* toplantı [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
