---
title: "سطر"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "ينشئ مثيلاً جديداً من الفئة Linegroupdocs.viewer.results/line."
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.results/line/line/
---

## Line() {#constructor}

ينشئ مثيلاً جديداً من الفئة [`Line`](../../line).

```csharp
public Line()
```

### انظر أيضًا

* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Line(string, double, double, double, double, List&lt;Word&gt;) {#constructor_1}

ينشئ مثيلاً جديداً من الفئة [`Line`](../../line).

```csharp
public Line(string line, double x, double y, double width, double height, List<Word> words)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| سطر | String | السطر. |
| x | Double | إحداثي X لأعلى نقطة يسرى في تخطيط الصفحة حيث يبدأ المستطيل الذي يحتوي على السطر. |
| y | Double | إحداثي Y لأعلى نقطة يسرى في تخطيط الصفحة حيث يبدأ المستطيل الذي يحتوي على السطر. |
| العرض | Double | عرض المستطيل الذي يحتوي على السطر (بالبكسل). |
| الارتفاع | Double | ارتفاع المستطيل الذي يحتوي على السطر (بالبكسل). |
| كلمات | List`1 | الكلمات التي يحتويها السطر. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يتم إلقاء الاستثناء عندما يكون *line* null أو فارغ. |
| ArgumentNullException | يتم إلقاء الاستثناء عندما يكون *words* null. |

### انظر أيضًا

* class [Word](../../word)
* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
