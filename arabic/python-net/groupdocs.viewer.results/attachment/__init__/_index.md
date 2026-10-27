---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يُنشئ مثالًا جديدًا من Attachment."
type: docs
url: /ar/python-net/groupdocs.viewer.results/attachment/__init__/
is_root: false
weight: 10
---


## __init__

يُنشئ مثلاً جديدًا من [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/).

```python
def __init__(self):
    ...
```

## __init__ {#file_name-file_path}

يُنشئ مثالًا جديدًا من Attachment.

```python
def __init__(self, file_name, file_path):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_name | `str` | اسم ملف المرفق. |
| file_path | `str` | المسار النسبي للمرفق مثل \"folder/file.docx\" أو اسم الملف عندما يكون الملف موجودًا في جذر الأرشيف، في رسالة بريد إلكتروني أو ملف بيانات. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `file_path` None أو فارغ. |

## __init__ {#id-file_name-file_path-size}

يُنشئ مثلاً جديدًا من فئة Attachment.

```python
def __init__(self, id, file_name, file_path, size):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| id | `str` | معرف فريد (في سياق ملف واحد) للمرفق. |
| file_name | `str` | اسم ملف المرفق. |
| file_path | `str` | المسار النسبي للمرفق مثل `folder/file.docx` أو اسم الملف عندما يكون الملف موجودًا في جذر الأرشيف، في رسالة بريد إلكتروني أو ملف بيانات. |
| size | `int` | حجم ملف المرفق بالبايت. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `file_path` يساوي null أو فارغًا. |

## __init__ {#id-file_name-file_path-file_type-size}

يُنشئ مثلاً جديدًا من فئة Attachment.

```python
def __init__(self, id, file_name, file_path, file_type, size):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| id | `str` | معرف فريد (في سياق ملف واحد) للمرفق. |
| file_name | `str` | اسم ملف المرفق. |
| file_path | `str` | المسار النسبي للمرفق مثل `folder/file.docx` أو اسم الملف عندما يكون الملف موجودًا في جذر الأرشيف، في رسالة بريد إلكتروني أو ملف بيانات. |
| file_type | `FileType` | نوع ملف المرفق. |
| size | `int` | حجم ملف المرفق بالبايت. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما يكون `file_type` يساوي null. |

### انظر أيضًا
* class [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/)
