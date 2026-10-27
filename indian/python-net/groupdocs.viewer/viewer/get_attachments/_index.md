---
title: "get_attachments मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "दस्तावेज़ में शामिल अटैचमेंट्स लौटाता है।"
type: docs
url: /hi/python-net/groupdocs.viewer/viewer/get_attachments/
is_root: false
weight: 1030
---


## get_attachments

दस्तावेज़ में शामिल अटैचमेंट्स लौटाता है।

और अधिक जानें:
- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def get_attachments(self):
    ...
```

**Returns:** Attachments contained by the document.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `PasswordRequiredException` | जब दस्तावेज़ खोलने के लिए पासवर्ड आवश्यक हो तो फेंका जाता है। |
| `IncorrectPasswordException` | जब निर्दिष्ट पासवर्ड गलत हो तो फेंका जाता है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # प्रत्येक संलग्नक को फ़ाइल में सहेजें
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### साथ में देखें
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
