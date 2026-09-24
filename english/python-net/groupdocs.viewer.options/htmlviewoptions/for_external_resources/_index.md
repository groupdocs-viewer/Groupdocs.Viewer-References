---
title: for_external_resources method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes an instance of the HtmlViewOptions class for rendering into HTML with external resources."
type: docs
url: /python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/
is_root: false
weight: 1060
---


## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url}

Initializes an instance of the [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) class for rendering into HTML with external resources.

For the code example, see the documentation.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | The method that instantiates stream used to write output page data. |
| create_resource_stream | `CreateResourceStream` | The method that releases stream created by `create_page_stream` method. |
| create_resource_url | `CreateResourceUrl` | The method that creates URL for HTML resource. |

**Returns:** New instance of the `HtmlViewOptions` class for rendering into HTML with external resources.

| Raises | Description |
| :- | :- |
| `ValueError` | When `create_resource_url` is None. |

### Example

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

Initializes an instance of the HtmlViewOptions class for rendering into HTML with external resources.

For additional usage examples, see the GroupDocs Viewer documentation.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url, release_page_stream, release_resource_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | The method that instantiates a stream used to write output page data. |
| create_resource_stream | `CreateResourceStream` | The method that instantiates a stream used to write output HTML resource data. |
| create_resource_url | `CreateResourceUrl` | The method that creates a URL for an HTML resource. |
| release_page_stream | `ReleasePageStream` | The method that releases the stream created by the delegate passed to `create_page_stream`. |
| release_resource_stream | `ReleaseResourceStream` | The method that releases the stream created by the delegate passed to `create_resource_stream`. |

**Returns:** HtmlViewOptions: New instance of the HtmlViewOptions class for rendering into HTML with external resources.

| Raises | Description |
| :- | :- |
| `ValueError` | When `release_resource_stream` is None. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_excel_to_html_external():
    # Load Excel spreadsheet
    with Viewer("invoice.xlsx") as viewer:
        # Convert the spreadsheet to HTML with external resources.
        # {0} and {1} are replaced with the current page number and resource name, respectively.
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

Initializes an HtmlViewOptions instance for rendering into HTML with external resources.

For more details, see the online documentation.

```python
def for_external_resources(cls, page_stream_factory, resource_stream_factory):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | The factory that implements methods for creating and releasing the output page stream. |
| resource_stream_factory | `IResourceStreamFactory` | The factory that implements methods required for creating resource URLs, instantiating, and releasing output HTML resource streams. |

**Returns:** HtmlViewOptions: A new HtmlViewOptions instance configured for external resources.

| Raises | Description |
| :- | :- |
| `ValueError` | If `resource_stream_factory` is None. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Create an HTML file for each page and store external resources separately.
    # {0} and {1} are replaced with the current page number and resource name, respectively.
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

Initializes an HtmlViewOptions instance configured to generate HTML files with external resources.

The instance uses the provided format strings:
- `html_file_path_format` – file path format for the output HTML files (e.g., `"page_{0}.html"`).
- `resources_path_format` – folder path format for external resource files (e.g., `"page_{0}/resource_{0}_{1}"`).
- `resources_url_format` – URL format for HTML resources (e.g., `"page_{0}/resource_{0}_{1}"`).

The output files are placed in the current working directory of the application.

```python
def for_external_resources(cls):
    ...
```

**Returns:** HtmlViewOptions: Configured options for rendering HTML with external resources.

### Example

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

Initializes an instance of the [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) class.

For the code example, see the documentation.

```python
def for_external_resources(cls, file_path_format, resource_file_path_format, resource_url_format):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path_format | `str` | The file path format, e.g. `'page_{0}.html'`. |
| resource_file_path_format | `str` | The resource file path format, e.g. `'page_{0}/resource_{1}'`. |
| resource_url_format | `str` | The resource URL format, e.g. `'page_{0}/resource_{1}'`. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `resource_url_format` is None or empty. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Load a document and render each page to an HTML file with external resources.
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

### See Also
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
