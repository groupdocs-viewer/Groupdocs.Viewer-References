---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक नया PngViewOptions इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/pngviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

एक नया [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) उदाहरण प्रारंभ करता है।

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

एक [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) क्लास का एक उदाहरण प्रारंभ करता है।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | The method that instantiates a stream used to write output page data. |
| release_page_stream | `ReleasePageStream` | `create_page_stream` पैरामीटर को पास किए गए डेलीगेट को सौंपे गए मेथड द्वारा निर्मित स्ट्रीम को रिलीज़ करने वाला मेथड। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `release_page_stream` None हो। |

## __init__ {#page_stream_factory}

एक नया [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) उदाहरण प्रारंभ करता है।

अधिक जानकारी के लिए, दस्तावेज़ देखें।

```python
def __init__(self, page_stream_factory):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | The factory which implements methods for creating and releasing output page stream. |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `page_stream_factory` `None` है। |

## __init__

एक PngViewOptions उदाहरण प्रारंभ करता है।

यह कंस्ट्रक्टर एक [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) बनाता है जिसमें आउटपुट फ़ाइलों के लिए डिफ़ॉल्ट फ़ाइल पाथ फ़ॉर्मेट ``\"p_{0}.png\"`` है। उत्पन्न PNG फ़ाइलें एप्लिकेशन की वर्तमान कार्य निर्देशिका में सहेजी जाती हैं।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

## __init__ {#file_path_format}

एक नया [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) उदाहरण प्रारंभ करता है।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

```python
def __init__(self, file_path_format):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_path_format | `str` | फ़ाइल पाथ फ़ॉर्मेट, उदाहरण के लिए `'page_{0}.png'`। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | When `file_path_format` is None or empty. |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

### साथ में देखें
* class [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
