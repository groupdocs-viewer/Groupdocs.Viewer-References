---
title: "Page"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يُنشئ مثيلًا جديدًا من الفئة Pagegroupdocs.viewer.results/page."
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.results/page/page/
---

## Page() {#constructor}

يُنشئ مثيلًا جديدًا من الفئة [`Page`](../../page).

```csharp
public Page()
```

### انظر أيضًا

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool) {#constructor_1}

يُنشئ مثيلًا جديدًا من الفئة [`Page`](../../page).

```csharp
public Page(int number, bool visible)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| عدد | Int32 | رقم الصفحة. |
| مرئي | Boolean | مؤشر ظهور الصفحة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما يكون *number* أقل أو يساوي الصفر. |

### انظر أيضًا

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_4}

يُنشئ مثيلًا جديدًا من الفئة [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| عدد | Int32 | رقم الصفحة. |
| اسم | String | اسم ورقة العمل أو الصفحة. |
| مرئي | Boolean | مؤشر ظهور الصفحة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما يكون *number* أقل أو يساوي الصفر. |

### انظر أيضًا

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_2}

يُنشئ مثيلًا جديدًا من الفئة [`Page`](../../page).

```csharp
public Page(int number, bool visible, int width, int height)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| عدد | Int32 | رقم الصفحة. |
| مرئي | Boolean | مؤشر ظهور الصفحة. |
| العرض | Int32 | عرض الصفحة بالبكسل عند عرضها كملف JPG أو PNG. |
| الارتفاع | Int32 | ارتفاع الصفحة بالبكسل عند عرضها كملف JPG أو PNG. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما يكون *number* أقل أو يساوي الصفر. |
| ArgumentException | يُرمى عندما يكون *العرض* أقل من أو يساوي الصفر. |
| ArgumentException | يُرمى عندما يكون *الارتفاع* أقل من أو يساوي الصفر. |

### انظر أيضًا

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_5}

يُنشئ مثيلًا جديدًا من الفئة [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible, int width, int height)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| عدد | Int32 | رقم الصفحة. |
| اسم | String | اسم ورقة العمل أو الصفحة. |
| مرئي | Boolean | مؤشر ظهور الصفحة. |
| العرض | Int32 | عرض الصفحة بالبكسل عند عرضها كملف JPG أو PNG. |
| الارتفاع | Int32 | ارتفاع الصفحة بالبكسل عند عرضها كملف JPG أو PNG. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما يكون *number* أقل أو يساوي الصفر. |
| ArgumentException | يُرمى عندما يكون *العرض* أقل من أو يساوي الصفر. |
| ArgumentException | يُرمى عندما يكون *الارتفاع* أقل من أو يساوي الصفر. |

### انظر أيضًا

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, List&lt;Line&gt;) {#constructor_3}

يُنشئ مثيلًا جديدًا من الفئة [`Page`](../../page).

```csharp
public Page(int number, bool visible, int width, int height, List<Line> lines)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| عدد | Int32 | رقم الصفحة. |
| مرئي | Boolean | مؤشر ظهور الصفحة. |
| العرض | Int32 | عرض الصفحة بالبكسل عند عرضها كملف JPG أو PNG. |
| الارتفاع | Int32 | ارتفاع الصفحة بالبكسل عند عرضها كملف JPG أو PNG. |
| سطور | List`1 | السطور الموجودة في الصفحة عند عرضها كملف JPG أو PNG مع تمكين استخراج النص. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما يكون *number* أقل أو يساوي الصفر. |
| ArgumentException | يُرمى عندما يكون *العرض* أقل من أو يساوي الصفر. |
| ArgumentException | يُرمى عندما يكون *الارتفاع* أقل من أو يساوي الصفر. |
| ArgumentNullException | يُرمى عندما تكون *lines* null. |

### انظر أيضًا

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, List&lt;Line&gt;) {#constructor_6}

يُنشئ مثيلًا جديدًا من الفئة [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible, int width, int height, List<Line> lines)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| عدد | Int32 | رقم الصفحة. |
| اسم | String | اسم ورقة العمل أو الصفحة. |
| مرئي | Boolean | مؤشر ظهور الصفحة. |
| العرض | Int32 | عرض الصفحة بالبكسل عند عرضها كملف JPG أو PNG. |
| الارتفاع | Int32 | ارتفاع الصفحة بالبكسل عند عرضها كملف JPG أو PNG. |
| سطور | List`1 | السطور الموجودة في الصفحة عند عرضها كملف JPG أو PNG مع تمكين استخراج النص. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما يكون *number* أقل أو يساوي الصفر. |
| ArgumentException | يُرمى عندما يكون *العرض* أقل من أو يساوي الصفر. |
| ArgumentException | يُرمى عندما يكون *الارتفاع* أقل من أو يساوي الصفر. |
| ArgumentNullException | يُرمى عندما تكون *lines* null. |

### انظر أيضًا

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
