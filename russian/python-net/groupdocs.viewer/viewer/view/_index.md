---
title: "метод view"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Создаёт представление всех страниц документа."
type: docs
url: /ru/python-net/groupdocs.viewer/viewer/view/
is_root: false
weight: 1130
---


## view {#options}

Создаёт представление всех страниц документа.

Подробнее

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | `ViewOptions` | Параметры просмотра. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `options` равно None. |
| `PasswordRequiredException` | Когда для открытия документа требуется пароль. |
| `IncorrectPasswordException` | Когда указанный пароль неверен. |
| `GroupDocsViewerException` | Когда вложение не найдено. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-page_numbers}

Создаёт представление определённых страниц документа.

Подробнее

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, page_numbers):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | `ViewOptions` | Параметры просмотра. |
| page_numbers | `list[int]` | Номера страниц для просмотра. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | когда `page_numbers` пусто. |
| `PasswordRequiredException` | когда требуется пароль для открытия документа. |
| `IncorrectPasswordException` | когда указанный пароль неверен. |
| `GroupDocsViewerException` | когда вложение не найдено. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-cancellation_token-page_numbers}

Создаёт представление определённых страниц документа.

Подробнее:

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, cancellation_token, page_numbers):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | `ViewOptions` | Параметры просмотра. |
| cancellation_token | `CancellationToken` | Токен отмены для прерывания обработки. |
| page_numbers | `list[int]` | Номера страниц для просмотра. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `page_numbers` пустой. |
| `PasswordRequiredException` | Когда требуется пароль для открытия документа. |
| `IncorrectPasswordException` | Когда указанный пароль неверен. |
| `GroupDocsViewerException` | Когда вложение не найдено. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### См. также
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
