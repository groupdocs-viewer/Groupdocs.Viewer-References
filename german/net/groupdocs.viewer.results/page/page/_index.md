---
title: Page
second_title: GroupDocs.Viewer für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonPagegroupdocs.viewer.results/page Klasse.
type: docs
weight: 10
url: /de/net/groupdocs.viewer.results/page/page/
---
## Page(int, bool) {#constructor}

Initialisiert eine neue Instanz von[`Page`](../../page) Klasse.

```csharp
public Page(int number, bool visible)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| number | Int32 | Die Seitenzahl. |
| visible | Boolean | Die Sichtbarkeitsanzeige der Seite. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wann geworfen*number* kleiner oder gleich Null ist. |

### Siehe auch

* class [Page](../../page)
* namensraum [GroupDocs.Viewer.Results](../../page)
* Montage [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_3}

Initialisiert eine neue Instanz von[`Page`](../../page) Klasse.

```csharp
public Page(int number, string name, bool visible)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| number | Int32 | Die Seitenzahl. |
| name | String | Der Arbeitsblatt- oder Seitenname. |
| visible | Boolean | Die Sichtbarkeitsanzeige der Seite. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wann geworfen*number* kleiner oder gleich Null ist. |

### Siehe auch

* class [Page](../../page)
* namensraum [GroupDocs.Viewer.Results](../../page)
* Montage [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_1}

Initialisiert eine neue Instanz von[`Page`](../../page) Klasse.

```csharp
public Page(int number, bool visible, int width, int height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| number | Int32 | Die Seitenzahl. |
| visible | Boolean | Die Sichtbarkeitsanzeige der Seite. |
| width | Int32 | Die Breite der Seite in Pixeln bei der Anzeige als JPG oder PNG. |
| height | Int32 | Die Höhe der Seite in Pixeln bei der Anzeige als JPG oder PNG. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wann geworfen*number* kleiner oder gleich Null ist. |
| ArgumentException | Wann geworfen*width* kleiner oder gleich Null ist. |
| ArgumentException | Wann geworfen*height* kleiner oder gleich Null ist. |

### Siehe auch

* class [Page](../../page)
* namensraum [GroupDocs.Viewer.Results](../../page)
* Montage [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_4}

Initialisiert eine neue Instanz von[`Page`](../../page) Klasse.

```csharp
public Page(int number, string name, bool visible, int width, int height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| number | Int32 | Die Seitenzahl. |
| name | String | Der Arbeitsblatt- oder Seitenname. |
| visible | Boolean | Die Sichtbarkeitsanzeige der Seite. |
| width | Int32 | Die Breite der Seite in Pixeln bei der Anzeige als JPG oder PNG. |
| height | Int32 | Die Höhe der Seite in Pixeln bei der Anzeige als JPG oder PNG. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wann geworfen*number* kleiner oder gleich Null ist. |
| ArgumentException | Wann geworfen*width* kleiner oder gleich Null ist. |
| ArgumentException | Wann geworfen*height* kleiner oder gleich Null ist. |

### Siehe auch

* class [Page](../../page)
* namensraum [GroupDocs.Viewer.Results](../../page)
* Montage [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, IList&lt;Line&gt;) {#constructor_2}

Initialisiert eine neue Instanz von[`Page`](../../page) Klasse.

```csharp
public Page(int number, bool visible, int width, int height, IList<Line> lines)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| number | Int32 | Die Seitenzahl. |
| visible | Boolean | Die Sichtbarkeitsanzeige der Seite. |
| width | Int32 | Die Breite der Seite in Pixeln bei der Anzeige als JPG oder PNG. |
| height | Int32 | Die Höhe der Seite in Pixeln bei der Anzeige als JPG oder PNG. |
| lines | IList`1 | Die auf der Seite enthaltenen Zeilen bei der Anzeige als JPG oder PNG mit aktivierter Textextraktion. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wann geworfen*number* kleiner oder gleich Null ist. |
| ArgumentException | Wann geworfen*width* kleiner oder gleich Null ist. |
| ArgumentException | Wann geworfen*height* kleiner oder gleich Null ist. |
| ArgumentNullException | Wann geworfen*lines* ist Null. |

### Siehe auch

* class [Line](../../line)
* class [Page](../../page)
* namensraum [GroupDocs.Viewer.Results](../../page)
* Montage [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, IList&lt;Line&gt;) {#constructor_5}

Initialisiert eine neue Instanz von[`Page`](../../page) Klasse.

```csharp
public Page(int number, string name, bool visible, int width, int height, IList<Line> lines)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| number | Int32 | Die Seitenzahl. |
| name | String | Der Arbeitsblatt- oder Seitenname. |
| visible | Boolean | Die Sichtbarkeitsanzeige der Seite. |
| width | Int32 | Die Breite der Seite in Pixeln bei der Anzeige als JPG oder PNG. |
| height | Int32 | Die Höhe der Seite in Pixeln bei der Anzeige als JPG oder PNG. |
| lines | IList`1 | Die auf der Seite enthaltenen Zeilen bei der Anzeige als JPG oder PNG mit aktivierter Textextraktion. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wann geworfen*number* kleiner oder gleich Null ist. |
| ArgumentException | Wann geworfen*width* kleiner oder gleich Null ist. |
| ArgumentException | Wann geworfen*height* kleiner oder gleich Null ist. |
| ArgumentNullException | Wann geworfen*lines* ist Null. |

### Siehe auch

* class [Line](../../line)
* class [Page](../../page)
* namensraum [GroupDocs.Viewer.Results](../../page)
* Montage [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
