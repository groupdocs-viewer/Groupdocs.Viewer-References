---
title: "فئة Layer"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يمثل طبقة موجودة في رسم CAD."
type: docs
url: /ar/python-net/groupdocs.viewer.results/layer/
is_root: false
weight: 60
---


## Layer class

يمثل طبقة موجودة في رسم CAD.

يعرض نوع Layer الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/) | ينشئ مثيلاً جديدًا من الفئة [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name) | ينشئ مثيلاً جديدًا من Layer. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name-visible) | ينشئ مثيلاً جديدًا من Layer. |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#other) | يحدد ما إذا كان Layer الحالي هو نفسه كائن Layer المحدد. |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#obj) | يتحقق مما إذا كان [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) الحالي مساويًا للكائن المحدد. |
| [equals_layer](/viewer/python-net/groupdocs.viewer.results/layer/equals_layer/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.results/layer/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.results/layer/get_hash_code/) | يعيد رمز التجزئة لكائن Layer الحالي. |
| [to_string](/viewer/python-net/groupdocs.viewer.results/layer/to_string/) | يعيد سلسلة تمثل الكائن الحالي. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [name](/viewer/python-net/groupdocs.viewer.results/layer/name/) | اسم الطبقة. |
| [visible](/viewer/python-net/groupdocs.viewer.results/layer/visible/) | مؤشر رؤية الطبقة. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("output.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### انظر أيضًا
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
