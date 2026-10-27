---
title: "فئة Rgb24Color"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يمثل لون RGB 24-بتًا مع 8 بتات لكل قناة (Red، Green، Blue) دون شفافية."
type: docs
url: /ar/python-net/groupdocs.viewer.drawing/rgb24color/
is_root: false
weight: 80
---


## Rgb24Color class

يمثل لون RGB 24-بتًا مع 8 بتات لكل قناة (Red، Green، Blue) دون شفافية.

تم تصميم هذا النوع ليكون مفيدًا لـ (ولكن ليس محصورًا في) عمليات CSS. راجع المزيد: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

يعرض نوع Rgb24Color الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/__init__/) |  |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | يحدد ما إذا كان هذا اللون يساوي الـ [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/). |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | يفحص هذا اللون مع اللون المحدد [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) للتحقق من المساواة. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#obj) | يفحص هذا اللون مقابل اللون غير المحول المحدد. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/from_rgb/#red-green-blue) | ينشئ قيمة [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) من قيم القنوات الحمراء والخضراء والزرقاء المحددة. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_brightness/) | يرجع إضاءة/سطوع Hue‑Saturation‑Lightness (HSL) لهذا الكائن [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/). |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hash_code/) | يرجع رمز تجزئة يحدد اللون الحالي. غير متوافق مع `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hue/) | يرجع مكوّن الصبغة (Hue) للون في مساحة ألوان HSL، معبرًا عنه بالدرجات. إذا كان اللون رماديًا (R == G == B)، تكون الصبغة غير معرفة وتعيد الطريقة 0. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_saturation/) | تشبع Hue‑Saturation‑Lightness (HSL) لهذا الكائن [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/). |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_argb/) | يرجع قيمة ARGB لهذا الكائن [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)، متوافقًا مع `System.Drawing.Color`. |
| [to_hex](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/) | يرجع هذا اللون في تمثيل سلسلة سداسي عشرية. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_rgb/) | يسلسل هذا الكائن [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) إلى تدوين دالة CSS 'rgb'. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_string/) | يسلسل هذا الكائن [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) إلى تنسيق 'rgb(r, g, b)'. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [b](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/b/) | مكوّن اللون الأزرق كعدد صحيح غير موقع 8‑بت [0..255]. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/g/) | مكوّن أخضر للون كعدد صحيح غير موقع 8‑بت في النطاق 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/is_default/) | تشير الخاصية إلى ما إذا كان هذا الكائن [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) هو الافتراضي (أسود) – جميع القنوات الثلاثة مضبوطة على 0. |
| [r](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/r/) | مكوّن أحمر للون كعدد صحيح غير موقع 8‑بت (0..255). |

### انظر أيضًا
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
