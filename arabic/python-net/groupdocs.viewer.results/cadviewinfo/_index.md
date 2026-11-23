---
title: "فئة CadViewInfo"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يمثل معلومات العرض لرسم CAD."
type: docs
url: /ar/python-net/groupdocs.viewer.results/cadviewinfo/
is_root: false
weight: 30
---


## CadViewInfo class

يمثل معلومات العرض لرسم CAD.

يعرض نوع CadViewInfo الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/__init__/#file_type-pages-layers-layouts) | يُهيئ نسخة جديدة من CadViewInfo. |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | يرجع سلسلة تمثل الكائن الحالي. (موروث من [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [layers](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layers/) | قائمة الطبقات الموجودة في رسم CAD. |
| [layouts](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layouts/) | قائمة التخطيطات الموجودة في رسم CAD. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | نوع الملف. (موروث من [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | قائمة الصفحات للعرض. (موروث من [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### مثال

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import CadViewInfo

def get_cad_info():
    with Viewer("sample.dwg") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        cad_info = cast(CadViewInfo, info)

        print("File type:", cad_info.file_type)
        print("Pages count:", len(cad_info.pages))
        print("Layers:")
        for layer in cad_info.layers:
            print(f"  {layer.name} (visible={layer.visible})")
        print("Layouts:")
        for layout in cad_info.layouts:
            print(f"  {layout.name} ({layout.width}x{layout.height})")

if __name__ == "__main__":
    get_cad_info()
```

### Guides
دلائل المهام التي تستخدم `CadViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### انظر أيضًا
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
