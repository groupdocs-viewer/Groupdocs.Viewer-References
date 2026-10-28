---
title: "Метод for_external_resources"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует экземпляр класса HtmlViewOptions для рендеринга в HTML с внешними ресурсами."
type: docs
url: /ru/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/
is_root: false
weight: 1060
---


## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url}

Инициализирует экземпляр класса [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) для рендеринга в HTML с внешними ресурсами.

Для примера кода см. документацию.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Метод, который создает поток, используемый для записи данных выходной страницы. |
| create_resource_stream | `CreateResourceStream` | Метод, который освобождает поток, созданный методом `create_page_stream`. |
| create_resource_url | `CreateResourceUrl` | Метод, который создает URL для HTML‑ресурса. |

**Returns:** New instance of the `HtmlViewOptions` class for rendering into HTML with external resources.

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `create_resource_url` имеет значение None. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("sample.docx") as viewer:
    options = HtmlViewOptions.for_external_resources(
        "page_{0}.html",
        "page_{0}/resource_{0}_{1}",
        "page_{0}/resource_{0}_{1}"
    )
    viewer.view(options)
```

## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url-release_page_stream-release_resource_stream}

Инициализирует экземпляр класса HtmlViewOptions для рендеринга в HTML с внешними ресурсами.

Для дополнительных примеров использования см. документацию GroupDocs Viewer.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url, release_page_stream, release_resource_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Метод, который создает поток, используемый для записи данных выходных страниц. |
| create_resource_stream | `CreateResourceStream` | Метод, который создает поток, используемый для записи данных выходного HTML‑ресурса. |
| create_resource_url | `CreateResourceUrl` | Метод, который создает URL для HTML‑ресурса. |
| release_page_stream | `ReleasePageStream` | Метод, который освобождает поток, созданный делегатом, переданным в `create_page_stream`. |
| release_resource_stream | `ReleaseResourceStream` | Метод, который освобождает поток, созданный делегатом, переданным в `create_resource_stream`. |

**Returns:** HtmlViewOptions: New instance of the HtmlViewOptions class for rendering into HTML with external resources.

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `release_resource_stream` имеет значение None. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_excel_to_html_external():
    # Загрузить таблицу Excel
    with Viewer("invoice.xlsx") as viewer:
        # Преобразовать таблицу в HTML с внешними ресурсами.
        # {0} и {1} заменяются соответственно текущим номером страницы и именем ресурса.
        view_options = HtmlViewOptions.for_external_resources(
            "render_excel_to_html_external/pdf_page_{0}.html",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}"
        )
        viewer.view(view_options)

if __name__ == "__main__":
    render_excel_to_html_external()
```

## for_external_resources {#page_stream_factory-resource_stream_factory}

Инициализирует экземпляр HtmlViewOptions для рендеринга в HTML с внешними ресурсами.

Для получения более подробной информации см. онлайн‑документацию.

```python
def for_external_resources(cls, page_stream_factory, resource_stream_factory):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Фабрика, реализующая методы создания и освобождения выходного потока страницы. |
| resource_stream_factory | `IResourceStreamFactory` | Фабрика, реализующая методы, необходимые для создания URL ресурсов, создания и освобождения выходных потоков HTML‑ресурсов. |

**Returns:** HtmlViewOptions: A new HtmlViewOptions instance configured for external resources.

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `resource_stream_factory` равно None. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Создайте HTML‑файл для каждой страницы и храните внешние ресурсы отдельно.
    # {0} и {1} заменяются соответственно текущим номером страницы и именем ресурса.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

## for_external_resources

Инициализирует экземпляр HtmlViewOptions, настроенный на генерацию HTML‑файлов с внешними ресурсами.

Экземпляр использует предоставленные строковые форматы:
- `html_file_path_format` – file path format for the output HTML files (e.g., `"page_{0}.html"`).
- `resources_path_format` – folder path format for external resource files (e.g., `"page_{0}/resource_{0}_{1}"`).
- `resources_url_format` – URL format for HTML resources (e.g., `"page_{0}/resource_{0}_{1}"`).

Выходные файлы помещаются в текущий рабочий каталог приложения.

```python
def for_external_resources(cls):
    ...
```

**Returns:** HtmlViewOptions: Configured options for rendering HTML with external resources.

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html_external():
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html_external()
```

## for_external_resources {#file_path_format-resource_file_path_format-resource_url_format}

Инициализирует экземпляр класса [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/).

Для примера кода см. документацию.

```python
def for_external_resources(cls, file_path_format, resource_file_path_format, resource_url_format):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path_format | `str` | Формат пути к файлу, например `'page_{0}.html'`. |
| resource_file_path_format | `str` | Формат пути к файлу ресурса, например `'page_{0}/resource_{1}'`. |
| resource_url_format | `str` | Формат URL ресурса, например `'page_{0}/resource_{1}'`. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `resource_url_format` равно None или пустой. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Загрузите документ и отрендерите каждую страницу в HTML‑файл с внешними ресурсами.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

### См. также
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
