---
title: Page
second_title: GroupDocs.Viewer for .NET API Reference
description: Initializes new instance of Pagegroupdocs.viewer.results/page class.
type: docs
weight: 10
url: /net/groupdocs.viewer.results/page/page/
---
## Page() {#constructor}

Initializes new instance of [`Page`](../../page) class.

```csharp
public Page()
```

### See Also

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../page)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool) {#constructor_1}

Initializes new instance of [`Page`](../../page) class.

```csharp
public Page(int number, bool visible)
```

| Parameter | Type | Description |
| --- | --- | --- |
| number | Int32 | The page number. |
| visible | Boolean | The page visibility indicator. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *number* is less or equal to zero. |

### See Also

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../page)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_4}

Initializes new instance of [`Page`](../../page) class.

```csharp
public Page(int number, string name, bool visible)
```

| Parameter | Type | Description |
| --- | --- | --- |
| number | Int32 | The page number. |
| name | String | The worksheet or page name. |
| visible | Boolean | The page visibility indicator. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *number* is less or equal to zero. |

### See Also

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../page)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_2}

Initializes new instance of [`Page`](../../page) class.

```csharp
public Page(int number, bool visible, int width, int height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| number | Int32 | The page number. |
| visible | Boolean | The page visibility indicator. |
| width | Int32 | The width of the page in pixels when viewing as JPG or PNG. |
| height | Int32 | The height of the page in pixels when viewing as JPG or PNG. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *number* is less or equal to zero. |
| ArgumentException | Thrown when *width* is less or equal to zero. |
| ArgumentException | Thrown when *height* is less or equal to zero. |

### See Also

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../page)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_5}

Initializes new instance of [`Page`](../../page) class.

```csharp
public Page(int number, string name, bool visible, int width, int height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| number | Int32 | The page number. |
| name | String | The worksheet or page name. |
| visible | Boolean | The page visibility indicator. |
| width | Int32 | The width of the page in pixels when viewing as JPG or PNG. |
| height | Int32 | The height of the page in pixels when viewing as JPG or PNG. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *number* is less or equal to zero. |
| ArgumentException | Thrown when *width* is less or equal to zero. |
| ArgumentException | Thrown when *height* is less or equal to zero. |

### See Also

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../page)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, List&lt;Line&gt;) {#constructor_3}

Initializes new instance of [`Page`](../../page) class.

```csharp
public Page(int number, bool visible, int width, int height, List<Line> lines)
```

| Parameter | Type | Description |
| --- | --- | --- |
| number | Int32 | The page number. |
| visible | Boolean | The page visibility indicator. |
| width | Int32 | The width of the page in pixels when viewing as JPG or PNG. |
| height | Int32 | The height of the page in pixels when viewing as JPG or PNG. |
| lines | List`1 | The lines contained by the page when viewing as JPG or PNG with enabled Text Extraction. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *number* is less or equal to zero. |
| ArgumentException | Thrown when *width* is less or equal to zero. |
| ArgumentException | Thrown when *height* is less or equal to zero. |
| ArgumentNullException | Thrown when *lines* is null. |

### See Also

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../page)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, List&lt;Line&gt;) {#constructor_6}

Initializes new instance of [`Page`](../../page) class.

```csharp
public Page(int number, string name, bool visible, int width, int height, List<Line> lines)
```

| Parameter | Type | Description |
| --- | --- | --- |
| number | Int32 | The page number. |
| name | String | The worksheet or page name. |
| visible | Boolean | The page visibility indicator. |
| width | Int32 | The width of the page in pixels when viewing as JPG or PNG. |
| height | Int32 | The height of the page in pixels when viewing as JPG or PNG. |
| lines | List`1 | The lines contained by the page when viewing as JPG or PNG with enabled Text Extraction. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *number* is less or equal to zero. |
| ArgumentException | Thrown when *width* is less or equal to zero. |
| ArgumentException | Thrown when *height* is less or equal to zero. |
| ArgumentNullException | Thrown when *lines* is null. |

### See Also

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../page)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
