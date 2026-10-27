---
title: "LoadOptions क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "फ़ाइल खोलने के लिए उपयोग किए जाने वाले विकल्प।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/loadoptions/
is_root: false
weight: 110
---


## LoadOptions class

फ़ाइल खोलने के लिए उपयोग किए जाने वाले विकल्प।

LoadOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/) | [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/) क्लास का एक उदाहरण प्रारंभ करता है। |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/#file_type) | एक नया LoadOptions उदाहरण प्रारंभ करता है। |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/) | यह प्रॉपर्टी [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), और [`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/) फ़ाइलों के लिए एन्कोडिंग डिटेक्शन सक्षम करती है। |
| [encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/) | टेक्स्ट-आधारित फ़ाइलों या ईमेल संदेशों को खोलते समय उपयोग की जाने वाली एन्कोडिंग, जैसे कि [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), और [`FileType.msg`](/viewer/python-net/groupdocs.viewer/filetype/msg/). डिफ़ॉल्ट मान `utf-8` है। |
| [file_type](/viewer/python-net/groupdocs.viewer.options/loadoptions/file_type/) | खोलने वाली फ़ाइल का प्रकार। |
| [password](/viewer/python-net/groupdocs.viewer.options/loadoptions/password/) | एन्क्रिप्टेड फ़ाइल खोलने के लिए पासवर्ड। |
| [resource_loading_timeout](/viewer/python-net/groupdocs.viewer.options/loadoptions/resource_loading_timeout/) | बाहरी संसाधनों को लोड करने का टाइमआउट। |
| [skip_external_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) | यह प्रॉपर्टी छवियों जैसी सभी बाहरी संसाधनों के लोडिंग को निष्क्रिय करती है, सिवाय उन संसाधनों के जो [`LoadOptions.whitelisted_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) में सूचीबद्ध हैं। |
| [try_repair](/viewer/python-net/groupdocs.viewer.options/loadoptions/try_repair/) | यह प्रॉपर्टी GroupDocs.Viewer को PDF दस्तावेज़ों में संरचनात्मक भ्रष्टाचार की मरम्मत का प्रयास करने में सक्षम बनाती है। डिफ़ॉल्ट रूप से False है। |
| [whitelisted_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) | जब [`LoadOptions.skip_external_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) को `True` पर सेट किया जाता है, तो लोड किए जाने वाले बाहरी संसाधनों से संबंधित URL फ्रैगमेंट की सूची। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, LoadOptions

load_options = LoadOptions()
load_options.password = "12345"

with Viewer("protected.docx", load_options) as viewer:
    viewer.view(HtmlViewOptions.for_embedded_resources("page_{0}.html"))
```

### साथ में देखें
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
