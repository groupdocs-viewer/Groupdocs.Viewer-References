---
title: "Seite"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der Klasse Pagegroupdocs.viewer.results/page."
type: docs
weight: 10
url: /de/net/groupdocs.viewer.results/page/page/
---

## Page() {#constructor}

Initialisiert eine neue Instanz der Klasse [`Page`](../../page).

```csharp
public Page()
```

### Siehe auch

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool) {#constructor_1}

Initialisiert eine neue Instanz der Klasse [`Page`](../../page).

```csharp
public Page(int number, bool visible)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Zahl | Int32 | Die Seitennummer. |
| sichtbar | Boolean | Der Sichtbarkeitsindikator der Seite. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *number* kleiner oder gleich null ist. |

### Siehe auch

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_4}

Initialisiert eine neue Instanz der Klasse [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Zahl | Int32 | Die Seitennummer. |
| Name | String | Der Arbeitsblatt- oder Seitenname. |
| sichtbar | Boolean | Der Sichtbarkeitsindikator der Seite. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *number* kleiner oder gleich null ist. |

### Siehe auch

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_2}

Initialisiert eine neue Instanz der Klasse [`Page`](../../page).

```csharp
public Page(int number, bool visible, int width, int height)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Zahl | Int32 | Die Seitennummer. |
| sichtbar | Boolean | Der Sichtbarkeitsindikator der Seite. |
| Breite | Int32 | Die Breite der Seite in Pixeln beim Anzeigen als JPG oder PNG. |
| Höhe | Int32 | Die Höhe der Seite in Pixeln beim Anzeigen als JPG oder PNG. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *number* kleiner oder gleich null ist. |
| ArgumentException | Wird ausgelöst, wenn *width* kleiner oder gleich Null ist. |
| ArgumentException | Wird ausgelöst, wenn *height* kleiner oder gleich Null ist. |

### Siehe auch

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_5}

Initialisiert eine neue Instanz der Klasse [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible, int width, int height)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Zahl | Int32 | Die Seitennummer. |
| Name | String | Der Arbeitsblatt- oder Seitenname. |
| sichtbar | Boolean | Der Sichtbarkeitsindikator der Seite. |
| Breite | Int32 | Die Breite der Seite in Pixeln beim Anzeigen als JPG oder PNG. |
| Höhe | Int32 | Die Höhe der Seite in Pixeln beim Anzeigen als JPG oder PNG. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *number* kleiner oder gleich null ist. |
| ArgumentException | Wird ausgelöst, wenn *width* kleiner oder gleich Null ist. |
| ArgumentException | Wird ausgelöst, wenn *height* kleiner oder gleich Null ist. |

### Siehe auch

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, List&lt;Line&gt;) {#constructor_3}

Initialisiert eine neue Instanz der Klasse [`Page`](../../page).

```csharp
public Page(int number, bool visible, int width, int height, List<Line> lines)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Zahl | Int32 | Die Seitennummer. |
| sichtbar | Boolean | Der Sichtbarkeitsindikator der Seite. |
| Breite | Int32 | Die Breite der Seite in Pixeln beim Anzeigen als JPG oder PNG. |
| Höhe | Int32 | Die Höhe der Seite in Pixeln beim Anzeigen als JPG oder PNG. |
| Zeilen | List`1 | Die Zeilen, die in der Seite enthalten sind, wenn sie als JPG oder PNG mit aktivierter Textextraktion angezeigt wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *number* kleiner oder gleich null ist. |
| ArgumentException | Wird ausgelöst, wenn *width* kleiner oder gleich Null ist. |
| ArgumentException | Wird ausgelöst, wenn *height* kleiner oder gleich Null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *lines* null ist. |

### Siehe auch

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, List&lt;Line&gt;) {#constructor_6}

Initialisiert eine neue Instanz der Klasse [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible, int width, int height, List<Line> lines)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Zahl | Int32 | Die Seitennummer. |
| Name | String | Der Arbeitsblatt- oder Seitenname. |
| sichtbar | Boolean | Der Sichtbarkeitsindikator der Seite. |
| Breite | Int32 | Die Breite der Seite in Pixeln beim Anzeigen als JPG oder PNG. |
| Höhe | Int32 | Die Höhe der Seite in Pixeln beim Anzeigen als JPG oder PNG. |
| Zeilen | List`1 | Die Zeilen, die in der Seite enthalten sind, wenn sie als JPG oder PNG mit aktivierter Textextraktion angezeigt wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *number* kleiner oder gleich null ist. |
| ArgumentException | Wird ausgelöst, wenn *width* kleiner oder gleich Null ist. |
| ArgumentException | Wird ausgelöst, wenn *height* kleiner oder gleich Null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *lines* null ist. |

### Siehe auch

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
