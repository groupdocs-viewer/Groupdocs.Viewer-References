---
title: "for_external_resources मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "बाहरी संसाधनों के साथ HTML में रेंडर करने के लिए HtmlViewOptions क्लास का एक इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/
is_root: false
weight: 1060
---


## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url}

बाहरी संसाधनों के साथ HTML में रेंडर करने के लिए [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) क्लास का एक इंस्टेंस प्रारंभ करता है।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | वह मेथड जो आउटपुट पेज डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंशिएट करता है। |
| create_resource_stream | `CreateResourceStream` | वह मेथड जो `create_page_stream` मेथड द्वारा बनाई गई स्ट्रीम को रिलीज़ करता है। |
| create_resource_url | `CreateResourceUrl` | वह मेथड जो HTML रिसोर्स के लिए URL बनाता है। |

**Returns:** New instance of the `HtmlViewOptions` class for rendering into HTML with external resources.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `create_resource_url` None हो। |

### उदाहरण

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

बाहरी संसाधनों के साथ HTML में रेंडर करने के लिए HtmlViewOptions क्लास का एक इंस्टेंस प्रारंभ करता है।

अधिक उपयोग उदाहरणों के लिए, GroupDocs Viewer दस्तावेज़ देखें।

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url, release_page_stream, release_resource_stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | The method that instantiates a stream used to write output page data. |
| create_resource_stream | `CreateResourceStream` | वह मेथड जो आउटपुट HTML रिसोर्स डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम को इंस्टैंशिएट करता है। |
| create_resource_url | `CreateResourceUrl` | वह मेथड जो HTML रिसोर्स के लिए URL बनाता है। |
| release_page_stream | `ReleasePageStream` | वह मेथड जो `create_page_stream` को पास किए गए डेलीगेट द्वारा बनाई गई स्ट्रीम को रिलीज़ करता है। |
| release_resource_stream | `ReleaseResourceStream` | वह मेथड जो `create_resource_stream` को पास किए गए डेलीगेट द्वारा बनाई गई स्ट्रीम को रिलीज़ करता है। |

**Returns:** HtmlViewOptions: New instance of the HtmlViewOptions class for rendering into HTML with external resources.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `release_resource_stream` None हो। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_excel_to_html_external():
    # Excel स्प्रेडशीट लोड करें
    with Viewer("invoice.xlsx") as viewer:
        # स्प्रेडशीट को बाहरी रिसोर्सेज़ के साथ HTML में कनवर्ट करें।
        # {0} और {1} क्रमशः वर्तमान पेज नंबर और रिसोर्स नाम से बदल दिए जाते हैं।
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

बाहरी संसाधनों के साथ HTML में रेंडर करने के लिए एक HtmlViewOptions इंस्टेंस को प्रारंभ करता है।

अधिक विवरण के लिए, ऑनलाइन दस्तावेज़ देखें।

```python
def for_external_resources(cls, page_stream_factory, resource_stream_factory):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | फ़ैक्टरी जो आउटपुट पेज स्ट्रीम को बनाने और रिलीज़ करने के मेथड्स को इम्प्लीमेंट करती है। |
| resource_stream_factory | `IResourceStreamFactory` | फ़ैक्टरी जो रिसोर्स URL बनाने, इंस्टैंशिएट करने और आउटपुट HTML रिसोर्स स्ट्रीम्स को रिलीज़ करने के लिए आवश्यक मेथड्स को इम्प्लीमेंट करती है। |

**Returns:** HtmlViewOptions: A new HtmlViewOptions instance configured for external resources.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `resource_stream_factory` None है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # प्रत्येक पृष्ठ के लिए एक HTML फ़ाइल बनाएं और बाहरी संसाधनों को अलग से संग्रहीत करें।
    # {0} और {1} क्रमशः वर्तमान पेज नंबर और रिसोर्स नाम से बदल दिए जाते हैं।
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

बाहरी संसाधनों के साथ HTML फ़ाइलें उत्पन्न करने के लिए कॉन्फ़िगर किया गया एक HtmlViewOptions इंस्टेंस को प्रारंभ करता है।

इंस्टेंस प्रदान किए गए फ़ॉर्मेट स्ट्रिंग्स का उपयोग करता है:
- `html_file_path_format` – file path format for the output HTML files (e.g., `"page_{0}.html"`).
- `resources_path_format` – folder path format for external resource files (e.g., `"page_{0}/resource_{0}_{1}"`).
- `resources_url_format` – URL format for HTML resources (e.g., `"page_{0}/resource_{0}_{1}"`).

आउटपुट फ़ाइलें एप्लिकेशन की वर्तमान कार्य निर्देशिका में रखी जाती हैं।

```python
def for_external_resources(cls):
    ...
```

**Returns:** HtmlViewOptions: Configured options for rendering HTML with external resources.

### उदाहरण

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

[`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) क्लास का एक इंस्टेंस प्रारंभ करता है।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

```python
def for_external_resources(cls, file_path_format, resource_file_path_format, resource_url_format):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_path_format | `str` | फ़ाइल पथ फ़ॉर्मेट, उदाहरण के लिए `'page_{0}.html'`। |
| resource_file_path_format | `str` | संसाधन फ़ाइल पथ फ़ॉर्मेट, उदाहरण के लिए `'page_{0}/resource_{1}'`। |
| resource_url_format | `str` | संसाधन URL फ़ॉर्मेट, उदाहरण के लिए `'page_{0}/resource_{1}'`। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `resource_url_format` None या खाली है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # एक दस्तावेज़ लोड करें और प्रत्येक पृष्ठ को बाहरी संसाधनों के साथ HTML फ़ाइल में रेंडर करें।
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

### साथ में देखें
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
