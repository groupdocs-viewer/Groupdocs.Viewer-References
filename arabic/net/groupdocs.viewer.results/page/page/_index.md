---
title: Page
second_title: GroupDocs.Viewer لمرجع .NET API
description: تهيئة مثيل جديد لـPagegroupdocs.viewer.results/page فئة .
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.results/page/page/
---
## Page(int, bool) {#constructor}

تهيئة مثيل جديد لـ[`Page`](../../page) فئة .

```csharp
public Page(int number, bool visible)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| number | Int32 | رقم الصفحة. |
| visible | Boolean | مؤشر رؤية الصفحة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | عندما ألقيت*number* أصغر أو يساوي الصفر. |

### أنظر أيضا

* class [Page](../../page)
* مساحة الاسم [GroupDocs.Viewer.Results](../../page)
* المجسم [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_3}

تهيئة مثيل جديد لـ[`Page`](../../page) فئة .

```csharp
public Page(int number, string name, bool visible)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| number | Int32 | رقم الصفحة. |
| name | String | ورقة العمل أو اسم الصفحة. |
| visible | Boolean | مؤشر رؤية الصفحة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | عندما ألقيت*number* أصغر أو يساوي الصفر. |

### أنظر أيضا

* class [Page](../../page)
* مساحة الاسم [GroupDocs.Viewer.Results](../../page)
* المجسم [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_1}

تهيئة مثيل جديد لـ[`Page`](../../page) فئة .

```csharp
public Page(int number, bool visible, int width, int height)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| number | Int32 | رقم الصفحة. |
| visible | Boolean | مؤشر رؤية الصفحة. |
| width | Int32 | عرض الصفحة بالبكسل عند عرضها بتنسيق JPG أو PNG. |
| height | Int32 | ارتفاع الصفحة بالبكسل عند عرضها بتنسيق JPG أو PNG. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | عندما ألقيت*number* أصغر أو يساوي الصفر. |
| ArgumentException | عندما ألقيت*width* أصغر أو يساوي الصفر. |
| ArgumentException | عندما ألقيت*height* أصغر أو يساوي الصفر. |

### أنظر أيضا

* class [Page](../../page)
* مساحة الاسم [GroupDocs.Viewer.Results](../../page)
* المجسم [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_4}

تهيئة مثيل جديد لـ[`Page`](../../page) فئة .

```csharp
public Page(int number, string name, bool visible, int width, int height)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| number | Int32 | رقم الصفحة. |
| name | String | ورقة العمل أو اسم الصفحة. |
| visible | Boolean | مؤشر رؤية الصفحة. |
| width | Int32 | عرض الصفحة بالبكسل عند عرضها بتنسيق JPG أو PNG. |
| height | Int32 | ارتفاع الصفحة بالبكسل عند عرضها بتنسيق JPG أو PNG. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | عندما ألقيت*number* أصغر أو يساوي الصفر. |
| ArgumentException | عندما ألقيت*width* أصغر أو يساوي الصفر. |
| ArgumentException | عندما ألقيت*height* أصغر أو يساوي الصفر. |

### أنظر أيضا

* class [Page](../../page)
* مساحة الاسم [GroupDocs.Viewer.Results](../../page)
* المجسم [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, IList&lt;Line&gt;) {#constructor_2}

تهيئة مثيل جديد لـ[`Page`](../../page) فئة .

```csharp
public Page(int number, bool visible, int width, int height, IList<Line> lines)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| number | Int32 | رقم الصفحة. |
| visible | Boolean | مؤشر رؤية الصفحة. |
| width | Int32 | عرض الصفحة بالبكسل عند عرضها بتنسيق JPG أو PNG. |
| height | Int32 | ارتفاع الصفحة بالبكسل عند عرضها بتنسيق JPG أو PNG. |
| lines | IList`1 | الأسطر التي تحتويها الصفحة عند عرضها بتنسيق JPG أو PNG مع تمكين استخراج النص. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | عندما ألقيت*number* أصغر أو يساوي الصفر. |
| ArgumentException | عندما ألقيت*width* أصغر أو يساوي الصفر. |
| ArgumentException | عندما ألقيت*height* أصغر أو يساوي الصفر. |
| ArgumentNullException | عندما ألقيت*lines* باطل. |

### أنظر أيضا

* class [Line](../../line)
* class [Page](../../page)
* مساحة الاسم [GroupDocs.Viewer.Results](../../page)
* المجسم [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, IList&lt;Line&gt;) {#constructor_5}

تهيئة مثيل جديد لـ[`Page`](../../page) فئة .

```csharp
public Page(int number, string name, bool visible, int width, int height, IList<Line> lines)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| number | Int32 | رقم الصفحة. |
| name | String | ورقة العمل أو اسم الصفحة. |
| visible | Boolean | مؤشر رؤية الصفحة. |
| width | Int32 | عرض الصفحة بالبكسل عند عرضها بتنسيق JPG أو PNG. |
| height | Int32 | ارتفاع الصفحة بالبكسل عند عرضها بتنسيق JPG أو PNG. |
| lines | IList`1 | الأسطر التي تحتويها الصفحة عند عرضها بتنسيق JPG أو PNG مع تمكين استخراج النص. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | عندما ألقيت*number* أصغر أو يساوي الصفر. |
| ArgumentException | عندما ألقيت*width* أصغر أو يساوي الصفر. |
| ArgumentException | عندما ألقيت*height* أصغر أو يساوي الصفر. |
| ArgumentNullException | عندما ألقيت*lines* باطل. |

### أنظر أيضا

* class [Line](../../line)
* class [Page](../../page)
* مساحة الاسم [GroupDocs.Viewer.Results](../../page)
* المجسم [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
