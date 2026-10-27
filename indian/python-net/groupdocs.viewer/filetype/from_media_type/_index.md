---
title: "from_media_type मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "फ़ाइल मीडिया टाइप को एक FileType से मैप करता है (उदाहरण के लिए, 'application/pdf' को FileType.pdf से मैप किया जाता है)।"
type: docs
url: /hi/python-net/groupdocs.viewer/filetype/from_media_type/
is_root: false
weight: 1110
---


## from_media_type {#media_type}

फ़ाइल मीडिया प्रकार को एक [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) से मैप करता है (उदाहरण के लिए, 'application/pdf' को [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/) से मैप किया जाता है)।

```python
def from_media_type(cls, media_type):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| media_type | `str` | फ़ाइल मीडिया टाइप, उदाहरण के लिए, ``application/pdf``। |

**Returns:** FileType: Corresponding file type when found; otherwise returns the default `FileType.unknown`.

### साथ में देखें
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
