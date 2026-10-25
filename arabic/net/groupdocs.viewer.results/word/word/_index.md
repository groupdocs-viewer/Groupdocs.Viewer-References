---
title: "كلمة"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "ينشئ مثيلاً جديداً من الفئة Wordgroupdocs.viewer.results/word."
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.results/word/word/
---

## Word() {#constructor}

ينشئ مثيلاً جديداً من الفئة [`Word`](../../word).

```csharp
public Word()
```

### انظر أيضًا

* class [Word](../../word)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Word(string, double, double, double, double, List&lt;Character&gt;) {#constructor_1}

ينشئ مثيلاً جديداً من الفئة [`Word`](../../word).

```csharp
public Word(string word, double x, double y, double width, double height, 
    List<Character> characters)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| كلمة | String | الكلمة. |
| x | Double | الإحداثي X لأعلى نقطة يسرى في تخطيط الصفحة حيث يبدأ المستطيل الذي يحتوي على الكلمة. |
| y | Double | الإحداثي Y لأعلى نقطة يسرى في تخطيط الصفحة حيث يبدأ المستطيل الذي يحتوي على الكلمة. |
| العرض | Double | عرض المستطيل الذي يحتوي على الكلمة. |
| الارتفاع | Double | ارتفاع المستطيل الذي يحتوي على الكلمة. |
| الأحرف | List`1 | الأحرف التي يحتويها الكلمة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما تكون *word* فارغة أو لا قيمة لها. |
| ArgumentNullException | يُرمى عندما تكون *characters* لا قيمة لها. |

### انظر أيضًا

* class [Character](../../character)
* class [Word](../../word)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
