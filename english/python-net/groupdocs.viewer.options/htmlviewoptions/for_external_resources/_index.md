---
title: for_external_resources method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes an instance of the HtmlViewOptions class for rendering into HTML with external resources."
type: docs
url: /python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/
is_root: false
weight: 1020
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
| create_page_stream | `CreatePageStream` | Callable that instantiates a stream used to write output page data. |
| create_resource_stream | `CreateResourceStream` | Callable that releases the stream created by `create_page_stream`. |
| create_resource_url | `CreateResourceUrl` | Callable that creates the URL for an HTML resource. |

**Returns:** HtmlViewOptions: New instance of the `HtmlViewOptions` class for rendering into HTML with external resources.

| Raises | Description |
| :- | :- |
| `ValueError` | If `create_page_stream`, `create_resource_stream`, or `create_resource_url` is None. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)
```

## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url-release_page_stream-release_resource_stream}

Initializes an HtmlViewOptions instance for rendering into HTML with external resources.

For a usage example, see the GroupDocs Viewer documentation.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url, release_page_stream, release_resource_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable that instantiates a stream used to write output page data. |
| create_resource_stream | `CreateResourceStream` | Callable that instantiates a stream used to write output HTML resource data. |
| create_resource_url | `CreateResourceUrl` | Callable that creates a URL for an HTML resource. |
| release_page_stream | `ReleasePageStream` | Callable that releases the stream created by the delegate passed to `create_page_stream`. |
| release_resource_stream | `ReleaseResourceStream` | Callable that releases the stream created by the delegate passed to `create_resource_stream`. |

**Returns:** HtmlViewOptions: New instance of the HtmlViewOptions class for rendering into HTML with external resources.

| Raises | Description |
| :- | :- |
| `ValueError` | If `release_resource_stream` is None. |

## for_external_resources {#page_stream_factory-resource_stream_factory}

Initializes an instance of [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) for rendering into HTML with external resources.

For more details, see the online documentation: https://docs.groupdocs.com/viewer/python-net/rendering-to-html/#rendering-to-html-with-external-resources

```python
def for_external_resources(cls, page_stream_factory, resource_stream_factory):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | The factory that implements methods for creating and releasing output page streams. |
| resource_stream_factory | `IResourceStreamFactory` | The factory that implements methods required for creating resource URLs, instantiating, and releasing output HTML resource streams. |

**Returns:** HtmlViewOptions: A new instance of `HtmlViewOptions` configured for external resources.

| Raises | Description |
| :- | :- |
| `ValueError` | If `resource_stream_factory` is None. |

## for_external_resources

Initializes an instance of the HtmlViewOptions class.

This constructor initializes an instance of the HtmlViewOptions class with `"p_{0}.html"` as file path format for the output HTML files, `"p_{0}_{1}"` as file path format for the output HTML‑resource files, and `"p_{0}_{1}"` as URL format for HTML resources. The output files will be placed into the current working directory of the application.

For a code example, see the documentation.

```python
def for_external_resources(cls):
    ...
```

## for_external_resources {#file_path_format-resource_file_path_format-resource_url_format}

Initializes an instance of the HtmlViewOptions class.

For the code example, see the documentation.

```python
def for_external_resources(cls, file_path_format, resource_file_path_format, resource_url_format):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path_format | `str` | The file path format e.g. 'page_{0}.html'. |
| resource_file_path_format | `str` | The resource file path format e.g. 'page_{0}/resource_{1}'. |
| resource_url_format | `str` | The resource URL format e.g. 'page_{0}/resource_{1}'. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `resource_url_format` is None or empty. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Create an HTML file for each page and store external resources separately.
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

### Aliases

These names call `for_external_resources` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `for_external_resources_create_page_stream` | `for_external_resources_create_page_stream(create_page_stream, create_resource_stream, create_resource_url, release_page_stream, release_resource_stream)`<br>`for_external_resources_create_page_stream(create_page_stream, create_resource_stream, create_resource_url)` |
| `for_external_resources_file` | `for_external_resources_file(file_path_format, resource_file_path_format, resource_url_format)` |
| `for_external_resources_string` | `for_external_resources_string(file_path_format, resource_file_path_format, resource_url_format)` |
| `for_external_resources_ipage_stream_factory` | `for_external_resources_ipage_stream_factory(page_stream_factory, resource_stream_factory)` |

### See Also
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
