---
title: "Page"
second_title: "GroupDocs.Viewer för .NET API-referens"
description: "Initierar en ny instans av Pagegroupdocs.viewer.results/page‑klass."
type: docs
weight: 10
url: /sv/net/groupdocs.viewer.results/page/page/
---

## Page() {#constructor}

Initierar en ny instans av [`Page`](../../page)-klass.

```csharp
public Page()
```

### Se även

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool) {#constructor_1}

Initierar en ny instans av [`Page`](../../page)-klass.

```csharp
public Page(int number, bool visible)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nummer | Int32 | Sidnumret. |
| synlig | Boolean | Sidans synlighetsindikator. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas när *number* är mindre än eller lika med noll. |

### Se även

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_4}

Initierar en ny instans av [`Page`](../../page)-klass.

```csharp
public Page(int number, string name, bool visible)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nummer | Int32 | Sidnumret. |
| name | String | Arbetsbladets eller sidans namn. |
| synlig | Boolean | Sidans synlighetsindikator. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas när *number* är mindre än eller lika med noll. |

### Se även

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_2}

Initierar en ny instans av [`Page`](../../page)-klass.

```csharp
public Page(int number, bool visible, int width, int height)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nummer | Int32 | Sidnumret. |
| synlig | Boolean | Sidans synlighetsindikator. |
| bredd | Int32 | Sidans bredd i pixlar när den visas som JPG eller PNG. |
| höjd | Int32 | Sidans höjd i pixlar när den visas som JPG eller PNG. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas när *number* är mindre än eller lika med noll. |
| ArgumentException | Kastas när *width* är mindre än eller lika med noll. |
| ArgumentException | Kastas när *height* är mindre än eller lika med noll. |

### Se även

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_5}

Initierar en ny instans av [`Page`](../../page)-klass.

```csharp
public Page(int number, string name, bool visible, int width, int height)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nummer | Int32 | Sidnumret. |
| name | String | Arbetsbladets eller sidans namn. |
| synlig | Boolean | Sidans synlighetsindikator. |
| bredd | Int32 | Sidans bredd i pixlar när den visas som JPG eller PNG. |
| höjd | Int32 | Sidans höjd i pixlar när den visas som JPG eller PNG. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas när *number* är mindre än eller lika med noll. |
| ArgumentException | Kastas när *width* är mindre än eller lika med noll. |
| ArgumentException | Kastas när *height* är mindre än eller lika med noll. |

### Se även

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, List&lt;Line&gt;) {#constructor_3}

Initierar en ny instans av [`Page`](../../page)-klass.

```csharp
public Page(int number, bool visible, int width, int height, List<Line> lines)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nummer | Int32 | Sidnumret. |
| synlig | Boolean | Sidans synlighetsindikator. |
| bredd | Int32 | Sidans bredd i pixlar när den visas som JPG eller PNG. |
| höjd | Int32 | Sidans höjd i pixlar när den visas som JPG eller PNG. |
| rader | List`1 | Raderna som finns på sidan när den visas som JPG eller PNG med aktiverad textutvinning. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas när *number* är mindre än eller lika med noll. |
| ArgumentException | Kastas när *width* är mindre än eller lika med noll. |
| ArgumentException | Kastas när *height* är mindre än eller lika med noll. |
| ArgumentNullException | Kastas när *lines* är null. |

### Se även

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, List&lt;Line&gt;) {#constructor_6}

Initierar en ny instans av [`Page`](../../page)-klass.

```csharp
public Page(int number, string name, bool visible, int width, int height, List<Line> lines)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nummer | Int32 | Sidnumret. |
| name | String | Arbetsbladets eller sidans namn. |
| synlig | Boolean | Sidans synlighetsindikator. |
| bredd | Int32 | Sidans bredd i pixlar när den visas som JPG eller PNG. |
| höjd | Int32 | Sidans höjd i pixlar när den visas som JPG eller PNG. |
| rader | List`1 | Raderna som finns på sidan när den visas som JPG eller PNG med aktiverad textutvinning. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas när *number* är mindre än eller lika med noll. |
| ArgumentException | Kastas när *width* är mindre än eller lika med noll. |
| ArgumentException | Kastas när *height* är mindre än eller lika med noll. |
| ArgumentNullException | Kastas när *lines* är null. |

### Se även

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
