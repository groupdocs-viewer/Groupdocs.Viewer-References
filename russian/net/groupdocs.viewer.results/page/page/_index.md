---
title: "Page"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инициализирует новый экземпляр класса Pagegroupdocs.viewer.results/page."
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.results/page/page/
---

## Page() {#constructor}

Инициализирует новый экземпляр класса [`Page`](../../page).

```csharp
public Page()
```

### См. также

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool) {#constructor_1}

Инициализирует новый экземпляр класса [`Page`](../../page).

```csharp
public Page(int number, bool visible)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| число | Int32 | Номер страницы. |
| видимый | Boolean | Индикатор видимости страницы. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *number* меньше или равно нулю. |

### См. также

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_4}

Инициализирует новый экземпляр класса [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| число | Int32 | Номер страницы. |
| имя | String | Имя листа или страницы. |
| видимый | Boolean | Индикатор видимости страницы. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *number* меньше или равно нулю. |

### См. также

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_2}

Инициализирует новый экземпляр класса [`Page`](../../page).

```csharp
public Page(int number, bool visible, int width, int height)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| число | Int32 | Номер страницы. |
| видимый | Boolean | Индикатор видимости страницы. |
| width | Int32 | Ширина страницы в пикселях при просмотре в формате JPG или PNG. |
| height | Int32 | Высота страницы в пикселях при просмотре в формате JPG или PNG. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *number* меньше или равно нулю. |
| ArgumentException | Выбрасывается, когда *width* меньше или равен нулю. |
| ArgumentException | Выбрасывается, когда *height* меньше или равен нулю. |

### См. также

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_5}

Инициализирует новый экземпляр класса [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible, int width, int height)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| число | Int32 | Номер страницы. |
| имя | String | Имя листа или страницы. |
| видимый | Boolean | Индикатор видимости страницы. |
| width | Int32 | Ширина страницы в пикселях при просмотре в формате JPG или PNG. |
| height | Int32 | Высота страницы в пикселях при просмотре в формате JPG или PNG. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *number* меньше или равно нулю. |
| ArgumentException | Выбрасывается, когда *width* меньше или равен нулю. |
| ArgumentException | Выбрасывается, когда *height* меньше или равен нулю. |

### См. также

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, List&lt;Line&gt;) {#constructor_3}

Инициализирует новый экземпляр класса [`Page`](../../page).

```csharp
public Page(int number, bool visible, int width, int height, List<Line> lines)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| число | Int32 | Номер страницы. |
| видимый | Boolean | Индикатор видимости страницы. |
| width | Int32 | Ширина страницы в пикселях при просмотре в формате JPG или PNG. |
| height | Int32 | Высота страницы в пикселях при просмотре в формате JPG или PNG. |
| строки | List`1 | Строки, содержащиеся на странице при просмотре в формате JPG или PNG с включённым извлечением текста. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *number* меньше или равно нулю. |
| ArgumentException | Выбрасывается, когда *width* меньше или равен нулю. |
| ArgumentException | Выбрасывается, когда *height* меньше или равен нулю. |
| ArgumentNullException | Выбрасывается, когда *lines* равно null. |

### См. также

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, List&lt;Line&gt;) {#constructor_6}

Инициализирует новый экземпляр класса [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible, int width, int height, List<Line> lines)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| число | Int32 | Номер страницы. |
| имя | String | Имя листа или страницы. |
| видимый | Boolean | Индикатор видимости страницы. |
| width | Int32 | Ширина страницы в пикселях при просмотре в формате JPG или PNG. |
| height | Int32 | Высота страницы в пикселях при просмотре в формате JPG или PNG. |
| строки | List`1 | Строки, содержащиеся на странице при просмотре в формате JPG или PNG с включённым извлечением текста. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *number* меньше или равно нулю. |
| ArgumentException | Выбрасывается, когда *width* меньше или равен нулю. |
| ArgumentException | Выбрасывается, когда *height* меньше или равен нулю. |
| ArgumentNullException | Выбрасывается, когда *lines* равно null. |

### См. также

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
