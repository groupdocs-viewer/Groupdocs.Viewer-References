---
title: "view मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "सभी दस्तावेज़ पृष्ठों का व्यू बनाता है।"
type: docs
url: /hi/python-net/groupdocs.viewer/viewer/view/
is_root: false
weight: 1130
---


## view {#options}

सभी दस्तावेज़ पृष्ठों का व्यू बनाता है।

और अधिक जानें

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| options | `ViewOptions` | व्यू विकल्प। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `options` None है। |
| `PasswordRequiredException` | जब दस्तावेज़ खोलने के लिए पासवर्ड आवश्यक होता है। |
| `IncorrectPasswordException` | जब निर्दिष्ट पासवर्ड गलत होता है। |
| `GroupDocsViewerException` | जब संलग्नक नहीं मिला। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-page_numbers}

विशिष्ट दस्तावेज़ पृष्ठों का व्यू बनाता है।

और अधिक जानें

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, page_numbers):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| options | `ViewOptions` | व्यू विकल्प। |
| page_numbers | `list[int]` | देखने के लिए पृष्ठ संख्याएँ। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `page_numbers` खाली है। |
| `PasswordRequiredException` | जब दस्तावेज़ खोलने के लिए पासवर्ड आवश्यक हो। |
| `IncorrectPasswordException` | जब निर्दिष्ट पासवर्ड गलत हो। |
| `GroupDocsViewerException` | जब संलग्नक नहीं मिला। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-cancellation_token-page_numbers}

विशिष्ट दस्तावेज़ पृष्ठों का व्यू बनाता है।

और अधिक जानें:

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, cancellation_token, page_numbers):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| options | `ViewOptions` | व्यू विकल्प। |
| cancellation_token | `CancellationToken` | प्रसंस्करण रद्द करने के लिए रद्दीकरण टोकन। |
| page_numbers | `list[int]` | देखने के लिए पृष्ठ संख्याएँ। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `page_numbers` खाली हो। |
| `PasswordRequiredException` | जब दस्तावेज़ खोलने के लिए पासवर्ड आवश्यक हो। |
| `IncorrectPasswordException` | जब निर्दिष्ट पासवर्ड गलत होता है। |
| `GroupDocsViewerException` | जब संलग्नक नहीं मिला। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### साथ में देखें
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
