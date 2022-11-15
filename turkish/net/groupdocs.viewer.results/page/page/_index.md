---
title: Page
second_title: .NET API Başvurusu için GroupDocs.Viewer
description: Yeni örneğini başlatırPagegroupdocs.viewer.results/page sınıf.
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.results/page/page/
---
## Page(int, bool) {#constructor}

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
| ArgumentException | ne zaman atıldı*number* sıfıra eşit veya küçüktür. |

### Ayrıca bakınız

* class [Page](../../page)
* ad alanı [GroupDocs.Viewer.Results](../../page)
* toplantı [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_3}

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
| ArgumentException | ne zaman atıldı*number* sıfıra eşit veya küçüktür. |

### Ayrıca bakınız

* class [Page](../../page)
* ad alanı [GroupDocs.Viewer.Results](../../page)
* toplantı [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_1}

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
| ArgumentException | ne zaman atıldı*number* sıfıra eşit veya küçüktür. |
| ArgumentException | ne zaman atıldı*width* sıfıra eşit veya küçüktür. |
| ArgumentException | ne zaman atıldı*height* sıfıra eşit veya küçüktür. |

### Ayrıca bakınız

* class [Page](../../page)
* ad alanı [GroupDocs.Viewer.Results](../../page)
* toplantı [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_4}

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
| ArgumentException | ne zaman atıldı*number* sıfıra eşit veya küçüktür. |
| ArgumentException | ne zaman atıldı*width* sıfıra eşit veya küçüktür. |
| ArgumentException | ne zaman atıldı*height* sıfıra eşit veya küçüktür. |

### Ayrıca bakınız

* class [Page](../../page)
* ad alanı [GroupDocs.Viewer.Results](../../page)
* toplantı [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, IList&lt;Line&gt;) {#constructor_2}

Yeni örneğini başlatır[`Page`](../../page) sınıf.

```csharp
public Page(int number, bool visible, int width, int height, IList<Line> lines)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| number | Int32 | Sayfa numarası. |
| visible | Boolean | Sayfa görünürlüğü göstergesi. |
| width | Int32 | JPG veya PNG olarak görüntülerken sayfanın piksel cinsinden genişliği. |
| height | Int32 | JPG veya PNG olarak görüntülerken sayfanın piksel cinsinden yüksekliği. |
| lines | IList`1 | Metin Çıkarma etkinken JPG veya PNG olarak görüntülerken sayfanın içerdiği satırlar. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | ne zaman atıldı*number* sıfıra eşit veya küçüktür. |
| ArgumentException | ne zaman atıldı*width* sıfıra eşit veya küçüktür. |
| ArgumentException | ne zaman atıldı*height* sıfıra eşit veya küçüktür. |
| ArgumentNullException | ne zaman atıldı*lines* boş. |

### Ayrıca bakınız

* class [Line](../../line)
* class [Page](../../page)
* ad alanı [GroupDocs.Viewer.Results](../../page)
* toplantı [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, IList&lt;Line&gt;) {#constructor_5}

Yeni örneğini başlatır[`Page`](../../page) sınıf.

```csharp
public Page(int number, string name, bool visible, int width, int height, IList<Line> lines)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| number | Int32 | Sayfa numarası. |
| name | String | Çalışma sayfası veya sayfa adı. |
| visible | Boolean | Sayfa görünürlüğü göstergesi. |
| width | Int32 | JPG veya PNG olarak görüntülerken sayfanın piksel cinsinden genişliği. |
| height | Int32 | JPG veya PNG olarak görüntülerken sayfanın piksel cinsinden yüksekliği. |
| lines | IList`1 | Metin Çıkarma etkinken JPG veya PNG olarak görüntülerken sayfanın içerdiği satırlar. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | ne zaman atıldı*number* sıfıra eşit veya küçüktür. |
| ArgumentException | ne zaman atıldı*width* sıfıra eşit veya küçüktür. |
| ArgumentException | ne zaman atıldı*height* sıfıra eşit veya küçüktür. |
| ArgumentNullException | ne zaman atıldı*lines* boş. |

### Ayrıca bakınız

* class [Line](../../line)
* class [Page](../../page)
* ad alanı [GroupDocs.Viewer.Results](../../page)
* toplantı [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
