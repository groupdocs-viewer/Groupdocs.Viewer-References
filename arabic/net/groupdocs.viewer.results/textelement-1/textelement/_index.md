---
title: "TextElement"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يُنشئ مثيلًا جديدًا من الفئة TextElementgroupdocs.viewer.results/textelement1."
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.results/textelement-1/textelement/
---

## TextElement() {#constructor}

يُنشئ مثيلًا جديدًا من الفئة [`TextElement`](../../textelement-1).

```csharp
public TextElement()
```

### انظر أيضًا

* class [TextElement&lt;T&gt;](../../textelement-1)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## TextElement(T, double, double, double, double) {#constructor_1}

يُنشئ مثيلًا جديدًا من الفئة [`TextElement`](../../textelement-1).

```csharp
public TextElement(T value, double x, double y, double width, double height)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| value | T | قيمة عنصر النص. |
| x | Double | الإحداثي X لأعلى نقطة يسرى في تخطيط الصفحة حيث يبدأ المستطيل الذي يحتوي العنصر. |
| y | Double | الإحداثي Y لأعلى نقطة يسرى في تخطيط الصفحة حيث يبدأ المستطيل الذي يحتوي العنصر. |
| العرض | Double | عرض المستطيل الذي يحتوي على العنصر (بالبكسل). |
| الارتفاع | Double | ارتفاع المستطيل الذي يحتوي على العنصر (بالبكسل). |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما يكون *value* فارغًا. |
| ArgumentException | يُرمى عندما يكون *العرض* أقل من أو يساوي الصفر. |
| ArgumentException | يُرمى عندما يكون *الارتفاع* أقل من أو يساوي الصفر. |

### انظر أيضًا

* class [TextElement&lt;T&gt;](../../textelement-1)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
