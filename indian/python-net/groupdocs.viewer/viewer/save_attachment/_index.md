---
title: "save_attachment मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "अटैचमेंट फ़ाइल को गंतव्य स्ट्रीम में सहेजता है।"
type: docs
url: /hi/python-net/groupdocs.viewer/viewer/save_attachment/
is_root: false
weight: 1070
---


## save_attachment {#attachment-destination}

`destination` स्ट्रीम में अटैचमेंट फ़ाइल सहेजता है।

- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def save_attachment(self, attachment, destination):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| attachment | `Attachment` | संलग्नक। |
| destination | `io.RawIOBase` | लेखनीय स्ट्रीम। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `destination` None है। |
| `PasswordRequiredException` | जब दस्तावेज़ खोलने के लिए पासवर्ड आवश्यक होता है। |
| `IncorrectPasswordException` | जब निर्दिष्ट पासवर्ड गलत होता है। |
| `GroupDocsViewerException` | जब संलग्नक नहीं मिला। |

### उदाहरण

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### साथ में देखें
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
