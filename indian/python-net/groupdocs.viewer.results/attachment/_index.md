---
title: "Attachment क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "ईमेल संदेश, आर्काइव, PDF दस्तावेज़, या Outlook डेटा फ़ाइल में सम्मिलित अटैचमेंट फ़ाइल का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.results/attachment/
is_root: false
weight: 20
---


## Attachment class

ईमेल संदेश, आर्काइव, PDF दस्तावेज़, या Outlook डेटा फ़ाइल में सम्मिलित अटैचमेंट फ़ाइल का प्रतिनिधित्व करता है।

Attachment प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/) | एक नया [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/) उदाहरण प्रारंभ करता है। |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#file_name-file_path) | एक नया Attachment उदाहरण प्रारंभ करता है। |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-size) | Attachment क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-file_type-size) | Attachment क्लास का एक नया उदाहरण प्रारंभ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/attachment/to_string/) | एक स्ट्रिंग लौटाता है जो वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करती है। |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.results/attachment/file_name/) | संलग्न फ़ाइल का नाम। |
| [file_path](/viewer/python-net/groupdocs.viewer.results/attachment/file_path/) | संलग्न फ़ाइल का सापेक्ष पथ, उदाहरण के लिए `folder/file.docx`, या फ़ाइलनाम जब फ़ाइल एक संग्रह की जड़ में, ई‑मेल संदेश में, या डेटा फ़ाइल में स्थित हो। |
| [file_type](/viewer/python-net/groupdocs.viewer.results/attachment/file_type/) | संलग्न फ़ाइल प्रकार। |
| [id](/viewer/python-net/groupdocs.viewer.results/attachment/id/) | एकल फ़ाइल के संदर्भ में जिसमें यह संलग्न है, उसका अद्वितीय पहचानकर्ता। |
| [size](/viewer/python-net/groupdocs.viewer.results/attachment/size/) | संलग्न फ़ाइल का आकार बाइट्स में। |

### उदाहरण

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # संलग्नक गुणों तक पहुँचें, उदाहरण के लिए, फ़ाइल नाम
        print(attachment.file_name)
        # संलग्नक को फ़ाइल पथ पर सहेजें
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### साथ में देखें
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
