---
title: "PdfViewInfo क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "PDF दस्तावेज़ के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.results/pdfviewinfo/
is_root: false
weight: 140
---


## PdfViewInfo class

PDF दस्तावेज़ के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।

PdfViewInfo प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/) | PdfViewInfo का नया उदाहरण प्रारंभ करता है। |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/#file_type-pages-printing_allowed) | PdfViewInfo का नया उदाहरण प्रारंभ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | एक स्ट्रिंग लौटाता है जो वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करती है। ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) से विरासत में मिली) |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [printing_allowed](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/printing_allowed/) | printing_allowed प्रॉपर्टी दर्शाती है कि दस्तावेज़ की प्रिंटिंग की अनुमति है या नहीं। |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | फ़ाइल का प्रकार। ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) से विरासत में मिला) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | देखने के लिए पृष्ठों की सूची। ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) से विरासत में मिली) |

### उदाहरण

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import PdfViewInfo

def get_pdf_info():
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        pdf_info = cast(PdfViewInfo, info)

        print("File type:", pdf_info.file_type)
        print("Pages count:", len(pdf_info.pages))
        print("Printing allowed:", pdf_info.printing_allowed)

if __name__ == "__main__":
    get_pdf_info()
```

### Guides
`PdfViewInfo` का उपयोग करने वाले कार्य गाइड:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### साथ में देखें
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
