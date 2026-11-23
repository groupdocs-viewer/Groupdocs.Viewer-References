---
title: "release_resource_stream मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "IResourceStreamFactory.createresourcestream मेथड द्वारा निर्मित स्ट्रीम को रिलीज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/release_resource_stream/
is_root: false
weight: 1050
---


## release_resource_stream {#page_number-resource-resource_stream}

[`IResourceStreamFactory.create_resource_stream`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/) मेथड द्वारा बनाई गई स्ट्रीम को रिलीज़ करता है।

```python
def release_resource_stream(self, page_number, resource, resource_stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| page_number | `int` | एक पृष्ठ की संख्या। |
| resource | `Resource` | फ़ॉन्ट, स्टाइल, इमेज या ग्राफ़िक्स जैसी HTML रिसोर्स। |
| resource_stream | `io.RawIOBase` | `IResourceStreamFactory.create_resource_stream` मेथड द्वारा निर्मित स्ट्रीम। |

**Returns:** None.

### साथ में देखें
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
