---
title: "فئة Attachment"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يمثل ملف مرفق يحتويه رسالة بريد إلكتروني أو أرشيف أو مستند PDF أو ملف بيانات Outlook."
type: docs
url: /ar/python-net/groupdocs.viewer.results/attachment/
is_root: false
weight: 20
---


## Attachment class

يمثل ملف مرفق يحتويه رسالة بريد إلكتروني أو أرشيف أو مستند PDF أو ملف بيانات Outlook.

يعرض نوع Attachment الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/) | يُنشئ مثلاً جديدًا من [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#file_name-file_path) | يُنشئ مثالًا جديدًا من Attachment. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-size) | يُنشئ مثلاً جديدًا من فئة Attachment. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-file_type-size) | يُنشئ مثلاً جديدًا من فئة Attachment. |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/attachment/to_string/) | يعيد سلسلة تمثل الكائن الحالي. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.results/attachment/file_name/) | اسم ملف المرفق. |
| [file_path](/viewer/python-net/groupdocs.viewer.results/attachment/file_path/) | المسار النسبي للمرفق، على سبيل المثال `folder/file.docx`، أو اسم الملف عندما يكون الملف موجودًا في جذر الأرشيف، أو في رسالة بريد إلكتروني، أو ملف بيانات. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/attachment/file_type/) | نوع ملف المرفق. |
| [id](/viewer/python-net/groupdocs.viewer.results/attachment/id/) | المعرّف الفريد للمرفق في سياق ملف واحد يحتوي على هذا المرفق. |
| [size](/viewer/python-net/groupdocs.viewer.results/attachment/size/) | حجم ملف المرفق بالبايت. |

### مثال

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # الوصول إلى خصائص المرفق، على سبيل المثال، اسم الملف
        print(attachment.file_name)
        # حفظ المرفق إلى مسار ملف
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### انظر أيضًا
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
