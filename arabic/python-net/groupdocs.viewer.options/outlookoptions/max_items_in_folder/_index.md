---
title: "خاصية max_items_in_folder"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "الحد الأقصى لعدد الرسائل أو العناصر التي يمكن عرضها من مجلد واحد."
type: docs
url: /ar/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/
is_root: false
weight: 2030
---


## max_items_in_folder property

الحد الأقصى لعدد الرسائل أو العناصر التي يمكن عرضها من مجلد واحد.

يمكن أن تكون ملفات بيانات Outlook كبيرة وقد يستغرق استرجاع جميع الرسائل وقتًا كبيرًا. تحد هذه الخاصية الحد الأقصى لعدد الرسائل أو العناصر التي يتم عرضها. القيمة الافتراضية هي `50`. لعرض جميع الرسائل، اضبط القيمة إلى `0`.

للحصول على مثال شفرة، راجع الوثائق.

### Definition:
```python
@property
def max_items_in_folder(self):
    ...
@max_items_in_folder.setter
def max_items_in_folder(self, value):
    ...
```

### انظر أيضًا
* class [`OutlookOptions`](/viewer/python-net/groupdocs.viewer.options/outlookoptions/)
