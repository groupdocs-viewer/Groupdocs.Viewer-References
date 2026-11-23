---
title: "render_layouts प्रॉपर्टी"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "यह फ़्लैग दर्शाता है कि CAD दस्तावेज़ से लेआउट्स रेंडर किए जाने चाहिए या नहीं।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/cadoptions/render_layouts/
is_root: false
weight: 2070
---


## render_layouts property

यह फ़्लैग दर्शाता है कि CAD दस्तावेज़ से लेआउट्स रेंडर किए जाने चाहिए या नहीं।

यह विकल्प केवल उन CAD ड्रॉइंग्स के लिए उपलब्ध है जो लेआउट्स का समर्थन करती हैं [`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/), [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/), [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/), [`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/), और [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/). डिफ़ॉल्ट रूप से केवल मॉडल रेंडर किया जाता है।

### Definition:
```python
@property
def render_layouts(self):
    ...
@render_layouts.setter
def render_layouts(self, value):
    ...
```

### साथ में देखें
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
