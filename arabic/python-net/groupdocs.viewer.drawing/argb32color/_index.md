---
title: "فئة Argb32Color"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يمثل لونًا 32‑بتًا بتنسيق ARGB، مع 8 بتات لكل قناة (Alpha، Red، Green، Blue)."
type: docs
url: /ar/python-net/groupdocs.viewer.drawing/argb32color/
is_root: false
weight: 10
---


## Argb32Color class

يمثل لونًا 32-بتًا بتنسيق ARGB، مع 8 بتات لكل قناة (Alpha، Red، Green، Blue). يدعم الشفافية.

تم تصميم هذا النوع ليكون مفيدًا لـ (ولكن ليس محصورًا في) عمليات CSS. راجع المزيد: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

يعرض نوع Argb32Color الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/argb32color/__init__/) |  |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | يتحقق مما إذا كان هذا اللون مساويًا للـ [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) المحدد. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | يحدد ما إذا كان هذا اللون مساويًا للـ [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) المحدد. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#obj) | يتحقق مما إذا كان هذا اللون يساوي اللون غير المحول المحدد. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_rgb_24_color/) |  |
| [from_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_argb/#argb) | ينشئ كائن Argb32Color من قيمة ARGB 32‑بت، متوافقًا مع القيم التي ينتجها `System.Drawing.Color.ToArgb()`. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | ينشئ كائنًا جديدًا من [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) من الكائن المحدد، ولكن مع قيمة ألفا (شفافية) معاد تعريفها. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | ينشئ كائن Argb32Color جديدًا من Rgb24Color المحدد، ولكن مع قيمة ألفا (شفافية) محددة. |
| [from_other_with_alpha_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_argb_32_color/) |  |
| [from_other_with_alpha_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/#red-green-blue) | ينشئ قيمة Argb32Color من القنوات الحمراء والخضراء والزرقاء المحددة، مع ضبط قناة الألفا لتكون غير شفافة بالكامل. |
| [from_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgba/#red-green-blue-alpha) | ينشئ قيمة من [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) من القيم المحددة للقنوات الحمراء والخضراء والزرقاء والألفا. |
| [from_single_value_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_single_value_rgb/#value) | ينشئ لونًا غير شفاف بالكامل (A=255) من قيمة بايت واحدة تُطبق على جميع القنوات. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_brightness/) | يعيد إضاءة/سطوع Hue‑Saturation‑Lightness (HSL) لهذا الكائن [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/). |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hash_code/) | يعيد رمز تجزئة يحدد اللون الحالي؛ غير متوافق مع `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hue/) | يعيد قيمة درجة اللون Hue‑Saturation‑Lightness (HSL) بالدرجات لهذا الكائن [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/); إذا كان R == G == B، تكون قيمة اللون غير ذات معنى وتعيد الطريقة 0. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_saturation/) | يعيد تشبع Hue‑Saturation‑Lightness (HSL) لهذا الكائن [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/). |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_argb/) | يعيد قيمة ARGB لهذا الكائن [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)، متوافقًا مع طريقة `System.Drawing.Color.ToArgb()`. |
| [to_hex_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgb/) | يسلسل هذا الكائن [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) إلى الصيغة الست عشرية `##RRGGBB` كسلسلة بدون قناة ألفا. |
| [to_hex_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgba/) | يسلسل هذا الكائن [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) إلى الصيغة الست عشرية `##RRGGBBAA` كسلسلة مع قناة ألفا. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgb/) | يسلسل هذا الكائن [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) إلى صيغة دالة CSS `rgb`، متجاهلاً قناة ألفا. |
| [to_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgba/) | يسلسل هذا الكائن [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) إلى صيغة دالة CSS 'rgba'. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_string/) | يسلسل كائن Argb32Color إلى أنسب صيغة دالة CSS حسب الشفافية. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [a](/viewer/python-net/groupdocs.viewer.drawing/argb32color/a/) | مكوّن ألفا للون كعدد صحيح غير موقع 8‑بت في النطاق 0..255. |
| [alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/alpha/) | مكوّن ألفا للون كقيمة عائمة في النطاق 0..1. |
| [b](/viewer/python-net/groupdocs.viewer.drawing/argb32color/b/) | مكوّن أزرق للون كعدد صحيح غير موقع 8‑بت في النطاق 0..255. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/argb32color/g/) | مكوّن أخضر للون كعدد صحيح غير موقع 8‑بت في النطاق 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) | تشير الخاصية إلى ما إذا كان هذا الكائن [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) هو الافتراضي (شفاف)، بمعنى أن جميع القنوات الأربعة مضبوطة على 0؛ وهو ما يعادل [`Argb32Color.is_empty`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/). |
| [is_empty](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/) | تشير الخاصية إلى ما إذا كان هذا الكائن [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) غير مهيأ (جميع القنوات الأربعة مضبوطة على 0). وهو ما يعادل اللون الافتراضي أو الشفاف ويتطابق مع [`Argb32Color.is_default`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/). |
| [is_fully_opaque](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_opaque/) | تشير الخاصية إلى ما إذا كان هذا الكائن [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) غير شفاف تمامًا، بدون شفافية (قناة ألفا لديها القيمة القصوى). |
| [is_fully_transparent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_transparent/) | تشير الخاصية إلى ما إذا كان هذا الكائن [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) شفافًا تمامًا—قناة ألفا لديها القيمة الدنيا (0)، وبالتالي لا تؤثر قنوات R و G و B بشكل مرئي. |
| [is_translucent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_translucent/) | تشير الخاصية إلى ما إذا كان هذا الكائن [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) شبه شفاف (ليس شفافًا تمامًا، ولا غير شفاف تمامًا). |
| [r](/viewer/python-net/groupdocs.viewer.drawing/argb32color/r/) | مكوّن أحمر للون كعدد صحيح غير موقع 8‑بت (0..255). |
| [value](/viewer/python-net/groupdocs.viewer.drawing/argb32color/value/) | تمثيل اللون كعدد صحيح موقع 32‑بت. |

### الحقول
| حقل | الوصف |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.drawing/argb32color/empty/) | يرجع لونًا فارغًا، لا يحتوي على معلومات القنوات وهو شفاف تمامًا. نفس '' . القيمة الافتراضية. |
| [TRANSPARENT](/viewer/python-net/groupdocs.viewer.drawing/argb32color/transparent/) | لون فارغ شفاف تمامًا. وهو نفس قيمة اللون الافتراضي ''. |

### مثال

```python
from groupdocs.viewer.drawing import Argb32Color

# إنشاء لون أصفر غير شفاف تمامًا (RGB 255, 255, 0)
yellow = Argb32Color.from_rgb(255, 255, 0)
```

### انظر أيضًا
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
