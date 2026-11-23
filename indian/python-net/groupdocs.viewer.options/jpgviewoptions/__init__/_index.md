---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "JpgViewOptions क्लास का एक उदाहरण प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/jpgviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

JpgViewOptions क्लास का एक उदाहरण प्रारंभ करता है।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

```python
def __init__(self, create_page_stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | The method that instantiates a stream used to write output page data. |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `create_page_stream` None हो। |

## __init__ {#create_page_stream-release_page_stream}

JpgViewOptions क्लास का एक उदाहरण प्रारंभ करता है।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | एक कॉलेबल जो आउटपुट पेज डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करता है। |
| release_page_stream | `ReleasePageStream` | एक कॉलेबल जो `create_page_stream` को पास किए गए डेलीगेट को असाइन किए गए मेथड द्वारा निर्मित स्ट्रीम को रिलीज़ करता है। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | `release_page_stream` None है। |

## __init__ {#page_stream_factory}

[`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) क्लास का एक उदाहरण प्रारंभ करता है।

कोड उदाहरण के लिए, https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg पर दस्तावेज़ देखें।

```python
def __init__(self, page_stream_factory):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | The factory which implements methods for creating and releasing output page stream. |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | `page_stream_factory` None है। |

## __init__

JpgViewOptions का एक उदाहरण प्रारंभ करता है।

यह कंस्ट्रक्टर [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) का एक उदाहरण प्रारंभ करता है, जिसमें आउटपुट फ़ाइलों के लिए फ़ाइल पाथ फ़ॉर्मेट `"p_{0}.jpg"` है। आउटपुट फ़ाइलें एप्लिकेशन की वर्तमान कार्य निर्देशिका में रखी जाती हैं।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = JpgViewOptions("render_excel_to_jpg/excel_to_jpg_{0}.jpg")
    view_options.width = 800
    view_options.height = 900
    viewer.view(view_options)
```

## __init__ {#file_path_format}

एक नया उदाहरण प्रारंभ करता है [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/).

कोड उदाहरण के लिए, दस्तावेज़ देखें।

```python
def __init__(self, file_path_format):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_path_format | `str` | फ़ाइल पाथ फ़ॉर्मेट, उदाहरण के लिए `'page_{0}.jpg'`। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | `file_path_format` None या खाली है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

def render_to_jpg():
    # एक दस्तावेज़ लोड करें (उदाहरण के लिए, एक Excel फ़ाइल)
    with Viewer("invoice.xlsx") as viewer:
        # फ़ाइल नाम पैटर्न के साथ JPEG व्यू विकल्प बनाएं।
        view_options = JpgViewOptions("output/excel_page_{0}.jpg")
        view_options.width = 800
        view_options.height = 900
        viewer.view(view_options)

if __name__ == "__main__":
    render_to_jpg()
```

### साथ में देखें
* class [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)
