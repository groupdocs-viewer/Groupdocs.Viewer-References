---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "PdfViewOptions का एक इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_file_stream}

[`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) का एक उदाहरण प्रारंभ करता है।

कोड उदाहरण के लिए, https://docs.groupdocs.com/viewer/net/rendering-to-pdf/ पर दस्तावेज़ देखें।

```python
def __init__(self, create_file_stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | वह मेथड जो आउटपुट फ़ाइल डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करता है। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `create_file_stream` `None` है। |

## __init__ {#create_file_stream-release_file_stream}

एक नया PdfViewOptions उदाहरण प्रारंभ करता है।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

```python
def __init__(self, create_file_stream, release_file_stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | `io.RawIOBase` स्ट्रीम लौटाने वाला कॉलेबल, जो आउटपुट फ़ाइल डेटा लिखने के लिए उपयोग होता है। |
| release_file_stream | `ReleaseFileStream` | `create_file_stream` को असाइन किए गए मेथड द्वारा निर्मित स्ट्रीम को रिलीज़ करने वाला कॉलेबल। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `release_file_stream` `None` है। |

## __init__ {#file_stream_factory}

एक PdfViewOptions उदाहरण प्रारंभ करता है।

कोड उदाहरण के लिए, दस्तावेज़ देखें: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

```python
def __init__(self, file_stream_factory):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_stream_factory | `IFileStreamFactory` | फ़ैक्टरी जो आउटपुट फ़ाइल स्ट्रीम बनाने और रिलीज़ करने के लिए मेथड्स को लागू करती है। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `file_stream_factory` `None` हो तो उत्पन्न होता है। |

## __init__

एक PdfViewOptions उदाहरण प्रारंभ करता है।

यह कंस्ट्रक्टर PdfViewOptions को `\"output.pdf\"` को आउटपुट फ़ाइल के फ़ाइल पथ स्वरूप के रूप में प्रारंभ करता है। आउटपुट फ़ाइल एप्लिकेशन की वर्तमान कार्य निर्देशिका में रखी जाएगी।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

## __init__ {#output_file_path}

एक [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) क्लास का उदाहरण प्रारंभ करता है।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

```python
def __init__(self, output_file_path):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| output_file_path | `str` | आउटपुट PDF फ़ाइल का पथ। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | `output_file_path` जब None या खाली हो। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### साथ में देखें
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
