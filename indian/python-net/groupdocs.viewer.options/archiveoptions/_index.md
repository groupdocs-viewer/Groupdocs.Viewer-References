---
title: "ArchiveOptions क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "आर्काइव फ़ाइलों को रेंडर करने के विकल्प शामिल करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/archiveoptions/
is_root: false
weight: 10
---


## ArchiveOptions class

आर्काइव फ़ाइलों को रेंडर करने के विकल्प शामिल करता है।

ArchiveOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/archiveoptions/__init__/) | [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/) क्लास का एक इंस्टेंस प्रारंभ करता है। |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.options/archiveoptions/file_name/) | दिखाया गया अभिलेख फ़ाइल नाम। |
| [folder](/viewer/python-net/groupdocs.viewer.options/archiveoptions/folder/) | रेंडर करने के लिए फ़ोल्डर। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "render_specific_archive_folder/specific_archive_folder.html"
    )
    view_options.archive_options.folder = "first_folder"
    viewer.view(view_options)
```

### साथ में देखें
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
