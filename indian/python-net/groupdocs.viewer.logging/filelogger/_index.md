---
title: "FileLogger क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "लॉग संदेशों को फ़ाइल में लिखता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.logging/filelogger/
is_root: false
weight: 20
---


## FileLogger class

लॉग संदेशों को फ़ाइल में लिखता है।

FileLogger प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.logging/filelogger/__init__/#file_name) | एक लॉगर को आरंभ करता है जो फ़ाइल में संदेश लिखता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [error](/viewer/python-net/groupdocs.viewer.logging/filelogger/error/#message-exception) | कंसोल में एक त्रुटि संदेश लिखता है। त्रुटि लॉग संदेश एप्लिकेशन प्रवाह में अपरिवर्तनीय घटनाओं की जानकारी प्रदान करते हैं। |
| [error_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_file/) |  |
| [error_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_string/) |  |
| [trace](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace/#message) | लॉग में एक ट्रेस संदेश लिखता है। ट्रेस लॉग संदेश एप्लिकेशन प्रवाह के बारे में सामान्यतः उपयोगी जानकारी प्रदान करते हैं। |
| [trace_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_file/) |  |
| [trace_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_string/) |  |
| [warning](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning/#message) | कंसोल में एक चेतावनी संदेश लिखता है। |
| [warning_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_file/) |  |
| [warning_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_string/) |  |

### उदाहरण

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import FileLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=FileLogger("./log.txt"))
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "write_logs_to_file/page_{0}.html"
    )
    viewer.view(html_options)
```

### साथ में देखें
* module [`groupdocs.viewer.logging`](/viewer/python-net/groupdocs.viewer.logging/)
