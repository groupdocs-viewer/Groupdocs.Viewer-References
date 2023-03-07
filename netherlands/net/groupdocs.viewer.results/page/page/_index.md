---
title: Page
second_title: GroupDocs.Viewer voor .NET API-referentie
description: Initialiseert nieuw exemplaar vanPagegroupdocs.viewer.results/page klasse.
type: docs
weight: 10
url: /nl/net/groupdocs.viewer.results/page/page/
---
## Page() {#constructor}

Initialiseert nieuw exemplaar van[`Page`](../../page) klasse.

```csharp
public Page()
```

### Zie ook

* class [Page](../../page)
* naamruimte [GroupDocs.Viewer.Results](../../page)
* montage [GroupDocs.Viewer](../../../)

---

## Page(int, bool) {#constructor_1}

Initialiseert nieuw exemplaar van[`Page`](../../page) klasse.

```csharp
public Page(int number, bool visible)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| number | Int32 | Het paginanummer. |
| visible | Boolean | De indicator voor paginazichtbaarheid. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException | Wanneer gegooid*number* kleiner is dan of gelijk is aan nul. |

### Zie ook

* class [Page](../../page)
* naamruimte [GroupDocs.Viewer.Results](../../page)
* montage [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_4}

Initialiseert nieuw exemplaar van[`Page`](../../page) klasse.

```csharp
public Page(int number, string name, bool visible)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| number | Int32 | Het paginanummer. |
| name | String | De naam van het werkblad of de pagina. |
| visible | Boolean | De indicator voor paginazichtbaarheid. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException | Wanneer gegooid*number* kleiner is dan of gelijk is aan nul. |

### Zie ook

* class [Page](../../page)
* naamruimte [GroupDocs.Viewer.Results](../../page)
* montage [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_2}

Initialiseert nieuw exemplaar van[`Page`](../../page) klasse.

```csharp
public Page(int number, bool visible, int width, int height)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| number | Int32 | Het paginanummer. |
| visible | Boolean | De indicator voor paginazichtbaarheid. |
| width | Int32 | De breedte van de pagina in pixels bij weergave als JPG of PNG. |
| height | Int32 | De hoogte van de pagina in pixels bij weergave als JPG of PNG. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException | Wanneer gegooid*number* kleiner is dan of gelijk is aan nul. |
| ArgumentException | Wanneer gegooid*width* kleiner is dan of gelijk is aan nul. |
| ArgumentException | Wanneer gegooid*height* kleiner is dan of gelijk is aan nul. |

### Zie ook

* class [Page](../../page)
* naamruimte [GroupDocs.Viewer.Results](../../page)
* montage [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_5}

Initialiseert nieuw exemplaar van[`Page`](../../page) klasse.

```csharp
public Page(int number, string name, bool visible, int width, int height)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| number | Int32 | Het paginanummer. |
| name | String | De naam van het werkblad of de pagina. |
| visible | Boolean | De indicator voor paginazichtbaarheid. |
| width | Int32 | De breedte van de pagina in pixels bij weergave als JPG of PNG. |
| height | Int32 | De hoogte van de pagina in pixels bij weergave als JPG of PNG. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException | Wanneer gegooid*number* kleiner is dan of gelijk is aan nul. |
| ArgumentException | Wanneer gegooid*width* kleiner is dan of gelijk is aan nul. |
| ArgumentException | Wanneer gegooid*height* kleiner is dan of gelijk is aan nul. |

### Zie ook

* class [Page](../../page)
* naamruimte [GroupDocs.Viewer.Results](../../page)
* montage [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, List&lt;Line&gt;) {#constructor_3}

Initialiseert nieuw exemplaar van[`Page`](../../page) klasse.

```csharp
public Page(int number, bool visible, int width, int height, List<Line> lines)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| number | Int32 | Het paginanummer. |
| visible | Boolean | De indicator voor paginazichtbaarheid. |
| width | Int32 | De breedte van de pagina in pixels bij weergave als JPG of PNG. |
| height | Int32 | De hoogte van de pagina in pixels bij weergave als JPG of PNG. |
| lines | List`1 | De regels op de pagina bij weergave als JPG of PNG met ingeschakelde tekstextractie. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException | Wanneer gegooid*number* kleiner is dan of gelijk is aan nul. |
| ArgumentException | Wanneer gegooid*width* kleiner is dan of gelijk is aan nul. |
| ArgumentException | Wanneer gegooid*height* kleiner is dan of gelijk is aan nul. |
| ArgumentNullException | Wanneer gegooid*lines* is niets. |

### Zie ook

* class [Line](../../line)
* class [Page](../../page)
* naamruimte [GroupDocs.Viewer.Results](../../page)
* montage [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, List&lt;Line&gt;) {#constructor_6}

Initialiseert nieuw exemplaar van[`Page`](../../page) klasse.

```csharp
public Page(int number, string name, bool visible, int width, int height, List<Line> lines)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| number | Int32 | Het paginanummer. |
| name | String | De naam van het werkblad of de pagina. |
| visible | Boolean | De indicator voor paginazichtbaarheid. |
| width | Int32 | De breedte van de pagina in pixels bij weergave als JPG of PNG. |
| height | Int32 | De hoogte van de pagina in pixels bij weergave als JPG of PNG. |
| lines | List`1 | De regels op de pagina bij weergave als JPG of PNG met ingeschakelde tekstextractie. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentException | Wanneer gegooid*number* kleiner is dan of gelijk is aan nul. |
| ArgumentException | Wanneer gegooid*width* kleiner is dan of gelijk is aan nul. |
| ArgumentException | Wanneer gegooid*height* kleiner is dan of gelijk is aan nul. |
| ArgumentNullException | Wanneer gegooid*lines* is niets. |

### Zie ook

* class [Line](../../line)
* class [Page](../../page)
* naamruimte [GroupDocs.Viewer.Results](../../page)
* montage [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
