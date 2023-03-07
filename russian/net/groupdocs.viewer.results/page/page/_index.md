---
title: Page
second_title: Справочник по API GroupDocs.Viewer для .NET
description: Инициализирует новый экземплярPagegroupdocs.viewer.results/page класс.
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.results/page/page/
---
## Page() {#constructor}

Инициализирует новый экземпляр[`Page`](../../page) класс.

```csharp
public Page()
```

### Смотрите также

* class [Page](../../page)
* пространство имен [GroupDocs.Viewer.Results](../../page)
* сборка [GroupDocs.Viewer](../../../)

---

## Page(int, bool) {#constructor_1}

Инициализирует новый экземпляр[`Page`](../../page) класс.

```csharp
public Page(int number, bool visible)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| number | Int32 | Номер страницы. |
| visible | Boolean | Индикатор видимости страницы. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Брошен, когда*number* меньше или равно нулю. |

### Смотрите также

* class [Page](../../page)
* пространство имен [GroupDocs.Viewer.Results](../../page)
* сборка [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_4}

Инициализирует новый экземпляр[`Page`](../../page) класс.

```csharp
public Page(int number, string name, bool visible)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| number | Int32 | Номер страницы. |
| name | String | Имя рабочего листа или страницы. |
| visible | Boolean | Индикатор видимости страницы. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Брошен, когда*number* меньше или равно нулю. |

### Смотрите также

* class [Page](../../page)
* пространство имен [GroupDocs.Viewer.Results](../../page)
* сборка [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_2}

Инициализирует новый экземпляр[`Page`](../../page) класс.

```csharp
public Page(int number, bool visible, int width, int height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| number | Int32 | Номер страницы. |
| visible | Boolean | Индикатор видимости страницы. |
| width | Int32 | Ширина страницы в пикселях при просмотре в формате JPG или PNG. |
| height | Int32 | Высота страницы в пикселях при просмотре в формате JPG или PNG. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Брошен, когда*number* меньше или равно нулю. |
| ArgumentException | Брошен, когда*width* меньше или равно нулю. |
| ArgumentException | Брошен, когда*height* меньше или равно нулю. |

### Смотрите также

* class [Page](../../page)
* пространство имен [GroupDocs.Viewer.Results](../../page)
* сборка [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_5}

Инициализирует новый экземпляр[`Page`](../../page) класс.

```csharp
public Page(int number, string name, bool visible, int width, int height)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| number | Int32 | Номер страницы. |
| name | String | Имя рабочего листа или страницы. |
| visible | Boolean | Индикатор видимости страницы. |
| width | Int32 | Ширина страницы в пикселях при просмотре в формате JPG или PNG. |
| height | Int32 | Высота страницы в пикселях при просмотре в формате JPG или PNG. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Брошен, когда*number* меньше или равно нулю. |
| ArgumentException | Брошен, когда*width* меньше или равно нулю. |
| ArgumentException | Брошен, когда*height* меньше или равно нулю. |

### Смотрите также

* class [Page](../../page)
* пространство имен [GroupDocs.Viewer.Results](../../page)
* сборка [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, List&lt;Line&gt;) {#constructor_3}

Инициализирует новый экземпляр[`Page`](../../page) класс.

```csharp
public Page(int number, bool visible, int width, int height, List<Line> lines)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| number | Int32 | Номер страницы. |
| visible | Boolean | Индикатор видимости страницы. |
| width | Int32 | Ширина страницы в пикселях при просмотре в формате JPG или PNG. |
| height | Int32 | Высота страницы в пикселях при просмотре в формате JPG или PNG. |
| lines | List`1 | Строки, содержащиеся на странице при просмотре в формате JPG или PNG с включенным извлечением текста. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Брошен, когда*number* меньше или равно нулю. |
| ArgumentException | Брошен, когда*width* меньше или равно нулю. |
| ArgumentException | Брошен, когда*height* меньше или равно нулю. |
| ArgumentNullException | Брошен, когда*lines* нулевой. |

### Смотрите также

* class [Line](../../line)
* class [Page](../../page)
* пространство имен [GroupDocs.Viewer.Results](../../page)
* сборка [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, List&lt;Line&gt;) {#constructor_6}

Инициализирует новый экземпляр[`Page`](../../page) класс.

```csharp
public Page(int number, string name, bool visible, int width, int height, List<Line> lines)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| number | Int32 | Номер страницы. |
| name | String | Имя рабочего листа или страницы. |
| visible | Boolean | Индикатор видимости страницы. |
| width | Int32 | Ширина страницы в пикселях при просмотре в формате JPG или PNG. |
| height | Int32 | Высота страницы в пикселях при просмотре в формате JPG или PNG. |
| lines | List`1 | Строки, содержащиеся на странице при просмотре в формате JPG или PNG с включенным извлечением текста. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Брошен, когда*number* меньше или равно нулю. |
| ArgumentException | Брошен, когда*width* меньше или равно нулю. |
| ArgumentException | Брошен, когда*height* меньше или равно нулю. |
| ArgumentNullException | Брошен, когда*lines* нулевой. |

### Смотрите также

* class [Line](../../line)
* class [Page](../../page)
* пространство имен [GroupDocs.Viewer.Results](../../page)
* сборка [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
