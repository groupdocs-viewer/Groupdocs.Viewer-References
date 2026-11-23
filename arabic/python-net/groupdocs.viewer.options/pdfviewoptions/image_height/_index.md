---
title: "خاصية image_height"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "ارتفاع صورة الإخراج بالبكسل."
type: docs
url: /ar/python-net/groupdocs.viewer.options/pdfviewoptions/image_height/
is_root: false
weight: 2010
---


## image_height property

ارتفاع صورة الإخراج بالبكسل.

استخدم هذه الخاصية لتعيين ارتفاع الصورة الناتجة (بالبكسل). يقوم GroupDocs.Viewer بتطبيق هذه الخاصية عند تحويل صورة واحدة إلى HTML فقط. للحصول على تفاصيل، راجع الوثائق على https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/.

إذا قمت بتعيين هذه الخاصية، يتم تجاهل خاصية [`PdfViewOptions.ImageMaxHeight`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_height/).

### Definition:
```python
@property
def image_height(self):
    ...
@image_height.setter
def image_height(self, value):
    ...
```

### انظر أيضًا
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
