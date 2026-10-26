---
title: "Page"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Inicializa una nueva instancia de la clase Pagegroupdocs.viewer.results/page."
type: docs
weight: 10
url: /es/net/groupdocs.viewer.results/page/page/
---

## Page() {#constructor}

Inicializa una nueva instancia de la clase [`Page`](../../page).

```csharp
public Page()
```

### Ver también

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool) {#constructor_1}

Inicializa una nueva instancia de la clase [`Page`](../../page).

```csharp
public Page(int number, bool visible)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| número | Int32 | El número de página. |
| visible | Boolean | El indicador de visibilidad de la página. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Lanzado cuando *number* es menor o igual a cero. |

### Ver también

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_4}

Inicializa una nueva instancia de la clase [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| número | Int32 | El número de página. |
| nombre | String | El nombre de la hoja de cálculo o página. |
| visible | Boolean | El indicador de visibilidad de la página. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Lanzado cuando *number* es menor o igual a cero. |

### Ver también

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_2}

Inicializa una nueva instancia de la clase [`Page`](../../page).

```csharp
public Page(int number, bool visible, int width, int height)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| número | Int32 | El número de página. |
| visible | Boolean | El indicador de visibilidad de la página. |
| width | Int32 | El ancho de la página en píxeles al visualizarse como JPG o PNG. |
| height | Int32 | La altura de la página en píxeles al visualizarse como JPG o PNG. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Lanzado cuando *number* es menor o igual a cero. |
| ArgumentException | Se lanza cuando *width* es menor o igual a cero. |
| ArgumentException | Se lanza cuando *height* es menor o igual a cero. |

### Ver también

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_5}

Inicializa una nueva instancia de la clase [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible, int width, int height)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| número | Int32 | El número de página. |
| nombre | String | El nombre de la hoja de cálculo o página. |
| visible | Boolean | El indicador de visibilidad de la página. |
| width | Int32 | El ancho de la página en píxeles al visualizarse como JPG o PNG. |
| height | Int32 | La altura de la página en píxeles al visualizarse como JPG o PNG. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Lanzado cuando *number* es menor o igual a cero. |
| ArgumentException | Se lanza cuando *width* es menor o igual a cero. |
| ArgumentException | Se lanza cuando *height* es menor o igual a cero. |

### Ver también

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, List&lt;Line&gt;) {#constructor_3}

Inicializa una nueva instancia de la clase [`Page`](../../page).

```csharp
public Page(int number, bool visible, int width, int height, List<Line> lines)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| número | Int32 | El número de página. |
| visible | Boolean | El indicador de visibilidad de la página. |
| width | Int32 | El ancho de la página en píxeles al visualizarse como JPG o PNG. |
| height | Int32 | La altura de la página en píxeles al visualizarse como JPG o PNG. |
| líneas | List`1 | Las líneas contenidas por la página al visualizarse como JPG o PNG con extracción de texto habilitada. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Lanzado cuando *number* es menor o igual a cero. |
| ArgumentException | Se lanza cuando *width* es menor o igual a cero. |
| ArgumentException | Se lanza cuando *height* es menor o igual a cero. |
| ArgumentNullException | Lanzado cuando *lines* es nulo. |

### Ver también

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, List&lt;Line&gt;) {#constructor_6}

Inicializa una nueva instancia de la clase [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible, int width, int height, List<Line> lines)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| número | Int32 | El número de página. |
| nombre | String | El nombre de la hoja de cálculo o página. |
| visible | Boolean | El indicador de visibilidad de la página. |
| width | Int32 | El ancho de la página en píxeles al visualizarse como JPG o PNG. |
| height | Int32 | La altura de la página en píxeles al visualizarse como JPG o PNG. |
| líneas | List`1 | Las líneas contenidas por la página al visualizarse como JPG o PNG con extracción de texto habilitada. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Lanzado cuando *number* es menor o igual a cero. |
| ArgumentException | Se lanza cuando *width* es menor o igual a cero. |
| ArgumentException | Se lanza cuando *height* es menor o igual a cero. |
| ArgumentNullException | Lanzado cuando *lines* es nulo. |

### Ver también

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
