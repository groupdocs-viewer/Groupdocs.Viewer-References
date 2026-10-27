---
title: "طريقة view"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "ينشئ عرضًا لجميع صفحات المستند."
type: docs
url: /ar/python-net/groupdocs.viewer/viewer/view/
is_root: false
weight: 1130
---


## view {#options}

ينشئ عرضًا لجميع صفحات المستند.

المزيد من المعلومات

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | `ViewOptions` | خيارات العرض. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما تكون `options` None. |
| `PasswordRequiredException` | عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| `IncorrectPasswordException` | عندما تكون كلمة المرور المحددة غير صحيحة. |
| `GroupDocsViewerException` | عندما لا يمكن العثور على مرفق. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-page_numbers}

ينشئ عرضًا لصفحات محددة من المستند.

المزيد من المعلومات

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, page_numbers):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | `ViewOptions` | خيارات العرض. |
| page_numbers | `list[int]` | أرقام الصفحات للعرض. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما تكون `page_numbers` فارغة. |
| `PasswordRequiredException` | عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| `IncorrectPasswordException` | عند كون كلمة المرور المحددة غير صحيحة. |
| `GroupDocsViewerException` | عند عدم العثور على المرفق. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-cancellation_token-page_numbers}

ينشئ عرضًا لصفحات محددة من المستند.

المزيد من المعلومات:

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, cancellation_token, page_numbers):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | `ViewOptions` | خيارات العرض. |
| cancellation_token | `CancellationToken` | رمز الإلغاء لإلغاء المعالجة. |
| page_numbers | `list[int]` | أرقام الصفحات للعرض. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عند `page_numbers` فارغًا. |
| `PasswordRequiredException` | عند الحاجة إلى كلمة مرور لفتح المستند. |
| `IncorrectPasswordException` | عندما تكون كلمة المرور المحددة غير صحيحة. |
| `GroupDocsViewerException` | عند عدم العثور على المرفق. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### انظر أيضًا
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
