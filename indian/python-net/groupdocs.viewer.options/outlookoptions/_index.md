---
title: "OutlookOptions क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "Outlook डेटा फ़ाइलों को रेंडर करने के विकल्प शामिल हैं।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/outlookoptions/
is_root: false
weight: 130
---


## OutlookOptions class

Outlook डेटा फ़ाइलों को रेंडर करने के विकल्प शामिल हैं।

विवरण के लिए, GroupDocs दस्तावेज़ देखें।

OutlookOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/outlookoptions/__init__/) |  |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [address_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/address_filter/) | प्रेषक या प्राप्तकर्ता द्वारा संदेशों को फ़िल्टर करने के लिए उपयोग किया गया ईमेल-पता। |
| [folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/folder/) | रेंडर करने के लिए फ़ोल्डर का नाम (जैसे Inbox, Sent Item या Deleted Items)। |
| [max_items_in_folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/) | एक फ़ोल्डर से रेंडर किए जा सकने वाले संदेशों या आइटमों की अधिकतम संख्या। |
| [text_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/text_filter/) | यह संदेशों को फ़िल्टर करने के लिए उपयोग किए जाने वाले कीवर्ड हैं। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_outlook():
    with Viewer("sample.pst") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "outlook.html"
        )
        # प्रति फ़ोल्डर रेंडर किए जाने वाले आइटमों की संख्या को सीमित करें।
        view_options.outlook_options.max_items_in_folder = 30
        viewer.view(view_options)
```

### साथ में देखें
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
