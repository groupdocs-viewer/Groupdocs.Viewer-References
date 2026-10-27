---
title: "خاصية tiles"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "مناطق الرسم التي سيتم عرضها."
type: docs
url: /ar/python-net/groupdocs.viewer.options/cadoptions/tiles/
is_root: false
weight: 2090
---


## tiles property

مناطق الرسم التي سيتم عرضها.

هذا الخيار متاح فقط لأنواع الملفات [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/) و[`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/). يتم تجاهل خيارات [`CadOptions.render_layouts`](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) و[`CadOptions.layout_name`](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) عند العرض باستخدام البلاط.

### Definition:
```python
@property
def tiles(self):
    ...
@tiles.setter
def tiles(self, value):
    ...
```

### انظر أيضًا
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
