---
title: "create_resource_stream मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "आउटपुट HTML रिसोर्स डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम बनाता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/
is_root: false
weight: 1010
---


## create_resource_stream {#page_number-resource}

आउटपुट HTML रिसोर्स डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम बनाता है।

```python
def create_resource_stream(self, page_number, resource):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| page_number | `int` | एक पृष्ठ की संख्या। |
| resource | `Resource` | फ़ॉन्ट, स्टाइल, इमेज या ग्राफ़िक्स जैसी HTML रिसोर्स। |

**Returns:** io.RawIOBase: Stream used to write output resource data.

### उदाहरण

```python
from groupdocs.viewer import Viewer

viewer = Viewer()
factory = viewer.resource_stream_factory

# पृष्ठ 1 पर CSS संसाधन के लिए एक स्ट्रीम बनाएं
stream = factory.create_resource_stream(pageNumber=1, resource="style.css")
with stream:
    stream.write(b"body { font-family: Arial; }")
```

### साथ में देखें
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
