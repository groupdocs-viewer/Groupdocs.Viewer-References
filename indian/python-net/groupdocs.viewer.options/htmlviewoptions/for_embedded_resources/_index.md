---
title: "for_embedded_resources method"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "HTML को एम्बेडेड संसाधनों के साथ रेंडर करने के लिए एक HtmlViewOptions इंस्टेंस को प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/
is_root: false
weight: 1010
---


## for_embedded_resources {#create_page_stream}

HTML को एम्बेडेड संसाधनों के साथ रेंडर करने के लिए एक HtmlViewOptions इंस्टेंस को प्रारंभ करता है।

For more details, see the documentation.

```python
def for_embedded_resources(cls, create_page_stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | The method that instantiates a stream used to write output page data. |

**Returns:** HtmlViewOptions: New instance configured for rendering HTML with embedded resources.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | If `create_page_stream` is None. |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#create_page_stream-release_page_stream}

एंबेडेड संसाधनों के साथ HTML में रेंडर करने के लिए [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) क्लास का एक इंस्टेंस प्रारंभ करता है।

```python
def for_embedded_resources(cls, create_page_stream, release_page_stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | The method that instantiates the stream used to write output page data. |
| release_page_stream | `ReleasePageStream` | The method that releases the stream created by the method assigned to the `create_page_stream` parameter. |

**Returns:** HtmlViewOptions: New instance of the `HtmlViewOptions` class for rendering into HTML with embedded resources.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | If `release_page_stream` is `None`. For the code example, see the documentation. |

## for_embedded_resources {#page_stream_factory}

एंबेडेड संसाधनों के साथ HTML में रेंडर करने के लिए एक HtmlViewOptions इंस्टेंस को प्रारंभ करता है।

For the code example, see the documentation at https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources.

```python
def for_embedded_resources(cls, page_stream_factory):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | The factory which implements methods for creating and releasing output page stream. |

**Returns:** HtmlViewOptions: New instance of HtmlViewOptions for rendering into HTML with embedded resources.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | When page_stream_factory is None. |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources

एंबेडेड संसाधनों के साथ [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) क्लास का एक इंस्टेंस प्रारंभ करता है।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

```python
def for_embedded_resources(cls):
    ...
```

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#file_path_format}

एंबेडेड संसाधनों के लिए एक HtmlViewOptions इंस्टेंस को प्रारंभ करता है।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

```python
def for_embedded_resources(cls, file_path_format):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_path_format | `str` | The file path format e.g. 'page_{0}.html'. |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | When `file_path_format` is None or empty. |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### साथ में देखें
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
